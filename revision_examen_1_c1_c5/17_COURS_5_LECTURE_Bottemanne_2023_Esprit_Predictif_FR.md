# L'esprit prédictif : introduction à la théorie du cerveau bayésien (Bottemanne, Longuet & Gauld, 2022) — Texte Intégral & Synthèse Orientée Cours (Séance 6)

> **Synthèse Orientée Cours (Alignée sur le Cours du 19 oct. 2026 `notes_seance_05_2026-10-19.md`, `PSY9613-01_GOLD_AGY`, `PSY9613-03_GOLD_AGY` et `Quelques explications sur les textes.txt`)**
> *Ce résumé extrait l'ensemble des concepts fondamentaux de la lecture obligatoire en français de la Séance 6 à la lumière des explications données par les Prs Pierre Poirier et Dave Saint-Amour en classe et sur Moodle :*
>
> 1. **Rôle du texte selon les professeurs (`Quelques explications sur les textes.txt`) :**
>    - Cet article de revue en français constitue la **porte d'entrée conceptuelle obligatoire** sur la théorie du **cerveau bayésien** et du **traitement prédictif (*Predictive Processing*, PP)**, complété par l'article neurophysiologique obligatoire de **de Lange, Heilbron & Kok (2018)** et par la formalisation mathématique recommandée de **Sprevak & Smith (2023)** (modèles POMDP, énergie libre variationnelle et inférence active).
> 2. **Racines historiques soulignées en classe (`PSY9613-01_GOLD_AGY` `[02:05:09]` & Cours du 19 oct. Diapos 2–4) — De Helmholtz, James et Hinton à Friston :**
>    - L'idée que la perception n'est pas une réception passive mais une **prédiction active** remonte aux **« inférences inconscientes » (*Unbewusster Schluss*) de Hermann von Helmholtz (1860)**, à **William James** et à l'épistémologie kantienne (*a priori*).
>    - Comme l'a détaillé le Pierre Poirier en classe (Diapos 2 à 4), la formulation contemporaine est née de la rencontre à Londres (UCL) entre **Geoffrey Hinton** (machines de Helmholtz, *product of experts*) et **Karl Friston** (principe de l'énergie libre variationnelle, 2005), ainsi que du modèle de codage prédictif visuel de **Rao & Ballard (1999)**.
>    - Sur le plan formel, la théorie hybride trois piliers : (a) le **théorème de Bayes (1763)** et Laplace, (b) la **théorie de l'information de Shannon (1948)** (entropie comme mesure de l'incertitude ou de l'imprédictibilité du signal, vue à la Séance 3 `[00:52:00]`), et (c) le **principe de l'énergie libre (*Free Energy Principle*) de Friston**.
> 3. **Mécanisme fondamental : Croyances (*priors*), Prédictions descendantes (*top-down*) et Erreurs de prédiction ascendantes (*bottom-up*) :**
>    - **Inversion du modèle classique :** Contrairement au modèle purement ascendant (*bottom-up*), le cerveau encode un **modèle génératif hiérarchique** du monde sous forme de distributions de probabilités appelées **croyances antérieures (*priors* / *a priori*)**.
>    - **Flux descendant (*top-down*, flèches vertes, Fig. 1 et 2) :** Les niveaux supérieurs de la hiérarchie corticale envoient continuellement des **prédictions** vers les niveaux sensoriels inférieurs sur les entrées attendues.
>    - **Flux ascendant (*bottom-up*, flèches violettes) :** Les niveaux inférieurs comparent ces prédictions aux entrées sensorielles réelles (**vraisemblance / *likelihood***) et ne font remonter vers le haut de la hiérarchie **que le signal résiduel non expliqué : l'erreur de prédiction (*prediction error*)**, mesurée mathématiquement par la **divergence de Kullback-Leibler ($D_{KL}$)**.
>    - **Pondération par la précision (*precision-weighting*) :** L'impact d'une erreur de prédiction sur la **mise à jour des croyances (*belief updating* $\rightarrow$ croyance postérieure / *posterior*)** dépend du rapport entre la **précision (inverse de la variance, $\Pi = 1/\sigma^2$)** de l'entrée sensorielle et celle de la croyance antérieure. **L'attention est définie en classe comme le processus d'optimisation des estimations de précision** (Diapos 64–67 de Pierre Poirier).
> 4. **Unification des grandes fonctions cognitives et exemples du cours du 19 octobre 2026 (Sections 3 à 6) :**
>    - **Les 3 niveaux de Marr et le calcul bayésien (Diapos 5 à 25 de Pierre Poirier) :** Le cerveau bayésien s'analyse au *niveau computationnel* (minimiser l'énergie libre variationnelle / doctrine probabiliste), au *niveau algorithmique* (inférence bayésienne illustrée par l'extrait du film *Cloverfield* et le tableau de Jakob Hohwy comparant le produit $P(h_i)\times P(e\mid h_i)$ des hypothèses $h_1\dots h_7$, ainsi que la **Tour de Dennett** sur l'origine phylogénétique et ontogénétique des *priors* : créatures darwiniennes, skinnériennes, poppériennes et grégoriennes), et au *niveau de l'implémentation* (colonnes corticales laminaires).
>    - **Perception comme « hallucination contrôlée » et intégration multisensorielle (Section 4 & Diapos de Dave Saint-Amour) :**
>      * **Rivalité binoculaire (Section 4.2 & Hohwy, Roepstorff & Frith, 2008) :** Lorsqu'une maison et un visage sont présentés séparément à chaque œil, l'alternance perceptive consciente résulte de l'accumulation de l'erreur de prédiction de l'image non sélectionnée qui force périodiquement le changement d'hypothèse.
>      * **Illusion de la main de caoutchouc (*Rubber Hand Illusion*) et Illusion du ventriloque :** Fusion bayésienne multisensorielle pondérée par la précision ($\hat{S} = w_V S_V + w_A S_A$, où la vision domine spatialement l'audition car $\sigma_V^2 \ll \sigma_A^2$).
>    - **Action et Inférence active (Section 5 & Exemple de la tasse de café) :** Pour minimiser l'erreur de prédiction, le cerveau dispose de **deux stratégies complémentaires** : (1) **changer ses croyances** pour les adapter au monde (*codage prédictif perceptif*), ou (2) **agir sur le monde** (mouvements moteurs, réflexes proprioceptifs) pour rendre les entrées sensorielles conformes aux prédictions (*inférence active*).
>    - **Intéroception, Émotion et Psychiatrie computationnelle (Section 6 — Autisme / HIPPEA & Schizophrénie) :** Tout comme le cerveau prédit le monde extérieur (*extéroception*), il prédit l'état interne du corps (*intéroception* : rythme cardiaque, viscères, homéostasie ; voir Séance 3 `[02:47:50]`). En psychopathologie, le modèle **HIPPEA** (*High, Inflexible Precision of Prediction Errors in Autism*, relié par Pierre Poirier à la *surfonction perceptive* de Laurent Mottron) explique l'autisme par une précision inflexiblement élevée accordée aux erreurs sensorielles locales, tandis que la psychose reflète une altération inverse de la pondération des *priors* et des erreurs.
> 5. **Limites épistémologiques et critiques à connaître pour l'examen (Section 7) :**
>    - **La « chambre noire » (*Dark Room Problem*) :** Si l'unique but du cerveau était de minimiser l'erreur de prédiction, pourquoi ne restons-nous pas immobiles dans une pièce sombre ? Réponse : nos *priors* biologiques et évolutifs incluent l'exploration et le maintien de l'homéostasie vitale.
>    - **Glissement sémantique et paradoxe de la représentation (Sections 7.1 et 7.2) :** Ne pas confondre une « croyance » mathématique (une distribution de probabilité sous-personnelle en neurosciences computationnelles) avec une croyance consciente ou propositionnelle en psychologie populaire, ni supposer qu'un modèle bayésien au niveau computationnel de Marr implique nécessairement que des neurones individuels calculent littéralement le théorème de Bayes.

---

<!-- ======================================================================= -->
<!-- PAGE 1                                                                  -->
<!-- ======================================================================= -->

L’Encéphale 48 (2022) 436–444

Disponible en ligne sur

ScienceDirect www.sciencedirect.com

Revue de la littérature

L’esprit predictif : introduction à la théorie du cerveau bayésien

The predictive mind: An introduction to Bayesian Brain Theory

H. Bottemanne a,b,c,∗, Y. Longuet d, C. Gauld e,f

a Paris Brain Institute – Institut du Cerveau (ICM), Sorbonne university/CNRS/Inserm, Paris, France b Sorbonne University, Department of Philosophy, SND research unit, UMR 8011, CNRS, Paris, France c Department of psychiatry, Pitié-Salpêtrière hospital, DMU Neuroscience, Sorbonne university, Assistance publique–Hôpitaux de Paris (AP–HP), Paris, France d Department

of psychiatry, Claude Bernard Lyon 1 university, 69000 Lyon, France e Department of psychiatry, university of Grenoble, 38000 Grenoble, France f IHPST UMR 8590, Sorbonne university, Paris 1, France

i n f o a r t i c l e

Historique de l’article

: Reçu le 14 juillet 2021 Accepté

le 30 septembre 2021 Disponible

sur Internet le 7 janvier 2022

Mots clés : Traitement

prédictif Codage

prédictif Cerveau

bayésien Croyance Bayésianisme Neurosciences

computationnelles Mise

à jour des croyances Interoception

r é

s u m é

La question du fonctionnement de l’esprit est au cœur des sciences cognitives. Ces dernières visent à comprendre

et à expliquer les processus complexes sous-tendant la perception, la prise de décision et

l’apprentissage, trois domaines fondamentaux de la cognition. La théorie du cerveau bayésien, une approche

computationnelle issue des principes du traitement prédictif (PP, Predictive Processing), propose une

formulation mécanistique et mathématique de ces processus cognitifs. Cette théorie suppose que le

cerveau encode des croyances (états probabilistes) pour générer des prédictions à propos des entrées sensorielles,

puis utilise les erreurs de prédictions pour mettre à jour ses croyances. Dans cet article, nous

présentons une introduction aux principes fondamentaux de la théorie du cerveau bayésien. Nous montrons

comment cette théorie innovante hybride des concepts hérités de la philosophie de l’esprit et

les données expérimentales issues des neurosciences, et comment elle traduit des processus cognitifs

complexes comme la perception, l’action, l’émotion, et la croyance, ou encore la symptomatologie psychiatrique.

© 2021 L’Encéphale, Paris.

Keywords: Predictive

processing Predictive

coding Bayesian

brain Belief Bayesianism Computational

neuroscience Computational

psychiatry Belief

updating Interoception

a b s t r a c t

The question of how the mind works is at the heart of cognitive science. It aims to understand and explain the

complex processes underlying perception, decision-making and learning, three fundamental areas of cognition. Bayesian Brain Theory, a computational approach derived from the principles of Predictive Processing

(PP), offers a mechanistic and mathematical formulation of these cognitive processes. This theory

assumes that the brain encodes beliefs (probabilistic states) to generate predictions about sensory

input, then uses prediction errors to update its beliefs. In this paper, we present an introduction to the

fundamentals of Bayesian Brain Theory. We show how this innovative theory hybridizes concepts inherited

from the philosophy of mind and experimental data from neuroscience, and how it translates

complex cognitive processes such as perception, action, emotion, or belief, or even the psychiatric symptomatology.

©

2021 L’Encéphale, Paris.

∗Auteur correspondant. Adresse

e-mail : hugo.bottemanne@aphp.fr (H. Bottemanne).

## 1. Introduction

La théorie du cerveau bayésien (Bayesian Brain theory) est aujourd’hui l’une des approches les plus populaires en neurosciences pour représenter les processus complexes sous-tendant la perception, la prise de décision et l’apprentissage, trois domaines

https://doi.org/10.1016/j.encep.2021.09.011 0013-7006/© 2021 L’Encéphale, Paris.

<!-- ======================================================================= -->
<!-- PAGE 2                                                                  -->
<!-- ======================================================================= -->

fondamentaux de la cognition [1]. Cette théorie computationnelle issue des principes du traitement prédictif (PP – Predictive Processing [2], parfois aussi désignée codage prédictif, PC – Predictive Coding), propose une formulation mécanistique et mathématique de ces processus cognitifs [3]. Selon cette théorie, le cerveau utilise des croyances afin de générer des prédictions (aussi nommé anticipation, ou attentes) pour prédire les entrées sensorielles que le corps va expérimenter [4], ou pour mettre en place des stratégies comportementales (i.e., décisions, mouvements moteurs) [5,6]. Ces croyances sont ensuite mises à jour en fonction des erreurs de prédiction provoquées par les entrées sensorielles, permettant au cerveau de s’adapter aux changements dans son environnement. La formalisation de la théorie du traitement prédictif à travers le prisme du bayésianisme, une théorie probabiliste héritée du XIXe siècle, constitue le cœur de la théorie du cerveau bayésien [7]. Le bayésianisme propose une formulation mathématique permettant de calculer la vraisemblance d’un événement (i.e., une entrée sensorielle) en fonction d’informations à propos de cet évènement et de croyances préalables. Ce calcul de vraisemblance peut ensuite être utilisé pour modifier les croyances préalables, au cours du processus de mise à jour des croyances. Appliquée au traitement

prédictif, la théorie bayésienne permet ainsi de comprendre comment le cerveau génère des inférences afin de déterminer la probabilité des informations sensorielles qu’il va recevoir au fur et à mesure de ses expériences, puis comment il modifie ses croyances en fonction des informations sensorielles perçues. Cette application mathématique bayésienne des principes du traitement prédictif permet aussi de générer des modèles computationnels [8]. Ces modèles désignent des représentations fondées sur des formulations mécanistiques et mathématiques des états mentaux et du comportement humain [9], pouvant faire l’objet de simulations ou être confrontées aux données expérimentales chez l’animal et chez l’homme [10]. Les modèles computationnels ont été utilisés pour représenter des processus comme la perception visuelle [11], la prise de décision [12], l’apprentissage probabiliste [13], la reconnaissance de l’action [14], la synesthésie [15], la focalisation de l’attention [16], les états altérés de conscience [17], ou encore l’apprentissage du langage [18]. Ces modèles ont aussi été utilisés en psychiatrie [19] pour représenter les mécanismes associés à l’émergence d’idées délirantes [20] et d’hallucinations dans les troubles psychotiques [21], aux variations d’humeur dans les troubles bipolaires [22], ou encore aux défauts d’inférence dans les troubles du spectre de l’autisme [23]. Du fait de l’importance croissante de la théorie du cerveau bayésien en sciences cognitives, il semble nécessaire de connaître et comprendre ses principes fondateurs. Dans cet article, nous présentons la théorie du cerveau bayésien en détaillant successivement : l’origine de la théorie en philosophie de l’esprit et en sciences cognitives, son cœur théorique et ses grands principes, des exemples de son application aux processus cognitifs et aux symptômes psychiatriques, et enfin les limites de son application en sciences cognitives. Nous montrons enfin comment cette théorie innovante hybride des concepts hérités de la philosophie de l’esprit et les données expérimentales issues des neurosciences, et comment elle traduit des processus cognitifs comme la perception, l’action, l’émotion, et la croyance, ou encore la symptomatologie retrouvée dans les troubles psychiatriques.

## 2. Un héritage philosophique et scientifique

### 2.1. Les fondements scientifiques

La théorie du traitement prédictif a émergé à partir d’un héritage

hybride, philosophique et scientifique. Bien que l’on retrouve la notion de prédiction dans les travaux de philosophes comme

Emmanuel Kant, Charles Sanders Peirce, ou William James [2,24], la première formulation du paradigme prédictif est historiquement associée aux travaux du physiologiste prussien Hermann von Helmholtz [25]. Celui-ci suggère que notre cerveau génère des inférences inconscientes prédisant l’état de son environnement immédiat, et évoluant en fonction de la réalité perçue par les organes sensoriels. Pour Helmholtz, ces prédictions sont équivalentes à une simulation mathématique du monde générée par le cerveau, témoignant de l’écart manifeste entre la perception subjective et la réalité objective. Sans faire d’hypothèses précises sur l’implémentation cérébrale des processus prédictifs, sa conception mécanistique constitue l’un des premiers fondements de la théorie du traitement prédictif. Ces fondements théoriques ont rapidement trouvé leur place au sein des sciences cognitives naissantes, s’hybridant progressivement avec les premiers modèles physiologiques de l’activité neuronale. À la suite des travaux menés par des neurophysiologistes comme Louis Lapicque sur la grenouille [26] ou Alan Hodgkin et Andrew Huxley sur le potentiel d’action de l’axone du calamar [27], le neuroscientifique Wilfrid Rall démontre que les arborisations dendritiques à l’extrémité des neurones modifient le traitement

synaptique et le transfert d’information électrique [28]. Ces découvertes du début au milieu du XXe siècle révolutionnent la compréhension du rôle des neurones en montrant que l’activité cérébrale est générée par le traitement automatisé de l’information au sein de réseaux neuronaux, et que les connexions synaptiques déterminent le type de message transmis par l’activité cérébrale.

### 2.2. De

la neurophysiologie à la cognition

Ces recherches

focalisées sur l’activité cérébrale ont ensuite été utilisées pour comprendre la manière dont le cerveau génère des états mentaux. Les travaux du psychologue Donald Hebb vont faire la jonction entre les théories physiologiques et psychologiques de la cognition : s’appuyant sur les découvertes en neurophysiologie de son époque, il suggère que les états mentaux sont encodés dans le cerveau par l’activation conjointe de réseaux de neurones connectés les uns avec les autres (hypothèse de la connexion hebbienne), et que ces neurones peuvent renforcer ou réduire leurs connexions en fonction des informations transmises (hypothèse de l’apprentissage hebbien) [29]. Ces deux hypothèses posent les fondements de la théorie du traitement prédictif en montrant que les états mentaux résultent de l’activation de réseaux de neurones, et que la modification de la connectivité entre ces réseaux permet de modifier les états mentaux. L’hypothèse hebbienne éclaire également les processus d’apprentissage, l’un des fondements de la psychologie expérimentale. S’appuyant sur cet héritage, les premiers modèles d’apprentissage par renforcement (RL – Reinforcement Learning) suggèrent que le cerveau génère des attentes de récompenses ou de punitions, et que l’écart entre les attentes (e.g. d’une récompense) et les résultats (e.g. perception d’une punition à la place de la récompense attendue) produit une erreur de prédiction utilisée par le cerveau pour corriger les attentes [13]. Appliqués aux sciences cognitives, ces modèles sont alors utilisés pour comprendre les phénomènes de plasticité cérébrale, désignant la

modification de la connectivité entre différents réseaux en fonction des expériences, et les processus de prise de décision, désignant la manière dont l’organisme réalise des actions en fonction de la balance de récompenses et de punitions attendues dans son environnement immédiat [30]. Cette formulation fait ainsi

la jonction entre la connectivité cérébrale et des processus cognitifs comme l’apprentissage, la prise de décision, et l’action [12].

437

<!-- ======================================================================= -->
<!-- PAGE 3                                                                  -->
<!-- ======================================================================= -->

> **Fig. 1. Schéma illustrant les fondementaux de la théorie du cerveau bayésien. À gauche, exemple d’un modèle prototypique du traitement prédictif au sein d’un réseau schématique avec quatre neurones : au sein de ce modèle, les informations montantes (flèches bleu) issues du traitement des signaux sensoriels aux niveaux inférieurs sont communiquées**

aux neurones des niveaux supérieurs dans la hiérarchie corticale, et les prédictions descendantes (flèches verte) issues des croyances provenant de niveaux supérieurs

sont communiquées aux neurones des niveaux inférieurs. Ces relations sont ici représentées au niveau cérébral en termes de connexions synaptiques. À droite : dans

le

théorème de Bayes, la probabilité d’un événement, ou croyance postérieure (distribution en rose) est prédite selon sa vraisemblance, ou fonction de vraisemblance (distribution en bleu) et les croyances antérieures associées à cet événement, ou prior (distribution en vert). Dans un environnement dynamique, l’évolution des croyances postérieures

est ainsi dépendante du type d’information sensorielle nouvelle acquises, et du type de croyance antérieure utilisée pour réaliser l’inférence bayésienne.

### 2.3. L’émergence du cerveau bayésien

C’est sur ce socle conceptuel que s’est développée la théorie du cerveau bayésien, profitant de la formalisation mathématique issue du bayésianisme. Le bayésianisme est initialement une théorie philosophique et mathématique issue des travaux du révérend Thomas Bayes, formalisée par le mathématicien Frank Ramsey au XXe siècle. Elle repose sur une équation simple qui permet de calculer la vraisemblance d’une nouvelle information en fonction de croyances préalables (estimation probabiliste), puis de modifier ces croyances antérieures en fonction des nouvelles informations (Fig. 1). Le succès de la théorie bayésienne réside dans sa capacité à formaliser ces processus quel que soit le domaine sur lequel portent les estimations probabilistes, allant d’un gradient d’ombre sur une image en deux dimensions à une attente de récompense monétaire au cours d’une loterie. Appliquée aux sciences cognitives, la théorie du cerveau bayésien est une formulation bayésienne de la théorie du traitement prédictif. Elle est alors en mesure de représenter conjointement la manière dont le cerveau traite l’information (théorie du fonctionnement cognitif) [31], et la manière dont les neurones codent ce traitement de l’information (théorie du fonctionnement neuronal) [32]. Le premier volet rend compte de la manière dont le cerveau

réalise des inférences afin de déterminer la probabilité des informations sensorielles reçues, puis modifie ses croyances en fonction du décalage entre ces prédictions et les informations inférées [31]. Le second volet représente la manière dont les neurones se transmettent l’information au sein des réseaux sous la forme d’une équation bayésienne, assimilant le bayésianisme à la neurophysiologie cérébrale [33]. Conjointement, ces théories du fonctionnement cognitif et du fonctionnement neuronal constituent la théorie du cerveau bayésien.

## 3. Principes généraux du traitement prédictif

### 3.1. Concepts fondamentaux

La théorie bayésienne du traitement prédictif implique deux concepts fondamentaux : les concepts de croyance, et de hiérarchie [34] ; et quatre notions dérivées de ces concepts : la prédiction, l’erreur de prédiction, la mise à jour et la précision [2]. Ces différents concepts, en particulier celui de croyance, sont tirés d’un héritage philosophique et scientifique hétérogène, et leur application au sein de la théorie du traitement prédictif fait appel à une représentation opératoire, divergente de leur formulation originale [35]. Chacune de ces notions peut ainsi avoir un sens spécifique au sein de la théorie prédictive, parfois très différent de celui de la psychologie expérimentale ou de la psychologie de sens commun (folk psychology).

La croyance, premier concept socle, est représentée comme une estimation probabiliste d’un état du monde, pouvant être par exemple un événement ou une suite d’événements [36]. Chaque croyance constitue une fraction du modèle probabiliste de l’environnement que le cerveau encode pour prédire l’état actuel du monde et son évolution. Ce modèle probabiliste constitué de l’ensemble des croyances contient conjointement une estimation statistique

de la probabilité de plusieurs événements, des variables causales qui influencent les variations de ces estimations, et de la volatilité de ces variations [2]. Contrairement à la formulation conventionnelle de la croyance en psychologie, ces modèles probabilistes ne sont pas nécessairement conscients [37]. La hiérarchie, deuxième concept socle, suppose que les croyances sont organisées selon une hiérarchie spécifique, isomorphe à la structure corticale du cerveau. En son sein, les couches de croyances plus profondes encodent des estimations statistiques

438

<!-- ======================================================================= -->
<!-- PAGE 4                                                                  -->
<!-- ======================================================================= -->

> **Fig. 2. Exemple d’une représentation de modèle bayésien hiérarchique. La théorie du cerveau bayésien suggère que les croyances probabilistes sont utilisées pour générer des prédictions**

à propos des informations sensorielles entrantes, puis que le décalage entre ces prédictions et la réalité génère des erreurs de prédiction qui permettent de mettre à

jour les croyances. Ces croyances sont également utilisées pour définir les actions réalisées par l’organisme, et les actions modifient en retour les informations sensorielles qu’il

expérimente. Dans le

contexte de la vision, des informations sensorielles visuelles (à gauche) sont ainsi traitées par le cerveau à l’aide d’un modèle hiérarchique de croyances (à droite). Dans ce modèle hiérarchique, le cerveau utilise des croyances probabilistes (X1, X2, X3, X4) pour générer des prédictions à propos des entrées sensorielles (flèches

vertes descendantes). Ces croyances sont organisées de manière hiérarchique, allant du niveau le plus élémentaire (prédiction de la couleur bleue) à des niveaux plus

élevés (prédiction de la mer). Le décalage entre ces prédictions descendantes et les entrées sensorielles visuelles génère des erreurs de prédiction, qui sont utilisées pour mettre

à jour les croyances (flèches bleues montantes). La précision (pointillés jaunes) des prédictions et des erreurs de prédiction influence la mise à jour des croyances : elle

permet de donner plus

ou moins d’importance aux données sensorielles (montantes) ou aux prédictions (descendantes), selon leur précision respective. Au cours de ce processus, la perception visuelle est ainsi produite en fonction de l’équilibre des prédictions, erreurs de prédiction, et mise à jour au sein de la hiérarchie de croyance.

d’événements

abstraits, avec un grain temporel et spatial étendu, tandis

que des couches de croyances plus superficielles sont dévolues à des estimations concernant des événements singuliers, sur une

plage temporelle et spatiale limitée [38]. Bien qu’il existe plusieurs hypothèses concurrentes à propos de l’implémentation neurologique

de cette hiérarchie, celle-ci est généralement associée à la balance d’excitation-inhibition maintenue par l’activité synaptique de colonnes de neurones pyramidaux (glutamatergiques) et d’interneurones inhibiteurs (GABAergiques) disséminées dans les couches superficielles et profondes du cortex [4,39,40].

### 3.2. La mise à jour des croyances

Les quatre principes dérivés des notions de croyance et de hiérarchie (prédiction, erreur de prédiction, mise à jour, précision) peuvent être compris au travers de la perception, i.e. la manière dont le cerveau traite les informations sensorielles [41]. En effet, le traitement prédictif suppose que les croyances hiérarchiques sont utilisées pour générer des prédictions à propos de nouvelles entrées sensorielles, et que le cerveau prédit constamment les entrées sensorielles à partir de sa hiérarchie de croyances [42]. Sur le plan hiérarchique, ces prédictions sont équivalentes à des hypothèses d’un niveau N sur les informations (ou l’activité cérébrale, selon que l’on se place sur le plan computationnel ou neurologique) portées par le niveau N−1 dans la hiérarchie [2]. À chaque degré de la hiérarchie de croyance, les hypothèses de niveau supérieur sont utilisées pour prédire les informations de niveau inférieur. Cette hiérarchie de croyances fonctionne ainsi comme une hiérarchie d’hypothèses sur l’environnement. Dans cette hiérarchie, le traitement descendant de l’information est confronté à un traitement montant de l’information, constitué par les entrées sensorielles. Le décalage (ou l’écart, ou la discordance) entre les prédictions (descendantes) d’un niveau N et les entrées sensorielles (montantes) d’un niveau N−1 provoquent des erreurs de prédiction. Celles-ci remontent dans la hiérarchie et permettent

de mettre à jour les croyances, en suivant les principes de l’inférence bayésienne. Ce traitement ascendant, issu des

erreurs de prédictions, correspond à l’intégration des entrées sensorielles

dans le réseau de croyances. Cette intégration permet alors la génération d’hypothèses sur le monde de moins en moins abstraites, nourries par l’expérience sensorielle. Avec la mise à jour des croyances, le cerveau peut expliquer le décalage entre ses prédictions

et les entrées sensorielles qu’il expérimente au fil de ses expériences (Fig. 2).

### 3.3. Croyances de second ordre

Par ailleurs, la prédiction et la mise à jour des croyances sont dépendantes d’une autre couche de croyances probabilistes, dites de second ordre [43]. Ces croyances de second ordre sont désignées comme des métacroyances, hyperpriors, ou hyperparamètres. Celles-ci encodent l’estimation de la précision (aussi appelée confiance) des prédictions descendantes et des erreurs de prédictions montantes. Des prédictions (descendantes) avec un haut degré de précision exerceront un pouvoir prédictif plus important : ces prédictions seront plus difficiles à mettre à jour que des prédictions avec un faible degré de précision. Inversement, des erreurs de prédiction (montantes) avec un haut degré de précision provoqueront une mise à jour des prédictions plus importante que des erreurs de prédiction avec un faible degré de précision. Le système de précision permet au cerveau de coder des variables statistiques comme la volatilité de l’environnement dans lequel il évolue. En effet, si l’environnement est volatil, c’est-àdire, particulièrement changeant, la précision sensorielle va être moins importante, réduisant le taux d’apprentissage bayésien et par conséquent la vitesse d’apprentissage au fil des expériences. Cette situation contraste avec un environnement stable au cours duquel la précision sensorielle est haute, favorisant la mise à jour des croyances à partir des erreurs de prédiction générées. Ce mécanisme permet d’éviter l’apprentissage d’un « bruit » (la composante non désirée d’un signal au cours du traitement de l’information) en permettant au cerveau de moins prendre en compte les informations issues d’un environnement volatil.

439

<!-- ======================================================================= -->
<!-- PAGE 5                                                                  -->
<!-- ======================================================================= -->

## 4. La perception, une prédiction

### 4.1. Perception visuelle

La perception a été historiquement au cœur des premières applications de la théorie bayésienne du traitement prédictif au fonctionnement cérébral, en particulier pour le traitement de l’information visuelle [11]. Les premiers travaux réalisés en 1999 par les neuroscientifiques Rao & Ballard ont ainsi montré que certaines aires visuelles de niveau supérieur (correspondant par exemple au traitement des formes ou des mouvements) font des prédictions sur l’activité neuronale des aires visuelles primaires, activées par les signaux sensoriels. En d’autres termes, lors de l’exposition à des stimuli visuels, un réseau hiérarchique de neurones s’active pour anticiper les images qui vont parvenir aux zones visuelles primaires. Cette activité de prédiction témoigne du fait que le traitement de l’information par le cerveau (qui reconnaît un objet ou sa dynamique) possède au moins trois caractéristiques : ce traitement est guidé par un algorithme de calcul descendant (la prédiction) ; il correspond au modèle de l’environnement appris au préalable (selon la théorie bayésienne) ; et il est biologiquement plausible,

c’est-à-dire, qu’il est implémenté au sein d’une structure cérébrale (implémentation neurologique) [44].

### 4.2. Rivalité binoculaire

La rivalité binoculaire pour la vision est un exemple de perception issue du traitement prédictif [45]. Ce phénomène désigne l’alternance de l’expérience visuelle de deux stimuli différents lorsqu’ils sont présentés conjointement à chaque œil, par exemple lorsqu’une image d’un tigre est présentée à l’œil droit et l’image d’un éléphant à l’œil gauche. Dans cette situation, l’expérience visuelle consciente alternera entre la vision d’un tigre et d’un éléphant, mais ne permettra pas d’intégrer une combinaison des stimuli. Plusieurs expériences ont été réalisées dans ce cadre et ont montré que la rivalité binoculaire dépendait notamment du type de stimuli perçu par chaque œil [45]. Ainsi lorsque des stimuli différents, que nous ne sommes pas habitués à percevoir combinés, sont présentés conjointement, il existe un phénomène de rivalité binoculaire. À l’inverse, des stimuli proches et que nous sommes habitués à percevoir combinés dans notre environnement provoquent moins de rivalité binoculaire. Par exemple, alors que l’exposition oculaire conjointe d’un tigre et d’un éléphant provoque une rivalité, la combinaison d’un arbre seul et d’une forêt est plus facilement combinée en un percept unique.

### 4.3. Probabilité perceptive

La théorie bayésienne du traitement prédictif permet de comprendre ce phénomène [45]. En effet, nous ne sommes pas habitués à voir un tigre et un éléphant hybridés (à l’exception bien sûr des représentations fantastiques de chimères dans les contes ou en science-fiction) : une faible probabilité est assignée à la combinaison de ces deux entrées sensorielles dans notre hiérarchie de croyances. Toutefois, nos yeux sont habitués à avoir des entrées sensorielles congruentes et à combiner les informations issues de chacune des rétines pour élaborer une perception visuelle cohérente et unifiée. De fait, l’observation de ces deux entrées sensorielles discordantes déclenche une série itérative d’erreurs de prédictions (prédiction d’un tigre, et observation d’un éléphant ; prédiction d’un éléphant, et observation d’un tigre) qui provoquent des mises à jour successives des prédictions. L’hypothèse visuelle la plus probable (déterminant la perception visuelle subjective et consciente) se déplace alors successivement du tigre vers l’éléphant au

fur et à mesure des erreurs de prédictions et des mises à jour au sein de la hiérarchie des croyances. À l’inverse, des stimuli ne pro-

voquant pas de rivalité binoculaire génèrent un équilibre entre la prédiction et les erreurs de prédiction, produisant une perception stable.

## 5. De l’action automatisée à l’action programmée

### 5.1. Intégration sensori-motrice

La théorie bayésienne du traitement prédictif permet aussi de modéliser les actions automatisées, liées par exemple à la poursuite

d’un stimulus visuel par les muscles oculaires, ou les actions complexes dirigées vers un but impliquant différentes chaînes motrices. Ces modèles computationnels représentent la manière dont le cerveau produit des perceptions stables et unifiées (par exemple, l’image visuelle d’un éléphant ou le bruit d’une cascade) malgré le déplacement de l’image ou du son en fonction du mouvement

des yeux et de la tête. Les travaux réalisés sur cette dimension d’intégration sensori-motrice montrent que l’activité motrice influence directement

le traitement perceptif, non seulement

du fait de la modification des entrées sensorielles au fur et à

mesure des changements spatio-temporels de l’organisme, mais également via un couplage entre les prédictions sur le résultat des actions et les

entrées sensorielles attendues en lien avec ces résultats

[46].

### 5.2. Inférence active

Basés sur de tels constats, des modèles d’inférence active ont été développés pour compléter la théorie bayésienne du traitement prédictif. Ces modèles suggèrent que l’organisme cherche à confirmer ses prédictions en mettant en place des actions. Ces actions vont corriger ses prédictions, en fonction de la différence entre les entrées sensorielles attendues à la suite d’une action et les entrées sensorielles réelles (c’est-à-dire en fonction des erreurs de prédiction) [12]. Le cerveau peut ainsi prédire à chaque instant quelles sont les causes les plus probables des entrées sensorielles qu’il rec¸ oit. Il utilise ensuite ses erreurs de prédictions pour corriger son estimation des causes les plus probables, sous la forme d’une mise à

jour des croyances. Ces arcs automatisés combinant prédiction, action et perception permettent de maintenir des perceptions unifiées malgré les mouvements du corps, en fonctionnant comme des systèmes anticipant les entrées sensorielles (consécutives à un mouvement moteur) les plus probables [5].

### 5.3. Arcs réflexes

Cette hiérarchie de croyances descendantes et d’erreurs de prédiction montantes n’est pas limitée au système nerveux central ni aux processus cognitifs complexes et élaborés [47]. Par exemple, les arcs réflexes déterminant le retrait d’un membre au contact d’une flamme peuvent être expliqués à l’aide de la théorie du traitement prédictif [48]. Lorsque les capteurs sensoriels nociceptifs situés sur la peau détectent la chaleur, un message d’erreur de prédiction est transmis [49]. Il se répercute jusqu’à la moelle épinière, où se fait le contact avec les premiers ganglions et les neurones moteurs (puis avec les neurones qui transmettent l’information de la moelle épinière jusqu’au cerveau) [50]. À chaque étape de transmission de l’information, l’erreur de prédiction est confrontée à des prédictions de plus haut niveau hiérarchique, opérant sans réelle prise de conscience subjective de la chaleur et de la douleur – bien avant que le message douloureux ne soit interprété par une hiérarchie de croyances de plus haut niveau dans le cerveau [51]. Ce traitement automatisé de bas niveau,

précédant la transmission au cortex, permet notamment des phénomènes réflexes rapides, comme le retrait instantané de

440

<!-- ======================================================================= -->
<!-- PAGE 6                                                                  -->
<!-- ======================================================================= -->

la main du feu, bien avant le ressenti nociceptif et la conscientisation de la brûlure [47]. Ce phénomène vaut d’ailleurs pour toute une série de phénomènes inconscients plus ou moins élaborés comme l’intéroception (en particulier les battements cardiaques, ou la contractilité intestinale) ou la proprioception [50].

## 6. L’émotion, une erreur de prédiction

### 6.1. Intéroception émotionnelle

L’intéroception viscérale et le traitement prédictif intéroceptif ont fait l’objet d’un intérêt croissant du fait de leur intrication avec les phénomènes émotionnels [52,53]. Un grand nombre de théories de l’émotion s’accordent sur le fait que les états émotionnels sont des états mentaux avec une dimension doxastique (un état de croyance, dirigé vers un objet), une dimension affective (un état affectif,

caractérisé par une valence négative ou positive, et une intensité), et une

dimension physiologique (un état physiologique, possédant

des caractéristiques propres selon l’émotion considérée). Selon

la théorie de l’émotion considérée, la part doxastique, affective, ou physiologique occupe une place plus ou moins importante, mais la majorité des théories s’accorde pour différencier ces dimensions au sein d’un même état émotionnel. Ainsi, si j’ai peur d’un cobra, mon émotion de peur est caractérisée par un ensemble de croyances en lien avec le cobra (j’ai la croyance que le cobra est un animal dangereux, qu’il pourrait me mordre, qu’il injecte du venin), de caractéristiques affectives (mon émotion comporte une valence négative, et elle est d’intensité élevée) et de caractéristiques physiologiques (mon rythme cardiaque s’accélère, mes pupilles se rétractent, mes muscles se contractent). La superposition de ces différents états doxastiques, affectifs, et physiologiques a opposé historiquement les théories physiologiques de l’émotion (mettant l’accent en priorité sur l’activation physiologique, avec une réaction cognitive secondaire) et les théories cognitives de l’émotion (mettant l’accent en priorité sur la réaction cognitive, avec activation physiologique secondaire) [54,55].

A contrario de ces distinctions, la théorie bayésienne du traitement prédictif propose une approche unificatrice de ces dimensions cognitives et physiologiques de l’émotion. Les modèles de prédiction intéroceptive supposent que les perceptions viscérales (entrées sensorielles venant de l’activité des viscères) ou cardiaques (vitesse des battements cardiaques, par exemple) dépendent d’une hiérarchie de prédiction et d’erreurs de prédiction. Les entrées sensorielles intéroceptives sont prédites par le cerveau, et lorsqu’il existe une différence entre les prédictions et l’activité perçue, des erreurs de prédiction sont générées. Comme nous l’avons vu précédemment, ces prédictions sont également couplées avec l’activité motrice, de telle manière que si l’organisme s’engage dans un mouvement moteur programmé (par exemple, commencer un jogging), les prédictions sur le rythme cardiaque (augmentation du rythme cardiaque) et les viscères (diminution de la contractilité viscérale) vont s’adapter automatiquement à l’action programmée, sans générer d’erreurs de prédiction.

### 6.2. Stimuli imprévus

Cependant, lorsque l’organisme est confronté à des stimuli imprévus qui n’étaient pas prédits dans la hiérarchie de croyances prédictives, des changements intéroceptifs non programmés vont se produire. Par exemple, si je découvre un cobra dans mon appartement, mes croyances concernant le danger dans mon environnement immédiat (sécurité de l’environnement, absence d’animaux

dangereux, absence de risque vital immédiat) vont immédiatement se mettre à jour, parallèlement à une augmen-

tation imprévue de mon rythme cardiaque et à une contraction non programmée de ma musculature. Ces changements intéroceptifs et extéroceptifs inattendus vont provoquer des erreurs de prédiction se répercutant dans la hiérarchie de prédiction intéroceptive et extéroceptive, signalant un changement inattendu dans l’environnement immédiat [56]. Au fil des inférences bayésiennes, les erreurs de prédiction vont remonter le long de la hiérarchie corticale et permettre au cortex de mettre à jour les prédictions antérieures. Le cœur de la théorie du traitement prédictif de l’émotion est associée à ce processus de mise à jour : l’émotion, au sens phénoménologique et mécanistique, est définie comme la conséquence des erreurs de prédictions intéroceptives, témoignant de la discordance entre l’activité intéroceptive prédite et l’activité intéroceptive réelle. Dans ce contexte, l’émotion émerge lors de la violation des prédictions intéroceptives, c’est-à-dire lorsque le cerveau n’a pas prédit efficacement la manière dont le corps allait s’adapter à l’environnement immédiat. La théorie bayésienne du traitement prédictif a ainsi l’ambition de proposer une nouvelle conception de l’émotion, hybridant les dimensions physiologiques et cognitives [57].

### 6.3. Nouvelle théorie de l’émotion

Ce modèle de l’émotion, ancré dans la théorie bayésienne du traitement prédictif, a l’avantage de faire le lien avec plusieurs champs appartenant aux sciences cognitives, à la psychologie expérimentale et à la psychiatrie. Il permet notamment de comprendre pourquoi les émotions sont si souvent provoquées par des sensations

intéroceptives comme la perception des battements cardiaques ou de la motilité intestinale, ou encore pourquoi les émotions sont associées à une phénoménologie corporelle spécifique. Par exemple, l’augmentation du rythme cardiaque ou les maux de ventre sont fréquemment associés à des émotions négatives comme la peur, tandis que la décontraction viscérale et ou le relâchement musculaire sont préférentiellement associés à des émotions positives à la joie. Ce modèle aide également à comprendre la relation bidirectionnelle entre les perturbations gastro-entérologiques (maux de ventre, diarrhée, constipation) et le ressenti émotionnel, en particulier dans les troubles fonctionnels intestinaux, ou encore l’importance du microbiote intestinal pour l’émotion [58,59]. Lorsque des perturbations du microbiote intestinal surviennent, le cerveau est moins en mesure de prédire l’évolution du transit et de la motilité intestinale. Ces hypothèses microbiotiques font ainsi directement le lien entre la régulation des variables intéroceptives par le système nerveux, l’influence du microbiote sur ces variables intéroceptives, et le ressenti émotionnel. La théorie du cerveau prédictif est ainsi en mesure d’offrir une conception unificatrice du fonctionnement du système nerveux central et périphérique, sans se limiter aux grandes fonctions cognitives comme un grand nombre des modèles cognitifs de la psychologie expérimentale.

## 7. Pour un bayésianisme modéré

### 7.1. L’agnosticisme bayésien

La théorie bayésienne du traitement prédictif et ses modèles présentent cependant plusieurs limites. La première est inhérente aux ambitions unificatrices de la théorie. Celle-ci offre un panorama descriptif de la plupart des processus cognitifs, et prétend ainsi être en mesure d’expliquer des fonctions cognitives comme la perception, l’action, l’attention, ainsi que des états psychologiques complexes comme la croyance, le désir ou l’émotion. Toutefois, la théorie

prédictive (et a fortiori, les modèles computationnels qui en sont issus) ne considère souvent que des perspectives partielles

441

<!-- ======================================================================= -->
<!-- PAGE 7                                                                  -->
<!-- ======================================================================= -->

de ces fonctions cognitives ou de ces états psychologiques, en ayant tendance à conserver uniquement ce qui est en accord avec ses principes fondamentaux et à délaisser les aspects qui échappent à son pouvoir explicatif [10]. Dans certains cas, la théorie est même amenée à redéfinir certains de ces états mentaux et processus cognitifs, comme cela a pu être le cas de la croyance [35] ou de l’émotion [57]. Deuxièmement, au sein de la théorie du traitement prédictif, il

existe une ambiguïté concernant la nature (voire l’existence) des processus cognitifs et des états psychologiques qui correspondent aux états mentaux. Il en est de même pour la nature de la représentation mathématique de ces processus cognitifs et états psychologiques au sein de cette théorie. Ainsi, il existe des confusions et des dérives sémantiques lors du transfert d’un terme d’un domaine à un autre. Par exemple, étant donné qu’un certain nombre de

termes désignant les états mentaux en psychologie et les représentations mathématiques dans la théorie du traitement prédictif sont identiques, ils sont souvent interchangés. L’un des exemples les plus marquants dans la théorie du traitement prédictif concerne la notion de prédiction, un terme polysémique parfois employé conjointement pour désigner une attente prédictive, une anticipation sensorielle, une prédiction comportementale, une prospection événementielle

ou encore un état de croyance probabiliste [33]. Dans cet article, nous avons spécifié la différence entre la croyance (état probabiliste) et la prédiction (message généré à partir de la croyance), mais cette distinction disparaît parfois dans la littérature en sciences cognitives, rendant confuse la distinction entre prédiction et croyance [35].

### 7.2. Le paradoxe de la représentation

Troisièmement, les modèles issus de la théorie du traitement prédictif prennent rarement position, sur le plan philosophique, en ce qui concerne la notion de représentation. Les modèles restent majoritairement agnostiques quant au fait de savoir si les prédictions sont des états représentationnels (ayant un contenu sémantique), pouvant par exemple être stockés dans la mémoire et exerc¸ ant un effet sur les voies sensorielles, ou si elles sont des états non représentationnels, résultant d’une activation de voies descendantes vers les aires sensorielles et facilitant le traitement des informations perceptives ou motrices prédites. Cette distinction est pourtant majeure : si les prédictions sont des états représentationnels, le cerveau simule à chaque instant la structure probabiliste de son environnement en mobilisant des états représentationnels complexes, et en les comparant à ses entrées sensorielles réelles. Si les prédictions sont des états non représentationnels, le cerveau incarne le rapport entre son corps et son environnement en prédisant et corrigeant simultanément ses entrées sensorielles, afin de maintenir une relative harmonie perceptuelle. Des passages de l’une à l’autre de ces modalités pourraient être envisagés, en particulier lorsque nous réalisons des prospections imaginaires (rêveries éveillées sur l’avenir), au cours des épisodes de dissociation péri-traumatique, ou encore sous l’effet de psychodysleptique dissociatif comme la kétamine [60,61]. La distinction entre des états représentationnels et non représentationnels est aussi majeure en termes d’implémentation neuronale de la théorie du traitement prédictif. Si les prédictions sont des états représentationnels, encodées dans la mémoire à partir des expériences antérieures et directement associées aux souvenirs, alors elles nécessitent un espace de stockage conséquent et une importante puissance de calcul pour traiter l’information. Étant donné la faible plausibilité biologique d’un tel encodage, les actualisations les plus récentes de la théorie du traitement prédictif considèrent que les prédictions sont encodées de manière indifférenciée, au sein de toute l’architecture fonctionnelle cérébrale (sans nécessiter

d’encodage mnémonique différencié ni spécifique) [62].

### 7.3. Limites de l’implémentation

Quatrièmement, les modèles proposés pour l’implémentation biologique de ces calculs ainsi que les formalismes mathématiques utilisés comportent d’importantes variations. Par exemple, les modèles computationnels que nous avons décrits dans cet article sont pour la plupart fondés sur le principe de l’énergie libre (FEP – Free Energy Principle) et s’appuient sur un formalisme mathématique issu de la physique statistique et de la théorie de l’information. Ce principe suggère qu’un système qui réalise des inférences bayésienne peut minimiser l’incertitude de ses afférences sensorielles [51]. Les modèles issus du FEP utilisent souvent la divergence de Kullback–Leibler, une mesure mathématique de la divergence entre deux distributions de probabilité pour représenter la taille de l’erreur de prédiction dans les différents niveaux de la hiérarchie prédictive [4,63]. Pourtant, de nombreux autres cadres d’implémentation des calculs bayésien ont été proposés et certaines versions du PP n’établissent pas de relation formelle avec le FEP [64,65]. A contrario, certains modèles utilisent le même type de formalisme bayésien pour décrire des phénomènes qui se produisent à différentes

échelles, du microscopique au macroscopique, du moléculaire au comportemental. Certains modèles font ainsi l’hypothèse de calculs bayésiens réalisés par ajustement de la plasticité synaptique au sein des réseaux de neurones [66], d’autres proposent d’interpréter les biais sensoriels comme des mécanismes d’implémentation des a priori sur l’environnement [67], tandis que d’autres se proposent de modéliser le processus de prise de décision à l’aide d’équations de diffusion (Drift Diffusion Model), qui peuvent être interprétées mathématiquement comme des mécanismes bayésiens d’accumulation d’évidences sensorielles [68]. Bien que tous ces modèles utilisent des formalismes bayésiens, ce n’est pas la même chose de supposer que le cerveau est bayésien parce que le neurone pourrait implémenter des mécanismes bayésiens, ou parce que le comportement suit des règles bayésiennes.

Cette diversité d’application mathématique limite la possibilité de falsification expérimentale, considérée comme un des fondements de la scientificité d’une théorie depuis les travaux du philosophe Karl Popper [69]. La falsification désigne la possibilité pour une théorie d’être invalidée par l’expérience. Par exemple, une théorie physique sur la vitesse du son pourra être qualifiée de scientifique si elle peut être invalidée par des résultats expérimentaux sur la vitesse de son. À l’inverse, une théorie physique sur l’existence de matière noire ne pourra pas être qualifiée de scientifique s’il n’existe aucune manière de démontrer sa fausseté, ou si tous les résultats expérimentaux issus des recherches sur la matière noire ne peuvent pas permettre de mettre en doute son existence.

Dans le cas du cerveau bayésien, s’il existe de multiples formalismes mathématiques permettant d’appliquer, de différentes manières, les principes généraux de la théorie, il est plus difficile d’imaginer une réfutation à cette théorie [70]. À l’inverse, le choix d’utiliser un formalisme unique (comme le principe de l’énergie libre – FEP) a pu restreindre la diversification de l’évolution des modèles prédictifs. Autrement dit, il existe une dépendance au chemin, qui implique que les différents modèles sur lesquels se construisent les neurosciences computationnelles s’appuient sur les modèles précédents [71]. Au sein de la théorie du traitement prédictif, on retrouve donc à la fois une diversité mathématique potentielle et une rigidité des modèles utilisés en pratique. L’ensemble de ces limites théoriques et méthodologiques devraient être considérées lors de l’application de la théorie bayésienne du traitement prédictif au fonctionnement cérébral et à ses corollaires en

psychologie et en psychiatrie.

442

<!-- ======================================================================= -->
<!-- PAGE 8                                                                  -->
<!-- ======================================================================= -->

## 8. Conclusion

Les principes fondamentaux de la théorie bayésienne du traitement prédictif sont fondés sur un riche héritage issu de la philosophie de l’esprit et des neurosciences computationnelles. Selon cette théorie, le cerveau utilise un ensemble de croyances (estimations probabilistes) pour générer des prédictions à propos des entrées sensorielles qu’il va expérimenter au fil du temps. Il utilise ensuite les erreurs de prédictions pour mettre à jour ses croyances sur le monde. Malgré ses limites, nous suggérons que cette théorie est en mesure de proposer un cadre explicatif de processus cognitifs complexes comme la perception, l’action, l’émotion, et la croyance, fournissant ainsi des hypothèses pertinentes concernant l’étiopathogénie des troubles psychiatriques.

Déclaration de liens d’intérêts

Les auteurs déclarent ne pas avoir de liens d’intérêts.
