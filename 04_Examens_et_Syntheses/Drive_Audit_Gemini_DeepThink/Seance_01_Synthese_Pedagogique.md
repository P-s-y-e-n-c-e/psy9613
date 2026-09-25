# 🧠 Synthèse Pédagogique Approfondie — Séance 1 (PSY9613)
**Cours :** PSY9613 — Perception, cognition et intelligence artificielle (UQAM)  
**Titre officiel de la séance :** Présentation du cours et introduction  
**Date du cours :** Lundi 14 septembre 2026 (14h00 – 17h00)  
**Professeurs :** Dave Saint-Amour & Pierre Poirier  
**Support de référence :** `cours1_Intro.pdf` (41 diapositives) & Notes de cours réelles `notes_seance_01_2026-09-14.md`  
**Lecture obligatoire :** Bosco et al. (2023), *The influence of action on perception spans different effectors*, *Frontiers in Systems Neuroscience*.  
**Poids sommatif associé :** Matière intégrante de l'Examen 1 du 2 novembre 2026 (35 % de la note finale).

---

## 📑 TABLE DES PILIERS THÉORIQUES

1. [Épistémologie & Vocabulaire Fondamental : Perception, Cognition, Intelligence](#1-épistémologie--vocabulaire-fondamental)
2. [Le Modèle Classique « Entrée – Traitement – Sortie » et ses Limites](#2-le-modèle-classique-entrée--traitement--sortie)
3. [De la Psychophysique Historique à la Théorie de la Détection du Signal (TDS)](#3-psychophysique-historique-et-théorie-de-la-détection-du-signal)
4. [Formules Mathématiques et Modélisation Normale de la TDS ($d'$, $c$, $\beta$)](#4-formules-mathématiques-et-scénarios-de-la-tds)
5. [Naissance du Fonctionnalisme & Le Cerveau Prédictif](#5-fonctionnalisme--cerveau-prédictif)
6. [L'Approche Écologique de James J. Gibson & La Notion d'Affordance](#6-lapproche-écologique-de-gibson--laffordance)
7. [Gibson (1977) vs Donald Norman (1988) : Affordance Réelle vs Affordance Perçue](#7-gibson-vs-norman-sur-laffordance)
8. [Les Démonstrations Empiriques de la Perception Active](#8-démonstrations-empiriques-de-la-perception-active)
9. [Neurosciences de la Vision : Modèle des Deux Voies Corticales (Milner & Goodale)](#9-modèle-des-deux-voies-corticales)
10. [Rupture de l'Étanchéité Modulaire : L'Étude de Jackson & Shaw (2000)](#10-rupture-de-létanchéité-modulaire)
11. [L'Action Sculpte la Perception : Attention Présaccadique & Rôle du FEF](#11-attention-présaccadique--rôle-du-fef)
12. [Perception Spécifique à l'Action (Proffitt) vs Perception Catégorielle (Harnad)](#12-action-specific-perception-vs-perception-catégorielle)
13. [Analyse Détaillée de l'Article Obligatoire : Bosco et al. (2017, 2023)](#13-analyse-de-larticle-obligatoire-bosco-et-al)
14. [Amorce Prospective : Reverse Hierarchy Theory (Hochstein & Ahissar)](#14-amorce-prospective-reverse-hierarchy-theory)

---

## 1. Épistémologie & Vocabulaire Fondamental

Dès l'ouverture conceptuelle du cours (Diapos 7 et 8), les professeurs Dave Saint-Amour et Pierre Poirier établissent une distinction sémantique et épistémologique stricte entre trois notions souvent confondues :

* **Perception** (*perceptum* : « ce qui est recueilli ») :
  * Processus interprétatif actif qui organise, discrimine et donne du sens aux stimulations sensorielles brutes.
  * La perception ne se réduit jamais à un simple enregistrement passif : elle est une **construction** dépendante des connaissances préalables de l'organisme, de ses attentes et de son histoire sensorimotrice.
* **Cognition** (*cognoscere* : « savoir, connaître ») :
  * Ensemble des processus mentaux par lesquels un organisme vivant ou artificiel acquiert, traite, transforme, stocke et réutilise l'information (perception, attention, mémoire, calcul, raisonnement, prise de décision).
  * **Règle d'or professorale :** La cognition désigne ce qui se déroule dans le système d'information **sans aucun jugement de valeur ou de qualité**. La cognition est une notion strictement **neutre et descriptive**. Un raisonnement fallacieux, une illusion perceptive ou un oubli mnésique relèvent de la cognition au même titre qu'une déduction logique impeccable.
* **Intelligence** (*intelligere* : « discerner, comprendre, lier ensemble ») :
  * Contrairement à la cognition, l'intelligence est une notion intrinsèquement **évaluative et normative**.
  * Elle qualifie l'**efficacité**, la pertinence et l'organisation optimale avec laquelle les processus cognitifs sont mobilisés pour résoudre des problèmes, s'adapter à des situations **nouvelles ou imprévues** et atteindre des buts vitaux (prédire, généraliser, agir efficacement).
* **Formulation mot à mot à retenir (Diapo 8) :**
  $$\text{La cognition est aux processus ce que l'intelligence est à l'usage optimal et adaptatif de ces processus.}$$

---

## 2. Le Modèle Classique « Entrée – Traitement – Sortie »

Le paradigme fondateur des sciences cognitives de première génération (computationalisme symbolique des années 1950–1970) modélisait l'esprit sur le schéma séquentiel de l'architecture de von Neumann (Diapo 9) :

$$\mathbf{Perception}\text{ (Input sensoriel passif)} \longrightarrow \mathbf{Cognition}\text{ (Traitement central / Représentations)} \longrightarrow \mathbf{Action}\text{ (Output moteur)}$$

* **Caractéristiques épistémologiques du modèle classique :**
  1. **Unidirectionnalité stricte :** L'information circule exclusivement de l'environnement vers les organes sensoriels, puis vers le processeur central, pour aboutir à une commande motrice.
  2. **Isolatisme modulaire :** La perception est considérée comme un simple canal d'alimentation de la pensée ; l'action n'est qu'un exécutant physique terminal dénué d'intelligence propre.
  3. **Absence de rétroaction motrice :** Le modèle postule qu'on peut comprendre intégralement la perception sans prendre en compte les mouvements et l'anatomie du corps de l'agent.
* **Statut dans le cours :** Ce modèle constitue l'obstacle épistémologique central réfuté tout au long de la séance pour imposer le paradigme de la cognition incarnée et de la boucle sensorimotrice fermée.

---

## 3. Psychophysique Historique et Théorie de la Détection du Signal

### A. La Psychophysique Classique (Diapos 10 & 11)
* **Ernst Weber (1830–1850) :** Étude expérimentale du sens tactile. Découverte du **seuil différentiel** (*Just Noticeable Difference* - JND). La variation minimale d'intensité physique ($\Delta I$) nécessaire pour percevoir une différence n'est pas constante dans l'absolu, mais proportionnelle à l'intensité de base du stimulus ($I$) :
  $$\frac{\Delta I}{I} = k \quad \text{(Fraction de Weber)}$$
* **Gustav Theodor Fechner (1860) :** Publication de *Elemente der Psychophysik*. En intégrant mathématiquement la loi de Weber, Fechner postule que la sensation psychologique subjective ($S$) varie comme le logarithme de l'énergie physique ($I$) :
  $$S = k \cdot \log(I)$$
  * *Démonstration en classe :* Passer de 10 à 20 points sur un écran saute aux yeux (ratio 2:1), alors que passer de 110 à 120 points est virtuellement imperceptible à l'œil nu, malgré un accroissement physique absolu strictement identique ($\Delta I = 10$).
* **Wilhelm Wundt (1879) :** Création du premier laboratoire de psychologie expérimentale à Leipzig.

### B. Le Problème du Seuil Fixe et l'Avènement de la TDS (Diapos 12 & 13)
* **L'aporie du seuil déterministe classique :** La psychophysique classique supposait qu'il existait un seuil absolu fixe et invariable sous lequel un stimulus n'était jamais détecté, et au-dessus duquel il était perçu à 100 %.
* **La réalité neurobiologique :** Le système nerveux est le siège d'une activité électrophysiologique spontanée continue (**bruit neuronal intrinsèque**). Il n'y a jamais de signal sensoriel pur dans un cerveau silencieux.
* **Tanner & Swets (1954) — *A decision-making theory of visual detection* :**
  * La détection n'est pas un mécanisme passif d'enregistrement, mais une **décision statistique prise sous incertitude** face à un mélange de signal et de bruit.
  * Modèle initial : L'opérateur radar qui doit distinguer sur son écran cathodique si une faible lueur représente un avion ennemi réel (Signal + Bruit) ou une fluctuation électronique / nuage de parasites (Bruit seul).

---

## 4. Formules Mathématiques et Scénarios de la TDS

La Théorie de la Détection du Signal modélise l'état interne du système par deux distributions gaussiennes de variance unitaire ($\sigma = 1$) : la distribution du **Bruit seul ($N$)** et la distribution du **Signal + Bruit ($S+N$)** (Diapos 14 à 17).

```
   Densité
      ▲
      │          Bruit (N)            Signal + Bruit (S+N)
      │          ┌───────┐                 ┌───────┐
      │         ┌┘       └┐               ┌┘       └┐
      │        ┌┘         └┐             ┌┘         └┐
      │       ┌┘           └┐           ┌┘           └┐
      │      ┌┘             └┐         ┌┘             └┐
      │     ┌┘       │       └┐       ┌┘       │       └┐
      └─────┴────────┼────────┴───────┴────────┼────────┴──────► Axe Sensoriel (X)
                   µ_N = 0                   µ_S
                     │◄───────── d' ──────────►│
                                   ▲
                                   │
                              Critère (Xc)
```

### A. Matrice des Contingences 2×2
| | **Signal Présent ($S$)** | **Signal Absent / Bruit ($N$)** |
| :--- | :---: | :---: |
| **Réponse « OUI » (Détecté)** | **Détection / Hit ($H$)** | **Fausse Alarme / False Alarm ($F$)** |
| **Réponse « NON » (Non détecté)** | **Omission / Miss ($1 - H$)** | **Rejet Correct / Correct Rejection ($1 - F$)** |

### B. Formules Mathématiques Exigibles
1. **Sensibilité discriminative ($d'$) :**
   $$d' = z(H) - z(F)$$
   * Distance standardisée entre les moyennes des deux distributions en unités d'écart-type.
   * Mesure la **capacité sensorielle objective** du sujet à discriminer le signal du bruit. Totalement indépendante de la stratégie ou du biais décisionnel.
2. **Critère de décision ($c$) :**
   $$c = -0,5 \times [z(H) + z(F)]$$
   * Position du critère par rapport au point neutre où les deux courbes se croisent ($c = 0$).
   * **Convention de signe obligatoire :**
     * $c = 0$ : **Neutre** (aucun biais a priori).
     * $c < 0$ : **Libéral / Laxiste** (déplacement vers la gauche $\rightarrow$ réponse « OUI » facilitée $\rightarrow$ hausse des Hits, mais hausse corrélative des Fausses Alarmes).
     * $c > 0$ : **Conservateur / Prudent** (déplacement vers la droite $\rightarrow$ réponse « NON » favorisée $\rightarrow$ baisse des Fausses Alarmes, mais hausse des Omissions et chute des Hits).
3. **Rapport de vraisemblance ($\beta$) :**
   $$\beta = \exp(c \times d') = \frac{f_S(X_c)}{f_N(X_c)}$$
   * $\beta = 1,00 \iff \text{Neutre}$ ; $\beta < 1,00 \iff \text{Libéral}$ ; $\beta > 1,00 \iff \text{Conservateur}$.

### C. Données Numériques Officielles (Diapo 17, $d' = 2,12$)
| Profil de décision | Valeur de $c$ | Valeur de $\beta$ | Taux de Hits ($H$) | Taux de Fausses Alarmes ($F$) |
| :--- | :---: | :---: | :---: | :---: |
| **Libéral** | **$-0,22$** | **$0,63$** | **$0,900$ (90,0 %)** | **$0,200$ (20,0 %)** |
| **Neutre** | **$0,00$** | **$1,00$** | **$0,856$ (85,6 %)** | **$0,144$ (14,4 %)** |
| **Conservateur** | **$+0,83$** | **$5,83$** | **$0,592$ (59,2 %)** | **$0,029$ (2,9 %)** |

* **Application Diapo 15 (Tâche Random Dot Motion - RDM) :**
  * Données : 45 Hits / 50 ($H = 0,90$) ; 10 FA / 50 ($F = 0,20$).
  * $z(0,90) = +1,28$ ; $z(0,20) = -0,84$.
  * $d' = 1,28 - (-0,84) = 2,12$.
  * $c = -0,5 \times (1,28 - 0,84) = -0,22$ $\rightarrow$ Profil Libéral avec $\beta = 0,63$.

---

## 5. Fonctionnalisme & Cerveau Prédictif

### A. William James (1890) et l'Approche Fonctionnelle (Diapo 18)
* Dans *The Principles of Psychology*, William James abandonne l'introspection structuraliste pour poser la question téléologique fondamentale : **À quoi sert l'esprit ?** Quelle est sa fonction dans l'adaptation de l'organisme à son milieu ?
* **Citation majeure (Diapo 18) :**
  > *« Une partie de ce que nous percevons nous vient de l'objet extérieur par le canal des sens, et l'autre partie … vient du dedans, c'est-à-dire de notre conscience. »*
* **La règle de l'objet le plus probable (Diapo 19) :** Devant une entrée sensorielle incomplète ou ambiguë, le système perceptif synthétise l'objet le plus probable compte tenu du contexte global.
  * Démonstration en classe : Un caractère central physiquement ambigu (trois barres formant un glyphe intermédiaire) est résolu en chiffre « 13 » dans la séquence horizontale numérique `12 - 13 - 14`, mais est interprété comme la lettre « B » dans la séquence verticale lexicale $\begin{pmatrix} A \\ B \\ C \end{pmatrix}$.

### B. Inférences Inconscientes et Hypothèses Perceptives (Diapo 20)
* **Hermann von Helmholtz (1821–1894) :** Théorie des **inférences inconscientes** (*Unconscious Inferences*). L'image projetée sur la rétine 2D étant mathématiquement sous-déterminée, le cerveau calcule en permanence l'état 3D le plus probable de la source lumineuse extérieure.
* **Richard Gregory (1923–2010) :** La perception comme formulation continue d'**hypothèses** testées contre les données sensorielles.

### C. Fonctionnalisme Computationnel : Karl Friston & Le Cerveau Prédictif (Diapo 21)
* **Théorie du codage prédictif (*Predictive Coding*) & Principe de l'Énergie Libre :**
  * Le cerveau n'est pas un accumulateur passif de données, mais un **moteur d'inférence active bayésienne**.
  * Des flux descendants (*top-down*) projettent en continu des prédictions générées par des modèles internes du monde.
  * Ces prédictions rencontrent les données ascendantes (*bottom-up*) en provenance des récepteurs sensoriels.
  * **Erreur de prédiction (*Prediction Error*) :** Seule la différence (le résidu d'erreur) est transmise vers les étages corticaux supérieurs pour ajuster le modèle interne.
* **Nature des illusions selon Friston (Diapos 22 & 23) :**
  * Les illusions visuelles (nuage en silhouette de théière, ombre trompeuse) et les anamorphoses urbaines (fossé 3D peint sur une chaussée plane qui force le piéton à enjamber le vide) prouvent que les *priors* prédictifs sont si puissants qu'ils configurent directement l'expérience consciente et déclenchent des programmes moteurs d'évitement avant même toute vérification tactile.

---

## 6. L'Approche Écologique de Gibson & L'Affordance

### A. Rupture Épistémologique de James J. Gibson (1904–1979) (Diapos 25 à 27)
* Dans *The Ecological Approach to Visual Perception* (1979), Gibson rejette le modèle computationnel de traitement de l'information (rejet des images rétiniennes dégradées, des calculs mentaux et des représentations internes symboliques).
* **Thèse ontologique fondamentale (Verbatim Diapo 26) :**
  > *« Ce qu’est une chose et ce qu’elle signifie ne sont pas séparés, le premier étant physique et le second mental comme nous avons l’habitude de le croire. »*
* **L'Affordance gibsonienne (Gibson, 1977, 1979) :**
  * Ensemble des opportunités d'action offertes directement et objectivement à un organisme par un objet, une surface ou un milieu.
  * L'affordance est une **propriété écologique relationnelle** : elle n'appartient ni à l'objet seul, ni au sujet seul, mais existe à l'intersection de la structure physique de l'environnement et des propriétés biomécaniques propres au corps de l'organisme (*body-scaled*).
  * L'affordance est **invariante et objective** : elle existe indépendamment du fait que l'observateur la perçoive, la reconnaisse ou souhaite l'utiliser.
* **Le Flux Optique (*Optical Flow*) :** Structure dynamique et continue de déformation de la lumière sur la rétine induite par les mouvements de l'agent. Le flux optique spécifie directement le cap de déplacement (centre d'expansion) et le temps de collision sans reconstruction géométrique abstraite.
* **La boucle perception-action :** « On perçoit pour agir, et on agit pour percevoir ».

---

## 7. Gibson vs Norman sur l'Affordance

L'un des pièges d'examen les plus classiques réside dans la confusion entre l'approche écologique de Gibson et l'approche ergonomique de Norman (Diapo 28) :

| Dimension d'analyse | James J. Gibson (1977, 1979) — Écologie Visuelle | Donald Norman (1988) — Ergonomie Cognitive & UX |
| :--- | :--- | :--- |
| **Domaine d'application** | Évolution animale, survie écologique, locomotion naturelle. | Conception d'artefacts, design d'interfaces, ergonomie industrielle. |
| **Définition de l'affordance** | **Affordance Réelle / Physique :** Propriété physique objective du milieu couplée à l'anatomie de l'organisme. | **Affordance Perçue :** Ce que l'utilisateur humain croit ou comprend qu'il peut faire d'après l'apparence visuelle. |
| **Rôle de la perception** | La perception est directe, sans médiation de modèle mental. | Repose sur les modèles mentaux, l'apprentissage culturel et les conventions. |
| **Concept clé dérivé** | Invariants écologiques, flux optique. | **Signifiants (*Signifiers*)** et faillites de design (**« Portes Norman »**). |
| **Exemple type** | Une surface rocheuse plane afforde la posture assise pour un humain. | Une porte munie d'une poignée verticale qu'il faut en réalité pousser (conflit ergonomique). |

---

## 8. Démonstrations Empiriques de la Perception Active

La perception n'est pas un système visuel qui contemple le monde, mais un système sensorimoteur qui s'éduque par l'action (Diapo 29).

### A. Held & Hein (1963) — Le Carrousel des Chatons
* **Dispositif :** Paires de chatons élevés dans le noir complet dès la naissance, placés dans un carrousel couplé mécaniquement lors des sessions d'exposition à la lumière :
  * **Chaton Actif :** Se déplace librement sur ses pattes et tracte le mécanisme.
  * **Chaton Passif :** Suspendu dans une nacelle tractée par le chaton actif ; ses pattes ne touchent pas le sol.
* **Contrôle expérimental capital :** Les deux chatons reçoivent **rigoureusement la même stimulation visuelle rétinienne** (même trajectoire, même flux optique, même durée).
* **Résultats aux tests de motricité visuelle guidée :**
  * Le chaton actif développe des réponses visuo-motrices normales : réflexe d'extension des pattes à l'approche du sol, clignement défensif et **évitement spontané du côté profond de la falaise visuelle (*visual cliff*)**.
  * Le chaton passif se comporte comme un animal aveugle : il ne déploie pas ses pattes pour amortir sa chute et marche sans hésiter au-dessus du vide de la falaise visuelle.
* **Conclusion :** La vision fonctionnelle de l'espace et de la profondeur exige impérativement le couplage en boucle fermée entre la commande motrice volontaire (efférence) et le retour sensoriel résultant (réafférence).

### B. Paul Bach-y-Rita (1969) — Substitution Sensorielle Tactile (TVSS)
* **Système TVSS (*Tactile Vision Substitution System*) :** Caméra vidéo dont les contrastes lumineux sont convertis en une matrice de pointes vibrantes appliquées sur la peau du dos ou la langue d'aveugles de naissance.
* **Résultat fondamental :**
  * Si la caméra est manipulée par l'expérimentateur, le sujet aveugle ne ressent qu'un chatouillement cutané localisé sur sa peau (perception égocentrée passive).
  * **Dès que le sujet prend lui-même le contrôle moteur actif de la caméra**, les sensations cutanées s'estompent de la conscience et basculent dans une phénoménologie spatiale externe : le sujet perçoit des **objets localisés à distance dans l'espace tridimensionnel** (*distal attribution*).

### C. Exemple Écologique : Conducteur vs Passager (Diapo 30)
* Le conducteur d'un véhicule engage en continu des boucles sensorimotrices (volant, pédales, freinage) : il mémorise le tracé et s'oriente sans effort conscient.
* Le passager reçoit passivement le défilement du paysage sans motricité associée : il demeure incapable de reproduire le trajet.

### D. Nataliya Kosmyna et al. (MIT Media Lab, 2025) — *Your Brain on ChatGPT* (Diapo 31)
* **Étude expérimentale :** Analyse EEG lors de la rédaction d'essais universitaires avec ou sans ChatGPT.
* **Données neurophysiologiques :**
  * Analyse de la puissance spectrale dans la **bande Alpha (8–12 Hz)**, biomarqueur de l'attention sélective, du contrôle exécutif et de l'effort cognitif actif.
  * L'externalisation passive de la réflexion à une IA générative entraîne un effondrement de l'engagement neurophysiologique et l'accumulation d'une **« dette cognitive » (*cognitive debt*)**.
* **Parallèle avec Held & Hein :** L'étudiant qui délègue passivement la synthèse intellectuelle à l'IA subit le même déficit fonctionnel que le chaton passif du carrousel : la privation d'action cognitive active bloque la consolidation mnésique durable.

---

## 9. Modèle des Deux Voies Corticales

David Milner et Melvyn Goodale (1992, 1995) ont révolutionné les neurosciences visuelles en réfutant la division anatomique classique « Où vs Quoi » (Ungerleider & Mishkin, 1982) pour lui substituer une séparation fonctionnelle basée sur la finalité de l'action (Diapo 34) :

```
                                  ┌───────────────────────────────┐
                                  │   Cortex Visuel Primaire V1   │
                                  └───────────────┬───────────────┘
                                                  │
                 ┌────────────────────────────────┴────────────────────────────────┐
                 ▼                                                                 ▼
   VOIE DORSALE (Occipito-pariétale)                                 VOIE VENTRALE (Occipito-temporale)
   « Le Où / Comment » (Vision-for-Action)                           « Le Quoi » (Vision-for-Perception)
  ────────────────────────────────────────                          ───────────────────────────────────────
  • Finalité : Guidage moteur en temps réel.                        • Finalité : Reconnaissance, identification, conscience.
  • Référentiel : Égocentré (centré sur le corps).                  • Référentiel : Allocentré (objets entre eux et scène).
  • Échelle temporelle : Calculs online immédiats (ms).             • Échelle temporelle : Mémoire à long terme, représentations.
  • Sensibilité : INSENSIBLE AUX ILLUSIONS OPTIQUES.                • Sensibilité : VULNÉRABLE AUX ILLUSIONS CONTEXTUELLES.
  • Métrique : Calcul métrique absolu (taille physique réelle).     • Métrique : Estimations comparatives relatives.
```

### L'Expérience Princeps d'Aglioti, DeSouza et Goodale (Current Biology, 1995) (Diapo 33)
* **Titre :** *Size-contrast illusions deceive the eye but not the hand*.
* **Tâche :** Disques 3D insérés dans l'illusion d'Ebbinghaus/Titchener. Les participants doivent soit estimer verbalement la taille du disque central (jugement perceptif conscient), soit tendre la main pour le saisir entre le pouce et l'index (*grasping*).
* **Mesure cinématique :** Enregistrement optoélectronique de l'**Ouverture Maximale de la Pince (*Maximum Grip Aperture* - MGA)** au cours de la phase de vol de la main.
* **Résultat :** Alors que l'estimation verbale consciente est lourdement biaisée par le contraste des disques périphériques (l'œil est trompé), l'ouverture MGA de la pince motrice s'ajuste avec une précision millimétrique à la taille physique objective du disque (la main n'est pas trompée).

---

## 10. Rupture de l'Étanchéité Modulaire

### Jackson & Shaw (2000) — *The Ponzo Illusion Affects Grip-Force But Not Grip-Aperture* (Diapo 35)
* **Protocole :** Objets cylindriques 3D placés sur l'illusion géométrique de Ponzo (perspectives linéaires trompeuses).
* **Double enregistrement cinématique et dynamique :**
  1. **Ouverture de la pince en vol (*Grip-Aperture* / MGA) :** Reste rigoureusement insensible à l'illusion géométrique de Ponzo, confirmant l'imperméabilité de la voie dorsale pour le calibrage spatial.
  2. **Force de serrage exercée après contact (*Grip-Force*) :** Significativement et lourdement **modulée par la taille subjective illusoire de l'objet** ! L'objet perçu visuellement comme plus grand est écrasé avec une force de préhension initiale nettement supérieure.
* **Conséquence théorique majeure :** Les voies dorsale et ventrale ne fonctionnent pas comme des modules hermétiques. L'anticipation cognitive et perceptuelle (voie ventrale : « cet objet paraît grand, donc il est lourd ») est directement injectée dans la commande motrice pour calibrer la force d'écrasement.

---

## 11. Attention Présaccadique & Rôle du FEF

Le cours inverse ensuite le sens du questionnement : **Est-ce que l'action (la motricité) peut moduler la perception ?** (Diapos 36 et 37).

### Deubel & Schneider (1996) — *Saccade target selection and object recognition*
* **Protocole :** Les participants fixent une croix centrale `+`. Ils reçoivent la consigne de préparer une saccade oculaire vers un emplacement spatial précis. Juste avant le déclenchement de la saccade (période présaccadique), un stimulus visuel à discriminer est brièvement présenté, soit sur la cible de la saccade, soit sur une position adjacente.
* **Résultat fondamental :** Les performances de discrimination visuelle sont **obligatoirement et sélectivement maximisées sur la cible spatiale exacte de la saccade**. Il est impossible de découpler l'attention spatiale visuelle de la cible motrice programmée.
* **Neuroanatomie fonctionnelle (Pouget, 2015 ; Neggers, 2007) :** Le Champ Oculaire Frontal (**FEF**) envoie une décharge corollaire qui pré-active sélectivement les populations neuronales du cortex visuel primaire et extrastrié avant même que les yeux ne bougent. La perturbation du FEF par stimulation magnétique transcrânienne (**TMS**) abolit ce couplage attention-motricité.

---

## 12. Action-Specific Perception vs Perception Catégorielle

L'un des apports majeurs de Dave Saint-Amour concerne la distinction conceptuelle fine entre l'approche motrice incarnée et la psycholinguistique symbolique (Diapo 38) :

### A. Dennis R. Proffitt — Perception Spécifique à l'Action (*Action-Specific Perception*)
* **Thèse :** La métrique spatiale perçue par l'œil est étalonnée sur les capacités biomécaniques, l'état physiologique et la performance motrice actuelle de l'agent.
* **Preuves expérimentales :**
  * **Baseball (Witt, Linkenauger, Bakdash & Proffitt, 2005) :** Les joueurs en réussite motrice (haute moyenne au bâton) perçoivent la balle de baseball comme physiquement **plus grosse** que les frappeurs en difficulté.
  * **Golf (Witt et al., 2008) :** Les golfeurs réussissant leurs putts perçoivent le trou de golf comme étant nettement **plus large**.
  * **Pente de la colline (*Hill slant*, Bhalla & Proffitt, 1999) :** Une colline paraît plus abrupte lorsqu'on est fatigué, âgé ou porteur d'un sac lourd.
  * **Usage d'outils (*Tool use*, Witt et al., 2005) :** Tenir un bâton permettant d'atteindre un objet distant compresse l'espace : l'objet est jugé plus proche.

### B. Confrontation Théorique Obligatoire : Proffitt vs Stevan Harnad
* **Perception Catégorielle (Stevan Harnad) :** Phénomène où l'apprentissage d'une **étiquette symbolique, conceptuelle ou linguistique discrète** altère la discriminabilité sensorielle (compression intra-catégorielle et étirement inter-catégoriel aux frontières, ex: phonèmes /b/ vs /d/).
* **Perception Spécifique à l'Action (Dennis Proffitt) :** Phénomène **purement sensorimoteur, analogique, continu et non symbolique**. Aucun mot, aucune étiquette n'intervient : c'est l'efficience motrice corporelle et le coût bioénergétique qui recalibrent la taille visuelle perçue.
* **Métaphore de classe :** L'effet « histoire de pêche » (*« Mon poisson était gros comme ça ! »*) : La réussite motrice corporelle gonfle subjectivement la métrique de la cible.

---

## 13. Analyse de l'Article Obligatoire : Bosco et al.

L'article de revue de **Bosco, Sanz Diez, Filippini et Fattori (2023)** (*Frontiers in Systems Neuroscience*) et l'étude princeps de **Bosco, Daniele & Fattori (2017)** (*Journal of Vision*) constituent le cœur de la lecture obligatoire de la Séance 1 (Diapos 39 et 40).

### A. Bosco, Daniele & Fattori (Journal of Vision, 2017)
* **Tâche :** Comparaison de l'effet d'un geste d'atteinte simple (*reaching*) vs un geste de préhension fine (*grasping*) sur le jugement de taille d'un objet.
* **Deux résultats capitaux :**
  1. L'action de *grasping* réduit la taille perçue de l'objet de façon significativement plus marquée que le simple geste d'atteinte.
  2. **L'EFFET PRÉ-MOTEUR :** Le simple fait de **savoir à l'avance** quelle action motrice devra être exécutée (*reaching* vs *grasping*) suffit à modifier le jugement perceptif de taille **avant même le déclenchement physique du moindre mouvement**.

### B. Le Cadre Théorique Intégrateur : La Théorie du Codage des Événements (TEC)
* **Hommel, Müsseler, Aschersleben & Prinz (2001) :** Stimuli perceptifs et actions motrices sont encodés sous un **format représentationnel commun** fait de faisceaux de traits (*feature codes* : orientation, taille, position, couleur).
* **Règle d'or de la TEC :**
  * **Facilitation :** Si la planification motrice partage des traits congruents avec le but perceptif, le traitement est accéléré (*priming*).
  * **Interférence (*Share-code weighting*) :** Si l'action motrice et le stimulus se disputent le même code partagé dans des tâches indépendantes, la planification motrice monopolise le code commun et provoque un retard ou une cécité perceptive temporaire.

### C. Matrice Triangulaire de Bosco et al. (2023) : 3 Effecteurs × 2 Phases

#### 1. Domaine Oculomoteur (L'Œil)
* **Planification :**
  * *Ancrage du regard (*Gaze Anchoring*, Neggers & Bekkering, 2000) :* Pendant un geste d'atteinte manuel, les yeux se verrouillent sur la cible et toute saccade vers un nouveau stimulus est inhibée jusqu'au contact de la main.
  * *Latences (Bekkering, 1994) :* En tâche simultanée œil-main vers une même cible, la latence de la saccade oculaire augmente considérablement, tandis que la latence manuelle reste stable.
  * *Anticipation :* La fixation oculaire devance la marche motrice de **0,8 à 1,1 seconde** (Patla & Vickers, 2003).
* **Exécution & Post-Action :**
  * *Adaptation saccadique et taille (Bosco et al., 2015) :* Le changement trans-saccadique de taille modifie l'amplitude de la saccade et la taille perçue.
  * *Découplage capital (Bosco et al., 2020) :* En modifiant la taille d'une **barre verticale** lors de **saccades horizontales**, la taille perçue change sans aucune modification d'amplitude de la saccade oculaire (preuve d'une prédiction trans-saccadique indépendante de l'adaptation motrice périphérique).
  * *Compression périsaccadique de l'espace et du temps (Ross, 1997 ; Morrone, 2005).*

#### 2. Domaine Manuel (La Main)
* **Planification :**
  * *Amorçage dimensionnel sélectif (Bekkering & Neggers, 2002 ; Gutteling, 2011) :* Planifier une préhension (*grasping*) rehausse sélectivement la sensibilité à l'**orientation** et à la **taille** de l'objet, sans effet sur la couleur ou la luminance. À l'inverse, l'atteinte (*reaching*) sensibilise à la **position spatiale** et à la **luminance** (Fagioli et al., 2007).
  * *Oscillations de sensibilité au contraste (Tomassini et al., 2015) :* Des modulations périodiques dans la bande thêta modulent le cortex visuel primaire V1 environ **500 ms avant le début du mouvement manuel**.
* **Exécution & Post-Action :**
  * *Perturbations en vol (Sanz Diez et al., 2022) :* Si l'objet s'allonge de 33 % en cours de vol de préhension, il est perçu post-action comme significativement plus petit ; s'il rétrécit de 33 %, aucun effet de recalibration n'est observé.
  * *Illusion Taille-Poids (SWI de Charpentier, 1891 ; Flanagan & Beltzner, 2000) :* Entre deux objets de masse identique mais de volume différent, le plus petit paraît toujours plus lourd. La voie motrice adapte rapidement la force de serrage réelle, mais l'illusion perceptive consciente (voie cognitive) demeure indestructible.

#### 3. Domaine Locomoteur (La Jambe — Espace Extrapersonnel)
* **Planification :** L'intention active de marcher vers un objet le fait paraître significativement plus proche (Fini et al., 2015) et étend les frontières de l'espace péripersonnel (Noel et al., 2015).
* **Exécution & Post-Action :**
  * *Marche à l'aveugle et déphasage du flux optique (*Blind Walking*, Rieser et al., 1995) :* Après avoir marché sur un tapis avec un flux virtuel déphasé, si le flux était **plus rapide** que la marche normale, le sujet s'arrête **avant** la cible lors du test à l'aveugle (**sous-estimation de la distance / *undershoot***) ; si le flux était plus lent, il dépasse la cible (**surestimation / *overshoot***).
  * *Rescaling spatial global (Kelly et al., 2013) :* L'interaction motrice de marche réétalonne globalement la taille perçue des objets distants en vertu de l'invariance taille-distance.

---

## 14. Amorce Prospective : Reverse Hierarchy Theory

En clôture de cours (Diapo 41), le professeur introduit la théorie de la hiérarchie visuelle inversée (*Reverse Hierarchy Theory* - RHT, Hochstein & Ahissar, 2002) :

* **La « Vision at a glance » (Vision au premier coup d'œil) :**
  * Première impression perceptive consciente.
  * Elle émerge directement au sommet de la hiérarchie corticale (aires visuelles supérieures à larges champs récepteurs).
  * Traitement holistique et rapide saisissant la globalité et le sens général de la scène (*gist*), sans résolution des détails fins.
* **La « Vision with scrutiny » (Vision sous examen attentif) :**
  * Si la tâche exige une précision métrique fine ou en présence d'une ambiguïté perceptive, le système nerveux déploie des connexions rétrogrades descendantes (*top-down feedback*).
  * L'attention motrice et exécutive revisite alors les aires primaires (V1, V2) pour inspecter les contours nets et les hautes fréquences spatiales.
* **Pont avec le fonctionnalisme :** Confirme que la conscience visuelle n'est pas construite de bas en haut brique par brique, mais part d'une hypothèse descendante globale immédiatement prête pour l'action.

---
*Document pédagogique certifié conforme aux sources textuelles et orales officielles de la Séance 1 du cours PSY9613 (Dave Saint-Amour & Pierre Poirier).*
