# 🛡️ Guide d'Audit Adversarial — Gemini Pro 3.1 DeepThink & NotebookLM
## PSY9613 — Perception, cognition et IA (UQAM) | Sessions 1 & 2

Ce dossier a été conçu sur mesure pour être ingéré instantanément et sans aucune erreur par **Gemini Pro 3.1 (mode DeepThink)**, un **Gem dédié**, ou **NotebookLM**.

---

### 📂 Pourquoi ce dossier fonctionne là où le Drive complet échouait ?
1. **Zéro pollution binaire** : Aucun PDF lourd de 50 Mo, aucune archive `.zip`, aucun dossier système `.git` ou `node_modules`.
2. **11 fichiers texte / markdown purs** (~900 Ko au total) : Parfaitement dans les quotas stricts d'indexation des Gems et de Google Drive Extensions.
3. **Synchronisation en direct** : Étant situé dans le Google Drive local (`G:\My Drive\...`), toute modification apportée par Antigravity est répercutée en quelques secondes dans le cloud Google Drive.

---

### 🚀 3 Méthodes d'utilisation au choix

#### Option A : Gemini Web avec le bouton "DeepThink" (Recommandé)
1. Ouvrir [gemini.google.com](https://gemini.google.com) et s'assurer que le modèle est **Gemini Pro 3.1** avec l'option **DeepThink** activée.
2. Dans le prompt, appeler l'extension Drive : `@Google Drive Drive_Audit_Gemini_DeepThink`.
3. Coller le **Prompt d'Audit Adversarial** ci-dessous.

#### Option B : Dans un Gem personnalisé ("Auditeur PSY9613")
1. Créer ou éditer ton Gem.
2. Dans les sources du Gem, lier spécifiquement ce sous-dossier `Drive_Audit_Gemini_DeepThink`.
3. Mettre les instructions du Gem en lui demandant d'adopter la posture d'un examinateur de doctorat impitoyable.

#### Option C : Dans NotebookLM
1. Ouvrir [notebooklm.google.com](https://notebooklm.google.com).
2. Créer un notebook *« PSY9613 — Audit Examens 1 & 2 »*.
3. Cliquer sur **Ajouter des sources** > **Google Drive** > Sélectionner les 11 fichiers de ce dossier.

---

### 📝 Prompt d'Audit Adversarial à copier-coller dans Gemini DeepThink

```markdown
Tu es un examinateur universitaire sévère et rigoureux, spécialiste en sciences cognitives, neurosciences computationnelles et philosophie de l'esprit, chargé d'auditer les banques de questions d'examen du cours de maîtrise PSY9613 (UQAM), co-enseigné par les professeurs Dave Saint-Amour et Pierre Poirier.

Tu as accès aux fichiers sources de vérité terrain :
- Séance 1 : Seance_01_GOLD_Verbatim_Classe.txt, Seance_01_Synthese_Pedagogique.md, Seance_01_Article_Bosco2023.txt
- Séance 2 : Seance_02_GOLD_Poirier_Enseignement.md, Seance_02_Synthese_Pedagogique.md, et les 4 textes fondateurs (Haugeland, Newell & Simon, McClelland, Sejnowski).
- Banques à auditer : Seance_01_Banque_Questions.md et Seance_02_Banque_Questions.md (35 questions à choix multiples par séance).

Règle d'or absolue des professeurs (Poirier, 02:26:06) :
"Les examens portent principalement sur la matière vue en cours. Aucune question d'examen ne portera sur un point abordé uniquement dans un texte sans avoir été discuté en classe."

Ta mission d'audit adversarial (sois impitoyable, sans complaisance ni optimisme béat) :
1. VÉRIFICATION DU NIVEAU COGNITIF & DES DISTRACTEURS :
   - Vérifie si les 3 choix de réponses erronés (distracteurs) sont réellement crédibles, subtils et représentatifs de fausses conceptions typiques d'étudiants gradués, ou s'ils sont ridicules/évidents.
   - Si une question se résout par simple élimination de réponses niaises (effet flashcard), signale-la immédiatement et propose 3 distracteurs hautement plausibles.

2. FIDÉLITÉ À LA VÉRITÉ TERRAIN DE LA CLASSE :
   - Vérifie que chaque question teste bien un concept explicité oralement par le professeur dans les fichiers GOLD/Verbatim (ex: métaphore de Québec/Montréal pour XOR, regret de Rosenblatt, LEABRA corrélationnel vs error-driven, fenêtre de 7 lettres de NETtalk, TVSS de Bach-y-Rita, Aglioti vs Jackson & Shaw, TDS et calculs de d'/c/beta).
   - Signale toute question qui dévierait vers du détail bibliographique hors-cours.

3. VALIDITÉ DES FEEDBACKS DIAGNOSTIQUES (TOAD) :
   - Vérifie que pour chaque option (A, B, C, D), le feedback de Toad explique avec une exactitude conceptuelle chirurgicale POURQUOI l'option est fausse (ou pourquoi elle est vraie), sans approximation.

Fournis un rapport d'audit structuré :
- Statut global (Note sur 100 de robustesse académique).
- Liste des questions à réviser d'urgence (avec le numéro exact de la question et la correction recommandée).
- Questions modèles validées sans réserve.
```
