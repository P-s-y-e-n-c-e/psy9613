# 📜 Règles Maîtresses du Workspace PSY9613 — Perception, cognition et IA (UQAM)

Ce fichier définit les directives absolues et les compétences automatisées pour tout agent Antigravity opérant dans ce workspace de cours.

---

## ⚡ 1. Création de Sessions de Chat Antigravity (Règle Anti-Hallucination)

> [!IMPORTANT]
> **Ne JAMAIS affirmer qu'un agent ne peut pas créer une session de chat ou proposer un sous-agent à la place.**
> Antigravity dispose d'une API CLI interne dédiée permettant d'instancier des sessions de chat de premier niveau (`nestingDepth: 0`), rattachées directement au projet actif et visibles dans la barre latérale gauche de l'utilisateur.

### Commande native d'instanciation :
```powershell
& "C:\Users\Psyence\.gemini\antigravity\bin\agentapi.bat" new-conversation --title="<Titre de la session>" "<Prompt initial d'accueil et de directives>"
```

### Commandes disponibles via `agentapi.bat` :
1. **Créer une conversation :**
   `agentapi new-conversation [--model=<flash_lite|flash|pro>] [--title=<titre>] <prompt>`
2. **Vérifier les métadonnées d'une session :**
   `agentapi get-conversation-metadata <conversation_id>`
3. **Communiquer entre sessions :**
   `agentapi send-message [--title=<titre>] <recipient_id> <contenu>`

---

## 🎯 2. Règle d'Or de Prise de Notes en Direct (PSY9613)

1. **ZÉRO REFORMULATION / ZÉRO PARAPHRASE :**
   - Tous les titres, sous-titres et puces des diapositives doivent être **100 % littéraux mot à mot** (*verbatim*), d'après le document PDF officiel distribué par les professeurs (Dave Saint-Amour & Pierre Poirier).
   - Les réflexions, questions et analyses personnelles de Michel sont formellement isolées sous des puces distinctes (*Réflexions & Notes personnelles*).

2. **HORODATAGE & SYNCHRONISATION MULTI-APPAREILS :**
   - Heure de référence universelle : **Heure légale de Montréal (EDT)**.
   - Noter l'heure de lancement $T_0$ de chaque appareil dès le premier message de Michel :
     * Arrivée en avance, à l'heure (14h00) ou en transit/retard.
   - Formule universelle d'offset :
     $$\text{Offset Audio (s)} = \text{Heure réelle (EDT)} - T_0 \text{ (Heure de lancement de l'appareil)}$$
   - Signaux de direct :
     * `D[chiffre]` = Transition de diapositive $\rightarrow$ calcul instantané des offsets Rec 1 (`S24D`) / Rec 2 (`S24`), mise à jour du tableau ENCORA et bascule de la visionneuse.
     * Texte sans préfixe = Note ou réflexion rattachée à la diapositive courante.

3. **VISIONNEUSE INTERACTIVE (PANNEAU DROIT) :**
   - Toujours maintenir `diaporama_cours_XX.html` (avec Tailwind CSS et navigation) et `diaporama_cours_XX.md`.

4. **SORTIE MASTER ENCORA :**
   - Produire à l'issue de chaque séance le fichier de transition Markdown officiel :
     `| **Timestamp (s)** | **Temps (HH:MM:SS)** | **Fichier PDF** | **Diapo** |`
   - Gérer les pauses avec `| **...** | HH:MM:SS | *-- PAUSE --* | *--* |`
   - Gérer la fin avec `| **...** | HH:MM:SS | *-- FIN --* | *--* |`

---

## 🧠 3. Coaching Relationnel & Communication (Adapté au TDAH)

1. **Le « Micro-Pitch 15 Secondes » face aux professeurs :**
   - *Phase 1 (0–5s) :* Constat de terrain brut et observable, sans jargon.
   - *Phase 2 (5–10s) :* Un seul concept théorique précis du cours (ergonomie cognitive / facteurs humains / perception-action).
   - *Phase 3 (10–15s) :* Question ouverte brève et **SILENCE COMPLET**.
   - ⛔ **Règle absolue :** Se taire dès la fin de la question, écouter la réponse, sans surenchérir d'exemples supplémentaires.
2. **Dédramatisation de la cohue de fin de cours :**
   - Si le professeur écourte la discussion (*« J'ai d'autres gens qui attendent... »*), ce n'est **JAMAIS** un rejet personnel.
   - Réflexe pro : *« Parfait [Nom], je t'envoie un courriel de 3 lignes pour qu'on en reparle au prochain atelier »*.
3. **Routine de décompression post-cours :**
   - 15 minutes dans la classe calme, lumières tamisées, *brain dump* dans l'agent pour faire chuter le cortisol avant de rentrer à vélo.
