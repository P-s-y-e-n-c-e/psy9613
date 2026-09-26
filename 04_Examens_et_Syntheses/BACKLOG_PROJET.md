# 📋 Backlog & Feuille de Route Officielle — PSY9613 (Station d'Étude & Examens)

**Dernière mise à jour :** 26 Septembre 2026 (01h50 EDT)  
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
| **Sprint 1.1 : Verrouillage sélecteur de langue & Easter Egg** | ✅ En production (`77cbdd0`) | Maintenance | HQ / Michel |
| **Sprint 1.2 : Quarantaine S1 EN & Réinitialisation Langue** | 🟡 En cours | Maintenance | HQ / Michel |
| **Sprint 1.2 : Moteur de Recherche & Surbrillance Visuelle** | 🟡 En cours | Maintenance | HQ / Michel |
| **Séance 3 : Présidence du Débat 1 (Louis vs Alexandrea)** | 🔵 Planifié (Séance 3) | HQ / Michel | Dave Saint-Amour |
| **Banque d'examen Séance 3 (Traitement de l'info)** | 🔵 Planifié | Contenu | Audit adversarial |
| **Préparation Examen 1 (Séances 1 à 6 — 2 nov. 2026)** | 🔵 Planifié | HQ / Contenu | Michel Mercier |

---

## 🚀 2. Livrables Complétés & Validés (Production v1.0 & v1.1)

### A. Psychométrie & Banque d'Examen (40 Items en Ligne)
- [x] **Dépollution calculatoire intégrale :** Éradication de tout calcul mathématique, formule de Weibull ou score Z. Les 40 items évaluent 100 % de mécanismes conceptuels qualitatifs, protocoles et dissociations (TDS, Held & Hein, TVSS, Aglioti vs Jackson & Shaw, Bosco 2023, PSSH, Connexionnisme).
- [x] **Parité psychométrique étalon-or :** Distribution équilibrée exacte des clés de correction ($10 \times \text{A}, 10 \times \text{B}, 10 \times \text{C}, 10 \times \text{D}$), parité de longueur des distracteurs ($\le 7$ caractères de variance), 160 diagnostics cliniques rédigés.
- [x] **Alignement strict vérité-classe (GOLD) :** Ancrage direct sur les verbatims oraux de Dave Saint-Amour (S1) et Pierre Poirier (S2).

### B. Front-End & Expérience Utilisateur (`index.html`)
- [x] **Restauration du défilement :** Élimination des balises `**` Markdown orphelines aux lignes 4187 & 4194 qui perturbaient l'algorithme d'adoption HTML5 et bloquaient le scrolling des 18 viewports (commit `2dcd303`).
- [x] **Barre d'outils unifiée :** Zoom typographique réinitialisable, masquage des sources pour auto-évaluation à l'aveugle.
- [x] **Pagination Google :** Navigation fluide 1-40 avec codes couleur de réponse, mémorisation `localStorage`, mode Flashcards avec auto-évaluation Spaced Repetition.
- [x] **Canal de feedback étudiant sécurisé :** Formulaire d'envoi par relais HTTPS (`formsubmit.co`) directement vers `mercier.michel.4@courrier.uqam.ca` avec repli `mailto:`. Suppression totale de la modale publique locale (commit `0aa8e3f`).
- [x] **Sprint 1.1 Déployé (commit `77cbdd0`) :**
  - Verrouillage du bouton de langue sur `🌐 Français (Original)` pour `doc_seance_01`, `doc_seance_02` et `doc_context`.
  - Easter Egg Toadette cliquable avec animation de tilt au survol pointant vers PSY7010 (`../psy7010/`).

### C. Corpus Scientifique & Traductions
- [x] **5 articles fondamentaux traduits mot à mot en français avec ancres interactives :**
  1. *Bosco et al. (2023)* — Action & Perception
  2. *Newell & Simon (1975)* — PSSH & Recherche Heuristique
  3. *McClelland (2009)* — Modélisation en Sciences Cognitives (PDP)
  4. *Sejnowski (2023)* — LLM et Test de Turing Inversé
  5. *Haugeland (1981)* — Moteurs Sémantiques & Cognitivisme

---

- [x] **Sprint 1.2 Déployé (commit `4299891`) :**
  - **Quarantaine `doc_seance_01_en` :** Cartouche d'avertissement explicite et attribut `data-quarantine="true"` pour interdire toute réactivation intempestive.
  - **Réinitialisation automatique :** Forçage de `docLanguage = 'fr'` dans `switchTab()` dès la sélection d'une note de cours native (`FRENCH_ONLY_DOCS`).
  - **Moteur de recherche non destructif haute visibilité (`TreeWalker`) :**
    - Résolution définitive du bogue de recherche (défilement sans surlignage).
    - **Palette orthogonale anti-confusion (Directive Michel) :** Interdiction stricte du jaune (déjà utilisé par les citations académiques `.source-anchor-target` en `#fef08a`).
    - Toutes les occurrences ciblées en **Cyan Électrique** (`#bae6fd` en clair, `rgba(6,182,212,0.38)` en sombre).
    - Occurrence active en **Magenta Vibrant / Fuchsia (`#d946ef`)** avec halo pulsant (`@keyframes searchPulse`) et défilement centré directement sur le mot.
    - Compteur dynamique `X/Total` en temps réel.

---

## ⚡ 3. Sprints à Venir & Améliorations Systémiques

### Tâche 1.2.3 : Portabilité de la correction de recherche vers PSY7010
- Documenter et préparer le patch miroir pour la station PSY7010 afin de corriger définitivement le même écueil vécu en séance d'évaluation (lignes 13010-13030 de `PSY7010/index.html`).

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
