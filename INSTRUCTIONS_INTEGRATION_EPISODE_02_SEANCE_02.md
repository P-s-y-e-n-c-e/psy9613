# 📋 Instructions d'Intégration Web & Git — Épisode 2 (Séance 2 : Pr Pierre Poirier)

Ce document fournit le cahier des charges complet pour la **Session Contenu** et la **Session Maintenance** afin d'intégrer le nouvel épisode audio dans l'application web `index.html` et de le déployer sur GitHub Pages.

---

## 🎧 Métadonnées du Nouvel Épisode Audio

* **Titre officiel :** « Épisode 2 — L'IA au défi de Descartes : La grande traversée avec Pierre Poirier »
* **Fichier cible :** `PSY9613_S02_Episode_02_Grand_Deep_Dive_Poirier.m4a`
* **Chemin relatif dans le repo :**  
  `02_Lectures_et_Articles/Semaine_02_IA_Perspectives_historiques/Podcast/PSY9613_S02_Episode_02_Grand_Deep_Dive_Poirier.m4a`
* **Format & Durée :** Audio Overview (Grand Deep Dive • 13:25 • 25.9 Mo)
* **Vocation :** Bilan magistral post-cours, étalon-or basé sur le verbatim GOLD de Pierre Poirier, les temps de passage réels sur les diapositives (*dwell times*) et les textes fondateurs (Haugeland, Newell & Simon, McClelland, Sejnowski).
* **Badge / Statut UI :** `NOUVEAU` (Actif par défaut à l'ouverture de la section).

---

## 🎛️ Spécifications d'Intégration Front-End (`index.html`)

Dans le bloc ressource audio de la Séance 2 (autour de la ligne 3014) :

1. **Parité ergonomique avec PSY7010 (Commutateur d'Épisodes) :**
   Mettre en place un sélecteur d'onglets au-dessus de la bannière ou dans l'en-tête du lecteur pour basculer facilement entre les deux enregistrements disponibles :
   * **Onglet 1 (Existant) :**  
     *Titre :* « Épisode 1 — La perception est une hallucination contrôlée » (22:42)  
     *Fichier :* `02_Lectures_et_Articles/Semaine_02_IA_Perspectives_historiques/Podcast/La_perception_est_une_hallucination_contrôlée.m4a`  
     *Badge :* `Pilote Pré-cours`
   * **Onglet 2 (Nouveau — Actif par défaut) :**  
     *Titre :* « Épisode 2 — L'IA au défi de Descartes : La grande traversée avec Pierre Poirier » (13:25)  
     *Fichier :* `02_Lectures_et_Articles/Semaine_02_IA_Perspectives_historiques/Podcast/PSY9613_S02_Episode_02_Grand_Deep_Dive_Poirier.m4a`  
     *Badge :* `NOUVEAU • Bilan Post-cours`

2. **Comportement JavaScript du lecteur :**
   - Mise à jour dynamique de la source `<audio id="localPodcastAudio">` lors du clic sur un onglet d'épisode.
   - Actualisation instantanée du titre, de la description et de la durée affichée.
   - Remise à zéro du curseur de lecture et conservation du volume / vitesse sélectionnés.

---

## 🚀 Déploiement Git & GitHub Pages (Session Maintenance)

1. **Vérification `.gitignore` :**
   S'assurer que le fichier `.gitignore` autorise le fichier audio finalisé :
   `!02_Lectures_et_Articles/Semaine_02_IA_Perspectives_historiques/Podcast/*.m4a`
   (tout en continuant de filtrer les enregistrements audio bruts de 100 Mo à la racine).
2. **Commit officiel :**
   `feat(audio): integration nouvel episode 2 post-cours Pierre Poirier pour la seance 2 et mascotte Toad`
3. **Synchronisation distante :**
   `git push origin main` pour que le fichier soit accessible publiquement par GitHub Pages sans erreur 404.

---

## 🍄 Bonus UI : Mascotte Header — Réciprocité Toad (PSY9613) ↔ Toadette (PSY7010)

Pour créer le lien réciproque parfait entre les deux stations d'étude de Michel :
1. **Fichier source :** `toad.png` est déjà copié et disponible à la racine du workspace `PSY9613/`.
2. **Dans le header (`index.html` ligne 2754) :**
   Remplacer :
   ```html
   <a href="../psy7010/" class="header-mascot-link" title="Basculer vers la station d'étude PSY7010">
     <img src="toadette.png" alt="Toadette - PSY7010" class="header-mascot-icon" ...>
   </a>
   ```
   par :
   ```html
   <a href="../psy7010/" class="header-mascot-link" title="Basculer vers la station d'étude PSY7010 (Toadette)">
     <img src="toad.png" alt="Toad - Vers Station PSY7010" class="header-mascot-icon" ...>
   </a>
   ```
3. **Animation de Tilt :** La règle CSS (`.header-mascot-link:hover img { transform: scale(1.2) rotate(-10deg); }`) assure déjà le tilt dynamique au survol.
4. **Favicon :** Remplacer `toadette.png` par `toad.png` dans les balises `<link rel="icon">` (lignes 8–10).
