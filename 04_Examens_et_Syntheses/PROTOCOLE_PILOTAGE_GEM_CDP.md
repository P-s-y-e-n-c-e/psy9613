# 🧭 Protocole Opérationnel Permanent : Pilotage du Gem DeepThink & Ingestion NotebookLM

> [!IMPORTANT]
> **Ce document consigne la procédure officielle et testée pour piloter l'Auditeur Doctoral (Gemini Pro 3.1 DeepThink) via le Chrome Debug Protocol (CDP port 9223) et administrer le carnet de sources NotebookLM sans ouvrir de navigateur autonome.**

---

## 1. Architecture & Prérequis Matériels

- **Profil Chrome dédié et authentifié :**
  `C:\Users\Michel\AppData\Local\Google\Chrome\AntigravityBrowser` (contient les sessions actives Moodle UQAM et Google AI Ultra / Gemini).
- **Raccourci officiel sur le Bureau :**
  `C:\Users\Michel\Desktop\Chrome Debug.lnk`
  Cible : `"C:\Program Files\Google\Chrome\Application\chrome.exe" --remote-debugging-port=9223 --user-data-dir="C:\Users\Michel\AppData\Local\Google\Chrome\AntigravityBrowser" https://notebooklm.google.com https://ena01.uqam.ca/course/view.php?id=78751`
- **Règle absolue :** Ne jamais lancer `chrome.exe` headless en arrière-plan depuis PowerShell (Session Isolation Windows). Michel ouvre le raccourci, et l'agent s'y connecte via CDP sur `127.0.0.1:9223`.

---

## 2. Authentification & Pilotage NotebookLM (CLI `nlm`)

1. **Raccordement initial des identifiants (si token expiré) :**
   ```powershell
   & "C:\Users\Michel\.local\bin\nlm.exe" login --cdp-url http://127.0.0.1:9223
   ```
   *Extrait instantanément les cookies du profil actif sans pop-up parasite et enregistre la session dans `~/.notebooklm-mcp-cli/`.*

2. **Commandes de gestion des sources du carnet PSY9613 (`bda39481-344d-444e-bf68-4cb6a704bcfd`) :**
   - **Lister les sources :**
     `nlm source list bda39481-344d-444e-bf68-4cb6a704bcfd`
   - **Renommer une source proprement :**
     `nlm source rename <source_id> "[S01-Diapos] ..." -n bda39481-344d-444e-bf68-4cb6a704bcfd`
   - **Ajouter un fichier local (PDF, Markdown, Texte) :**
     `nlm source add bda39481-344d-444e-bf68-4cb6a704bcfd --file "<chemin_absolu>" --title "<titre_normalise>" --wait`
   - **Interroger le carnet en ligne de commande :**
     `nlm query notebook bda39481-344d-444e-bf68-4cb6a704bcfd "<question>"`

---

## 3. Communication Exclusif avec l'Onglet du Gem (Client Node.js)

Le script de pilotage permanent est situé dans :
[`C:\Users\Michel\.gemini\antigravity\brain\76989406-e739-4d56-85aa-9280b2a78eb4\scratch\gemini_gem_client.js`](file:///C:/Users/Michel/.gemini/antigravity/brain/76989406-e739-4d56-85aa-9280b2a78eb4/scratch/gemini_gem_client.js)

### Commandes disponibles :
```powershell
# 1. Vérifier le statut de l'onglet et le prompt actif
& "C:\Users\Michel\.local\bin\node.exe" "<chemin_script>/gemini_gem_client.js" status

# 2. Injecter une instruction / un bloc de questions au Gem
& "C:\Users\Michel\.local\bin\node.exe" "<chemin_script>/gemini_gem_client.js" send "<Votre prompt ou question>"

# 3. Lire la dernière réponse du Gem (mode DeepThink)
& "C:\Users\Michel\.local\bin\node.exe" "<chemin_script>/gemini_gem_client.js" read-last

# 4. Attendre la fin du raisonnement DeepThink (max 120s) et afficher la sortie
& "C:\Users\Michel\.local\bin\node.exe" "<chemin_script>/gemini_gem_client.js" wait 120
```

---

## 4. Cadre Psychométrique et Épistémique de l'Audit

1. **Un examen est un outil psychométrique d'échantillonnage comportemental :**
   Il vise à inférer la maîtrise réelle du domaine enseigné sans biais (zéro faux positif par élimination triviale, zéro faux négatif par pinaillage sur des détails non enseignés).
2. **Validité de contenu ancrée sur le GOLD :**
   La parole orale brute des professeurs en classe (Dave Saint-Amour et Pierre Poirier) constitue l'étalon d'or. Ce qui a été mis en emphase oralement détermine ce qui est évaluable.
3. **Respect de la Zone Proximale de Développement (ZPD) :**
   Articuler les évaluations en paliers progressifs (socle conceptuel $\rightarrow$ application $\rightarrow$ pièges adversariaux de haut vol) pour que le matériel soit un accélérateur d'apprentissage et non un facteur d'inhibition cognitive.
