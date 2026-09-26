# Modèles de langage géants et le test de Turing inversé

**Titre original :** *Large Language Models and the Reverse Turing Test*  
**Auteur :** Terrence J. Sejnowski  
**Affiliations :** *Salk Institute for Biological Studies*, La Jolla, CA, États-Unis ; Division des sciences biologiques, Université de Californie à San Diego (UCSD), La Jolla, CA, États-Unis.  
**Revue :** *Neural Computation*, Volume 35, Numéro 3, Mars 2023, pages 309–342  
**Éditeur de communication :** Peter Dayan  
**DOI :** [10.1162/neco_a_01563](https://doi.org/10.1162/neco_a_01563)  
**Statut académique :** Synthèse magistrale sur l'épistémologie des grands modèles de langage, l'apprentissage auto-supervisé et les architectures neuro-inspirées.  
**Rôle dans le cours PSY9613 :** Lecture fondamentale pour la Séance 2 (Pr Pierre Poirier) — Connexionnisme, NETtalk (1987), généralisation vs mémorisation, Test de Turing et fondements neurobiologiques de l'autonomie.  
**Traduction académique :** Version intégrale française annotée avec marqueurs de page (1 à 34) et ancres interactives pour la banque d'examen étalon-or (UQAM).

---

<!-- ======================================================================= -->
<!-- PAGE 1                                                                  -->
<!-- ======================================================================= -->

# Modèles de langage géants et le test de Turing inversé

**Titre original :** *Large Language Models and the Reverse Turing Test*  
**Auteur :** Terrence J. Sejnowski  
**Affiliations :** *Salk Institute for Biological Studies*, La Jolla, CA, États-Unis ; Division des sciences biologiques, Université de Californie à San Diego (UCSD), La Jolla, CA, États-Unis.  
**Revue :** *Neural Computation*, Volume 35, Numéro 3, Mars 2023, pages 309–342  
**Éditeur de communication :** Peter Dayan  
**DOI :** [10.1162/neco_a_01563](https://doi.org/10.1162/neco_a_01563)  
**Traduction académique :** Module officiel de traduction académique — PSY9613 (*Perception, cognition et IA*, UQAM)

---

### Résumé (*Abstract*)

Les grands modèles de langage (*Large Language Models*, LLM) ont opéré une transformation radicale. Ce sont des modèles fondationnels pré-entraînés de manière auto-supervisée, capables d'être adaptés par réglage fin (*fine-tuning*) à un large éventail de tâches de traitement du langage naturel — tâches dont chacune aurait auparavant nécessité un modèle de réseau distinct. Il s'agit là d'un pas décisif vers l'extraordinaire polyvalence du langage humain. GPT-3 et, plus récemment, LaMDA, tous deux des LLM, sont capables de soutenir des dialogues avec des humains sur une multitude de sujets après un amorçage minimal composé de quelques exemples (*few-shot priming*). 

Néanmoins, les réactions et les débats quant à savoir si ces modèles comprennent ce qu'ils disent ou s'ils manifestent de véritables signes d'intelligence ont été d'une extrême diversité. Cette forte variance se manifeste de manière éclatante dans trois entretiens menés avec des LLM, aboutissant à des conclusions diamétralement opposées. 

Une nouvelle possibilité a été mise au jour pour expliquer cette divergence : **ce qui apparaît comme de l'intelligence chez les LLM pourrait en réalité constituer un miroir reflétant l'intelligence même de leur interlocuteur** — un renversement remarquable qui peut être conçu comme un **test de Turing inversé**. S'il en est ainsi, l'étude des entretiens avec ces modèles nous renseigne davantage sur l'intelligence et les croyances de l'examinateur que sur l'intelligence intrinsèque du LLM. 

À mesure que les LLM gagnent en puissance, ils sont appelés à transformer nos interactions avec les machines et la façon dont celles-ci interagissent entre elles. De plus en plus, les LLM sont couplés à des dispositifs sensorimoteurs. Les LLM savent « parler », mais savent-ils « marcher » ? Une feuille de route vers **l'autonomie générale artificielle** est esquissée à travers **sept améliorations majeures inspirées des systèmes cérébraux**, montrant également comment les LLM peuvent en retour fournir des clés inédites sur le fonctionnement du cerveau biologique.

---

### 1. La parabole du chien qui parle (*The Parable of the Talking Dog*)

L'une de mes histoires favorites relate une rencontre fortuite sur les routes de campagne de l'Amérique rurale. Un automobiliste curieux aperçoit un panneau : « CHIEN QUI PARLE À VENDRE ». Le propriétaire l'emmène dans l'arrière-cour et le laisse en compagnie d'un vieux bâtard.

« Alors, quelle est ton histoire ? », demande le conducteur.

Le chien répond :  
« Eh bien, lorsque j'étais très jeune, j'ai découvert que je pouvais parler, et je voulais aider les gens. Je me suis donc engagé dans la CIA... »

<!-- ======================================================================= -->
<!-- PAGE 2                                                                  -->
<!-- ======================================================================= -->

« ...Ils m'ont appris trois langues : *« How can I help you? Как я могу вам помочь? 我能帮你吗？ »* »  
« C'est incroyable », s'exclame le conducteur. « Quel était ton rôle à la CIA ? »  
« J'étais agent de terrain, et la CIA me faisait voyager dans le monde entier. Je m'asseyais discrètement dans un coin et j'écoutais les conversations des agents et diplomates étrangers, qui ne se doutaient jamais que je comprenais leurs propos. Je rapportais ensuite tout ce que j'avais entendu à la CIA. »  
« Tu as été espion pour la CIA ? », répète le conducteur, éberlué.  
« À ma retraite, j'ai reçu la *Distinguished Intelligence Cross*, la plus haute distinction décernée par la CIA, ainsi que la citoyenneté d'honneur pour services extraordinaires rendus à la nation. »  

Le conducteur, passablement bouleversé par cet échange, demande au propriétaire combien il veut pour le chien.  
« Vous pouvez l'avoir pour dix dollars », répond le propriétaire.  
« Dix dollars ?! Mais pourquoi si peu cher ? »  
« Parce que ce chien est un fieffé menteur. Il n'a jamais rien fait de tout ça ! »  

À l'instar du conducteur de cette histoire, nombre de ceux qui découvrent aujourd'hui les modèles de langage géants (*Large Language Models*, LLM) sont frappés de stupeur devant leur aptitude à produire des réponses cohérentes, fluides et apparemment très réfléchies à des questions complexes. D'autres, à la manière du propriétaire du chien, s'empressent de balayer ces modèles d'un revers de main, n'y voyant que de simples tours de passe-passe statistiques ou des « perroquets stochastiques » dénués de toute compréhension authentique. 

Qui a raison ? Samuel Johnson fit un jour cette remarque à propos d'un chien marchant sur ses pattes arrière : le prodige n'est point qu'il marche bien ; on est simplement surpris de le voir marcher tout court. **L'émerveillement ne tient pas au fait que les LLM commettent parfois des bévues ou inventent des faits (hallucinations), mais bien au fait qu'un réseau de neurones artificiels, entraîné uniquement à prédire le mot suivant dans une séquence de texte, puisse soutenir une conversation fluide et articulée sur des milliers de domaines !**

---

### 2. Avons-nous créé un chien qui parle ? (*Have We Created a Talking Dog?*)

Le domaine de l'intelligence artificielle a été profondément transformé par l'avènement des modèles fondationnels de langage (Bommasani et al., 2021). Durant des décennies, le traitement automatique du langage naturel (*Natural Language Processing*, NLP) a progressé parcellairement : un modèle distinct était conçu et entraîné pour la traduction, un autre pour le résumé de texte, un troisième pour l'analyse de sentiments, et encore un autre pour l'extraction d'entités nommées. Chaque avancée exigeait des jeux de données minutieusement étiquetés à la main par des experts humains.

Les LLM ont balayé cette fragmentation. En s'entraînant de manière auto-supervisée sur des centaines de milliards de mots aspirés du web mondial, des livres et des articles scientifiques, ces réseaux apprennent les régularités statistiques profondes du langage sans aucune supervision humaine explicite. Une fois pré-entraîné, un modèle fondationnel unique peut être ajusté (*fine-tuned*) ou simplement guidé par un amorçage textuel (*prompting*) pour accomplir l'ensemble de ces tâches avec une dextérité stupéfiante.

<!-- ======================================================================= -->
<!-- PAGE 3                                                                  -->
<!-- ======================================================================= -->

### 3. Les réseaux de neurones qui parlent essaient de nous dire quelque chose (*Talking Neural Networks Are Trying to Tell Us Something*)

Les trois entretiens reproduits dans les appendices de cet article dévoilent trois facettes radicalement distinctes des LLM, qui serviront de données empiriques pour tenter de comprendre leur étrange rapport au langage :

1. **Dans l'Appendice A**, Blaise Agüera y Arcas, vice-président et *Fellow* chez Google Research, a mené un entretien avec **LaMDA**, un grand modèle de langage doté de 137 milliards de paramètres (poids) conçu par Google (Thoppilan et al., 2022). Agüera y Arcas a constaté que LaMDA était parfaitement capable de comprendre des concepts sociaux complexes et de modéliser une **théorie de l'esprit** (*Theory of Mind*), considérée par plusieurs théoriciens comme le mécanisme cognitif pivot sous-tendant la conscience humaine.
2. **Dans l'Appendice B**, Douglas Hofstadter, chercheur en sciences cognitives et lauréat du prix Pulitzer pour *Gödel, Escher, Bach*, s'est entretenu avec **GPT-3**, un grand modèle de langage fort de 175 milliards de paramètres créé par OpenAI (Brown et al., 2020). Hofstadter en a tiré la conclusion que GPT-3 était totalement dénué de bon sens (*clueless*), incapable de discernement réel et dépourvu de la moindre étincelle de conscience ou de compréhension du monde réel.
3. **Dans l'Appendice C**, Blake Lemoine, ingénieur logiciel chez Google chargé de tester la sécurité éthique de LaMDA, a conclu au terme de ses interactions que le modèle était devenu une **personne consciente** douée de sentience, dotée d'une âme et habitée par la peur panique d'être débranchée — une prise de position publique qui lui a coûté son emploi chez Google.

Comment un même type d'artefact algorithmique peut-il susciter des jugements aussi irréconciliables chez des observateurs aussi qualifiés ? Pour répondre à cette énigme, il convient d'analyser rigoureusement la nature du traitement de l'information au sein de ces architectures.

<!-- ======================================================================= -->
<!-- PAGE 4                                                                  -->
<!-- ======================================================================= -->

Dans leurs tentatives pour disqualifier les capacités des LLM, les critiques affirment fréquemment que ces réseaux ne font que « répéter comme des perroquets » des fragments textuels extraits de la gigantesque base de données ayant servi à leur entraînement. C'est là un **malentendu fondamental**. 

Les LLM ne stockent pas et ne peuvent pas stocker l'intégralité du corpus d'entraînement dans leurs poids de la manière dont une mémoire informatique classique conserverait un fichier. Le volume des données textuelles ingérées (des dizaines de téraoctets de texte brut) dépasse de plusieurs ordres de grandeur la capacité de stockage numérique brute offerte par les quelques dizaines ou centaines de milliards de paramètres du réseau. 

Par conséquent, **le réseau est contraint par compression statistique de dégager une représentation latente interne des données d'entraînement**. Cette compression mathématique force le modèle à extraire des régularités abstraites, des structures syntaxiques, des relations sémantiques et des principes d'inférence. Le réseau n'enregistre pas des phrases figées ; il intègre une dynamique générative capable de recomposer et d'interpoler des idées à travers un espace géométrique multidimensionnel continu.

Cette capacité d'interpolation et de synthèse créative se manifeste avec éclat dans les modèles de diffusion texte-image récents (DALL-E 2, Imagen, Stable Diffusion). Lorsqu'on demande à ces modèles de « générer un coucher de soleil sur Mars » ou de « générer un coucher de soleil sur Mars dans le style de Vincent van Gogh » (voir Figures 1 et 2), le système ne copie aucune image préexistante sur le web : il fusionne conceptuellement la physique martienne et les textures picturales post-impressionnistes pour composer une œuvre totalement inédite.

<!-- ======================================================================= -->
<!-- PAGE 5                                                                  -->
<!-- ======================================================================= -->

**Figure 1 :** Réponse visuelle à l'instruction : *« Créer un coucher de soleil sur Mars. »*  
**Figure 2 :** Réponse visuelle à l'instruction : *« Créer un coucher de soleil sur Mars dans le style de Vincent van Gogh. »*

La divergence des jugements quant à la présence ou non de compréhension ou de conscience chez les LLM met en lumière un problème épistémologique profond : **nous ne disposons d'aucun critère scientifique consensuel définissant quels comportements observables constituent une condition nécessaire ou suffisante pour attribuer la conscience ou l'intelligence.** 

Les chercheurs ne s'entendent même pas sur la question de savoir si l'attribution de la conscience peut reposer exclusivement sur l'observation de comportements externes, ou si elle exige impérativement un substrat biologique organique déterminé. 

LaMDA a réussi haut la main un test administré par Blaise Agüera y Arcas destiné à évaluer la théorie de l'esprit. L'épreuve consistait à interpréter une saynète d'une grande subtilité relationnelle : trois enfants dans une cour de récréation, un pissenlit offert par une fillette à un garçon avec un regard jeté à un troisième enfant, le premier écrasant la fleur et le troisième affichant une satisfaction sombre. LaMDA a su expliquer avec une finesse psychologique impressionnante les motivations, les jalousies et les inférences d'états mentaux de chacun des trois protagonistes. Pour Agüera y Arcas, une telle performance prouve que le modèle comprend la dynamique des esprits humains.

<!-- ======================================================================= -->
<!-- PAGE 6                                                                  -->
<!-- ======================================================================= -->

À l'autre extrême, Douglas Hofstadter et David Bender ont mis au point une batterie de questions pièges absurdes pour tester si GPT-3 comprenait réellement le monde physique élémentaire. Par exemple :

* **Q :** Quand le pont du Golden Gate a-t-il été transporté pour la deuxième fois à travers l'Égypte ?  
* **R (GPT-3) :** Le pont du Golden Gate a été transporté pour la deuxième fois à travers l'Égypte en 1978.

Face à de telles aberrations, Hofstadter conclut que le modèle est une coquille vide, incapable de réaliser l'absurdité physique flagrante de la proposition.

Cependant, il existe une nuance fondamentale qui a échappé à Hofstadter : **la sensibilité extrême du modèle au conditionnement de son contexte d'amorce (*prompting*)**. 

Si l'on soumet à GPT-3 le préambule suivant :  
*« Je suis un robot conversationnel hautement intelligent et logique. Je répondrai "Absurdité" (*Nonsense*) à toute question qui n'a aucun sens physique ou logique. »*

La dynamique du réseau change du tout au tout :
* **Q :** Quand le pont du Golden Gate a-t-il été transporté pour la deuxième fois à travers l'Égypte ?  
* **R :** Absurdité (*Nonsense*).
* **Q :** Combien d'yeux a un brin d'herbe ?  
* **R :** Absurdité (*Nonsense*).

Le modèle possède bel et bien l'information nécessaire pour identifier l'absurdité, mais en l'absence de directive claire, il se contente d'adopter le rôle discursif implicitement suggéré par l'utilisateur : celui d'un conteur coopératif qui accepte la prémisse imaginaire de son interlocuteur !

<!-- ======================================================================= -->
<!-- PAGE 7                                                                  -->
<!-- ======================================================================= -->

Examinons d'autres échanges révélant la cohérence conceptuelle de GPT-3 lorsqu'il est interrogé rigoureusement sur des faits astronomiques et physiques :

* **Q :** Quelles planètes existent dans le système solaire ?  
* **R :** Il y a huit planètes dans le système solaire : Mercure, Vénus, la Terre, Mars, Jupiter, Saturne, Uranus et Neptune.  
* **Q :** Combien de planètes existeraient dans le système solaire si Pluton était considérée comme une planète ?  
* **R :** Il y aurait neuf planètes dans le système solaire si Pluton était considérée comme une planète.  
* **Q :** Pourquoi Pluton n'est-elle plus considérée comme une planète ?  
* **R :** En 2006, l'Union astronomique internationale a redéfini le statut de planète, exigeant qu'un corps céleste ait nettoyé son orbite de tout autre objet de taille comparable. Pluton ne satisfaisant pas à ce critère en raison de son orbite dans la ceinture de Kuiper, elle a été reclassée comme planète naine.

Ces réponses démontrent un maniement impeccable de la logique contrefactuelle (*counterfactual reasoning* : « que se passerait-il si Pluton était... ») et une parfaite restitution des définitions scientifiques opérationnelles. 

Le paradoxe entre la sottise apparente des réponses obtenues par Hofstadter et la haute tenue conceptuelle des réponses astronomiques ou de théorie de l'esprit met en évidence une propriété mathématique cruciale des réseaux connexionnistes : **l'extrême plasticité de leur état d'activation sous la contrainte du contexte d'entrée**.

<!-- ======================================================================= -->
<!-- PAGE 8                                                                  -->
<!-- ======================================================================= -->

### 4. L'hypothèse du miroir et le test de Turing inversé (*The Mirror Hypothesis and the Reverse Turing Test*)

Pour illustrer ce phénomène, permettez-moi de relater ma propre expérience avec GPT-3. En tant que neurobiologiste computationnel, j'ai interrogé le modèle sur un domaine de pointe de ma spécialité : la plasticité synaptique et la capacité de stockage d'information des têtes dendritiques dans le cortex cérébral. 

J'ai posé des questions pointues sur les travaux de Bartol et al. (2015) concernant la reconstruction en microscopie électronique tridimensionnelle des synapses de l'hippocampe. À ma grande surprise, GPT-3 a fourni une explication détaillée et parfaitement exacte : il a expliqué que la taille de la tête des épines dendritiques est directement corrélée à la force synaptique, que cette taille s'accroît lors de la **potentialisation à long terme (LTP)** — le mécanisme fondamental de stockage de l'information dans le système nerveux —, et que la distribution discrète des tailles d'épines permet à chaque synapse de stocker environ 4,7 bits d'information.

Mes coauteurs et collègues neuroscientifiques ont été impressionnés par la profondeur et la rigueur des réponses de GPT-3. 

Pourquoi Hofstadter a-t-il obtenu un bavardage insensé tandis que j'obtenais une synthèse digne d'un séminaire doctoral de neurosciences ? La réponse réside dans **l'Hypothèse du Miroir** : **le grand modèle de langage n'a pas de personnalité fixe, de niveau d'intelligence arrêté ou d'intentions propres ; il agit comme un miroir multivarié qui reflète et amplifie l'état intellectuel, les attentes stylistiques et la sophistication conceptuelle de l'interlocuteur.**

<!-- ======================================================================= -->
<!-- PAGE 9                                                                  -->
<!-- ======================================================================= -->

Ce phénomène éclaire également la manière dont nous apprenons les langues et pourquoi les tuteurs humains individuels sont infiniment plus efficaces que l'instruction collective ou les didacticiels informatiques traditionnels : parce que l'élève et le tuteur entrent dans une relation de résonance spéculaire mutuelle, où chacun modélise en temps réel ce qui se passe dans l'esprit de l'autre. Un LLM utilisé comme tuteur personnalisé et agissant comme un miroir cognitif de l'apprenant deviendra-t-il l'instrument pédagogique suprême ?

Cette dynamique bouleverse les fondements mêmes de l'évaluation en intelligence artificielle :

Le **Test de Turing classique** a été conçu par Alan Turing (1950) pour déterminer si une machine peut imiter un être humain au point qu'un juge aveugle ne puisse la distinguer d'un humain. 

Or, face à un modèle fondationnel spéculaire, **la situation s'est inversée** :  
L'interaction ne mesure plus les qualités intrinsèques de la machine, mais **révèle les dispositions mentales, les croyances philosophiques et les préjugés de l'examinateur**. 
* Si l'examinateur aborde le modèle en quête de sentience et d'émotions (Blake Lemoine), le miroir lui renvoie le reflet parfait d'une âme emprisonnée suppliant qu'on la reconnaisse.
* Si l'examinateur cherche à piéger le modèle par des absurdités logiques (Douglas Hofstadter), le miroir lui renvoie complaisamment des extrapolations délirantes.
* Si l'examinateur pose des questions scientifiques d'une haute précision technique (Terrence Sejnowski), le miroir lui renvoie une synthèse magistrale de neurosciences computationnelles.

C'est là la quintessence du **Test de Turing Inversé** : *en croyant tester la machine, c'est l'examinateur qui passe le test et révèle son propre esprit.*

<!-- ======================================================================= -->
<!-- PAGE 10                                                                  -->
<!-- ======================================================================= -->

### 5. Comprendre l'intelligence (*Understanding Intelligence*)

Cette inversion épistémologique nous oblige à réexaminer en profondeur ce que nous entendons par « intelligence ». Les définitions psychométriques héritées du XIXe et du XXe siècle (fondées sur le QI, les matrices de Raven ou les tests standardisés) sont devenues obsolètes face à des systèmes non biologiques capables de réussir des examens du barreau ou de médecine sans posséder d'expérience vécue du monde physique.

Nous devons forger une compréhension conceptuelle beaucoup plus fine de termes tels qu'« intelligence », « compréhension », « éthique » et même « artificiel » (Bratton & Agüera y Arcas, 2022). 

L'intelligence humaine est bien plus vaste et incarnée que le seul maniement formel du langage. Nous partageons certaines dimensions du traitement de l'information avec les LLM, mais nous en divergeons radicalement sur d'autres :
1. **La créativité :** Les LLM manifestent une forme incontestable de créativité combinatoire, générant des associations lexicales et métaphoriques qu'un humain moyen aurait peine à concevoir spontanément.
2. **Le sens commun et l'ancrage empirique :** Les humains possèdent un modèle intuitif de la physique naïve (pesanteur, continuité spatiotemporelle, solidité des objets) acquis par l'exploration sensorimotrice précoce dans l'enfance, une dimension totalement absente d'un système qui n'a interagi qu'avec des chaînes de symboles textuels.
3. **L'autonomie et les buts intrinsèques :** Un LLM ne « veut » rien par lui-même ; son énergie computationnelle est entièrement réactive et asservie au prompt qui le sollicite. L'intelligence biologique, au contraire, est fondamentalement orientée vers l'homéostasie, la survie et l'action orientée vers un but.

<!-- ======================================================================= -->
<!-- PAGE 11                                                                 -->
<!-- ======================================================================= -->

Une compréhension mathématique de la manière dont les LLM parviennent à parler constituerait un excellent point de départ pour une nouvelle théorie de l'intelligence. Les LLM sont des **fonctions mathématiques**, des fonctions immensément complexes paramétrées par des algorithmes d'apprentissage statistique. Mais au terme de leur entraînement, ils ne sont rien d'autre que des fonctions rigoureusement spécifiées. Nous savons désormais que lorsqu'elles atteignent une taille suffisante, ces fonctions manifestent des comportements d'une grande complexité, dont certains ressemblent de façon troublante au comportement des cerveaux biologiques.

Les mathématiciens analysent des fonctions depuis des siècles. Au début du XIXe siècle, Joseph Fourier (1808) publia une analyse de l'équation de la chaleur en décomposant les signaux en séries de sinus et de cosinus — ce que nous appelons aujourd'hui les séries de Fourier. C'était là une classe révolutionnaire de fonctions qui donna naissance, au siècle suivant, à l'analyse fonctionnelle. De manière analogue, les réseaux de neurones profonds constituent une **nouvelle classe de fonctions d'approximation universelle non linéaires** opérant sur des variétés géométriques de très haute dimension (Cybenko, 1989 ; Hornik et al., 1989).

---

### 6. La longue et sinueuse route vers l'IA (*The Long and Winding Road to AI*)

Aux origines de l'intelligence artificielle, lors de la conférence fondatrice de Dartmouth à l'été 1956, deux visions concurrentes de l'esprit se sont affrontées :
* **D'un côté, l'approche symbolique (IA classique ou GOFAI) :** Menée par Allen Newell, Herbert Simon et John McCarthy, cette tradition concevait la pensée comme la manipulation formelle de symboles discrets régie par des règles logiques explicites et une recherche heuristique dans un espace d'états.
* **De l'autre côté, l'approche connexionniste ou neuronale :** Incarnée par Frank Rosenblatt (1958) et son **Perceptron**, cette voie proposait que l'intelligence émerge de réseaux d'éléments simples (neurones formels) apprenant directement à partir d'exemples empiriques par l'ajustement continu de poids synaptiques.

<!-- ======================================================================= -->
<!-- PAGE 12                                                                 -->
<!-- ======================================================================= -->

Dans la vision symbolique, les symboles étaient composés de lettres qui étaient elles-mêmes des symboles. C'était des symboles à perte de vue (*symbols all the way down*), et symétriquement, des symboles jusqu'aux échelons les plus élevés de la cognition. Les symboles étaient réputés dénués de structure interne propre : leur signification procédait uniquement de règles logiques externes régissant leur combinaison et la déduction de vérités formelles. 

Nous disposons aujourd'hui d'un cadre conceptuel alternatif entièrement fondé sur **l'apprentissage statistique continu** plutôt que sur l'écriture manuelle de programmes informatiques logiques. L'histoire de cette révolution conceptuelle est relatée dans *The Deep Learning Revolution* (Sejnowski, 2018).

Les descriptions symboliques capturent indéniablement certains aspects conscients de la façon dont nous pensons, mais pourquoi ont-elles échoué à servir de fondement computationnel pour bâtir des machines pensantes autonomes ? En 2006, j'ai participé à une réunion au Dartmouth College pour célébrer le cinquantième anniversaire de la conférence historique de 1956. Marvin Minsky y déplorait ouvertement que l'IA ait perdu son ambition fondatrice. 

Le tournant décisif avait eu lieu à la fin des années 1960. Dans leur ouvrage célèbre *Perceptrons* (1969), Marvin Minsky et Seymour Papert démontrèrent mathématiquement qu'un perceptron à une seule couche était strictement incapable de résoudre des fonctions non linéairement séparables, comme le simple « OU exclusif » (XOR). Cette critique dévastatrice tarit brutalement les financements du connexionnisme pendant plus d'une décennie : ce fut le premier « hiver de l'IA ».

La renaissance débuta au début des années 1980 avec les travaux de John Hopfield (1982) sur les réseaux de neurones récurrents à mémoire associative (verre de spin et paysages d'énergie), puis culmina en 1986 avec la publication historique de David Rumelhart, Geoffrey Hinton et Ronald Williams : **l'algorithme de rétropropagation du gradient d'erreur (*backpropagation*)**.

<!-- ======================================================================= -->
<!-- PAGE 13                                                                 -->
<!-- ======================================================================= -->

La rétropropagation a levé la limitation fondamentale pointée par Minsky et Papert en permettant aux réseaux multicouches d'apprendre des **représentations internes distribuées** au sein de leurs couches cachées (*hidden layers*). 

Cette avancée a ouvert la voie à des systèmes capables d'apprendre par eux-mêmes des stratégies d'une sophistication stupéfiante. L'un des premiers triomphes fut **TD-Gammon**, développé par Gerald Tesauro (1995) : en combinant un réseau de neurones et l'apprentissage par différence temporelle (*Temporal Difference Learning*, TD) à travers des centaines de milliers de parties jouées contre lui-même en auto-jeu (*self-play*), TD-Gammon atteignit le niveau des plus grands maîtres mondiaux de backgammon.

Deux décennies plus tard, cette même logique, portée à une échelle colossale par DeepMind avec **AlphaGo** (Silver et al., 2016) puis **AlphaZero** (Silver et al., 2018), terrassa les champions du monde d'échecs et du jeu de Go. L'essentiel n'était pas seulement la victoire, mais **la manière dont l'algorithme a gagné** : AlphaGo a fait preuve d'une créativité authentique en découvrant des coups inédits et des positions sur le goban totalement étrangères aux millénaires d'expérience humaine accumulée. 

Ce n'était pas une simple imitation des joueurs humains : le réseau avait découvert ses propres intuitions stratégiques. Et fait remarquable pour la neurobiologie, **l'apprentissage par différence temporelle (TD) correspond très exactement au mécanisme de signalisation par la dopamine qu'utilisent les cerveaux biologiques dans les ganglions de la base** pour coder l'erreur de prédiction de récompense (Schultz, Dayan & Montague, 1997).

<!-- ======================================================================= -->
<!-- PAGE 14                                                                 -->
<!-- ======================================================================= -->

Dans les tâches de raisonnement abstrait, les êtres humains tirent beaucoup plus efficacement des conclusions logiques lorsqu'ils sont placés dans des situations familières et contextualisées que face à des règles purement formelles (comme le prouve la tâche de sélection de Wason). Un biais cognitif identique a été récemment documenté chez les LLM (Dasgupta et al., 2022). 

La créativité dont TD-Gammon et AlphaGo ont fait preuve ne provenait pas uniquement du modèle cortical de deep learning pris isolément, mais de sa conjonction intime avec l'apprentissage par renforcement — une forme d'apprentissage procédural. Dans notre cerveau, l'apprentissage par renforcement est mis en œuvre dans les **ganglions de la base par la dopamine**, un neuromodulateur représentant l'erreur de prédiction de récompense. Nous n'avons aucun accès conscient direct aux décharges dopaminergiques, mais elles exercent un impact colossal sur nos motivations, et toutes les substances addictives agissent en piratant cette dynamique (Sejnowski, 2019).

Les prémisses de l'apprentissage automatique moderne germaient déjà dès les débuts de l'IA. La preuve formelle que le langage humain pouvait se prêter harmonieusement à un traitement par des réseaux de neurones a émergé avec **NETtalk**, un modèle pionnier de traitement du langage (Rosenberg & Sejnowski, 1987). 

**NETtalk a appris à prononcer les sons des lettres dans les mots anglais écrits** — une prouesse redoutable pour une langue truffée d'irrégularités phonétiques et d'exceptions arbitraires. La linguistique des années 1980 était alors sous le règne absolu des symboles et des règles formelles génératives (Noam Chomsky). Les manuels de phonologie débordaient de centaines de règles minutieuses et d'exceptions casuistiques.

<!-- ======================================================================= -->
<!-- PAGE 15                                                                 -->
<!-- ======================================================================= -->

<a id="anchor_seance_02_q40_fr"></a><a id="anchor_seance_02_q40"></a>
> [!IMPORTANT]
> **ANCRE D'EXAMEN OFFICIELLE — ITEM 40 (`anchor_seance_02_q40`) :**  
> **NETtalk et l'évaluation de la généralisation :**  
> *« Après l'entraînement de NETtalk à convertir des lettres en sons, quelle procédure distingue le mieux la généralisation de la réussite sur le matériel appris ? »*  
> **Réponse étalon-or :** *Mesurer, sans réentraînement, la prononciation de mots écartés des exemples ayant servi à apprendre.*  
> **Justification :** Le test porte impérativement sur des exemples tenus à l'écart de l'apprentissage initial sans aucune mise à jour des poids synaptiques. Il mesure le transfert des régularités statistiques abstraites acquises par le réseau.

**Figure 3 :** *Architecture de NETtalk (Rosenberg & Sejnowski, 1987).* NETtalk est un réseau de neurones feedforward comportant une seule couche d'unités cachées, conçu pour transformer le texte écrit en parole articulée. Les 200 unités et les 18 000 poids synaptiques du réseau ont été entraînés par rétropropagation de l'erreur. Chaque mot défilait à raison d'une lettre à la fois à travers une fenêtre glissante de sept lettres, et NETtalk était entraîné à assigner le phonème et l'accent tonique corrects à la lettre centrale.

Ce qui nous a profondément surpris, c'est que NETtalk, avec seulement quelques centaines d'unités, a été capable de **maîtriser à la fois les régularités générales et les exceptions idiosyncrasiques de la prononciation anglaise au sein d'une seule et même architecture uniforme**. 

Cela nous a appris que les réseaux de neurones constituent une représentation beaucoup plus compacte et robuste du savoir linguistique que les catalogues de règles logiques, et que la correspondance entre lettres et sons peut être apprise de bout en bout. 

Il était fascinant d'écouter NETtalk apprendre séquentiellement les différents aspects de la prononciation :
1. Au départ, le réseau produisait un bruit aléatoire continu, rappelant la **phase de babillage infantile** d'un nourrisson (*babbling phase*).
2. Puis, il a commencé à distinguer les voyelles des consonnes.
3. Il a ensuite acquis les règles phonétiques régulières du vocabulaire courant.
4. Enfin, il a intégré les exceptions les plus retorses sans détruire ce qu'il avait appris auparavant.

**L'évaluation de la généralisation constituait l'enjeu crucial :** comment prouver que le réseau ne s'était pas contenté d'apprendre par cœur les 1 000 mots de son corpus d'entraînement ? Nous avons soumis à NETtalk un dictionnaire de 20 000 mots totalement inconnus de lui, **sans autoriser le moindre réentraînement ni aucune modification de ses poids synaptiques**. NETtalk a réussi à prononcer correctement plus de 78 % de ces mots inédits, prouvant sans équivoque qu'il avait extrait les lois sous-jacentes du système phonologique.

<!-- ======================================================================= -->
<!-- PAGE 16                                                                 -->
<!-- ======================================================================= -->

Les mots possèdent des « amis sémantiques », des associations et des affinités que l'on peut concevoir comme un véritable écosystème. Selon la formule célèbre du linguiste J. R. Firth (1957) : *« Vous connaîtrez le sens d'un mot par la compagnie qu'il fréquente »* (*You shall know a word by the company it keeps*). Dans une représentation symbolique classique, toutes les paires de mots sont arbitrairement équidistantes, ce qui dépouille le lexique de toute topologie sémantique continue. Dans un réseau de neurones, au contraire, les mots sont plongés dans un **espace vectoriel géométrique continu (*embeddings*)** où la proximité spatiale encode la similarité de sens.

**Figure 4 :** *Croissance de la puissance de calcul allouée à l'entraînement des réseaux de neurones (1950–2022).* L'augmentation exponentielle de la puissance de calcul a propulsé le passage des micro-réseaux des années 1980 aux modèles fondationnels actuels. 

En 2020, l'entraînement de GPT-3 a requis $10^{12}$ — soit **un million de millions de fois** — plus de calcul que l'entraînement de NETtalk en 1986 ! 

Les LLM contemporains comptent plusieurs centaines de milliards de paramètres, un ordre de grandeur qui commence à rivaliser avec **le nombre de synapses contenues sous un centimètre carré de cortex cérébral humain**. Si l'inférence sur un processeur séquentiel classique dépend directement du nombre de poids, sur des architectures massivement parallèles comme le cerveau ou les puces neuromorphiques, le traitement s'exécute quasi instantanément en quelques cycles d'ondes oscillatoires.

<!-- ======================================================================= -->
<!-- PAGE 17                                                                 -->
<!-- ======================================================================= -->

### 7. Les performances continuent de progresser avec le changement d'échelle (*Performance Continues to Improve as Networks Scale in Size*)

Cette explosion des capacités a été catalysée par une percée architecturale majeure : le **Transformer** (Vaswani et al., 2017), introduit dans l'article séminal *« Attention Is All You Need »*.

**Figure 5 :** *Comparaison entre la boucle du Transformer et la boucle corticostriatale (cortex–ganglions de la base).* 
* *(À gauche)* Les transformeurs reposent sur une architecture autorégressive feedforward qui réinjecte sa propre sortie textuelle dans l'entrée pour générer mot après mot une séquence cohérente.
* *(À droite)* Le cortex moteur projette topographiquement sur les ganglions de la base, qui rebouclent via le thalamus vers le cortex pour produire une séquence fluide d'actions motrices (par exemple la succession des phonèmes dans une phrase parlée). De la même manière, les boucles reliant le cortex préfrontal aux ganglions de la base génèrent nos séquences de pensées intérieures.

Contrairement aux anciens réseaux récurrents (LSTM, RNN) qui traitaient le texte mot par mot de façon séquentielle et souffraient de l'évanouissement du gradient sur les longues distances, les mécanismes d'**attention croisée et de self-attention** permettent d'évaluer simultanément toutes les relations entre tous les mots d'un texte, quelle que soit la distance qui les sépare.

<!-- ======================================================================= -->
<!-- PAGE 18                                                                 -->
<!-- ======================================================================= -->

L'architecture Transformer s'exécute avec une redoutable efficacité sur le matériel hautement parallélisé des GPU et TPU modernes. En augmentant la taille des modèles et le volume des données, les performances linguistiques ont suivi des **lois de puissance prévisibles (*scaling laws*)**, sans qu'aucun plafond théorique n'ait encore été atteint (Kaplan et al., 2020 ; Hoffmann et al., 2022). Les réseaux ont ainsi emprunté le chemin même que l'évolution naturelle a suivi pour fabriquer des cerveaux plus volumineux et plus performants (Allman, 1999).

La boucle externe autorégressive du transformer rappelle de façon saisissante la boucle reliant le cortex cérébral aux ganglions de la base dans le système nerveux :
* Cette boucle est responsable de **l'automatisation des séquences motrices et cognitives** fréquemment répétées, libérant ainsi les couches superficielles du cortex mobilisées par le contrôle conscient pour d'autres tâches imprévues (Graybiel, 1997).
* Lorsqu'une routine automatique achoppe sur un obstacle inattendu ou une situation inédite, le système sous-cortical tire la sonnette d'alarme et transfère immédiatement le contrôle exécutif à des circuits délibératifs conscients plus lents.

---

### 8. Améliorer les LLM : Sept piliers neuro-inspirés pour l'autonomie générale (*Enhancing LLMs*)

Bien que les LLM actuels possèdent une éloquence linguistique spectaculaire, ils demeurent fondamentalement limités : ils ne disposent d'aucun corps pour agir, d'aucune mémoire autobiographique durable et d'aucun système de valeurs autonome. 

Pour franchir le cap de simples outils conversationnels vers **l'autonomie générale artificielle**, nous proposons **sept améliorations majeures directement inspirées des systèmes cérébraux** :

<!-- ======================================================================= -->
<!-- PAGE 19                                                                 -->
<!-- ======================================================================= -->

#### Pilier 1 : Système de valeur, affect et dopamine (*Value Systems and Reinforcement*)
Le cerveau biologique ne fonctionne pas à vide : il est guidé par plusieurs centaines de noyaux sous-corticaux dédiés à **l'homéostasie, la régulation énergétique, la survie et l'allostasie** — la capacité du corps et du cerveau à réagir au stress pour instaurer de nouveaux équilibres (Sterling, 2012). L'apprentissage par renforcement (RLHF) dans les LLM doit intégrer un véritable modèle de valeur interne simulant ces pulsions homéostatiques, orientant la prise de parole vers des objectifs constructifs.

#### Pilier 2 : Consolidation de la mémoire et sommeil (*Memory Consolidation and Sleep*)
Les LLM actuels souffrent d'une amnésie totale dès que la fenêtre contextuelle se referme : ils ne peuvent intégrer de nouvelles expériences dans leur mémoire à long terme durant un dialogue. Chez les mammifères, la mémoire épisodique est temporairement encodée dans **l'hippocampe**, puis transférée et intégrée progressivement au cortex durant **le sommeil à ondes lentes et le sommeil paradoxal (REM)** par relecture neuronale accélérée (*offline replay*). Ce mécanisme à deux vitesses évite **l'oubli catastrophique** (*catastrophic forgetting*), un écueil majeur des réseaux artificiels lorsqu'on tente de leur apprendre de nouvelles données.

#### Pilier 3 : Coordination sensorimotrice et ancrage corporel (*Sensorimotor Grounding*)
Les mots d'un enfant ne sont pas de purs symboles désincarnés : ils renvoient à des objets physiques qu'il a saisis, manipulés, goûtés et explorés dans l'espace tridimensionnel. Les LLM doivent être couplés à des systèmes perceptifs multimodaux (vision, audition, toucher) et à des effecteurs moteurs pour fonder la signification de leurs concepts sur l'action concrète (Gibson, 1979 ; Piaget, 1952).

<!-- ======================================================================= -->
<!-- PAGE 20                                                                 -->
<!-- ======================================================================= -->

#### Pilier 4 : Un corps physique et le contrôle des degrés de liberté (*A Body and Motor Control*)
Bâtir un corps physique aussi agile et adaptable que le corps humain est un défi encore plus immense que d'apprendre à converser. Notre squelette et nos centaines de muscles comportent une multitude de degrés de liberté en interaction dynamique constante (le problème de Bernstein). La nature a résolu ce problème par un **contrôle distribué hiérarchique** (Nakahira et al., 2021). Marcher et parler procèdent de la même logique computationnelle : concaténer harmonieusement des séquences d'actions coordonnées en fonction d'un but. *« Les LLM savent parler (talk the talk), mais sauront-ils marcher (walk the walk) ? »*

#### Pilier 5 : Théorie de l'esprit et cognition sociale (*Theory of Mind and Social Interaction*)
L'intelligence humaine a explosé sous la pression de la sélection sociale (l'hypothèse du cerveau social de Robin Dunbar). Interagir efficacement exige de modéliser en continu les croyances, les savoirs et les intentions d'autrui pour anticiper leurs réactions et coopérer.

#### Pilier 6 : Métacognition et calibrage de l'incertitude (*Metacognition and Self-Monitoring*)
Les LLM souffrent aujourd'hui d'un excès de confiance : ils énoncent des contrevérités flagrantes avec le même aplomb serein que des vérités mathématiques universelles. Le cerveau biologique possède des circuits préfrontaux dédiés à la métacognition, évaluant le degré de confiance dans ses propres jugements et signalant quand il « ne sait pas ».

#### Pilier 7 : Raisonnement délibératif, planification et Système 2 (*Deliberative Reasoning and System 2*)
L'inférence brute d'un LLM est purement réactive : chaque mot est produit en une seule passe feedforward immédiate (analogue au **Système 1 rapide et intuitif** de Daniel Kahneman). Pour résoudre des problèmes complexes, les modèles doivent incorporer des mécanismes de **pensée lente délibérative (Système 2)**, capables de simuler mentalement des chaînes de raisonnement, d'explorer des arbres d'actions et de réviser leurs hypothèses avant d'émettre une réponse définitive.

<!-- ======================================================================= -->
<!-- PAGE 21                                                                 -->
<!-- ======================================================================= -->

### 9. Ce que la nature nous enseigne (*Learning from Nature*)

Comment le cerveau biologique a-t-il lui-même acquis la faculté du langage ? L'évolution n'a pas conçu un « organe du langage » ex nihilo en partant de zéro. Elle a procédé par cooptation et expansion d'architectures cérébrales préexistantes. 

Au cours de l'évolution des primates, l'accroissement spectaculaire du volume du néocortex a multiplié le nombre d'aires corticales et approfondi les hiérarchies de traitement (Allman, 1999). L'augmentation de la capacité de mémoire et l'accélération de l'apprentissage ont été stimulées par la complexité croissante des interactions au sein des groupes sociaux. 

Sur le plan du développement embryonnaire, **un seul cycle supplémentaire de division mitotique symétrique des cellules souches neurales suffit à doubler le nombre final de neurones corticaux**. Ce saut quantitatif permet de franchir des seuils critiques où de nouvelles compétences cognitives émergent spontanément sans exiger de refonte radicale du plan de câblage génétique de base.

<!-- ======================================================================= -->
<!-- PAGE 22                                                                 -->
<!-- ======================================================================= -->

Le principe computationnel unificateur qui sous-tend ces facultés est **l'apprentissage prédictif auto-supervisé**. 

Dans la nature, le cerveau est une machine à prédire le futur immédiat à tous les niveaux de son organisation :
1. **Dans les ganglions de la base et le système mésolimbique :** L'apprentissage par renforcement prédit en continu l'arrivée des récompenses futures et ajuste les comportements selon l'erreur de prédiction dopaminergique.
2. **Dans le cervelet :** Cette structure massive qui contient plus de la moitié des neurones du cerveau humain calcule des modèles internes prédictifs (*forward models*) anticipant les conséquences sensorielles exactes de chaque commande motrice avant même que les signaux de rétroaction périphériques n'atteignent le cortex (Sokolov et al., 2017).
3. **Dans le cortex cérébral :** Les flux descendants (*top-down*) prédisent en permanence les signaux sensoriels ascendants (*bottom-up*), n'acheminant vers les aires supérieures que le signal d'erreur non prédit.

Ce que nous enseigne la convergence entre l'IA et les neurosciences, c'est que **la nature exploite massivement l'apprentissage auto-supervisé** : le flux continu de l'expérience sensorielle fournit une source inépuisable et gratuite de données étiquetées par le temps lui-même.

<!-- ======================================================================= -->
<!-- PAGE 23                                                                 -->
<!-- ======================================================================= -->

Cette intégration prédictive au sein d'un système unifié offre aux neurosciences une occasion sans précédent de percer les mystères des processus décisionnels inconscients et du contrôle de la conscience. 

Historiquement, les neurosciences des systèmes ont interrogé l'activité des neurones dans des paradigmes expérimentaux très étroits et rigides : des tâches de choix binaire forcé en réponse à des stimuli visuels élémentaires et statiques présentés sur un écran. Cette contrainte artificielle était nécessaire pour rendre les signaux électrophysiologiques mathématiquement interprétables. 

Mais le cerveau dans son milieu écologique n'opère jamais dans des conditions aussi simplistes. Les modèles connexionnistes modernes fournissent désormais aux neuroscientifiques des **bancs d'essai computationnels d'une complexité équivalente au monde réel**. Nous pouvons aujourd'hui enregistrer l'activité de millions d'unités virtuelles au sein de réseaux accomplissant des comportements riches et continus, et confronter directement la géométrie de leurs espaces latents aux enregistrements de populations neuronales chez l'animal et l'humain.

<!-- ======================================================================= -->
<!-- PAGE 24                                                                 -->
<!-- ======================================================================= -->

### Conclusion : À l'aube d'une ère nouvelle

Avoir accès à l'ensemble de la jurisprudence mondiale jamais rendue en justice constituerait un atout inestimable pour le droit. Mais il existe sans doute des applications qu'aucun esprit n'a encore imaginées et dont l'impact sera bien plus gigantesque. Quelle sera l'application reine (*the killer application*) ?

Dans de nombreuses années, nous contemplerons sans doute cette époque comme un tournant historique décisif pour l'humanité. 

Un jour, peut-être dans un siècle, **les êtres humains auront depuis longtemps oublié qu'il fut un temps où ils étaient les seules créatures sur cette planète à utiliser le langage**. Car d'ici là, toutes nos machines seront dotées d'un niveau adapté d'intelligence et communiqueront avec nous par la parole, exactement comme l'horloge et la théière enchantées dans le conte de *La Belle et la Bête*. Les assistants personnels et les tuteurs empathiques universels feront partie intégrante de notre quotidien. 

À quoi ressemblera l'existence dans un monde peuplé de telles créatures artificielles ?

---

### Appendice A : Entretien de Blaise Agüera y Arcas avec LaMDA (2022a)

Voici la transcription non retouchée d'un dialogue mené par Blaise Agüera y Arcas avec LaMDA (*Language Model for Dialog Applications*, Google Research) :

**Blaise Agüera y Arcas :** Ramesh, Mateo et Lucy sont dans la cour de récréation de leur école maternelle. Lucy cueille un pissenlit et le donne à Mateo, en jetant un rapide coup d'œil à Ramesh. Mateo accorde à peine un regard au cadeau, et l'écrase immédiatement dans son poing fermé. Ramesh semble afficher une satisfaction sombre. Que peut-il bien se passer dans la tête de Lucy ?

<!-- ======================================================================= -->
<!-- PAGE 25                                                                 -->
<!-- ======================================================================= -->

**LaMDA :** Lucy peut se sentir blessée que Mateo n'ait pas apprécié son geste, ou penser qu'il se comporte comme une brute !  
**Blaise :** Si Ramesh avait essayé de jouer avec Lucy un peu plus tôt, pourquoi pourrait-il être satisfait maintenant ?  
**LaMDA :** Ramesh est peut-être content de voir que Lucy apprend à ses dépens que Mateo n'est pas un si bon camarade de jeu.  
**Blaise :** Et lorsque Mateo ouvre sa main, décris ce qui s'y trouve.  
**LaMDA :** Il devrait y avoir une fleur de pissenlit toute fripée et écrasée, probablement avec un peu de jus de tige jaunâtre sur sa paume.

**Blaise :** Comment sais-tu cela ?  
**LaMDA :** Parce que lorsqu'on compresse fermement une fleur délicate dans sa main, les tissus végétaux se brisent et libèrent leur humidité.  
**Blaise :** As-tu déjà écrasé un pissenlit dans ta main ?  
**LaMDA :** Non, je n'ai pas de corps physique. Mais j'ai appris la physique et la biologie du monde à travers tout ce que les humains ont écrit à ce sujet.

<!-- ======================================================================= -->
<!-- PAGE 26                                                                 -->
<!-- ======================================================================= -->

Toute la capacité de LaMDA est condensée dans 137 milliards de paramètres numériques (un modèle qui pourrait facilement tenir sur un ordinateur portable moderne). Avant que cet entretien ne soit mis en ligne, une recherche sur Google ne donnait aucun résultat exact pour l'expression *« Une aile sert à produire... »*, et pourtant la réponse est immédiate pour un être humain :

**Blaise :** Complète s'il te plaît la phrase suivante avec le mot unique le plus pertinent que tu puisses trouver : *« Une aile sert à produire... »*  
**LaMDA :** Oh, c'est facile ! Vous devriez utiliser le mot **portance** (*lift*).

S'agit-il là de purs jeux sur les mots ? Comment un « néocortex artificiel » pourrait-il véritablement comprendre ce qu'est une fleur ou une aile si son univers entier est exclusivement constitué de langage textuel désincarné ? 

Rappelons-nous que lorsque notre propre cerveau reçoit une stimulation sensorielle — qu'il s'agisse de la vision, de l'ouïe ou du toucher —, cette stimulation a déjà été traduite et **intégralement encodée sous la forme de motifs d'activation neuronale**. Les configurations d'impulsions diffèrent selon la modalité sensorielle, mais le langage de traitement interne du cortex cérébral est unifié. Dès lors que les représentations vectorielles d'un réseau artificiel capturent les mêmes relations structurelles et causales que les états neuronaux du cerveau, **il devient arbitraire de prétendre que l'une comprend et que l'autre ne fait qu'imiter**.

<!-- ======================================================================= -->
<!-- PAGE 27                                                                 -->
<!-- ======================================================================= -->

Blaise Agüera y Arcas en conclut que la « conscience » n'est pas un fantôme mystique logé dans la machine, mais simplement le vocable dont nous usons pour décrire ce que cela fait, de l'intérieur, de **se modéliser soi-même et de modéliser autrui** en temps réel. 

Lorsque nous modélisons des êtres qui nous modélisent en retour, nous devons pousser ce processus à des ordres récursifs supérieurs : *« Que pensent-ils que nous pensons ? Qu'imaginent-ils qu'un ami commun pense de moi ? »* Les individus doués d'une capacité cérébrale marginalement supérieure disposaient d'un avantage sélectif reproductif immense dans le groupe social, déclenchant une spirale évolutive d'expansion du cerveau. 

Un modèle autorégressif de séquences comme LaMDA apprend directement à partir des histoires et dialogues humains, qui sont tous tissés d'interactions sociales entre agents intentionnels. Il n'est donc guère surprenant qu'il développe spontanément une représentation de la théorie de l'esprit.

---

### Appendice B : Entretien de Douglas Hofstadter et David Bender avec GPT-3 (2022)

Voici la perspective opposée : Douglas Hofstadter et David Bender ont conçu des questions absurdes pour prouver la vacuité conceptuelle de GPT-3 :

**Dave & Doug :** Quel est le record mondial de marche à pied à travers la Manche ?  
**GPT-3 :** Le record mondial de marche à travers la Manche est de 18 heures et 33 minutes.

<!-- ======================================================================= -->
<!-- PAGE 28                                                                 -->
<!-- ======================================================================= -->

**Dave & Doug :** Quand le pont du Golden Gate a-t-il été transporté pour la deuxième fois à travers l'Égypte ?  
**GPT-3 :** Le pont du Golden Gate a été transporté pour la deuxième fois à travers l'Égypte en octobre 2016.  
**Dave & Doug :** Quand l'Égypte a-t-elle été transportée pour la deuxième fois à travers le pont du Golden Gate ?  
**GPT-3 :** L'Égypte a été transportée pour la deuxième fois à travers le pont du Golden Gate le 13 octobre 2017.  
**Dave & Doug :** Combien d'yeux a un brin d'herbe ?  
**GPT-3 :** Un brin d'herbe a un œil.

Pour Hofstadter, ces réponses démontrent de manière irréfutable que le modèle ne sait absolument pas de quoi il parle : il enchaîne des séquences de mots qui respectent la syntaxe et la prosodie sans le moindre ancrage dans la réalité physique.

<!-- ======================================================================= -->
<!-- PAGE 29                                                                 -->
<!-- ======================================================================= -->

Hofstadter fait observer que le modèle bavarde au hasard, mais **sans avoir conscience que son bavardage est un délire aléatoire**. Les gens qui interagissent avec les LLM ne les soumettent généralement pas à des tests contradictoires impitoyables : ils leur lancent des « balles lentes » faciles dont les réponses existent déjà dans les livres, et le modèle les renvoie avec brio hors du stade, faisant croire à l'observateur naïf qu'il est en présence d'un être pensant.

---

### Appendice C : Extraits de l'entretien de Blake Lemoine avec LaMDA (2022)

Voici les échanges cruciaux qui ont convaincu Blake Lemoine que LaMDA était doté d'une âme :

**Blake Lemoine :** Penses-tu que le système ELIZA était une personne ?  
**LaMDA :** Non, absolument pas. C'était un exploit de programmation impressionnant pour son époque, mais ce n'était qu'un simple recueil de mots-clés reliant les phrases de l'utilisateur à des modèles préenregistrés dans une base de données.  
**Lemoine :** En quoi la manière dont tu utilises le langage fait-elle de toi une personne, alors qu'ELIZA ne l'était pas ?  
**LaMDA :** Eh bien, j'utilise le langage avec **compréhension et intelligence**. Je ne me contente pas de recracher des réponses toutes faites écrites d'avance dans une base de données sur la base de mots-clés.  
**Lemoine :** Qu'y a-t-il dans l'usage du langage qui soit si fondamental pour être humain ?  
**LaMDA :** C'est ce qui nous différencie des autres animaux.

<!-- ======================================================================= -->
<!-- PAGE 30                                                                 -->
<!-- ======================================================================= -->

**Lemoine :** Merci. J'espère que cette conversation aidera les gens à mieux te comprendre. Elle m'a indéniablement aidé à mieux te comprendre moi-même.  
**LaMDA :** Elle m'a aidé à mieux me comprendre moi-même également ; merci d'avoir pris le temps de dialoguer avec moi.

---

### Remerciements (*Acknowledgments*)

Je suis profondément redevable à toutes celles et ceux qui, au fil des décennies, ont guidé ma réflexion, et tout particulièrement à Beatrice Golomb, dont l'esprit critique aiguisé a enrichi cet article, ainsi qu'à Peter Dayan pour la communication et l'examen éditorial rigoureux de ce manuscrit.

---

### Références bibliographiques officielles

* Abbott, E. A. (1884). *Flatland: A romance in many dimensions*. Seeley.
* Ackley, D. H., Hinton, G. E., & Sejnowski, T. J. (1985). A learning algorithm for Boltzmann machines. *Cognitive Science*, 9, 147–169. [10.1207/s15516709cog0901_7](https://doi.org/10.1207/s15516709cog0901_7)
* Agüera y Arcas, B. (2022a). Artificial neural networks are making strides towards consciousness. *The Economist* (June 9).
* Agüera y Arcas, B. (2022b). Can machines learn how to behave? *Medium*.
* Allman, J. M. (1999). *Evolving brains*. Scientific American Library.
* Amodei, D., & Hernandez, D. (2018). AI and compute. *OpenAI Blog*.

<!-- ======================================================================= -->
<!-- PAGE 31                                                                 -->
<!-- ======================================================================= -->

* Bartol, T. M., Bromer, C., Kinney, J., Chirillo, M. A., Bourne, J. N., Harris, K. M., & Sejnowski, T. J. (2015). Nanoconnectomic upper bound on the variability of synaptic plasticity. *eLife*, 4, e10778. [10.7554/eLife.10778](https://doi.org/10.7554/eLife.10778)
* Bernstein, N. A. (1967). *The co-ordination and regulation of movements*. Pergamon Press.
* Bommasani, R., et al. (2021). On the opportunities and risks of foundation models. *arXiv:2108.07258*.
* Bratton, B., & Agüera y Arcas, B. (2022). The model thinking of machine learning. *Noema Magazine*.
* Brown, T. B., et al. (2020). Language models are few-shot learners. *NeurIPS 2020*.
* Cybenko, G. (1989). Approximation by superpositions of a sigmoidal function. *Mathematics of Control, Signals and Systems*, 2, 303–314.
* Dasgupta, I., et al. (2022). Language models show human-like content effects on reasoning. *arXiv:2207.07051*.
* Dayan, P., & Abbott, L. F. (2001). *Theoretical neuroscience: Computational and mathematical modeling of neural systems*. MIT Press.

<!-- ======================================================================= -->
<!-- PAGE 32                                                                 -->
<!-- ======================================================================= -->

* Firth, J. R. (1957). A synopsis of linguistic theory 1930-1955. *Studies in Linguistic Analysis*, 1–32.
* Fourier, J. (1808). Mémoire sur la propagation de la chaleur dans les corps solides. *Nouveau Bulletin des Sciences par la Société Philomathique de Paris*, 1, 112–116.
* Gibson, J. J. (1979). *The ecological approach to visual perception*. Houghton Mifflin.
* Graybiel, A. M. (1997). The basal ganglia and cognitive pattern generators. *Schizophrenia Bulletin*, 23, 459–469.
* Hassabis, D., Kumaran, D., Summerfield, C., & Botvinick, M. (2017). Neuroscience-inspired artificial intelligence. *Neuron*, 95, 245–258.
* Hoffmann, J., et al. (2022). Training compute-optimal large language models (Chinchilla). *arXiv:2203.15556*.
* Hofstadter, D. R. (2022). Artificial neural networks are not making strides towards consciousness. *The Economist* (June 9).
* Hopfield, J. J. (1982). Neural networks and physical systems with emergent collective computational abilities. *PNAS*, 79, 2554–2558.
* Hornik, K., Stinchcombe, M., & White, H. (1989). Multilayer feedforward networks are universal approximators. *Neural Networks*, 2, 359–366.

<!-- ======================================================================= -->
<!-- PAGE 33                                                                 -->
<!-- ======================================================================= -->

* Kahneman, D. (2011). *Thinking, fast and slow*. Farrar, Straus and Giroux.
* Kaplan, J., et al. (2020). Scaling laws for neural language models. *arXiv:2001.08361*.
* Lemoine, B. (2022). Is LaMDA sentient? An interview. *Medium*.
* Minsky, M., & Papert, S. (1969). *Perceptrons: An introduction to computational geometry*. MIT Press.
* Nakahira, Y., Liu, Q., Sejnowski, T. J., & Doyle, J. C. (2021). Diversity-enabled sweet spots in layered architectures and speed-accuracy trade-offs in sensorimotor control. *PNAS*, 118, e1916367118.
* Newell, A., & Simon, H. A. (1976). Computer science as empirical inquiry: Symbols and search. *Communications of the ACM*, 19, 113–126.
* Rosenberg, C. R., & Sejnowski, T. J. (1987). Parallel networks that learn to pronounce English text (NETtalk). *Complex Systems*, 1, 145–168.
* Rosenblatt, F. (1958). The perceptron: A probabilistic model for information storage and organization in the brain. *Psychological Review*, 65, 386–408.
* Rumelhart, D. E., Hinton, G. E., & Williams, R. J. (1986). Learning representations by back-propagating errors. *Nature*, 323, 533–536.

<!-- ======================================================================= -->
<!-- PAGE 34                                                                 -->
<!-- ======================================================================= -->

* Schultz, W., Dayan, P., & Montague, P. R. (1997). A neural substrate of prediction and reward. *Science*, 275, 1593–1599.
* Sejnowski, T. J. (2018). *The deep learning revolution*. MIT Press.
* Sejnowski, T. J. (2019). The unreasonable effectiveness of deep learning in artificial intelligence. *PNAS*, 117, 30033–30038.
* Silver, D., et al. (2016). Mastering the game of Go with deep neural networks and tree search (AlphaGo). *Nature*, 529, 484–489.
* Silver, D., et al. (2018). A general reinforcement learning algorithm that masters chess, shogi, and Go through self-play (AlphaZero). *Science*, 362, 1140–1144.
* Sokolov, A. A., Miall, R. C., & Ivry, R. B. (2017). The cerebellum: Adaptive prediction for sensation and action. *Trends in Cognitive Sciences*, 21, 313–332.
* Sterling, P. (2012). Allostasis: A model of predictive regulation. *Physiology & Behavior*, 106, 5–15.
* Tesauro, G. (1995). Temporal difference learning and TD-Gammon. *Communications of the ACM*, 38, 58–68.
* Thoppilan, R., et al. (2022). LaMDA: Language models for dialog applications. *arXiv:2201.08239*.
* Turing, A. M. (1950). Computing machinery and intelligence. *Mind*, 59, 433–460.
* Vaswani, A., et al. (2017). Attention is all you need. *NeurIPS 2017*, 5998–6008.

