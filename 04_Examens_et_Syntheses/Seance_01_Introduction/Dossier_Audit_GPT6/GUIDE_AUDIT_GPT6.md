# 📜 GUIDE D'AUDIT ADVERSARIAL CROISÉ (POUR GPT-6)
**Dossier d'évaluation :** Séance 1 — Introduction et Rôle fondamental de l'action (PSY9613, UQAM)  
**Objectif :** Contre-expertise critique et validation factuelle de la banque de questions d'examen par un LLM externe (GPT-6) afin de limiter le biais d'alignement.

---

## 📦 COMPOSITION DU PACK DE SOURCES JOINT
Pour que GPT-6 puisse auditer rigoureusement chaque question sur la base de la vérité terrain, les sources suivantes sont fournies dans ce dossier :

1. **`Notes_Seance_01_Verbatim_et_Chronologie.md` :**
   * Notes intégrales et chronologie à la seconde du cours magistral du 14 septembre 2026.
   * Citations verbatim des professeurs Dave Saint-Amour et Pierre Poirier.
   * Retranscription fidèle et mot à mot des 41 diapositives du support `cours1_Intro.pdf`.
2. **`Bosco_et_al_2023_Texte_Integral.txt` :**
   * Texte intégral brut (16 pages) avec pagination de la revue obligatoire : *The influence of action on perception spans different effectors* (*Frontiers in Systems Neuroscience*, Mai 2023).
3. **`cours1_Intro.pdf` :**
   * Le document visuel officiel distribué aux étudiants par les professeurs.
4. **`Banque_Questions_Seance_01.md` :**
   * Le fichier soumis à l'évaluation, contenant 35 questions d'examen de niveau maîtrise universitaire (QCM approfondis) réparties en 9 blocs thématiques.

---

## 🎯 PROMPT MAÎTRE À COPIER DANS GPT-6

Copiez le texte encadré ci-dessous dans la fenêtre de discussion avec GPT-6 après avoir téléversé les fichiers ci-dessus :

```text
Tu es un examinateur expert et intransigeant en sciences cognitives, psychophysique et neurosciences des facteurs humains (niveau maîtrise et doctorat universitaire, UQAM).

Je te téléverse les sources documentaires officielles du cours PSY9613 (Séance 1) :
- "Notes_Seance_01_Verbatim_et_Chronologie.md" (notes de cours, verbatim des professeurs Dave Saint-Amour et Pierre Poirier, 41 diapositives).
- "Bosco_et_al_2023_Texte_Integral.txt" (revue obligatoire de Bosco et al. 2023, Frontiers in Systems Neuroscience).
- "Banque_Questions_Seance_01.md" (35 questions d'examen à choix multiples approfondies).

Puisque tu n'as pas d'accès direct à un système de fichiers externe, TOUTE ton analyse critique doit être ancrée et vérifiée EXCLUSIVEMENT à partir des documents que je viens de te fournir.

TA MISSION D'AUDIT ADVERSARIAL :
Pour chaque question (ou bloc de questions) :
1. FACT-CHECKING STRICT :
   - Vérifie dans les documents joints que la réponse déclarée correcte est incontestable.
   - Valide l'exactitude des noms d'auteurs, dates, équations mathématiques (ex: formule de d', c, beta en TDS), données numériques et attributions théoriques.
2. RIGUEUR DES DISTRACTEURS :
   - Vérifie que les 3 distracteurs sont formellement faux au regard des textes de référence, mais hautement plausibles (reflétant de réelles fausses conceptions d'étudiants).
   - Signale si un distracteur est arbitraire, absurde ou involontairement vrai.
3. ABSENCE D'AMBIGUÏTÉ :
   - Traque toute ambiguïté syntaxique, double sens ou présupposé non explicité dans l'énoncé.
4. VERDICT ADVERSARIAL :
   - [VALIDÉ TEL QUEL] si la question respecte 100 % des exigences universitaires.
   - [AMENDEMENT REQUIS] avec proposition de correction textuelle appuyée sur la citation exacte du document source.
```
