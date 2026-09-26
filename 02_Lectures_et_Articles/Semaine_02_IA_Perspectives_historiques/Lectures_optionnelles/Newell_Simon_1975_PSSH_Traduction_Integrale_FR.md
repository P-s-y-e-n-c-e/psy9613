# L'informatique comme enquête empirique : symboles et recherche

**Titre original :** *Computer Science as Empirical Inquiry: Symbols and Search*  
**Auteurs :** Allen Newell & Herbert A. Simon  
**Institution :** Carnegie-Mellon University, Pittsburgh, Pennsylvanie  
**Événement :** Conférence du Prix Turing de l'ACM 1975 (*1975 ACM Turing Award Lecture*), prononcée le 20 octobre 1975 à Minneapolis  
**Publication officielle :** *Communications of the ACM* (Mars 1976), Volume 19, Numéro 3, pages 113–126  
**DOI :** [10.1145/360018.360022](https://doi.org/10.1145/360018.360022)  
**Traduction académique :** Module officiel de traduction académique — PSY9613 (*Perception, cognition et IA*, UQAM)

---

### Résumé (*Abstract*)

L'informatique est une discipline empirique qui étudie les phénomènes émergeant autour des ordinateurs. À l'instar d'autres sciences naturelles comme la biologie cellulaire ou la géologie, elle progresse par la formulation et la mise à l'épreuve expérimentale de **lois de structure qualitative**. Deux de ces lois fondamentales, issues de vingt années de recherches à l'intersection de l'intelligence artificielle et de la psychologie cognitive, sont exposées et analysées :

1. **L'Hypothèse du Système de Symboles Physiques (PSSH) :** Un système de symboles physiques possède les moyens nécessaires et suffisants pour l'action intelligente générale. Cette hypothèse postule que l'esprit humain tout comme l'ordinateur universel tirent leur faculté d'adaptation intelligente de la manipulation physique de structures de motifs désignatifs et interprétables.
2. **L'Hypothèse de la Recherche Heuristique :** Les systèmes de symboles physiques résolvent des problèmes en générant et en testant progressivement des structures de symboles au sein d'un espace de problème, c'est-à-dire par la recherche heuristique. Face au spectre de l'explosion combinatoire ($B^D$), l'intelligence ne se mesure pas au volume brut d'exploration, mais à la capacité d'élaguer drastiquement les ramifications grâce à la sélectivité du générateur, à l'analyse moyens-fins et à l'extraction de connaissances sémantiques.

Les implications épistémologiques pour la psychologie cognitive (démontrant la nécessité du système symbolique chez l'humain) et pour l'intelligence artificielle (démontrant sa suffisance opérationnelle) sont minutieusement articulées.

**Mots-clés :** système de symboles physiques, recherche heuristique, PSSH, analyse moyens-fins, espaces de problèmes, explosion combinatoire, désignation, interprétation, traitement de listes, psychologie cognitive, prix Turing.

---
<!-- ======================================================================= -->
<!-- PAGE 1                                                                  -->
<!-- ======================================================================= -->

### Conférence du Prix Turing ACM 1975

Le Prix Turing de l'ACM pour l'année 1975 a été décerné conjointement à **Allen Newell** et **Herbert A. Simon** lors de la Conférence annuelle de l'ACM à Minneapolis, le 20 octobre. En présentant les lauréats, Bernard A. Galler, président du comité du Prix Turing, a donné lecture de l'éloge officiel suivant :

> « C'est un privilège de pouvoir décerner le Prix Turing de l'ACM à deux amis de longue date, les professeurs Allen Newell et Herbert A. Simon, tous deux de l'Université Carnegie-Mellon.
> 
> Dans des efforts scientifiques conjoints s'étendant sur plus de vingt années — initialement en collaboration avec J.C. Shaw à la RAND Corporation, puis avec de nombreux collègues professeurs et étudiants à l'Université Carnegie-Mellon —, ils ont apporté des contributions fondamentales à l'intelligence artificielle, à la psychologie de la cognition humaine et au traitement de listes.
> 
> En **intelligence artificielle**, ils ont contribué à établir ce domaine comme un champ de recherche scientifique légitime, au développement de la programmation heuristique en général, et plus particulièrement de la recherche heuristique, de l'analyse moyens-fins et des méthodes d'induction ; apportant des démonstrations rigoureuses de la suffisance de ces mécanismes pour résoudre des problèmes complexes et stimulants.
> 
> En **psychologie**, ils ont été les principaux instigateurs de l'idée selon laquelle la cognition humaine peut être décrite en termes de système de symboles, et ils ont développé des théories détaillées de la résolution de problèmes chez l'humain, de l'apprentissage verbal et du comportement inductif dans plusieurs domaines de tâches, en utilisant des programmes informatiques incarnant ces théories pour simuler le comportement humain.
> 
> Ils ont été, selon toute apparence, les inventeurs du **traitement de listes**, et ont contribué de manière majeure à la fois à la technologie logicielle et au développement du concept de l'ordinateur comme un système de manipulation de structures symboliques, et non pas simplement comme un processeur de données numériques.
> 
> C'est un honneur pour les professeurs Newell et Simon de recevoir ce prix, mais c'est aussi un honneur pour l'ACM de pouvoir ajouter leurs noms à notre liste de récipiendaires, car par leur présence, ils rehaussent le prestige et l'importance du Prix Turing de l'ACM. »

---

# L'informatique comme enquête empirique : symboles et recherche
**Allen Newell & Herbert A. Simon**  
*Carnegie-Mellon University, Pittsburgh, Pennsylvanie*

L'informatique est l'étude des phénomènes qui entourent les ordinateurs. Les fondateurs de notre société savante l'ont fort bien compris lorsqu'ils se sont baptisés l'**Association for Computing Machinery** (ACM). La machine — non pas simplement le matériel physique (*hardware*), mais la machine programmée, vivante — est l'organisme même que nous étudions.

Il s'agit ici de la dixième conférence Turing. Les neuf personnes qui nous ont précédés à cette tribune ont présenté neuf visions différentes de l'informatique. Car notre organisme, la machine, peut être étudié à de multiples niveaux et sous de multiples facettes. Nous sommes profondément honorés d'être parmi vous aujourd'hui pour présenter une perspective supplémentaire, celle-là même qui a imprégné l'ensemble des travaux scientifiques pour lesquels nous sommes honorés. Nous souhaitons parler de l'informatique comme d'une **enquête empirique** (*empirical inquiry*).


<!-- ======================================================================= -->
<!-- PAGE 2                                                                  -->
<!-- ======================================================================= -->

Notre vision n'en est qu'une parmi d'autres ; les conférences précédentes l'ont amplement démontré. Toutefois, même prises dans leur ensemble, ces conférences ne parviennent pas à couvrir toute l'étendue de notre science. De nombreux aspects fondamentaux n'ont pas encore été représentés dans ces dix récompenses. Et si le moment arrive jamais — certainement pas de sitôt — où la rose des vents aura été complètement parcourue, où l'informatique aura été discutée sous toutes ses coutures, il sera temps de recommencer le cycle. Car le conférencier, tel le lièvre, devra effectuer un sprint annuel pour rattraper l'accumulation de petits gains progressifs que la tortue du développement scientifique et technique aura accomplis dans sa marche régulière. Chaque année créera un nouvel écart et exigera un nouveau sprint, car en science, il n'y a jamais de dernier mot.

L'informatique est une discipline empirique. Nous l'aurions volontiers qualifiée de science expérimentale, mais, à l'instar de l'astronomie, de l'économie et de la géologie, certaines de ses formes uniques d'observation et d'expérience ne cadrent pas avec le stéréotype étroit de la méthode expérimentale. Il n'en demeure pas moins qu'il s'agit bel et bien d'expériences. Chaque nouvelle machine construite est une expérience. Construire effectivement la machine revient à poser une question à la nature ; et nous écoutons la réponse en observant la machine en fonctionnement et en l'analysant par tous les moyens d'analyse et de mesure disponibles. Chaque nouveau programme conçu est une expérience. Il pose une question à la nature, et son comportement offre des indices pour une réponse. 

Ni les machines ni les programmes ne sont des boîtes noires ; ce sont des artefacts qui ont été conçus, tant sur le plan matériel que logiciel, et nous pouvons les ouvrir pour regarder à l'intérieur. Nous pouvons relier leur structure à leur comportement et tirer de multiples leçons d'une seule et unique expérience. Nous n'avons pas besoin de fabriquer 100 exemplaires, disons, d'un démonstrateur de théorèmes, pour prouver statistiquement qu'il n'a pas surmonté l'explosion combinatoire de la recherche de la manière espérée. L'inspection du programme à la lumière de quelques exécutions révèle la faille et nous permet de passer à la tentative suivante.

Nous construisons des ordinateurs et des programmes pour de nombreuses raisons. Nous les construisons pour servir la société et comme outils destinés à accomplir les tâches économiques de la société. Mais en tant que chercheurs en science fondamentale, nous construisons des machines et des programmes comme un moyen de découvrir de nouveaux phénomènes et d'analyser des phénomènes que nous connaissons déjà. La société se méprend souvent à ce sujet, croyant que les ordinateurs et les programmes ne doivent être construits que pour l'usage économique immédiat qui peut en être fait (ou comme étapes intermédiaires vers un tel usage). Elle doit comprendre que les phénomènes entourant les ordinateurs sont profonds et obscurs, exigeant une intense expérimentation pour évaluer leur nature. Elle doit comprendre que, comme dans toute science, les gains issus de cette expérimentation et de cette compréhension se traduisent par l'acquisition permanente de nouvelles techniques ; et que ce sont ces techniques qui créeront les instruments capables d'aider la société à atteindre ses buts.

Notre propos ici n'est toutefois pas de plaider pour la compréhension du monde extérieur. Il s'agit d'examiner un aspect de notre science : le développement d'une nouvelle compréhension fondamentale par l'enquête empirique. La meilleure façon d'y parvenir est de recourir à des illustrations. On nous pardonnera si, profitant de l'occasion, nous choisissons nos exemples dans le champ de nos propres recherches. Comme cela deviendra évident, ces exemples englobent tout le développement de l'intelligence artificielle, particulièrement dans ses premières années. Ils reposent sur bien plus que nos seules contributions personnelles. Et même là où nous avons apporté des contributions directes, cela s'est fait en coopération avec d'autres. Nos collaborateurs ont notamment inclus Cliff Shaw, avec qui nous avons formé une équipe de trois durant la période stimulante de la fin des années cinquante. Mais nous avons également collaboré avec un grand nombre de collègues et d'étudiants à l'Université Carnegie-Mellon.

Le temps imparti ne nous permet d'aborder que deux exemples. Le premier est le développement de la notion de **système symbolique**. Le second est le développement de la notion de **recherche heuristique**. Ces deux conceptions revêtent une signification profonde pour comprendre comment l'information est traitée et comment l'intelligence est réalisée. Elles sont pourtant loin d'épuiser l'ensemble de l'intelligence artificielle, bien qu'elles nous paraissent exemplaires pour exposer la nature des connaissances fondamentales dans cette branche de l'informatique.

---

## I. Symboles et systèmes de symboles physiques

L'une des contributions fondamentales de l'informatique à la connaissance a été d'expliquer, à un niveau très fondamental, ce que sont les symboles. Cette explication constitue une proposition scientifique portant sur la Nature. Elle est dérivée empiriquement, au terme d'un développement long et graduel.

Les symboles se situent au fondement même de l'action intelligente, qui constitue, bien entendu, l'objet d'étude premier de l'intelligence artificielle. C'est d'ailleurs une question fondamentale pour l'ensemble de l'informatique. Car toute information est traitée par les ordinateurs au service de finalités déterminées, et nous mesurons l'intelligence d'un système à sa capacité à atteindre les buts fixés en dépit des variations, des difficultés et des complexités posées par l'environnement de la tâche. Cet investissement général de l'informatique dans la réalisation de l'intelligence est parfois masqué lorsque les tâches accomplies sont de portée limitée, car les variations de l'environnement peuvent alors être anticipées avec exactitude. Mais cela devient éclatant dès que nous étendons les ordinateurs à des tâches plus globales, complexes et riches en connaissances — lorsque nous tentons d'en faire nos agents, capables de gérer par eux-mêmes l'ensemble des contingences du monde naturel.


<!-- ======================================================================= -->
<!-- PAGE 3                                                                  -->
<!-- ======================================================================= -->

Notre compréhension des exigences systémiques requises pour l'action intelligente n'émerge que lentement. Elle est composite, car aucun élément simple et isolé ne saurait rendre compte de l'intelligence dans toutes ses manifestations. Il n'existe aucun « principe d'intelligence » universel, tout comme il n'existe aucun « principe vital » qui conférerait par sa nature même l'essence de la vie. Mais l'absence d'un *deus ex machina* simpliste n'implique nullement qu'il n'existe aucune exigence structurelle pour l'intelligence. L'une de ces exigences réside dans la capacité à stocker et à manipuler des symboles. Pour formuler la question scientifique, nous pourrions paraphraser le titre d'un célèbre article de Warren McCulloch [1961] : *Qu'est-ce qu'un symbole, pour que l'intelligence puisse en faire usage, et qu'est-ce que l'intelligence, pour qu'elle puisse faire usage d'un symbole ?*

### Lois de structure qualitative

Toutes les sciences caractérisent la nature essentielle des systèmes qu'elles étudient. Ces caractérisations sont invariablement de nature **qualitative**, car elles établissent les termes conceptuels au sein desquels des connaissances plus détaillées peuvent être développées. Leur essence peut souvent être résumée dans des énoncés très courts et très généraux. On pourrait juger que ces lois générales, en raison de leur spécificité restreinte, apportent une contribution modeste à l'ensemble d'une science, n'était la preuve historique qui démontre qu'elles constituent en réalité des découvertes de la plus haute importance.

**La doctrine cellulaire en biologie.** Un excellent exemple de loi de structure qualitative est la doctrine cellulaire en biologie, qui affirme que l'unité constitutive fondamentale de tous les organismes vivants est la **cellule**. Les cellules se présentent sous une grande diversité de formes, bien qu'elles possèdent toutes un noyau entouré de cytoplasme, le tout enveloppé d'une membrane. Mais cette structure interne ne faisait pas partie, historiquement, de la formulation initiale de la doctrine cellulaire ; il s'agissait d'une spécification ultérieure mise au jour par des investigations approfondies. La doctrine cellulaire peut être transmise presque entièrement par l'énoncé que nous venons de formuler, assorti de quelques notions vagues sur la taille qu'une cellule peut avoir. L'impact de cette loi sur la biologie a pourtant été prodigieux, et le temps perdu dans cette discipline avant son acceptation graduelle fut considérable.

**La tectonique des plaques en géologie.** La géologie fournit un exemple fascinant de loi de structure qualitative, fascinant parce qu'elle n'a été acceptée qu'au cours de la dernière décennie et que son accession au rang de paradigme établi est encore fraîche dans nos mémoires. La théorie de la tectonique des plaques affirme que la surface du globe est une mosaïque de plaques gigantesques — quelques dizaines en tout — qui se déplacent (à des vitesses géologiques) les unes contre les autres, les unes par-dessus et par-dessous les autres, s'enfonçant vers le centre de la Terre où elles perdent leur identité. Les mouvements de ces plaques rendent compte de la configuration et de l'emplacement relatif des continents et des océans, des zones d'activité volcanique et sismique, des dorsales océaniques profondes, et ainsi de suite. Avec quelques détails supplémentaires sur la vitesse et la taille, l'essentiel de la théorie se trouve formulé. Elle ne fut naturellement acceptée que lorsqu'elle parvint à expliquer un faisceau de détails empiriques cohérents (par exemple la concordance de la flore, de la faune et de la stratification géologique entre l'Afrique de l'Ouest et le nord-est de l'Amérique du Sud). La tectonique des plaques est une théorie éminemment qualitative. Maintenant qu'elle est admise, la Terre entière semble en offrir des preuves manifestes partout, car nous voyons désormais le monde à travers ses termes.

**La théorie des germes des maladies.** Il y a un peu plus d'un siècle, Louis Pasteur énonçait la théorie des germes pathogènes, une loi de structure qualitative qui a révolutionné la médecine. Cette théorie propose que la majorité des maladies infectieuses sont causées par la présence et la multiplication dans l'organisme de minuscules êtres vivants unicellulaires, et que la contagion consiste en la transmission de ces organismes d'un hôte à un autre. Une part considérable du travail d'élaboration de la théorie a consisté à identifier les organismes associés à des maladies spécifiques, à les décrire et à retracer leurs cycles de vie. Le fait que cette loi souffre de nombreuses exceptions — que beaucoup de maladies ne soient pas causées par des germes — ne retire rien à son importance capitale. La loi nous intime de chercher un type particulier de cause ; elle ne garantit pas que nous le trouverons toujours.

**La doctrine de l'atomisme.** La doctrine de l'atomisme offre un contraste saisissant avec les trois lois qualitatives que nous venons de décrire. Telle qu'elle est issue des travaux de Dalton et de ses démonstrations démontrant que les composés chimiques se combinent selon des proportions fixes, la loi offrait un exemple typique de structure qualitative : les éléments chimiques sont composés de petites particules uniformes, distinctes d'un élément à l'autre. Mais parce que les espèces atomiques sous-jacentes sont simples et en nombre limité, des théories quantitatives furent rapidement formulées, assimilant toute la structure générale présente dans l'hypothèse qualitative originelle. Avec les cellules, les plaques tectoniques et les germes, la variété des structures est si phénoménale que le principe qualitatif sous-jacent demeure distinct, et sa contribution à la théorie globale reste nettement discernable.


<!-- ======================================================================= -->
<!-- PAGE 4                                                                  -->
<!-- ======================================================================= -->

**Conclusion.** Les lois de structure qualitative se rencontrent partout en science. Certaines de nos plus grandes découvertes scientifiques comptent parmi elles. Comme l'illustrent ces exemples, elles établissent souvent les conditions mêmes dans lesquelles opère une science tout entière.

### Systèmes de symboles physiques

Revenons maintenant à la question des symboles, et définissons ce qu'est un **système de symboles physiques** (*physical symbol system*). L'adjectif « physique » dénote deux caractéristiques fondamentales :
1. De tels systèmes obéissent manifestement aux lois de la physique — ils sont matériellement réalisables par des systèmes d'ingénierie constitués de composants matériels ;
2. Bien que notre usage du mot « symbole » préfigure l'interprétation que nous entendons lui donner, il ne se restreint nullement aux seuls systèmes de symboles humains.

Un **système de symboles physiques** consiste en un ensemble d'entités, appelées **symboles**, qui sont des motifs physiques (*physical patterns*) pouvant apparaître comme composants d'un autre type d'entité appelé une **expression** (ou structure de symboles). Ainsi, une structure de symboles est composée d'un ensemble d'occurrences (*tokens*) de symboles reliées d'une certaine façon physique (par exemple, une occurrence étant contiguë à une autre). À tout instant, le système contient une collection de ces structures de symboles. 

Outre ces structures, le système comprend également une collection de **processus** qui opèrent sur les expressions pour produire d'autres expressions : processus de *création*, de *modification*, de *reproduction* et de *destruction*. Un système de symboles physiques est une machine qui produit au fil du temps une collection évolutive de structures symboliques. Un tel système s'insère dans un monde d'objets bien plus vaste que ces seules expressions symboliques elles-mêmes.

Deux notions sont centrales à cette architecture d'expressions, de symboles et d'objets : **la désignation** et **l'interprétation**.

> **Désignation :** Une expression **désigne** un objet si, étant donné l'expression, le système peut soit affecter l'objet lui-même, soit se comporter de manière dépendante de cet objet. Dans un cas comme dans l'autre, un accès à l'objet via l'expression a été obtenu, ce qui constitue l'essence même de la désignation.
> 
> **Interprétation :** Le système peut **interpréter** une expression si l'expression désigne un processus et si, étant donné l'expression, le système peut exécuter ce processus. L'interprétation implique une forme particulière d'action dépendante : étant donné une expression, le système peut exécuter le processus indiqué, c'est-à-dire qu'il peut évoquer et exécuter ses propres processus à partir des expressions qui les désignent.

Un système capable de désignation et d'interprétation, au sens que nous venons d'indiquer, doit également satisfaire un ensemble d'exigences complémentaires de complétude et de clôture :
1. Un symbole peut être employé pour désigner n'importe quelle expression concevable (arbitraire du symbole atomique).
2. Il existe des expressions qui désignent chaque processus dont la machine est capable.
3. Il existe des processus pour créer toute expression et pour modifier toute expression de façon arbitraire.
4. Les expressions sont stables dans le temps : une fois créées, elles subsistent jusqu'à ce qu'elles soient explicitement modifiées ou effacées.
5. Le nombre d'expressions que le système peut emmagasiner est virtuellement illimité.

Le type de système que nous venons de définir n'est pas inconnu des informaticiens. Il présente un air de famille frappant avec l'ensemble des ordinateurs universels. Si l'on considère un langage de manipulation de symboles, tel que **LISP**, comme définissant une machine abstraite, la parenté devient littéralement fraternelle. Notre intention en exposant un tel système n'est pas de proposer quelque chose de radicalement inédit, mais bien au contraire d'exposer ce qui est désormais connu et théorisé au sujet des systèmes qui satisfont une telle caractérisation.

Nous pouvons maintenant énoncer une hypothèse scientifique générale — une loi de structure qualitative pour les systèmes de symboles :

> ### L'Hypothèse du Système de Symboles Physiques (PSSH)
> **Un système de symboles physiques possède les moyens nécessaires et suffisants pour l'action intelligente générale.**
> 
> *(The Physical Symbol System Hypothesis. A physical symbol system has the necessary and sufficient means for general intelligent action.)*

Par **« nécessaire »**, nous entendons que tout système manifestant une intelligence générale s'avérera, à l'analyse, être un système de symboles physiques.  
Par **« suffisant »**, nous entendons que tout système de symboles physiques de taille appropriée peut être organisé de manière à exhiber une intelligence générale.  
Par **« action intelligente générale »**, nous désignons la même étendue et portée d'intelligence que celle observée dans l'action humaine : à savoir que dans toute situation réelle, un comportement adapté aux finalités du système et adaptable aux exigences de l'environnement peut être produit, dans certaines limites de vitesse et de complexité.

L'hypothèse du système de symboles physiques constitue sans équivoque une loi de structure qualitative. Elle délimite une vaste classe générale de systèmes au sein de laquelle on trouvera ceux qui sont capables d'action intelligente.

Il s'agit d'une **hypothèse empirique**. Nous avons défini une classe de systèmes physiques ; nous posons la question de savoir si cette classe rend compte d'un ensemble de phénomènes réels observés dans le monde naturel. L'action intelligente nous entoure partout dans le monde biologique, principalement dans le comportement humain. C'est une forme de comportement que nous reconnaissons à ses effets, qu'il soit produit par des humains ou non. L'hypothèse pourrait fort bien s'avérer fausse. Le comportement intelligent n'est pas si aisé à produire pour que n'importe quel système l'exhibe spontanément. En réalité, certains chercheurs concluent, sur des bases philosophiques ou scientifiques, que l'hypothèse est erronée. Scientifiquement, on ne peut l'attaquer ou la défendre qu'en apportant des preuves empiriques issues de l'observation du monde naturel.


<!-- ======================================================================= -->
<!-- PAGE 5                                                                  -->
<!-- ======================================================================= -->

Il nous faut maintenant retracer le développement de cette hypothèse et examiner les preuves empiriques qui militent en sa faveur.

### Développement de l'hypothèse du système de symboles

Un système de symboles physiques est une instanciation d'une **machine universelle**. Ainsi, l'hypothèse du système de symboles implique que l'intelligence sera réalisée par un calculateur universel. Toutefois, l'hypothèse va bien au-delà de l'argument classique — souvent avancé au nom d'un déterminisme physique général — selon lequel tout calcul physiquement réalisable peut être accompli par une machine universelle, pourvu qu'il soit formellement spécifié. Car elle affirme très précisément que **la machine intelligente est un système de symboles**, formulant ainsi une proposition architecturale précise sur la nature intime des systèmes intelligents. Il importe de comprendre comment cette spécification structurelle s'est progressivement dégagée.

**La logique formelle.** Les racines de l'hypothèse remontent au programme d'axiomatisation de Frege, ainsi que de Whitehead et Russell, visant à formaliser la logique : capturer les notions mathématiques fondamentales au sein de la logique et asseoir les concepts de preuve et de déduction sur un socle rigoureux. Cet effort a culminé dans la logique mathématique moderne — notre calcul des propositions, ainsi que les logiques du premier ordre et d'ordres supérieurs. Il en est résulté une vision caractéristique, souvent qualifiée de **« jeu de symboles »** (*symbol game*). La logique, et par extension l'ensemble des mathématiques, était conçue comme un jeu opéré sur des jetons dépourvus de signification intrinsèque, selon des règles purement syntaxiques. Toute sémantique en avait été purgée. On disposait d'un système mécanique, bien que permissif (nous dirions aujourd'hui non déterministe), au sein duquel diverses propriétés pouvaient être formellement démontrées.

Ainsi, les premiers progrès ont été accomplis en prenant délibérément congé de tout ce qui semblait relever de la signification et des symboles humains. Nous pourrions qualifier cette phase d'**étape de la manipulation formelle de symboles**.

Cette posture générale s'est fidèlement reflétée dans l'essor de la théorie de l'information. On a maintes et maintes fois rappelé que Shannon avait défini un cadre mathématique purement technique, utile exclusivement pour la communication et la sélection de signaux, et qui ne possédait aucun lien avec le sens ou la signification. Des regrets furent même exprimés quant au choix d'un vocable aussi large que « théorie de l'information », et des tentatives eurent lieu pour la rebaptiser « théorie de l'information sélective » — sans succès, bien entendu.

<span id="anchor_seance_02_q35_fr" class="doc-anchor-target"></span>
**Les machines de Turing et l'ordinateur numérique.** Le développement des premiers ordinateurs numériques et de la théorie des automates, inauguré par les travaux pionniers d'Alan Turing dans les années 1930, peut être envisagé conjointement. Ces deux courants s'accordent sur ce qui est essentiel. Utilisons le modèle original de Turing, car il en expose parfaitement les principes cardinaux.

Une machine de Turing se compose de deux mémoires : un **ruban infini** (*unbounded tape*) et une **unité de contrôle à états finis** (*finite state control*). Le ruban contient les données, à savoir les fameux zéros et uns. La machine ne possède qu'un répertoire extrêmement restreint d'opérations élémentaires : des opérations de lecture, d'écriture et de déplacement sur le ruban. L'opération de lecture n'est pas une manipulation de données en soi, mais déclenche un branchement conditionnel vers un état de contrôle interne en fonction du symbole présent sous la tête de lecture. Comme nous le savons tous, ce modèle contient les éléments essentiels de tous les ordinateurs concevables quant à leurs capacités de calcul, même si d'autres ordinateurs dotés de mémoires et d'instructions différentes peuvent exécuter les mêmes computations avec des contraintes d'espace et de temps distinctes. En particulier, le modèle de la machine de Turing contient en son sein tant la notion de ce qui ne peut pas être calculé (l'indécidabilité) que celle de **machine universelle** — des ordinateurs capables d'exécuter n'importe quel calcul pouvant être accompli par n'importe quelle machine spécialisée.

Nous devrions nous émerveiller de ce que deux de nos intuitions les plus profondes sur le traitement de l'information aient été conquises dans les années trente, bien avant l'avènement des ordinateurs électroniques modernes. C'est un hommage éclatant au génie d'Alan Turing. C'est également un tribut au développement de la logique mathématique de cette époque, et le témoignage de l'immense dette contractée par l'informatique envers elle. Concomitamment aux travaux de Turing apparurent ceux des logiciens Emil Post et (indépendamment) Alonzo Church. Partant de conceptions distinctes de systèmes logistiques (respectivement les systèmes de production de Post et le lambda-calcul / fonctions récursives de Church), ils aboutirent à des résultats rigoureusement analogues quant à l'indécidabilité et à l'universalité — résultats dont l'équivalence formelle fut rapidement démontrée. La convergence de toutes ces tentatives indépendantes visant à définir la classe la plus générale de systèmes de traitement de l'information fonde notre conviction inébranlable que ces modèles capturent l'essence même du calcul.

Pourtant, dans aucun de ces systèmes initiaux n'apparaissait en surface le concept de symbole comme entité assurant une **désignation**. Les données étaient simplement conçues comme des chaînes inertes de zéros et de uns — de fait, l'inertie des données était indispensable pour réduire le calcul à un processus strictement mécanique et physique. Le contrôle à états finis était invariablement pensé comme un petit automate rigide, et des jeux logiques étaient disputés pour réduire au minimum le nombre d'états sans détruire l'universalité de la machine. À cette époque, personne ne songeait à ajouter dynamiquement de nouveaux états au contrôle interne, ni à concevoir la mémoire de contrôle comme le réceptacle de la vaste majorité des connaissances du système. Ce qui fut accompli à cette étape représentait **la première moitié du principe d'interprétation** : démontrer qu'une machine peut être pilotée à partir d'une description textuelle formelle. C'est l'**étape de la manipulation automatique formelle de symboles**.

**Le concept de programme enregistré.** Avec l'avènement de la deuxième génération de machines électroniques au milieu des années quarante (après l'ENIAC) émergea le **concept de programme enregistré en mémoire** (*stored program concept*). Cela fut à juste titre salué comme une révolution, tant conceptuelle que pratique. Les programmes devenaient désormais des **données**, et pouvaient être manipulés en tant que données. Cette capacité était, certes, déjà implicite dans le modèle théorique de Turing, où la table d'instructions résidait sur le même ruban que les données de calcul. Pourtant, l'idée ne put être concrétisée qu'au moment où les machines acquirent une mémoire interne suffisante pour héberger de véritables programmes. Rappelons qu'après tout, l'ENIAC ne possédait que vingt registres électroniques.


<!-- ======================================================================= -->
<!-- PAGE 6                                                                  -->
<!-- ======================================================================= -->

Le concept de programme enregistré incarne la **seconde moitié du principe d'interprétation**, celle qui stipule que les données propres du système peuvent être interprétées comme du code exécutable. Cependant, il ne contient pas encore la notion de **désignation** — cette relation physique singulière qui sous-tend la signification et le renvoi sémantique.

**Le traitement de listes.** Le pas suivant, franchi en 1956, fut le **traitement de listes** (*list processing*). Le contenu des structures de données était désormais constitué de **symboles**, au sens exact de notre système de symboles physiques : des motifs qui désignaient, qui possédaient des référents. Les listes contenaient des adresses mémoires qui donnaient un accès physique direct à d'autres listes — engendrant ainsi la notion de **structures de listes**. 

Qu'il s'agissait là d'une conception profondément neuve nous fut prouvé à maintes reprises aux débuts du traitement de listes, lorsque des collègues nous demandaient avec insistance où se trouvaient les véritables données — c'est-à-dire quelle liste contenait finalement les paquets de bits qui constituaient le contenu intrinsèque du système. Ils trouvaient déconcertant qu'il n'y eût point de tels bits ultimes, mais seulement des symboles désignant indéfiniment d'autres structures de symboles.

Le traitement de listes représente simultanément trois percées majeures dans l'histoire de l'informatique :
1. **Une mémoire véritablement dynamique :** Il crée une structure de mémoire dynamique au sein d'une machine qui avait été jusqu'alors perçue comme un ensemble rigide de cases fixes. Il ajouta à notre répertoire d'opérations celles qui construisent et modifient la structure elle-même, en plus de celles qui se contentent de remplacer ou de modifier des valeurs locales.
2. **L'abstraction des types de données :** Il démontra très tôt l'abstraction fondamentale selon laquelle un ordinateur est constitué d'un ensemble de types de données et d'un ensemble d'opérations propres à ces types, de sorte qu'un système computationnel peut employer les types de données appropriés à son application, indépendamment de la machine matérielle sous-jacente.
3. **Un modèle physique de la désignation :** Le traitement de listes a produit un modèle opérationnel de la désignation, définissant la manipulation de symboles au sens précis où nous l'entendons aujourd'hui en informatique.

Comme cela arrive souvent, la pratique technique de l'époque avait déjà anticipé certains aspects du traitement de listes : les adresses étaient couramment utilisées pour pointer des données, et les ordinateurs à tambour magnétique utilisaient des instructions chaînées (l'adressage dit « un-plus-un »). Mais la conceptualisation du traitement de listes en tant qu'**abstraction formelle** a créé un monde conceptuel nouveau dans lequel la désignation et la structure symbolique dynamique devinrent les propriétés définitoires. L'intégration des premiers systèmes de traitement de listes dans des langages spécialisés (les langages IPL, puis LISP) a parfois été critiquée comme un frein à la diffusion de ces techniques dans la programmation ordinaire ; mais c'est précisément ce véhicule linguistique qui permit de maintenir l'abstraction unifiée.

**LISP.** Une étape supplémentaire mérite d'être soulignée : la création de **LISP** par John McCarthy en 1959-1960 [McCarthy, 1960]. Elle acheva l'acte d'abstraction en extrayant les structures de listes de leur enracinement dans des machines concrètes, créant un système formel élégant fondé sur les expressions symboliques (**S-expressions**), dont l'équivalence avec les autres formalismes universels de calcul put être rigoureusement démontrée.

**Conclusion.** Le fait que le concept de symbole désignant et de manipulation de symboles ne soit apparu qu'au milieu des années cinquante ne signifie nullement que les étapes antérieures étaient accessoires ou de moindre importance. Le concept unifié final est la conjonction indissociable de la **calculabilité**, de la **réalisabilité physique** (à travers des technologies matérielles multiples), de l'**universalité**, de la **représentation symbolique des processus** (c'est-à-dire l'interprétabilité) et, enfin, de la **structure symbolique et de la désignation**. Chacune de ces étapes a apporté une pierre indispensable à l'édifice.

La première étape de cette chaîne, formulée par Turing, était de nature théorique et mathématique ; mais toutes les étapes subséquentes plongent de profondes racines dans l'empirisme. Nous avons été guidés par l'évolution de l'ordinateur lui-même. Le principe du programme enregistré est né de l'expérience pratique acquise sur l'ENIAC. Le traitement de listes est né de la volonté de construire des programmes intelligents. Il a pris appui sur l'émergence des mémoires à accès aléatoire (RAM), qui ont fourni une réalisation physique limpide du symbole désignant sous la forme de l'**adresse mémoire**. LISP est né de l'expérience accumulée avec le traitement de listes.

---

### Les Preuves Empiriques

Nous en venons maintenant aux preuves étayant l'hypothèse selon laquelle les systèmes de symboles physiques sont capables d'action intelligente, et selon laquelle toute action intelligente générale exige un système de symboles physiques. L'hypothèse est une **généralisation empirique** et non un théorème déductif. Nous ne connaissons aucun moyen de démontrer le lien entre systèmes symboliques et intelligence sur des bases purement logiques *a priori*. À défaut d'une telle déduction, il nous faut impérativement examiner les faits.

Notre propos n'est pas de passer en revue la totalité des preuves dans le détail, mais d'utiliser cet exemple pour illustrer la proposition fondamentale selon laquelle l'informatique est un champ d'enquête empirique. Nous indiquerons donc la nature des preuves accumulées et la logique générale de leur réfutation ou corroboration.

La notion de système de symboles physiques s'est stabilisée dans sa forme contemporaine au milieu des années cinquante, date à laquelle on peut faire remonter la constitution de l'intelligence artificielle comme sous-discipline cohérente de l'informatique. Les vingt années de travaux écoulées depuis lors ont vu l'accumulation constante de preuves empiriques réparties selon deux grandes orientations :

1. **La preuve de suffisance (Intelligence Artificielle) :** Elle s'attache à démontrer que les systèmes de symboles physiques suffisent à produire de l'intelligence, en s'efforçant de concevoir, programmer et tester des systèmes artificiels concrets dotés de telles capacités.
2. **La preuve de nécessité (Psychologie Cognitive) :** Elle s'attache à vérifier si la présence d'un système de symboles physiques est nécessaire partout où se manifeste l'intelligence. Elle prend pour point de départ l'Être Humain — le système intelligent qui nous est le plus familier — et cherche à déterminer si son activité cognitive s'explique par les mécanismes d'un système de symboles physiques.

Ces deux orientations constituent les piliers empiriques majeurs : la première s'appelle couramment l'**intelligence artificielle** ; la seconde, la **psychologie cognitive du traitement de l'information**.


<!-- ======================================================================= -->
<!-- PAGE 7                                                                  -->
<!-- ======================================================================= -->

### 1. La construction de systèmes intelligents (Intelligence Artificielle)

Le paradigme expérimental de base mobilisé lors des premiers tests de la théorie microbienne des maladies était limpide : *identifier une maladie, puis chercher le germe*. Un paradigme rigoureusement analogue a guidé l'immense majorité des recherches en intelligence artificielle : **identifier un domaine de tâche exigeant de l'intelligence, puis concevoir un programme pour ordinateur numérique capable d'accomplir les tâches de ce domaine**.

Les tâches les plus faciles et les mieux structurées ont été explorées en premier : les jeux de réflexion, les casse-têtes logiques, les problèmes de recherche opérationnelle (ordonnancement et allocation de ressources), et les tâches d'induction élémentaires. Des dizaines, voire des centaines de programmes de cette nature ont désormais été conçus, chacun manifestant une certaine mesure d'action intelligente dans son domaine d'expertise.

L'intelligence n'est naturellement pas une propriété de « tout ou rien » ; on a assisté à une progression continue vers des niveaux accrus de performance dans des domaines ciblés, ainsi qu'à un élargissement constant de ces domaines. Les premiers programmes d'échecs, par exemple, étaient jugés concluants s'ils parvenaient simplement à jouer des coups légaux avec une vague esquisse de cohérence ; peu après, ils atteignirent le niveau de débutants humains ; en l'espace de dix à quinze ans, ils commencèrent à battre des amateurs sérieux. Le progrès a certes été graduel, mais ininterrompu, et le paradigme « concevoir et tester » a opéré selon un cycle régulier — l'activité de recherche globale mimant à l'échelle macroscopique le cycle élémentaire de **« génération et test »** qui anime nombre de programmes d'IA.

Le spectre de l'action intelligente accessible aux machines s'élargit constamment : des tâches combinatoires originelles, la recherche s'est étendue à la compréhension du langage naturel, à l'interprétation de scènes visuelles, à la coordination œil-main en robotique, à la conception assistée, à la synthèse automatique de programmes informatiques et à la compréhension de la parole. S'il existe des limites absolues au-delà desquelles l'hypothèse du système de symboles physiques cesserait de s'appliquer, elles ne sont absolument pas encore apparues.

Mais il s'est produit bien plus qu'une simple accumulation disparate d'exemples de systèmes spécialisés. Il eût été pour le moins décevant que les programmes d'IA accomplissant ces diverses tâches n'aient rien d'autre en commun que d'être des instances abstraites de systèmes symboliques. C'est pourquoi un intérêt scientifique majeur s'est porté sur **la découverte de mécanismes génériques** et de composants transversaux communs à de multiples tâches. Cette quête transporte la théorie au-delà de l'hypothèse initiale du système de symboles, vers une caractérisation plus fine des classes spécifiques de systèmes de symboles qui se révèlent efficaces en intelligence artificielle. Dans la deuxième partie de cet exposé, nous présenterons une hypothèse se situant précisément à ce second niveau de spécificité : **l'hypothèse de la recherche heuristique**.

La quête de généralité a donné naissance à une lignée de programmes conçus pour dissocier les mécanismes généraux de résolution de problèmes des particularismes d'une tâche donnée. Le **General Problem Solver (GPS)** en fut historiquement le premier jalon marquant ; parmi ses descendants contemporains figurent des systèmes tels que PLANNER et CONNIVER. La recherche de composants communs a produit des formalités génériques de représentation pour les buts et les plans, des réseaux de discrimination, des procédures de contrôle d'arbres de recherche, des mécanismes de filtrage de motifs (*pattern matching*) et des analyseurs syntaxiques. À l'instar de la théorie des germes, qui est passée de l'identification d'agents pathogènes isolés à l'étude des structures biologiques communes des bactéries, l'intelligence artificielle est passée de programmes empiriques ad hoc à l'identification des briques modulaires fondamentales de l'intelligence.

---

### 2. La modélisation du comportement symbolique humain (Psychologie Cognitive)

L'hypothèse du système de symboles physiques implique que le comportement symbolique de l'être humain s'explique par le fait qu'il possède, lui aussi, les caractéristiques physiques d'un système de symboles. Par conséquent, les résultats des efforts visant à modéliser le comportement humain au moyen de systèmes symboliques informatiques constituent une composante majeure des preuves étayant l'hypothèse. C'est pourquoi la recherche en intelligence artificielle se déploie en symbiose étroite avec la **psychologie du traitement de l'information** (*information processing psychology*).

Cette quête d'explications du comportement intelligent humain en termes de systèmes de symboles a remporté des succès éclatants au cours des vingt dernières années, au point où la théorie du traitement de l'information constitue aujourd'hui le paradigme dominant de la psychologie cognitive. Particulièrement dans les domaines de la **résolution de problèmes**, de l'**acquisition de concepts** et de la **mémoire à long terme**, les modèles computationnels de manipulation de symboles occupent désormais le devant de la scène.

La recherche en psychologie du traitement de l'information mobilise deux démarches empiriques conjointes :
1. La conduite d'observations rigoureuses et d'expérimentations sur le comportement humain dans des tâches exigeant de l'intelligence ;
2. La programmation de systèmes symboliques destinés à simuler fidèlement ce comportement observé.

Les observations psychologiques conduisent à formuler des hypothèses sur les processus symboliques mobilisés par les sujets, et ces hypothèses inspirent directement la programmation des architectures logicielles. C'est ainsi que les mécanismes fondamentaux du **GPS** ont été dérivés de l'analyse minutieuse des **protocoles verbaux** de sujets humains réfléchissant à haute voix (*thinking aloud*) lors de la résolution de problèmes logiques.


<!-- ======================================================================= -->
<!-- PAGE 8                                                                  -->
<!-- ======================================================================= -->

Le caractère éminemment empirique de l'informatique n'apparaît nulle part plus clairement que dans cette alliance féconde avec la psychologie. Non seulement les expériences psychologiques sont indispensables pour éprouver la véridicité des modèles de simulation informatique comme explications du comportement humain, mais c'est de ces expériences mêmes qu'émergent de nouvelles idées pour la conception et l'architecture des systèmes de symboles physiques.

**Autres preuves (La preuve négative).** Le principal ensemble de preuves en faveur de l'hypothèse du système de symboles physiques que nous n'avons pas encore abordé est constitué de preuves négatives : **l'absence d'hypothèses rivales précises** quant à la manière dont l'activité intelligente pourrait être réalisée — que ce soit chez l'humain ou dans une machine. La plupart des tentatives visant à formuler de telles hypothèses ont vu le jour au sein de la psychologie, où l'on a vu se succéder un continuum de théories allant du béhaviorisme à la *Gestalt-théorie*. 

Aucun de ces deux points de vue ne constitue un compétiteur sérieux face à l'hypothèse du système de symboles physiques, et ce pour deux raisons décisives :
1. Ni le béhaviorisme ni la psychologie de la forme n'ont démontré, ni même indiqué comment démontrer, que les mécanismes explicatifs qu'ils postulent (associations S-R, restructuration perceptive de champ) suffiraient à rendre compte d'un comportement intelligent dans des tâches complexes.
2. Aucune de ces théories n'a jamais été formulée avec un degré de spécificité opérationnelle approchant, même de loin, la précision des programmes informatiques d'intelligence artificielle. En réalité, ces théories alternatives demeurent suffisamment vagues pour qu'il ne soit guère difficile de leur conférer une interprétation en termes de traitement symbolique de l'information, et de les assimiler ainsi à l'hypothèse du système de symboles physiques.

### Conclusion de la première partie

Nous avons tenté d'utiliser l'exemple de l'Hypothèse du Système de Symboles Physiques pour illustrer concrètement le fait que l'informatique est une entreprise scientifique au sens plein et traditionnel du terme : elle élabore des hypothèses théoriques fondamentales qu'elle s'emploie ensuite à valider par l'enquête empirique. Mais nous avions également une seconde motivation : cette hypothèse constitue en elle-même une loi scientifique majeure, du type de celles que nous avons qualifiées de **« lois de structure qualitative »**. Elle représente une découverte fondamentale de l'informatique qui, si elle continue d'être étayée par les données empiriques comme c'est le cas actuellement, exercera un impact durable et déterminant sur notre discipline.

Nous nous tournons à présent vers un second exemple fondamental : **le rôle de la recherche dans l'intelligence**. Ce thème, et l'hypothèse spécifique qui s'y rattache, ont également joué un rôle central dans l'essor de l'informatique en général et de l'intelligence artificielle en particulier.

---

## II. La Recherche Heuristique (*Heuristic Search*)

Savoir que les systèmes de symboles physiques fournissent la matrice indispensable à l'action intelligente ne nous dit pas encore *comment* ils parviennent à accomplir cette prouesse. Notre second exemple de loi de structure qualitative en informatique aborde directement cette question, en affirmant que **les systèmes de symboles résolvent des problèmes en mettant en œuvre les processus de la recherche heuristique**.

Cette généralisation, tout comme la précédente, repose sur des preuves empiriques et n'a pas été déduite formellement d'autres prémisses logiques. Nous verrons cependant dans un instant qu'elle entretient un lien logique intime avec l'hypothèse du système de symboles, et l'on peut espérer une formalisation rigoureuse de cette connexion dans l'avenir. D'ici là, notre démarche demeure celle de l'enquête empirique. Nous décrirons ce que nous savons de la recherche heuristique et passerons en revue les résultats expérimentaux qui éclairent la manière dont elle confère son caractère intelligent à l'action.

Commençons par énoncer cette loi de structure qualitative :

> ### L'Hypothèse de la Recherche Heuristique
> **Les solutions aux problèmes sont représentées sous forme de structures de symboles. Un système de symboles physiques exerce son intelligence dans la résolution de problèmes par la recherche — c'est-à-dire en générant et en modifiant progressivement des structures de symboles jusqu'à ce qu'il produise une structure de solution.**
> 
> *(Heuristic Search Hypothesis. The solutions to problems are represented as symbol structures. A physical symbol system exercises its intelligence in problem solving by search—that is, by generating and progressively modifying symbol structures until it produces a solution structure.)*

Les systèmes de symboles physiques doivent nécessairement recourir à la recherche heuristique pour résoudre des problèmes parce qu'ils disposent de **ressources de traitement limitées** : en un nombre fini d'étapes et sur un intervalle temporel fini, ils ne peuvent exécuter qu'un nombre fini d'opérations élémentaires. Certes, il ne s'agit pas d'une limitation théorique écrasante, car toutes les machines de Turing universelles y sont soumises. Mais nous entendons cette limitation au sens fort : **une limitation pratique et effective**. Nous pouvons concevoir des calculateurs idéaux capables, par exemple, d'explorer en parallèle tous les nœuds d'un arbre à croissance exponentielle à une vitesse constante par pas de profondeur unitaire. Nous ne nous intéressons pas ici à de tels systèmes chimériques, mais à des systèmes réels dont les ressources computationnelles sont rares et limitées en regard de la complexité astronomique des situations auxquelles ils sont confrontés.

Cette contrainte n'exclut aucun système de symboles réel, qu'il soit incarné dans un ordinateur ou dans un cerveau humain face à des tâches du monde physique. Le fait que les ressources soient limitées nous autorise, pour la plupart des usages pratiques, à appréhender un système de symboles comme un **dispositif sériel** n'exécutant qu'un seul processus à la fois. S'il ne peut accomplir qu'une infime quantité de traitement dans un bref intervalle, nous pouvons tout aussi bien considérer qu'il procède étape par étape. Ainsi, les expressions « système de symboles à ressources limitées » et **« système de symboles sériel »** sont pratiquement synonymes. Le problème de l'allocation d'une ressource rare d'un instant à l'autre peut généralement être traité comme un problème d'ordonnancement sériel.


<!-- ======================================================================= -->
<!-- PAGE 9                                                                  -->
<!-- ======================================================================= -->

### La Résolution de Problèmes

Puisque la capacité à résoudre des problèmes est universellement tenue pour l'indicateur par excellence de l'intelligence, il est naturel qu'une part considérable de l'histoire de l'intelligence artificielle ait été consacrée à la construction et à l'élucidation de systèmes capables de résoudre des problèmes. La résolution de problèmes a été débattue par les philosophes et les psychologues pendant plus de deux millénaires, dans des discours imprégnés d'un profond sentiment de mystère. Si vous jugez qu'il n'y a rien de mystérieux ni de problématique dans le fait qu'un système symbolique résolve des problèmes, vous êtes alors un enfant de notre époque, dont la pensée a été façonnée depuis le milieu de ce siècle.

Platon (et, d'après son témoignage, Socrate) éprouvait des difficultés insurmontables à concevoir ne serait-ce que la manière dont un problème pouvait être posé à l'esprit, et bien plus encore la manière dont il pouvait être résolu. Qu'il suffise de rappeler comment cette aporie fut formulée dans le *Ménon* :

> **Ménon :** « Et de quelle manière chercheras-tu, Socrate, ce dont tu ne sais absolument pas ce que c'est ? Quelle chose entre celles que tu ignores choisiras-tu comme objet de ta recherche ? Et même si tu venais à tomber pile dessus, comment sauras-tu que c'est là précisément ce que tu ne savais pas ? »

Pour surmonter cette énigme insoluble pour la pensée grecque classique, Platon forgea sa célèbre **théorie de la réminiscence** : lorsque vous croyez découvrir ou apprendre quelque chose de nouveau, vous ne faites en réalité que vous ressouvenir de ce que votre âme connaissait déjà dans une existence antérieure. Si cette explication vous paraît prédatée ou extravagante, nous disposons aujourd'hui d'une réponse infiniment plus simple, directement issue de notre compréhension moderne des systèmes de symboles. En voici la formulation générale :

> **Poser un problème, c'est désigner :**  
> (1) **Un test** applicable à une classe de structures symboliques (qui définira les solutions du problème) ; et  
> (2) **Un générateur** de structures symboliques (qui produit des solutions potentielles candidates).  
> **Résoudre un problème, c'est générer une structure, au moyen du générateur (2), qui satisfait pleinement le critère d'évaluation du test (1).**

Nous sommes en présence d'un véritable problème si nous savons ce que nous voulons accomplir (le test), mais que nous ne savons pas immédiatement comment y parvenir (notre générateur ne produit pas d'emblée la structure symbolique requise). Un système de symboles est capable de formuler et de résoudre des problèmes précisément parce qu'il possède la double capacité de **générer et tester** (*generate and test*).

S'il ne s'agit que de cela, pourquoi ne pas engendrer directement et instantanément l'expression exacte satisfaisant le test ? C'est effectivement ce que nous faisons dans nos songes et nos rêveries pieuses. « Si les souhaits étaient des chevaux, les mendiants monteraient à cheval. » Mais en dehors du monde des songes, cela est impossible. Connaître le critère qui permettra de valider une solution une fois qu'elle est sous nos yeux ne signifie nullement que nous sachions comment la fabriquer — ni que nous disposions d'un générateur capable de la fabriquer d'un seul jet.

Par exemple, nous savons pertinemment ce que signifie « résoudre » une partie d'échecs en gagnant à tous les coups. Il existe un test simple et univoque pour reconnaître une position gagnante : l'échec et mat infligé au roi adverse. Dans un monde imaginaire, il suffirait d'engendrer d'emblée la stratégie magistrale menant à l'échec et mat contre toutes les ripostes possibles de l'adversaire. Hélas, aucun générateur doué d'un tel pouvoir n'est à la portée des systèmes de symboles physiques existants, qu'il s'agisse des humains ou des ordinateurs. À la place, les coups prometteurs aux échecs sont recherchés en générant une multitude d'alternatives plausibles et en les évaluant méticuleusement au moyen de mesures approchées, heuristiques et souvent faillibles, censées estimer la probabilité qu'une trajectoire donnée mène à une configuration victorieuse. **Des générateurs de coups, nous en avons ; mais un générateur direct de coups infailliblement gagnants, cela n'existe pas.**

Avant qu'un générateur d'actions puisse opérer sur un problème, il doit exister un **espace de problème** (*problem space*) : un univers de structures symboliques au sein duquel les situations du problème — y compris l'état initial et les états buts recherchés — peuvent être formellement représentées. Les générateurs d'actions sont des processus permettant de transformer une situation de l'espace de problème en une autre. Les caractéristiques intrinsèques des systèmes de symboles physiques garantissent qu'ils sont capables de représenter des espaces de problèmes et qu'ils possèdent des générateurs de mouvements. Comment, dans une situation concrète nouvelle, ils parviennent à synthétiser un espace de problème et des générateurs adaptés à cette situation demeure une question majeure située à la frontière même de la recherche contemporaine en IA.

La tâche à laquelle est confronté un système de symboles lorsqu'on lui soumet un problème et un espace de problème consiste donc à **mobiliser ses ressources limitées de traitement pour générer des solutions potentielles, les unes après les autres, jusqu'à en découvrir une qui satisfasse le test du problème**. Si le système possédait un certain contrôle sur l'ordre dans lequel les solutions candidates sont générées, il lui serait éminemment avantageux d'ordonner cette génération de façon à maximiser la probabilité que les solutions effectives apparaissent très tôt dans la séquence. Un système symbolique manifeste de l'intelligence dans l'exacte mesure où il parvient à orchestrer cette sélection sélective. **L'intelligence, pour un système à ressources limitées, consiste à faire des choix avisés quant à ce qu'il convient de faire ensuite (*what to do next*).**


<!-- ======================================================================= -->
<!-- PAGE 10                                                                 -->
<!-- ======================================================================= -->

### Extraire de l'information de l'espace de problème

Considérons un ensemble de structures symboliques dont un infime sous-ensemble constitue les solutions d'un problème donné. Supposons de surcroît que ces solutions soient réparties de manière rigoureusement aléatoire au sein de l'ensemble global. Cela signifierait qu'aucune information n'est disponible pour permettre à un générateur de faire mieux qu'une recherche purement aléatoire à l'aveugle. Dans un tel cas, aucun système symbolique ne pourrait faire montre de davantage d'intelligence (ni de moins d'intelligence) qu'un autre : le succès ne reposerait que sur la chance pure.

Par conséquent, **la condition indispensable à l'émergence de l'intelligence est que la distribution des solutions ne soit pas entièrement aléatoire**, c'est-à-dire que l'espace des structures de symboles recèle un minimum d'ordre, de régularité et de structure. Une deuxième condition est que ce patron d'organisation soit plus ou moins détectable par les mécanismes du système. Une troisième condition est que le générateur de solutions potentielles soit capable d'adapter différentiellement son comportement en fonction des régularités qu'il a détectées. Il doit exister de l'information dans l'espace de problème, et le système de symboles doit être capable de l'extraire et de l'exploiter.

Examinons un exemple très simple, où l'intelligence s'obtient aisément : la résolution d'une équation algébrique élémentaire :

$$AX + B = CX + D$$

Le test définit comme solution toute expression de la forme $X = E$ telle que $AE + B = CE + D$. On pourrait théoriquement concevoir comme générateur un mécanisme aveugle qui produirait des nombres au hasard, puis les testerait en les substituant dans l'équation. Nous ne qualifierions certes pas un tel dispositif de générateur intelligent.

À l'inverse, on peut concevoir des générateurs qui exploitent le fait mathématique que l'équation originale peut être transformée — en ajoutant ou en retranchant des quantités identiques de chaque côté, ou en multipliant ou divisant les deux membres par une même quantité — sans altérer l'ensemble de ses solutions. Mais nous pouvons obtenir bien plus d'informations pour guider le générateur en comparant la forme de l'expression actuelle avec la forme cible de la solution, et en opérant précisément les modifications qui rapprochent l'équation de la forme recherchée tout en préservant l'égalité.

Un tel générateur intelligent observera qu'il existe un terme indésirable $CX$ dans le membre droit, le soustraira des deux côtés et regroupera les termes en $X$. Il remarquera ensuite qu'il existe une constante indésirable $B$ dans le membre gauche et la retranchera des deux côtés. Enfin, il éliminera le coefficient résiduel $(A - C)$ en divisant les deux membres.

Par cette procédure, le générateur produit des structures symboliques successives, chacune obtenue en modifiant la précédente ; et les modifications visent expressément à **réduire les différences** entre la structure actuelle et la structure cible, tout en respectant les contraintes d'invariance de l'équation.

Cet exemple illustre les principes cardinaux mis en œuvre par les systèmes symboliques :
1. Chaque expression successive n'est pas engendrée de manière indépendante, mais par modification ciblée de la précédente ;
2. Les modifications dépendent d'une part de connaissances invariantes intégrées au générateur (les règles de transformation préservant l'équivalence), et d'autre part d'informations dynamiques détectées à chaque étape (l'écart de forme résiduel entre l'état courant et l'état but). C'est l'essence même de l'**analyse moyens-fins** (*means-ends analysis*).

Il n'y a aucun mystère quant à l'origine de l'information qui a guidé cette recherche. Nul besoin de postuler avec Platon une âme immortelle ayant contemplé la solution dans une existence antérieure : un système modérément sophistiqué de génération et test articulé à une analyse des différences résout l'énigme sans réincarnation.

---

### Arbres de recherche et explosion combinatoire

L'exemple algébrique peut sembler particulier, voire pathologique. Ce n'est assurément pas une recherche par essais et erreurs, car s'il y a eu quelques étapes, il n'y a eu aucune erreur. Nous sommes plus accoutumés à nous représenter la recherche dans la résolution de problèmes sous la forme d'**arbres foisonnants de solutions partielles** qui peuvent ramifier en milliers, voire en millions de branches avant de livrer une issue.

Ainsi, si à partir de chaque expression produite le générateur engendre $B$ nouvelles branches, l'arbre croîtra alors comme :

$$	ext{Taille de l'arbre} pprox B^D$$

où $B$ est le facteur de branchement (*branchiness*) et $D$ la profondeur de recherche (*depth*). L'arbre généré pour le problème algébrique avait la particularité singulière que son facteur de branchement était strictement égal à l'unité ($B = 1$).

Les programmes qui jouent aux échecs déploient typiquement des arbres de recherche immenses, atteignant dans certains cas un million de branches ou plus. L'un des courants majeurs de recherche sur les jeux s'est focalisé sur l'optimisation des structures de données et des processus de déplacement afin d'accélérer le parcours des nœuds et d'explorer des arbres toujours plus volumineux, selon l'idée que plus la recherche dynamique est profonde, plus les évaluations aux feuilles terminales seront exactes.

D'un autre côté, il existe des preuves empiriques solides montrant que **les plus forts joueurs humains, les grands maîtres internationaux, n'explorent que très rarement des arbres de plus d'une centaine de branches**. Cette stupéfiante économie n'est pas obtenue en calculant moins profondément que les ordinateurs, mais en opérant une **ramification extrêmement clairsemée et sélective à chaque nœud**. Cela n'est possible, sans dégrader dramatiquement la qualité des coups choisis, que parce qu'une part massive de la sélectivité est incorporée directement au sein du générateur lui-même, de sorte qu'il n'engendre que les branches hautement susceptibles de contenir des informations pertinentes.

La conclusion apparemment paradoxale à laquelle nous conduit cette analyse est que si la recherche séquentielle de solutions potentielles est un aspect fondamental de l'exercice de l'intelligence, **la quantité brute de recherche effectuée n'est absolument pas une mesure du degré d'intelligence manifesté**. Ce qui fait qu'un problème est un problème n'est pas qu'il requiert une recherche colossale, mais qu'il exigerait une recherche colossale si un niveau suffisant d'intelligence ne lui était pas appliqué. Lorsqu'un système symbolique en sait suffisamment sur un domaine, il avance droit vers son but ; ce n'est que lorsque ses connaissances deviennent lacunaires, lorsqu'il pénètre en *terra incognita*, qu'il est menacé de devoir errer dans des espaces immenses de recherche avant de retrouver sa voie.


<!-- ======================================================================= -->
<!-- PAGE 11                                                                 -->
<!-- ======================================================================= -->

La menace constante de l'**explosion exponentielle** de l'arbre de recherche nous met en garde contre l'illusion de compter sur la seule force brute des ordinateurs — même les plus colossaux et les plus rapides — pour compenser l'ignorance et le manque de sélectivité de leurs générateurs. L'espoir renaît périodiquement dans certains cœurs naïfs qu'un ordinateur suffisamment rapide, programmé avec assez d'astuce, parviendra à jouer aux échecs au plus haut niveau mondial par recherche brute exhaustive. Rien dans la théorie mathématique du jeu n'exclut formellement cette éventualité ; mais les études empiriques sur la gestion d'arbres volumineux démontrent qu'il s'agit d'une voie sans issue en regard des espoirs initiaux. Nous devons considérer ce résultat comme l'une des conclusions empiriques les plus marquantes de la recherche sur les jeux d'échecs en IA.

### Les Formes de l'Intelligence et la Boîte à Outils Heuristique

Le rôle de l'intelligence consiste donc à conjurer la menace permanente de l'explosion combinatoire. Comment y parvenir ?

La première voie consiste à **incorporer la sélectivité directement au sein du générateur** : n'engendrer que des structures qui présentent de réelles promesses de constituer des solutions ou de se situer sur la trajectoire y conduisant. La conséquence usuelle est de diminuer le facteur de branchement effectif ($B$), mais rarement de l'annuler totalement. L'explosion exponentielle ultime n'est pas éliminée — sauf dans des cas exceptionnellement structurés comme notre problème d'algèbre —, elle est simplement différée dans le temps. C'est pourquoi un système intelligent a impérativement besoin de compléter la sélectivité de son générateur par d'autres techniques d'exploitation de l'information pour guider la recherche.

Vingt années d'expérience dans la maîtrise de la recherche arborescente ont doté l'intelligence artificielle d'une trousse d'outils génériques devenue le patrimoine commun de tout chercheur :

Dans une recherche heuristique sérielle, la question cardinale est invariablement : **que convient-il de faire ensuite (*what shall be done next*) ?**  
Dans un arbre de recherche, cette question se scinde en deux sous-décisions fondamentales :
1. **À partir de quel nœud de l'arbre devons-nous poursuivre la recherche ?**
2. **Quelle direction (quel opérateur) devons-nous appliquer à partir de ce nœud ?**

L'information utile pour répondre à la première question évalue la distance relative estimée des différents nœuds par rapport au but : c'est la **recherche du meilleur d'abord** (*best-first search*), qui prescrit de développer en priorité le nœud qui semble le plus proche de la solution.

L'information utile pour répondre à la seconde question — dans quelle direction progresser — s'obtient typiquement en détectant les différences spécifiques entre l'état actuel et l'état but, puis en sélectionnant des actions spécialisées aptes à réduire ces différences particulières. C'est la technique reine de l'**analyse moyens-fins** (*means-ends analysis*), qui constitue le moteur central du *General Problem Solver* (GPS).

L'analyse historique montre que ces concepts cardinaux ont d'abord été forgés empiriquement :
- Les rudiments de la recherche *best-first* étaient déjà présents, bien que sans ce nom formel, dans le *Logic Theorist* dès 1955.
- Le GPS incarna l'analyse moyens-fins en 1957, en la combinant initialement avec une recherche en profondeur modifiée.
- Les programmes d'échecs ont privilégié, pour des raisons évidentes de saturation de mémoire vive, la recherche en profondeur d'abord (*depth-first*), complétée à partir de 1958 par le puissant algorithme d'**élagage alpha-bêta** (*alpha-beta pruning*).

---

### Méthodes « Faibles » et Méthodes « Fortes »

Les techniques que nous venons de décrire sont dédiées au contrôle et à l'atténuation de l'expansion exponentielle plutôt qu'à son éradication complète. Pour cette raison, elles ont été très justement baptisées **« méthodes faibles »** (*weak methods*) — des méthodes de recours universel lorsque les connaissances du système symbolique ou le degré de structure intrinsèque de l'espace de problème sont insuffisants pour autoriser l'évitement pur et simple de la recherche.

Il est instructif de contraster une situation hautement structurée (pouvant être formulée sous forme de problème de programmation linéaire) avec les situations mal structurées de problèmes combinatoires tels que le problème du voyageur de commerce ou les énigmes d'ordonnancement. En programmation linéaire, le calcul matriciel peut être considérable, mais **la recherche ne ramifie jamais** : chaque pas franchi est un pas garanti en direction de l'optimum. En revanche, dans la résolution de problèmes combinatoires ou la démonstration automatique de théorèmes, l'arborescence ne peut être contournée, et le succès dépend entièrement de méthodes de recherche heuristique.

Tous les courants de l'IA n'ont pas embrassé cette démarche empirique. Les travaux en démonstration formelle de théorèmes ont longtemps subi l'influence des mathématiques pures, où l'on refusait catégoriquement l'emploi d'heuristiques dès lors que la complétude formelle ne pouvait être prouvée déductivement. Puisque la complétude peut rarement être garantie pour des heuristiques *best-first* ou des générateurs sélectifs, cette exigence logiciste a paralysé le domaine. Lorsque les programmes de démonstration se trouvèrent systématiquement anéantis par l'explosion combinatoire de leurs arbres de résolution, les logiciens durent se résoudre à adopter des heuristiques sélectives — telles que l'heuristique de l'ensemble de soutien (*set-of-support*), qui n'est autre qu'une variante de travail à rebours (*working backwards*).


<!-- ======================================================================= -->
<!-- PAGE 12                                                                 -->
<!-- ======================================================================= -->

### Bilan de l'Expérience Historique

Nous avons maintenant décrit le fonctionnement de notre seconde loi de structure qualitative, qui affirme que les systèmes de symboles physiques résolvent des problèmes au moyen de la recherche heuristique. Au-delà de cet énoncé, nous avons examiné certaines caractéristiques subsidiaires de la recherche heuristique, en particulier la menace omniprésente de l'explosion exponentielle de l'arbre et les moyens mobilisés pour la conjurer.

Les jugements divergent quant au degré réel d'efficacité de la recherche heuristique comme mécanisme universel de résolution — les appréciations dépendant étroitement des domaines de tâches considérés et du niveau d'exigence adopté. Le succès peut être garanti si l'on fixe le seuil d'aspiration très bas ; l'échec est tout aussi certain si on le place trop haut. Les résultats empiriques accumulés peuvent se résumer comme suit :

Très peu de programmes résolvent aujourd'hui des problèmes au niveau d'un **« expert »** humain chevronné. Le programme de jeu de dames d'Arthur Samuel ainsi que le système **DENDRAL** de Feigenbaum et Lederberg (analyse de structures moléculaires en chimie organique) constituent les exceptions les plus célèbres ; mais on pourrait également citer divers programmes de recherche opérationnelle (ordonnancement d'usines et programmation en nombres entiers).

Dans de nombreux domaines, les programmes opèrent au niveau d'**amateurs compétents** : aux échecs, dans certains sous-domaines de la démonstration de théorèmes, ainsi que dans une multitude de casse-têtes. En revanche, le niveau humain est encore très loin d'être atteint par les systèmes confrontés à une interface perceptive complexe (*complex perceptual front end*) : la reconnaissance de scènes visuelles réelles, la compréhension continue de la parole et le pilotage de robots autonomes manœuvrant dans l'espace et le temps physiques. Néanmoins, des progrès remarquables ont été accomplis et un vaste corpus de connaissances a été constitué.

Nous ne disposons pas d'explications théoriques déductives profondes pour justifier la disparité des performances observées. Sur des bases empiriques, nous pouvons cependant tirer deux conclusions fondamentales :
1. D'après ce que nous avons appris de l'expertise humaine dans des tâches comme les échecs, il est hautement probable que tout système capable d'égaler cette compétence devra avoir accès, dans ses mémoires, à de **gigantesques bases de connaissances sémantiques** ;
2. Une part importante de la supériorité humaine dans les tâches à forte composante perceptive doit être attribuée à l'**architecture matérielle parallèle spécialisée** de l'œil et de l'oreille humains.

---

### L'Intelligence sans Recherche Extensive

Notre analyse a assimilé l'intelligence à la capacité d'extraire et d'exploiter l'information relative à la structure de l'espace de problème, afin de produire la solution le plus promptement et directement possible. Dès lors, les voies nouvelles pour décupler les capacités des systèmes symboliques consistent à inventer de **nouvelles manières d'extraire et d'utiliser l'information**. Trois pistes majeures se dégagent :

#### 1. L'utilisation non locale de l'information (*Nonlocal Use of Information*)

En premier lieu, plusieurs chercheurs ont relevé que les informations acquises au cours de l'exploration d'un arbre de recherche ne sont habituellement utilisées que de manière **locale**, pour éclairer la décision au nœud précis où elles ont été recueillies. L'information extraite d'une position d'échecs lors de l'analyse dynamique d'un sous-arbre de variantes ne sert généralement qu'à évaluer cette seule position, et n'est pas réinvestie pour évaluer d'autres positions qui partagent pourtant l'essentiel de ces caractéristiques. Par conséquent, les mêmes faits doivent être redécouverts inlassablement à différents nœuds de l'arbre.

Transposer aveuglément une information hors de son contexte d'origine pour l'appliquer universellement ne résout pas la difficulté, car cette information n'est souvent valide que dans un périmètre restreint. Ces dernières années, des tentatives prometteuses ont été entreprises pour transférer des connaissances de leur contexte source vers d'autres contextes pertinents :
- Les travaux de Hans Berliner [1975] sur l'**analyse causale** aux échecs : si une faiblesse tactique peut être imputée au coup initial qui l'a engendrée, la même vulnérabilité doit être anticipée dans toutes les positions descendantes issues de ce même coup.
- Le système **HEARSAY-II** pour la compréhension de la parole : il mène une recherche en parallèle à de multiples niveaux (phonémique, lexical, syntaxique et sémantique). Chaque niveau dépose ses hypothèses et découvertes sur un **tableau noir partagé** (*common blackboard*) lisible par l'ensemble des sources de connaissances. Cette information mutualisée permet d'éliminer immédiatement de vastes classes d'hypothèses qui auraient autrement exigé une recherche exhaustive.


<!-- ======================================================================= -->
<!-- PAGE 13                                                                 -->
<!-- ======================================================================= -->

#### 2. Les Systèmes de Reconnaissance Sémantique (*Semantic Recognition Systems*)

Une deuxième possibilité majeure pour élever le niveau d'intelligence d'un système consiste à le doter d'un **riche corpus d'informations sémantiques** relatives au domaine traité.

Par exemple, les recherches empiriques conduites sur la psychologie des maîtres d'échecs (inaugurées par Adriaan de Groot, puis approfondies par Chase et Simon) révèlent qu'une part prépondérante du talent du grand maître repose sur des connaissances emmagasinées en mémoire à long terme lui permettant de **reconnaître instantanément un très grand nombre de motifs visuels et de configurations tactiques typiques** sur l'échiquier, et d'associer immédiatement à ces motifs des plans d'action appropriés.

Ce principe général était certes présent dans les programmes d'échecs dès l'origine. Ce qui est radicalement nouveau, c'est la prise de conscience du **volume colossal** de ces motifs requis pour jouer au niveau de maître : **de l'ordre de 50 000 motifs perceptifs distincts (*chunks*)**.

La possibilité de **substituer la reconnaissance à la recherche** (*substituting recognition for search*) provient du fait qu'un motif particulier, surtout s'il est rare et discriminant, recèle une quantité phénoménale d'informations, à condition d'être intimement arrimé à la structure profonde de l'espace de problème. Lorsque cette structure est « irrégulière » et rebelle à toute description mathématique analytique simple, la possession en mémoire d'une vaste bibliothèque de motifs pertinents constitue la clé de voûte du comportement intelligent.

---

#### 3. Le Choix d'une Représentation Appropriée (*Selecting Appropriate Representations*)

Une troisième piste de recherche fondamentale réside dans l'évitement ou la réduction drastique de la recherche par **le choix d'un espace de problème adéquat**. Un exemple classique illustre cette métamorphose de façon saisissante : **le problème du damier mutilé** (*the mutilated checkerboard problem*).

> Un damier traditionnel de 64 cases peut être exactement et intégralement recouvert par 32 dominos rectangulaires de taille $1 	imes 2$, chaque domino recouvrant très exactement deux cases adjacentes.  
> Supposons à présent que nous découpons et supprimons deux cases situées aux **deux coins diagonalement opposés** du damier, laissant un plateau résiduel de 62 cases.  
> **Ce damier amputé peut-il être recouvert exactement par 31 dominos ?**

Avec une patience littéralement surhumaine, l'impossibilité géométrique d'un tel pavage pourrait être démontrée en essayant méthodiquement toutes les combinaisons d'agencements imaginables dans l'arbre de recherche combinatoire.

L'alternative — réservée à ceux qui ont moins de patience mais davantage d'intelligence — consiste à changer d'espace de représentation et à observer une propriété structurelle élémentaire : **les deux coins diagonalement opposés d'un échiquier sont obligatoirement de la même couleur** (disons blancs). Par conséquent, le damier mutilé compte 32 cases d'une couleur (noires) et seulement 30 cases de l'autre (blanches). Or, tout domino posé sur le plateau recouvre nécessairement **exactement une case blanche et une case noire**, si bien que 31 dominos recouvriront invariablement 31 cases de chaque couleur. Le pavage est donc rigoureusement impossible.

Comment un système de symboles physiques peut-il découvrir spontanément cet argument inductif élégant pour s'épargner une recherche combinatoire désespérée parmi des millions de dispositions stériles ? Nous accorderions sans hésiter les plus hautes notes d'intelligence à un système capable d'une telle découverte.

Pourtant, en posant cette question, nous n'échappons peut-être pas à la recherche. Nous n'avons fait que **déplacer la recherche d'un espace de solutions potentielles vers un espace de représentations potentielles**. Quoi qu'il en soit, le processus consistant à basculer d'une représentation à une autre, à découvrir et à évaluer de nouveaux espaces de problèmes constitue une *terra incognita* de la recherche en résolution de problèmes. Les lois de structure qualitative gouvernant les représentations restent encore à découvrir.

---

### Conclusion Générale

Voilà notre bilan sur les systèmes de symboles et l'intelligence. Le chemin parcouru depuis le *Ménon* de Platon jusqu'à nos jours a été long, mais il est réconfortant de constater que la quasi-totalité des progrès décisifs ont été accomplis depuis le début du vingtième siècle, et une fraction majeure depuis le milieu de ce siècle.

La pensée humaine demeurait insaisissable et ineffable jusqu'à ce que la logique formelle moderne l'interprétât comme **la manipulation de jetons formels**. Et elle semblait encore confinée dans le ciel des Idées platoniciennes ou dans les recoins obscurs de l'âme, jusqu'à ce que les ordinateurs nous apprennent comment des symboles matériels peuvent être traités par des machines physiques. Alan M. Turing, que nous commémorons ce matin, a apporté ses contributions magistrales au carrefour de ces deux courants historiques majeurs unissant la logique à l'ordinateur.


<!-- ======================================================================= -->
<!-- PAGE 14                                                                 -->
<!-- ======================================================================= -->

### Récapitulation des Deux Lois Fondamentales

**1. Les Systèmes de Symboles Physiques.** L'étude conjointe de la logique et de l'informatique nous a révélé que **l'intelligence réside dans les systèmes de symboles physiques**. C'est la loi de structure qualitative la plus fondamentale de l'informatique.

Les systèmes de symboles sont des collections de motifs et de processus, ces derniers étant capables de produire, de modifier, de reproduire et de détruire les premiers. Les propriétés les plus déterminantes de ces motifs sont qu'ils peuvent **désigner** des objets, des processus ou d'autres motifs, et que, lorsqu'ils désignent des processus, ils peuvent être **interprétés**. L'interprétation signifie l'exécution matérielle effective du processus désigné. Les deux classes les plus remarquables de systèmes de symboles physiques que nous connaissions sont **les êtres humains et les ordinateurs**.

Notre compréhension actuelle des systèmes de symboles s'est forgée à travers une succession d'étapes historiques majeures :
- La **logique formelle** nous a familiarisés avec les symboles traités syntaxiquement comme le matériau brut de la pensée, manipulés selon des règles rigoureuses ;
- La **machine de Turing** a conféré au traitement syntaxique son caractère mécanique universel ;
- Le concept de **programme enregistré** a réaffirmé l'interprétabilité interne des symboles ;
- Le **traitement de listes** a propulsé au premier plan les capacités dénotatives des symboles et instauré une manipulation de structures indépendante de l'architecture matérielle fixe de la machine.

Dès 1956, tous ces concepts étaient en place, assortis du matériel électronique capable de les concrétiser. L'étude de l'intelligence des systèmes symboliques — le domaine de l'intelligence artificielle — pouvait commencer.

**2. La Recherche Heuristique.** La seconde loi de structure qualitative de l'IA affirme que **les systèmes de symboles résolvent des problèmes en générant des solutions potentielles et en les testant — c'est-à-dire en cherchant**. Les solutions sont découvertes en créant des expressions symboliques et en les modifiant séquentiellement jusqu'à ce qu'elles satisfassent les critères de la solution. Parce que leurs ressources physiques sont limitées, la recherche ne peut être instantanée : elle est obligatoirement **sérielle**. Elle laisse derrière elle soit une trajectoire rectiligne directe vers le but, soit, si des retours en arrière sont requis, un arbre foisonnant de chemins explorés.

Les systèmes de symboles physiques ne sauraient faire montre d'intelligence s'ils étaient plongés dans un chaos absolu. Ils exercent leur intelligence en extrayant l'information de l'espace de problème et en utilisant cette information pour orienter leur recherche, évitant ainsi les impasses stériles et les détours labyrinthiques. L'espace de problème doit receler de l'ordre et de la structure pour que la méthode opère. L'énigme du *Ménon* de Platon est résolue : l'information peut être remémorée, mais elle peut surtout être continuellement extraite du domaine que les symboles désignent.

---

### Le Socle Empirique de l'IA

La recherche en intelligence artificielle se préoccupe de la manière dont les systèmes de symboles physiques doivent être organisés pour se comporter intelligemment. Vingt années de travaux acharnés ont permis d'amasser un corpus imposant de connaissances, consigné dans des ouvrages volumineux, constitué pour l'essentiel d'expériences très concrètes sur le comportement de classes spécifiques de systèmes dans des domaines de tâches bien délimités. De cette pratique sont néanmoins émergées de puissantes généralisations transversales touchant aux lois universelles de l'intelligence.

Ces généralisations sont avant tout **qualitatives** plutôt que purement mathématiques. Elles possèdent davantage la saveur de la géologie ou de la biologie évolutive que celle de la physique théorique. Elles sont pourtant déjà suffisamment robustes pour nous permettre aujourd'hui de concevoir et d'édifier des systèmes artificiels modérément intelligents dans une large palette d'activités, tout comme de pénétrer profondément les mécanismes de l'intelligence humaine.

### Et Maintenant ?

Dans notre tableau d'aujourd'hui, nous avons évoqué des questions résolues mais aussi de nombreuses questions ouvertes. Nous ne voyons aucun fléchissement dans la passion de l'exploration qui anime ce domaine depuis un quart de siècle. Deux contraintes matérielles détermineront le rythme des progrès au cours des décennies à venir :
1. **La puissance de calcul brute** disponible ;
2. Et surtout, facteur infiniment plus décisif, **le nombre de jeunes chercheurs talentueux** qui se tourneront vers cette discipline fascinante comme le défi le plus stimulant qu'ils puissent relever.

Alan M. Turing concluait son célèbre article fondateur de 1950, *« Computing Machinery and Intelligence »*, par ces mots visionnaires :

> **« Nous ne pouvons voir qu'à une courte distance devant nous, mais nous pouvons y voir bien des choses qui demandent à être accomplies. »**

Bien des choses que Turing entrevoyait en 1950 ont été accomplies, mais le programme de travail demeure plus vaste que jamais. Peut-être donnons-nous une portée excessive à sa simple remarque, mais nous aimons croire que Turing y reconnaissait la vérité fondamentale que tout informaticien éprouve instinctivement. Car pour tous les systèmes de symboles physiques, condamnés comme nous le sommes à l'exploration sérielle d'environnements complexes, la question critique et lancinante demeure éternellement :

<p style="text-align: center; font-size: 1.25rem; font-weight: 700; color: var(--primary); margin: 20px 0;">
  « Que convient-il de faire ensuite ? »<br>
  <span style="font-size: 1rem; font-style: italic; font-weight: 400; color: var(--text-muted);">(What to do next?)</span>
</p>

---

### Références Bibliographiques

- **Berliner, H. [1975].** *Chess as problem solving: the development of a tactics analyzer.* Thèse de doctorat, Département d'informatique, Carnegie-Mellon University (non publiée).
- **McCarthy, J. [1960].** Recursive functions of symbolic expressions and their computation by machine. *Communications of the ACM*, 3(4), 184–195.
- **McCulloch, W. S. [1961].** What is a number, that a man may know it, and a man, that he may know a number. *General Semantics Bulletin*, 26–27, 7–18.
- **Nilsson, N. J. [1971].** *Problem Solving Methods in Artificial Intelligence.* New York: McGraw-Hill.
- **Turing, A. M. [1936].** On computable numbers, with an application to the Entscheidungsproblem. *Proceedings of the London Mathematical Society*, 42(2), 230–265.
- **Turing, A. M. [1950].** Computing machinery and intelligence. *Mind*, 59(236), 433–460.


