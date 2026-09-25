# Protocole & Règles de Prise de Notes — Séance 3 (PSY9613)

Ce document rassemble les directives méthodologiques, techniques et relationnelles pour la séance 3 du **lundi 28 septembre 2026** (14h00 – 17h00).

---

## 🎯 1. Contexte du Cours 3 (PSY9613)

* **Date :** Lundi 28 septembre 2026 (14h00 – 17h00 EDT)
* **Enseignants :** Pr Dave Saint-Amour & Pr Pierre Poirier
* **Thème du cours :** **Principes du traitement de l'information**
  * Théorie de l'information
  * Traitement hiérarchique vs parallèle
  * Représentation locale vs distribuée
  * Cognition incarnée
* **Événement majeur d'ouverture (14h00 – 14h45) :**
  * **Débat 1 en dyade : Louis vs Alexandrea**
  * **Président de séance (Modérateur) : Michel** (mandaté officiellement par le Pr Dave Saint-Amour).
  * Fiche de cadrage officielle : [`03_Debats_et_Presentations/2026-09-28_Debat_01_Louis_vs_Alexandrea_Presidence_Michel.md`](file:///g:/My%20Drive/UQAM/Maitrise%20(2194)/PSY9613/03_Debats_et_Presentations/2026-09-28_Debat_01_Louis_vs_Alexandrea_Presidence_Michel.md)

---

## ⚡ 2. Règle Matérielle Absolue : Briser le Cycle des Méthodes Lourdes

> [!CAUTION]
> **GARDE-FOU PROCESSEUR CORE M3 (< 1 GHz, 8 Go RAM, ÉCRAN 4K) :**
> Lors de la Séance 2, l'agent précédent a surchargé la machine en créant et exécutant continuellement des scripts Python et des commandes shell lourdes. Cela a provoqué des latences, des gels d'interface et un gaspillage inutile de ressources.
> **INTERDICTION FORMELLE pour l'agent de la Séance 3 :**
> 1. Ne JAMAIS créer de script Python (ex: `sync_slide.py`) ou lancer un interpréteur Python local pour faire de la synchronisation de diapositives ou calculer des offsets.
> 2. Ne JAMAIS exécuter de commandes shell complexes ou de boucles PowerShell en tâche de fond.
> 3. Utiliser **EXCLUSIVEMENT** les opérations directes de l'environnement : calcul direct de l'offset dans la réponse de l'agent, et modifications directes de fichiers via `write_to_file`, `replace_file_content`, `view_file`.

---

## 📑 3. Recette Technique de Prise de Notes en Direct

1. **RÉCEPTION DU PDF ET GÉNÉRATION DU DIAPORAMA :**
   - Dès que le PDF officiel est déposé dans le dossier (ex: `cours3_Traitement_information.pdf`) :
     * Parser le texte diapo par diapo sans paraphrase ni résumé.
     * Générer le fichier interactif propre et autonome : `diaporama_cours_03.html` dans `01_Diapositives_et_Notes/` ET dans le brain (`ArtifactMetadata: { UserFacing: true, Summary: "Visionneuse Séance 3", RequestFeedback: false }`).
     * Caractéristiques du diaporama : touches fléchées Gauche/Droite, menu déroulant `<select>`, mode Verbatim complet, CSS Tailwind fluide.

2. **FILET DE SÉCURITÉ DANS LE CHAT (RÈGLE ANTI-BULLSHIT) :**
   - L'agent ne dispose d'aucun capteur UI pour savoir si le panneau latéral d'artefacts est visible ou masqué sur l'écran de Michel.
   - Ne jamais affirmer « le panneau est ouvert ».
   - **Garantie visuelle obligatoire :** À chaque signal `D[chiffre]` de Michel, l'agent réinjecte **immédiatement dans le corps de sa réponse dans le chat** :
     * Numéro et titre exact de la diapositive.
     * Sous-titre et puces textuelles mot à mot.
     * Horodatage EDT et offsets Rec 1 (`S24`) / Rec 2 (`S24D`).

3. **HORODATAGE & SYNCHRONISATION MULTI-APPAREILS :**
   - Heure de référence universelle : **Heure légale de Montréal (EDT)**.
   - Noter immédiatement $T_0$ de chaque appareil dès le premier message :
     * Principal (`S24`) et Backup (`S24D`).
   - Calcul instantané sans script : $\text{Offset (s)} = \text{Heure de l'événement (EDT)} - T_0$.
   - Format de transition officiel ENCORA à 4 colonnes :
     `| **Timestamp (s)** | **Temps (HH:MM:SS)** | **Fichier PDF** | **Diapo** |`

---

## ⚖️ 4. Directives d'Animation pour la Présidence du Débat 1

* Michel anime l'ouverture de la séance (14h00 – 14h45).
* **Minutage strict :**
  - Introduction par Michel (2 min) : présentation de Louis et Alexandrea, annonce de la question.
  - Exposé Louis (5 à 10 min).
  - Exposé Alexandrea (5 à 10 min).
  - Débat croisé & Discussion plénière (15 à 20 min) animée par Michel (tours de parole, relances méthodologiques/conceptuelles).
  - Synthèse & Clôture par Michel (2-3 min) avant de passer la main aux professeurs.
* L'agent de session doit avoir sous la main les relances types formulées dans `03_Debats_et_Presentations/2026-09-28_Debat_01_Louis_vs_Alexandrea_Presidence_Michel.md`.

---

## 🧠 5. Coaching Relationnel TDAH & Décompression

1. **Micro-Pitch 15 Secondes face aux profs :**
   - Constat terrain brut (5s) ➔ Concept théorique précis (5s) ➔ Question ouverte (5s) ➔ **Silence complet**.
2. **Dédramatisation fin de cours :**
   - Si le prof écourte l'échange, ce n'est jamais personnel : *« Parfait Dave/Pierre, je t'envoie un courriel de 3 lignes »*.
3. **Routine post-cours :**
   - 15 minutes au calme dans la classe pour faire le *brain dump* dans l'agent avant de rentrer à vélo.
