# 🎙️ Guide de Production & Curation des Podcasts NotebookLM : Séance 2

* **Cours :** PSY9613 — Perception, cognition et intelligence artificielle (UQAM)
* **Date de la séance en classe :** Lundi 21 septembre 2026
* **Enseignant titulaire :** Pr Pierre Poirier (PhD)
* **Co-enseignant :** Pr Dave Saint-Amour (PhD)
* **Titre officiel :** *Histoire et fondements de l'IA : Du calcul symbolique au connexionnisme*
* **Corpus source d'étalon-or :**
  1. `[S02-GOLD] Enseignement intégral Pierre Poirier (21 sept 2026)` (Verbatim de classe épuré)
  2. `[S02-Diapos] Pr Pierre Poirier - Histoire et fondements de l'IA (21 sept 2026)` (114 diapositives)
  3. `[S02-Transitions] Horodatages, diapos et temps de passage en classe` (`PSY9613-02_Transitions_v2.md`)
  4. `[S02-Obligatoire] Haugeland (1981) - Semantic Engines`
  5. `[S02-Obligatoire] Newell & Simon (1975) - Physical Symbol Systems`
  6. `[S02-Optionnel] McClelland (2009) - Modelling in Cognitive Science`
  7. `[S02-Optionnel] Sejnowski (2023) - Reverse Turing Test & LLMs`
* **Carnet officiel Google NotebookLM :** [`bda39481-344d-444e-bf68-4cb6a704bcfd`](https://notebooklm.google.com/notebook/bda39481-344d-444e-bf68-4cb6a704bcfd)

---

## 🧭 Cartographie des Épisodes de la Séance 2

| Épisode | Statut / Rôle | Titre | Format & Durée | Vocation Pédagogique |
| :--- | :---: | :--- | :---: | :--- |
| **Épisode 1 (Pilote pré-cours)** | *Existant* | « La perception est une hallucination contrôlée » | ~22:42 | Mise en bouche avant le cours (lectures Clark, Seth, Dreyfus, Haugeland). |
| **Épisode 2 (Master post-cours)** | **MASTER ÉTALON-OR** ⭐ | « De Descartes à NETtalk » | Grand Deep Dive (16:46 • 32.4 Mo) | **Consolidation post-cours étalon-or** : Ancrage chirurgical sur ce qui s'est réellement dit en classe, analyse des temps de passage (*dwell times*), rupture cartésienne, Turing/Chomsky, Haugeland soccer, surface d'erreur 3D et démonstration sonore historique de NETtalk 1987. |

---

## 🛠️ Partition Directrice NotebookLM (Grand Deep Dive Post-Cours)

### Consignes de cadrage & Style linguistique
* **Langue et registre obligatoires :** Français canadien (Québec). Les deux co-animateurs adoptent un français québécois soigné, fluide, naturel et universitaire (registre académique de l'UQAM).
* **Bannissement total et absolu de toute tournure de France :** Interdiction formelle de *« du coup »*, *« en vrai »*, *« pour le coup »*, *« boulot »*, *« bagnole »*, etc.
* **Désignation de l'enseignant :** Toujours désigner l'enseignant par *« le professeur Pierre Poirier »* ou *« le Pr Poirier »*.
* **Posture :** Deux chercheurs d'études supérieures en sciences cognitives et IA qui décortiquent rétrospectivement la séance de 3 heures pour un étudiant qui révise en profondeur.

### Plan de vol thématique détaillé

1. **Introduction & La Rupture Cartésienne (L'énigme Esprit vs Mécanisme) :**
   - Situer le point de départ de Pierre Poirier : René Descartes et les automates animaux vs l'humain.
   - Les deux critères cartésiens fondamentaux (Diapos 6-7) :
     * *Le langage :* impossibilité mécanique d'agencer des paroles pour répondre avec à-propos à toute situation.
     * *L'universalité de la raison :* la raison comme « instrument universel », contrastée avec la modularité étroite et rigide des mécanismes d'organes spécifiques.
   - Le paradoxe fondateur : comment un mécanisme physique fini peut-il engendrer une infinité de comportements intelligents ?

2. **La Révolution de Turing et la Récursivité Syntaxique de Chomsky :**
   - Alan Turing (1936 / 1950, Diapos 14-17) : La Machine de Turing universelle comme solution mécanique au dilemme cartésien.
   - Noam Chomsky (*Cartesian Linguistics*, Diapos 18-19) : L'usage infini de moyens finis grâce à la récursivité syntaxique ($n = n + 1$, enchâssement de propositions : *"Chatterer said that Buster thought that the tree was tall"*).
   - L'annotation contemporaine de Poirier (Diapo 10) : l'analogie moderne de l'enseignant évaluant un travail d'étudiant vs ChatGPT.

3. **Le Computationnalisme Symbolique (PSSH) & L'Indépendance du Médium :**
   - L'hypothèse centrale de Newell & Simon (1975, Diapos 20-21) : *« A physical symbol system has the necessary and sufficient means for general intelligent action »*.
   - L'indépendance par rapport au médium (*substrate neutrality* / réalisabilité multiple, Diapo 26) : neurones de carbone, puces de silicium ou engrenages de bois.
   - De George Boole (1854) aux *Principia Mathematica* de Whitehead & Russell (Diapos 28-29) : la pensée réduite à un calcul aveugle sur des symboles discrets.

4. **Les Moteurs Sémantiques et l'Analogie du Soccer (Haugeland) :**
   - Dwell massif de Poirier sur John Haugeland (1981, *Semantic Engines*, Diapos 36-45).
   - L'animation du terrain de football : jetons et règles de déplacement purement syntaxiques sans aucune conscience du « jeu réel ».
   - La formule d'or de Haugeland : *« If you take care of the syntax, the semantics will take care of itself »*. Le miracle de l'isomorphisme formel entre la syntaxe interne et le monde externe.
   - Distinction formelle : symboles manipulés en mémoire vs référents réels dans le monde.

5. **La Vision Computationnelle de David Marr :**
   - L'application du computationnalisme à la perception (Diapo 57).
   - Le pipeline séquentiel : Image rétinienne $\rightarrow$ Primal sketch $\rightarrow$ 2.5-D sketch (*viewer-centred*) $\rightarrow$ Représentation 3D (*object-centred*).

6. **Le Tournant Connexionniste & La Démonstration NETtalk :**
   - Pourquoi le symbolisme a flanché : fragilité face au bruit, problème de l'ancrage des symboles (*symbol grounding*), incapacité d'apprendre par l'expérience.
   - De McCulloch & Pitts (1943) et Shannon (1940, Diapos 63-64) à Rosenblatt (Perceptron).
   - La sommation pondérée et la fonction de seuil (Diapo 77, l'analogie de la classe qui vote à main levée).
   - Le saut pédagogique de Poirier : pourquoi sauter les équations intermédiaires (Diapos 85-94) pour se concentrer sur la surface d'erreur 3D (Diapo 95) et la descente de gradient par rétropropagation (*backpropagation*).
   - La démonstration audio historique de NETtalk (Sejnowski & Rosenberg 1987, Diapo 96) : du babillage d'enfant à la parole continue articulée.
   - Les représentations internes distribuées (Diapos 97-98, Bullinaria 1997) : émergence spontanée de clusters sémantiques et phonétiques dans l'espace caché, sans symboles préprogrammés.

7. **Conclusion & Trajectoire PSY9613 :**
   - Bouclage rétrospectif : comment le débat Symbolisme vs Connexionnisme permet de réinterpréter la Séance 1 (perception-action, Held & Hein, Aglioti).
   - Ouverture vers la Séance 3 : les principes du traitement de l'information, et le Débat 1 d'ouverture (Louis vs Alexandrea, sous la présidence de Michel).

---

## 📦 Fiche de Transfert Technique (Pour Sessions Contenu & Maintenance)

* **Fichier audio final officiel :** `PSY9613_S02_Episode_02_De_Descartes_a_NETtalk.m4a`
* **Emplacement local :** `02_Lectures_et_Articles/Semaine_02_IA_Perspectives_historiques/Podcast/`
* **Durée :** 16 min 46 sec (32.4 Mo)
* **Bannière Web (`index.html`) :**
  - Mettre en place un commutateur d'épisodes (parité ergonomique avec PSY7010) :
    * Onglet 1 : *Épisode 1 (Pilote pré-cours) — « La perception est une hallucination contrôlée » (22 min)*
    * Onglet 2 : *Épisode 2 (Master post-cours) — « De Descartes à NETtalk » (16 min 46 s • Actif par défaut avec badge « ÉTALON-OR »)*.
    * Onglet 3 : *Épisode 3 (Pré-cours Séance 3) — « L'Espace de Travail Global du cerveau & Cadrage du Débat 1 » (23 min 27 s)*.
