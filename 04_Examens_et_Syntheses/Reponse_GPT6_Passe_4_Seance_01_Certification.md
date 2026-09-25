Audit doctoral contradictoire — Séance 1, passe 4
Décision : certification « Étalon-Or » non accordée à la version examinée

Plusieurs réserves sont effectivement levées, mais l’intégration annoncée n’est pas complète. Des rétroactions contredisent encore les corrections exposées dans le rapport de conformité. Un défaut transversal compromet également l’évaluation sommative : dans les vingt questions, la réponse désignée comme correcte est systématiquement l’option la plus longue. Une sélection fondée uniquement sur cette propriété reproduit donc les 20 clés sur 20, sans mobiliser le contenu du cours. Ce résultat provient de mon contrôle des options, non d’une estimation des performances étudiantes. 
GitHub
+2
GitHub
+2

La décision ne consiste pas à annuler les progrès réalisés. L’équilibre des lettres, les calculs de Q6 et Q7, plusieurs corrections protocolaires et la présence des huit piliers sont acquis. En revanche, la validité des rétroactions et l’absence d’indices de réponse ne sont pas acquises.

L’examen porte sur le corrigé enseignant publié : 20 questions, 80 rétroactions et 20 conseils d’examen. Son identification comme document enseignant règle la réserve concernant la présence des clés dans ce fichier : celles-ci n’ont pas à être supprimées d’un corrigé. Elles devront naturellement être absentes de l’épreuve étudiante. 
GitHub

1. Contrôles structurels : équilibre confirmé, raccourci de réponse majeur
1.1. La distribution 5–5–5–5 est exacte

La séquence publiée comporte bien cinq occurrences de chacune des quatre lettres. L’ancienne contrainte systématique imposant une permutation A–B–C–D dans chaque bloc de quatre a également été rompue. Ces deux points sont validés. 
GitHub

En revanche, l’affirmation selon laquelle aucun groupe de quatre questions consécutives ne contient les quatre lettres est fausse. Le contre-exemple le plus immédiat est :

Q17–Q20=D, A, B, C.

Le contrôle exhaustif trouve six fenêtres sur dix-sept comportant quatre lettres distinctes : Q2–Q5, Q6–Q9, Q12–Q15, Q14–Q17, Q16–Q19 et Q17–Q20.

Ces permutations occasionnelles ne constituent pas, en elles-mêmes, une anomalie à éliminer. Interdire toute occurrence créerait une nouvelle contrainte artificielle. Il faut simplement remplacer la déclaration excessive par un constat exact : l’organisation systématique par blocs a disparu.

De même, 25 % est l’espérance d’une réponse choisie uniformément au hasard, pas un plafond applicable à toutes les stratégies de réponse. Un équilibrage des lettres ne neutralise ni les indices rédactionnels ni les différences de plausibilité.

1.2. La longueur identifie toutes les clés

J’ai comparé les quatre options de chaque question, hors lettres de réponse, sur une transcription du texte consulté. Les commandes mathématiques ont été normalisées pour le comptage. Le résultat est identique en nombre de mots et en nombre de caractères : la clé est toujours l’unique option la plus longue.

Quelques exemples sans ambiguïté de segmentation mathématique :

Question	Clé	Mots dans la clé	Mots dans le distracteur le plus long
Q1	B	46	34
Q10	A	65	25
Q15	A	80	30
Q16	C	80	27
Q20	C	87	34

Ces nombres sont mes calculs sur les options publiées. Le contrôle complet des vingt questions figure dans l’annexe numérique liée à la fin du rapport. 
GitHub
+2
GitHub
+2

La conséquence est précise :

« Choisir l’option la plus longue »⟹20/20 selon le corrig
e
ˊ
 pr
e
ˊ
vu.

Cela ne démontre pas que tous les étudiants repéreront la règle. Cela démontre qu’une stratégie indépendante du construit évalué suffit à reproduire toutes les réponses attendues.

Mélanger les lettres ne corrige pas ce défaut. Il faut modifier la rédaction : déplacer les précisions communes dans l’énoncé, donner aux options une granularité comparable et éviter que seule la bonne réponse contienne toutes les nuances méthodologiques.

Il n’est pas nécessaire d’imposer artificiellement le même nombre de mots partout. L’objectif est d’empêcher la longueur de prédire systématiquement la clé.

1.3. Q6 contient encore des indices éliminatoires explicites

Les options B et C comportent toujours la mention « à tort ». Une erreur est donc signalée à l’intérieur du distracteur que l’étudiant est censé évaluer. 
GitHub

La réserve n’est pas levée. L’option ne doit pas expliquer qu’un étudiant a omis un signe : elle doit présenter le résultat correspondant à cette omission, sans annoncer sa faute.

Pour Q6, quatre triplets numériques présentés de façon parallèle suffiraient. Les diagnostics d’erreur appartiennent à Toad, pas aux propositions proposées au candidat.

2. Vérification TDS : calculs validés, une erreur mathématique subsiste dans Toad
2.1. Q6 : validation complète du calcul

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

Ces relations correspondent à la paramétrisation utilisée dans la question. 
Springer Nature

Avec les quantiles fournis :

d
′
=1,48,c=−0,74,
β=e
1,48(−0,74)
=e
−1,0952
≈0,33447.

Le triplet attendu est correct. La différence entre 0,33 et une valeur calculée avec davantage de décimales ne constitue pas une erreur, puisque le quantile est lui-même arrondi dans l’énoncé.

La réserve restante concerne donc la construction des options, pas la solution.

2.2. Q7 : validation du critère optimal et de la distinction entre les taux

En supposant des coûts nuls pour les décisions correctes :

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
0,99
	​

=4,95.

Pour d
′
=2 :

c
∗
=
2
ln(4,95)
	​

≈0,79969.

Le taux de fausses alarmes prédit par ce modèle est :

F
∗
=1−Φ(c
∗
+
2
d
′
	​

)≈0,03595.

Le critère conservateur et le taux d’environ 3,6 % sont corrects. La distinction avec la prévalence de 99 % est maintenant explicitement maintenue dans le conseil. Le seuil C
Miss
	​

>99, pour les autres paramètres inchangés, est également correct. Cette réserve de passe 3 est levée. 
GitHub

2.3. Q5 : la définition de c est corrigée, mais la justification de la ROC contient une autre confusion

La définition signée de c et la distinction entre ROC ordinaire et z-ROC sont désormais correctes. Toutefois, Toad A attribue une forme en cloche à la fonction de répartition gaussienne. 
GitHub

Il faut distinguer :

ϕ(x)=
2π
	​

1
	​

e
−x
2
/2
— densit
e
ˊ
 en cloche,
Φ(x)=∫
−∞
x
	​

ϕ(t)dt— fonction de r
e
ˊ
partition croissante.

Puisque Φ
′
(x)=ϕ(x)>0, la fonction de répartition n’est pas en cloche.

La justification correcte de la géométrie est :

H=Φ[Φ
−1
(F)+d
′
],

d’où, en coordonnées transformées :

z(H)=z(F)+d
′
.

Correctif exigé : conserver Q5-C et remplacer l’explication de Toad A. Ce n’est pas une objection à la bonne équation : c’est une erreur dans l’explication censée l’enseigner.

2.4. Le contenu mathématique doit aussi être techniquement réparé

Dans le contenu brut et le rendu textuel consultés, plusieurs commandes mathématiques apparaissent tronquées ou mêlées à des caractères de contrôle, notamment autour de \beta, \times et des fractions. 
GitHub
+1

Cette réserve est distincte du calcul. Une formule correcte dans l’intention doit rester lisible dans le livrable. Il faut réparer le fichier source puis vérifier le rendu destiné aux enseignants et aux étudiants.

3. Les principales réserves scientifiques qui ne sont pas fidèlement résolues
3.1. Q2 — Bosco (2017) : l’exclusion décisionnelle est corrigée, mais le contraste est de nouveau mal nommé

La correction de Toad A est acquise : elle n’exclut plus catégoriquement un mécanisme décisionnel.

Cependant, Toad B décrit maintenant le d
′
 comme une séparation « atteinte vs saisie ». Ce n’est pas le contraste correspondant aux indices invoqués. 
GitHub

Dans l’analyse pertinente, les distributions PK et NPK sont comparées séparément pour chaque type de mouvement. La figure 8 du manuscrit permet de vérifier directement cette organisation. Les valeurs 1,022 et 1,070 ne sont pas deux façons de mesurer une différence entre atteinte et saisie. 
Cris
+1

La correction à appliquer est limitée mais indispensable :

Le d
′
 quantifie ici la séparation des distributions d’estimations entre connaissance préalable et absence de connaissance préalable du geste, à l’intérieur de chaque condition de mouvement.

Il faut également éviter de définir NPK comme une condition où aucune action ne serait prévue. Ne pas connaître à l’avance le type de geste n’est pas équivalent à ne pas devoir agir.

Décision : correction partielle seulement. Le problème n’est plus l’exclusion du mécanisme décisionnel ; c’est l’identification incohérente des conditions comparées.

3.2. Q8 — Britten et al. (1992) : la comparaison demeure mal spécifiée

La référence bibliographique et la prudence concernant un décodage par population sont améliorées. Mais Q8-A compare encore directement un d
′
 neuronal avec un seuil psychométrique comportemental. 
GitHub

Ce ne sont pas la même variable. Un indice de séparation des distributions et un seuil exprimé, par exemple, en cohérence de mouvement ne deviennent pas commensurables parce qu’ils décrivent tous deux une performance. La TDS permet précisément de construire les transformations nécessaires entre distributions de réponses et performance prédite. 
Springer Nature

La reformulation attendue est :

Comparer les seuils neurométrique et psychométrique exprimés sur la même échelle de stimulus et définis selon un même niveau de performance.

La conclusion sur la disponibilité d’information dans une unité peut ensuite être discutée. Elle ne doit être confondue ni avec une égalité numérique entre paramètres différents, ni avec la démonstration du mécanisme exact de lecture utilisé par le cerveau.

Décision : réserve de commensurabilité non levée.

3.3. Q11 — TVSS : les trois niveaux restent réunis en une seule chaîne causale

La distinction annoncée entre apprentissage sensorimoteur, extériorisation et recrutement occipital n’est pas maintenue dans la question et ses rétroactions. La manipulation active de la caméra demeure présentée comme une nécessité universelle, avec exclusion de toute expérience distale lorsque quelqu’un d’autre la déplace. 
GitHub

L’étude de Ptito et collaborateurs mesure notamment, par imagerie, le recrutement occipital après entraînement à une tâche de discrimination utilisant une stimulation électrotactile linguale. Ce résultat ne démontre pas, à lui seul, la nécessité du contrôle actif de la caméra pour toute extériorisation. 
OUP Academic
+1

Pour établir cette nécessité, il faudrait un contraste expérimental approprié, des conditions d’apprentissage contrôlées et une mesure de l’extériorisation elle-même. Un corrélat d’imagerie ne remplace pas ces contrôles.

Correctif exigé : attribuer séparément les résultats aux protocoles correspondants. L’importance possible de l’exploration active peut être enseignée sans transformer toutes les étapes en une démonstration causale unique.

Décision : réserve non levée, concernant l’énoncé, Q11-D et les conseils.

3.4. Q15 — DF et ataxie optique : la préservation relative est encore annulée par le corrigé

L’ajout du caractère relatif dans l’énoncé et la clé constitue un progrès. Mais les rétroactions reviennent ensuite à une réussite perceptive parfaite chez l’ataxique, et le conseil attribue le comportement de DF à une « voie dorsale intacte ». 
GitHub

Cette dernière généralisation est directement mise en difficulté par les travaux de Rossit et collaborateurs : DF présente des déficits d’atteinte périphérique et de corrections rapides en ligne dans les conditions examinées. Une préservation relative dans une tâche ne permet pas de déclarer toute la voie dorsale fonctionnellement intacte. 
Enlighten Publications

La correction n’exige pas d’abandonner le modèle des deux voies. Elle exige de distinguer les profils historiques schématiques, les patients réels et les conditions précises des tâches.

Il faut remplacer les formulations de réussite absolue par des performances relatives, et préciser les conditions de comparaison : vision centrale ou périphérique, contrôle de la fixation, réponse immédiate ou différée, tâche perceptive ou visuomotrice.

Décision : réserve clinique non levée. Une phrase rappelant la prudence ne corrige pas les affirmations incompatibles qui l’entourent.

3.5. Q16 — Durgin : l’attribution est corrigée, pas la portée de l’inférence

L’attribution à Durgin et al. et l’emploi d’une explication de couverture sont maintenant appropriés. En revanche, Toad C affirme encore que les participants « modifiaient consciemment leur rapport verbal ». 
GitHub

L’étude rapporte que les participants convaincus par l’explication du matériel d’enregistrement ne diffèrent pas des témoins sans sac dans leurs jugements. Les auteurs interprètent ce résultat comme un argument en faveur des demandes expérimentales. Il ne mesure pas directement une décision consciente de falsifier ou d’ajuster la réponse. 
Springer Nature

La disparition d’un effet sous un contrôle constitue un argument méthodologique important. Elle ne suffit pas à établir simultanément la conscience du biais, l’explication de tous les résultats de Proffitt et l’imperméabilité générale du traitement visuel.

Correctif exigé : maintenir l’explication par la demande comme interprétation étayée, sans la convertir en observation directe d’un mécanisme conscient universel.

Décision : réserve non levée dans la rétroaction de la clé et le conseil final.

3.6. Q13 — Kosmyna : variable corrigée, médiation causale non établie

La réserve concernant la puissance spectrale est levée. La référence porte désormais sur les analyses de connectivité et les résultats comportementaux, dans le contexte d’une tâche rédactionnelle.

La correction restante concerne le passage de ces observations à une chaîne mécanistique de désengagement et de dette mnésique. Même lorsque la condition d’utilisation de l’outil est manipulée, cela ne démontre pas que la différence de connectivité est le mécanisme causal de la différence de rappel. Les auteurs soulignent eux-mêmes les limites de généralisation de leur étude. 
MIT Media Lab
+1

Le conseil devrait distinguer : résultat EEG, résultat comportemental, interprétation proposée. Il ne doit pas présenter la connectivité comme une mesure directe du métabolisme ou une signature pathologique.

Décision : correction substantielle, mais réserve interprétative encore partielle.

4. Réserves de portée théorique : trois distinctions à maintenir jusqu’au conseil final
Q9 — La précision doit être comparée à celle du prior

La définition comme inverse de variance est correcte. Toutefois, une faible précision sensorielle ne suffit pas, à elle seule, à établir la domination du prior : la pondération est relative. Le cadre de pondération par la précision n’implique pas une bascule automatique déterminée par le seul bruit sensoriel. 
GitHub
+1

Dans un exemple gaussien simple, le poids de l’information sensorielle est :

w
s
	​

=
π
s
	​

+π
p
	​

π
s
	​

	​

.

Si le prior est encore beaucoup moins précis que l’information sensorielle, cette dernière peut conserver le poids principal.

Modification suffisante : préciser « toutes choses égales par ailleurs » pour une diminution du poids sensoriel, et réserver la domination du prior au cas où sa précision relative la justifie.

Q18 — La nature de la revue est corrigée ; la prédiction doit rester conditionnelle

La reconnaissance de Bosco (2023) comme synthèse multi-effecteurs, plutôt que comme expérience unique de transfert, est acquise. Mais la généralisation de l’interférence à tout stimulus apparaissant du côté d’une action préparée demeure trop large. 
GitHub

La TEC distingue notamment activation et intégration des traits ; le recouvrement des codes peut contribuer à des bénéfices ou à des coûts selon les conditions. Le texte original et ses échanges critiques montrent précisément l’importance de spécifier ces conditions. 
Academia

Correctif exigé : indiquer la tâche, le trait partagé, la temporalité et la mesure concernée. Présenter ensuite le résultat comme compatible avec l’explication TEC, non comme une preuve exclusive de l’amodalité.

Q19 — Compression corrigée, fausse opposition mathématique persistante

La disparition supposée de toute discrimination intracatégorielle a été retirée : cette réserve est levée. Les résultats de recherche sur l’apprentissage catégoriel sont compatibles avec une modification relative des distances perçues, sans indiscernabilité universelle. 
PLOS

Il reste à retirer l’opposition entre non-linéaire et continu. Ces propriétés ne s’excluent pas : f(x)=x
3
, par exemple, est continue et non linéaire. Des catégories discrètes ne démontrent pas non plus une discontinuité de toutes les mesures perceptives.

Enfin, le passage à une déformation strictement proportionnelle à l’effort demande un modèle et des données spécifiques ; il ne découle pas du seul principe d’une perception liée aux ressources d’action. 
GitHub

Correctif exigé : opposer les facteurs explicatifs et les signatures expérimentales recherchées — apprentissage des catégories versus ressources et coûts d’action — plutôt que deux lois mathématiques générales artificiellement exclusives.

5. Matrice décisoire des vingt questions

Les états ci-dessous concernent les réserves scientifiques précises. Ils n’annulent pas la révision transversale des options rendue nécessaire par le résultat « plus longue = clé » dans les vingt items.

Question	État de la correction annoncée	Intervention restante
Q1 — B	Réserve ciblée levée	La double dissociation n’est plus réservée aux patients. Maintenir la distinction entre dissociation comportementale et preuve anatomique ; limiter les conclusions d’immunité au protocole.
Q2 — B	Partielle	Garder la prudence de Toad A ; corriger Toad B en PK/NPK au sein de chaque geste et définir correctement NPK.
Q3 — D	Protocole rétabli	Conserver la dissociation taille–amplitude. Ne pas assimiler une recalibration mesurée consciemment à un ajustement volontairement conscient ; remplacer les alternatives excessives.
Q4 — A	Réserve centrale levée	Gaussianité et critère fixe sont correctement traités. Retirer la partition trop absolue entre bruit exclusivement biologique et critère exclusivement imposé de l’extérieur.
Q5 — C	Partielle	Conserver la définition de c et la z-ROC ; corriger densité versus fonction de répartition dans Toad A.
Q6 — D	Calcul validé ; indices non supprimés	Présenter quatre résultats parallèles sans commentaire désignant les erreurs.
Q7 — C	Réserve calculatoire levée	Conserver les coûts, le prior et le taux conditionnel. Harmoniser la longueur et le niveau de détail des options.
Q8 — A	Partielle	Comparer des seuils construits sur une échelle commune, pas directement un d
′
 et un seuil en cohérence.
Q9 — B	Partielle	Expliciter la précision relative et distinguer diminution de poids et domination du prior.
Q10 — A	Correction protocolaire acquise	Limiter les conclusions aux contingences locomotrices manipulées et aux comportements testés ; remplacer les distracteurs pathologiques fictifs.
Q11 — D	Réserve non levée	Séparer nécessité comportementale, expérience distale et recrutement occipital ; retirer la chaîne causale universelle.
Q12 — D	Distinction conceptuelle acquise	Conserver affordance relationnelle, perception et signalisation distinctes ; harmoniser les attributions historiques et améliorer les alternatives.
Q13 — C	Partielle	Maintenir la bonne variable EEG ; retirer les inférences métaboliques et mécanistiques non démontrées.
Q14 — B	Noyau théorique conservable	Maintenir l’attribution au modèle et le contrôle en ligne ; ne pas transformer les spécialisations fonctionnelles en localisations absolues.
Q15 — A	Réserve non levée	Éliminer de toutes les rétroactions les réussites parfaites et la généralisation d’une voie dorsale intacte chez DF.
Q16 — C	Réserve non levée dans Toad	Conserver Durgin et le contrôle ; distinguer résultat, interprétation post-perceptive et conscience supposée du biais.
Q17 — D	Partielle	L’attribution séparée des travaux sur les FEF est rétablie. Limiter le couplage obligatoire aux conditions du paradigme, sans loi universelle à la coordonnée exacte.
Q18 — A	Partielle	Garder la qualification de revue ; spécifier les conditions de liaison et distinguer compatibilité théorique et confirmation exclusive.
Q19 — B	Partielle	Garder la compression relative ; supprimer l’opposition nécessaire entre non-linéarité et continuité, ainsi que la proportionnalité non établie.
Q20 — C	Noyau conservable ; distracteurs non conformes	Conserver la chronologie RHT. Remplacer notamment l’alternative attribuant l’abstraction sémantique à la rétine.

Cette matrice résulte de la confrontation entre les corrections annoncées et le contenu effectif des questions et rétroactions, non d’un classement fondé sur leurs seuls titres. 
GitHub
+3
GitHub
+3
GitHub
+3

Deux points méritent d’être définitivement distingués.

Held et Hein : le rétablissement de la mobilité de la tête et des membres est exact et correspond au protocole original. Cette correction ne doit pas être rouverte ; seule la portée de la généralisation et la qualité des distracteurs restent à traiter. 
ResearchGate
+1

Bosco (2020) : la manipulation transsaccadique et la dissociation avec l’adaptation d’amplitude sont rétablies. L’ancienne expérience fictive n’est plus un motif de refus de Q3. 
ResearchGate

6. Distracteurs et Toad : la difficulté demeure souvent extérieure au construit
6.1. Des alternatives invraisemblables subsistent

Le remplacement annoncé n’est pas général. Certaines options reposent encore sur une pharmacologie absente du protocole, des lésions inventées ou des fonctions anatomiques manifestement incompatibles avec la tâche. Q10 et Q20 en fournissent des exemples particulièrement nets. 
GitHub
+1

Le critère de révision devrait être :

Quelle erreur d’un étudiant partiellement informé rendrait cette option attractive ?

Pour Held–Hein, des distracteurs portant sur exposition visuelle, attention, contrôle locomoteur et apprentissage des contingences seraient plus discriminants que des dommages vestibulaires inventés.

Pour la RHT, des alternatives qui inversent ordre du traitement neuronal et ordre de l’accès conscient seraient plus pertinentes que des propositions rétiniennes absurdes.

La difficulté doit résulter d’une distinction conceptuelle à résoudre, non d’une accumulation de termes techniques dans la seule réponse plausible.

6.2. La présence des rétroactions n’en garantit pas l’exactitude

La complétude formelle est validée : 80 rétroactions et 20 conseils. Il n’y a pas lieu de demander maintenant un autre format ou quatre encadrés par question. 
GitHub

La correction nécessaire porte sur leur contenu. Le principal défaut est une progression récurrente :

cl
e
ˊ
 prudente⟶r
e
ˊ
troaction plus affirmative⟶conseil absolu.

Or le conseil est précisément la partie destinée à être mémorisée. Il doit conserver la limite essentielle, pas la supprimer.

Les rétroactions doivent aussi réfuter l’option effectivement écrite. Remplacer sa proposition par une conséquence plus extrême facilite la réfutation, mais ne corrige pas le raisonnement initial.

7. Couverture : huit piliers présents, saturation évaluative encore à démontrer

La présence thématique des huit piliers est validée. Il n’est pas nécessaire d’ajouter de nouveau des questions uniquement pour faire apparaître Harnad ou la RHT : ils sont déjà présents. La correspondance avec le référentiel est la suivante. 
GitHub
+2
GitHub
+2

Pilier	Questions correspondantes
TDS, sensibilité et décision	Q2, Q4–Q8
Inférence inconsciente et codage prédictif	Q9
Gibson, affordances et Norman	Q12
Perception active, Held–Hein et substitution sensorielle	Q10–Q11
Deux voies et dissociations	Q1, Q14–Q15
Proffitt et perception catégorielle	Q16, Q19
Theory of Event Coding	Q18
Reverse Hierarchy Theory	Q20

Cette présence ne suffit pas à établir que les huit construits sont correctement discriminés par l’épreuve. Un candidat pouvant reproduire toutes les clés par la longueur des options, le score ne peut pas être interprété comme une démonstration de maîtrise sur cette seule base.

L’exigence du référentiel d’au moins 40 % d’items de paliers supérieurs correspond toujours à huit questions sur vingt. Elle doit être documentée par l’opération cognitive réellement exigée : calculer, contrôler une inférence, départager des modèles ou interpréter une dissociation. Q6 et Q7 offrent désormais des applications numériques identifiables ; les autres classements nécessitent la correction des indices et distracteurs. 
GitHub

8. Conditions de levée des réserves et verdict définitif sur cette livraison

Correction scientifique. Appliquer les modifications localisées dans la matrice, en vérifiant chaque chaîne complète : énoncé, clé, trois distracteurs, quatre rétroactions, conseil. Une réserve n’est pas résolue si sa correction ne figure que dans le préambule.

Correction évaluative. Réviser les options des vingt items afin que leur longueur ne détermine plus la clé. Supprimer les indices métalinguistiques et remplacer les explications impossibles par de véritables erreurs conceptuelles. Il n’est pas demandé de rendre toutes les options artificiellement identiques, mais de supprimer leur pouvoir de réponse indépendant du contenu.

Correction de livraison. Réparer les expressions mathématiques, contrôler le rendu et identifier la version examinée. Le statut de certification figurant dans le document doit rester cohérent avec les décisions d’audit : les passes précédentes n’ont pas accordé l’approbation finale.

Une approbation éditoriale et scientifique resterait distincte d’une validation psychométrique empirique, qui demanderait des données de passation. Le refus actuel ne repose toutefois pas sur l’absence de telles données : il repose sur des défauts directement observables dans le fichier.

Les contrôles arithmétiques, les fenêtres de clés et le comptage des longueurs sont disponibles dans l’
annexe de vérification numérique. Elle précise sa méthode de transcription et ne prétend pas constituer une copie binaire du fichier distant.

Prononcé

Sceau d’excellence « Étalon-Or » : non attribué à la version examinée en passe 4.

L’équilibrage des lettres, les calculs TDS et plusieurs rectifications expérimentales sont validés. L’exactitude intégrale des rétroactions et la qualité de l’instrument sommative ne le sont pas.

Le motif décisif est double : certaines corrections annoncées restent contredites dans le corrigé, et une propriété rédactionnelle extérieure au cours permet encore de reproduire les vingt réponses attendues.