# La place de la modélisation en sciences cognitives

**Titre original :** *The Place of Modeling in Cognitive Science*  
**Auteur :** James L. McClelland  
**Institution :** Department of Psychology and Center for Mind, Brain, and Computation, Stanford University  
**Publication officielle :** *Topics in Cognitive Science* (Janvier 2009), Volume 1, Numéro 1, pages 11–38  
**DOI :** [10.1111/j.1756-8765.2008.01003.x](https://doi.org/10.1111/j.1756-8765.2008.01003.x)  
**Traduction académique :** Module officiel de traduction académique — PSY9613 (*Perception, cognition et IA*, UQAM)

---

### Résumé (*Abstract*)

J'examine ici le rôle de la modélisation cognitive au sein des sciences cognitives. La modélisation, et les ordinateurs qui la rendent matériellement possible, occupent une position centrale dans notre discipline, mais leur fonction épistémologique fait souvent l'objet de profonds malentendus. 

Les modèles n'ont pas pour vocation de capturer dans toute son exhaustivité la réalité empirique des processus qu'ils tentent d'élucider. Ils constituent bien plutôt des **instruments d'exploration conceptuelle** portant sur la nature intime des mécanismes cognitifs. Dans ces explorations, **la simplification est essentielle** : c'est précisément par la simplification que les implications des idées fondamentales deviennent transparentes et intelligibles. Cela ne signifie nullement que la simplification soit sans écueil ; elle comporte des angles morts réels, qui sont ici analysés en détail.

J'examine ensuite plusieurs cadres paradigmatiques contemporains de modélisation cognitive (symbolique, connexionniste, bayésien, systèmes dynamiques, architectures hybrides), en insistant sur le fait que chaque cadre possède son domaine naturel d'application et sa fécondité propre. L'accroissement colossal de la puissance de calcul des ordinateurs (d'un facteur d'environ 4 millions depuis 1958) a permis l'éclosion de nouveaux paradigmes de modélisation, mais ceux-ci dépendent tout autant de l'invention de nouvelles manières de penser. De nouveaux paradigmes surgiront-ils lors du prochain saut d'un facteur 1 000 de la puissance de calcul ?

**Mots-clés :** cadres de modélisation, simulation informatique, modèles connexionnistes, approches bayésiennes, systèmes dynamiques, modèles symboliques de la cognition, modèles hybrides, architectures cognitives.

---
<!-- ======================================================================= -->
<!-- PAGE 1                                                                  -->
<!-- ======================================================================= -->

# La place de la modélisation en sciences cognitives

**Titre original :** *The Place of Modeling in Cognitive Science*  
**Auteur :** James L. McClelland  
**Affiliation :** Département de psychologie et Centre pour l'esprit, le cerveau et le calcul (*Center for Mind, Brain, and Computation*), Université Stanford  
**Publication :** *Topics in Cognitive Science*, Vol. 1, No. 1 (2009), pages 11–38  
**DOI :** [10.1111/j.1756-8765.2008.01003.x](https://doi.org/10.1111/j.1756-8765.2008.01003.x)  
**Traduction académique :** Module officiel de traduction académique — PSY9613 (*Perception, cognition et IA*, UQAM)

---

### Résumé (*Abstract*)

J'examine ici le rôle de la modélisation cognitive au sein des sciences cognitives. La modélisation, et les ordinateurs qui la rendent matériellement possible, occupent une position centrale dans notre discipline, mais leur fonction épistémologique fait souvent l'objet de profonds malentendus. 

Les modèles n'ont pas pour vocation de capturer dans toute son exhaustivité la réalité empirique des processus qu'ils tentent d'élucider. Ils constituent bien plutôt des **instruments d'exploration conceptuelle** portant sur la nature intime des mécanismes cognitifs. Dans ces explorations, **la simplification est essentielle** : c'est précisément par la simplification que les implications des idées fondamentales deviennent transparentes et intelligibles. Cela ne signifie nullement que la simplification soit sans écueil ; elle comporte des angles morts réels, qui sont ici analysés en détail.

J'examine ensuite plusieurs cadres paradigmatiques contemporains de modélisation cognitive (symbolique, connexionniste, bayésien, systèmes dynamiques, architectures hybrides), en insistant sur le fait que chaque cadre possède son domaine naturel d'application et sa fécondité propre. L'accroissement colossal de la puissance de calcul des ordinateurs (d'un facteur d'environ 4 millions depuis 1958) a permis l'éclosion de nouveaux paradigmes de modélisation, mais ceux-ci dépendent tout autant de l'invention de nouvelles manières de penser. De nouveaux paradigmes surgiront-ils lors du prochain saut d'un facteur 1 000 de la puissance de calcul ?

**Mots-clés :** cadres de modélisation, simulation informatique, modèles connexionnistes, approches bayésiennes, systèmes dynamiques, modèles symboliques de la cognition, modèles hybrides, architectures cognitives.

---

## 1. Introduction

Avec l'inauguration d'une nouvelle revue pour les sciences cognitives (*Topics in Cognitive Science*), trente ans après le premier colloque de la *Cognitive Science Society*, il apparaît primordial de s'interroger sur le rôle de la modélisation computationnelle dans notre discipline. Puisque l'invitation suggérait une réflexion sur l'histoire passée et les perspectives d'avenir de cette démarche, je commencerai par analyser les forces qui ont façonné notre champ de recherche.

La force motrice première a sans doute été l'invention et le développement technologique fulgurant de l'ordinateur numérique. Les ordinateurs actuels sont plusieurs millions de fois plus rapides qu'ils ne l'étaient il y a cinquante ans, et ces bonds de puissance computationnelle ont constitué des conditions nécessaires à l'émergence de nouveaux paradigmes scientifiques. Pourtant, les cadres conceptuels que les chercheurs insufflent dans la modélisation cognitive jouent un rôle tout aussi déterminant. Les ordinateurs figurent certes parmi les forces qui modèlent ces cadres conceptuels, mais d'autres forces théoriques sont également à l'œuvre.


<!-- ======================================================================= -->
<!-- PAGE 2                                                                  -->
<!-- ======================================================================= -->

La deuxième section aborde la question du rôle de la modélisation dans l'effort pour comprendre les facultés cognitives humaines, en mettant l'accent sur les relations entre les modèles et les théories sous-jacentes, ainsi que sur le processus pragmatique par lequel le travail de modélisation s'accomplit. Je soutiens que nous devons appréhender les modèles comme des **outils destinés à explorer les implications d'idées théoriques**. Ils peuvent nous éclairer sur les conséquences logiques d'une manière particulière de concevoir les processus mentaux à l'œuvre dans des tâches cognitives ciblées, avec des résultats parfois tout à fait surprenants.

Dans ce contexte, j'examine le principe fondamental consistant à **« garder le modèle simple »** (*keeping it simple*) — la simplification est indispensable mais comporte des pièges, et différentes simplifications sont requises pour explorer des problématiques distinctes. De manière corollaire, les réussites et les échecs d'ajustement d'un modèle aux données empiriques (*fitting*) doivent être interprétés avec la plus grande prudence :
- Un excellent ajustement statistique ne signifie jamais qu'un modèle puisse être proclamé comme l'explication unique et vraie des données observées ;
- À l'inverse, un mauvais ajustement ne prouve pas nécessairement que les principes fondamentaux incarnés dans le modèle soient la cause de la divergence.

Les modèles sont des outils de recherche qui possèdent leurs forces et leurs faiblesses, à l'instar de tous les instruments scientifiques.

Dans la troisième section, je passe en revue les grands cadres contemporains de modélisation cognitive, en attribuant à chacun une légitimité théorique et un domaine naturel de pertinence, tout en discutant les défis auxquels chacun fait face.

La section finale se tourne vers l'avenir : que nous apportera le prochain bond d'un facteur 1 000 de la puissance de calcul ? Selon la loi de Moore, un tel accroissement surviendra d'ici une vingtaine d'années, autorisant un réalisme accru, un contenu enrichi et une meilleure inscription située des futurs modèles cognitifs. Je soutiens toutefois que l'impact sur notre discipline restera marginal à moins que de nouveaux cadres conceptuels n'émergent conjointement.

---

## 2. Le rôle de l'ordinateur aux origines des sciences cognitives

Où en seraient les sciences cognitives aujourd'hui sans l'ordinateur ? Peut-on seulement l'imaginer ?

Je le peux personnellement, car ma formation initiale en psychologie était, pourrait-on dire, pré-computationnelle. Lorsque j'étais étudiant de premier cycle à l'Université Columbia à la fin des années 1960, j'ai étudié diverses déclinaisons de la psychologie béhavioriste, les mécanismes sensoriels via la physiologie et la psychophysique, ainsi que la théorie de la détection du signal. Bien que l'ordinateur existât déjà depuis plus de vingt ans, son influence n'avait pas encore pénétré tous les départements universitaires.

Ailleurs, cependant, l'invention de l'ordinateur provoquait une onde de choc, comme je l'ai découvert en entrant aux études supérieures. J'y ai rencontré la psychologie cognitive naissante et la psycholinguistique, toutes deux profondément imprégnées de concepts computationnels.

Selon Ulric Neisser (1967), auteur de l'ouvrage séminal *Cognitive Psychology*, **l'invention de l'ordinateur a permis aux psychologues de surmonter leur réticence positiviste à théoriser des processus mentaux inobservables**, contribuant de manière décisive à l'effondrement du béhaviorisme. Même si un observateur regardant un ordinateur de l'extérieur ne pouvait pas observer directement les opérations internes de la machine, des processus hautement complexes s'y déroulaient bel et bien, permettant à la machine et à ses programmes de produire des sorties organisées en réponse à des entrées environnementales. Il n'y avait qu'un pas pour concevoir que des processus internes inobservables analogues prenaient place au sein de l'esprit humain.


<!-- ======================================================================= -->
<!-- PAGE 3                                                                  -->
<!-- ======================================================================= -->

Comme pour administrer la preuve expérimentale de cette rupture épistémologique, l'ordinateur autorisait un genre entièrement inédit d'investigation scientifique : **la simulation computationnelle de processus mentaux de nature quasi humaine**, tels qu'ils étaient envisagés par des chercheurs issus d'horizons variés. Considérons deux exemples séminaux de la fin des années 1950.

### 2.1. Le démonstrateur de théorèmes logiques de Newell et Simon

Dans son autobiographie, Herbert Simon (1991) raconte être entré dans sa classe en janvier 1956 en annonçant : *« Pendant les vacances de Noël, Allen Newell et moi avons inventé une machine qui pense. »* Il faisait référence à la création du **Logic Theorist**, un programme informatique capable de démontrer des théorèmes de logique formelle issus des *Principia Mathematica* de Whitehead et Russell (Newell & Simon, 1956).

Ce programme a marqué l'acte de naissance du paradigme symbolique :
- Il utilisait une recherche heuristique sélective pour naviguer dans l'espace arborescent des déductions logiques ;
- Il démontra que des manipulations de symboles discrets pouvaient accomplir des tâches tenues jusqu'alors pour le privilège exclusif de l'intellect supérieur humain ;
- Il a donné l'impulsion à toute la psychologie computationnelle classique, affirmant que la pensée humaine est fondamentalement une manipulation physique de structures de symboles selon des règles formelles.

### 2.2. Le Perceptron de Frank Rosenblatt

À la même époque, en 1958, Frank Rosenblatt présentait une vision radicalement différente avec le **Perceptron** (Rosenblatt, 1958). Inspiré des travaux neurophysiologiques de McCulloch et Pitts (1943) et des théories d'assemblées cellulaires de Donald Hebb (1949), Rosenblatt ne concevait pas l'esprit comme un manipulateur de symboles logiques, mais comme **un réseau de neurones interconnectés apprenant par modification continue de poids synaptiques**.

Le Perceptron modélisait la perception visuelle et la classification de motifs :
- Des unités d'entrée sensorielles projetaient vers des unités d'association, qui convergeaient vers des unités de décision ;
- L'apprentissage s'effectuait par ajustement progressif des connexions synaptiques en fonction des erreurs de prédiction ;
- Contrairement au programme de Newell et Simon fondé sur des règles explicites programmées à l'avance, le réseau de Rosenblatt **apprenait à partir d'exemples** par une règle d'apprentissage statistique distribuée.

Ces deux modèles ont inauguré les deux grandes traditions concurrentes des sciences cognitives : le **paradigme symbolique classique** (*GOFAI*) et le **paradigme connexionniste des réseaux neuronaux** (*PDP*).


<!-- ======================================================================= -->
<!-- PAGE 4                                                                  -->
<!-- ======================================================================= -->

### 2.3. L'impact de l'ordinateur sur les sciences cognitives

L'ordinateur a transformé les sciences cognitives de trois manières fondamentales :
1. **La métaphore de l'esprit :** L'esprit humain est devenu concevable comme un système matériel de traitement de l'information (physique des symboles ou dynamique neuronale).
2. **L'outil de calcul empirique :** L'ordinateur permet de simuler des théories dont la dynamique non linéaire ou combinatoire excède les capacités déductives du cerveau des chercheurs.
3. **Le générateur de disciplines connexes :** Il a fécondé l'intelligence artificielle, la linguistique computationnelle, les neurosciences computationnelles et la robotique cognitive.

---

## 3. La nature et le rôle des modèles en sciences cognitives

Mon objectif dans cette section est d'examiner comment nous devons envisager ce que sont les modèles et quels rôles ils jouent en sciences cognitives (y compris en neurosciences cognitives et en psychologie cognitive). Je puiserai des exemples dans mes propres travaux collaboratifs, non par complaisance, mais parce que ce sont les modèles dont je connais le plus intimement les ressorts et les impasses vécues. Les leçons méthodologiques qui s'en dégagent s'appliquent toutefois à l'ensemble des modélisations en sciences de l'esprit.

La thèse centrale de cette section est la suivante :

> **La finalité essentielle de la modélisation cognitive est de permettre l'investigation des implications des idées théoriques, bien au-delà des limites du raisonnement intuitif humain.**

Les modèles permettent d'explorer les conséquences d'hypothèses qui ne peuvent être pleinement sondées par la seule pensée réflexive. À ce titre, **ils sont des véhicules de découverte scientifique**, exactement au même titre que les expériences conduites sur des participants humains ou animaux en laboratoire.

Mais les découvertes issues de la modélisation prennent une forme singulière : **un système doté d'un ensemble spécifié de propriétés matérielles engendre, comme conséquences logiques et dynamiques, un autre ensemble de propriétés émergentes**. À partir de ces observations computationnelles, nous tentons ensuite de tirer des implications quant à la nature de la cognition humaine réelle.

Hélas, ces inférences sont structurellement sous-contraintes (*under-constrained*). Il subsiste presque toujours une marge d'incertitude et de désaccord quant à la portée d'un résultat de simulation. Cela ne signifie pas que les modèles soient inutiles, mais qu'une prudence extrême est de mise dans l'interprétation de leurs réussites comme de leurs échecs.


<!-- ======================================================================= -->
<!-- PAGE 5                                                                  -->
<!-- ======================================================================= -->

### 3.1. Utiliser les modèles pour explorer les implications d'idées théoriques

J'ai ressenti pour la première fois la nécessité de développer un modèle informatique au milieu des années 1970, lorsque je me suis posé la question suivante : *Et si le traitement de l'information impliquait bien une série d'étapes successives — comme Saul Sternberg (1969) nous incitait à le supposer avec sa méthode des facteurs additifs —, mais que la propagation de l'information d'une étape à l'autre était continue et graduée dans le temps et en valeur, plutôt que d'être discrète et tout-ou-rien ?*

J'ai rédigé un article théorique sur cette question que j'ai soumis à la *Psychological Review* en 1975. Les évaluateurs ont trouvé les idées intrigantes, mais ils ne parvenaient pas à comprendre comment un tel système continu pouvait réellement fonctionner, et le rédacteur en chef m'a vivement conseillé de construire un modèle de simulation informatique.

Vers la même époque, j'ai découvert les modèles de réseaux neuronaux de James Anderson (1977). Ces architectures m'ont permis de formaliser ma question de manière limpide et explicite dans ce qui est devenu le **modèle en cascade** (*cascade model*, McClelland, 1979).

J'ai envisagé une série de niveaux de traitement, chacun composé d'un ensemble de nœuds élémentaires. L'activation d'une unité donnée $i$ au niveau $l$ était régie par une équation différentielle linéaire dépendant de l'écart entre sa valeur d'entrée nette $v_{il}(t)$ (somme pondérée des activations des unités $j$ du niveau précédent $l-1$) et son niveau d'activation actuel $a_{il}(t)$ :

$$\frac{da_{il}}{dt} = k_l \left( v_{il}(t) - a_{il}(t) \right)$$

où :

$$v_{il}(t) = \sum_j w_{ij} a_{j, l-1}(t)$$

Pour simplifier, j'ai postulé que le paramètre de vitesse de traitement $k_l$ pouvait varier selon le niveau $l$, mais restait constant pour toutes les unités d'un même niveau. L'activation d'une unité motrice terminale déclenchait la réponse dès qu'elle franchissait un seuil fixé.

L'exploration computationnelle de ce modèle a mis au jour des résultats qui ont stupéfié la psychologie cognitive de l'époque :
1. **Additivité compatible avec la continuité :** Des manipulations expérimentales affectant la dynamique de deux niveaux distincts (les constantes de vitesse $k_l$) produisaient des effets **rigoureusement additifs** sur les temps de réaction, exactement comme dans les modèles à étapes discrètes. Cela démontrait pour la première fois que la présence d'additivité statistique n'implique nullement l'existence d'étapes discrètes, contrairement au dogme méthodologique alors en vigueur !
2. **Faillite des facteurs additifs :** En revanche, des manipulations modifiant les activations asymptotiques brisaient systématiquement l'additivité lorsqu'elles étaient combinées entre elles ou avec des facteurs dynamiques. La logique de Sternberg n'était donc plus une garantie absolue.

Le modèle avait ainsi enseigné aux psychologues une leçon théorique fondamentale sur la propagation continue du signal que la seule intuition formelle n'avait jamais pu déduire.


<!-- ======================================================================= -->
<!-- PAGE 6                                                                  -->
<!-- ======================================================================= -->

<span id="anchor_seance_02_q34_fr" class="doc-anchor-target"></span><span id="anchor_seance_02_q34" class="doc-anchor-target"></span>
### 3.2. L'enjeu de la simplification : « Garder le modèle simple » (*Keeping it simple*)

J'ai pu obtenir les résultats novateurs décrits ci-dessus précisément grâce aux **simplifications délibérées** que j'avais introduites dans la conception du modèle en cascade :
- Stipuler que tout le flux de traitement était strictement ascendant et direct (*feedforward*) ;
- Stipuler que les valeurs d'entrée étaient de simples sommes pondérées strictement linéaires des sorties du niveau antérieur.

Ces simplifications ont permis d'isoler analytiquement les facteurs temporels des facteurs asymptotiques. Cependant, certaines des simplifications adoptées ont par la suite engendré des limites prédictives lorsqu'on a voulu étendre le modèle à la variance des distributions de temps de réaction (Ashby, 1982 ; Roberts & Sternberg, 1993).

Dès lors, une question épistémologique cruciale se pose : **La simplification en science peut-elle être justifiée ? Ne devrions-nous pas toujours viser la fidélité biologique et empirique maximale, en intégrant tous les détails connus ?**

Dans une parabole célèbre qui éclaire magistralement cette question, l'écrivain Jorge Luis Borges (1998, *De la rigueur de la science*) dépeint un empire lointain où les cartographes étaient possédés par une obsession maladive de vérisimilitude et d'exactitude. Chaque guilde de cartographes s'efforçait de surpasser les autres en dessinant des cartes toujours plus détaillées et réalistes. Les cartes ordinaires étaient méprisées pour leur échelle trop réduite et le tracé schématique de leurs routes. Cette dérive culmina dans la confection d'une **Carte de l'Empire grandeur nature**, qui avait exactement la taille de l'Empire lui-même et coïncidait point par point avec son territoire ! Cette carte était, bien entendu, totalement inutile : son maniement n'était pas plus aisé que l'exploration directe du pays physique réel.

Lorsqu'il s'agit de cartographie, **la simplification est l'essence même de l'utilité : le but d'une carte est d'offrir un guide intelligible, et non une réplique aveugle de la réalité**.

Il en va exactement de même pour la modélisation cognitive computationnelle. **Nous nous efforçons de comprendre, et pour comprendre, nous devons impérativement simplifier.** Plus nous incorporons de détails hétérogènes dans un modèle, plus ce modèle devient opaque et réfractaire à la compréhension. Les bons modèles cognitifs doivent résolument viser la simplicité, et les utilisateurs de ces modèles doivent comprendre que la simplification est délibérément adoptée au service de l'intelligibilité théorique.

Même si la puissance de nos superordinateurs continue de croître exponentiellement et que la simulation exhaustive d'un cerveau humain à l'échelle des interactions moléculaires et subatomiques devient techniquement réalisable, **la simplification demeurera la condition absolue pour permettre la compréhension scientifique**.

Toutefois, la simplification a un prix : elle circonscrit la portée de ce que le modèle permet de conclure. Une simplification peut masquer un phénomène crucial ou fausser une prédiction quantitative. Mais la réponse ne consiste pas à empiler tous les détails biologiques possibles : elle consiste à identifier **les simplifications optimales qui retiennent les propriétés structurelles pertinentes pour la fonction que l'on veut expliquer**, tout en laissant de côté les détails superflus.


<!-- ======================================================================= -->
<!-- PAGE 7                                                                  -->
<!-- ======================================================================= -->

### 3.3. Les modèles incarnent-ils des « postulats » ?

J'ai délibérément évité le terme « postulat » ou « hypothèse fondamentale » (*assumption*), qui est fréquemment employé pour désigner les caractéristiques spécifiées d'un modèle, car ce terme induit facilement en erreur.

Considérons par exemple ce passage tiré de la critique acerbe de Steven Pinker et Alan Prince (1988, pp. 95–96) à l'encontre de notre modèle connexionniste de l'acquisition du temps passé des verbes anglais (Rumelhart & McClelland, 1986) :

> *« Voici les postulats linguistiques fondamentaux du modèle de Rumelhart et McClelland : Que les Wickelphones/Wickelfeatures fournissent une base adéquate pour la généralisation phonologique, éliminant le besoin de traiter des chaînes de symboles. Que le passé est formé par la modification directe de la phonétique de la racine [...]. Que la formation des passés irréguliers est déterminée par des considérations purement phonétiques. »*

Rumelhart et moi n'avons jamais envisagé ces caractéristiques comme des « postulats linguistiques fondamentaux » ! Notre objectif était bien plutôt **d'explorer les conséquences d'un ensemble de propriétés computationnelles spécifiques** dans notre tentative d'aborder une question beaucoup plus fondamentale : **l'esprit a-t-il réellement besoin de règles linguistiques symboliques explicites pour produire des comportements réguliers et irréguliers ?**

En réalité, nous avions explicitement écrit dans l'article original que nous ne formulions aucune prétention théorique pérenne en faveur des Wickelphones, si ce n'est qu'ils suffisaient à discriminer et faire apprendre les 500 verbes anglais les plus fréquents au sein d'une **représentation distribuée**.

Permettez-moi de réécrire le passage de Pinker et Prince comme il aurait dû l'être :

> *« Le modèle de Rumelhart et McClelland explore la possibilité que des représentations distribuées sous-lexicales puissent fournir une base adéquate pour la généralisation de la morphologie du passé. Le modèle examine une situation simplifiée où le passé est formé par transformation directe des propriétés phonétiques, laissant délibérément de côté, par souci de simplicité méthodologique, l'influence des facteurs sémantiques. »*

Les critiques ont certes le droit de souligner les insuffisances empiriques d'une première implémentation. Mais lorsqu'ils prennent des choix délibérés de simplification pour des « dogmes fondateurs », ils entravent l'exploration scientifique féconde d'alternatives prometteuses au modèle symbolique conventionnel.


<!-- ======================================================================= -->
<!-- PAGE 8                                                                  -->
<!-- ======================================================================= -->

### 3.4. Comment doit-on évaluer un modèle cognitif ?

Dans des disciplines comme l'informatique appliquée, l'apprentissage automatique (*machine learning*) ou la robotique, l'ingénieur poursuit le but de fabriquer une machine douée d'aptitudes cognitives performantes, souvent sans se soucier de savoir si ses mécanismes ressemblent à ceux du cerveau humain. Ces efforts constituent une source inestimable d'idées algorithmiques, mais ils ne représentent pas l'essence de la modélisation en sciences cognitives.

Le modélisateur en sciences cognitives s'efforce de **capturer l'essence des capacités mentales humaines réelles**. Trois grands critères d'évaluation émergent :

1. **Le critère de suffisance (*sufficiency criterion*) :** Défendu vigoureusement par Allen Newell (1973), il reflète une exigence opérationnelle forte : le modèle est-il capable d'accomplir effectivement la tâche cognitive visée ? Réussir à reconnaître des objets dans une scène naturelle ou comprendre un texte courant est une tâche d'une complexité titanesque que bien des modèles simplistes sont incapables d'exécuter.
2. **Le critère d'optimalité (*rationality / optimality*) :** Porté par les approches bayésiennes et l'analyse rationnelle de John R. Anderson (1990), ce critère se demande quelle est la politique mathématiquement optimale face aux incertitudes de l'environnement.
3. **Le critère d'adéquation empirique (*empirical adequacy*) :** Le modèle rend-il compte fidèlement des temps de réaction, des patrons d'erreurs, des étapes développementales et des données neurophysiologiques observés chez l'humain ?

Je ne vois personnellement aucune frontière étanche entre ces trois critères. La performance humaine est intrinsèquement probabiliste, limitée et sujette à l'erreur. L'évaluation d'un modèle consiste donc à vérifier : **Le modèle accomplit-il la tâche aussi bien que l'humain, atteint-il le même niveau d'optimalité relative, et dévie-t-il de l'optimalité exactement de la même manière que l'humain ?**


<!-- ======================================================================= -->
<!-- PAGE 9                                                                  -->
<!-- ======================================================================= -->

### 3.5. Attribuer le blâme et apprendre des échecs d'un modèle

Lorsqu'un modèle échoue à rendre compte d'un aspect du comportement humain, cet échec représente simultanément un défi méthodologique et une opportunité scientifique exceptionnelle :
- Le défi est d'identifier **quelle composante précise du modèle est responsable de l'erreur** ;
- L'opportunité réside dans le fait que l'échec focalise l'attention des chercheurs sur les angles morts théoriques, déclenchant des avancées empiriques spectaculaires.

**L'exemple de la lecture de mots isolés :**  
Dans le modèle développemental de lecture de Seidenberg et McClelland (1989), un réseau connexionniste apprenait à prononcer des mots réguliers et des mots irréguliers (exceptions) au sein d'une **voie unique intégrée**, défiant la théorie classique de la « double voie » (qui postulait un lexique pour les exceptions et un système de règles graphème-phonème pour les régularités).

Des critiques (Besner et al., 1990 ; Coltheart et al., 1993) ont objecté que le réseau échouait à lire correctement des **pseudo-mots nouveaux** (non-mots prononçables), n'atteignant que 60 % d'exactitude là où les humains atteignent 95 %. Les partisans de la double voie ont immédiatement crié à la réfutation définitive du connexionnisme !

Pourtant, en retravaillant le modèle (Plaut, McClelland, Seidenberg & Patterson, 1996), nous avons découvert que la faille ne résidait nullement dans le principe connexionniste de la voie unique, mais dans les détails du schéma de codage des entrées phonologiques. Avec des représentations phonotactiques améliorées, le réseau révisé parvint à lire à la fois les mots irréguliers et les pseudo-mots inconnus avec une précision égale à celle des humains !

**L'exemple du modèle d'activation interactive :**  
Dans le modèle d'activation interactive pour la perception des mots et des lettres (McClelland & Rumelhart, 1981) et le modèle TRACE pour la parole (McClelland & Elman, 1986), nous postulions une propagation bidirectionnelle (interactive) de l'activation entre les niveaux sensoriel, lexical et conceptuel. Dominic Massaro (1989) a vivement critiqué l'architecture en montrant qu'elle ne cadrait pas avec certaines données quantitatives d'intégration de traits. Là encore, la cause n'était pas l'interactivité, mais le déterminisme absolu du calcul. En incorporant du **bruit stochastique intrinsèque** dans les unités, le modèle a parfaitement reproduit les données empiriques (McClelland, 1991).


<!-- ======================================================================= -->
<!-- PAGE 10                                                                 -->
<!-- ======================================================================= -->

### 3.6. Ce que l'exploration des modèles peut nous enseigner

Les modèles permettent d'évaluer la suffisance, l'optimalité et l'adéquation empirique des hypothèses scientifiques. Mais cette évaluation doit être conduite avec discernement, car un modèle réunit une mosaïque de propriétés : isoler celle qui est responsable d'une réussite ou d'un échec exige une longue série d'expérimentations computationnelles.

### 3.7. Ce que l'exploration des modèles NE PEUT PAS prouver

Il importe d'insister vigoureusement sur ce qu'un modèle ne pourra jamais accomplir :

> **Même si un chercheur démontre que son modèle s'ajuste parfaitement à l'ensemble des données expérimentales disponibles, ce succès ne prouve JAMAIS que le modèle constitue l'explication vraie des processus cognitifs sous-jacents.**

L'ajustement aux données établit uniquement que les principes incarnés dans le modèle sont **compatibles** avec les faits observés. Le modèle ne peut donc pas être rejeté sur cette base. Mais d'autres architectures radicalement différentes pourraient s'ajuster tout aussi bien. C'est l'application directe de l'épistémologie de Karl Popper (1959) : **un modèle peut être réfuté par les faits, mais il ne peut jamais être vérifié de façon définitive.**

### 3.8. Les modèles sont-ils jamais réfutables ?

Certains critiques prétendent que les modélisateurs disposent d'un nombre infini de paramètres libres (*degrees of freedom*) et qu'ils peuvent ajuster n'importe quel ensemble de données en tournant des molettes (*parameter twiddling*).

Cette objection est infondée dans la pratique scientifique sérieuse. Lorsqu'un modèle souffre d'un défaut structurel fondamental, aucun bricolage de paramètres ne parvient à masquer l'échec. Ce sont précisément ces échecs tenaces qui forcent les chercheurs à réviser leurs théories.


<!-- ======================================================================= -->
<!-- PAGE 11                                                                 -->
<!-- ======================================================================= -->

### 3.9. Vers une transparence accrue des modèles cognitifs

En tant que discipline, nous faisons face à de redoutables défis pour élucider la nature des processus cognitifs, même équipés de tous les outils sophistiqués de la modélisation computationnelle. La modélisation ne nous permet d'évaluer que des combinaisons particulières de propriétés, explorées conjointement avec des simplifications délibérées et des choix arbitraires de mise en œuvre. Lorsqu'un modèle échoue à s'ajuster à un ensemble de données expérimentales, nous savons seulement que *quelque chose* cloche, mais attribuer précisément la responsabilité de l'erreur est une entreprise éminemment complexe.

Le fait que de nombreux modèles manquent de transparence a suscité une vive insatisfaction, en particulier à l'égard des modèles connexionnistes qualifiés parfois de « boîtes noires opaques » (McCloskey, 1991). Ce problème n'est toutefois pas l'apanage de la psychologie : il surgit dans toutes les sciences qui manipulent des systèmes complexes. Cela ne justifie nullement d'abandonner les modèles ; cela exige au contraire de les ériger en objets d'investigation scientifique à part entière afin de disséquer leurs principes formels.

Comment pouvons-nous accroître leur niveau de transparence et d'intelligibilité ? L'un des leviers majeurs que notre discipline sous-exploite encore est **l'analyse mathématique rigoureuse**. Nous devons nous efforcer de conduire de telles analyses chaque fois que possible, même si elles exigent des simplifications préalables draconiennes. Lorsque ces dérivations formelles sont articulées à des simulations numériques systématiques qui s'affranchissent des simplifications, nous accédons à une compréhension théorique authentique. Mes propres recherches ont tiré un profit immense de collaborations étroites avec des physiciens et des mathématiciens (McClelland & Chappell, 1998 ; Movellan & McClelland, 2001 ; Usher & McClelland, 2001).

---

## 4. Les grands cadres de modélisation cognitive (*Frameworks*)

Un ouvrage récent et précieux, le *Cambridge Handbook of Computational Psychology* (Sun, 2008), dresse un panorama de l'état de l'art dans notre discipline en regroupant les modèles sous divers paradigmes :
- Les modèles connexionnistes (Thomas & McClelland, 2008) ;
- Les modèles bayésiens (Griffiths, Kemp & Tenenbaum, 2008) ;
- Les approches par systèmes dynamiques (Schöner, 2008) ;
- Les modèles déclaratifs fondés sur la logique (Bringsjord, 2008) ;
- Les architectures cognitives unifiées (Taatgen & Anderson, 2008).

Je préfère personnellement les termes de **« cadre »** (*framework*) ou d'**« approche »** à celui de « paradigme », trop rigide.

Les tentatives visant à comparer ces approches ont souvent été formulées en termes de **niveaux d'analyse** (notamment la tripartition classique de David Marr, 1982). On soutient ainsi fréquemment que les modèles connexionnistes / PDP se situent au niveau de l'implémentation physique et neuronale (Broadbent, 1985 ; Pinker & Prince, 1988 ; Smolensky, 1988), tandis que d'autres approches opèrent au niveau algorithmique ou au niveau computationnel de Marr. Mes collègues et moi-même avons contesté cette hiérarchie réductrice : l'approche connexionniste PDP propose **des représentations et des processus alternatifs**, et défend une posture résolument distincte au **niveau computationnel** lui-même (Rogers & McClelland, 2004, 2008 ; Rumelhart & McClelland, 1985).

Chaque cadre théorique a rallié des partisans parce qu'il se révèle particulièrement adapté à une classe spécifique de phénomènes cognitifs. Chacun possède ses zones d'avantage comparatif, ses limites intrinsèques et ses espaces de controverse.


<!-- ======================================================================= -->
<!-- PAGE 12                                                                 -->
<!-- ======================================================================= -->

### 4.1. Les modèles connexionnistes / Traitement Parallèle Distribué (PDP)

Les modèles connexionnistes / PDP offrent une manière naturelle et puissante d'expliquer une vaste gamme de phénomènes cognitifs tout en proposant une rupture radicale avec les thèses symboliques classiques. 

Leur domaine naturel d'application privilégié englobe tous les aspects de la cognition qui reposent sur des **processus quasi automatiques forgés par une longue expérience environnementale** :
- La perception visuelle et auditive ;
- La mémoire associative et intuitive ;
- La sémantique incarnée et la catégorisation ;
- La lecture et le traitement du langage naturel.

Il est indéniable que les modélisateurs connexionnistes s'inspirent de l'architecture du cerveau pour construire leurs réseaux ; mais la portée de cette filiation biologique est souvent mal comprise. La plupart des chercheurs en sciences cognitives connexionnistes ne trouvent pas cette inspiration attrayante pour elle-même (pour singer la biologie), mais pour sa fécondité fonctionnelle à résoudre des énigmes computationnelles et psychologiques majeures (Anderson, 1977 ; McClelland, Rumelhart & Hinton, 1986).

Par exemple, dans le modèle d'activation interactive (McClelland & Rumelhart, 1981), notre motivation première était d'explorer l'idée que **la satisfaction simultanée de contraintes mutuelles multiples** sous-tend la remarquable capacité humaine à percevoir un élément beaucoup plus vite et avec plus d'exactitude lorsqu'il s'insère dans un contexte familier cohérent (effet de supériorité du mot, Rumelhart, 1977). Le formalisme des réseaux de neurones interconnectés s'est révélé idéal pour concrétiser cette intuition.

De même, dans notre modèle du temps passé (Rumelhart & McClelland, 1986), notre motivation était d'éprouver l'hypothèse selon laquelle les êtres humains peuvent manifester un comportement linguistique hautement régulier et généralisable **sans faire appel à des règles symboliques formelles**. Nous étions convaincus que la frontière entre régularités grammaticales et exceptions n'est pas dichotomique et catégorielle, mais s'inscrit le long d'un **continuum de régularité statistique**. L'inspiration neurobiologique — un ensemble d'unités de traitement simples échangeant des signaux pondérés par des connexions ajustables par l'expérience — fournissait la matrice idéale pour explorer ces idées.

Cette inspiration neuronale a généré des bénéfices immenses, mais aussi des malentendus. Certains ont reproché aux réseaux PDP de violer des détails neurophysiologiques connus (comme la règle de Dale ou les potentiels d'action discrets). Bien que j'aie pu partager ce souci par moments, je considère désormais ce débat comme mal posé : les facultés cognitives humaines défient encore nos modèles les plus avancés. Nos efforts doivent s'inspirer des neurosciences, mais ne doivent en aucun cas être emprisonnés dans un lit de Procuste par notre conception parcellaire actuelle de la biologie cérébrale.


<!-- ======================================================================= -->
<!-- PAGE 13                                                                 -->
<!-- ======================================================================= -->

### 4.2. Les approches rationnelles et bayésiennes

Les approches rationnelles en sciences cognitives procèdent de la conviction, ou du moins de l'espoir, qu'il est possible d'appréhender la cognition et le comportement humains comme **une réponse optimale aux contraintes imposées à l'agent cognitif par son environnement**. Une démarche « rationnelle » intègre tout naturellement les concepts bayésiens, qui prescrivent formellement quelles inférences doivent être tirées d'observations incertaines ou bruitées, mais elle incorpore également un arbitrage entre coûts et bénéfices (où le temps et l'effort computationnel constituent des coûts majeurs imposant une rationalité limitée, Simon, 1957).

Il est indéniablement légitime de s'interroger sur ce que serait la politique de décision optimale dans une tâche donnée, car cela fournit un étalon normatif permettant de mesurer si les humains sont optimaux, et d'isoler précisément leurs déviations systématiques.

Dans certains domaines perceptifs et inductifs, l'analyse rationnelle bayésienne a produit des prédictions empiriques remarquablement vérifiées :
- **Perception visuelle :** Geisler et Perry ont analysé statistiquement les scènes naturelles pour calculer la probabilité exacte que deux segments de droite émergeant d'un occluseur appartiennent à une même arête continue. Les jugements d'observateurs humains coïncident avec une précision frappante avec les probabilités objectives dérivées des statistiques de l'environnement physique.
- **Généralisation sémantique :** Roger Shepard (1987) et Xu et Tenenbaum (2007) ont démontré comment les inférences humaines sur l'extension d'un concept s'ajustent optimalement aux distributions bayésiennes des exemplaires rencontrés.

Cependant, le cadre bayésien contemporain suscite d'importantes réserves critiques :
Dans les modèles de Kemp et Tenenbaum, l'apprentissage est défini comme **la sélection explicite, parmi un ensemble de structures de connaissances prédéfinies à l'avance (arbres taxonomiques, graphes, ordres linéaires), de celle qui s'ajuste le mieux aux données**. Il ne s'agit donc pas seulement d'un principe bayésien pur, mais d'une théorie substantielle postulant un répertoire inné de structures géométriques abstraites. Ce qui sépare nos modèles connexionnistes (Rogers & McClelland, 2004) de ces modèles bayésiens structurés n'est pas le calcul des probabilités, mais **le refus connexionniste de postuler des structures préexistantes figées au profit d'une émergence continue de représentations distribuées**.


<!-- ======================================================================= -->
<!-- PAGE 14                                                                 -->
<!-- ======================================================================= -->

Considérée plus largement, l'approche des « modèles rationnels » fait face à un problème méthodologique fondamental : **ce qui est décrété « rationnel » dépend entièrement de ce que le théoricien postule être le but subjectif de l'agent dans la tâche**.

Par exemple, si un participant humain refuse d'abaisser son seuil de décision pour maximiser son taux global de gain monétaire dans une tâche de temps de réaction, nous ne pouvons pas en conclure hâtivement qu'il est irrationnel : nous avons peut-être ignoré une variable subjective majeure dans sa fonction de coût interne — pour lui, éviter de commettre une erreur humiliante peut avoir une valeur infiniment supérieure au gain de quelques points. Si nous introduisons un paramètre libre pour représenter cette préférence subjective, nous pourrons alors expliquer *a posteriori* n'importe quel seuil de réponse arbitraire, et la théorie de la rationalité perdra tout pouvoir réfutatif !

De surcroît, les partisans des modèles optimaux invoquent couramment **la sélection naturelle évolutionnaire** comme garantie que l'esprit humain doit être optimal. Les failles monumentales de ce raisonnement ont été brillamment exposées par le biologiste Stephen Jay Gould (1980) dans *Le pouce du panda* :
1. **L'évolution ne produit jamais un optimum global idéal :** Elle sélectionne localement pour un avantage compétitif relatif immédiat au sein d'une population donnée ;
2. **Les contraintes historiques et phylogénétiques :** Les adaptations biologiques sont des bricolages d'organes préexistants (ex. le faux pouce du panda géant façonné à partir d'un os sésamoïde du poignet), non des architectures d'ingénierie créées *ex nihilo* sur une table à dessin ;
3. **Le décalage environnemental :** Rien ne garantit que les compromis forgés dans l'environnement ancestral de nos ancêtres hominidés demeurent optimaux dans le monde technologique contemporain.

Par conséquent, tout comme l'inspiration issue de la biologie neuronale n'est pas une garantie automatique de vérité psychologique pour le connexionnisme, **l'invocation de la rationalité ou de la sélection naturelle n'est en rien une garantie de succès pour un modèle cognitif**. Les modèles issus de ces deux démarches doivent être jugés exclusivement sur leur fécondité concrète à expliquer les données empiriques réelles.


<!-- ======================================================================= -->
<!-- PAGE 15                                                                 -->
<!-- ======================================================================= -->

### 4.3. Les approches par les systèmes dynamiques

L'approche par les **systèmes dynamiques** prend son essor dans l'affirmation de la nature située et incarnée (*embodied and situated*) du comportement humain (Schöner, 2008). De fait, elle a principalement été appliquée :
- Aux propriétés physiques et motrices de l'action (le réflexe de marche chez le nourrisson selon sa posture corporelle, Thelen & Smith, 1994) ;
- À l'impact direct des variables physiques environnementales sur le comportement (l'impact de l'agencement spatial du test sur la fameuse **erreur A-non-B** de Jean Piaget, Thelen, Schöner, Scheier & Smith, 2001).

La présence ou l'absence de ces conduites développementales avait été jusqu'alors interprétée par la psychologie classique comme le signe de la maturation de représentations cognitives internes (la permanence de l'objet) ou de mécanismes inhibiteurs corticaux. Les systèmes dynamiques ont jeté un éclairage radicalement nouveau :

Par exemple, des nourrissons tenus debout manifestent des mouvements coordonnés de marche réflexe dans leurs premières semaines de vie, puis cessent de le faire vers deux mois, avant de remarcher beaucoup plus tard. Les théories traditionnelles postulaient une inhibition corticale transitoire. Esther Thelen et Linda Smith (1994) ont démontré, par des manipulations physiques simples (immerger les jambes du bébé dans l'eau pour réduire l'effet de la gravité), que **cette disparition temporaire s'explique simplement par la masse graisseuse accrue des cuisses du nourrisson que sa force musculaire ne parvient pas encore à soulever**. L'explication n'est pas cognitive, elle est purement biomécanique et dynamique !

Bien que cette démarche ait produit des modèles passionnants de la motricité physique, la question de savoir si elle permettra d'édifier une théorie globale de la cognition supérieure demeure entièrement ouverte. Jusqu'à présent, les systèmes dynamiques sont restés relativement silencieux sur la manière dont les connaissances s'acquièrent à travers l'expérience, les transitions qualitatives étant souvent modélisées par des « paramètres de contrôle » imposés arbitrairement de l'extérieur par l'expérimentateur. L'extension du cadre aux aspects symboliques et abstraits de la pensée constitue leur défi pour l'avenir.


<!-- ======================================================================= -->
<!-- PAGE 16                                                                 -->
<!-- ======================================================================= -->

### 4.4. Les approches symboliques et logiques

L'idée selon laquelle la pensée humaine consiste essentiellement à dériver de nouvelles propositions à partir de propositions antérieures et de règles d'inférence déductive plonge au cœur de notre tradition philosophique occidentale. Il n'est donc nullement surprenant qu'elle ait régné en maître aux débuts des sciences cognitives.

Jerry Fodor et Zenon Pylyshyn (1988) ont formulé la thèse selon laquelle **la caractéristique distinctive fondamentale de l'esprit réside dans sa capacité à opérer sur des contenus arbitraires au moyen de règles sensibles à la structure et insensibles au contenu (*structure-sensitive, content-invariant rules*)**.

C'est incontestablement l'un des accomplissements suprêmes de l'intelligence humaine que d'avoir forgé des systèmes d'inférence de cette nature — ces systèmes ont permis de démontrer les théorèmes de la géométrie, de l'algèbre et du calcul infinitésimal. Il était donc naturel de concevoir la pensée humaine elle-même comme un tel système formel. L'apprentissage des règles de calcul arithmétique ou de la programmation informatique est au centre de l'éducation moderne, et de nombreuses erreurs commises par les élèves peuvent être rigoureusement analysées comme l'absence ou l'application défectueuse d'une règle sensible à la structure (par exemple l'analyse minutieuse des erreurs d'emprunt dans les soustractions à colonnes par Brown & VanLehn, 1980). Le cadrage de nombreuses tâches cognitives en termes de systèmes de règles formelles continuera donc à jouer un rôle important.

Pourtant, deux questions critiques s'imposent :
1. Dans quelle mesure ce cadre s'applique-t-il aux aspects ordinaires, non formels de la cognition quotidienne ?
2. Même en logique et en mathématiques, les éclairs de compréhension intuitive (*insight*) qui permettent d'exploiter un système formel se déroulent-ils réellement selon les règles de ce système lui-même ?

L'affirmation selon laquelle les règles formelles sont indispensables pour rendre compte du langage naturel (postulée par Chomsky, 1957, et reprise par Fodor & Pylyshyn) a été vigoureusement contestée tant par les linguistes fonctionnalistes (Bybee, 2001 ; Kuno, 1987) que par les sciences cognitives computationnelles (Elman, in press ; McClelland, 1992). Les locuteurs natifs appliquent des régularités sans jamais avoir accès consciemment à des règles formelles explicites.


<!-- ======================================================================= -->
<!-- PAGE 17                                                                 -->
<!-- ======================================================================= -->

L'idée qu'une approche logiciste s'applique universellement au raisonnement humain bute contre un écueil expérimental célèbre : **la tâche de sélection de Peter Wason (1966)**.

Dans cette expérience classique, les participants se révèlent dramatiquement incapables de choisir quelles cartes retourner pour vérifier la règle conditionnelle abstraite : *« Si une carte a une voyelle sur une face, alors elle a un chiffre pair sur l'autre face. »* Moins de 10 % des adultes éduqués sélectionnent la combinaison logique exacte (retourner la voyelle $P$ et le chiffre impair $\neg Q$, selon le *modus tollens*).

En revanche, dès que la tâche est formulée sous une forme concrète régie par un contrat social ou un contexte déontologique familier (*« Si une personne boit de l'alcool, elle doit avoir plus de 18 ans »*, ou *« Si l'enveloppe est scellée, elle doit être affranchie à 20 centimes »*), le taux de réussite grimpe en flèche à plus de 80 % ! Ce phénomène démontre de façon irréfutable que **le raisonnement humain ordinaire n'opère pas au moyen de règles syntaxiques abstraites insensibles au contenu**, mais mobilise des schémas pragmatiques et sémantiques contextuels (Cosmides, 1989 ; Oaksford & Chater, 1996).

Face à ces limites du logicisme pur, les systèmes de production symboliques modernes ont profondément évolué. Le cadre contemporain le plus influent, **ACT-R** (développé par John R. Anderson et Christian Lebiere, 1998), associe certes des propositions déclaratives explicites et des règles de production condition-action, mais il introduit des mécanismes novateurs :
- Les règles peuvent faire explicitement référence au contexte sémantique de la tâche ;
- Elles ne sont pas accessibles consciemment par introspection directe ;
- Et surtout, **ACT-R dote chaque fait déclaratif et chaque règle de production de variables de force continue graduée (*strength variables*)**, qui reflètent la fréquence d'usage, la récence et l'utilité bayésienne estimée de la règle.

L'incorporation de pondérations continues graduées et de mécanismes statistiques d'apprentissage au sein des systèmes de production symboliques rend la frontière empirique entre modèles symboliques modernes et modèles connexionnistes de plus en plus poreuse et floue.


<!-- ======================================================================= -->
<!-- PAGE 18                                                                 -->
<!-- ======================================================================= -->

### 4.5. Architectures cognitives et systèmes hybrides

Le constat que chacun des grands cadres de modélisation possède ses atouts propres a naturellement favorisé l'essor des **systèmes hybrides** (Sun, 2002) et des **architectures cognitives unifiées** (Jilk, Lebiere, O'Reilly & Anderson, 2008).

L'ambition première d'une architecture cognitive est d'offrir une instanciation intégrée d'un **système cognitif humain complet**. Allen Newell (1990, 1994, *Unified Theories of Cognition*) plaidait passionnément pour une couverture comportementale globale et intégrée, quitte à sacrifier la précision fine de certains ajustements locaux dans un domaine isolé — reflétant son dessein d'ingénieur visant à concevoir un système opérationnel complet, par contraste avec l'ambition psychologique étroite d'isoler un micro-phénomène en laboratoire.

L'édification de telles architectures devient particulièrement impérieuse si l'on admet que notre esprit est constitué de **sous-systèmes modulaires fonctionnellement différenciés**. Dans ce cas, comprendre la cognition dans son ensemble exige non seulement d'élucider le fonctionnement intime de chaque composant, mais surtout de comprendre **comment ces différents modules s'articulent et collaborent en synergie**.

La spécialisation fonctionnelle du cerveau est une réalité anatomique incontournable, et caractériser les rôles respectifs des structures cérébrales constitue une priorité absolue des neurosciences cognitives. J'ai moi-même formulé des propositions fondées sur la complémentarité des systèmes d'apprentissage (McClelland, McNaughton & O'Reilly, 1995) :
- **L'hippocampe :** Spécialisé dans l'apprentissage épisodique ultra-rapide et l'encodage d'expériences uniques sans interférence ;
- **Le néocortex :** Spécialisé dans l'extraction lente et progressive de connaissances sémantiques partagées et de régularités structurelles distribuées.

Je mets toutefois en garde contre certaines approches hybrides qui adoptent une logique disjonctive étanche de type « tout-ou-rien », assignant mécaniquement une tâche donnée soit à un module symbolique soit à un module connexionniste. L'avenir réside bien plutôt dans des modèles où des sous-systèmes hétérogènes **coopèrent en synergie continue par satisfaction mutuelle de contraintes** (comme dans l'architecture hybride **CLARION** de Ron Sun, 2002, 2008).


<!-- ======================================================================= -->
<!-- PAGE 19                                                                 -->
<!-- ======================================================================= -->

## 5. L'avenir de la modélisation cognitive

Selon l'inventeur et futurologue Raymond Kurzweil, la croissance exponentielle de la puissance des ordinateurs se poursuivra indéfiniment sans ralentir. Dans son ouvrage *The Singularity Is Near* (2005), il prédisait que les ordinateurs personnels atteindraient une puissance de calcul équivalente à celle du cerveau humain dès l'an 2020. D'ici 2045, prévoit-il, nous atteindrons la **singularité technologique** — un basculement vers des intelligences artificielles véritablement autonomes, infiniment plus intelligentes que les humains et capables d'engendrer par elles-mêmes des versions supérieures d'elles-mêmes.

Bien que l'on puisse légitimement douter de la pérennité sans faille de cette croissance exponentielle et de son impact réel sur l'intelligence des machines, il est indubitable que l'informatique deviendra toujours plus prodigieuse, ubiquitaire et puissante. Il est donc passionnant de s'interroger sur ce que ces développements technologiques réservent à la modélisation en sciences cognitives.

Si la loi de Moore continue de s'appliquer, nous disposerons d'ici vingt ans d'ordinateurs **1 000 fois plus rapides** que ceux d'aujourd'hui (soit un facteur de plusieurs milliards par rapport aux machines des années 1950).

Que permettra concrètement cette débauche de puissance de calcul pour notre discipline ? J'envisage trois extensions majeures :
1. **L'accroissement de l'échelle et du contenu (*Scale and Content*) :** La possibilité de construire des réseaux dotés de millions d'unités et de milliards de connexions synaptiques, capables d'ingérer de véritables corpus massifs de données textuelles, visuelles et auditives, se rapprochant de l'expérience sensorielle accumulée par un être humain au fil d'une vie entière.
2. **L'enrichissement du réalisme biologique :** La possibilité de simuler des réseaux intégrant des neurones à impulsions (*spiking neurons*), des compartiments dendritiques complexes, des récepteurs synaptiques multiples (AMPA, NMDA, GABA) et des modulations astrocytaires.
3. **L'inscription dans des environnements virtuels incarnés (*Embodiment and Situatedness*) :** La possibilité d'immerger des agents cognitifs artificiels au sein d'environnements physiques ou virtuels immersifs tridimensionnels réalistes, exigeant une coordination motrice en temps réel fermée sur l'environnement.


<!-- ======================================================================= -->
<!-- PAGE 20                                                                 -->
<!-- ======================================================================= -->

Toutefois, je tiens à sonner l'alarme contre une illusion technologique pernicieuse :

> **La puissance brute de calcul ne se substituera jamais à l'invention de nouveaux cadres conceptuels théoriques.**

Si l'expansion de la puissance informatique ne s'accompagne pas d'une réflexion épistémologique profonde sur les principes organisationnels de l'esprit, elle ne produira rien d'autre que des modèles éléphantesques, aussi opaques et inexplicables que le cerveau biologique lui-même. Nous nous retrouverions alors exactement dans la situation absurde des cartographes de Borges, contemplant une simulation informatique grandeur nature du cerveau dont le fonctionnement interne nous échapperait totalement !

Le défi ultime de la modélisation cognitive n'est pas de construire un cerveau artificiel grandeur nature, mais de **dégager des lois qualitatives de fonctionnement de l'esprit intelligibles pour l'intelligence humaine**.


<!-- ======================================================================= -->
<!-- PAGE 21                                                                 -->
<!-- ======================================================================= -->

### 5.1. Des modèles dotés d'une plus grande fidélité aux réseaux neuronaux réels

Aujourd'hui, je peux acheter un ordinateur de bureau pour environ 2 000 dollars qui exécute environ 15 millions d'opérations en virgule flottante par seconde (FLOPS). Comme il faut environ deux opérations par synapse pour propager l'activité à travers un réseau (et deux autres pour mettre à jour les poids synaptiques), je peux, en gros, simuler en temps réel un réseau d'un million de connexions avec une granularité temporelle d'une mise à jour chaque quart de seconde.

Un bond d'un facteur 1 000 dans la puissance de calcul permettrait de simuler **40 fois plus de connexions avec une fidélité temporelle 25 fois supérieure**, soit 40 millions de synapses mises à jour 100 fois par seconde. Une telle échelle correspond approximativement à la taille de **l'hippocampe du rongeur**, et l'échelle temporelle devient suffisante pour modéliser la décharge neuronale précise aux différentes phases du **rythme thêta** (cette oscillation à 8 Hz qui balaie l'hippocampe).

Simuler l'hippocampe du rat en temps réel avec cette précision permettrait d'éprouver en profondeur les théories actuelles du stockage et du rappel mnésiques (Hasselmo, Bodelón & Wyble, 2002 ; Mehta, Lee & Wilson, 2002), qui reposent sur le déphasage temporel fin des potentiels d'action pour encoder des séquences d'événements. Un facteur 10 supplémentaire permettrait même de simuler les **ondes aiguës et oscillations rapides (200 Hz / *sharp wave ripples*)**, durant lesquelles les souvenirs épisodiques compressés sont « rejoués » (*replay*) pour assurer leur consolidation progressive dans le néocortex (Buzsáki et al., 1992).

Une telle simulation à grande échelle ne relève pas de la vaine quête d'un réalisme gratuit pour lui-même : elle permet de tester rigoureusement si les mécanismes biophysiques postulés fonctionnent réellement avec l'efficacité qu'on leur prête, et d'affiner notre compréhension des rouages de la mémoire.


<!-- ======================================================================= -->
<!-- PAGE 22                                                                 -->
<!-- ======================================================================= -->

### 5.2. Des modèles dotés de bases de connaissances sémantiques massives

La grande majorité des modèles actuels opèrent sur des bases de connaissances extrêmement étriquées et des représentations d'items appauvries. Pour la lecture de mots, nous pouvons certes modéliser des vocabulaires quasi complets (Sibley, Kello, Plaut & Elman, 2008), et il est possible d'extraire des approximations de sens à partir de matrices de cooccurrences lexicales (Landauer & Dumais, 1997 ; Griffiths, Steyvers & Tenenbaum, 2007).

Cependant, le réservoir sémantique humain est édifié à partir du flux ininterrompu d'expériences visuelles, tactiles et auditives d'objets réels et de paroles entendues. Si l'on traduit grossièrement cette expérience en texte, un être humain est exposé à l'équivalent d'environ **100 000 mots par jour**. Une puissance de calcul multipliée par 1 000 facilitera grandement l'extraction de régularités statistiques à partir d'un tel déluge de données sensorielles réelles.

### 5.3. Complexité accrue des agents cognitifs situés et incarnés

Un autre horizon passionnant réside dans le pilotage d'**agents cognitifs incarnés (*situated agents*)** interagissant avec leur environnement et avec d'autres agents. Des chercheurs utilisent déjà des robots humanoïdes pour explorer des univers simplifiés où les agents apprennent à manipuler des objets et à négocier un vocabulaire émergent partagé (Luc Steels, 2007).

À mesure que la puissance de calcul croîtra, ces robots intégreront de multiples processeurs spécialisés dans l'intégration multimodale (vision, ouïe, toucher, proprioception). La démultiplication de la puissance computationnelle est la condition sine qua non de ces développements vers une véritable cognition incarnée.


<!-- ======================================================================= -->
<!-- PAGE 23                                                                 -->
<!-- ======================================================================= -->

## 6. À quoi pourraient ressembler les futurs cadres de modélisation ?

Prédire l'avenir est un exercice notoirement périlleux ; mais au vu des dynamiques contemporaines, nous pouvons anticiper quelques évolutions probables :

1. **La convergence féconde entre connexionnisme et approches bayésiennes :**  
   J'attends avec impatience **l'effacement des frontières entre modèles probabilistes/bayésiens et modèles connexionnistes**. Il existe une correspondance mathématique beaucoup plus étroite entre ces deux approches qu'on ne le suppose communément (McClelland, 1998), comme l'illustrent nos modèles hybrides intégrant l'apprentissage distribué de distributions statistiques continues (Vallabha et al., 2007).
2. **L'intégration des systèmes dynamiques et des réseaux neuronaux :**  
   Les approches par systèmes dynamiques et le connexionnisme partagent d'immenses territoires conceptuels. De fait, la plupart des modèles dynamiques contemporains sont des réseaux de neurones récurrents dotés d'attracteurs, de variabilité stochastique intrinsèque et d'inhibitions latérales topographiques (Spencer, Thomas & McClelland, 2009).
3. **Le statut épistémologique du paradigme symbolique :**  
   Je suis enclin à penser que **le cadre symbolique propositionnel sera compris comme une description approximative macroscopique d'un processus sous-jacent infiniment plus riche, dynamique et continu**, analogue à ce que simulent les réseaux connexionnistes distribués. Néanmoins, le niveau symbolique subsistera comme un formalisme indispensable et succinct pour représenter les contenus de pensée abstraits et la communication logique.
4. **L'émergence d'un cadre conceptuel radicalement inédit :**  
   Enfin, je forme l'espoir que surgira au cours des vingt prochaines années **un cadre théorique entièrement nouveau et aujourd'hui insoupçonné**. Son avènement exigera à la fois une puissance de calcul décuplée et, par-dessus tout, **des éclairs de génie théorique novateurs** capables d'émanciper les sciences cognitives des frontières étriquées de nos paradigmes actuels.


<!-- ======================================================================= -->
<!-- PAGE 24                                                                 -->
<!-- ======================================================================= -->

### Remerciements

L'auteur remercie chaleureusement Tim Rogers pour ses discussions stimulantes ayant contribué à la formulation de certaines idées de cet article, Mike Lee et Amy Perfors pour leurs contributions sur le rôle des calculateurs dans la modélisation bayésienne, ainsi que Wayne Gray, Karalyn Patterson et un évaluateur anonyme pour leurs remarques constructives sur les versions antérieures du manuscrit.

---

### Références Bibliographiques (Partie 1 : A–B)

- **Alibali, M. W., & Goldin-Meadow, S. (1993).** Gesture–speech mismatch and mechanisms of learning: What the hands reveal about a child’s state of mind. *Cognitive Psychology*, 25, 468–523.
- **Anderson, J. A. (1977).** Neural models with cognitive implications. In D. LaBerge & S. J. Samuels (Eds.), *Basic processes in reading: Perception and comprehension* (pp. 27–90). Hillsdale, NJ: Erlbaum.
- **Anderson, J. R., & Lebiere, C. (1998).** *The atomic components of thought.* Mahwah, NJ: Erlbaum.
- **Ashby, F. G. (1982).** Deriving exact predictions from the cascade model. *Psychological Review*, 89, 599–607.
- **Bengio, Y., Lamblin, P., Popovici, D., & Larochelle, H. (2007).** Greedy layer-wise training of deep networks. In B. Schölkopf, J. Platt & T. Hoffman (Eds.), *Advances in Neural Information Processing Systems (NIPS)*. Cambridge, MA: MIT Press.
- **Besner, D., Twilley, L., McCann, R. S., & Seergobin, K. (1990).** On the connection between connectionism and data: Are a few words necessary? *Psychological Review*, 97, 432–446.
- **Borges, J. L. (1998).** On the exactitude of science. In *Collected Fictions*, trad. A. Hurley (p. 325). London: Penguin. [Édition originale : *De la rigueur de la science*, 1946].
- **Bringsjord, S. (2008).** Declarative / logic-based cognitive models. In R. Sun (Ed.), *Cambridge Handbook of Computational Psychology* (pp. 127–169). New York: Cambridge University Press.
- **Broadbent, D. (1985).** A question of levels: Comment on McClelland and Rumelhart. *Journal of Experimental Psychology: General*, 114, 189–192.
- **Brown, J. S., & VanLehn, K. (1980).** Repair theory: A generative theory of bugs in procedural skills. *Cognitive Science*, 4, 379–426.
- **Buzsaki, G., Horvath, Z., Urioste, R., Hetke, J., & Wise, K. (1992).** High frequency network oscillation in the hippocampus. *Science*, 256, 1025–1027.
- **Bybee, J. (2001).** *Phonology and language use.* New York: Cambridge University Press.
- **Bybee, J., & Slobin, D. I. (1982).** Rules and schemas in the development and use of the English past tense. *Language*, 58, 265–289.


<!-- ======================================================================= -->
<!-- PAGE 25                                                                 -->
<!-- ======================================================================= -->

### Références Bibliographiques (Partie 2 : C–G)

- **Chomsky, N. (1957).** *Syntactic Structures.* The Hague: Mouton.
- **Coltheart, M., Curtis, B., Atkins, E., & Hailer, M. (1993).** Models of reading aloud: Dual-route and parallel-distributed-processing approaches. *Psychological Review*, 100, 589–608.
- **Cosmides, L. (1989).** The logic of social exchange: Has natural selection shaped how humans reason? Studies with the Wason selection task. *Cognition*, 31, 187–276.
- **Elman, J. L. (in press).** On the meaning of words and dinosaur bones: Lexical knowledge without a lexicon. *Cognitive Science*.
- **Fodor, J. A., & Pylyshyn, Z. W. (1988).** Connectionism and cognitive architecture: A critical analysis. *Cognition*, 28, 3–71.
- **Geisler, W. S., & Perry, J. S. (in press).** Contour statistics in natural images: grouping across occlusions. *Visual Neuroscience*.
- **Gould, S. J. (1980).** *The Panda's Thumb: More Reflections in Natural History.* New York: W. W. Norton. [Édition française : *Le pouce du panda*, Grasset].
- **Griffiths, T. L., Kemp, C., & Tenenbaum, J. B. (2008).** Bayesian models of cognition. In R. Sun (Ed.), *Cambridge Handbook of Computational Psychology* (pp. 59–100). New York: Cambridge University Press.
- **Griffiths, T. L., Steyvers, M. X., & Tenenbaum, J. B. (2007).** Topics in semantic representation. *Psychological Review*, 114, 211–244.
- **Grossberg, S. (1978).** A theory of human memory: Self-organization and performance of sensory-motor codes, maps, and plans. *Progress in Theoretical Biology*, 5, 233–374.


<!-- ======================================================================= -->
<!-- PAGE 26                                                                 -->
<!-- ======================================================================= -->

### Références Bibliographiques (Partie 3 : H–M)

- **Hasselmo, M. E., Bodelón, C., & Wyble, B. P. (2002).** A proposed function for hippocampal theta rhythm: Separate phases of encoding and retrieval enhance reversal of prior learning. *Neural Computation*, 14, 793–817.
- **Hebb, D. O. (1949).** *The Organization of Behavior: A Neuropsychological Theory.* New York: Wiley.
- **Hinton, G. E., & Salakhutdinov, R. R. (2006).** Reducing the dimensionality of data with neural networks. *Science*, 313, 504–507.
- **Jackendoff, R. (2002).** *Foundations of Language: Brain, Meaning, Grammar, Evolution.* Oxford: Oxford University Press.
- **Jilk, D. J., Lebiere, C., O'Reilly, R. C., & Anderson, J. R. (2008).** SAL: An explicitly pluralistic cognitive architecture. *Journal of Experimental and Theoretical Artificial Intelligence*, 20, 197–218.
- **Joanisse, M. F., & Seidenberg, M. S. (1999).** Impairments in verb morphology after brain injury: A connectionist model. *Proceedings of the National Academy of Sciences of the USA*, 96, 7592–7597.
- **Kemp, C., & Tenenbaum, J. B. (2008).** Structured models of semantic cognition. *Behavioral and Brain Sciences*, 31, 717–718.
- **Kurzweil, R. (2005).** *The Singularity Is Near: When Humans Transcend Biology.* New York: Viking Penguin.
- **Landauer, T. K., & Dumais, S. T. (1997).** A solution to Plato’s problem: The latent semantic analysis theory of acquisition, induction and representation of knowledge. *Psychological Review*, 104, 211–240.
- **Marr, D. (1982).** *Vision: A Computational Investigation into the Human Representation and Processing of Visual Information.* San Francisco: Freeman.
- **Massaro, D. W. (1989).** Testing between the TRACE model and the fuzzy logical model of speech perception. *Cognitive Psychology*, 21, 398–421.
- **McClelland, J. L. (1979).** On the time relations of mental processes: An examination of systems of processes in cascade. *Psychological Review*, 86, 287–330.
- **McClelland, J. L., & Rumelhart, D. E. (1981).** An interactive activation model of context effects in letter perception: Part 1. An account of basic findings. *Psychological Review*, 88, 375–407.
- **McClelland, J. L., McNaughton, B. L., & O'Reilly, R. C. (1995).** Why there are complementary learning systems in the hippocampus and neocortex: Insights from the successes and failures of connectionist models of learning and memory. *Psychological Review*, 102, 419–457.


<!-- ======================================================================= -->
<!-- PAGE 27                                                                 -->
<!-- ======================================================================= -->

### Références Bibliographiques (Partie 4 : N–R)

- **McCulloch, W. S., & Pitts, W. (1943).** A logical calculus of the ideas immanent in nervous activity. *Bulletin of Mathematical Biophysics*, 5, 115–133.
- **Neisser, U. (1967).** *Cognitive Psychology.* New York: Appleton-Century-Crofts.
- **Newell, A. (1973).** You can’t play 20 questions with nature and win: Projective comments on the papers of this symposium. In W. G. Chase (Ed.), *Visual Information Processing* (pp. 283–308). New York: Academic Press.
- **Newell, A. (1990).** *Unified Theories of Cognition.* Cambridge, MA: Harvard University Press.
- **Newell, A., & Simon, H. A. (1956).** The logic theory machine: A complex information processing system. *IRE Transactions on Information Theory*, 2(3), 61–79.
- **Newell, A., & Simon, H. A. (1976).** Computer science as empirical inquiry: Symbols and search. *Communications of the ACM*, 19(3), 113–126.
- **Oaksford, M., & Chater, N. (1996).** Rational explanation of the selection task. *Psychological Review*, 103, 381–391.
- **Pinker, S., & Prince, A. (1988).** On language and connectionism: Analysis of a parallel distributed processing model of language acquisition. *Cognition*, 28, 73–193.
- **Plaut, D. C., McClelland, J. L., Seidenberg, M. S., & Patterson, K. (1996).** Understanding normal and impaired word reading: Computational principles in quasi-regular domains. *Psychological Review*, 103, 56–115.
- **Popper, K. R. (1959).** *The Logic of Scientific Discovery.* London: Hutchinson.
- **Roberts, S., & Sternberg, S. (1993).** The meaning of additive reaction-time effects: Tests of three alternatives. In D. E. Meyer & S. Kornblum (Eds.), *Attention and Performance XIV* (pp. 611–653). Cambridge, MA: MIT Press.
- **Rogers, T. T., & McClelland, J. L. (2004).** *Semantic Cognition: A Parallel Distributed Processing Approach.* Cambridge, MA: MIT Press.
- **Rosenblatt, F. (1958).** The perceptron: A probabilistic model for information storage and organization in the brain. *Psychological Review*, 65, 386–408.
- **Rumelhart, D. E., & McClelland, J. L. (1982).** An interactive activation model of context effects in letter perception: Part 2. The contextual enhancement effect and some tests and extensions of the model. *Psychological Review*, 89, 60–94.
- **Rumelhart, D. E., & McClelland, J. L. (1986).** On learning the past tenses of English verbs. In J. L. McClelland, D. E. Rumelhart, & the PDP Research Group (Eds.), *Parallel Distributed Processing: Explorations in the Microstructure of Cognition*, Vol. 2 (pp. 216–271). Cambridge, MA: MIT Press.


<!-- ======================================================================= -->
<!-- PAGE 28                                                                 -->
<!-- ======================================================================= -->

### Références Bibliographiques (Partie 5 : S–Z)

- **Schöner, G. (2008).** Dynamical systems approaches to cognition. In R. Sun (Ed.), *Cambridge Handbook of Computational Psychology* (pp. 101–126). New York: Cambridge University Press.
- **Seidenberg, M. S., & McClelland, J. L. (1989).** A distributed, developmental model of word recognition and naming. *Psychological Review*, 96, 523–568.
- **Shepard, R. N. (1987).** Toward a universal law of generalization for physical and psychological science. *Science*, 237, 1317–1323.
- **Simon, H. A. (1957).** *Models of Man: Social and Rational.* New York: Wiley.
- **Simon, H. A. (1991).** *Models of My Life.* New York: Basic Books.
- **Smolensky, P. (1988).** On the proper treatment of connectionism. *Behavioral and Brain Sciences*, 11, 1–74.
- **Spencer, J. P., Thomas, M. S. C., & McClelland, J. L. (Eds.) (2009).** *Toward a New Grand Theory of Development: Connectionism and Dynamical Systems Theory Re-considered.* Oxford: Oxford University Press.
- **Steels, L. (2007).** The recruitment bias in language evolution. *Language Learning and Development*, 3, 129–152.
- **Sternberg, S. (1969).** The discovery of processing stages: Extensions of Donders’ method. *Acta Psychologica*, 30, 276–315.
- **Sun, R. (2002).** *Duality of the Mind: A Bottom-up Approach Toward Cognition.* Mahwah, NJ: Erlbaum.
- **Sun, R. (Ed.) (2008).** *The Cambridge Handbook of Computational Psychology.* New York: Cambridge University Press.
- **Taatgen, N. A., & Anderson, J. R. (2008).** Constraints in cognitive architectures. In R. Sun (Ed.), *Cambridge Handbook of Computational Psychology* (pp. 170–185). New York: Cambridge University Press.
- **Thelen, E., & Smith, L. B. (1994).** *A Dynamic Systems Approach to the Development of Cognition and Action.* Cambridge, MA: MIT Press.
- **Thelen, E., Schöner, G., Scheier, C., & Smith, L. B. (2001).** The dynamics of embodiment: A field theory of infant perseverative reaching. *Behavioral and Brain Sciences*, 24, 1–86.
- **Usher, M., & McClelland, J. L. (2001).** The time course of perceptual choice: The leaky, competing accumulator model. *Psychological Review*, 108, 550–592.
- **Vallabha, G. K., McClelland, J. L., Pons, F., Werker, J. F., & Amano, S. (2007).** Unsupervised learning of vowel categories from infant-directed speech. *Proceedings of the National Academy of Sciences of the USA*, 104, 13273–13278.
- **Wason, P. C. (1966).** Reasoning. In B. M. Foss (Ed.), *New Horizons in Psychology* (pp. 135–151). Harmondsworth: Penguin.
- **Xu, F., & Tenenbaum, J. B. (2007).** Word learning as Bayesian inference. *Psychological Review*, 114, 245–272.


