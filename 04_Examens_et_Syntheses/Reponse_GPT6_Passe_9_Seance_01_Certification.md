Audit doctoral contradictoire — Séance 1, passe 9
Décision : corrections ciblées validées en partie ; Sceau « Étalon-Or » non accordé

Q02-C, la matrice de Q03, Q04-C et la nouvelle rétroaction Q11-A répondent aux réserves visées. Le calcul de Q09 est également correct. En revanche, la révision de Q07 introduit une erreur dans le corrigé : Toad D approuve un taux de fausses alarmes de 93,3 % alors que le critère indiqué conduit à environ 69,1 %. La clé C reste correcte ; c’est la justification d’un distracteur qui enseigne une relation fausse. 
GitHub
+2
GitHub
+2

Deux autres points empêchent de conclure au traitement intégral des réserves : le huitième item d’opération supérieure n’est pas effectivement opérationnalisé, et les modifications de Q11-C et Q17-B ne suffisent pas à démontrer le durcissement annoncé.

Version examinée : fichier brut portant l’en-tête Passe 9. Cet en-tête annonce déjà une certification finale ; cette mention constitue une déclaration du document, pas le résultat du présent audit. L’examen reste un avis scientifique et éditorial au regard de votre grille interne, non une homologation institutionnelle de l’UQAM. 
GitHub

1. Réponses aux demandes de validation des remplacements
Élément	Décision	Justification
Q02-C	Réserve de redondance levée	La confusion avant–après exécution est distincte de la confusion entre atteinte et saisie proposée en A.
Q03 : profils 2 × 2	Réserve de construction levée	Les quatre combinaisons des deux variables sont maintenant représentées. Reconnaître le seul résultat oculomoteur ne suffit plus à choisir.
Q04-C	Remplacement accepté	L’alternative oppose désormais variabilité de l’évidence interne et variabilité du critère : c’est une confusion pertinente pour la TDS.
Q07-D	Présentation corrigée ; rétroaction non conforme	L’aveu d’omission a disparu de l’option. Toutefois, son taux de fausses alarmes est incompatible avec son critère et reste approuvé dans Toad.
Q11-A, rétroaction	Réserve de nécessité universelle levée	L’apprentissage n’est plus transformé en preuve que toute réorganisation occipitale exige le pilotage personnel d’une caméra.
Q11-C	Reformulation effectuée ; durcissement insuffisant	La nouvelle terminologie conserve essentiellement la même thèse globale de non-recrutabilité des aires visuelles.
Q17-B	Amélioration technique partielle	Le thème temporel et la distinction des voies sont pertinents, mais l’option cumule plusieurs erreurs plutôt qu’une confusion bien isolée.

Ces décisions concernent les modifications effectivement présentes, et non les seules intentions exposées dans le mandat. 
GitHub
+2
GitHub
+2

Précision nécessaire pour Q02-C

Le nouveau distracteur est utilisable. Sa réfutation doit toutefois rester limitée à l’analyse TDS visée, et ne pas laisser entendre que l’article de Bosco ne comporte aucune comparaison avant–après mouvement.

L’article étudie également des estimations avant et après l’action. En revanche, la figure 8 compare bien les distributions PK et NPK, séparément pour chaque geste, dans l’analyse dont proviennent les valeurs citées. 
Cris
+1

Une formulation suffisante serait :

Dans l’analyse de la figure 8 ici visée, les distributions PK et NPK sont comparées séparément pour chaque geste. Il ne s’agit pas de la comparaison avant–après exécution, également étudiée dans d’autres analyses de l’article.

Cela corrige la portée de Toad C sans retirer le nouveau distracteur ni rouvrir la réserve de redondance.

Q03 : amélioration effectivement acquise

La nouvelle organisation croise les deux résultats :

Option	Adaptation de l’amplitude saccadique	Adaptation de la taille perçue
A	Oui	Non
B	Oui	Oui
C	Non	Non
D	Non	Oui

La correction prescrite a donc été réalisée. Pour la rédaction scientifique, « sans adaptation significative détectée » reste préférable à une invariance parfaite, mais cette précision ne remet pas en cause l’amélioration de la structure des alternatives. 
GitHub

2. Q07 : une erreur mathématique nouvelle dans la rétroaction
2.1. La clé C demeure correcte

Sous le modèle gaussien à variances égales, avec :

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

les relations utilisées sont :

d
′
=z(H)−z(F),c=−
2
z(H)+z(F)
	​

.

Elles donnent :

z(F)=−c−
2
d
′
	​

,

donc :

F=1−Φ(c+
2
d
′
	​

)
	​

.

La distinction entre le critère centré c et sa position relativement à la distribution du bruit est essentielle dans cette paramétrisation. 
Springer Nature

Pour les données de Q07 :

β
∗
=
0,01×20
0,99×1
	​

=4,95,
c
∗
=
2
ln(4,95)
	​

≈0,79969,
F
∗
=1−Φ(1,79969)≈0,0359545.

La réponse C — 4,95;+0,80;3,6% — est validée.

2.2. Les taux de A et D ne découlent pas de leurs critères

Voici le contrôle des quatre propositions, en utilisant les valeurs arrondies de c effectivement affichées :

Option	c affiché	F affiché	F=1−Φ(c+1)
A	−0,80	78,8 %	42,1 %
B	0,00	15,9 %	15,9 %
C	+0,80	3,6 %	3,6 %
D	−1,50	93,3 %	69,1 %

Ces résultats sont mes calculs à partir des paramètres publiés. Les valeurs incorrectes de A et D correspondent à :

1−Φ(−0,80)≈78,8%,
1−Φ(−1,50)≈93,3%.

Le décalage d
′
/2=1 a donc été omis.

Pour D, en repartant du rapport de coûts plutôt que du critère arrondi :

c=
2
ln(0,05)
	​

≈−1,49787,
F=1−Φ(−0,49787)≈69,07%.

La différence entre 69,07 % et 69,15 % relève de l’arrondi. Aucune des deux méthodes ne donne 93,3 %.

2.3. Pourquoi ce n’est pas simplement un distracteur volontairement faux

Une option incorrecte peut parfaitement contenir une erreur de calcul. Le défaut décisif est ailleurs : Toad D présente les 93,3 % comme la conséquence correcte de l’omission du seul rapport des prévalences. 
raw.githubusercontent.com

Or cette option contient deux erreurs distinctes :

L’omission du rapport P(N)/P(S) pour choisir le critère.

L’omission du décalage d
′
/2 pour transformer ce critère en taux de fausses alarmes.

Le corrigé ne peut diagnostiquer la première tout en approuvant la seconde.

2.4. Deux réparations possibles

Solution la plus simple : conserver un seul piège principal par option. Remplacer les taux de A et D par leurs valeurs compatibles avec les critères affichés :

Option	β	c	F
A	0,20	−0,80	42,1 %
B	1,00	0,00	15,9 %
C	4,95	+0,80	3,6 %
D	0,05	−1,50	69,1 %

Les mauvaises options restent mauvaises parce que leurs critères ne sont pas optimaux.

Pour Toad D :

Ne retenir que le rapport des coûts conduit à β=0,05, puis à c≈−1,50 et à un taux de fausses alarmes d’environ 69,1 %. Ce critère n’est pas optimal : il omet le multiplicateur de prévalence égal à 99.

L’autre solution consiste à conserver les taux incorrects comme pièges supplémentaires, mais Toad doit alors identifier explicitement les deux erreurs.

Décision : Q07-C reste correcte ; la rétroaction D doit être réparée avant certification.

3. Q09 : calcul d’intégration bayésienne validé

Les données fournies donnent :

π
s
	​

=
σ
s
2
	​

1
	​

=
4
1
	​

=0,25,π
p
	​

=
σ
p
2
	​

1
	​

=1.

D’où :

w
s
	​

=
0,25+1
0,25
	​

=0,20,
w
p
	​

=
1,25
1
	​

=0,80.

La clé B est correcte dans le modèle gaussien explicitement posé. Contrairement aux versions précédentes, cette question demande maintenant une application numérique effective. Cette modification est validée. 
GitHub

La conséquence doit conserver sa portée : le prior reçoit ici le poids le plus élevé, sans que l’information sensorielle disparaisse. Avec w
s
	​

=0,20, sa contribution demeure non nulle.

La formule ne justifie pas non plus une règle indépendante du contexte selon laquelle tout signal bruité ferait nécessairement dominer le prior. La conclusion dépend des deux précisions fournies. Le conseil peut simplement commencer par « Avec ces variances… ».

Maintien des autres validations numériques
Item	Résultat confirmé
Q06	d
′
=1,48, c=−0,74, β=e
−1,0952
≈0,33447.
Q07, clé C	β
∗
=4,95, c
∗
≈0,79969, F
∗
≈3,60%.
Q08, corrigé	p(α)=1−
2
1
	​

e
−1
≈81,606%.
Q09	w
s
	​

=0,20, w
p
	​

=0,80.

Le seuil de Q08 reste conforme à la définition utilisée dans l’article de Britten et collaborateurs. Ce résultat n’est pas remis en question. 
CNS NYU

4. Q11-C et Q17-B : remplacement lexical et amélioration évaluative ne sont pas équivalents
Q11-A : la réserve précise est levée

La rétroaction distingue maintenant plasticité associée à l’apprentissage et nécessité universelle de pilotage personnel d’une caméra. La correction demandée est présente. Elle ne doit pas être refusée au motif que les versions antérieures étaient excessives. 
GitHub

Q11-C : le fond de l’ancien distracteur persiste

La nouvelle proposition remplace une destruction anatomique par une dégénérescence synaptique irréversible, mais conserve la même conclusion globale : les aires visuelles seraient indisponibles pour tout recrutement non visuel.

Le changement de vocabulaire ne produit pas, à lui seul, une nouvelle confusion conceptuelle. Ce n’est pas le fait que l’option soit fausse qui pose problème ; c’est le maintien d’une alternative absolue, éloignée de la distinction méthodologique que l’item devrait faire travailler. 
GitHub

Un piège plus utile consisterait à inférer de l’activation occipitale, à elle seule, une expérience subjective identique à celle d’un voyant. La rétroaction pourrait alors distinguer mesure d’imagerie et expérience phénoménologique, sans inventer une incapacité cérébrale générale.

Décision : la correction de Toad A est validée ; le durcissement de C n’est pas suffisamment établi.

Q17-B : un progrès technique, mais une erreur encore composite

La proposition porte désormais sur trois dimensions pertinentes : temporalité, suppression saccadique et voie visuelle. Elle cumule toutefois une durée très anticipée, une abolition intégrale et une attribution parvocellulaire.

Ces dimensions peuvent servir à construire un bon distracteur, mais leur cumul rend le diagnostic moins spécifique : on ne sait pas laquelle l’étudiant a réellement acceptée. La suppression visuelle sélective étudiée dans les travaux de Burr et collaborateurs constitue en outre une question expérimentale distincte de l’allocation attentionnelle testée par Deubel et Schneider. 
ResearchGate

Une alternative centrée sur le résultat spatial serait plus directement alignée sur Q17 :

La discrimination est améliorée de façon identique à la cible de saccade et à une cible secondaire indiquée, sans priorité pour la destination du mouvement.

Elle oppose une prédiction concurrente au résultat visé, sans ajouter plusieurs erreurs physiologiques indépendantes.

Décision : amélioration partielle, non démonstration d’un durcissement intégral. Ce point n’est pas, isolément, le motif déterminant du refus.

5. Les huit items supérieurs : un progrès réel, mais le minimum n’est pas encore solidement démontré
5.1. Trois applications numériques sont maintenant explicites

Q06, Q07 et Q09 comportent bien une tâche d’application. La correction de la rétroaction Q07 demeure nécessaire, mais elle ne transforme pas l’item en simple question de rappel.

Il n’est pas nécessaire d’exiger une dérivation écrite pour reconnaître une application dans un QCM. Inversement, choisir la bonne combinaison de paramètres ne prouve pas que le candidat a recalculé séparément chaque composante : en Q07, le seul β
∗
 peut suffire à identifier C.

Cela ne disqualifie pas l’item. Cela limite ce que son résultat permet d’attester.

5.2. Classement des huit questions revendiquées
Item	Opération effectivement identifiable	Appréciation
Q06	Appliquer les relations entre taux, sensibilité et critère.	Application validée.
Q07	Pondérer les coûts par les probabilités et déterminer un critère.	Application validée, corrigé à réparer.
Q09	Calculer les poids à partir des précisions.	Application validée.
Q01	Distinguer résultat fonctionnel et conclusion anatomique.	Palier 2 défendable dans une lecture qualitative.
Q02	Identifier le contraste auquel se rapporte l’indice.	Palier 2 défendable comme interprétation du plan.
Q03	Choisir un profil conjoint parmi quatre combinaisons.	Amélioration suffisante pour soutenir le palier 2 visé.
Q16	Distinguer résultat d’un contrôle et portée de l’inférence.	Palier 2 défendable comme arbitrage méthodologique.
Q08	Restituer la conclusion de l’étude de Britten.	L’opération supérieure annoncée n’est pas effectivement demandée.

Cette appréciation est un classement expert du contenu, pas une mesure psychométrique empirique. Elle retient favorablement les quatre interprétations qualitatives, sans imposer que toute question supérieure comporte un tableau inédit ou un calcul. 
GitHub
+1

5.3. Q08 reste le maillon non opérationnalisé

La matrice annonce une détermination de seuil. Pourtant, la fonction de Quick/Weibull et l’évaluation à s=α apparaissent dans la rétroaction, non dans une tâche confiée au candidat. Celui-ci doit reconnaître une conclusion déjà étudiée ; il n’a ni seuil à calculer ni résultats fournis à interpréter. 
GitHub

La présence d’un calcul dans Toad ne signifie pas que ce calcul est évalué.

Dans une lecture favorable, le noyau revendiqué comporte donc sept items défendables, pas huit incontestablement opérationnalisés. Le seuil de votre référentiel est bien de huit sur vingt. 
GitHub

La réparation est limitée : fournir la fonction

p(s)=1−
2
1
	​

exp[−(s/α)
γ
]

dans l’énoncé, demander p(α), puis faire sélectionner la portée correcte de la comparaison neurométrique–psychométrique. Le candidat doit alors réellement effectuer l’opération revendiquée.

5.4. La cartographie taxonomique omet Q15

Le préambule classe :

11 items au palier 1+5 au palier 2+3 au palier 3=19.

Q15 est absente des trois listes. Cela ne signifie pas qu’une question manque dans la banque : les vingt items sont présents. C’est leur cartographie qui est incomplète. 
GitHub

Il faut réintégrer Q15 dans le classement retenu et justifier ce choix. L’ajouter arbitrairement au palier supérieur pour atteindre le seuil ne remplacerait pas l’examen de son opération effective.

6. Contrôles métriques : décompte confirmé, espérance annoncée incorrecte
6.1. Distribution des lettres

Le contrôle confirme :

5A,5B,5C,5D.
	​


Cela établit l’équilibre des fréquences, non un biais positionnel psychométrique mesuré à 0 %. Une propriété arithmétique et une propriété du fonctionnement de l’épreuve ne sont pas interchangeables.

6.2. Longueur des options

Le comptage principal utilise les unités séparées par des blancs, expressions LaTeX comprises, lettres A–D exclues.

Situation de la clé	Questions	Effectif
Seule option la plus longue	Q03, Q05, Q08, Q09, Q20	5/20
À égalité maximale	Q01, Q06, Q07, Q19	4/20
Plus courte qu’au moins une option	Les onze autres	11/20

Les effectifs de votre message sont confirmés. En revanche, le préambule du fichier annonce quatre clés strictement maximales, ce qui ne correspond pas à ce comptage. 
GitHub

Les mesures reposent sur une transcription locale des options affichées. Les tentatives de téléchargement binaire direct n’ayant pas abouti, je ne présente pas cette transcription comme une copie brute certifiée du dépôt. La méthode et les vingt lignes de résultats figurent dans l’annexe.

6.3. Les égalités donnent une espérance de 32,5 %, pas de 25 %

Les maxima sont au nombre de deux en Q01, quatre en Q06, quatre en Q07 et deux en Q19.

Avec un choix uniforme parmi les options maximales :

E[concordances]=5+
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

=6,5.

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
es]=32,5%.
	​


Selon le départage, la stratégie peut produire de 5 à 9 concordances sur vingt.

Cinq clés seules en tête ne suffisent pas à ramener cette stratégie au hasard uniforme de 25 %. L’affirmation contraire doit être corrigée.

Cette observation ne rétablit pas l’ancien défaut déterministe : le raccourci 20/20 reste supprimé. Elle ne démontre pas non plus que les étudiants exploiteraient cet indice. C’est une correction du compte rendu métrique, non le motif principal de non-certification.

7. Conditions de clôture et portée de la décision

Les acquis sont substantiels : les principales clés expérimentales corrigées ne présentent pas de nouvelle inversion, les huit piliers restent représentés, les rétroactions et conseils sont présents, et Q09 ajoute une application numérique effective.

La clôture requiert maintenant des modifications limitées :

Priorité	Modification	Critère de vérification
Scientifique	Corriger Q07-D, et harmoniser le traitement de Q07-A.	Chaque taux doit découler du critère indiqué, ou son erreur supplémentaire être explicitement diagnostiquée.
Évaluative	Opérationnaliser réellement Q08, ou un autre huitième item.	L’opération doit être nécessaire au choix avant lecture de Toad.
Distracteurs	Revoir Q11-C et simplifier le piège de Q17-B.	Une erreur principale plausible et identifiable par option.
Documentation	Réintégrer Q15 dans la matrice et corriger les statistiques de longueur.	Vingt items classés une fois ; méthode et égalités explicitement traitées.
Statut	Retirer l’octroi anticipé du sceau de l’en-tête.	Le statut publié doit correspondre à la décision effectivement obtenue.

Il n’est pas nécessaire de reconstruire une dixième banque complète. Les corrections validées doivent être conservées ; les défauts restants doivent être réparés à leur emplacement précis.

L’annexe reproductible de passe 9 contient les calculs, le script de comptage, les vingt mesures et les correctifs ciblés. Le 
tableau des longueurs et les 
correctifs directement applicables sont également accessibles séparément.

Prononcé final

Conformité de Q02-C, Q03, Q04-C et de la restriction de Q11-A : validée.
Calcul numérique de Q09 : validé.
Clé C de Q07 : validée ; rétroaction D : à corriger.
Noyau de huit opérations supérieures : pas encore suffisamment établi.
Sceau d’Excellence « Étalon-Or » : non accordé à la passe 9.

Enfin, un audit expert de contenu ne peut pas, à lui seul, acter un verrouillage psychométrique complet : il ne mesure ni la discrimination observée des items ni la fidélité du score. Le refus actuel ne repose toutefois pas sur l’absence de ces données ; il repose sur une erreur mathématique vérifiable dans le corrigé et sur des réserves de construction encore présentes.