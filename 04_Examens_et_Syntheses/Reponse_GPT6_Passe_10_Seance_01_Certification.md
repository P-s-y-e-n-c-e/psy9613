Audit doctoral contradictoire — Séance 1, passe 10
Décision : correctifs ciblés validés ; certification intégrale « Étalon-Or » non accordée en l’état

L’erreur mathématique de Q07 est corrigée. Q08 contient désormais une tâche de calcul dans son énoncé. Les nouveaux distracteurs Q11-C et Q17-B correspondent aux confusions demandées. La cartographie comprend les vingt questions, sans omission ni doublon. Ces acquis sont validés ; les objections correspondantes de passe 9 ne doivent plus être maintenues. 
GitHub
+4
GitHub
+4
GitHub
+4

Je n’accorde toutefois pas le sceau intégral dans la portée annoncée. La nouvelle Q08 reste insuffisamment discriminante, sa rétroaction doit mieux limiter l’inférence sur le décodage neuronal, et le compte rendu de longueur contient encore une erreur. Surtout, cet audit de contenu de la séance 1 ne peut pas être étendu à un « verrouillage psychométrique » des deux séances.

Demande	Décision
Cohérence de Q07 et de Toad D	Oui, aux arrondis explicitement utilisés.
Présence effective du calcul en Q08	Oui. La tâche est désormais proposée au candidat.
Remplacements Q11-C et Q17-B	Oui sur les confusions ciblées.
Cartographie des neuf items supérieurs	Oui comme classification interne de contenu, avec les limites explicitées ci-dessous.
Certification psychométrique complète des séances 1 et 2	Non. Cette conclusion excède les éléments examinés et les propriétés démontrées.

Version examinée : contenu brut identifié Passe 10, consulté le 25 septembre 2026. L’adresse sans paramètre renvoyait une version antérieure ; elle n’a pas servi à juger les corrections actuelles. L’en-tête de la passe 10 indique bien un statut de soumission, sans anticiper l’octroi du sceau. 
GitHub

1. Q07 — Réserve arithmétique levée
1.1. La relation correcte est appliquée aux quatre propositions

Sous le modèle gaussien à variances égales unitaires, avec la convention :

β=
f
N
	​

(k)
f
S
	​

(k)
	​

,

on a :

d
′
=z(H)−z(F),c=−
2
z(H)+z(F)
	​

.

En isolant z(F) :

z(F)=−c−
2
d
′
	​

,

d’où :

F=1−Φ(c+
2
d
′
	​

)
	​

.

Le décalage d
′
/2 distingue bien le critère centré c de sa position relativement à la distribution du bruit. Cette paramétrisation est celle utilisée dans le traitement méthodologique de la TDS. 
Springer Nature

Avec d
′
=2, le contrôle des valeurs arrondies de c affichées dans les options donne :

Option	c affiché	Argument de Φ	F recalculé
A	−0,80	−0,80+1=0,20	42,074 % → 42,1 %
B	0,00	0+1=1	15,866 % → 15,9 %
C	+0,80	0,80+1=1,80	3,593 % → 3,6 %
D	−1,50	−1,50+1=−0,50	69,146 % → 69,1 %

L’omission signalée en passe 9 est donc corrigée dans les options et dans les rétroactions. Toad D identifie désormais correctement le rapport de prévalence oublié, sans approuver une seconde erreur dans la conversion du critère en fausses alarmes. 
GitHub

1.2. La clé C demeure optimale

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

≈0,799694,
F
∗
=1−Φ(1,799694)≈0,0359545.

La réponse C est correcte. Les autres options proposent des critères non optimaux, mais leurs taux affichés sont désormais compatibles avec les valeurs arrondies de ces critères.

1.3. Précision sur l’expression « cohérence parfaite »

Il s’agit d’une cohérence aux arrondis annoncés, pas d’identités exactes entre tous les nombres affichés.

Par exemple, repartir de β=0,20 sans réarrondir c donne :

c=
2
ln(0,20)
	​

≈−0,804719,

puis F≈42,26%. Les 42,1 % résultent, eux, du calcul explicitement réalisé à partir de c=−0,80.

Ce n’est pas une nouvelle réserve bloquante. Je valide la correction conformément à la chaîne d’arrondis prescrite en passe 9. Une mention commune précisant que les taux sont calculés à partir des critères affichés suffirait à éviter toute ambiguïté.

2. Q08 — Opérationnalisation acquise, mais qualité des alternatives encore insuffisante
2.1. Le calcul appartient maintenant à la question

La fonction est fournie avant les réponses :

p(s)=1−
2
1
	​

exp[−(s/α)
γ
].

Pour s=α :

(s/α)
γ
=1,

donc :

p(α)=1−
2
1
	​

e
−1
≈0,8160603.

La valeur de 81,6 % est correcte. Elle correspond au seuil conventionnel d’environ 82 % défini dans l’article de Britten et collaborateurs. 
CNS NYU

La réserve précise de passe 9 est levée : la formule n’est plus confinée à Toad, et le candidat est effectivement invité à l’utiliser. Je ne maintiens donc pas l’objection selon laquelle Q08 serait restée une simple restitution dépourvue de tâche numérique.

2.2. La réussite n’atteste cependant pas nécessairement le calcul exact

Les valeurs proposées sont actuellement 81,6 %, 50 %, 100 % et 0 %. 
GitHub

Or, au point s=α :

0<e
−1
<1⟹
2
1
	​

<p(α)<1.

La seule option strictement comprise entre 50 % et 100 % est A. Un encadrement suffit donc à sélectionner la clé, sans calculer 81,6 % ni examiner la conclusion neurométrique qui accompagne chaque proposition.

Cet encadrement est un raisonnement mathématique légitime. Il ne rend pas l’item invalide et peut soutenir son classement comme application simple. En revanche, il ne justifie pas d’affirmer que la réussite démontre nécessairement les deux opérations annoncées : calcul précis et interprétation de la comparaison neuronale.

C’est ici que subsiste le problème de conception : la nouvelle question sollicite davantage qu’avant, mais ses alternatives permettent encore de n’évaluer qu’une partie de son objectif.

2.3. La rétroaction C doit conserver la prudence de A

Toad A présente correctement les résultats comme compatibles avec un décodage de population. Toad C passe à une affirmation plus directe sur l’origine distribuée de la décision. 
GitHub

La comparaison des seuils ne suffit pas, à elle seule, à identifier le nombre de neurones effectivement utilisés. L’article examine d’ailleurs plusieurs simulations de mise en commun des réponses ; leurs conclusions dépendent notamment des hypothèses de corrélation et de lecture des signaux. 
CNS NYU

La réfutation appropriée est donc :

La comparabilité des seuils ne démontre pas qu’un neurone unique commande effectivement le choix de l’animal ; elle ne détermine pas, à elle seule, l’architecture causale du décodage.

Il ne faut pas remplacer une surinterprétation « neurone unique » par une autre conclusion présentée comme directement prouvée par la seule comparaison.

2.4. Correction locale proposée

Pour exiger les deux opérations, les alternatives peuvent croiser un calcul correct ou erroné et une conclusion prudente ou excessive :

Option	p(α)	Portée de la conclusion
A — clé	81,6 %	Sensibilité unitaire élevée ; la comparaison seule n’identifie pas le nombre de neurones effectivement lus.
B	63,2 %	Même conclusion prudente.
C	81,6 %	La comparaison démontre que le neurone enregistré commande seul la décision.
D	63,2 %	Même conclusion causale excessive.

Les 63,2 % correspondent à une erreur identifiable :

1−e
−1
≈0,6321,

c’est-à-dire l’omission du coefficient 1/2.

Cette proposition ne modifie ni le résultat scientifique ni la clé A. Elle rend simplement nécessaire le contrôle séparé du calcul et de l’inférence. Une version rédigée avec ses rétroactions figure dans l’annexe.

3. Q11-C et Q17-B — Les remplacements ciblés sont validés
Q11-C : une erreur d’inférence est désormais évaluée

L’option ne postule plus une incapacité biologique générale des aires visuelles. Elle infère maintenant, à partir d’un recrutement occipital, une identité complète de l’expérience subjective avec celle d’un voyant. La confusion ciblée est pertinente : une observation neurofonctionnelle ne détermine pas, à elle seule, la nature complète de l’expérience phénoménologique. 
GitHub

La réfutation de Toad C distingue correctement ces deux niveaux. Elle ne doit pas être lue comme démontrant l’absence de toute expérience à caractère visuel ; elle montre que l’identité subjective revendiquée par le distracteur n’est pas établie par cette mesure.

Décision : réserve de remplacement levée. Une formulation moins absolue rendrait l’alternative plus subtile, mais il n’y a pas lieu de continuer à lui reprocher l’ancienne thèse de dégénérescence.

Q17-B : la concurrence porte maintenant sur la bonne variable

Le nouveau distracteur oppose une distribution spatiale symétrique à une priorité pour la cible saccadique. Il ne cumule plus durée excessive, abolition de contraste et attribution à une voie sensorielle. Le remplacement demandé est réalisé. 
GitHub

La réfutation doit rester rapportée aux conditions du paradigme. Le conseil final possède cette restriction ; les formulations intermédiaires doivent être interprétées dans ce même périmètre.

Décision : réserve ciblée levée.

Q02-C : précision d’attribution validée

La rétroaction indique maintenant que la figure 8 vise la comparaison PK/NPK et reconnaît l’existence d’autres analyses avant–après dans l’article. La réserve documentaire précise de passe 9 est levée. 
GitHub

4. Cartographie taxonomique : omission corrigée et seuil minimal recevable

Le fichier répartit désormais les vingt questions une seule fois :

11 au palier 1+6 au palier 2+3 au palier 3=20.

Q15 a bien été réintégrée. Les neuf étiquettes supérieures représentent :

20
9
	​

=45%.

La cartographie documentaire est donc complète. 
GitHub

Appréciation des opérations
Groupe	Questions	Appréciation
Applications numériques	Q06, Q07, Q09	Applications effectives dans le cadre des modèles posés.
Calcul et interprétation	Q08	Application maintenant présente ; ses alternatives doivent mieux distinguer les deux objectifs.
Interprétations méthodologiques	Q01, Q02, Q03, Q16	Classement de palier 2 défendable selon la grille interne retenue.
Dissociation clinique relative	Q15	Classement de palier 2 recevable comme comparaison de profils et de conditions de tâche.

Je ne maintiens plus l’objection selon laquelle le huitième item serait absent faute de formule dans Q08. Selon la lecture qualitative déjà retenue en passe 9, le noyau minimal peut maintenant être défendu indépendamment du statut supplémentaire donné à Q15.

Cela ne signifie pas que les neuf questions possèdent une difficulté doctorale empiriquement démontrée. Une classification de contenu décrit l’opération visée ; la difficulté et la discrimination exigent des réponses de candidats.

Il faut également éviter une inférence individuelle excessive : lorsqu’un triplet numérique permet de trouver la clé dès sa première composante, une bonne réponse ne prouve pas que l’étudiant a recalculé les trois. Cette limite est compatible avec l’emploi du QCM ; elle doit simplement limiter l’interprétation du score.

Décision : cartographie complète et seuil interne recevables, sans attestation de difficulté psychométrique. Le minimum de 40 % figure bien dans votre référentiel. 
GitHub

5. Contrôles métriques : 4–5–11 confirmés, mais espérance de 30 %
5.1. Clés

Le contrôle confirme exactement :

5A,5B,5C,5D.
	​


Cela établit un équilibre des fréquences. Cela ne mesure pas un biais positionnel psychométrique nul.

5.2. Longueur

Le comptage principal utilise les unités séparées par des blancs, expressions LaTeX comprises et lettres A–D exclues.

Position de la clé	Questions	Effectif
Seule option la plus longue	Q03, Q05, Q09, Q20	4/20
À égalité maximale	Q01, Q06, Q07, Q08, Q19	5/20
Plus courte qu’au moins une option	Les onze autres	11/20

Les effectifs de votre message sont exacts. Le préambule du fichier demeure cependant à 5–4–11 : cette section n’a pas été entièrement synchronisée avec les nouvelles options. 
GitHub

Les mesures reposent sur une transcription locale des quatre options de chaque question. Le téléchargement binaire direct ayant échoué, je ne présente pas cette transcription comme une copie brute certifiée du dépôt.

5.3. Espérance avec départage uniforme

Les cinq égalités comprennent respectivement deux, quatre, quatre, deux et deux options maximales.

E[concordances]=4+
2
1
	​

+
4
1
	​

+
4
1
	​

+
2
1
	​

+
2
1
	​

=6.

Donc :

E[concordance avec les cl
e
ˊ
s d
e
ˊ
clar
e
ˊ
es]=30%.
	​


L’espérance n’est plus de 32,5 %. Le déplacement de Q08, de maximum unique vers une égalité à deux, explique la diminution.

Selon le départage des égalités, la stratégie produit de 4 à 9 concordances sur vingt. Ce résultat descriptif ne prédit pas que les étudiants utiliseront cette stratégie.

Le défaut déterministe 20/20 reste levé. La correction du compte rendu à 30 % ne constitue pas une nouvelle réserve scientifique ; elle permet simplement de documenter exactement la version examinée.

6. Portée du verdict : contenu, qualité des items et psychométrie ne sont pas synonymes
Ce qui peut être acté maintenant

Les correctifs scientifiques et documentaires expressément prescrits en passe 9 sont, pour l’essentiel, accomplis. Q07 est réconciliée, Q08 est opérationnalisée, les deux distracteurs ciblés sont remplacés, Q02-C est clarifiée et la matrice classe les vingt items.

Les huit piliers restent présents. Il n’est pas nécessaire de reconstruire une nouvelle banque complète ni de rouvrir les corrections expérimentales déjà validées.

Ce qui empêche encore l’attestation intégrale demandée

Q08 demeure une question dont les alternatives ne contrôlent pas suffisamment les deux opérations annoncées. La nouvelle rédaction est meilleure, mais elle ne satisfait pas encore pleinement l’exigence de distracteurs compétitifs. Le problème est local et réparable ; la proposition à deux dimensions ci-dessus le traite directement.

Une formulation de Toad C doit également être ramenée de la conclusion causale à la portée réellement autorisée par la comparaison. Il ne s’agit pas d’une nouvelle erreur numérique dans la clé.

Ces réserves se rattachent à des exigences déjà présentes dans le référentiel : qualité des distracteurs et justification de l’erreur. Elles ne demandent pas d’atteindre une proportion artificiellement exacte de clés longues ou d’inventer une nouvelle catégorie taxonomique. 
GitHub

Ce que cet audit ne peut pas établir

Sans données de passation, il n’est pas possible de calculer la difficulté observée des items, leur discrimination, la fidélité du score ou l’incertitude de mesure. Le fait que les lettres soient équilibrées et les formules correctes ne fournit pas ces données.

Cette distinction n’ajoute pas une nouvelle condition pour lever les réserves scientifiques. Elle interdit simplement d’appeler cette levée un “verrouillage psychométrique”.

Enfin, la séance 2 n’a pas été examinée dans cette passe. Aucune décision sur sa version actuelle ne peut être déduite d’un audit portant sur le fichier de la séance 1. Le présent rapport ne confirme ni n’annule un éventuel avis distinct à son sujet.

7. Dispositif de clôture

La correction restante ne justifie pas une nouvelle refonte intégrale :

Q08 : conserver la formule et le résultat, mais croiser réellement calcul et portée de l’inférence ; maintenir la prudence dans Toad C.

Préambule métrique : remplacer les anciens effectifs par 4–5–11, puis l’espérance par 6/20, soit 30 %. Remplacer la déclaration de biais nul par celle d’équilibre des fréquences.

Statut : conserver la distinction entre audit interne de contenu, approbation pédagogique et validation psychométrique empirique. Toute décision doit porter sur une révision identifiée plutôt que sur toutes les versions futures du lien main.

L’annexe reproductible de passe 10 contient les calculs, les vingt mesures de longueur, la transcription utilisée et les scripts. Les 
ajustements ciblés, dont une Q08 rédigée avec ses rétroactions, sont également disponibles séparément.

Prononcé final

Q07 : validée aux arrondis affichés.
Q08 : calcul et présence de la tâche validés ; alternatives et portée du corrigé à ajuster.
Q11-C et Q17-B : remplacements ciblés validés.
Cartographie : complète, avec neuf items supérieurs recevables selon la grille interne.
Sceau intégral « Étalon-Or » : non accordé en l’état.
Verrouillage psychométrique des séances 1 et 2 : non établi par cet audit.

La conclusion est donc favorable sur les réparations ciblées, mais pas sur la garantie absolue demandée. Le travail restant porte sur Q08 et sur l’exactitude du statut documentaire, non sur une reconstruction des vingt questions.