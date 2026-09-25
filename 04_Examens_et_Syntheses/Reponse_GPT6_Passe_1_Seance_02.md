Conclusion de cette première passe

Le bloc ne permet pas de déclarer la séance 2 « validée ». Q13 porte sur une notion réelle, mais ne couvre pas le problème organisateur du cours. Q14 transforme une propriété logique conditionnelle en garantie générale. Q15 confond effectivement activations, poids et adresse mémoire. Q16 transforme une propriété possible en garantie universelle de robustesse.

J’ai examiné les quatre questions et les rétroactions supplémentaires de la réponse brute, en les confrontant au GOLD, aux lectures originales, au référentiel et à la transcription des diapositives. Les remarques ci-dessous concernent cette livraison, pas d’éventuelles questions présentes dans d’autres blocs.

Télécharger le dossier d’audit — preuves, corrections minimales et questions candidates

1. Audit des questions 13 à 16
Q13 — L’intentionnalité est correctement définie, mais ne résume pas le problème présenté au cours

La réponse A est correcte pour une question portant spécifiquement sur le problème sémantique. Haugeland examine bien comment des mécanismes physiques peuvent manipuler des représentations signifiantes. Sa note 8 définit l’intentionnalité par le fait de porter sur quelque chose ou d’avoir une signification. Il n’y a donc aucune raison de déclarer cette notion fausse. 

Haugeland (1981) - Semantic Eng… +1

Le problème est l’équivalence exclusive proposée dans le conseil d’examen entre le « problème classique de la cognition » et l’intentionnalité. Dans le GOLD, l’introduction s’organise autour du défi cartésien : productivité du langage et adaptation générale, puis possibilité d’une infinité de représentations. Une question sur le sens ne remplace pas une question sur ces capacités. 
GitHub
+1

Les distracteurs sont perfectibles pour des raisons précises. B juxtapose un terme informatique et une architecture cérébrale caricaturale. C touche une vraie difficulté, mais la « nécessité absolue » d’un homoncule facilite l’élimination. D pourrait tester une confusion intéressante entre productivité et stockage, mais la référence aux souvenirs épisodiques détourne la question.

Correction minimale proposée : conserver A et resserrer l’énoncé :

Dans la discussion des moteurs sémantiques chez Haugeland, quel problème concerne spécifiquement l’intentionnalité d’une représentation ?

Le conseil d’examen devrait distinguer sens, productivité et adaptation générale, plutôt que les fusionner. La variante du ZIP oppose ces problèmes à celui du contrôle et à l’indépendance du médium : les distracteurs deviennent des notions voisines, plutôt que des inventions.

Q14 — La préservation de la vérité ne garantit pas une compréhension parfaite

Le noyau de D est juste : une règle valide peut être appliquée mécaniquement tout en préservant la vérité. Mais trois propositions différentes sont amalgamées :

Une règle préserve la vérité.

Les conclusions effectivement produites sont vraies.

Le système comprend parfaitement et manifeste une intelligence générale.

Haugeland explique la deuxième dans un cadre déterminé : une interprétation donnée, des prémisses vraies et des règles préservant la vérité. Il précise ensuite que, hors du cas logique et mathématique, la vérité ne suffit pas à garantir que les productions aient un sens approprié. 

Haugeland (1981) - Semantic Eng… +1

La nuance est importante : une règle valide reste valide même lorsqu’on lui soumet des prémisses fausses. Ce qu’elle ne garantit plus alors, c’est la vérité des conclusions. L’erreur n’est donc pas la notion de préservation; c’est son extension à une garantie infaillible de sens et de compréhension.

L’appel à Newell et Simon ne comble pas cet écart. Leur hypothèse est empirique, non un théorème; la suffisance suppose notamment une taille suffisante et une organisation appropriée du système. 

Newell and Simon (1975) - Compu… +1

Une rétroaction mérite également correction. L’explication de A suggère que les capteurs et l’interaction sensorimotrice permettent d’exclure l’approche symbolique classique. Pourtant, Haugeland décrit explicitement des transducteurs d’entrée et de sortie. A ne décrit pas le mécanisme formel demandé, mais ce n’est pas parce que des capteurs seraient incompatibles avec une architecture symbolique. 

Haugeland (1981) - Semantic Eng…

Correction minimale proposée pour D :

La machine manipule les symboles selon leur forme. Dans un système interprété, des règles préservant la vérité permettent de tirer des conclusions vraies de prémisses vraies.

L’énoncé ne devrait plus promettre une compréhension « parfaitement » simulée. La variante du ZIP teste directement les conditions de cette garantie.

Aucune correction de date n’est nécessaire pour « Newell et Simon, 1976 » : le document correspond à la conférence Turing de 1975, publiée en mars 1976. 

Newell and Simon (1975) - Compu… +1

Q15 — La réponse désignée correcte contient une confusion conceptuelle

Le passage problématique est :

« un motif d’activation […] réparti sur une multitude de poids synaptiques ».

Les activations sont les états des unités; les poids sont des paramètres des connexions. Ce ne sont pas deux noms pour la même chose. Un réseau peut garder exactement les mêmes poids et produire des motifs d’activation différents en réponse à des entrées différentes.

La distinction est explicite dans les équations de McClelland, qui séparent les activations a des poids w. Elle est également formulée dans le texte d’Agüera y Arcas reproduit en annexe A de Sejnowski. 

McClelland (2009) - The Place o…

 

Sejnowski (2023) - Large Langua…

L’autre confusion est « un concept symbolique = une adresse mémoire physique ». Newell et Simon définissent des expressions composées de symboles et des processus qui transforment ces structures; ils distinguent aussi les abstractions utilisées de leur machine d’implémentation. Une adresse informatique ne constitue pas la définition d’un mode de représentation conceptuelle. 

Newell and Simon (1975) - Compu… +1

La rétroaction de B renforce cette confusion en opposant le connexionnisme au CPU central. Une architecture neuronale peut être simulée sur un ordinateur exécutant ses opérations séquentiellement. McClelland décrit précisément les simulations informatiques du perceptron. L’organisation du modèle et son support d’exécution ne doivent pas être confondus. 

McClelland (2009) - The Place o…

Correction minimale proposée : cibler explicitement les modèles PDP à représentations distribuées, puis remplacer le passage fautif par :

Dans l’approche symbolique, on manipule des structures symboliques explicites. Dans le modèle PDP distribué considéré, une représentation en cours correspond à un motif d’activation sur plusieurs unités; les poids des connexions reflètent les régularités apprises.

Cela conserve le contraste recherché sans assimiler concept, fichier disque, unité et connexion. La variante du ZIP utilise une situation à poids fixes et activations variables, plus directement diagnostique.

Q16 — La dégradation progressive n’est pas une garantie pour toute lésion

La notion elle-même est légitime. Elle figure d’ailleurs aux diapositives 111–112 de leur transcription Markdown. Je ne la déclare donc ni inventée ni automatiquement hors programme. 
GitHub

En revanche, l’énoncé et B affirment que la distribution entraîne intrinsèquement une baisse seulement douce. La rétroaction complète ajoute une garantie concernant la suppression de 15 % des unités, avec maintien de la reconnaissance. Aucun modèle ou protocole précis n’est donné pour soutenir cette affirmation. 
GitHub

Il ne s’agit pas seulement d’une absence de citation : la garantie universelle est réfutable. Le ZIP contient un contre-exemple calculé. Cent unités codent des caractéristiques distinctes; une décision dépend de leur contribution collective et d’un seuil. Le stimulus est reconnu avec les cent unités, mais la suppression de quinze contributions fait passer la somme sous le seuil et change la décision.

Ce contre-exemple ne réfute pas l’existence de dégradations progressives. Il montre uniquement que « représentation distribuée » n’implique pas « reconnaissance toujours conservée après 15 % de lésions ».

L’analogie biologique doit également rester une hypothèse à examiner, pas une validation automatique. McClelland avertit précisément que l’inspiration neuronale ne confère pas, à elle seule, une crédibilité psychologique privilégiée à un modèle. 

McClelland (2009) - The Place o…

Correction minimale proposée :

Certaines architectures distribuées peuvent conserver une performance partielle malgré des perturbations et présenter une dégradation progressive.

La rétroaction devrait préciser les conditions observées plutôt qu’imposer un pourcentage universel. La variante du ZIP décrit une courbe de performance et demande ce qu’on peut réellement en conclure.

2. Qualité psychométrique : ce qui est observable et ce qui ne l’est pas

Ces quatre questions demandent principalement de reconnaître une définition ou une association théorique. Elles ne demandent ni de calculer une sortie neuronale, ni de diagnostiquer une limite architecturale, ni d’interpréter un protocole d’apprentissage.

Les défauts observables sont les distracteurs caricaturaux, les absolus qui facilitent leur élimination et les alternatives qui changent simultanément plusieurs dimensions. Par exemple, la « neurogenèse artificielle » spontanée de Q16 permet de rejeter A sans comprendre le mécanisme de robustesse recherché.

Autre point conditionnel, non un bogue constaté : si le thème « Dégradation gracieuse » est affiché avant la réponse, il fournit directement le terme attendu dans B.

Je ne peux pas attribuer à ces items une discrimination ou une difficulté empirique sans réponses d’étudiants. Le seuil de 40 % d’application/dissociation est une cible de votre référentiel, pas une preuve de validation psychométrique ni une consigne professorale indépendamment établie. 
GitHub

L’amélioration proposée est donc concrète : remplacer les fausses alternatives extravagantes par des erreurs identifiables — omettre le biais, confondre poids et activations, confondre entraînement et généralisation, confondre universalité computationnelle et intelligence.

3. Angles morts effectivement repérables dans cette livraison

Voici les principaux repères de classe auxquels rattacher les compléments. Les horodatages sont ceux du GOLD, pas des temps certifiés par une écoute indépendante. 
GitHub

Notion insuffisamment évaluée par Q13–Q16	Repère GOLD
Défi cartésien : langage productif et adaptation générale	00:48:08–00:54:24
Récursion et infinité potentielle	01:07:32–01:12:52
Système formel et indépendance du médium	01:18:11–01:20:28
Automate fini, mémoire et universalité	01:29:26–01:34; 01:49:15–01:50:18
Nécessité et suffisance de l’hypothèse symbolique	01:52:32–01:54:55
Introduction aux niveaux de Marr	01:55:12–01:59:08
Neurone, biais, séparabilité et couches cachées	02:39:00–02:48:27
Apprentissage associatif et guidé par l’erreur : introduction	02:56:29–02:57:29; 03:10:43–03:11:29
NETtalk : contexte, apprentissage et généralisation	03:14:34–03:30:12
Simplification des modèles neuronaux	02:54:46–02:58:32

Mentionner l’hypothèse symbolique dans la justification de Q14 n’équivaut pas à vérifier que l’étudiant distingue nécessité et suffisance. De même, reconnaître le mot « connexionnisme » ne vérifie pas la compréhension d’un neurone ou de l’apprentissage.

Perceptron et XOR : un complément justifié

Le passage oral transcrit est imparfait dans sa désignation des fonctions, mais il traite la limite de séparation et les couches cachées. McClelland nomme explicitement XOR et explique la distinction entre les limites du perceptron et l’apprentissage multicouche. Il est donc possible de construire une question solide en donnant les quatre entrées-sorties, sans exiger une mémorisation bibliographique. 

McClelland (2009) - The Place o…

NETtalk : un angle mort plus directement étayé que le seul titre de Sejnowski

NETtalk constitue un excellent point de jonction entre le cours et la lecture ciblée. La section 7 de Sejnowski permet de travailler le contexte orthographique, l’apprentissage des régularités et exceptions, et les représentations apprises. La figure 3 montre la fenêtre d’entrée et la cible de prononciation. Ce sont des mécanismes à comprendre, pas des noms d’auteurs à réciter. 

Sejnowski (2023) - Large Langua…

LEABRA, Reverse Turing Test et dégradation progressive : trois statuts à ne pas confondre

LEABRA : je n’ai pas identifié de passage probant établissant son enseignement dans cette séance. Sa présence dans le référentiel n’est pas suffisante. L’introduction de deux formes d’apprentissage ne prouve pas que leur combinaison dans cette architecture nommée ait été enseignée. Je le garde en réserve, plutôt que d’en faire une omission obligatoire.

Reverse Turing Test : la lecture soutient bien une question sur l’hypothèse du miroir, mais celle-ci se trouve en section 4, et non dans les sections 6–7 particulièrement ciblées. Le texte la présente comme une hypothèse et propose une façon de la tester; il n’en fait pas un instrument psychométrique établi. Son inclusion dans le noyau de séance reste à rattacher à un passage de classe. 

Sejnowski (2023) - Large Langua…

Dégradation progressive : présence dans les diapositives transcrites, traitement oral non localisé. Cette réserve curriculaire est distincte de l’erreur de généralisation de Q16. Le GOLD annonce explicitement qu’une partie du diaporama sera reportée : les 114 diapositives ne peuvent donc pas toutes être assimilées automatiquement à la matière déjà traitée. 
GitHub
+1

4. Contre-propositions concrètes

Le dossier propose des corrections minimales, puis des variantes séparées. Voici trois exemples de compléments qui évaluent davantage qu’une reconnaissance de vocabulaire.

Exemple A — Intégration neuronale

Un neurone calcule

net=0,8x
1
	​

−0,4x
2
	​

−0,5,

puis produit y=1 si net>0, sinon y=0. Pour x
1
	​

=1 et x
2
	​

=0, quel couple obtient-on ?

A) (0,3;1)
B) (0,8;1)
C) (−0,1;0)
D) (−0,5;0)

Réponse : A. B omet le biais; C compte le poids de la deuxième entrée malgré son activation nulle; D omet l’entrée active. Les nombres sont créés pour l’exercice, et le calcul est vérifié. Le principe de somme pondérée et de seuil est décrit dans la lecture. 

McClelland (2009) - The Place o…

Exemple B — Capacité d’une architecture

La cible vaut 1 pour (0,1) et (1,0), et 0 pour (0,0) et (1,1). Pourquoi un seul neurone à seuil appliqué à une somme pondérée ne peut-il pas reproduire ces quatre réponses ?

A) Ses poids doivent être initialisés avec des valeurs plus petites.
B) Les deux exemples positifs doivent être présentés plus souvent.
C) Les deux classes ne sont pas séparables par une droite.
D) La cible exige une information temporelle absente des entrées.

Réponse : C. L’item distingue une limite de représentation d’un problème d’initialisation ou d’entraînement. La preuve élémentaire figure dans le ZIP; elle ne conclut à aucune impossibilité pour les réseaux multicouches. 

McClelland (2009) - The Place o…

Exemple C — Généralisation

Quelle procédure permet d’évaluer directement la capacité de généralisation d’un réseau de prononciation entraîné ?

A) Tester des mots nouveaux sans ajuster préalablement les poids sur ces mots.
B) Représenter les mots d’entraînement dans un ordre différent.
C) Vérifier que l’erreur d’entraînement continue à diminuer.
D) Entraîner le réseau sur les nouveaux mots, puis mesurer sa réussite sur ceux-ci.

Réponse : A. B change l’ordre, pas les exemples; C mesure l’ajustement à l’entraînement; D retire aux exemples leur statut de données nouvelles pour ce test. Il s’agit d’évaluer une capacité, pas de garantir à l’avance que le réseau la manifestera. La distinction entre mémorisation et généralisation est développée par Sejnowski. 

Sejnowski (2023) - Large Langua…

5. Ce que contient le dossier

Le ZIP comprend l’audit argumenté, la lecture des 16 options originales, la matrice de couverture et 19 propositions : quatre révisions, treize compléments et deux compléments conditionnels. La révision de Q16 reste elle-même en réserve quant à son rattachement à cette séance. Chaque proposition possède quatre options, quatre rétroactions et ses repères sources.

Ce nombre n’est ni un quota à intégrer ni une nouvelle banque déclarée validée. Les treize compléments constituent un choix de formulations couvrant les lacunes identifiées.

Les quatre PDF originaux sont conservés inchangés dans l’archive, avec leurs empreintes. Les contrôles du dossier et les calculs ont réussi; ils ne constituent pas des essais psychométriques ni des tests du site. Les documents GitHub ont été consultés en ligne, sans certification d’un commit exact.

La suite utile est une révision ciblée du contenu et de sa couverture. Aucun changement du lecteur, des traductions, de l’apparence du site ou de PSY7010 n’est demandé dans ce dossier.