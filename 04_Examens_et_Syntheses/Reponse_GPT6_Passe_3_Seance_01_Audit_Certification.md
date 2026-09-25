Audit doctoral contradictoire — Séance 1, passe 3
Décision : certification définitive non accordée — conformité partielle acquise

La passe 3 apporte des corrections substantielles et vérifiables. La répartition 5–5–5–5 est exacte, les calculs centraux de Q6 et Q7 sont corrects, le protocole de Bosco (2020) est rétabli, et les huit piliers sont désormais représentés. Les 80 options disposent d’une rétroaction et les 20 questions d’un conseil d’examen. 
GitHub

La certification finale reste néanmoins bloquée par des erreurs scientifiques présentes dans certaines clés et, plus fréquemment, dans leurs rétroactions. Une correction prudente dans l’option correcte est parfois annulée quelques lignes plus loin par une conclusion catégorique non démontrée.

Il ne s’agit donc pas de rejeter indistinctement la refonte ni d’exiger une nouvelle banque intégrale. Il faut préserver ses acquis, corriger les affirmations identifiées ci-dessous et remplacer les distracteurs qui restent éliminables sans maîtrise du cours.

Dimension auditée	Décision
Répartition des clés	Conforme : 5 A, 5 B, 5 C, 5 D.
Calculs de Q6 et Q7	Conformes sous les hypothèses précisées ci-dessous.
Sources expérimentales corrigées	Corrections réelles, mais plusieurs surinterprétations persistent.
Présence des huit piliers	Conforme sur le plan thématique.
Exactitude intégrale des clés et rétroactions	Non conforme.
Qualité discriminante des distracteurs	Insuffisante pour la certification demandée.

Portée de l’avis. Cet examen porte sur le fichier publié, ses corrections et leur confrontation aux sources pertinentes. C’est un audit expert de contenu et de conception. Il ne constitue pas une validation psychométrique empirique : sans réponses étudiantes, aucune difficulté observée, discrimination statistique ou fidélité du score n’est établie.

1. Vérification mathématique : ce qui est effectivement acquis
1.1. Distribution des clés : conformité exacte, mais pas absence de toute structure

Le décompte donne bien :

n
A
	​

=n
B
	​

=n
C
	​

=n
D
	​

=5,5/20=25%.

L’ancien cycle continu A–B–C–D a disparu. Cependant, la nouvelle séquence conserve une organisation reconnaissable : chacun des cinq blocs consécutifs de quatre questions contient une fois chaque lettre.

Q01–Q04 : B D A C
Q05–Q08 : A D B C
Q09–Q12 : D A C B
Q13–Q16 : D B A C
Q17–Q20 : D A B C

Ce constat résulte du regroupement de la séquence publiée. 
GitHub

Une répartition par blocs n’est pas intrinsèquement invalide. En revanche, elle ne justifie pas l’affirmation d’une disparition de tout indice séquentiel. Lorsqu’un étudiant connaît trois réponses d’un bloc et repère cette contrainte, la quatrième peut devenir déductible.

Autre distinction importante : 25 % est l’espérance de réussite d’une réponse choisie uniformément au hasard, pas un plafond individuel de score. Pour vingt réponses aléatoires indépendantes :

X∼Binomiale(20,0,25),E[X]=5.

Un score supérieur à cinq demeure possible. L’équilibrage supprime l’avantage d’une stratégie consistant à choisir systématiquement une lettre dominante ; il ne borne pas toute devinette à exactement 25 %.

Réserve de livraison. La séquence complète figure encore dans l’en-tête. Le fichier convient donc à une banque corrigée destinée à l’enseignant, pas à une version étudiante telle quelle. Cette distinction doit être explicite plutôt que de considérer l’annonce des clés comme supprimée. 
GitHub

1.2. Q6 : calcul validé

Sous le modèle gaussien à variances égales, avec la convention β=f
S
	​

(k)/f
N
	​

(k) :

d
′
=z(H)−z(F),c=−
2
z(H)+z(F)
	​

,lnβ=d
′
c.

Ces relations correspondent au cadre de calcul usuel de la TDS. 
Springer Nature

Avec les quantiles fournis :

d
′
=1,48−0=1,48,
c=−
2
1,48+0
	​

=−0,74,
β=e
1,48(−0,74)
=e
−1,0952
≈0,3345.

La réponse D est numériquement correcte : critère libéral, c<0, β<1. L’approximation 0,33 est cohérente avec le quantile arrondi fourni ; elle ne constitue pas une erreur à sanctionner.

La présence d’effectifs explicites permet désormais une véritable application. Il reste toutefois à retirer les indices rédactionnels qui signalent eux-mêmes qu’une autre option contient une erreur, et à éviter d’attribuer une signification clinique ou normative particulière à d
′
=1,48 sans référence adaptée.

1.3. Q7 : calcul optimal validé, conseil d’examen à corriger

Avec des coûts nuls pour les décisions correctes :

β
∗
=
P(S)C
Miss
	​

P(N)C
FA
	​

	​

=
0,01×20
0,99×1
	​

=4,95.

Puis :

c
∗
=
2
ln(4,95)
	​

=
2
1,59939
	​

≈0,79969.

La réponse B est correcte : le critère optimal demeure conservateur malgré un coût d’omission vingt fois supérieur.

La rétroaction doit néanmoins préserver la distinction entre prévalence du bruit et taux de fausses alarmes. Le conseil final les confond dans sa formulation. 
GitHub

La vérification numérique donne, dans ce même modèle :

F=1−Φ(c
∗
+
2
d
′
	​

)=1−Φ(1,79969)≈0,03595.

Le taux de fausses alarmes conditionnel aux essais sans signal est donc ici d’environ 3,60 %, non 99 %.

Le conseil exact serait :

Comparer les probabilités préalables pondérées par les coûts. Une faible prévalence favorise un critère conservateur, mais ne le garantit pas indépendamment du coût des omissions.

Par exemple, avec les mêmes probabilités et C
FA
	​

=1, un coût d’omission supérieur à 99 ferait passer β
∗
 sous 1. La règle est quantitative, non narrative.

2. Les quatre rectifications expérimentales centrales
2.1. Q2 — Bosco, Daniele et Fattori (2017)

Correction principale acquise. Les indices rapportés comparent les distributions d’estimations entre conditions PK et NPK. Ils ne constituent pas une mesure directe d’acuité de V1. La figure 8 et la définition des distributions dans la méthode confirment cette lecture. 
Cris
+1

Réserve bloquante dans la rétroaction A. La prudence de la clé D n’est pas maintenue : la réfutation du déplacement exclusivement décisionnel devient une exclusion de l’explication décisionnelle elle-même. 
GitHub

La distinction logique est décisive :

« Un m
e
ˊ
canisme exclusivement d
e
ˊ
cisionnel n’est pas d
e
ˊ
montr
e
ˊ
 »

n’implique pas :

« Un m
e
ˊ
canisme d
e
ˊ
cisionnel est exclu ».

Le d
′
 calculé entre deux conditions indique leur séparation sur la variable analysée. À lui seul, il ne localise pas la modification dans la perception, la décision ou la production de la réponse. Les auteurs peuvent défendre une interprétation perceptive ; le corrigé doit la distinguer de ce que cet indice établit directement.

Correctif exigé : conserver le noyau de Q2-D et remplacer la justification de Q2-A par :

L’option affirme une exclusivité que l’analyse ne démontre pas. Les résultats établissent une modulation des estimations liée à la connaissance préalable de l’action ; cette comparaison ne suffit pas, isolément, à départager tous les mécanismes perceptifs et post-perceptifs.

2.2. Q3 — Bosco et al. (2020)

La reconstruction du protocole est substantiellement correcte. L’étude manipule la longueur verticale d’une cible pendant des saccades horizontales, en maintenant son centre. Elle observe une différence de taille perçue entre les conditions de modification sans adaptation concomitante de l’amplitude saccadique dans les expériences principales. 
ResearchGate

Cette correction lève l’objection majeure des passes précédentes.

Il faut néanmoins enseigner le résultat avec sa portée exacte : absence de modification significative de l’amplitude, et non identité parfaite de toutes les saccades ; dissociation avec ce paramètre moteur, et non démonstration d’une absence générale d’apprentissage moteur.

L’absence d’adaptation de l’amplitude est attendue lorsque le centre de la cible demeure stable. Elle ne constitue pas un échec du système saccadique ni une preuve que ce système serait incapable d’adaptation. 
ResearchGate

Décision : conserver Q3-A, corriger les généralisations des rétroactions et durcir les alternatives.

2.3. Q10 — Held et Hein (1963)

Correction protocolaire acquise : les mouvements de tête étaient libres chez les deux animaux, et le chaton transporté pouvait déplacer ses membres. L’ancienne assimilation à une immobilité complète a donc été corrigée. 
ResearchGate

La conclusion doit toutefois porter sur les contingences entre locomotion auto-produite et stimulation visuelle, pas sur l’absence de toute contingence sensorimotrice chez le chaton passif.

Un animal qui bouge la tête conserve des relations entre ces mouvements et certaines transformations visuelles. De même, l’appariement du dispositif n’équivaut pas à une identité intégrale des images rétiniennes.

Enfin, les résultats doivent être rapportés aux comportements testés. Une déficience de coordination visuomotrice ne doit pas devenir un diagnostic global de cécité ou une démonstration directe de l’absence de tout signal d’efférence. 
ResearchGate

Décision : conserver le contraste expérimental, restreindre la clé et les rétroactions aux contingences manipulées et aux fonctions mesurées.

2.4. Q13 — Kosmyna et al. (2025)

La confusion puissance spectrale–connectivité est corrigée. La présentation institutionnelle de l’étude confirme que l’analyse concernait les profils de connectivité, sans analyse des changements de puissance spectrale. Elle rapporte également des différences comportementales, notamment de rappel immédiat du texte produit. 
MIT Media Lab

La réserve restante concerne l’enchaînement causal du corrigé :

connectivit
e
ˊ
 r
e
ˊ
duite⟹d
e
ˊ
sengagement⟹dette mn
e
ˊ
sique.

Un effet de la condition expérimentale ne démontre pas automatiquement que la modification de connectivité est le mécanisme causal du résultat mnésique. La connectivité n’est pas, par elle-même, une mesure directe de dépense métabolique ni un diagnostic clinique.

Les auteurs précisent que leurs conclusions sont contextuelles et centrées sur une tâche de rédaction. La quatrième session comporte aussi des résultats différents selon l’ordre d’utilisation de l’outil, ce qui interdit une règle générale indépendante de l’histoire de la tâche. 
MIT Media Lab

Correctif exigé : présenter séparément les mesures EEG, les mesures comportementales et l’interprétation proposée en termes d’externalisation. La notion de dette cognitive peut être attribuée aux auteurs ; elle ne doit pas être transformée en biomarqueur causal définitivement validé.

3. Autres objections scientifiques qui empêchent la certification
3.1. Q5 — Les équations sont correctes, mais la définition de c ne l’est pas

L’option A décrit c comme un « point de symétrie ». 
GitHub

Or, avec un seuil décisionnel k, des moyennes μ
S
	​

,μ
N
	​

 et un écart-type commun σ :

c=
σ
k−(μ
S
	​

+μ
N
	​

)/2
	​

	​

.

c mesure la position signée du critère relativement au milieu des deux distributions. Il n’est pas ce milieu. Le cas c=0 correspond au critère situé à cet endroit. Cette distinction est visible dans la définition et la représentation des paramètres TDS. 
Springer Nature

Il faut également préciser les coordonnées de la ROC. Dans les coordonnées ordinaires :

H=Φ[Φ
−1
(F)+d
′
].

Elle est incurvée pour d
′
>0, mais devient la diagonale lorsque d
′
=0. Dans les coordonnées z, le modèle à variances égales produit une droite de pente 1.

Décision : réécrire Q5-A et sa justification. Le rétablissement des bonnes équations ne suffit pas si leur interprétation verbale reste erronée.

3.2. Q8 — La comparaison neurométrique doit porter sur des mesures commensurables

La référence bibliographique à normaliser est Britten, Shadlen, Newsome et Movshon (1992). L’étude compare la discrimination de signaux de mouvement par des neurones individuels et par l’observateur comportemental. 
The Journal of Neuroscience
+1

La formulation correcte doit distinguer trois opérations :

Construire une mesure neurométrique à partir de distributions de réponses neuronales sur des essais répétés ; obtenir une performance ou un seuil neurométrique ; le comparer à une performance ou un seuil comportemental défini de manière correspondante.

Une variance isolée, un potentiel d’action isolé, un d
′
 et un seuil exprimé en cohérence ne sont pas des quantités interchangeables.

Surtout, la sensibilité élevée d’un neurone ne démontre pas que le cerveau n’utilise pas un ensemble de neurones. La disponibilité d’information dans une unité et son utilisation effective dans la décision sont deux questions distinctes.

Correctif exigé : retirer la réfutation générale du traitement collectif et préciser la construction des mesures comparées.

3.3. Q11 — TVSS : distinguer apprentissage, extériorisation et recrutement cortical

Le corrigé doit séparer l’apprentissage des contingences sensorimotrices, l’expérience d’un objet distal et le recrutement de régions occipitales.

L’étude de Ptito et collaborateurs rapporte un recrutement occipital après entraînement à une tâche de discrimination d’orientation avec stimulation électrotactile linguale chez des participants aveugles. Ce résultat d’imagerie ne constitue pas, à lui seul, une expérience démontrant que le contrôle actif de la caméra est la condition nécessaire de toute extériorisation. 
OUP Academic

Le rôle de l’action peut être central sans que chaque lien d’une chaîne causale soit établi par la même expérience.

Correctif exigé : attribuer séparément chaque résultat à son protocole et supprimer les formulations universelles non justifiées.

3.4. Q15 — Double dissociation clinique : pertinence rétablie, perfection fictive à retirer

L’introduction de profils croisés est un progrès réel. Toutefois, une dissociation fonctionnelle n’exige pas une fonction totalement détruite opposée à une fonction parfaitement intacte.

Les réanalyses des données originales de DF ont notamment relevé des déficits visuomoteurs dans certaines tâches, dont l’insertion d’une carte, malgré une préservation relative par rapport aux tâches perceptives. Cette distinction est explicitement discutée dans les recherches ultérieures sur DF. 
Enlighten Publications

Q15 doit donc abandonner le profil miroir parfait. Deux solutions sont acceptables : présenter des profils schématiques explicitement idéalisés, ou décrire les patients réels avec des performances relatives, des tâches précises et des contrôles appropriés.

Une correction connexe s’impose en Q1 : la double dissociation n’est pas réservée aux patients cérébrolésés. Des travaux expérimentaux chez des participants sains emploient cette logique, notamment Ganel, Tanzer et Goodale dans le domaine même des illusions et de la préhension. 
AllPsych
+1

Pour Jackson et Shaw, l’objection pertinente est donc l’absence d’une démonstration anatomique croisée dans les résultats invoqués — pas une interdiction générale liée au recrutement de participants sains.

3.5. Q16 — Une explication de couverture ne démontre pas toute la chaîne interprétative

Le contrôle du sac présenté comme contenant du matériel d’enregistrement provient notamment de Durgin et al. (2009). Dans cette étude, les jugements de pente des participants convaincus par cette explication ne différaient pas de ceux des participants sans sac. Les auteurs y voient un argument en faveur des demandes expérimentales. 
Springer Nature

Ce résultat justifie une objection méthodologique à l’interprétation perceptive. Il ne démontre pas simultanément que chaque participant modifiait consciemment sa réponse, que V1 est imperméable à toute influence pertinente, et que l’ensemble de la théorie de Proffitt est réfuté.

Une explication de couverture ne constitue pas non plus, à elle seule, une procédure en double aveugle.

Correctif exigé : faire identifier l’explication alternative et le contrôle qui l’évalue, sans présenter la position théorique des critiques comme un résultat directement mesuré.

3.6. Q18 — L’erreur de transfert inter-effecteurs persiste dans Toad

La revue de Bosco et al. (2023) rassemble des résultats obtenus avec plusieurs effecteurs et différents paradigmes. Elle ne rapporte pas une expérience unique démontrant qu’un même effet prémoteur se transfère librement entre œil, main et jambe. 
Frontiers

Cette inférence subsiste pourtant dans la rétroaction D. 
GitHub

Il faut également préciser le coût de liaison des traits. Dans la TEC, les conséquences du partage de traits dépendent notamment de la tâche et de l’état d’activation ou de liaison des représentations. Le codage commun ne se réduit pas à un dossier neuronal unique nécessairement indisponible chaque fois qu’un stimulus apparaît du même côté qu’une action préparée. 
Cambridge University Press
+1

Correctif exigé : supprimer le transfert attribué à la revue et spécifier le paradigme permettant de prédire facilitation ou interférence. Une prédiction compatible avec la TEC n’en constitue pas une preuve exclusive.

3.7. Q19 — Compression catégorielle ne signifie pas disparition des différences

Le pilier manquant est réintroduit, mais une réduction de la distance perçue entre exemplaires d’une même catégorie n’équivaut pas à leur indiscernabilité.

Dans une étude cosignée par Harnad, l’apprentissage produit notamment une séparation intercatégorielle accrue ; la compression intracatégorielle peut être plus faible et n’est pas significative dans toutes les analyses. Ce résultat est incompatible avec une obligation générale d’annuler les différences internes à une catégorie. 
PLOS

Les catégories peuvent être discrètes comme réponses de classement tout en conservant des différences perceptives graduées entre leurs membres.

L’opposition avec Proffitt doit donc porter sur la nature des facteurs explicatifs et des signatures recherchées, non sur une opposition mathématique universelle entre une fonction en marches d’escalier et une fonction strictement proportionnelle à la fatigue.

Correctif exigé : réécrire Q19-B et son conseil final. Cet item ne peut être certifié dans sa formulation actuelle.

4. Matrice d’intervention sur les vingt questions

Cette matrice distingue le maintien de l’objectif d’une question de la certification de sa formulation actuelle. Les prescriptions prolongent les objections documentées ci-dessus.

Question — clé	Décision	Intervention indispensable
Q1 — B	Noyau conservable	Maintenir Ponzo et le contraste force–ouverture ; corriger la restriction de la double dissociation aux cas cliniques et les généralisations d’immunité.
Q2 — D	Correction ciblée bloquante	Maintenir la séparation PK/NPK ; retirer de Toad A l’exclusion non démontrée d’un mécanisme décisionnel.
Q3 — A	Noyau conservable	Conserver le protocole réel ; distinguer absence d’adaptation significative, invariance parfaite et absence générale d’apprentissage.
Q4 — C	Révision ciblée	Maintenir la compatibilité avec un critère fixe ; présenter la gaussianité comme une hypothèse de modèle, non comme une définition universelle de la TDS.
Q5 — A	Réécriture de la clé	Définir correctement c ; préciser les coordonnées et conditions de la ROC.
Q6 — D	Calcul validé	Retirer les indices qui désignent une option comme fautive ; employer des erreurs numériques plausibles et distinctes.
Q7 — B	Calcul validé	Corriger la confusion prévalence–fausses alarmes et le conseil général sur la rareté.
Q8 — C	Réécriture méthodologique	Définir les distributions et seuils comparés ; ne pas inférer l’absence de traitement collectif.
Q9 — D	Noyau conservable	Enseigner une pondération relative des précisions, non une annulation automatique de tout signal bruité.
Q10 — A	Correction de portée	Restreindre l’absence de contingence à la relation manipulée ; préserver les mouvements libres et les comportements réellement mesurés.
Q11 — C	Réécriture causale	Séparer les résultats comportementaux, phénoménologiques et d’imagerie.
Q12 — B	Noyau conservable	Maintenir la distinction possibilité d’action–signifiant ; préciser le caractère relationnel et ne pas réduire les signifiants aux seuls indices visuels.
Q13 — D	Réécriture interprétative	Garder la connectivité comme mesure ; distinguer résultats, mécanisme supposé et dette cognitive interprétative.
Q14 — B	Révision ciblée	Conserver le modèle fonctionnel et le contrôle en ligne ; éviter de transformer ses spécialisations en localisations absolues de toute conscience.
Q15 — A	Réécriture clinique	Remplacer la perfection symétrique par des dissociations relatives, spécifiques aux tâches.
Q16 — C	Réécriture méthodologique	Attribuer le contrôle, séparer résultat et interprétation, retirer les conclusions universelles.
Q17 — D	Correction de portée	Conserver le couplage observé ; ne pas généraliser à toute attention couverte ni attribuer une preuve causale des FEF au seul protocole comportemental.
Q18 — A	Réécriture théorique et documentaire	Spécifier le coût de liaison ; supprimer la démonstration fictive de transfert inter-effecteurs.
Q19 — B	Réécriture de la clé	Distinguer compression et indiscernabilité ; retirer l’opposition mathématique absolue.
Q20 — C	Noyau conservable	Maintenir la distinction entre traitement ascendant initial et ordre d’accès conscient ; remplacer les alternatives anatomiquement absurdes.

Pour Q17, la revue obligatoire distingue elle-même les résultats comportementaux de Deubel et Schneider des travaux ultérieurs de stimulation des champs oculaires frontaux. Il faut conserver cette attribution séparée. 
Frontiers

5. Robustesse des distracteurs et validité des rétroactions
5.1. Les distracteurs caricaturaux n’ont pas disparu

Les erreurs conceptuelles plausibles existent désormais : inversion de convention de β, confusion entre coût individuel et coût pondéré, confusion entre séparation des estimations et acuité sensorielle.

Mais elles voisinent encore avec des alternatives qui invoquent des mécanismes manifestement disproportionnés ou incohérents, notamment dans Q13, Q16, Q18 et Q20. 
GitHub
+1

Une option fausse doit pouvoir être choisie par un étudiant partiellement informé. Elle ne devrait pas exiger qu’il accepte simultanément une anatomie inversée, une causalité inventée et une conséquence pathologique extrême.

Le durcissement attendu n’est donc pas d’ajouter du jargon. Il consiste à opposer des erreurs voisines : mauvaise variable dépendante, mauvais contraste expérimental, conclusion trop forte, inversion d’un signe ou confusion entre paramètre et estimation.

5.2. Un énoncé ne doit pas fournir le critère d’élimination

Q13 indique dès l’énoncé que les variations de puissance spectrale n’ont pas été examinées. Une option les attribue ensuite à l’étude. L’étudiant peut la rejeter par simple cohérence textuelle.

Ce procédé peut être utile dans un exercice guidé. Il ne démontre pas la connaissance autonome de la méthodologie de l’article.

De même, une mauvaise option ne doit pas signaler elle-même son erreur de calcul. Les erreurs doivent être à détecter, non à reconnaître parce qu’elles sont annoncées.

5.3. Complétude formelle de Toad : validée ; exactitude intégrale : non validée

Les 80 rétroactions et 20 conseils répondent à l’exigence de présence de cette passe. Il n’y a pas lieu d’exiger maintenant 80 encadrés distincts : le format demandé est bien un conseil par question. 
GitHub

En revanche, les rétroactions doivent maintenir la même prudence que les clés. Les cas prioritaires sont Q2-A, Q7, Q13, Q15, Q18-D et Q19.

La structure attendue peut rester :

Erreur identifiable → relation correcte → justification pertinente → limite → conseil de résolution.

La justification doit toutefois démontrer pourquoi l’option choisie est erronée. Une affirmation sur une paralysie ne réfute pas correctement une option qui parlait d’une inhibition corticale localisée ; elle déplace le propos.

Enfin, un conseil mnémotechnique ne doit pas supprimer la limite scientifique qu’il devrait aider à retenir. Une formule mémorisable mais fausse reste une erreur d’enseignement.

6. Couverture des huit piliers : présence rétablie, maîtrise non encore certifiée

La confrontation au référentiel confirme que les deux absences majeures de passe 2 sont corrigées. Harnad et la RHT sont réintroduits. 
GitHub
+1

Pilier	Questions	État de couverture
TDS	Q2, Q4–Q8	Présence substantielle et deux applications numériques ; définitions et interprétations à corriger.
Helmholtz–Friston	Q9	Pondération prédictive abordée ; le lien avec l’inférence inconsciente reste peu directement évalué.
Gibson–Norman	Q12	Distinction nettement améliorée ; objectif conservable.
Perception active : Held–Hein, TVSS	Q10–Q11	Deux paradigmes présents ; leurs limites causales doivent être mieux évaluées.
Deux voies et double dissociation	Q1, Q14–Q15	Couverture renforcée ; profils cliniques et inférences anatomiques trop absolus.
Proffitt–Harnad	Q16, Q19	Pilier rétabli, mais opposition théorique encore déformée.
TEC	Q18	Présente ; prédiction à préciser et preuve attribuée à Bosco à retirer.
Reverse Hierarchy Theory	Q20	Pilier rétabli ; noyau conceptuel conservable, distracteurs insuffisants.

Présence des huit piliers : oui. Saturation évaluative démontrée : non.

Le référentiel exige au moins 40 % de questions d’application ou de dissociation, soit :

0,40×20=8.

Cette exigence doit être documentée par une classification des opérations réellement demandées, pas simplement par les intitulés des questions. Q6 et Q7 apportent désormais des applications identifiables ; plusieurs autres items pourraient contribuer au seuil après correction. Leur simple longueur ou technicité ne suffit pas à les classer aux paliers supérieurs. 
GitHub

Le référentiel lui-même doit aussi être harmonisé avec les corrections acquises : il conserve notamment des raccourcis sur les paramètres TDS, les affordances perçues et les signifiants, ainsi que le protocole du chaton passif. Un référentiel ne doit pas réintroduire dans la prochaine révision les erreurs que l’audit vient de corriger. 
GitHub

7. Dispositif final de certification
Éléments que je valide

L’équilibre arithmétique des clés, les calculs centraux de Q6 et Q7, la restauration du protocole de Bosco (2020), l’abandon de l’erreur de puissance spectrale attribuée à Kosmyna, la correction de l’immobilité supposée du chaton passif, la présence des huit piliers et la complétude formelle des rétroactions.

Ces acquis doivent être conservés.

Éléments qui bloquent encore l’approbation

Les corrections prioritaires concernent la portée de l’analyse de Bosco en Q2, la définition de c en Q5, la comparaison neurométrique en Q8, les inférences causales en Q11 et Q13, la perfection clinique fictive en Q15, la portée du contrôle expérimental en Q16, le transfert attribué à Bosco en Q18 et l’indiscernabilité intracatégorielle en Q19.

S’y ajoutent les corrections ciblées des autres rétroactions et une révision transversale des distracteurs.

Verdict final sur la version examinée

Certification définitive « Étalon-Or » : non accordée.

Conformité arithmétique : acquise. Couverture thématique : rétablie. Conformité scientifique et évaluative intégrale : non acquise.

La correction restante peut être ciblée. Son principe directeur est précis : ne jamais transformer une séparation statistique en localisation causale, une préservation relative en perfection clinique, un ensemble d’études en expérience de transfert, ou une compression perceptive en disparition des différences.