# Les Moteurs Sémantiques : Une Introduction au Mind Design

**Titre original :** *Semantic Engines: An Introduction to Mind Design*  
**Auteur :** John Haugeland  
**Publication officielle :** John Haugeland (éd.), *Mind Design: Philosophy, Psychology, Artificial Intelligence*, MIT Press (Bradford Books), Cambridge, MA, 1981, pages 1–34.  
**Statut pédagogique :** Lecture suggérée pour la Séance 2 (Pr Pierre Poirier) — Épistémologie fondatrice de l'IA symbolique classique (GOFAI), systèmes formels automatiques et moteurs sémantiques.  
**Traduction académique :** Version intégrale française annotée avec marqueurs de page (1 à 17) et ancres interactives pour l'examen et la banque de questions étalon-or (UQAM).

---

### Fiche de Synthèse Conceptuelle & Points Clés

* **Thèse centrale :** La pensée et la rationalité humaine peuvent être physiquement instanciées dans la matière parce que le calcul logique n'est rien d'autre que la manipulation formelle réglée de symboles dénués de signification intrinsèque.
* **Le calcul selon Hobbes :** Penser, c'est calculer (*« Le raisonnement n'est que calcul »*, Leviathan, 1651).
* **Le paradoxe cartésien résolu :** Descartes refusait la possibilité d'un esprit matériel en raison de l'absence de flexibilité des automates de son temps. Les ordinateurs numériques résolvent ce paradoxe en combinant plasticité programmatique et rigueur formelle.
* **La maxime d'or de l'IA symbolique (GOFAI) :** *« Si vous prenez soin de la syntaxe, la sémantique prendra soin d'elle-même. »*
* **Les moteurs sémantiques :** Des dispositifs formels automatiques où la conformité aveugle aux règles syntaxiques préserve miraculeusement la vérité et la cohérence sémantique sous une interprétation isomorphe.

---

<!-- ======================================================================= -->
<!-- PAGE 1                                                                 -->
<!-- ======================================================================= -->

### I. Les Sciences Cognitives

« Le raisonnement n'est que calcul », déclarait Thomas Hobbes (1651, chap. V), formulant ainsi la toute première expression de la conception computationnelle de la pensée. Trois siècles plus tard, avec l'avènement des ordinateurs électroniques, son intuition a enfin commencé à s'imposer ; et en l'espace de trois décennies, elle est devenue l'hypothèse théorique la plus déterminante de la psychologie contemporaine (et de plusieurs disciplines connexes), tout en fondant un nouveau champ de recherche particulièrement stimulant : l'« intelligence artificielle ».

Récemment, l'expression *sciences cognitives* a été introduite pour désigner l'ensemble de ces entreprises convergentes, en reconnaissance de leur socle conceptuel commun. Ce terme ne s'applique donc pas à toute théorie scientifique de la cognition, mais uniquement à celles qui partagent une perspective fondamentale : l'approche par « traitement de l'information » ou par « manipulation de symboles ». Il semblerait qu'enfin l'intuition philosophique de Hobbes ait trouvé son ancrage au sein d'un véritable paradigme scientifique (Kuhn, 1970).

Bien souvent, les débats en sciences cognitives se focalisent sur l'intelligence artificielle — l'« IA » pour les intimes — parce qu'elle constitue en quelque sorte la quintessence distillée des sciences cognitives. Mais il importe de comprendre que l'IA (tout comme les sciences cognitives) possède une acception plus précise que ne le suggèrent les mots eux-mêmes. De façon schématique, on peut formuler la distinction en termes de technologies : un projet chez IBM visant à câbler et programmer un robot intelligent relèverait assurément de l'IA, alors qu'un projet chez DuPont visant à synthétiser et mouler un androïde organique n'en relèverait probablement pas.

Pourtant, cette distinction matérielle peut induire en erreur ; l'enjeu crucial ne réside pas dans l'opposition entre le protoplasme et le semi-conducteur (le substrat biologique ou *wetware* contre le matériel ou *hardware*), mais bien dans la question de savoir si le produit est conçu et spécifié selon une structure computationnelle. Si tel est le cas, un modèle fonctionnel peut être matérialisé bien plus aisément par l'électronique et la programmation ; et c'est là l'unique pertinence de la technologie. L'inspiration directrice des sciences cognitives affirme qu'à un niveau d'abstraction approprié, une théorie de l'intelligence « naturelle » doit revêtir la même forme fondamentale que les théories qui expliquent les systèmes informatiques sophistiqués. C'est cette thèse qui confère à l'intelligence artificielle son statut de forme centrale et pure de la recherche psychologique.

On saisit mieux l'effervescence entourant cette idée en se demandant pourquoi trois cents ans ont été nécessaires pour que la proposition originale de Hobbes soit enfin reconnue à sa juste valeur. Fondamentalement, <a id="3"></a>trois célèbres dilemmes philosophiques faisaient obstacle : (i) le problème métaphysique de l'interaction entre l'esprit et la matière ; (ii) le problème théorique d'expliquer la pertinence causale des significations sans recourir à un homoncule illégitime ; et (iii) la question méthodologique de la testabilité empirique (et donc de la respectabilité scientifique) des explications mentalistes. L'hypothèse computationnelle tranche ces trois dilemmes d'un seul coup, et c'est ce qui lui confère son immense pouvoir explicatif et sa séduction viscérale.


<!-- ======================================================================= -->
<!-- PAGE 2                                                                 -->
<!-- ======================================================================= -->

Descartes, contemporain de Hobbes, donna au problème de l'esprit et de la matière sa formulation moderne dans sa doctrine du dualisme métaphysique. L'esprit et le corps, affirmait-il, constituent deux substances de nature radicalement dissemblable : l'une possède comme propriété distinctive des pensées et des sentiments conscients, tandis que l'autre se caractérise par des formes géométriques, des mouvements spatiaux et des interactions causales gouvernées par des lois physiques déterministes. Intuitivement, cette conception est bien plus séduisante que le matérialisme (la principale alternative au dualisme), selon lequel toute entité, y compris l'esprit, n'est en réalité que de la matière sous une forme ou une autre. Non seulement répugnons-nous à attribuer des pensées ou des affects à la « simple » matière inerte, mais nous éprouvons également une peine immense à concevoir qu'un esprit ou une idée puisse posséder une forme géométrique ou une localisation spatiale précise.

Cependant, un dilemme insurmontable guette tout dualiste : comment l'esprit et le corps peuvent-ils interagir causalement ? D'un côté, cette interaction semble empiriquement évidente : une décision mentale commande une action corporelle motrice, tandis qu'une stimulation physique externe engendre une perception mentale consciente ; à vrai dire, on ne voit guère comment la perception et l'action intentionnelle pourraient être possibles sans interaction psychophysique. Mais d'un autre côté, les lois de la physique sont supposées décrire intégralement l'ensemble des mouvements de tous les corps matériels en termes exclusifs de leurs interactions physiques réciproques. En d'autres termes, la physique moderne ne laisse strictement aucune place à une quelconque intervention causale du mental immatériel. Le prix à payer pour soutenir l'interactionnisme dualiste est donc la violation ouverte des lois physiques de conservation de l'énergie — un tribut intellectuel que presque aucun scientifique ou philosophe contemporain n'est prêt à acquitter.

La pensée elle-même (indépendamment de son assise corporelle) n'est ni statique ni aléatoire : elle se déploie et chemine selon des formes qui respectent (du moins la plupart du temps) diverses règles d'inférence, de logique et de rationalité. Superficiellement, cela évoque une analogie avec les particules matérielles obéissant aux lois de la gravitation ou de l'électromagnétisme. Mais l'analogie s'effondre sur un point névralgique : les particules physiques n'ont ni le choix ni la moindre difficulté à « obéir » aux lois physiques — cela s'opère de manière infaillible, aveugle et automatique. Les êtres humains, à l'inverse, doivent souvent faire un effort délibéré pour être rationnels ; se conformer aux règles de la raison est loin d'être infaillible et peut s'avérer ardu. Il ne saurait donc y avoir de dynamique explicative de la pensée comparable aux théories physiques déterministes ; le statut normatif des règles rationnelles diffère profondément du statut descriptif des lois de la nature.

Puisque l'application appropriée des règles de la raison à des pensées dépend de ce que ces pensées signifient sémantiquement, il semble indispensable de postuler un agent actif appliquant les règles — une entité qui « comprend » les pensées et les règles, et qui les applique du mieux qu'elle peut. Si l'activité de cet agent doit rendre compte de la rationalité de nos processus intellectuels, il faut alors le concevoir comme un véritable petit être humain complet — un *homoncule* (en latin) — logé à l'intérieur de la boîte crânienne et régulant le trafic des idées à la manière d'un agent de la circulation. Le piège est fatal : une théorie qui recourt à un homoncule pour expliquer la pensée commet une pétition de principe, car l'homoncule doit lui-même penser, et sa propre pensée demeure inexpliquée.

Enfin se pose la question de savoir comment une psychologie de la pensée pourrait prétendre au statut de science rigoureuse. Les pensées, semble-t-il, échappent à l'observation publique ; et l'obstacle ne tient pas au fait qu'elles seraient trop petites ou trop lointaines comme les électrons ou les galaxies. Elles sont intrinsèquement subjectives et privées. La science empirique ne peut donc s'appuyer que sur les comportements publiquement observables. Dès lors, invoquer des croyances ou des désirs internes invisibles est beaucoup trop facile : pour tout comportement donné, on peut toujours inventer une infinité de motivations plausibles après coup. Faute de contrôle expérimental indépendant, le béhaviorisme a proclamé l'illégitimité scientifique de tout recours aux états mentaux. Cependant, tenter d'expliquer le comportement humain complexe sans faire intervenir le moindre processus mental s'est avéré une impasse absolue, confinant le béhaviorisme à l'analyse de comportements mécaniques triviaux.

L'issue à ce double blocage intellectuel a été apportée par les sciences cognitives : elles permettent d'être à la fois matérialistes (non dualistes) et mentalistes (non béhavioristes), en offrant des explications causales en termes de sens et de règles sans supposer le moindre homoncule inexpliqué. Tout repose sur une analogie remarquablement féconde avec les ordinateurs, dont la machine jouant aux échecs offre l'archétype le plus éclairant.


<!-- ======================================================================= -->
<!-- PAGE 3                                                                 -->
<!-- ======================================================================= -->

### II. Les Systèmes Formels

Il serait absurde d'attribuer une âme immatérielle à un ordinateur qui joue aux échecs. Pourtant, ses décisions logiques internes causent bel et bien des actions physiques observables (sur un écran ou une imprimante). Lorsqu'elle joue, la machine suit des règles en deux sens précis : elle respecte scrupuleusement les règles du jeu d'échecs, et elle déploie des heuristiques judicieuses pour sélectionner les meilleurs coups. Bien que ces règles ne soient en rien des lois de la nature, le comportement de la machine s'explique par leur intermédiaire, sans faire appel à un quelconque « homoncule » caché dans ses circuits. S'il n'existe aucun mystère philosophique pour une machine jouant aux échecs, pourquoi en existerait-il pour l'intelligence humaine ? Pourquoi ne pas postuler que les êtres humains sont eux-mêmes des systèmes formels incarnés ?

Pour asseoir cette perspective avec rigueur, nous devons définir avec précision ce qu'est un ordinateur : c'est un **système formel automatique**. Examinons d'abord ce qu'est un système formel en soi, avant d'aborder son automatisation matérielle.

Un système formel est analogue à un jeu dans lequel des jetons (*tokens*) sont manipulés conformément à des règles explicites, afin d'explorer les configurations possibles. Pour définir un tel système formel, trois éléments doivent être spécifiés de manière exhaustive :

  * **1. Les jetons autorisés :** la nature physique discrète et les types de jetons admis dans le système.

  * **2. La configuration initiale :** la position de départ à partir de laquelle le jeu commence.

  * **3. Les coups légaux :** l'ensemble des transformations ou déplacements permis pour chaque position donnée.

Implicitement, ces spécifications délimitent l'espace des états possibles (par exemple, la géométrie du plateau pour un jeu de damier). Parfois, une configuration cible ou gagnante est stipulée comme objectif pour le système.

Considérons le jeu de solitaire avec chevilles : les jetons sont des fiches plantées dans des alvéoles, et le plateau initial présente toutes les cases remplies sauf celle du centre. Le seul coup autorisé consiste à faire sauter une cheville par-dessus une cheville adjacente vers une case vide, puis à retirer la cheville sautée. Le but est de terminer avec une unique cheville au centre.

Trois propriétés fondamentales caractérisent ce système formel :

<ol class="doc-list">
  * **L'autosuffisance (Self-contained) :** Seuls les jetons, les positions et les coups internes ont une incidence sur le système. Le monde extérieur (la météo, la température, la situation économique) n'exerce strictement aucune influence sur le déroulement formel du jeu.

  * **La parfaite définition (Perfectly definite) :** Il n'existe aucune ambiguïté, aucune approximation ni aucun jugement subjectif. Pour toute cheville et tout alvéole, la cheville est soit rigoureusement dans le trou, soit hors du trou à 100 %, sans cas limite ni zone d'indécision.

  * **La vérifiabilité finie (Finitely checkable) :** Pour toute position donnée et tout coup candidat, un nombre strictement fini et discret d'éléments doit être inspecté pour déterminer si le coup est légal ou non.

</ol>
Tout système ou jeu qui combine ces trois propriétés est qualifié de **numérique (digital)**. Tous les systèmes formels sont, par définition même, rigoureusement numériques.


<!-- ======================================================================= -->
<!-- PAGE 4                                                                 -->
<!-- ======================================================================= -->

La nature numérique des systèmes formels engendre une conséquence théorique capitale : deux systèmes qui paraissent superficiellement dissemblables peuvent être *strictement et fondamentalement identiques*. Remplacer les chevilles du jeu de solitaire par des billes de verre ou des hélicoptères posés sur un aérodrome géant ne modifierait en rien la logique formelle du jeu, pourvu que les règles de saut soient fidèlement respectées.

La transposition peut être encore plus spectaculaire. Imaginons un jeu utilisant deux corbeilles et trente-trois dominos, chacun portant une lettre et un chiffre (par exemple B3, B4, C1, D4, etc.). Une « triade » est constituée de trois dominos partageant la même lettre avec des chiffres consécutifs, ou le même chiffre avec des lettres consécutives. La règle stipule que l'on peut basculer une triade d'une corbeille à l'autre dès que deux de ses membres occupent une corbeille et le troisième l'autre. Bien qu'à première vue ce jeu de dominos semble n'avoir aucun rapport avec le jeu de chevilles sur plateau, il lui est en vérité rigoureusement équivalent.

Cette identité de structure profonde porte le nom d'**équivalence formelle (formal equivalence)**. Deux systèmes formels sont formellement équivalents s'il existe une correspondance bijective (un isomorphisme) respectant les conditions suivantes :

  * À chaque position du premier système correspond une position unique dans le second ;

  * Les positions initiales se correspondent exactement ;

  * Dès qu'une transition est légale d'une position A vers une position B dans le premier système, la transition équivalente est légale entre les positions correspondantes dans le second système.

Deux complications majeures enrichissent les systèmes formels complexes :

La première est l'existence de *types de jetons distincts*. Aux échecs, chaque camp commence avec 16 pièces réparties en 6 types différents (pions, tours, cavaliers, fous, dame, roi). La légalité d'un coup dépend du type formel de la pièce manipulée : ce qui est permis pour un fou ne l'est pas pour une tour. Deux pièces traitées de manière identique par les règles appartiennent au même type formel et sont mutuellement interchangeables.

La seconde complication capitale réside dans le fait que *les positions entières d'un système formel peuvent servir de jetons dans un système formel de niveau supérieur*. C'est précisément ainsi que fonctionne l'algèbre ou la logique formelle.


<!-- ======================================================================= -->
<!-- PAGE 5                                                                 -->
<!-- ======================================================================= -->

### III. Les Systèmes Formels Automatiques

En algèbre, chaque équation constitue un jeton « composé » ou « moléculaire », lui-même constitué d'éléments de base (« jetons atomiques » : lettres, chiffres, opérateurs opérant selon les règles de formation d'expressions bien formées). Les règles de déduction formelle s'appliquent à ces équations en fonction de leur structure syntaxique interne (par exemple, simplifier un terme présent des deux côtés de l'égalité). Ainsi, un nombre fini de règles syntaxiques suffit pour gouverner une infinité d'expressions moléculaires distinctes.

Il peut sembler curieux de ranger les mathématiques et la logique formelle dans la même catégorie que le jeu de dames ou d'échecs, sous prétexte que leurs symboles sont porteurs de sens. Pourtant, du point de vue strictement syntaxique, les mathématiques et la logique sont des systèmes formels au sens le plus pur : elles possèdent des axiomes de départ, des règles explicites de transformation, et obéissent aux critères de délimitation numérique. Les significations sémantiques attribuées aux symboles sont, à ce stade syntaxique, totalement étrangères au mécanisme interne du système.

Un **système formel automatique** est un dispositif physique matériel (une machine) qui manipule automatiquement les jetons discrets d'un système formel conformément aux règles de ce système. C'est l'équivalent d'un échiquier physique robotisé qui déplacerait ses propres pièces et jouerait une partie autonome sans la moindre intervention humaine, ou d'un dispositif mécanique qui dériverait ses propres théorèmes logiques sans mathématicien.

L'ancêtre théorique universel de tous les systèmes formels automatiques est la **machine de Turing**, conçue abstraitement par Alan Turing en 1936. Une machine de Turing se compose de :

  * **1. Un ensemble illimité de registres ou cases de mémoire** (le ruban divisé en cases), chacune pouvant contenir exactement un jeton discret à la fois ;

  * **2. Un ensemble fini d'unités d'exécution physiques** (ou table d'états et d'instructions) ;

  * **3. Un pointeur ou registre indicateur** désignant à chaque étape l'état actif courant et la case inspectée.

La machine progresse par étapes discrètes : l'unité d'exécution active lit le symbole présent dans la case courante, écrit un nouveau symbole, déplace le ruban vers la gauche ou la droite, et positionne l'indicateur dans un nouvel état d'exécution.


<!-- ======================================================================= -->
<!-- PAGE 6                                                                 -->
<!-- ======================================================================= -->

Toute machine de Turing constitue l'automatisation physique d'un système formel spécifique. Mais la proposition inverse est encore plus saisissante : *tout système formel automatique concevable peut être formellement imité par une machine de Turing appropriée*. Deux systèmes formels automatiques qui effectuent les mêmes choix de transition à chaque étape sont dits **dynamiquement équivalents**.

Dans un dispositif informatique moderne, le système imitateur se scinde couramment en deux composantes : la *machine virtuelle* (qui matérialise l'architecture logique du système formel à émuler) et le *programme* (l'ensemble fini d'instructions codées en mémoire qui guide le matériel hôte pour reproduire fidèlement les règles de la machine virtuelle).

L'importance fondatrice des machines de Turing culmine dans un théorème démontré par Turing lui-même : l'existence de **machines de Turing universelles**. Une machine universelle est une machine de Turing unique capable d'exécuter la description codée de n'importe quelle autre machine de Turing particulière. Dès lors, par la thèse de Church-Turing, une machine de Turing universelle peut imiter n'importe quel système formel automatique sans exception ! Il suffit d'avoir une seule machine universelle et d'y introduire le bon programme pour réaliser n'importe quel calcul formel possible.

C'est précisément ce que sont les ordinateurs numériques modernes : des machines universelles physiques (avec pour seule restriction concrète une capacité de mémoire finie). En pratique, les programmeurs ne programment presque jamais le processeur au niveau des circuits physiques de silicium ; ils écrivent des logiciels pour des machines virtuelles de haut niveau (langages de programmation, interpréteurs et compilateurs). L'ordinateur physique émule une machine intermédiaire, qui elle-même émule le logiciel applicatif.


<!-- ======================================================================= -->
<!-- PAGE 7                                                                 -->
<!-- ======================================================================= -->

### IV. Le Problème du Contrôle

Un objet physique donné peut donc constituer simultanément une multitude de machines formelles différentes selon le **niveau de description** retenu. Au niveau matériel le plus bas, il s'agit d'un circuit électronique commutant des tensions ; à un niveau supérieur, il s'agit d'un processeur manipulant des octets ; à un niveau encore supérieur, il s'agit d'un interpréteur LISP ou d'un moteur de raisonnement jouant aux échecs. Il est donc profondément erroné de prétendre qu'un ordinateur n'est « rien d'autre qu'une grosse calculatrice qui brasse des 0 et des 1 ». C'est confondre le support matériel de bas niveau avec le système formel fonctionnel incarné au niveau abstrait pertinent.

Cependant, dans la majorité des systèmes formels riches, plusieurs coups distincts sont parfaitement légaux à partir d'une position donnée. Pour automatiser un tel système, la machine doit non seulement savoir générer les coups légaux, mais elle doit impérativement disposer d'un mécanisme pour *choisir* quel coup effectuer.

On peut se représenter l'architecture comme deux sous-machines en interaction :

  * Un générateur de coups légaux (qui propose les options autorisées par les règles) ;

  * Un organe de décision qui sélectionne le coup optimal parmi les options proposées.

La conception de cet organe de sélection constitue **le problème du contrôle**. Dans la pratique, la conception du contrôle s'avère la dimension la plus ardue de l'intelligence artificielle.


<!-- ======================================================================= -->
<!-- PAGE 8                                                                 -->
<!-- ======================================================================= -->

Dans une position moyenne d'une partie d'échecs, un joueur dispose d'environ 30 à 35 coups légaux. Il est aisé de concevoir un programme énumérant ces 35 options. La difficulté colossale réside dans le choix du coup à jouer. On pourrait imaginer naïvement que la rapidité de calcul d'un ordinateur lui permette de calculer exhaustivement tous les arbres de variantes jusqu'à la fin de la partie.

<a id="6"></a>Or, ce calcul exhaustif est physiquement impossible en raison de l'explosion combinatoire. Avec environ 31,6 options par demi-coup, chaque coup complet (les deux camps ayant joué) multiplie le nombre de ramifications par 1 000. Explorer 5 coups complets implique un quadrillion (10^15) de configurations ; une partie normale de 40 coups exigerait d'examiner 10^120 configurations — un chiffre astronomique qui dépasse de loin le nombre total de secondes écoulées depuis le Big Bang (10^18 secondes). L'explosion combinatoire frappe impitoyablement toute recherche exhaustive.

Les grands maîtres d'échecs humains ne calculent pas des millions de coups : ils sélectionnent immédiatement les deux ou trois coups pertinents et ignorent totalement la masse des coups stupides. La résolution du problème du contrôle exige donc de remplacer la force brute par des **heuristiques** sélectives.

La distinction fondamentale entre un **algorithme** et une **heuristique** est la suivante :

  * Un *algorithme* est une procédure infaillible garantie d'aboutir au résultat voulu (il suffit de tourner la manivelle mécanique, comme pour la multiplication de deux entiers) ;

  * Une *heuristique* est une règle empirique judicieuse, plausible et généralement fiable, mais qui n'offre aucune garantie absolue et demeure faillible.

Un ordinateur peut exécuter de façon rigoureusement infaillible un programme qui implémente des heuristiques hautement faillibles.


<!-- ======================================================================= -->
<!-- PAGE 9                                                                 -->
<!-- ======================================================================= -->

### V. Numérique et Analogique

Les heuristiques s'avèrent redoutablement efficaces dans des univers clos et formellement bien définis (les « micro-mondes », les jeux de plateau, la démonstration de théorèmes mathématiques). Dans ces domaines spécialisés, le but est clairement formalisable d'avance (mat aux échecs, dérivation d'une formule). En revanche, pour des comportements intelligents ouverts tels que converser normalement ou écrire de la poésie, il devient extrêmement difficile de caractériser formellement ce que serait une décision réussie.

Les systèmes formels automatiques sont par nature des calculateurs *numériques (digitaux)*. Il existe une autre classe d'appareils : les **systèmes analogiques**. Alors qu'un système numérique est constitué de transitions discrètes parfaitement tranchées, un système analogique opère sur des grandeurs continues sans états nettement ségrégués.

L'analogie la plus parlante est celle du sélecteur à crans par rapport au bouton de réglage continu d'une radio :

  * Le sélecteur numérique possède des positions franches (crans clairs) : il est impossible d'être réglé entre AM et FM.

  * Le cadran analogique se déplace de façon fluide et continue sans crans : le signal varie subtilement et capter une station requiert un ajustement empirique sensible.

Les maquettes architecturales projetant des ombres, les animaux de laboratoire en pharmacologie, les règles à calcul ou les réseaux de fils électriques sont des exemples d'instruments analogiques précieux.


<!-- ======================================================================= -->
<!-- PAGE 10                                                                 -->
<!-- ======================================================================= -->

<a id="4"></a>Le véritable avantage théorique des systèmes numériques sur les dispositifs analogiques ne réside pas seulement dans leur versatilité logicielle, mais avant tout dans leur immunité radicale face à l'accumulation et à la propagation du bruit et des erreurs de mesure matérielle. Dans tout système physique analogique continu, chaque étape de traitement ou de transmission ajoute inévitablement une petite imprécision ou une dérive physique microscopique. Au fil de calculs prolongés, ces erreurs s'accumulent de manière cumulative et exponentielle, finissant par dégrader et détruire complètement le signal initial.

À l'inverse, dans un système numérique discret, les jetons formels sont isolés par des seuils de tolérance francs (l'analogie des jetons de poker) : qu'un jeton soit légèrement ébréché, sali ou décentré de quelques millimètres n'altère en rien son appartenance catégorielle à 100 % au type « jeton rouge ». Le système physique rétablit à chaque étape la discrimination catégorielle pure, empêchant tout bruit matériel de se propager d'une étape à la suivante. C'est cette imperméabilité au bruit matériel qui confère au calcul numérique son infaillibilité reproductible.


<!-- ======================================================================= -->
<!-- PAGE 11                                                                 -->
<!-- ======================================================================= -->

### VI. Deux Descriptions des Symboles

Pour appréhender comment un système physique matériel peut faire preuve de rationalité, nous devons distinguer les deux descriptions complémentaires sous lesquelles tout symbole formel peut être envisagé :

<a id="5"></a>Ainsi, les jetons formels mènent une double vie : une vie syntaxique interne, dans laquelle ils ne sont que des marqueurs physiques inertes dénués de sens, manipulés aveuglément selon les règles combinatoires du jeu formel ; et une vie sémantique externe, dans laquelle ils sont dotés d'une interprétation et se rapportent intentionnellement à des objets, des états de fait ou des propositions du monde réel.

Du point de vue purement mécanique ou physique, le mécanisme qui manipule les jetons (le processeur électronique) ne « voit » et ne traite que la forme syntaxique spatio-temporelle des jetons ; il ignore superbement ce que ces jetons signifient. C'est la syntaxe matérielle qui guide exclusivement la causalité de la machine.


<!-- ======================================================================= -->
<!-- PAGE 12                                                                 -->
<!-- ======================================================================= -->

### VII. Interprétation et Sémantique

Qu'est-ce qui relie la vie syntaxique aveugle d'un symbole à sa vie sémantique intelligible ? C'est l'**interprétation sémantique systématique**. Une interprétation est une fonction de correspondance qui associe de manière cohérente et systématique :

  * Des jetons atomiques à des objets ou concepts du monde ;

  * Des structures syntaxiques composées à des propositions susceptibles d'être vraies ou fausses ;

  * Des transformations de règles formelles à des déductions rationnelles préservant la vérité.

Un système formel est dit doté d'une **sémantique préservant la vérité** lorsque chaque application valide d'une règle syntaxique transforme un ensemble de propositions tenues pour vraies en une nouvelle proposition qui s'avère nécessairement vraie dans le monde sous cette interprétation.


<!-- ======================================================================= -->
<!-- PAGE 13                                                                 -->
<!-- ======================================================================= -->

### VIII. Les Moteurs Sémantiques

Nous parvenons ici au cœur épistémologique de l'intelligence artificielle classique (GOFAI) :

<a id="1"></a>En pratique, dans un système formel interprété doté d'axiomes vrais et de règles formelles préservant rigoureusement la vérité, s'applique la célèbre maxime fondatrice des sciences cognitives : *« Si vous prenez soin de la syntaxe, la sémantique prendra soin d'elle-même. »* (If you take care of the syntax, the semantics will take care of itself.)

<a id="2"></a>Un système formel automatique doté d'une interprétation telle que la manipulation purement syntaxique de ses jetons internes garantit en tout temps la correction sémantique de ses résultats est précisément ce que j'appelle un **moteur sémantique (semantic engine)**.

Un moteur sémantique est une merveille conceptuelle : il matérialise physiquement la rationalité dans une machine sans requérir la moindre magie, sans enfreindre les lois de la physique, et sans faire intervenir un homoncule conscient dans les engrenages. La causalité aveugle de la matière produit mécaniquement de la vérité logique.


<!-- ======================================================================= -->
<!-- PAGE 14                                                                 -->
<!-- ======================================================================= -->

Un tel moteur sémantique intégré dans le corps d'un robot mobile agirait en apparence de manière remarquablement intelligente, motivée et cohérente : il soutiendrait une conversation, adapterait ses croyances aux observations factuelles et prendrait des décisions rationnelles conformes à ses objectifs déclarés.

Pourtant, un philosophe sceptique pourrait objecter que la machine n'a cure de ce qu'elle profère : les symboles ne signifient quelque chose que pour l'observateur extérieur humain qui les déchiffre. Pour la machine elle-même, ce ne sont que des impulsions électriques et des configurations d'interrupteurs fermés ou ouverts. Cette intuition sceptique motive les critiques affirmant que les ordinateurs ne peuvent pas posséder d'authentique compréhension intrinsèque.

Mais si les sciences cognitives sont sur la bonne voie, alors certains moteurs sémantiques matériels — à commencer par les cerveaux des êtres humains — peuvent bel et bien éprouver des sentiments, avoir des intentions et s'engager authentiquement dans le monde.


<!-- ======================================================================= -->
<!-- PAGE 15                                                                 -->
<!-- ======================================================================= -->

### IX. Les Sciences Cognitives (Retour d'ensemble)

L'hypothèse centrale des sciences cognitives affirme donc que les créatures intelligentes sont fondamentalement des moteurs sémantiques — autrement dit, des systèmes formels automatiques instanciés dans la biologie, dotés d'interprétations selon lesquelles ils produisent systématiquement du sens et de la rationalité.

De ce point de vue unifié, la psychologie et l'intelligence artificielle poursuivent le même objet d'étude : les êtres humains et les machines intelligentes ne sont que des matérialisations contingentes distinctes du même phénomène computationnel sous-jacent. De surcroît, grâce à l'universalité des machines de Turing, tout moteur sémantique concevable peut en principe être formellement simulé sur un ordinateur universel pourvu qu'on découvre le bon programme.

Deux grandes stratégies argumentatives ont été forgées pour contester cette vision fondatrice :

<ol class="doc-list">
  * **La stratégie de la coquille vide (Hollow Shell strategy) :** Quelle que soit la perfection extérieure avec laquelle un moteur sémantique agit comme s'il comprenait, il ne comprend rien en vérité, car il lui manque une qualité intérieure essentielle « X » (la conscience phénoménale, l'intentionnalité originelle, la sensibilité vécue). Le robot intelligent ne serait qu'un automate sans âme, une imposture purement comportementale.

  * **La stratégie du substitut indigent (Poor Substitute strategy) :** Elle refuse même à la machine la capacité d'égaler le comportement humain. Les moteurs sémantiques formels ne réussiront jamais à manifester le plein registre du sens commun humain, restant à jamais cantonnés à des micro-mondes artificiels étroits.

</ol>


<!-- ======================================================================= -->
<!-- PAGE 16                                                                 -->
<!-- ======================================================================= -->

Le candidat le plus évident pour l'inconnue « X » de la coquille vide est la **conscience**. On affirme couramment qu'aucun ordinateur ne saurait comprendre quoi que ce soit parce qu'il n'est pas conscient. Pourtant, les sciences cognitives et les neurosciences n'apportent encore que très peu de lumière sur la nature physique de la conscience ; le terme est d'ailleurs longtemps demeuré presque tabou dans la littérature technique formaliste (malgré les efforts pionniers de philosophes comme Dennett, 1978).

Un second candidat fondamental pour « X » est ce qu'on nomme l'**intentionnalité originelle (original intentionality)**. L'idée reçue est que les symboles d'un ordinateur n'ont de sens que parce que des programmeurs humains leur en attribuent un : leur intentionnalité est dérivée et empruntée, à l'image des signaux de fumée ou de l'encre sur une page de livre. En revanche, l'esprit humain jouirait d'une intentionnalité intrinsèque et originelle. Mais la question décisive demeure : qu'est-ce qui confère matériellement à un système biologique son intentionnalité originelle ? Si l'on écarte les explications mystiques ou théologiques, cela doit dépendre de la structure causale interne de l'organisme et de ses dispositions sensori-motrices en interaction écologique avec son environnement.

La stratégie du « substitut indigent » soulève une question empirique directe : le système formel parvient-il oui ou non à agir dans le monde réel avec le bon sens et la plasticité d'un être humain ? Si la réponse est non, existe-t-il une régularité dans ses échecs qui nous éclaire sur les limites intrinsèques des systèmes formels ? C'est là l'interrogation la plus profonde posée à l'intelligence artificielle contemporaine.


<!-- ======================================================================= -->
<!-- PAGE 17                                                                 -->
<!-- ======================================================================= -->

### Notes et Références Épistémologiques

Il est établi depuis Kurt Gödel (1931) qu'aucun système formel cohérent et axiomatique ne peut être sémantiquement complet pour l'arithmétique (les célèbres théorèmes d'incomplétude de Gödel). Bien que certains penseurs (notamment Lucas, 1961) aient tenté d'invoquer ce résultat pour affirmer l'irréductibilité métaphysique de l'esprit humain face aux machines, la grande majorité des chercheurs en sciences cognitives s'accorde pour considérer que les limitations gödeliennes n'invalident en rien la théorie computationnelle de l'esprit : les êtres humains sont eux-mêmes soumis à des limites intrinsèques de calcul et commettent des erreurs de raisonnement.

**Références fondamentales citées par John Haugeland (1981) :**

  * Austin, John L. (1970). *How to Do Things with Words*. Oxford: Oxford University Press.

  * Davidson, Donald (1973). « Radical interpretation », *Dialectica*, 27, 313–328.

  * Dennett, Daniel C. (1978). « Toward a cognitive theory of consciousness », dans *Brainstorms: Philosophical Essays on Mind and Psychology*. Bradford Books.

  * Dennett, Daniel C. (1981). « Three kinds of intentional psychology », dans Healey (éd.), *Reduction, Time and Reality*. Cambridge University Press.

  * Gödel, Kurt (1931). « Über formal unentscheidbare Sätze der Principia Mathematica und verwandter Systeme I », *Monatshefte für Mathematik und Physik*, 38, 173–198.

  * Grice, H. Paul (1975). « Logic and conversation », dans Cole & Morgan (éds.), *Syntax and Semantics*, vol. 3.

  * Haugeland, John (1979). « Understanding natural language », *Journal of Philosophy*, 76, 619–632.

  * Hobbes, Thomas (1651). *Leviathan, or The Matter, Forme, & Power of a Common-wealth Ecclesiasticall and Civill*.

  * Kuhn, Thomas S. (1970). *The Structure of Scientific Revolutions* (2e éd.). Chicago: University of Chicago Press.

  * Lucas, John R. (1961). « Minds, machines and Gödel », *Philosophy*, 36, 120–124.

  * Quine, Willard Van Orman (1960). *Word and Object*. Cambridge, MA: MIT Press.

  * Searle, John R. (1969). *Speech Acts: An Essay in the Philosophy of Language*. Cambridge University Press.

  * Turing, Alan M. (1936/1937). « On computable numbers, with an application to the Entscheidungsproblem », *Proceedings of the London Mathematical Society*, 42, 230–265.

