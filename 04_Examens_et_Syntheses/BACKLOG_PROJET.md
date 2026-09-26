# 📋 Backlog & Feuille de Route Officielle — PSY9613 (Station d'Étude & Examens)

**Dernière mise à jour :** 26 Septembre 2026  
**Responsable de la gouvernance :** Session Quartier Général (HQ)  
**Acteurs opérationnels :** 
- Session Contenu Web (`76989406-e739-4d56-85aa-9280b2a78eb4`)
- Session Maintenance Web (`30eff855-2022-4c41-a03d-1dc843aed0d0`)
- Session Traduction Académique (`5fb475cb-85e7-45bf-8b7e-e1643b727dce`)

---

## 🎯 1. État d'Avancement Global (Vue Synthétique)

| Module / Périmètre | Statut | Responsable | Validé par |
|---|---|---|---|
| **Architecture Quadrangulaire & Règles (`AGENTS.md`)** | ✅ Terminé | HQ | Michel Mercier |
| **Banque d'examen certifiée (40 items : S1 & S2)** | ✅ En production | Contenu | GPT-6 & DeepThink |
| **Correction du bogue de défilement (Strong tags)** | ✅ En production | Maintenance | Audit CDP live |
| **Système de Feedback Étudiant (FormSubmit privé)** | ✅ En production | Maintenance | Michel Mercier |
| **Corpus de 5 articles intégraux traduits en FR** | ✅ En production | Traduction | Équipe |
| **Hygiène du basculeur de langue (Notes FR grisées)** | 🟡 En cours (Sprint 1.1) | Maintenance | HQ |
| **Easter Egg inter-cours (Toadette ↔ PSY7010)** | 🟡 En cours (Sprint 1.1) | Maintenance (9613/7010) | HQ |
| **Séance 3 : Présidence du Débat 1 (Louis vs Alexandrea)** | 🔵 Planifié (Séance 3) | HQ / Michel | Dave Saint-Amour |
| **Banque d'examen Séance 3 (Traitement de l'info)** | 🔵 Planifié | Contenu | Audit adversarial |
| **Préparation Examen 1 (Séances 1 à 6 — 2 nov. 2026)** | 🔵 Planifié | HQ / Contenu | Michel Mercier |

---

## 🚀 2. Livrables Complétés & Validés (Production v1.0)

### A. Psychométrie & Banque d'Examen (40 Items en Ligne)
- [x] **Dépollution calculatoire intégrale :** Éradication de tout calcul mathématique, formule de Weibull ou score Z. Les 40 items évaluent 100 % de mécanismes conceptuels qualitatifs, protocoles et dissociations (TDS, Held & Hein, TVSS, Aglioti vs Jackson & Shaw, Bosco 2023, PSSH, Connexionnisme).
- [x] **Parité psychométrique étalon-or :** Distribution équilibrée exacte des clés de correction ($10 \times \text{A}, 10 \times \text{B}, 10 \times \text{C}, 10 \times \text{D}$), parité de longueur des distracteurs ($\le 7$ caractères de variance), 160 diagnostics cliniques rédigés.
- [x] **Alignement strict vérité-classe (GOLD) :** Ancrage direct sur les verbatims oraux de Dave Saint-Amour (S1) et Pierre Poirier (S2).

### B. Front-End & Expérience Utilisateur (`index.html`)
- [x] **Restauration du défilement :** Élimination des balises `**` Markdown orphelines aux lignes 4187 & 4194 qui perturbaient l'algorithme d'adoption HTML5 et bloquaient le scrolling des 18 viewports.
- [x] **Barre d'outils unifiée :** Recherche textuelle en direct avec surbrillance, zoom typographique réinitialisable, masquage des sources pour auto-évaluation à l'aveugle.
- [x] **Pagination Google :** Navigation fluide 1-40 avec codes couleur de réponse, mémorisation `localStorage`, mode Flashcards avec auto-évaluation Spaced Repetition.
- [x] **Canal de feedback étudiant sécurisé :** Formulaire d'envoi par relais HTTPS (`formsubmit.co`) directement vers `mercier.michel.4@courrier.uqam.ca` avec repli `mailto:`. Suppression totale de la modale publique locale.

### C. Corpus Scientifique & Traductions
- [x] **5 articles fondamentaux traduits mot à mot en français avec ancres interactives :**
  1. *Bosco et al. (2023)* — Action & Perception
  2. *Newell & Simon (1975)* — PSSH & Recherche Heuristique
  3. *McClelland (2009)* — Modélisation en Sciences Cognitives (PDP)
  4. *Sejnowski (2023)* — LLM et Test de Turing Inversé
  5. *Haugeland (1981)* — Moteurs Sémantiques & Cognitivisme

---

## ⚡ 3. Sprint Actuel en Cours (Version 1.1)

### Tâche 1.1.1 : Verrouillage du sélecteur de langue pour les notes de cours FR
- **Constat :** Les onglets *Séance 1 (Dave Saint-Amour)*, *Séance 2 (Pierre Poirier)* et *Contexte UQAM* sont des notes de cours natives rédigées directement en français. Afficher une bascule vers l'anglais sur ces documents est incohérent et risque d'afficher un viewport vide ou corrompu.
- **Spécification :**
  - Dans `switchTab(docId)` et `updateLanguageUI()` : si l'onglet actif est `doc_seance_01`, `doc_seance_02` ou `doc_context`, désactiver le bouton `docLangToggleBtn` (`disabled = true; opacity: 0.4; pointer-events: none; cursor: not-allowed;`).
  - Forcer le libellé à `🌐 Français (Original)`.
  - Réactiver le bouton avec libellé dynamique (`🌐 Français / Anglais`) dès qu'un article traduit (Bosco, Newell, McClelland, Sejnowski, Haugeland) est sélectionné.
- **Assigné à :** Maintenance (`30eff855-2022-4c41-a03d-1dc843aed0d0`).

### Tâche 1.1.2 : Easter Egg inter-cours (Mascotte Toadette)
- **Spécification :**
  - Dans l'en-tête de `index.html` (PSY9613), encapsuler l'icône de Toadette (`toadette.png`) dans un lien hypertexte pointant vers PSY7010 (`../psy7010/`) avec infobulle `title="Basculer vers la station d'étude PSY7010"`.
  - Appliquer l'effet d'animation au survol : `transform: scale(1.2) rotate(-10deg); transition: transform 0.2s ease; cursor: pointer;`.
  - Coordonner avec la session de maintenance de PSY7010 (`620d8c7a-e3d2-4df7-9db0-1af3f8b76824`) pour intégrer le lien retour réciproque vers PSY9613 (`../psy9613/`).
- **Assigné à :** Maintenance PSY9613 & Maintenance PSY7010.

### Tâche 1.1.3 : Maintien du badge de sécurité
- **Spécification :** Conserver la mention `🚧 En construction` dans l'en-tête tant que les finitions du Sprint 1.1 ne sont pas déployées et vérifiées par Michel.

---

## 📅 4. Prochaines Étapes & Échéancier Académique

### Séances 3 & 4 (28 Septembre & 5 Octobre 2026)
- [ ] **Présidence du Débat 1 (28 sept. 2026) :** Animation par Michel du débat en dyade Louis vs Alexandrea (*« Principes du traitement de l'information »*). Utilisation du fichier de cadrage `03_Debats_et_Presentations/2026-09-28_Debat_01_Louis_vs_Alexandrea_Presidence_Michel.md`.
- [ ] **Captation & Chronométrie Séance 3 :** Application des règles de prise de notes en direct (Offsets $T_0$, transitions $D[n]$, sortie master ENCORA).
- [ ] **Banque d'examen Séance 3 :** Traitement de l'information, formalisme computationnel, analogique vs numérique.

### Examens et Jalons Majeurs
- **2 Novembre 2026 (14h00) :** **Examen Intra (35 % de la note finale)** — Séances 1 à 6.
- **14 Décembre 2026 (14h00) :** **Débat en dyade de Michel (25 % de la note finale)**.
- **21 Décembre 2026 (14h00) :** **Examen Final (35 % de la note finale)** — Séances 8 à 12.
