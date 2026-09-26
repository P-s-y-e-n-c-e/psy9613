# L'influence de l'action sur la perception s'étend à différents effecteurs

**Titre original :** *The influence of action on perception spans different effectors*  
**Auteurs :** Annalisa Bosco (1, 2*), Pablo Sanz Diez (3, 4), Matteo Filippini (1), Patrizia Fattori (1, 2)  
**Affiliations :**  
(1) Département des sciences biomédicales et neuromotrices, Université de Bologne, Bologne, Italie  
(2) Institut de recherche Alma Mater pour une intelligence artificielle centrée sur l'humain (*Alma Human AI*), Université de Bologne, Bologne, Italie  
(3) Carl Zeiss Vision International GmbH, Aalen, Allemagne  
(4) Institut de recherche ophtalmique, Université Eberhard Karl de Tübingen, Tübingen, Allemagne  
**Revue :** *Frontiers in Systems Neuroscience* (2023), Vol. 17, Art. 1145643  
**DOI :** [10.3389/fnsys.2023.1145643](https://doi.org/10.3389/fnsys.2023.1145643)  
**Type d'article :** Synthèse critique (*Review*) — Accès libre (*Open Access*)  
**Traduction académique :** Module officiel de traduction académique — PSY9613 (*Perception, cognition et IA*, UQAM)

---

### Résumé (*Abstract*)

La perception et l'action sont des processus fondamentaux qui caractérisent notre existence et notre capacité à modifier le monde qui nous entoure. De multiples données probantes ont mis en lumière une interaction intime et réciproque entre la perception et l'action, nous amenant à postuler que ces deux processus reposent sur un ensemble partagé de représentations communes. La présente synthèse critique se concentre sur un aspect particulier de cette interaction : **l'influence de l'action sur la perception sous l'angle des effecteurs moteurs**, examinée au cours de deux phases distinctes : **la planification de l'action** et **la phase consécutive à l'exécution de l'action**.

Les mouvements exécutés par les yeux, les mains et les jambes exercent un impact différencié sur la perception des objets et de l'espace ; les travaux exploitant des approches et des paradigmes variés dressent un tableau général particulièrement éloquent démontrant l'existence d'un effet de l'action sur la perception, tant en amont (avant) qu'en aval (après) de son exécution motrice. Bien que les mécanismes intimes sous-jacents fassent encore l'objet de vifs débats, diverses études démontrent que cet effet modèle et amorce de façon hautement pragmatique la perception des caractéristiques pertinentes de l'objet ou de l'environnement qui sollicite l'action ; à d'autres moments, il affine et perfectionne notre perception par l'entremise de l'expérience motrice et de l'apprentissage sensorimoteur. Enfin, nous dégageons une perspective d'avenir prometteuse, en suggérant que ces mécanismes peuvent être directement exploités pour accroître la confiance et l'efficience des systèmes d'intelligence artificielle (IA) appelés à interagir étroitement avec les êtres humains.

**Mots-clés :** propriétés des objets, geste d'atteinte (*reaching*), geste de préhension (*grasping*), mouvements oculaires, saccades, marche, effecteurs moteurs, théories du codage commun.

---

<!-- ======================================================================= -->
<!-- PAGE 1                                                                  -->
<!-- ======================================================================= -->

## Introduction

À la base de tout comportement adaptatif réussi se trouve l'interaction dynamique entre la perception et l'action. Selon la conception classique, la perception informe les mécanismes de l'action quant aux propriétés de l'environnement, et ces mécanismes moteurs sont en retour responsables des modifications apportées à cet environnement. S'il est indéniable que la perception influence l'action, l'influence inverse — à savoir **l'influence de l'action sur la perception** — ne peut être tenue pour acquise avec la même évidence immédiate.

Partant d'une telle considération, la présente revue a pour objectif d'examiner l'impact de l'action sur la perception visuelle de différentes propriétés des objets (notamment la taille, l'orientation et la localisation spatiale), en se focalisant sur les actions déployées par différents effecteurs moteurs tels que **l'œil**, **la main** et **la jambe**. Puisque deux étapes temporelles peuvent être formellement dissociées lorsqu'on étudie l'influence de l'action sur le traitement perceptif — à savoir **la planification** et **l'exécution** —, nous proposons dans les sections suivantes un panorama structuré : d'abord des études qui explorent l'effet de la planification de l'action sur la perception du stimulus/objet, puis de celles qui examinent l'exécution motrice et ses conséquences directes sur la perception.

---

<!-- ======================================================================= -->
<!-- PAGE 2                                                                  -->
<!-- ======================================================================= -->

## 1. L'effet de la planification de l'action sur la perception

En tant qu'observateurs perceptifs, nous recevons quotidiennement une vaste gamme d'informations relatives aux caractéristiques de notre environnement immédiat. En tant qu'acteurs engagés, nous explorons activement cet environnement à partir du traitement sensoriel des stimuli directement liés à nos buts, à nos intentions et aux actions motrices qui en découlent. Par exemple, des tâches de la vie quotidienne telles que saisir une tasse ou empoigner le manche d'une poêle à frire constituent des actions d'une remarquable précision que nous accomplissons de manière quasi automatique ; pourtant, elles mobilisent une approche sensorimotrice d'une grande complexité, dont de nombreux mécanismes demeurent encore méconnus.

Une action — définie comme un mouvement intentionnel et orienté vers un but (*targeted movement*) — se distingue par une succession de séquences fonctionnelles qui structurent son traitement en coordination étroite avec la perception (Hommel et al., 2016). Au sein de cette chaîne de traitement (qui englobe l'évaluation des indices environnementaux, la localisation dans l'espace tridimensionnel, ainsi que la sélection, l'intégration et l'initiation de l'action), **la planification de l'action** constitue une composante absolument fondamentale (Hommel et al., 2016 ; Mattar et Lengyel, 2022).

La planification motrice est formellement définie comme le processus qui détermine l'exécution des actions en fonction des contraintes de l'environnement et des résultats attendus (Sutton et Barto, 1998 ; Mattar et Lengyel, 2022). D'un point de vue chronométrique, la planification de l'action correspond à l'intervalle temporel situé entre la phase décisionnelle et la phase d'impulsion motrice initiale. Durant cette phase de planification, l'agent génère un but d'action (fondé sur les propriétés spatiales et temporelles de l'environnement), lequel est ensuite transmis au système moteur pour concrétiser cette finalité spécifique. Autrement dit, l'information sensorielle est d'abord organisée, puis intégrée au sein d'un plan moteur structuré. Cette particularité confère au système une grande plasticité et favorise l'adaptation rapide à d'éventuelles modifications des signaux d'entrée ou des objectifs finaux (Mattar et Lengyel, 2022).

À titre d'illustration, lors de la préhension d'un objet, on observe un ajustement précoce de la conformation de la main aux propriétés intrinsèques de cet objet bien avant le contact (Jeannerod, 1981), ce qui souligne l'importance primordiale de la planification motrice dans l'interface entre l'environnement physique et le but recherché. En réalité, les informations visuelles d'entrée sont traitées en parallèle par des voies neurales opérant au sein d'un cadre commun liant action et perception (*shared action-perception framework*, Prinz, 1990 ; Hommel et al., 2001) ; or, il a été démontré que la planification motrice elle-même module et biaise activement ce réseau (Hommel et al., 2001, 2016 ; Witt, 2018).

En dépit de l'abondante littérature scientifique consacrée à la contribution de la planification aux processus cognitifs, les données actuelles ne nous offrent encore qu'un aperçu préliminaire de l'ampleur des mécanismes en jeu. Dans les sections qui suivent, nous présentons les principales études comportementales ayant documenté l'impact de la planification motrice sur la perception.

---

### 1.1 Le domaine de l'œil (Effecteur oculomoteur)

Notre système visuel capte les informations primordiales destinées à guider nos actes. Une fois l'environnement visuel exploré et les objets d'intérêt identifiés, l'information visuospatiale est acheminée vers les structures motrices afin de planifier, d'exécuter et de contrôler les actions dirigées vers un but (Hayhoe, 2017). L'impact de la vision sur le contrôle moteur a toujours suscité un intérêt scientifique majeur (Prablanc et al., 1979 ; Desmurget et al., 1998 ; Land, 2006, 2009). Il y a plusieurs décennies déjà, des travaux pionniers décrivaient comment la vision optimise la précision des mouvements finalisés (Woodworth, 1899 ; Bernstein, 1967). Depuis lors, une multitude d'études se sont attachées à disséquer la manière dont la vision influence la planification, l'exécution et la régulation continue du geste.

L'information visuelle contribue de façon décisive à la phase de planification de l'action. Pendant cette étape préparatoire, la présence d'une rétroaction visuelle (*visual feedback*) relative au membre moteur est de première importance. Il a été démontré que les gestes moteurs sont nettement plus précis lorsqu'une rétroaction visuelle est disponible dès la phase de planification motrice, que le membre demeure visible ou non pendant l'exécution proprement dite du mouvement (Prablanc et al., 1979 ; Conti et Beaubaton, 1980 ; Pélisson et al., 1986 ; Velay et Beaubaton, 1986 ; Elliott et al., 1991, 2014 ; Rossetti et al., 1994 ; Desmurget et al., 1995, 1997 ; Coello et Grealy, 1997 ; Bagesteiro et al., 2006 ; Bourdin et al., 2006 ; Sarlegna et Sainburg, 2009).

En effet, la vision joue un rôle clé dans la planification motrice dans la mesure où les mouvements semblent être programmés sous forme de vecteurs définis dans les coordonnées extrinsèques de l'environnement visuel (Morasso, 1981 ; Flanagan et Rao, 1995 ; Wolpert et al., 1995 ; Sarlegna et Sainburg, 2009). Dès que l'information visuelle est extraite, la planification doit intégrer les propriétés physiques qui modèleront les actions à venir. Prenons l'exemple d'un conducteur à l'approche d'une intersection routière : son système visuel extrait la position et la cinématique des autres véhicules, des piétons et la signalisation lumineuse. Sur la base de ces coordonnées extrinsèques fournies par l'environnement visuel, la planification motrice calcule les vecteurs cinématiques appropriés (accélération, freinage ou braquage) permettant de franchir l'intersection de façon fluide et sécuritaire.

Dans un cadre théorique consensuel, deux stades successifs ont été proposés au sein de la planification de l'action :
1. **Le stade primaire**, au cours duquel la vision est essentielle pour déterminer les attributs visuospatiaux (la cible, les membres corporels et l'environnement) ;
2. **Le stade secondaire**, au cours duquel cette entrée primaire est convertie en commandes motrices spécifiques destinées à déclencher l'action physique (Sarlegna et Sainburg, 2009).

Par conséquent, dans des conditions normales, la vision fournit durant la planification de l'action les données critiques garantissant la réussite du geste moteur.

Toutefois, l'acquisition de cette information visuospatiale précise serait impossible sans les mouvements oculaires. Lorsqu'une cible apparaît dans la périphérie du champ visuel, les mouvements oculaires interviennent pour en déterminer la localisation exacte. Supposons que nous souhaitions atteindre un objet de la main. Compte tenu du gradient de résolution spatiale de la rétine, dès qu'une cible d'intérêt est repérée, la région fovéale — dotée de la plus haute acuité rétinienne — doit être impérativement alignée sur cette cible (Liversedge et Findlay, 2000 ; Land, 2006). Pour ce faire, avant même que le geste manuel d'atteinte (*reaching*) ne s'amorce, les yeux déclenchent une saccade en direction de l'objet, puis maintiennent une fixation stable et continue sur celui-ci jusqu'à ce que la main entre en contact physique avec la cible. Ce scénario élémentaire met en lumière le rôle capital des mouvements oculaires, qui assurent sans relâche le couplage fonctionnel entre vision et action (Land, 2006, 2009 ; Hayhoe, 2017 ; de Brouwer et al., 2021).

---

<!-- ======================================================================= -->
<!-- PAGE 3                                                                  -->
<!-- ======================================================================= -->

Les recherches portant sur l'interaction entre systèmes visuel et moteur ont révélé à quel point les yeux guident et soutiennent en temps réel nos actions dans une multitude de tâches dynamiques (Angel et al., 1970 ; Biguer et al., 1982 ; Pélisson et al., 1986 ; Land, 1992 ; Land et al., 1999 ; Neggers et Bekkering, 1999, 2000, 2001, 2002 ; Johansson et al., 2001 ; Patla et Vickers, 2003). Par exemple, Land et al. (1999) ont démontré que les mouvements oculaires ciblent systématiquement les objets directement impliqués dans la chaîne opératoire de nos actions courantes. 

Dans une série d'études remarquables, Neggers et Bekkering (1999, 2000, 2001, 2002) ont élégamment mis en évidence un mécanisme baptisé **l'ancrage du regard** (*gaze anchoring*) lors des actions manuelles. Ils ont observé que pendant l'exécution d'un geste d'atteinte, les sujets sont incapables d'initier une nouvelle saccade oculaire vers une autre cible visuelle tant et aussi longtemps que leur main n'a pas atteint la cible en cours. 

Des observations concordantes ont été rapportées par Johansson et al. (2001). Dans leur protocole, les participants devaient atteindre et saisir une barre (*reaching & grasping*), la déplacer en contournant divers obstacles, pour finalement l'insérer sur un interrupteur. Les auteurs ont constaté que les fixations du regard se verrouillaient rigoureusement sur les points mécaniques critiques de l'action : les yeux guidaient en continu l'action de saisie, la trajectoire d'évitement et l'amarrage de l'objet (Johansson et al., 2001). 

D'autres travaux ont par ailleurs établi que les patrons de fixation oculaire diffèrent radicalement selon qu'un objet est saisi activement ou simplement observé de manière passive (Vishwanath et Kowler, 2003 ; Brouwer et al., 2009). Ces deux études ont démontré qu'en visualisation passive, les fixations oculaires convergent spontanément vers le **centre de gravité** géométrique de l'objet, alors que lors d'une tâche de préhension, le regard se focalise sélectivement sur **les zones de contact futures des doigts** (l'index et le pouce). De surcroît, Brouwer et al. (2009) ont observé que les temps de réaction saccadiques étaient significativement plus lents dans la condition de préhension comparativement à la condition de simple visualisation. Ce résultat prouve formellement que l'initiation du mouvement oculaire est étroitement subordonnée à la planification de l'action, c'est-à-dire aux situations où l'œil et la main sont mobilisés conjointement au sein d'un même programme moteur unifié.

L'allongement des latences de réponse oculaire en relation avec l'action manuelle a été documenté par plusieurs équipes (Bekkering et al., 1994, 1995 ; Lünenburger et al., 2000 ; Pelz et al., 2001 ; Hayhoe et al., 2003). Bekkering et al. (1994) ont mesuré les latences motrices de l'œil et de la main en comparant des protocoles en tâche simple (*single-task*) et en double tâche (*dual-task*). Tout comme Brouwer et al. (2009), et ainsi que l'illustre la **Figure 1**, les latences des saccades oculaires étaient nettement plus élevées en condition de double tâche, c'est-à-dire lorsque l'œil et la main devaient se mobiliser simultanément vers la même cible visuelle. En revanche, les latences de la main demeuraient rigoureusement stables entre la tâche simple et la double tâche (Bekkering et al., 1994). 

À l'opposé, une autre étude a rapporté une réduction des latences saccadiques lors de mouvements simultanés de l'œil et de la main vers une cible commune (Lünenburger et al., 2000). Il est très probable que la nature spécifique de l'action planifiée (pointage, simple atteinte, préhension fine, etc.) joue un rôle déterminant dans cet effet d'interférence. Des temps de calcul neural plus longs peuvent être requis selon la complexité cinématique de l'action programmée, modulant ainsi différemment les temps de réaction oculaires (Brouwer et al., 2009). Quoi qu'il en soit, ces résultats apportent la démonstration formelle que les systèmes moteurs oculaires et manuels ne sont pas des modules indépendants, mais partagent des processus synergiques étroits lorsqu'ils convergent vers un même but comportemental.

Des études plus récentes ont mis en lumière la façon dont les mouvements oculaires soutiennent la sélection et la préparation motrice vers un objectif. Notamment, l'analyse des interactions œil-membre dans des tâches naturalistes a montré que les mouvements oculaires extraient un flux continu de données visuelles, créant un contexte intégrant propriétés intrinsèques et coordonnées spatiales pendant la planification afin de guider efficacement le geste moteur futur (Zelinsky et al., 1997 ; Land et al., 1999 ; Pelz et al., 2001 ; Brouwer et al., 2009). Dans des tâches telles que dévisser un bocal ou se laver les mains, il a été mis en évidence que les gestes d'atteinte manuelle sont systématiquement précédés de **fixations anticipatrices** dirigées vers la cible d'intérêt (Pelz et al., 2001 ; Hayhoe et al., 2003). Ces fixations interviennent durant la planification de l'action et fournissent à l'observateur les coordonnées spatiales déterminantes pour guider le geste à venir (Hayhoe et al., 2003). 

Dans d'autres activités motrices complexes, comme la marche sur terrain accidenté ou la conduite automobile sur routes sinueuses, l'information visuospatiale issue des mouvements oculaires s'avère tout aussi primordiale lors de la planification motrice (Land et Lee, 1994 ; Patla et Vickers, 2003 ; Land, 2006). Par exemple, au cours de la marche, **la fixation du regard devance l'action physique de 0,8 à 1,1 seconde en moyenne** (Patla et Vickers, 2003 ; Land, 2006). Cela suggère fortement que pendant la planification, le système visuel se comporte comme un dispositif d'anticipation opérant selon une modalité prospective (*feedforward*) pour préparer l'exécution du mouvement.

---

> #### **Figure 1 : Latences des réponses oculaires et manuelles en tâche simple vs double tâche**
> Latences moyennes des réponses motrices de l'œil et de la main, mesurées en millisecondes (ms), sous les deux conditions expérimentales : tâche simple (*single-task*) et double tâche (*dual-task*). En condition de double tâche (mouvement combiné œil-main), la latence de la saccade oculaire augmente significativement, témoignant d'une interférence centrale liée à la planification motrice conjointe, tandis que la latence de la main reste inchangée. *(Adapté de Bekkering et al., 1994).*

---

Alors que les études qui précèdent ont examiné le rôle des yeux en tant que support préparatoire aux actions accomplies par d'autres effecteurs moteurs (tels que la main ou les membres locomoteurs), de nombreux travaux ont investigué l'impact direct de la planification motrice oculaire sur la perception visuelle au sein même du système oculomoteur. Ces recherches démontrent de manière éclatante que **la perception spatiale est rehaussée de manière sélective à l'endroit précis où le mouvement oculaire projette d'atterrir, une fraction de seconde avant son déclenchement physique** (Hoffman et Subramaniam, 1995 ; Deubel et Schneider, 1996 ; Neggers et al., 2007). 

Par exemple, il a été prouvé que la sélection de la cible de la saccade est modulée par les mécanismes de reconnaissance des objets (Deubel et Schneider, 1996), et que l'attention visuelle influence directement la planification et l'exécution des saccades (Hoffman et Subramaniam, 1995). De plus, un couplage intime et rigide entre attention visuospatiale et mouvements oculaires a été mis en évidence (Neggers et al., 2007), le foyer attentionnel précédant obligatoirement le regard. Ce couplage peut être perturbé lorsque la stimulation magnétique transcrânienne (TMS) est appliquée sur les **champs oculaires frontaux (FEF)**, ce qui démontre l'existence d'un lien causal direct entre commande motrice oculaire et allocation attentionnelle (Neggers et al., 2007). 

Ces données suggèrent que le processus de planification motrice oculaire exerce une influence déterminante sur le traitement perceptif. Bien que les mécanismes intimes sous-tendant cette modulation fassent encore l'objet d'investigations, l'hypothèse prévalente invoque l'activité coordonnée de multiples structures cérébrales incluant le système saccadique, le système vestibulaire et les circuits attentionnels fronto-pariétaux.


<!-- ======================================================================= -->
<!-- PAGE 4                                                                  -->
<!-- ======================================================================= -->

### 1.2 Le domaine de la main (Effecteur manuel : Atteinte et Préhension)

Au cours des dernières décennies, la littérature scientifique a fourni des preuves irréfutables attestant que **la perception visuelle est directement biaisée par la planification des mouvements du membre supérieur**, tels que les gestes d'atteinte (*reaching*) et de préhension (*grasping*) (Müsseler et Hommel, 1997 ; Prinz, 1997 ; Craighero et al., 1999 ; Wohlschläger, 2000 ; Hommel et al., 2001 ; Knoblich et Flach, 2001 ; Wühr et Müsseler, 2001 ; Hamilton et al., 2004 ; Kunde et Wühr, 2004 ; Fagioli et al., 2007 ; Wykowska et al., 2009, 2011 ; Kirsch et al., 2012 ; Kirsch et Kunde, 2013 ; Kirsch, 2015). 

Du point de vue du sujet percevant, il est fascinant de constater que lorsqu'on planifie un geste d'atteinte ou de saisie vers un objet, la perception même de cet objet s'en trouve profondément altérée. Prenons le cas d'une personne tendant le bras vers une tasse de café : son système visuel prend en compte la localisation spatiale et l'orientation de la tasse par rapport à son corps. Or, les propriétés visuelles perçues de cette tasse sont simultanément façonnées par l'action motrice projetée, le système moteur devant calibrer ses paramètres cinématiques sur ces caractéristiques afin d'assurer une prise en main réussie. Ce constat révèle que **le système moteur ne se borne pas à exécuter des mouvements physiques : il participe activement à la configuration de la perception en fonction des intentions d'action de l'agent**. De fait, une multitude de dimensions perceptives — telles que l'orientation, la taille, la luminance, la position spatiale ou encore la trajectoire du mouvement — ont été documentées comme étant directement modulées par la planification motrice (Müsseler et Hommel, 1997 ; Craighero et al., 1999 ; Wohlschläger, 2000 ; Zwickel et al., 2007 ; Lindemann et Bekkering, 2009 ; Kirsch et al., 2012). Par exemple, les travaux de Kirsch ont démontré que la planification motrice interfère directement avec l'estimation des distances et, par voie de conséquence, avec la localisation spatiale de la cible (Kirsch et al., 2012 ; Kirsch et Kunde, 2013 ; Kirsch, 2015).

Cette interaction dynamique entre planification de l'action et perception est strictement subordonnée à la nature de la relation existant entre le but perceptif et l'action motrice :
* **Scénario de facilitation :** Lorsqu'il existe une relation directe et congruente entre le but visuel et l'action motrice, le traitement perceptif est grandement facilité par la préparation motrice ;
* **Scénario d'interférence :** À l'inverse, lorsque les deux processus sont mutuellement indépendants mais entrent en concurrence fonctionnelle, la planification de l'action dégrade et ralentit le traitement perceptif (Hommel et al., 2016).

Plusieurs études princeps conduites au tournant des années 1990 et 2000 ont magistralement illustré ces deux régimes d'interaction. Sur la base d'une série de cinq expériences élégantes, Müsseler et Hommel (1997) ont rapporté l'impact de la planification motrice sur la perception de la direction d'un stimulus visuel. La discrimination directionnelle (droite vs gauche) était directement influencée par la préparation concurrente d'une réponse motrice (pression sur un bouton droit ou gauche). Plus précisément, identifier la direction d'une flèche pointant vers la droite s'avérait significativement plus coûteux sur le plan cognitif et chronométrique lorsque le participant préparait simultanément une pression motrice sur le bouton droit (Müsseler et Hommel, 1997). Dans le cadre de la **Théorie du codage d'événements (TEC / *Theory of Event Coding*)** et de l'hypothèse d'un **code représentationnel commun** (*common coding*, Hommel et al., 2001), le fait de planifier une action motrice vers une direction précise engendre une situation de concurrence : la monopolisation des ressources de codage par le plan d'action (*share-code weighting*) privilégie temporairement le pôle moteur au détriment du pôle perceptif, induisant une forme de « cécité » ou d'inhibition perceptive transitoire (Müsseler et Hommel, 1997 ; Hommel et al., 2016).

Des travaux ultérieurs ont corroboré ce couplage fonctionnel étroit. Dans l'étude de Wohlschläger (2000), les participants devaient rapporter la direction perçue du déplacement de disques visuels projetés tout en tournant manuellement une molette dans une direction prescrite : la cinématique de la main biaisa systématiquement la direction perçue du mouvement visuel. Selon un protocole voisin de celui de Craighero et al. (1999), Lindemann et Bekkering (2009) ont demandé à des volontaires d'atteindre, de saisir puis de faire pivoter un manipulateur en forme de croix dès l'apparition d'un signal visuel de départ (*go signal*). Ici, une barre inclinée (-45° ou +45°) servait de signal de départ. Les participants détectaient l'apparition du signal visuel beaucoup plus rapidement dans les conditions congruentes, c'est-à-dire lorsque l'orientation de la barre et la direction de l'action planifiée coïncidaient (Lindemann et Bekkering, 2009). Ces résultats démontrent que **la perception est hautement facilitée le long de la dimension spatiale dans laquelle l'action motrice a été préalablement programmée**.

À l'inverse, tout comme Müsseler et Hommel (1997), Zwickel et al. (2007) ont observé un couplage action-perception sous un régime d'interférence : les temps de réaction s'allongeaient considérablement lorsque les déviations visuelles du stimulus correspondaient à la direction de la planification motrice (Zwickel et al., 2007). D'autres auteurs ont documenté des phénomènes similaires d'interférence motrice sur la perception (Schubö et al., 2001 ; Hamilton et al., 2004 ; Zwickel et al., 2010), confirmant que l'issue du couplage (facilitation ou interférence) dépend de l'arrimage fonctionnel entre la cible perceptive et le programme moteur activé.

Des recherches fondamentales récentes ont en outre démontré **la spécificité dimensionnelle du type de geste planifié dans le biaisage perceptif** (Bekkering et Neggers, 2002 ; Fagioli et al., 2007 ; Symes et al., 2008 ; Wykowska et al., 2009, 2011 ; Gutteling et al., 2011). Bekkering et Neggers (2002) ont instruit des participants à pointer (*pointing*) ou à saisir (*grasping*) un objet caractérisé par une orientation et une couleur déterminées. Les auteurs ont constaté que si le taux d'erreurs relatives à la couleur était identique entre les deux types de mouvements, **les erreurs d'orientation diminuaient drastiquement lors de la préparation d'un geste de préhension**.

De façon similaire, Gutteling et al. (2011) ont invité des volontaires à exécuter un mouvement de préhension ou de pointage tout en effectuant simultanément une tâche de discrimination d'orientation ou de luminance (voir **Figure 2**). La sensibilité perceptive à l'orientation augmentait de façon spectaculaire lors de la planification d'une préhension comparée à celle d'un simple pointage. La taille, la position et la luminance ont également été identifiées comme des attributs visuels dont le gain perceptif dépend sélectivement du type de planification motrice (Fagioli et al., 2007 ; Wykowska et al., 2009, 2011 ; Kirsch et al., 2012 ; Wykowska et Schubö, 2012 ; Kirsch et Kunde, 2013). 

Fagioli et al. (2007) ont révélé une double dissociation remarquable :
* La planification d'un geste de préhension (*grasping*) affine sélectivement la détection des variations de **taille** de l'objet ;
* La planification d'un geste d'atteinte (*reaching*) facilite quant à elle sélectivement la détection des variations de **position spatiale**.

Les travaux de Wykowska et al. (2009) et de Wykowska et Schubö (2012) ont confirmé et étendu cette dissociation fonctionnelle : planifier une saisie manuelle exalte le traitement de la taille, alors que planifier une atteinte sensibilise sélectivement à la luminance.

L'ensemble de ces données expérimentales converge vers le postulat d'un couplage unifié action(planification)-perception : **la préparation d'une action motrice amorce et sensibilise préférentiellement les dimensions visuelles critiques nécessaires à la réussite de cette action spécifique** (Hommel et al., 2001 ; Wykowska et al., 2009).

La grande majorité des études mentionnées ont démontré que le système moteur module dynamiquement les signaux sensoriels entrants. Néanmoins, ces modulations ont été pour l'essentiel observées dans des paradigmes où le signal perceptif était intriquée avec des mécanismes décisionnels et attentionnels directement liés à la réponse motrice (ex. Gutteling et al., 2011). Un pan déterminant de la recherche s'est donc attaché à explorer l'accordage temporel (*temporal tuning*) de l'information perceptive aux stades corticaux les plus précoces. 

Pour ce faire, divers travaux ont mesuré **la sensibilité au contraste** face à un bref stimulus visuel totalement indépendant de l'action motrice à effectuer, présenté à divers intervalles temporels au cours de la planification et de l'exécution motrices. Les chercheurs ont sélectionné la sensibilité au contraste précisément parce qu'elle reflète fidèlement l'activité du **cortex visuel primaire (V1)**, toute modulation de la visibilité du contraste requérant une régulation neurale à ce niveau cortical élémentaire (Boynton et al., 1999). 

Par ailleurs, des découvertes récentes ont établi que les processus sensoriels et moteurs sont régis par des dynamiques rythmiques sous-tendues par les oscillations de l'excitabilité neuronale (Buzsáki et Draguhn, 2004 ; Thut et al., 2012). En synthétisant ces approches, Tomassini et al. (2015) ont testé si des oscillations rythmiques de la sensibilité visuelle au contraste émergeaient lors de la synchronisation du signal perceptif avec l'initiation d'un mouvement d'atteinte et de préhension. Leurs résultats ont démontré que **des oscillations de la sensibilité au contraste se manifestent environ 500 ms avant le déclenchement du mouvement, en pleine phase de planification motrice, même lorsque le stimulus visuel testé est totalement étranger à la tâche motrice** (voir **Figure 3**). 

Ces observations ont été étendues dans une étude en électroencéphalographie (EEG), où la même équipe a démontré que la planification motrice s'arrime intimement aux oscillations neurales perceptives (Tomassini et al., 2017). Des oscillations perceptives synchronisées et « verrouillées sur l'action » (*action-locked oscillations*) ont également été identifiées lors de mouvements exécutés avec les yeux (Benedetto et Morrone, 2017 ; Benedetto et al., 2020). Dans ces travaux, les auteurs ont mis en évidence un couplage rigoureux entre la préparation saccadique et les oscillations de la sensibilité au contraste, suggérant un alignement fonctionnel précis entre le déclenchement de la saccade et la suppression visuelle transitoire (Benedetto et Morrone, 2017).

---

<!-- ======================================================================= -->
<!-- PAGE 5                                                                  -->
<!-- ======================================================================= -->

> #### **Figure 2 : Effet de la planification de la préhension et du pointage sur la détection d'orientation et de luminance**
> **(A) Paradigme expérimental :** Les expériences 1 et 2 utilisaient un dispositif visuel similaire comprenant un point de fixation et deux barres. Les participants devaient exécuter une action après un signal impératif (*go-cue*) déclenché par l'apparition de la première barre. La seconde barre présentait soit une légère rotation d'orientation (Expérience 1), soit une différence de luminance (Expérience 2) par rapport à la première.  
> **(B) Expérience 1 :** Les participants ont démontré une discrimination significativement supérieure de l'orientation lorsqu'ils planifiaient une action de **préhension** (*grasping*) plutôt qu'une action de **pointage** (*pointing*).  
> **(C) Expérience 2 :** Aucun changement consistant de discrimination de la luminance n'a été observé entre la planification de la préhension et celle du pointage. *(Adapté de Gutteling et al., 2011).*

---

<!-- ======================================================================= -->
<!-- PAGE 6                                                                  -->
<!-- ======================================================================= -->

> #### **Figure 3 : Oscillations rythmiques de la sensibilité au contraste synchronisées avec les mouvements de la main**
> **(A) Dispositif expérimental des tâches motrice et visuelle.**  
> **(B) Chronologie d'un essai :** Un bruit visuel et un point de fixation étaient affichés continuellement du début à la fin de l'essai. À un instant aléatoire, un stimulus de Gabor apparaissait dans le quadrant inférieur droit ou gauche de la fixation.  
> **(C) Évolution temporelle des réponses de discrimination d'orientation pour chaque participant, alignée sur l'initiation du mouvement de la main :** Les oscillations de la sensibilité au contraste émergent nettement environ 500 ms avant le début du geste moteur, témoignant d'un accordage cortical oscillatoire précoce en phase de planification. *(Adapté de Tomassini et al., 2015).*

---

### 1.3 Le domaine de la jambe et du corps entier (Effecteur locomoteur et Espace extrapersonnel)

Les travaux décrits jusqu'ici portent principalement sur **l'espace péripersonnel** (l'espace immédiatement accessible par les membres supérieurs). Toutefois, des recherches révèlent que l'impact de la planification motrice sur la perception s'étend également au domaine des effecteurs locomoteurs (les jambes et le corps entier), induisant des effets notables de facilitation sur la métrique de **l'espace extrapersonnel**.

Plusieurs études ont mis en évidence que lorsque nous observons des objets situés dans notre espace extrapersonnel, nous rééchelonnons la distance perçue en fonction de l'action motrice projetée. Par exemple, si nous prévoyons de marcher sur une certaine distance, nous évaluons celle-ci sur la base de la quantité d'effort locomoteur nécessaire pour la parcourir ; tandis que si nous prévoyons de lancer une balle vers cette cible, la distance perçue est calibrée sur la quantité d'effort biomécanique requise pour le lancer (Witt et al., 2004 ; Proffitt, 2006 ; Witt et Proffitt, 2008). 

La manière dont nous appréhendons notre environnement visuel apparaît ainsi profondément façonnée par les actions spécifiques que nous anticipons déployer, la perception s'ajustant dynamiquement selon **un principe optimal de coût-bénéfice bioénergétique** (Proffitt, 2006). 

Récemment, Fini et al. (2014, 2015a,b) ont employé un protocole immersif en réalité virtuelle afin de sonder l'influence des actions motrices projetées sur la métrique spatiale. Les participants devaient évaluer la position d'un objet placé à des distances progressivement croissantes ou décroissantes par rapport à un cadre de référence. Les auteurs ont constaté que **les participants percevaient l'objet cible comme étant significativement plus proche de leur propre corps lorsqu'ils avaient l'intention motrice de marcher vers lui**, comparativement à la condition où ils n'avaient aucune intention de se mouvoir. Cet effet de rapprochement spatial subjectif disparaissait lorsque l'objet cible devait être comparé à un autre objet physique statique (Fini et al., 2015a). 

En outre, des recherches ont établi que lorsque des actions impliquant les membres inférieurs (telles que la marche ou la course) sont amorcées cognitivement, la portion de l'espace extrapersonnel jugée comme « proche » selon des coordonnées égocentrées et allocentrées s'élargit substantiellement (Fini et al., 2017), parallèlement à **une véritable extension dynamique des frontières de l'espace péripersonnel lors de mouvements du corps entier (comme la marche active) comparativement à la station debout immobile** (Noel et al., 2015). 

Ces données démontrent de façon indiscutable que la perception visuelle de l'environnement physique au-delà de notre enveloppe corporelle est massivement influencée par nos intentions d'action, nos plans moteurs et nos capacités physiques réelles. De fait, la modalité primordiale d'exploration de l'environnement étendu réside dans la locomotion, celle-ci constituant l'unique moyen de franchir les distances et d'accéder aux informations issues de régions distantes de l'espace extrapersonnel, là où l'échantillonnage perceptif ne peut se satisfaire des sources de proximité (di Marco et al., 2019).


<!-- ======================================================================= -->
<!-- PAGE 6 (suite)                                                          -->
<!-- ======================================================================= -->

## 2. L'effet de l'exécution de l'action sur la perception

La capacité humaine à accomplir des actes moteurs influe directement en retour sur la perception visuelle des objets et des cibles de l'environnement. Ce constat constitue le socle théorique sur lequel s'appuient les modèles expliquant l'impact de l'exécution de l'action sur le traitement perceptif.

Les **effets spécifiques à l'action** (*action-specific effects*) désignent l'ensemble des modulations de la perception spatiale induites par la capacité motrice effective d'un agent à agir sur le monde (Proffitt, 2006, 2008). L'étude princeps ayant inauguré ce paradigme a été menée par Bhalla et Proffitt (1999). Ces chercheurs ont démontré que **l'estimation visuelle de l'inclinaison d'une colline est directement indexée sur le potentiel physiologique de l'observateur** : lorsque le coût bioénergétique requis pour gravir la pente augmente (par exemple en état de fatigue physique, sous l'effet du vieillissement ou lors du port d'un sac à dos lourd), la pente de la colline est systématiquement jugée comme étant plus abrupte qu'elle ne l'est physiquement.

À la suite de ce travail pionnier, de nombreuses recherches ont approfondi et élargi ce concept au-delà du seul potentiel métabolique en explorant d'autres facettes de la motricité :
* Les joueuses de softball les plus performantes à la frappe estiment la taille de la balle comme étant significativement plus volumineuse que leurs homologues moins habiles (Witt et Proffitt, 2005 ; Gray, 2013) ;
* Les archers réalisant les meilleurs tirs perçoivent la cible comme étant physiquement plus grande (Lee et al., 2012) ;
* Les adeptes de parkour jugent les murs à franchir comme étant moins hauts que les individus sédentaires (Taylor et al., 2011) ;
* Les joueurs de tennis expérimentés perçoivent le filet comme étant plus bas que les novices (Witt et Sugovic, 2010).

Une autre branche féconde consacrée aux effets spécifiques à l'action s'est attachée à analyser **la perception des affordances**, c'est-à-dire les opportunités concrètes d'action offertes par un objet ou un aménagement spatial (Gibson, 1979). Généralement, la mesure psychophysique de la perception des affordances consiste à déterminer le seuil critique à partir duquel une action motrice est jugée comme « tout juste réalisable ». Par exemple, divers travaux ont mesuré la largeur minimale d'un encadrement de porte perçue comme franchissable, ou la hauteur maximale d'une marche d'escalier permettant un enjambement direct (Warren, 1984 ; Mark, 1987 ; Warren et Whang, 1987). 

D'autres études ont montré que des individus présentant une carrure d'épaules plus large perçoivent les ouvertures de portes comme étant plus étroites que des personnes de morphologie plus menue (Stefanucci et Geuss, 2009). De même, lorsqu'une cible visuelle est placée au-delà de la portée normale du bras, elle est perçue comme significativement plus proche dès lors que le participant tient un râteau ou un outil d'extension de portée (*reach-extending tool*) lui permettant de l'atteindre, alors qu'elle paraît plus distante lorsque l'observateur agit sans cet instrument (Witt et al., 2005 ; Witt et Proffitt, 2008 ; Witt, 2011 ; Davoli et al., 2012 ; Osiurak et al., 2012 ; Morgado et al., 2013).

Fort de ces résultats remarquables, la section suivante examine les effets spécifiques à l'action sur la perception en fonction des effecteurs précis mobilisés, élargissant l'horizon à d'autres modes expérimentaux.

---

<!-- ======================================================================= -->
<!-- PAGE 7                                                                  -->
<!-- ======================================================================= -->

### 2.1 Le domaine de l'œil (Effecteur oculomoteur : Exécution de saccades)

Dans le registre oculomoteur, l'impact de l'exécution des saccades sur la perception a été minutieusement disséqué à travers deux mécanismes expérimentaux majeurs : **l'adaptation saccadique** et **la mauvaise localisation périsaccadique** (*perisaccadic mislocalization*).

L'adaptation saccadique permet aux chercheurs de mesurer comment l'amplitude d'une saccade s'ajuste en réponse à un déplacement artificiel de la cible visuelle déclenché en plein vol oculaire (*post-saccadic target shift*). Ce saut de cible peut s'effectuer de manière parallèle ou orthogonale à la direction principale de la saccade. Il est rigoureusement établi que le système oculomoteur recalibre automatiquement l'amplitude de ses saccades lorsqu'une cible de petite taille est décalée horizontalement pendant le mouvement de l'œil (McLaughlin, 1967 ; Miller et al., 1981 ; Deubel, 1987 ; Watanabe et al., 2003 ; Hopp et Fuchs, 2004 ; Kojima et al., 2005 ; Ethier et al., 2008 ; Rahmouni et Madelain, 2019).

Des travaux approfondis ont interrogé l'existence de coordonnées partagées entre le système saccadique et d'autres domaines moteurs. De fait, plusieurs équipes ont démontré que **la modification des paramètres moteurs induite par l'adaptation saccadique entraîne une distorsion concomitante de la position perçue de la cible**, que cette localisation spatiale soit évaluée par un geste de pointage manuel ou par un jugement perceptif verbal (Bahcall et Kowler, 1999 ; Awater et al., 2005 ; Bruno et Morrone, 2007 ; Collins et al., 2007 ; Zimmermann et Lappe, 2010 ; Garaas et Pomplun, 2011 ; Gremmler et al., 2014).

Une application particulièrement féconde du paradigme d'adaptation saccadique a été développée en utilisant des cibles spatialement étendues qui, en plein milieu de la trajectoire saccadique, modifient systématiquement leur dimension horizontale (Bosco et al., 2015), ainsi que dans l'étude des mouvements oculaires lors de la lecture (McConkie et al., 1989 ; Lavergne et al., 2010). Dans l'étude de Bosco et al. (2015), cette manipulation a directement influencé la perception visuelle de la taille de l'objet. 

**La modification de la taille perçue s'effectue rigoureusement dans le sens de l'adaptation de l'amplitude saccadique :**
* Si la saccade est adaptée vers une amplitude plus courte (*shortening adaptation*), la cible est ultérieurement perçue comme étant plus petite ;
* Si la saccade est adaptée vers une amplitude plus longue (*lengthening adaptation*), la cible est perçue comme étant significativement plus grande (Bosco et al., 2015).

Le schéma de ce protocole d'adaptation saccadique et la modification consécutive du jugement de taille — mesurée par l'écartement de la pince digitale manuelle (*grip aperture*) — sont illustrés à la **Figure 4**.

---

> #### **Figure 4 : Modification de la perception de taille induite par l'adaptation saccadique**
> **(A) Ligne supérieure : Condition d'adaptation au raccourcissement (*Shortening adaptation*).** Le point de fixation apparaît au début de l'essai. Après 1 seconde, une barre horizontale apparaît, mais les participants doivent maintenir leur regard sur le point de fixation. Après un délai aléatoire, un signal acoustique autorise l'exécution d'une saccade vers la barre. Dès que l'amorce de la saccade est détectée par l'oculomètre, la barre subit un rétrécissement instantané de 30 % de sa longueur par son bord droit.  
> **Ligne inférieure : Condition d'adaptation à l'allongement (*Lengthening adaptation*).** Condition identique, à l'exception près que la barre est allongée de 30 % pendant le vol de la saccade oculaire.  
> **(B) Déviation moyenne de l'ouverture de la pince manuelle (*grip aperture*) par rapport à la ligne de base** pour l'adaptation au raccourcissement (barres blanches) et à l'allongement (barres noires). Les données sont moyennées sur l'ensemble des sujets et des tailles de cibles. Les barres d'erreur représentent l'erreur standard (SE). \*p < 0,05, déviations statistiquement significatives par rapport à la ligne de base. *(Adapté de Bosco et al., 2015).*

---

<!-- ======================================================================= -->
<!-- PAGE 8                                                                  -->
<!-- ======================================================================= -->

Cependant, des études capitales ont récemment révélé qu'**une modification de la perception des propriétés visuelles peut survenir en l'absence totale de toute adaptation de l'amplitude saccadique** (Herwig et Schneider, 2014 ; Herwig et al., 2015, 2018 ; Valsecchi et Gegenfurtner, 2016 ; Paeye et al., 2018 ; Köller et al., 2020 ; Valsecchi et al., 2020). Ce phénomène de recalibration s'observe pour de multiples dimensions : la fréquence spatiale (Herwig et Schneider, 2014 ; Herwig et al., 2018), la forme géométrique (Herwig et al., 2015 ; Paeye et al., 2018 ; Köller et al., 2020) et la taille (Valsecchi et Gegenfurtner, 2016 ; Bosco et al., 2020 ; Valsecchi et al., 2020).

Par exemple, Bosco et al. (2020) ont conçu une manipulation consistant à raccourcir ou allonger symétriquement une **barre verticale** pendant l'exécution d'une **saccade horizontale**, de façon délibérée à **ne provoquer aucune modification de l'amplitude de la saccade motrice** (voir **Figure 5A**). Dans ces conditions strictes, les auteurs ont pourtant mis en évidence une différence hautement significative dans la taille perçue de l'objet après l'exécution de la saccade (voir **Figure 5B**). 

**Cette découverte établit une dissociation fondamentale : la modification de la perception de taille ne dépend pas de l'altération motrice de l'amplitude saccadique induite par les circuits périphériques d'adaptation**. Dans les travaux de Valsecchi et al. (2020), il a été montré que l'adaptation saccadique et la recalibration de la taille partagent une cinétique temporelle similaire. Toutefois, la recalibration de taille des stimuli visuels persistait même dans l'hémichamp opposé, alors que l'adaptation saccadique demeurait latéralisée, ce qui confirme l'implication de mécanismes neuraux distincts. 

Même si la modification des paramètres moteurs induite par l'adaptation saccadique n'est pas la cause mécanique directe de l'altération perceptive, **le basculement rapide de l'image de la cible de la périphérie rétinienne vers la fovéa — accompli par la saccade — demeure la cause première de la modification perceptive observée**.

---

> #### **Figure 5 : Modification de la perception de taille non induite par l'adaptation saccadique**
> **(A) Ligne supérieure : Condition de raccourcissement symétrique.** Dispositif identique à la Figure 4, mais la barre présentée est verticale et subit un rétrécissement symétrique de 30 % lors d'une saccade horizontale, ce qui n'altère en rien l'amplitude motrice de la saccade.  
> **Ligne inférieure : Condition d'allongement symétrique.** La barre verticale subit une extension symétrique de 30 % en plein vol saccadique.  
> **(B) Déviation moyenne du jugement de taille (ouverture de la pince digitale) par rapport à la ligne de base** pour les essais de raccourcissement (barres blanches) et d'allongement (barres noires). Les données démontrent une modification franche et significative de la taille perçue malgré l'absence absolue d'adaptation motrice de l'amplitude de la saccade oculaire. \*p < 0,05. *(Adapté de Bosco et al., 2020).*

---

<!-- ======================================================================= -->
<!-- PAGE 9                                                                  -->
<!-- ======================================================================= -->

Un pan considérable de la littérature en neurosciences visuelles a documenté que des stimuli présentés brièvement juste avant ou pendant le vol d'une saccade oculaire subissent **une mauvaise localisation spatiale systématique** et sont perçus comme étant nettement plus proches de la cible saccadique (Matin et Pearce, 1965 ; Honda, 1989 ; Schlag et Schlag-Rey, 1995 ; Ross et al., 1997). En d'autres termes, cette distorsion périsaccadique se manifeste sous deux facettes :
1. Un décalage de la position apparente dans la direction de la saccade (Honda, 1989, 1995 ; Schlag et Schlag-Rey, 1995 ; Cai et al., 1997 ; Lappe et al., 2000) ;
2. **Une compression spatiale massive** des positions perçues vers le point d'atterrissage fovéal de la saccade (Bischof et Kramer, 1968 ; Ross et al., 1997 ; Lappe et al., 2000).

Le décalage directionnel est classiquement attribué à un désaccord temporel (*mismatch*) entre la position mécanique réelle des globes oculaires pendant la saccade et la position prédite générée par **la décharge corollaire interne** (*internal corollary discharge* ou copie d'efférence motrice, Duhamel et al., 1992 ; Nakamura et Colby, 2002 ; Kusunoki et Goldberg, 2003 ; Morrone et al., 2005). 

Fait remarquable, **l'effet de compression spatiale s'observe principalement parallèlement à la trajectoire de la saccade** (Ross et al., 1997), mais également dans la dimension orthogonale (Kaiser et Lappe, 2004 ; Zimmermann et al., 2014, 2015), démontrant qu'une simple translation géométrique linéaire du repère de coordonnées internes est une explication réductrice. 

De surcroît, des attributs non spatiaux — tels que la forme et la couleur des stimuli périsaccadiques — ont été rigoureusement analysés pour évaluer l'étendue de cette compression. Il a été démontré que **la discrimination de la forme (Matsumiya et Uchikawa, 2001) et de la couleur (Lappe et al., 2006 ; Wittenberg et al., 2008) des stimuli visuels est parfaitement préservée**, bien que leur localisation spatiale soit fusionnée ou comprimée vers la cible. Bien que les substrats neuraux précis de ce phénomène demeurent débattus, la thèse générale envisage la mauvaise localisation périsaccadique comme le sous-produit direct des mécanismes corticaux voués au maintien de **la stabilité visuelle trans-saccadique** du monde extérieur malgré les déplacements incessants du regard (Matin et Pearce, 1965 ; Honda, 1989 ; Schlag et Schlag-Rey, 1995 ; Ross et al., 1997 ; Lappe et al., 2000 ; Pola, 2004 ; Binda et Morrone, 2018).


<!-- ======================================================================= -->
<!-- PAGE 9 (suite)                                                          -->
<!-- ======================================================================= -->

### 2.2 Le domaine de la main (Effecteur manuel : Exécution de l'atteinte et de la préhension)

L'exécution de différents types de mouvements de la main engendre des modifications perceptives directes portant sur les propriétés des objets déterminantes pour l'action engagée, au premier chef **la perception de la taille et du poids**.

En 2017, Bosco et al. ont investigué l'impact direct de l'exécution d'un geste d'atteinte (*reaching*) par rapport à un geste de préhension (*grasping*) sur le jugement de taille d'une cible visuelle. Leurs résultats ont révélé que **la modification du jugement de taille était significativement plus marquée après un geste de préhension qu'après un simple geste d'atteinte : l'ensemble des participants percevaient systématiquement l'objet comme étant plus petit après l'avoir saisi comparativement à la condition où ils l'avaient simplement atteint du doigt** (Bosco et al., 2017). Ces données se sont avérées d'une rigoureuse cohérence tant au niveau des réponses manuelles (écartement de la pince digitale) que des jugements verbaux directs (voir **Figure 6**).

Dans le prolongement de ces travaux, Sanz Diez et al. (2022) ont évalué la perception de la taille consécutivement à un geste de préhension dirigé vers une cible visuelle dont les dimensions étaient modifiées de façon imprévisible en cours de mouvement. Bien que la cible visuelle présentée lors de la phase de test perceptif pré- et post-mouvement fût physiquement identique, les auteurs ont découvert qu'après l'action de préhension, les estimations perceptives divergeaient significativement selon la nature de la perturbation survenue pendant l'action :
* Comme le montre la **Figure 7**, les observateurs rapportaient une perception de taille significativement **réduite** lorsque la cible avait été **allongée** durant l'exécution de la saisie ;
* En revanche, aucune modification perceptive n'était constatée lorsque la cible avait été **raccourcie** au cours du geste (Sanz Diez et al., 2022).

Dans ces deux protocoles, la réévaluation perceptive s'opère fidèlement en fonction de la dynamique motrice spécifique (atteinte vs préhension) et des perturbations imprévisibles survenues pendant le vol de la main. Cela démontre de manière exemplaire que **la perception visuelle post-action se comporte comme un paramètre descriptif rétrospectif (*descriptive parameter*) de l'action motrice venant d'être accomplie** (Bosco et al., 2017 ; Sanz Diez et al., 2022).

---

> #### **Figure 6 : Modification de la perception de taille après des actions d'atteinte (*reaching*) vs de préhension (*grasping*)**
> **(A) Déviation moyenne des réponses perceptives mesurées par l'ouverture de la pince digitale (*grip aperture*)** pour l'atteinte (colonnes blanches) et la préhension (colonnes noires).  
> **(B) Déviation moyenne des rapports perceptifs verbaux** pour l'atteinte (colonnes blanches) et la préhension (colonnes noires). Toutes les données sont moyennées sur l'ensemble des participants et des tailles de stimuli. Les barres d'erreur représentent l'erreur standard de la moyenne (SEM). \*p < 0,05, différence statistiquement significative démontrant une sous-estimation systématique et marquée de la taille de l'objet consécutive à la préhension. *(Adapté de Bosco et al., 2017).*

---

<!-- ======================================================================= -->
<!-- PAGE 10                                                                 -->
<!-- ======================================================================= -->

Un bénéfice adaptatif majeur découlant de l'impact de l'exécution motrice sur la perception réside dans les réorganisations du système moteur acquises lors de **l'apprentissage d'habiletés sensorimotrices**. L'encodage et la réactivation de mémoires sensorimotrices forgées par les interactions manuelles antérieures avec les objets constituent le pilier de l'apprentissage de la manipulation experte (Westling et Johansson, 1984 ; Johansson et Westling, 1988). Ce mécanisme permet notamment d'ajuster les forces de serrage des doigts selon un mode hautement anticipatoire, c'est-à-dire bien avant le décollement physique de l'objet du plan de travail (Gordon et al., 1993 ; Burstedt et al., 1999 ; Salimi et al., 2000). 

Dans des tâches obligeant les participants à soulever un objet tout en neutralisant le couple de renversement (*roll*) provoqué par une distribution asymétrique de sa masse, l'apprentissage implicite consécutif à l'action conduit à l'annihilation du basculement grâce à une reconfiguration dynamique de la position des doigts sur l'objet (Lukos et al., 2007, 2008) et à une modulation optimale de la répartition des forces exercées par chacun des doigts (Salimi et al., 2000 ; Fu et al., 2010).

Dans cette même perspective théorique, il convient de souligner le cas emblématique de **l'illusion taille-poids (SWI / *Size-Weight Illusion*)**, décrite pour la toute première fois par Augustin Charpentier (1891). L'illusion de Charpentier se manifeste avec éclat lorsqu'un individu soulève deux objets de volumes disparates mais de masse rigoureusement identique : l'objet le plus petit est immanquablement jugé comme étant nettement plus lourd que le grand. L'illusion taille-poids est d'une remarquable robustesse psychophysique (Murray et al., 1999 ; Flanagan et Beltzner, 2000 ; Kawai, 2002a,b, 2003a,b ; Grandy et Westwood, 2006 ; Dijker, 2008 ; Flanagan et al., 2008 ; Chouinard et al., 2009) ; l'effet illusoire persiste même lorsque le sujet sait pertinemment à l'avance que les deux objets ont un poids rigoureusement identique (Flanagan et Beltzner, 2000).

L'illusion taille-poids a été intensément étudiée pour élucider les mécanismes d'intégration des signaux multisensoriels concourant à la perception du poids ; elle constitue l'exemple paradigmatique d'un **fonctionnement sensorimoteur bayésien**. Selon cette modélisation, le système nerveux central combine un savoir préalable acquis par l'expérience motrice passée (l'**a priori** ou *prior* — stipulant qu'un objet plus volumineux est habituellement plus pesant) avec l'information sensorielle courante (la **vraisemblance** ou *likelihood*), afin de calculer une estimation optimale de la propriété physique (l'**a posteriori** ou *posterior*) dévolue aux fonctions perceptives et motrices (van Beers et al., 2002 ; Körding et Wolpert, 2006). 

Dans la majorité des contextes écologiques, l'intégration du *prior* et de la vraisemblance génère une perception exacte et un comportement adapté ; toutefois, le système peut être induit en erreur. Dans le cas de l'illusion taille-poids, la pondération de l'a priori s'avère excessivement dominante par rapport à la vraisemblance sensorielle, engendrant une distorsion perceptive spectaculaire qui ne reflète pas les propriétés physiques réelles de la masse soulevée. Néanmoins, la réitération de l'action de levage recalibre progressivement le système moteur : l'ajustement des forces cinématiques se synchronise avec le poids physique réel dès les essais suivants, même si le biais perceptif subjectif perdure. Quoi qu'il en soit du débat théorique sur la genèse de l'illusion, un fait demeure indiscutable : **l'exécution de l'action de manipulation sur les objets exerce un effet pragmatique décisif sur la calibration conjointe du poids et de la taille**.

---

> #### **Figure 7 : Modification de la perception de taille après une préhension perturbée dynamiquement**
> **(A) Séquence chronologique de la tâche :** Les participants effectuent une préhension manuelle vers une cible qui subit une perturbation imprévisible de dimension (allongement ou raccourcissement) pendant le mouvement.  
> **(B) Déviation moyenne de l'ouverture de la pince digitale (*grip aperture*) par rapport à la ligne de base**, moyennée selon les conditions de perturbation. Une cible allongée pendant le geste de saisie induit consécutivement une perception de taille significativement plus petite. \*p < 0,05. *(Adapté de Sanz Diez et al., 2022).*

---

### 2.3 Le domaine de la jambe et du corps entier (Effecteur locomoteur : Marche et Espace)

L'interaction active par la marche engendre une recalibration bidirectionnelle du couplage perception-action, habituellement investiguée par la mesure de la taille perçue ou de la distance perçue. Ce lien découle directement de **l'hypothèse d'invariance taille-distance** (Sedgwick, 1986), en vertu de laquelle l'estimation de la taille et celle de la distance spatiale sont indissolublement liées au plan géométrique et optique.

Bien que Brenner et van Damme (1999) aient suggéré une indépendance relative entre les estimations de forme, de taille et d'éloignement, de nombreux travaux confirment que les jugements perceptifs de distance et de dimension sont intimement intriqués dans la plupart des situations dynamiques (Gogel et al., 1985 ; Hutchison et Loomis, 2006).

Des données fondamentales démontrant une amélioration spectaculaire de l'exactitude des jugements de distance consécutivement à une interaction locomotrice active ont été apportées par Waller et Richardson (2008). De manière cruciale, ces auteurs ont prouvé que **l'estimation des distances au sein d'un environnement virtuel ne subissait aucune amélioration lorsque les participants étaient confrontés à une simple simulation visuelle passive de marche (flux optique pur)**. Ce résultat démontre formellement qu'**un mouvement corporel physique actif (*body-based movement*) est rigoureusement nécessaire** pour opérer la recalibration métrique de l'espace. 

Dans cette optique, la précision des estimations spatiales augmente de façon remarquable après des épreuves de **marche à l'aveugle** (*blind-walking tasks*) assorties d'une rétroaction visuelle ou verbale terminale (Richardson et Waller, 2005 ; Mohler et al., 2006), confirmant la primauté de l'interaction motrice corporelle. Kelly et al. (2013) ont par ailleurs constaté que les jugements perceptifs de la taille des objets s'affinaient significativement à la suite d'un épisode de marche active, cet ajustement étant médié par une réévaluation conjointe de la distance perçue. 

Le fait que l'estimation perceptive de la taille s'améliore après l'interaction motrice indique que **la marche active ne se réduit pas à une simple recalibration métrique de la distance parcourue : elle induit un véritable rééchelonnement (*rescaling*) global de la perception de l'espace visuel** (Siegel et al., 2017).

Dans les tâches de marche à l'aveugle en boucle ouverte (*open-loop blind walking*), la calibration et la recalibration de la locomotion humaine ont pu être analysées avec une grande finesse psychophysique. Dans ces paradigmes, l'observateur fixe une cible posée sur le sol, ferme les yeux, puis se déplace vers elle sans aucun retour visuel. Dans les conditions de contrôle normales, la performance en marche aveugle fait preuve d'une exactitude frappante et reflète parfaitement la position spatiale perçue de la cible (Rieser et al., 1990 ; Loomis et Philbeck, 2008). 

Toutefois, lorsqu'on manipule artificiellement le débit du flux optique environnemental par rapport à la cadence biomécanique réelle de la marche :
* Les observateurs **sous-estiment** la distance et s'arrêtent avant la cible (*undershoot*) lorsque le flux optique défile plus rapidement que la marche normale ;
* Ils **dépassent** systématiquement la cible (*overshoot*) lorsque le flux optique défile plus lentement que la vitesse normale de progression corporelle (Rieser et al., 1995).

De surcroît, les travaux examinant la perception visuelle des distances égocentriques ont mis en lumière une dissociation fascinante : alors que les jugements perceptifs explicites (tels que les rapports verbaux) manifestent **une sous-estimation systématique et prononcée des distances physiques égocentrées** (Foley, 1977 ; Li et Giudice, 2013), **la marche les yeux bandés dirigée vers cette même cible mémorisée s'exécute avec une remarquable exactitude métrique** (Loomis et al., 1992 ; Li et Giudice, 2013). Bien que l'espace visuel statique fasse l'objet d'une compression géométrique subjective, la locomotion finalisée échappe à cette distorsion perceptive et préserve l'intégrité de l'acte moteur.

---

<!-- ======================================================================= -->
<!-- PAGE 11                                                                 -->
<!-- ======================================================================= -->

> #### **Figure 8 : Modulation synoptique de la perception des objets et de l'espace par la planification et l'exécution motrices à travers les différents effecteurs**
> Schéma récapitulatif synthétisant l'ensemble des interactions démontrées dans cette revue :  
> 1. **Phase de planification (En amont) :** L'œil anticipe l'action de 0,8 à 1,1 s et induit un rehaussement spatial pré-saccadique ; la main amorce les traits visuels congruents (préhension $
ightarrow$ orientation/taille ; atteinte $
ightarrow$ position/luminance) et déclenche des oscillations neurales de sensibilité au contraste ~500 ms avant le mouvement ; la jambe/corps comprime la distance perçue selon le coût bioénergétique et élargit l'espace péripersonnel.  
> 2. **Phase d'exécution et post-action (En aval) :** Les saccades provoquent une compression spatiale et une recalibration de taille trans-saccadique ; la préhension réduit subjectivement la taille perçue de l'objet et recalibre les forces de levage (illusion taille-poids bayésienne) ; la marche active recalibre globalement l'échelle métrique de l'espace extrapersonnel.

---

<!-- ======================================================================= -->
<!-- PAGE 11 (suite) & PAGE 12                                               -->
<!-- ======================================================================= -->

## 3. Conclusions et perspectives d'avenir

Une multitude de travaux convergents ont été présentés ici, démontrant sans équivoque **l'impact des actions exécutées par les yeux, les mains et les jambes sur la perception visuelle des objets et de l'espace**, à travers une riche palette d'approches méthodologiques et de paradigmes psychophysiques. 

L'influence de l'action se manifeste avec force **aussi bien en amont (avant) qu'en aval (après) l'exécution physique du mouvement**. Cela suggère que la perception visuelle, lorsqu'elle est intimement intégrée à l'action motrice :
1. Se trouve dans un état « **prêt à agir** » (*ready to act*) avant l'exécution du geste ;
2. Est **profondément transformée et recalibrée** par l'exécution même de l'acte moteur (voir la **Figure 8** pour une synthèse globale).

Dans les deux cas de figure, les réponses perceptives — recueillies sous différentes modalités expérimentales — constituent de véritables **paramètres descriptifs qui qualifient les réponses motrices antérieures ou subséquentes**. Cette dynamique postule l'existence d'un mécanisme de dialogue bidirectionnel continu, échangeant des flux constants d'informations entre les systèmes perceptif et moteur dès lors que l'organisme est engagé dans une contingence visuomotrice spécifique.

Au plan comportemental, nous pouvons tirer un parti considérable de ces mécanismes :
* En phase de **planification motrice**, les modulations perceptives peuvent être exploitées comme **des prédicteurs directs des intentions d'action de l'agent** ;
* Après **l'exécution de l'action**, les modifications perceptives constituent, de manière hautement stimulante, **une composante postdictive** (*postdictive component*) qui encode l'expérience motrice passée. Dans ce dernier cas, cette composante postdictive actualise et met à jour en boucle fermée les paramètres sensorimoteurs indispensables à l'ajustement d'une action subséquente potentielle.

### Applications technologiques et Intelligence Artificielle (IA)

L'exploitation des informations perceptives ancrées dans l'action ouvre des perspectives technologiques majeures pour l'ensemble des systèmes d'**intelligence artificielle (IA)** couplés à des **dispositifs d'assistance motrice et de cobotique** (interfaces cerveau-machine, neuroprothèses, exosquelettes).

En effet :
1. **Pendant la planification de l'action :** L'extraction de signaux perceptifs spécifiques peut être intégrée à d'autres biomarqueurs (notamment les signaux électrophysiologiques et neuraux) afin de **décoder en amont les intentions motrices de l'utilisateur**. Une telle architecture permet de tirer parti des capacités motrices résiduelles chez des patients moteurs déficitaires (par exemple en détectant l'intention d'appuyer sur une commande, de mobiliser un effecteur ou d'étendre sélectivement certains doigts plutôt que d'autres à partir de la seule reconfiguration précoce de leur sensibilité visuelle).
2. **Après l'exécution de l'action :** L'intégration des données perceptives consécutives au geste peut être directement implémentée au cœur des agents artificiels interactifs appelés à coopérer étroitement avec des opérateurs humains, dans le but d'établir **un apprentissage mutuel et symbiotique** (*mutual learning exchange*). En pratique, la modification fine de la perception survenant après un geste spécifique peut servir de **signal d'erreur et de rétroaction biologique (*feedback signal*)** pour corriger immédiatement les commandes motrices subséquentes et compenser les erreurs découlant d'une décision d'action erronée prise par le système d'IA.

Ce couplage prédictif et postdictif fermé permettrait au système autonome d'optimiser en temps réel l'issue cinématique de l'action partagée, renforçant de manière décisive **la confiance mutuelle (*trust*) de l'utilisateur humain envers le système d'intelligence artificielle**.

---

### Contributions des auteurs

* **Annalisa Bosco (AB) :** Conceptualisation, visualisation, rédaction du manuscrit original (*writing original draft*), révision critique et édition.
* **Pablo Sanz Diez (PSD) :** Visualisation et rédaction du manuscrit original.
* **Matteo Filippini (MF) :** Révision critique et édition.
* **Patrizia Fattori (PF) :** Révision critique et édition, acquisition des financements.
* *Tous les auteurs ont activement contribué à l'article et ont validé la version définitive soumise pour publication.*

### Financement et déclarations

* Le projet **MAIA** a bénéficié d'un financement du programme de recherche et d'innovation *Horizon 2020* de l'Union européenne au titre de la convention de subvention n° 951910.
* Financement complémentaire accordé par le *Ministero dell'Istruzione, dell'Università e della Ricerca* (MIUR, Italie).
* **Conflit d'intérêts :** L'auteur Pablo Sanz Diez est employé par l'entreprise Carl Zeiss Vision International GmbH. Les autres auteurs déclarent que cette recherche a été menée en l'absence totale de relations commerciales ou financières pouvant être interprétées comme un conflit d'intérêts potentiel.



---

## Références bibliographiques

References

Angel, R. W., Alston, W., and Garland, H. (1970). Functional relations between the manual and oculomotor control systems. Exp. Neurol. 27, 248–257. doi: 10.1016/0014-4886(70)90218-9

Awater, H., Burr, D., Lappe, M., Morrone, M. C., and Goldberg, M. E. (2005). Eﬀect of saccadic adaptation on localization of visual targets. J. Neurophysiol. 93, 3605–14. doi: 10.1152/jn.01013.2003

Bagesteiro, L. B., Sarlegna, F. R., and Sainburg, R. L. (2006). Diﬀerential inﬂuence of vision and proprioception on control of movement distance. Exp. Brain Res. 171, 358. doi: 10.1007/s00221-005-0272-y

Bahcall, D. O., and Kowler, E. (1999). Illusory shifts in visual direction accompany adaptation of saccadic eye movements. Nature 400, 864–6. doi: 10.1038/ 23693

Bekkering, H., Adam, J. J., van den Aarssen, A., Kingma, H., and Whiting, H. T. A. (1995). Interference between saccadic eye and goal-directed hand movements. Exp. Brain. Res. 106, 475–484. doi: 10.1007/BF00231070

Bekkering, H., Adam, Jos, J., Kingma, H., Huson, A., and Whiting, H. T. A. (1994). Reaction time latencies of eye and hand movements in single- and dual-task conditions. Exp. Brain. Res. 97, 12. doi: 10.1007/BF00241541

Bekkering, H., and Neggers, S. F. (2002). Visual search is modulated by action intentions. Psychol. Sci. 13, 370–374. doi: 10.1111/j.0956-7976.2002.00466.x

Benedetto, A., and Morrone, M. C. (2017). Saccadic suppression is embedded within extended oscillatory modulation of sensitivity. J. Neurosci. 37, 3661. doi: 10.1523/JNEUROSCI.2390-16.2016

Benedetto, A., Morrone, M. C., and Tomassini, A. (2020). The common rhythm of action and perception. J. Cogn. Neurosci. 32, 187–200. doi: 10.1162/jocn_a_01436

Bernstein, N. (1967). The Co-Ordination and Regulation of Movements. Oxford: Pergamon Press.

Bhalla, M., and Proﬃtt, D. R. (1999). Visual–motor recalibration in geographical slant perception. J. Exp. Psychol. Hum. Percept. Perform. 25, 1076–1096. doi: 10.1037/0096-1523.25.4.1076

Biguer, B., Jeannerod, M., and Prablanc, C. (1982). The coordination of eye, head, and arm movements during reaching at a single visual target. Exp. Brain. Res. 46, 301–304. doi: 10.1007/BF00237188

Binda, P., and Morrone, M. C. (2018). Vision during saccadic eye movements. Annu. Rev. Vis. Sci. 4, 193–213. doi: 10.1146/annurev-vision-091517-034317

Bischof, N., and Kramer, E. (1968). Untersuchungen und berlegungen zur Richtungswahrnehmung bei willkrlichen sakkadischen Augenbewegungen. Psychol. Forsch. 32, 185–218. doi: 10.1007/BF00418660

Bosco, A., Daniele, F., and Fattori, P. (2017). Reaching and grasping actions and their context shape the perception of object size. J. Vis. 17, 10. doi: 10.1167/17.12.10

Bosco, A., Lappe, M., and Fattori, P. (2015). Adaptation of saccades and perceived size after trans-saccadic changes of object size. J. Neurosci. 35, 14448–14456. doi: 10.1523/JNEUROSCI.0129-15.2015

Bosco, A., Rifai, K., Wahl, S., Fattori, P., and Lappe, M. (2020). Trans-saccadic adaptation of perceived size independent of saccadic adaptation. J. Vis. 20, 19. doi: 10.1167/jov.20.7.19

Bourdin, C., Bringoux, L., Gauthier, G. M., and Vercher, J. L. (2006). Vision of the hand prior to movement onset allows full motor adaptation to a multi-force environment. Brain. Res. Bull. 71, 101–110. doi: 10.1016/j.brainresbull.2006.08.007

Boynton, G. M., Demb, J. B., Glover, G. H., and Heeger, D. J. (1999). Neuronal basis of contrast discrimination. Vision Res. 39, 257–269. doi: 10.1016/S0042-6989(98)00113-8

Brenner, E., and van Damme, W. J. M. (1999). Perceived distance, shape and size. Vision Res. 39, 975–986. doi: 10.1016/S0042-6989(98)00162-X

Brouwer, A.-M., Franz, V. H., and Gegenfurtner, K. R. (2009). Diﬀerences in ﬁxations between grasping and viewing objects. J. Vis. 9, 1–24. doi: 10.1167/9.1.18

Bruno, A., and Morrone, M. C. (2007). Inﬂuence of saccadic adaptation on spatial localization: comparison of verbal and pointing reports. J. Vis. 7, 1–13. doi: 10.1167/7.5.16

Burstedt, M. K. O., Flanagan, J. R., and Johansson, R. S. (1999). Control of grasp stability in humans under diﬀerent frictional conditions during multidigit manipulation. J. Neurophysiol. 82, 2393–2405. doi: 10.1152/jn.1999.82.5.2393

Buzsáki, G., and Draguhn, A. (2004). Neuronal oscillations in cortical networks. Science 304, 1926–1929. doi: 10.1126/science.1099745

Cai, R. H., Pouget, A., Schlag-Rey, M., and Schlag, J. (1997). Perceived geometrical relationships aﬀected by eye-movement signals. Nature 386, 601–604. doi: 10.1038/386601a0

Charpentier, A. (1891). Analyse experimentale de quelques elements de la sensation de poids. Arch. Physiol. Norm. Pathol. 3, 122–135.

Chouinard, P., Large, M., Chang, E., and Goodale, M. (2009). Dissociable neural mechanisms for determining the perceived heaviness of objects and the predicted weight of objects during lifting: An fMRI investigation of the size–weight illusion. Neuroimage 44, 200–212. doi: 10.1016/j.neuroimage.2008. 08.023

Coello, Y., and Grealy, M. A. (1997). Eﬀect of size and frame of visual ﬁeld on the accuracy of an aiming movement. Perception 26, 287–300. doi: 10.1068/p260287 12

Collins, T., Doré-Mazars, K., and Lappe, M. (2007). Motor space structures perceptual space: evidence from human saccadic adaptation. Brain Res. 1172, 32–39. doi: 10.1016/j.brainres.2007.07.040

Conti, P., and Beaubaton, D. (1980). Role of structured visual ﬁeld and visual reaﬀerence in accuracy of pointing movements. Percept. Mot. Skills 50, 239–244. doi: 10.2466/pms.1980.50.1.239

Craighero, L., Fadiga, L., Rizzolatti, G., and Umiltà, C. (1999). Action for perception a motor—visual attentional eﬀect. J. Exp. Psychol. Hum. Percept. Perform. 25, 1673–1692. doi: 10.1037/0096-1523.25.6.1673

Davoli, C. C., Brockmole, J. R., and Witt, J. K. (2012). Compressing perceived distance with remote tool-use: Real, imagined, and remembered. J. Exp. Psychol. Hum. Percept. Perform. 38, 80–89. doi: 10.1037/a0024981 de Brouwer, A. J., Flanagan, J. R., and Spering, M. (2021). Functional use of eye movements for an acting system. Trends Cogn. Sci. 25, 252–263. doi: 10.1016/j.tics.2020.12.006

Desmurget, M., Pélisson, D., Rossetti, Y., and Prablanc, C. (1998). “From eye to hand: planning goal-directed movements,” in Neuroscience and Biobehavioral Reviews, p. 761–788. doi: 10.1016/S0149-7634(98)00004-9

Desmurget, M., Rossetti, Y., Jordan, M., Meckler, C., and Prablanc, C. (1997). Viewing the hand prior to movement improves accuracy of pointing performed toward the unseen contralateral hand. Exp. Brain. Res. 115, 180–186. doi: 10.1007/PL00005680

Desmurget, M., Rossetti, Y., Prablanc, C., Jeannerod, M., and Stelmach, G. E. (1995). Representation of hand position prior to movement and motor variability. Can. J. Physiol. Pharmacol. 73, 262–272. doi: 10.1139/y95-037

Deubel, H. (1987). “Adaptivity of gain and direction in oblique saccades.,” in Eye movements from physiology to cognition. (London: Elsevier), p. 181–190. doi: 10.1016/B978-0-444-70113-8.50030-8

Deubel, H., and Schneider, W. X. (1996). Saccade target selection and object recognition: evidence for a common attentional mechanism. Vision. Res. 36, 1827–1837. doi: 10.1016/0042-6989(95)00294-4 di Marco, S., Tosoni, A., Altomare, E. C., Ferretti, G., Perrucci, M. G., and Committeri, G. (2019). Walking-related locomotion is facilitated by the perception of distant targets in the extrapersonal space. Sci. Rep. 9, 9884. doi: 10.1038/s41598-019-46384-5

Dijker, A. J. M. (2008). Why Barbie feels heavier than Ken: the inﬂuence of size- based expectancies and social cues on the illusory perception of weight. Cognition 106, 1109–1125. doi: 10.1016/j.cognition.2007.05.009

Duhamel, J.-R., Colby, C. L., and Goldberg, M. E. (1992). The updating of the representation of visual space in parietal cortex by intended eye movements. Science 255, 90–92. doi: 10.1126/science.1553535

Elliott, D., Dutoy, C., Andrew, M., Burkitt, J. J., Grierson, L. E. M., Lyons, J. L., et al. (2014). The inﬂuence of visual feedback and prior knowledge about feedback on vertical aiming strategies. J. Mot. Behav. 46, 433–443. doi: 10.1080/00222895.2014.933767

Elliott, D., Garson, R. G., Goodman, D., and Chua, R. (1991). Discrete vs. continuous visual control of manual aiming. Hum. Mov. Sci. 10, 393–418. doi: 10.1016/0167-9457(91)90013-N Ethier, V., Zee, D. S., and Shadmehr, R. (2008). Changes in control of saccades during gain adaptation. J. Neurosci. 28, 13929 LP–13937. doi: 10.1523/JNEUROSCI.3470-08.2008

Fagioli, S., Hommel, B., and Schubotz, R. I. (2007). Intentional control of attention: action planning primes action-related stimulus dimensions. Psychol. Res. 71, 22–29. doi: 10.1007/s00426-005-0033-3

Fini, C., Bardi, L., Troje, N. F., Committeri, G., and Brass, M. (2017). Priming biological motion changes extrapersonal space categorization. Acta. Psychol. 172, 77–83. doi: 10.1016/j.actpsy.2016.11.006

Fini, C., Brass, M., and Committeri, G. (2015a). Social scaling of extrapersonal space: target objects are judged as closer when the reference frame is a human agent with available movement potentialities. Cognition 134, 50–56. doi: 10.1016/j.cognition.2014.08.014

Fini, C., Committeri, G., Müller, B. C. N., Deschrijver, E., and Brass, M. (2015b). How watching pinocchio movies changes our subjective experience of extrapersonal space. PLoS One 10, e0120306. doi: 10.1371/journal.pone.0120306

Fini, C., Costantini, M., and Committeri, G. (2014). Sharing space: the presence of other bodies extends the space judged as near. PLoS One 9, e114719. doi: 10.1371/journal.pone.0114719

Flanagan, J. R., and Beltzner, M. A. (2000). Independence of perceptual and sensorimotor predictions in the size–weight illusion. Nat. Neurosci. 3, 737–741. doi: 10.1038/76701

Flanagan, J. R., Bittner, J. P., and Johansson, R. S. (2008). Experience can change distinct size-weight priors engaged in lifting objects and judging their weights. Curr. Biol. 18, 1742–1747. doi: 10.1016/j.cub.2008.09.042

Flanagan, J. R., and Rao, A. K. (1995). Trajectory adaptation to a non-linear visuomotor transformation: evidence of motion planning in visually perceived space. J. Neurophysiol. 74, 2174–2178. doi: 10.1152/jn.1995.74.5.2174

Foley, J. M. (1977). Eﬀect of distance information and range on two indices of visually perceived distance. Perception 6, 449–460. doi: 10.1068/p060449

Fu, Q., Zhang, W., and Santello, M. (2010). Anticipatory planning and control of grasp positions and forces for dexterous two-digit manipulation. J. Neurosci. 30, 9117–9126. doi: 10.1523/JNEUROSCI.4159-09.2010

Garaas, T. W., and Pomplun, M. (2011). Distorted object perception following whole-ﬁeld adaptation of saccadic eye movements. J. Vis. 11, 2. doi: 10.1167/11.1.2

Gibson, J. (1979). The Ecological Approach to Visual Perception. New York, NY: Houghton Miﬄin.

Gogel, W. C., Loomis, J. M., Newman, N. J., and Sharkey, T. J. (1985). Agreement between indirect measures of perceived distance. Percept. Psychophys. 37, 17–27. doi: 10.3758/BF03207134

Gordon, A. M., Westling, G., Cole, K. J., and Johansson, R. S. (1993). Memory representations underlying motor commands used during manipulation of common and novel objects. J. Neurophysiol. 69, 1789–1796. doi: 10.1152/jn.1993.69. 6.1789

Grandy, M. S., and Westwood, D. A. (2006). Opposite perceptual and sensorimotor responses to a size-weight illusion. J. Neurophysiol. 95, 3887–3892. doi: 10.1152/jn.00851.2005

Gray, R. (2013). Being selective at the plate: processing dependence between perceptual variables relates to hitting goals and performance. J. Exp. Psychol. Hum. Percept. Perform. 39, 1124–1142. doi: 10.1037/a0030729 Gremmler, S., Bosco, A., Fattori, P., and Lappe, M. (2014). Saccadic adaptation shapes visual space in macaques. J. Neurophysiol. 111, 1846–1851. doi: 10.1152/jn.00709.2013

Gutteling, T. P., Kenemans, J. L., and Neggers, S. F. W. (2011). Grasping preparation enhances orientation change detection. PLoS One 6, 11. doi: 10.1371/journal.pone.0017675 Hamilton, A., Wolpert, D., and Frith, U. (2004). Your own action inﬂuences how you perceive another person’s action. Curr. Biol. 14, 493–498. doi: 10.1016/j.cub.2004.03.007

Hayhoe, M. M. (2017). Vision and action. Ann. Rev. Vis. Sci. 3, 389–413. doi: 10.1146/annurev-vision-102016-061437

Hayhoe, M. M., Shrivastava, A., Mruczek, R., and Pelz, J. B. (2003). Visual memory and motor planning in a natural task. J. Vis. 3, 6. doi: 10.1167/3.1.6

Herwig, A., and Schneider, W. X. (2014). Predicting object features across saccades: evidence from object recognition and visual search. J. Exp. Psychol. Gen. 143, 1903–1922. doi: 10.1037/a0036781

Herwig, A., Weiß, K., and Schneider, W. X. (2015). When circles become triangular: how transsaccadic predictions shape the perception of shape. Ann. N Y Acad. Sci. 1339, 97–105. doi: 10.1111/nyas.12672

Herwig, A., Weiß, K., and Schneider, W. X. (2018). Feature prediction across eye movements is location speciﬁc and based on retinotopic coordinates. J. Vis. 18, 13. doi: 10.1167/18.8.13 Hoﬀman, J. E., and Subramaniam, B. (1995). The role of visual attention in saccadic eye movements. Percept. Psychophys. 57, 787–795. doi: 10.3758/BF03206794

Hommel, B., Brown, S., and Nattkemper, D. (2016). Human Action Control. Cham: Springer. doi: 10.1007/978-3-319-09244-7

Hommel, B., Müsseler, J., Aschersleben, G., and Prinz, W. (2001). The theory of event coding (TEC): a framework for perception and action planning. Behav. Brain Sci. 24, 849–878. doi: 10.1017/S0140525X01000103

Honda, H. (1989). Perceptual localization of visual stimuli ﬂashed during saccades. Percept. Psychophys. 45, 162–174. doi: 10.3758/BF03208051

Honda, H. (1995). Visual mislocalization produced by a rapid image displacement on the retina: examination by means of dichoptic presentation of a target and its background scene. Vision. Res. 35, 3021–3028. doi: 10.1016/0042-6989(95)00108-C

Hopp, J. J., and Fuchs, A. F. (2004). The characteristics and neuronal substrate of saccadic eye movement plasticity. Prog. Neurobiol. 72, 27–53. doi: 10.1016/j.pneurobio.2003.12.002

Hutchison, J. J., and Loomis, J. M. (2006). Does energy expenditure aﬀect the perception of egocentric distance? a failure to replicate experiment 1 of proﬃtt, stefanucci, banton, and epstein (2003). Span. J. Psychol. 9, 332–339. doi: 10.1017/S1138741600006235

Jeannerod, M. (1981). Intersegmental coordination during reaching at natural visual objects. Atten. Perform. 11, 153–169. Johansson, R. S., and Westling, G. (1988). Programmed and triggered actions to rapid load changes during precision grip. Exp. Brain Res. 2, 71. doi: 10.1007/BF00247523

Johansson, R. S., Westling, G., Bäckström, A., and Flanagan, J. R. (2001). Eye–hand coordination in object manipulation. J. Neurosci. 21, 6917–6932. doi: 10.1523/JNEUROSCI.21-17-06917.2001

Kaiser, M., and Lappe, M. (2004). Perisaccadic mislocalization orthogonal to saccade direction. Neuron 41, 293–300. doi: 10.1016/S0896-6273(03)00849-3 13 Kawai, S. (2002a). Heaviness perception: I. constant involvement of haptically perceived size in weight discrimination. Exp. Brain Res. 147, 16–22. doi: 10.1007/s00221-002-1209-3

Kawai, S. (2002b). Heaviness perception: II. contributions of object weight, haptic size, and density to the accurate perception of heaviness or lightness. Exp. Brain. Res. 147, 23–28. doi: 10.1007/s00221-002-1210-x

Kawai, S. (2003a). Heaviness perception: III. Weight/aperture in the discernment of heaviness in cubes haptically perceived by thumb-index ﬁnger grasp. Exp. Brain Res. 153, 289–296. doi: 10.1007/s00221-003-1621-3

Kawai, S. (2003b). Heaviness perception: IV. Weight x aperture−1 as a heaviness model in ﬁnger-grasp perception. Exp. Brain Res. 153, 297–301. doi: 10.1007/s00221-003-1622-2

Kelly, J. W., Donaldson, L. S., Sjolund, L. A., and Freiberg, J. B. (2013). More than just perception–action recalibration: walking through a virtual environment causes rescaling of perceived space. Atten. Percept. Psychophys. 75, 1473–1485. doi: 10.3758/s13414-013-0503-4

Kirsch, W. (2015). Impact of action planning on spatial perception: attention matters. Acta. Psychol. (Amst) 156, 22–31. doi: 10.1016/j.actpsy.2015.01.002

Kirsch, W., Herbort, O., Butz, M., v., and Kunde, W. (2012). Inﬂuence of motor planning on distance perception within the peripersonal space. PLoS One 7, e34880. doi: 10.1371/journal.pone.0034880

Kirsch, W., and Kunde, W. (2013). Visual near space is scaled to parameters of current action plans. J. Exp. Psychol. Hum. Percept. Perform. 39, 1313–1325. doi: 10.1037/a0031074

Knoblich, G., and Flach, R. (2001). Predicting the eﬀects of actions: interactions of perception and action. Psychol. Sci. 12, 467–472. doi: 10.1111/1467-9280.00387

Kojima, Y., Iwamoto, Y., and Yoshida, K. (2005). Eﬀect of saccadic amplitude adaptation on subsequent adaptation of saccades in diﬀerent directions. Neurosci. Res. 53, 404–412. doi: 10.1016/j.neures.2005.08.012

Köller, C. P., Poth, C. H., and Herwig, A. (2020). Object discrepancy modulates feature prediction across eye movements. Psychol. Res. 84, 231–244. doi: 10.1007/s00426-018-0988-5

Körding, K. P., and Wolpert, D. M. (2006). Bayesian decision theory in sensorimotor control. Trends Cogn. Sci. 10, 319–326. doi: 10.1016/j.tics.2006.05.003

Kunde, W., and Wuhr, P. (2004). Actions blind to conceptually overlapping stimuli. Psychologic. Res. Psychologische Forschung 4, 68. doi: 10.1007/s00426-003-0156-3

Kusunoki, M., and Goldberg, M. E. (2003). The time course of perisaccadic receptive ﬁeld shifts in the lateral intraparietal area of the monkey. J. Neurophysiol. 89, 1519–1527. doi: 10.1152/jn.00519.2002

Land, M., Mennie, N., and Rusted, J. (1999). The roles of vision and eye movements in the control of activities of daily living. Perception 28, 1311–1328. doi: 10.1068/p2935

Land, M. F. (1992). Predictable eye-head coordination during driving. Nature 359, 318–320. doi: 10.1038/359318a0

Land, M. F. (2006). Eye movements and the control of actions in everyday life. Prog Retin Eye Res 25, 296–324. doi: 10.1016/j.preteyeres.2006.01.002

Land, M. F. (2009). Vision, eye movements, and natural behavior. Vis. Neurosci. 26, 51–62. doi: 10.1017/S0952523808080899

Land, M. F., and Lee, D. N. (1994). Where we look when we steer. Nature 369, 742–744. doi: 10.1038/369742a0 Lappe, M., Awater, H., and Krekelberg, B. (2000). Postsaccadic visual references generate presaccadic compression of space. Nature 403, 892–895. doi: 10.1038/35002588

Lappe, M., Kuhlmann, S., Oerke, B., and Kaiser, M. (2006). The fate of object features during perisaccadic mislocalization. J. Vis. 6, 11. doi: 10.1167/6.11.11

Lavergne, L., Vergilino-Perez, D., Collins, T., and Dore’-Mazars, K. (2010). Adaptation of within-object saccades can be induced by changing stimulus size. Exp. Brain Res. 203, 773–780. doi: 10.1007/s00221-010-2282-7

Lee, Y., Lee, S., Carello, C., and Turvey, M. T. (2012). An archer’s perceived form scales the “hitableness” of archery targets. J. Exp. Psychol. Hum. Percept. Perform. 38, 1125–1131. doi: 10.1037/a0029036

Li, H., and Giudice, N. (2013). “The eﬀects of 2D and 3D maps on learning virtual multi-level indoor environments,” in Proceedings of the 1st ACM SIGSPATIAL International Workshop on Map Interaction (Orlando: ACM, Orlando, p. 7–12.

Lindemann, O., and Bekkering, H. (2009). Object manipulation and motion perception: Evidence of an inﬂuence of action planning on visual processing. J. Exp. Psychol. Hum. Percept. Perform. 35, 1062–1071. doi: 10.1037/a0015023

Liversedge, S. P., and Findlay, J. M. (2000). Saccadic eye movements and cognition. Trends Cogn. Sci. 4, 6–14. doi: 10.1016/S1364-6613(99)01418-7

Loomis, J. M., da Silva, J. A., Fujita, N., and Fukusima, S. S. (1992). Visual space perception and visually directed action. J. Exp. Psychol. Hum. Percept. Perform. 18, 906–921. doi: 10.1037/0096-1523.18.4.906

Loomis, J. M., and Philbeck, J. W. (2008). “Measuring perception with spatial updating and action.,” in. Embodiment, ego-space, and action (Mahwah, NJ: Erlbaum.), eds R. L. Klatzky, M. Behrmann, and B. MacWhinney, p. 1–43.

Lukos, J., Ansuini, C., and Santello, M. (2007). Choice of contact points during multidigit grasping: eﬀect of predictability of object center of mass location. J. Neurosci. 27, 3894–3903. doi: 10.1523/JNEUROSCI.4693-06.2007

Lukos, J. R., Ansuini, C., and Santello, M. (2008). Anticipatory control of grasping: independence of sensorimotor memories for kinematics and kinetics. J. Neurosci. 28, 12765–12774. doi: 10.1523/JNEUROSCI.4335-08.2008

Lünenburger, L., Kutz, D. F., and Hoﬀmann, K.-P. (2000). Inﬂuence of arm movements on saccades in humans. Euro. J. Neurosci. 12, 4107–4116. doi: 10.1046/j.1460-9568.2000.00298.x

Mark, L. S. (1987). Eyeheight-scaled information about aﬀordances: a study of sitting and stair climbing. J. Exp. Psychol. Hum. Percept. Perform. 13, 361–370. doi: 10.1037/0096-1523.13.3.361

Matin, L., and Pearce, D. G. (1965). Visual perception of direction for stimuli ﬂashed during voluntary saccadic eye movements. Science 148, 1485–1488. doi: 10.1126/science.148.3676.1485

Matsumiya, K., and Uchikawa, K. (2001). Apparent size of an object remains uncompressed during presaccadic compression of visual space. Vision Res. 41, 3039–3050. doi: 10.1016/S0042-6989(01)00174-2

Mattar, M. G., and Lengyel, M. (2022). Planning in the brain. Neuron. 110, 914–934. doi: 10.1016/j.neuron.2021.12.018

McConkie, G., PW, K., Reddix, M., Zola, D., and Jacobs, A. (1989). Eye movement control during reading: II. frequency of reﬁxating a word. Percept. Psychophys. 46, 245–253. doi: 10.3758/BF03208086

McLaughlin, S. C. (1967). Parametric adjustment in saccadic eye movements. Percept. Psychophys. 2, 359–362. doi: 10.3758/BF03210071

Miller, J., Anstis, T., and Templeton, W. (1981). Saccadic plasticity: parametric adaptive control by retinal feedback. J. Exp. Psychol. Hum. Percept. Perform. 7, 356–66. doi: 10.1037/0096-1523.7.2.356

Mohler, B. J., Creem-Regehr, S. H., and Thompson, W. B. (2006). “The inﬂuence of feedback on egocentric distance judgments in real and virtual environments,” in ACM SIGGRAPH Symposium on Applied Perception in Graphics and Visualization (Washington, DC: ACM), p. 9–14. doi: 10.1145/1140491.1140493

Morasso, P. (1981). Spatial control of arm movements. Exp. Brain Res. 2, 42. doi: 10.1007/BF00236911

Morgado, N., Gentaz, É., Guinet, É., Osiurak, F., and Palluel-Germain, R. (2013). Within reach but not so reachable: Obstacles matter in visual perception of distances. Psychon. Bull. Rev. 20, 462–467. doi: 10.3758/s13423-012-0358-z

Morrone, M. C., Ross, J., and Burr, D. (2005). Saccadic eye movements cause compression of time as well as space. Nat. Neurosci. 8, 950–954. doi: 10.1038/nn1488

Murray, D. J., Ellis, R. R., Bandomir, C. A., and Ross, H. E. (1999). Charpentier 1891 on the size—weight illusion. Percept. Psychophys. 61, 1681–1685. doi: 10.3758/BF03213127

Musseler, J., and Hommel, B. (1997). Blindness to response-compatible stimuli. J. Exp. Psychol. Hum. Percept. Perform. 23, 861–872. doi: 10.1037/0096-1523.23.3.861

Nakamura, K., and Colby, C. L. (2002). Updating of the visual representation in monkey striate and extrastriate cortex during saccades. Proceed. Nat. Acad. Sci. 99, 4026–4031. doi: 10.1073/pnas.052379899

Neggers, S., Huijbers, W., Vrijlandt, C., Vlaskamp, B., Schutter, D., and

Kenemans, J. (2007). TMS pulses on the frontal eye ﬁelds break coupling between visuospatial attention and eye movements. J. Neurophysiol. 98, 2765–2778. doi: 10.1152/jn.00357.2007

Neggers, S. F., and Bekkering, H. (2000). Ocular gaze is anchored to the target of an ongoing pointing movement. J. Neurophysiol. 83, 639–651. doi: 10.1152/jn.2000.83.2.639

Neggers, S. F. W., and Bekkering, H. (1999). Integration of visual and somatosensory target information in goal-directed eye and arm movements. Exp. Brain. Res. 125, 97–107. doi: 10.1007/s002210050663

Neggers, S. F. W., and Bekkering, H. (2001). Gaze anchoring to a pointing target is present during the entire pointing movement and is driven by a non-visual signal. J. Neurophysiol. 86, 961–970. doi: 10.1152/jn.2001.86.2.961 Neggers, S. F. W., and Bekkering, H. (2002). Coordinated control of eye and hand movements in dynamic reaching. Hum. Mov. Sci. 21, 37–64. doi: 10.1016/S0167-9457(02)00120-3

Noel, J.-P., Grivaz, P., Marmaroli, P., Lissek, H., Blanke, O., and Serino, A. (2015). Full body action remapping of peripersonal space: the case of walking. Neuropsychologia 70, 375–384. doi: 10.1016/j.neuropsychologia.2014.08.030

Osiurak, F., Morgado, N., and Palluel-Germain, R. (2012). Tool use and perceived distance: when unreachable becomes spontaneously reachable. Exp. Brain Res. 218, 331–339. doi: 10.1007/s00221-012-3036-5 14

Paeye, C., Collins, T., Cavanagh, P., and Herwig, A. (2018). Calibration of peripheral perception of shape with and without saccadic eye movements. Atten. Percept. Psychophys. 80, 723–737. doi: 10.3758/s13414-017-1478-3

Patla, A., and Vickers, J. (2003). How far ahead do we look when required to step on speciﬁc locations in the travel path during locomotion? Exp. Brain Res. 148, 133–138. doi: 10.1007/s00221-002-1246-y

Pelisson, D., Prablanc, C., Goodale, M., and Jeannerod, M. (1986). Visual control of reaching movements without vision of the limb. Exp. Brain Res. 62, 303–311.

Pelz, J., Hayhoe, M., and Loeber, R. (2001). The coordination of eye, head, and hand movements in a natural task. Exp. Brain Res. 139, 266–277. doi: 10.1007/s0022101 00745

Pola, J. (2004). Models of the mechanism underlying perceived location of a perisaccadic ﬂash. Vision Res. 44, 2799–2813. doi: 10.1016/j.visres.2004. 06.008

Prablanc, C., Echallier, J. F., Komilis, E., and Jeannerod, M. (1979). Optimal response of eye and hand motor systems in pointing at a visual target. Biol. Cybern. 35, 113–124. doi: 10.1007/BF00337436

Prinz, W. (1990). “A Common Coding Approach to Perception and Action,” in Relationships Between Perception and Action: Current Approaches, eds. O. Neumann and W. Prinz (Berlin, Heidelberg: Springer Berlin Heidelberg), p. 167–201. doi: 10.1007/978-3-642-75348-0_7

Prinz, W. (1997). Perception and action planning. Euro. J. Cogn. Psychol. 9, 129–154. doi: 10.1080/713752551 Proﬃtt, D. (2008). “An action-speciﬁc approach to spatial perception,” in R. L. Klatzky, B. MacWhinney and M. Behrmann (Eds.) (New York: Psychology Press.), 179–202. Proﬃtt, D. R. (2006). Distance perception. Curr. Dir. Psychol. Sci. 15, 131–135. doi: 10.1111/j.0963-7214.2006.00422.x Rahmouni, S., and Madelain, L. (2019). Inter-individual variability and consistency of saccade adaptation in oblique saccades: amplitude increase and decrease in the horizontal or vertical saccade component. Vision Res. 160, 82–98. doi: 10.1016/j.visres.2019.05.001

Richardson, A. R., and Waller, D. (2005). The eﬀect of feedback training on distance estimation in virtual environments. Appl. Cogn. Psychol. 19, 1089–1108. doi: 10.1002/acp.1140

Rieser, J. J., Ashmead, D. H., Talor, C. R., and Youngquist, G. A. (1990). Visual perception and the guidance of locomotion without vision to previously seen targets. Perception 19, 675–689. doi: 10.1068/p190675

Rieser, J. J., Pick, H. L., Ashmead, D. H., and Garing, A. E. (1995). Calibration of human locomotion and models of perceptual-motor organization. J. Exp. Psychol. Hum. Percept. Perform. 21, 480–497. doi: 10.1037/0096-1523.21.3.480

Ross, J., Morrone, M. C., and Burr, D. C. (1997). Compression of visual space before saccades. Nature 386, 598–601. doi: 10.1038/386598a0

Rossetti, Y., Stelmach, G., Desmurget, M., Prablanc, C., and Jeannerod, M. (1994). The eﬀect of viewing the static hand prior to movement onset on pointing kinematics and variability. Exp. Brain. Res. 101, 323–330. doi: 10.1007/BF00228753

Salimi, I., Hollender, I., Frazier, W., and Gordon, A. M. (2000). Speciﬁcity of internal representations underlying grasping. J. Neurophysiol. 84, 2390–2397. doi: 10.1152/jn.2000.84.5.2390

Sanz Diez, P., Bosco, A., Fattori, P., and Wahl, S. (2022). Horizontal target size perturbations during grasping movements are described by subsequent size perception and saccade amplitude. PLoS One 17, e0264560. doi: 10.1371/journal.pone.0264560

Sarlegna, F. R., and Sainburg, R. L. (2009). The Roles of Vision and Proprioception in the Planning of Reaching Movements, p. 317–335. doi: 10.1007/978-0-387-77064-2_16

Schlag, J., and Schlag-Rey, M. (1995). Illusory localization of stimuli ﬂashed in the dark before saccades. Vision. Res. 35, 2347–2357. doi: 10.1016/0042-6989(95)00021-Q

Schubö, A., Aschersleben, G., and Prinz, W. (2001). Interactions between perception and action in a reaction task with overlapping S-R assignments. Psychol. Res. 65, 145–157. doi: 10.1007/s004260100061

Sedgwick, H. (1986). “Space perception.,” in Handbook of perception and human performance: Vol I. Sensory processes and perception, eds Thomas (New York, NY: Wiley.), p. 21–57.

Siegel, Z. D., Kelly, J. W., and Cherep, L. A. (2017). Rescaling of perceived space transfers across virtual environments. J. Exp. Psychol. Hum. Percept. Perform. 43, 1805–1814. doi: 10.1037/xhp0000401

Stefanucci, J. K., and Geuss, M. N. (2009). Big people, little world: the body inﬂuences size perception. Perception 38, 1782–1795. doi: 10.1068/p6437

Sutton, R., and Barto, A. (1998). Reinforcement Learning: An Introduction. London: The MIT Press. doi: 10.1109/TNN.1998.712192 Symes, E., Tucker, M., Ellis, R., Vainio, L., and Ottoboni, G. (2008). Grasp preparation improves change detection for congruent objects. J. Exp. Psychol. Hum. Percept. Perform. 34, 854–871. doi: 10.1037/0096-1523. 34.4.854

Taylor, J. E. T., Witt, J. K., and Sugovic, M. (2011). When walls are no longer barriers: perception of wall height in parkour. Perception 40, 757–760. doi: 10.1068/p6855

Thut, G., Miniussi, C., and Gross, J. (2012). The functional importance of rhythmic activity in the brain. Current Biology 22, R658–R663. doi: 10.1016/j.cub.2012.06.061

Tomassini, A., Ambrogioni, L., Medendorp, W. P., and Maris, E. (2017). Theta oscillations locked to intended actions rhythmically modulate perception. Elife 6, e25618. doi: 10.7554/eLife.25618.014

Tomassini, A., Spinelli, D., Jacono, M., Sandini, G., and Morrone, M. C. (2015). Rhythmic oscillations of visual contrast sensitivity synchronized with action. J. Neurosci. 35, 7019. doi: 10.1523/JNEUROSCI.4568-14.2015

Valsecchi, M., Cassanello, C., Herwig, A., Rolfs, M., and Gegenfurtner, K. R. (2020). A comparison of the temporal and spatial properties of trans-saccadic perceptual recalibration and saccadic adaptation. J. Vis. 20, 2. doi: 10.1167/jov.20.4.2

Valsecchi, M., and Gegenfurtner, K. R. (2016). Dynamic re-calibration of perceived size in fovea and periphery through predictable size changes. Curr. Biol. 26, 59–63. doi: 10.1016/j.cub.2015.10.067 van Beers, R. J., Baraduc, P., and Wolpert, D. M. (2002). Role of uncertainty in sensorimotor control. Philos. Trans. R Soc. Lond. B Biol. Sci. 357, 1137–1145. doi: 10.1098/rstb.2002.1101

Velay, J., and Beaubaton, D. (1986). Inﬂuence of visual context on pointing movement accuracy. Cahiers de Psychologie Cognitive 6, 447–456.

Vishwanath, D., and Kowler, E. (2003). Localization of shapes: eye movements and perception compared. Vision. Res. 43, 1637–1653. doi: 10.1016/S0042-6989(03)00168-8

Waller, D., and Richardson, A. R. (2008). Correcting distance estimates by interacting with immersive virtual environments: Eﬀects of task and available sensory information. J. Exp. Psychol. Appl. 14, 61–72. doi: 10.1037/1076-898X. 14.1.61

Warren, W. H. (1984). Perceiving aﬀordances: visual guidance of stair climbing. J. Exp. Psychol. Hum. Percept. Perform. 10, 683–703. doi: 10.1037/0096-1523.10.5.683

Warren, W. H., and Whang, S. (1987). Visual guidance of walking through apertures: body-scaled information for aﬀordances. J. Exp. Psychol. Hum. Percept. Perform. 13, 371–383. doi: 10.1037/0096-1523.13.3.371

Watanabe, S., Ogino, S., Nakamura, T., and Koizuka, I. (2003). Saccadic adaptation in the horizontal and vertical directions in normal subjects. Auris Nasus Larynx 30, 41–45. doi: 10.1016/S0385-8146(02)00119-0

Westling, G., and Johansson, R. S. (1984). Factors inﬂuencing the force control during precision grip. Exp. Brain Res. 53, 6. doi: 10.1007/BF00238156

Witt, J. (2018). “Perception and Action,” in Stevens’ Handbook of Experimental Psychology and Cognitive Neuroscience (New York, NY: Wiley), p. 489–523. doi: 10.1002/9781119170174.epcn211

Witt, J. K. (2011). Tool use inﬂuences perceived shape and perceived parallelism, which serve as indirect measures of perceived distance. J. Exp. Psychol. Hum. Percept. Perform. 37, 1148–1156. doi: 10.1037/a0021933

Witt, J. K., and Proﬃtt, D. R. (2005). See the ball, hit the ball: apparent ball size is correlated with batting average. Psychol. Sci. 16, 937–938. doi: 10.1111/j.1467-9280.2005.01640.x

Witt, J. K., and Proﬃtt, D. R. (2008). Action-speciﬁc inﬂuences on distance perception: a role for motor simulation. J. Exp. Psychol. Hum. Percept. Perform. 34, 1479–1492. doi: 10.1037/a0010781

Witt, J. K., Proﬃtt, D. R., and Epstein, W. (2004). Perceiving distance: a role of eﬀort and intent. Perception 33, 577–590. doi: 10.1068/p5090

Witt, J. K., Proﬃtt, D. R., and Epstein, W. (2005). Tool use aﬀects perceived distance, but only when you intend to use it. J. Exp. Psychol. Hum. Percept. Perform. 31, 880–888. doi: 10.1037/0096-1523.31.5.880

Witt, J. K., and Sugovic, M. (2010). Performance and ease inﬂuence perceived speed. Perception 39, 1341–1353. doi: 10.1068/p6699

Wittenberg, M., Bremmer, F., and Wachtler, T. (2008). Perceptual evidence for saccadic updating of color stimuli. J. Vis. 8, 9. doi: 10.1167/8.14.9

Wohlschläger, A. (2000). Visual motion priming by invisible actions. Vision. Res. 40, 925–930. doi: 10.1016/S0042-6989(99)00239-4

Wolpert, D. M., Ghahramani, Z., and Jordan, Michael, I. (1995). Are arm trajectories planned in kinematic or dynamic coordinates? an adaptation study. Exp. Brain. Res. 5, 103. doi: 10.1007/BF00241505

Woodworth, R. S. (1899). Accuracy of voluntary movement. Psychologic. Rev. Monograp. Suppl. 3, i−114. doi: 10.1037/h0092992

Wühr, P., and Müsseler, J. (2001). Time course of the blindness to response- compatible stimuli. J. Exp. Psychol. Hum. Percept. Perform. 27, 1260–1270. doi: 10.1037/0096-1523.27.5.1260

Wykowska, A., Hommel, B., and Schubo, A. (2011). Action-induced eﬀects on perception depend neither on element-level nor on set-level similarity between stimulus and response sets. Atten. Percept. Psychophys. 73, 1034–1041. doi: 10.3758/s13414-011-0122-x 15

Wykowska, A., and Schubö, A. (2012). Action intentions modulate allocation of visual attention: electrophysiological evidence. Front. Psychol. 3, 12. doi: 10.3389/fpsyg.2012.00379

Wykowska, A., Schubö, A., and Hommel, B. (2009). How you move is what you see: action planning biases selection in visual search. J. Exp. Psychol. Hum. Percept. Perform. 35, 1755–1769. doi: 10.1037/a0016798

Zelinsky, G. J., Rao, R. P. N., Hayhoe, M. M., and Ballard, D. H. (1997). Eye movements reveal the spatiotemporal dynamics of visual search. Psychol. Sci. 8, 448–453. doi: 10.1111/j.1467-9280.1997.tb00459.x

Zimmermann, E., and Lappe, M. (2010). Motor signals in visual localization. J. Vis. 10, 1–11. doi: 10.1167/10.6.2 Zimmermann, E., Morrone, M. C., and Burr, D. (2015). Visual mislocalization during saccade sequences. Exp. Brain. Res. 233, 577–585. doi: 10.1007/s00221-014-4138-z

Zimmermann, E., Morrone, M. C., and Burr, D. C. (2014). The visual component to saccadic compression. J. Vis. 14, 13. doi: 10.1167/14.12.13

Zwickel, J., Grosjean, M., and Prinz, W. (2007). Seeing while moving: measuring the online inﬂuence of action on perception. Q. J. Experiment. Psychol. 60, 1063–1071. doi: 10.1080/17470210701288722

Zwickel, J., Grosjean, M., and Prinz, W. (2010). On interference eﬀects in concurrent perception and action. Psychologic. Res. Psychologische Forschung 74, 152–171. doi: 10.1007/s00426-009-0226-2 16
