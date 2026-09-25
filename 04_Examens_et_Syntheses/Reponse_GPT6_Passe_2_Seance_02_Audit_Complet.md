Audit de la Passe 2 — Séance 2

Verdict : points d’ajustement résiduels précis.

La révision apporte de vraies corrections, mais elle n’est pas encore prête pour une validation définitive. Le problème principal est Q18 : sa réponse désignée correcte déforme la condition de suffisance de Newell et Simon. Plusieurs autres erreurs se trouvent dans les rétroactions, alors que les bonnes réponses correspondantes ont été réparées.

Télécharger le ZIP — Audit Passe 2, preuves et corrections ciblées

J’ai examiné les dix questions Q13–Q22, leurs 40 options, les rétroactions, les justifications et les conseils d’examen. Le dossier distingue les corrections factuelles nécessaires des clarifications et des variantes pédagogiques facultatives. Il ne contient aucun remplacement du lecteur documentaire ni aucun code de déploiement.

1. Vérification des quatre questions révisées
Q13 — Intentionnalité : réponse A conservée, explication du contrôle à corriger

Le sens central de A est correct. L’intentionnalité concerne bien le fait qu’une représentation porte sur quelque chose ou possède une signification. C’est explicitement la définition donnée par Haugeland, note 8, page imprimée 50. 

Haugeland (1981) - Semantic Eng…

Le mot intrinsèquement ne suffit pas à rendre cette réponse fausse : on peut justement poser la question de l’intentionnalité intrinsèque. En revanche, il ne faudrait pas présenter cette question comme déjà résolue par la simple présence de symboles physiques. Haugeland distingue les propriétés formelles des propriétés sémantiques, puis discute l’intentionnalité originale comme un problème philosophique, non comme une conclusion définitivement démontrée. 

Haugeland (1981) - Semantic Eng… +1

L’erreur établie concerne la rétroaction D. Le problème de contrôle ne consiste pas simplement à mécaniser la syntaxe. Chez Haugeland, il consiste à choisir le prochain mouvement parmi ceux que les règles autorisent. Cette distinction apparaît clairement dans la section IV, page 40. 

Haugeland (1981) - Semantic Eng…

Correction proposée pour cette seule rétroaction :

Le problème de contrôle est le choix du prochain mouvement parmi les mouvements légalement possibles. Il ne consiste pas à supprimer les transducteurs et se distingue du problème de la signification des représentations.

Sur les distracteurs : indépendance du médium et productivité sont des notions voisines pertinentes. Leur présence constitue une amélioration par rapport aux alternatives caricaturales de la première livraison.

Q14 — Préservation de la vérité : C corrigée, mais A reçoit une explication fausse

La réponse C exprime maintenant correctement la garantie conditionnelle. Dans un système interprété, des règles préservant la vérité permettent de tirer des conclusions vraies de prémisses vraies. C’est bien le raisonnement de Haugeland, page 44. 

Haugeland (1981) - Semantic Eng…

La rétroaction A commet cependant l’erreur inverse : elle transforme des prémisses fausses en garantie de conclusion fausse. 
GitHub

La réfutation est élémentaire. La règle

P ⊢ P∨Q

est valide : lorsque P est vrai, P∨Q est vrai. Mais lorsque P est faux et Q vrai, la conclusion reste vraie.

Une règle valide peut donc conduire d’une prémisse fausse à une conclusion vraie. Elle ne garantit simplement plus la vérité de la conclusion lorsque ses prémisses ne sont pas toutes vraies.

Correction minimale :

Si les prémisses sont fausses, la validité des règles ne garantit plus la vérité de la conclusion : celle-ci peut être vraie ou fausse.

Autre restriction utile : appliquer une règle sans consulter le sens des symboles ne démontre pas que le système entier est incapable de comprendre. Haugeland examine précisément ce débat. La rétroaction devrait décrire le fonctionnement mécanique sans transformer cette description en verdict philosophique sur toute compréhension possible. 

Haugeland (1981) - Semantic Eng…

Décision : conserver C; corriger la rétroaction A. L’ancienne accusation de garantie inconditionnelle ne doit plus être appliquée à cette bonne réponse.

Q15 — Poids et activations : distinction restaurée, confusion d’implémentation persistante

La réponse A distingue désormais correctement les poids appris w et les activations courantes a. McClelland les emploie comme variables distinctes dans son modèle; l’annexe A de Sejnowski distingue également paramètres appris et niveaux d’activité dynamiques. 

McClelland (2009) - The Place o…

 

Sejnowski (2023) - Large Langua…

La rétroaction C conserve néanmoins l’erreur sur les adresses mémoire. Un réseau à représentations distribuées peut parfaitement être simulé sur un ordinateur dont la mémoire possède des adresses. Distribué décrit ici le codage du modèle, pas l’absence d’emplacements physiques dans son implémentation. Les simulations informatiques du perceptron décrites par McClelland suffisent déjà à montrer pourquoi les deux niveaux ne doivent pas être confondus. 

McClelland (2009) - The Place o…

Newell et Simon distinguent eux aussi les types de données et opérations de la machine sous-jacente. 

Newell and Simon (1975) - Compu…

Correction proposée :

Le choix C confond la représentation du modèle et son implémentation. Des poids stockés dans une mémoire informatique adressée peuvent participer à un codage distribué. Le signal d’erreur utilisé pour apprendre n’est pas non plus le motif d’activation ordinaire représentant l’entrée.

Enfin, persistant ne signifie pas immuable. Les poids peuvent rester constants pendant une phase d’inférence sans apprentissage, puis être modifiés à l’entraînement. Le conseil devrait préciser cette condition plutôt que présenter une matrice universellement fixe.

Décision : conserver A. L’erreur critique activations/poids de la Passe 1 est réellement corrigée.

Q16 — Dégradation gracieuse : D corrigée, seuils et analogie biologique à borner

D reconnaît maintenant qu’une chute brutale reste possible. L’ancienne garantie des 15 % est désormais une proposition rejetée : ce n’est plus une erreur de la bonne réponse. 
GitHub

Le problème résiduel est de généraliser les activations binaires à tous les réseaux. Une décision catégorielle peut avoir un seuil sans que toutes les unités possèdent une activation binaire. McClelland décrit justement le passage à des activations continues et son importance pour l’apprentissage multicouche. 

McClelland (2009) - The Place o…

Correction proposée :

La performance peut se dégrader progressivement dans certaines architectures et conditions de perturbation. Une décision catégorielle peut néanmoins basculer lorsqu’une frontière de décision est franchie. Cela ne suppose pas que toutes les unités du réseau soient binaires.

La justification biologique doit aussi rester proportionnée. Une inspiration neuronale n’accorde pas automatiquement une supériorité explicative au modèle. McClelland le dit expressément : cette inspiration n’est pas, à elle seule, une preuve de validité psychologique. 

McClelland (2009) - The Place o…

La rétroaction concernant les sauvegardes reproduit par ailleurs la confusion de Q15 : restaurer une sauvegarde n’est pas de la dégradation gracieuse, mais une implémentation PDP n’est pas pour autant interdite de sauvegarde.

Décision : conserver D; corriger les généralisations des rétroactions.

2. Audit des six nouvelles questions
Q17 — Défi cartésien : B conservée

La séparation entre productivité du langage et adaptation générale est correcte. La réponse attribue à la récursion une explication de la première, plutôt que de prétendre qu’elle suffit à expliquer la seconde. Cela correspond à l’organisation du GOLD. 
GitHub

Une précaution est nécessaire dans la justification : un automate à états finis peut produire un langage infini. Une boucle émettant successivement « a » permet déjà des chaînes de longueur arbitraire. Il serait donc faux de corriger le texte en affirmant que tout automate fini ne peut produire qu’un ensemble fini de chaînes.

Mais cette infinité ne rend pas un automate fini équivalent à une machine de Turing. La différence de mémoire reste déterminante; Newell et Simon distinguent explicitement le contrôle fini du ruban non borné. 

Newell and Simon (1975) - Compu…

La justification devrait donc conserver la productivité à partir de règles finies sans assimiler les puissances des différents modèles ni annoncer la résolution de toute l’adaptation humaine.

Distracteurs : les options C et D disposent actuellement d’une rétroaction fusionnée. Deux retours distincts seraient plus utiles : l’un expliquerait pourquoi mémorisation et apprentissage ne constituent pas les deux facultés visées; l’autre ferait la même distinction pour transduction et coordination motrice. Il n’est pas nécessaire d’ajouter une biographie de Chomsky.

Q18 — PSSH : erreur substantielle dans la réponse correcte C

C doit être corrigée avant utilisation. La suffisance y devient une production inévitable d’intelligence par le matériel. 
GitHub

La preuve contraire se trouve directement page 116 du PDF original. Newell et Simon précisent qu’un système de symboles physiques de taille suffisante peut être organisé pour manifester une intelligence générale. Ils ajoutent que l’hypothèse est empirique, pourrait être fausse et ne signifie pas que n’importe quel système manifestera arbitrairement cette intelligence. 

Newell and Simon (1975) - Compu…

La différence n’est pas stylistique :

Possibilité avec organisation appropriée : c’est la suffisance proposée.

Intelligence inévitable dès que le matériel existe : ce n’est pas cette proposition.

La nécessité porte également sur l’intelligence générale, pas indistinctement sur toute manifestation d’une capacité intelligente.

C proposée :

C’est une hypothèse empirique et réfutable. La nécessité signifie que tout système manifestant une intelligence générale devrait se révéler, à l’analyse, être un système de symboles physiques. La suffisance signifie qu’un tel système, de taille suffisante, peut être organisé pour manifester une intelligence générale.

Les rétroactions doivent conserver « selon l’hypothèse ». Les auteurs précisent qu’ils ne disposent pas d’une démonstration purement logique du lien entre systèmes symboliques et intelligence. 

Newell and Simon (1975) - Compu…

Aucune autre option actuelle ne remplace correctement C. Il faut corriger son contenu, pas simplement changer la lettre du corrigé.

Q19 — Marr : pas d’erreur démontrée dans l’énoncé et A

Le contraste est correct : tâche, finalité et contraintes d’un côté; représentations et procédures de l’autre. Le passage du GOLD consacré aux niveaux soutient cette distinction. 
GitHub

Je ne demande pas de remplacer cette question.

Sa portée doit seulement être décrite correctement : elle interroge directement deux niveaux, tandis que le troisième est expliqué dans la rétroaction. Elle ne vérifie pas encore la capacité à classer une observation nouvelle au bon niveau.

La rétroaction D ajoute une position générale attribuée à Marr sur la conscience et l’évolution que les passages examinés n’établissent pas. Il suffit d’expliquer la confusion des niveaux; cela ne justifie ni une condamnation historique sans preuve ni l’ajout du livre entier aux lectures.

Q20 — Perceptron et XOR : noyau correct, deux précisions nécessaires

La translation de la frontière par le biais et la non-séparabilité de XOR sont correctement visées. McClelland situe bien la limite du perceptron et son dépassement dans les réseaux multicouches. 

McClelland (2009) - The Place o…

Première précision : ne pas confondre deux usages de b. Pour un neurone dont la décision dépend de

z=w
1
	​

x
1
	​

+w
2
	​

x
2
	​

+b,

la frontière z=0 s’écrit, lorsque w
2
	​


=0,

x
2
	​

=−
w
2
	​

w
1
	​

	​

x
1
	​

−
w
2
	​

b
	​

.

Son ordonnée à l’origine vaut donc −b/w
2
	​

, pas généralement b. Avec w
1
	​

=2, w
2
	​

=4 et b=−8, elle vaut 2.

L’équation y=mx+b n’est pas fausse. C’est le transfert non explicité de sa notation à l’équation neuronale qui crée l’ambiguïté. Et le GOLD emploie déjà cette analogie : il ne faut pas attribuer à DeepThink une invention indépendante du cours. La correction consiste à expliciter la notation, pas à réécrire le verbatim. 
GitHub

Pour XOR, préciser également une transformation cachée non linéaire. Empiler uniquement des transformations affines donne encore une transformation affine. Une couche cachée non linéaire est une solution dans la famille étudiée; ce n’est pas le seul procédé mathématique imaginable. La démonstration et deux constructions sont dans le ZIP, comme preuves d’audit, non comme nouvelles exigences d’examen.

Deuxième correction : la portée historique. McClelland décrit un hiver des réseaux neuronaux pendant lequel les approches symboliques prospéraient. Il ne décrit pas, dans ce passage, un effondrement uniforme de toute l’IA jusqu’au retour de la rétropropagation. 

McClelland (2009) - The Place o…

Le raccourci figure également dans votre référentiel : la correction doit donc porter sur cette formulation commune, pas seulement sur DeepThink.

Q21 — Hebb et rétropropagation : B acceptable dans un cadre supervisé explicite

Le contraste recherché est utile : information locale de coactivation versus ajustement guidé par une erreur de tâche. Mais la rétropropagation n’est pas définie par l’existence d’étiquettes fournies par un enseignant externe.

Un contre-exemple primaire suffit : Hinton et Salakhutdinov décrivent une rétropropagation de l’erreur de reconstruction dans un autoencodeur, où l’entrée sert de référence à reconstruire. Le calcul du gradient ne détermine donc pas, à lui seul, le régime de supervision. 
University of Toronto CS

Cela n’ajoute pas les autoencodeurs au programme. La correction la plus courte est de préciser :

Dans le contraste entre la règle hebbienne élémentaire et l’apprentissage supervisé par erreur illustré ici…

Puis d’expliquer que, dans ce cas supervisé, on compare la sortie à une cible et on utilise les gradients pour ajuster les poids. NETtalk constitue bien un exemple d’apprentissage avec rétropropagation d’erreurs vers une cible phonémique. 

Sejnowski (2023) - Large Langua…

Je ne retiens pas une critique automatique du signe positif dans Δw=ηδx : cette écriture peut être correcte selon la définition de δ. Le dossier explicite la convention plutôt que de changer arbitrairement le signe.

Limite curriculaire importante : le GOLD annonce à 03:10:43–03:11:29 que les détails des règles d’apprentissage seront repris la semaine suivante. Une introduction est donc justifiée; une dérivation complète du gradient n’est pas nécessaire pour clore cette séance. 
GitHub

Q22 — NETtalk : D soutenue, récit sur DECtalk non établi

Le résultat central de D est appuyé par Sejnowski : apprendre régularités et exceptions dans la même architecture, sans programmer individuellement chaque règle de prononciation. Cela ne signifie pas absence de choix de codage, d’architecture, de données ou de supervision. 

Sejnowski (2023) - Large Langua…

L’affirmation selon laquelle DECtalk se serait effondré n’est pas établie par la preuve annoncée. Le papier original de NETtalk décrit au contraire l’utilisation du synthétiseur de DECtalk pour produire les sons à partir des phonèmes générés, en contournant son module de conversion lettres-phonèmes. Cela impose de distinguer les modules, sans conclure que DECtalk était exempt de limites. 
Wolfram Content

Une vérification permet aussi d’écarter une fausse accusation : les 80 unités cachées sont bien documentées, dans la figure 1 du papier de 1987. Aucune correction de ce nombre n’est demandée. 
Wolfram Content

Enfin, réussir cette tâche avec un réseau ne démontre pas, à soi seul, que le cerveau utilise exactement ce mécanisme ou que tout traitement symbolique est inutile. McClelland distingue explicitement succès d’un modèle et preuve du processus humain réel. 

McClelland (2009) - The Place o…

Sur l’architecture : la figure 3 de Sejnowski montre une fenêtre de sept lettres et la prédiction correspondant à la lettre centrale. Ces informations sont davantage exposées que testées par l’item actuel. Une variante portant sur la cible ou sur une évaluation en mots nouveaux serait plus directement applicable. 

Sejnowski (2023) - Large Langua…

3. Distracteurs et diagnostics Toad

Le vocabulaire technique ne garantit pas un niveau d’application. Les questions demandent principalement de reconnaître des descriptions. Plusieurs contrastes sont pertinents, mais d’autres alternatives restent éliminables par des associations grossières.

Par exemple, confondre biais et taux d’apprentissage constitue un piège conceptuel plausible. Lui ajouter simultanément une description manifestement erronée de XOR facilite son élimination sans résoudre le premier problème. De même, opposer nécessité et suffisance est utile; leur substituer une prétendue obsolescence du cerveau teste beaucoup moins précisément cette distinction.

Ce sont des observations de construction des items, pas des estimations empiriques de difficulté ou de discrimination.

Le diagnostic Toad devrait expliquer ce que le choix confond, sans inférer l’inattention ou une déficience de l’étudiant. Une seule réponse ne permet pas cette attribution individuelle.

Le ZIP contient quatre variantes facultatives d’application, avec leurs quatre options et rétroactions : logique conditionnelle, contre-exemple à la nécessité de la PSSH, calcul du biais et test de généralisation. Elles ne constituent pas une nouvelle banque obligatoire. Le compromis est signalé : la variante numérique de Q20 teste le biais, mais ne remplace pas à elle seule une évaluation de XOR.

4. Couverture de la séance et gain marginal Δ
Le gain de couverture est réel, mais sa saturation n’est pas démontrée

Les six ajouts introduisent effectivement davantage de matière. Cependant, une notion citée dans une explication n’est pas nécessairement évaluée.

Dans ce bloc, trois aspects restent sans interrogation directe : la distinction automate fini/machine universelle, l’exécution d’un système formel sur un cas, et le rôle de la simplification développé au §3.2 de McClelland. Ce dernier explique pourquoi simplifier aide à comprendre tout en limitant les conclusions possibles. 

McClelland (2009) - The Place o…

Cela ne prouve pas une lacune de toute la banque : Q1–Q12 ne font pas partie de cette livraison. Il faut comparer leur couverture avant d’ajouter quoi que ce soit.

Je ne transforme pas non plus les mentions de LEABRA ou du Reverse Turing Test dans le référentiel en obligations automatiques. Pour ce dernier, la lecture présente une hypothèse et un test envisageable, pas une mesure psychométrique déjà validée. 

Sejnowski (2023) - Large Langua…

Le seuil de 1 % n’est pas calculable avec les données fournies

Δ n’a ici ni fonction de qualité définie, ni barème stable, ni deux mesures comparables. La livraison est passée de quatre à dix questions. Attribuer « 0,8 % », « 99 % de qualité » ou un autre chiffre serait arbitraire.

Le référentiel demande 40 % d’application/dissociation, mais ne définit pas suffisamment le codage de ces catégories pour transformer ce quota en mesure de saturation. 
GitHub

Un indicateur descriptif limité est possible : au moins une réponse désignée correcte sur dix — Q18 — contient une erreur substantielle établie, soit 10 % des items affectés dans leur bonne réponse au minimum. Ce chiffre n’est pas Δ, ne mesure pas toutes les erreurs et ne prédit pas le taux d’échec des étudiants.

La conclusion utile est donc :

La Passe 2 améliore réellement le contenu, mais les ajustements restants ne sont pas seulement stylistiques. La validation définitive n’est pas justifiée à ce stade.

5. Livrable et portée de la vérification

Le ZIP contient le rapport complet, les corrections localisées avec leurs preuves et critères d’acceptation, la revue des 40 options, la matrice de couverture, les variantes facultatives et les quatre PDF originaux conservés à l’identique. Les empreintes, onze rendus de pages sources et les résultats des huit groupes de vérification réussis y figurent également.

Ces vérifications portent sur les exemples mathématiques et les fichiers du dossier, pas sur des performances d’étudiants ni sur le site.

Les documents GitHub ont été consultés sur main; aucun commit exact ni export brut identique octet par octet n’a été certifié. L’audit concerne la livraison examinée, non le déploiement. Les horodatages sont ceux du GOLD, sans prétention d’écoute indépendante de l’audio.

L’agent commence par AGENT_START_HERE.txt. La suite est une correction des champs désignés, pas une nouvelle refonte. Aucun site n’a été modifié; PSY7010 reste exclu.