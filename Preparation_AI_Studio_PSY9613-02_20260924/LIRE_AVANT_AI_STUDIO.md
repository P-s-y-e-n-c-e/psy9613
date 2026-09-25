# Guide de Triangulation AI Studio — PSY9613-02 (21 septembre 2026)

## 📌 Audio Source et Ancrage Temporel
- **Piste utilisée :** `PSY9613 - 21 septembre [S24D].m4a`
- **Emplacement :** Enregistreur S24D placé à proximité immédiate du professeur Pierre Poirier (meilleure qualité vocale).
- **T0 Audio :** 13:30:00 EDT (Heure de Montréal) = `0.00 s` dans l'audio et dans `PSY9613-02_RAW_PRÉTRIANGULATION.json`.
- **Début effectif du cours :** 14:00:00 EDT = `1800.00 s` (offset 00:30:00).
- **IMPORTANT sur les repères :** 14h00 = 0:00 DU COURS, mais = 1800s DANS LE FICHIER AUDIO S24D. Les timestamps de `PSY9613-02_RAW_PRÉTRIANGULATION.json` et de `PSY9613-02_Transitions.md` sont TOUS exprimés dans le référentiel de l'audio S24D (début du cours à 1800.00 s). Ne retranchez pas 1800s en silence.

## 📦 Fichiers à charger dans Google AI Studio
1. `PSY9613-02_RAW_PRÉTRIANGULATION.json` (Extraction WhisperX + alignement wav2vec2, 1788 segments)
2. `Introduction générale au cours PSY9613-2026.pdf` (114 diapositives)
3. `PSY9613-02_Transitions_raw.md` (Tableau initial de transitions brutes)
4. Copier-coller le texte de `PSY9613-02_PROMPT_AI_STUDIO_TRIANGULATION.txt` dans la zone de prompt.

## ⏱️ Repères clés de la séance
- **0.00 s à 1800.00 s (13:30 à 14:00) :** Installation pré-cours, discussions informelles.
- **1800.00 s (14:00:00) :** Début du cours magistral, Diapo 1 affichée.
- **2038.00 s (14:03:58) :** Transition Diapo 2 ("Aujourd'hui").
- **7293.00 s à 8472.00 s (15:31:33 à 15:51:12) :** Pause de mi-séance. Reprise avec Pr Dave Saint-Amour sur les débats en dyades.
- **11507.00 s (16:41:47) :** Défilement rapide fin de cours : diapos 84 -> 96 -> 97 (middle letter /n/) -> 98 (Bullinaria).
- **12731.00 s (17:02:11) :** Fin du diaporama, plénière questions.
- **12976.00 s (17:06:16) :** Arrêt officiel du cours. Audio total : 14951.88 s.
