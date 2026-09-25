Audit doctoral contradictoire — Séance 1, passe 11
Décision : avis favorable — Sceau « Étalon-Or » de contenu et de conception sommative accordé

Oui. Les réserves bloquantes de passe 10 sont levées. La nouvelle Q08 sépare correctement le calcul du seuil et la portée de l’inférence causale ; Toad C respecte désormais cette distinction. Le recomptage confirme également 4–5–11, une espérance de concordance de 30,0 % pour la stratégie de longueur avec départage uniforme, et cinq clés de chaque lettre.

J’accorde donc le Sceau « Étalon-Or » dans le cadre de votre dispositif interne d’audit de contenu et de conception sommative, pour la séance 1, version Passe 11 examinée. Il ne s’agit ni d’une homologation délivrée par l’UQAM ni d’une validation psychométrique empirique.

Demande de clôture	Décision
Matrice Q08 : calcul × portée causale	Validée.
Retenue méthodologique de Toad C	Validée.
Décomptes 4–5–11 et espérance de 30 %	Confirmés par recalcul.
Distribution 5 A, 5 B, 5 C, 5 D	Confirmée.
Certification interne de contenu et de conception — Séance 1	Accordée pour le texte examiné.

Version de référence : contenu affichant explicitement Passe 11, consulté le 25 septembre 2026. L’outil renvoyait une version antérieure pour l’URL sans paramètre ; ce contenu ancien n’a pas servi à juger les corrections actuelles. 
GitHub
+1

1. Q08 : les deux dimensions sont maintenant effectivement distinguées
1.1. Le calcul est correct

La fonction fournie est :

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

d’où :

p(α)=1−
2
1
	​

e
−1
=0,8160602794…≈81,6%.
	​


Le distracteur numérique résulte d’une erreur identifiable :

1−e
−1
=0,6321205588…≈63,2%.

Il omet le coefficient 1/2, lequel permet ici à la fonction de respecter un niveau de hasard de 50 % lorsque le signal est nul. Le seuil conventionnel d’environ 82 % correspond bien à la définition utilisée par Britten et collaborateurs. 
CNS NYU

1.2. La matrice 2 × 2 est conforme
Option	Calcul du seuil	Conclusion sur le décodage	Diagnostic approprié
A — clé	81,6 % : correct	Prudente	Les deux composantes sont correctes.
B	63,2 % : incorrect	Prudente	Omission du coefficient 1/2.
C	81,6 % : correct	Excessive	Attribution causale exclusive injustifiée.
D	63,2 % : incorrect	Excessive	Cumul des deux erreurs.

L’ancien encadrement ne suffit plus à isoler la clé, puisque 63,2 % et 81,6 % appartiennent tous deux à l’intervalle ouvert entre 50 % et 100 %.

Le calcul correct retient A et C. La conclusion méthodologiquement prudente retient A et B. Leur intersection identifie A.

La correction prescrite en passe 10 est donc réalisée : les alternatives permettent de distinguer les deux composantes de l’objectif, au lieu de rendre l’une inutile pour sélectionner la réponse. Cette conformité concerne la construction de l’item ; une réponse correcte ne révèle évidemment pas toute la démarche mentale effectivement suivie par chaque candidat. 
raw.githubusercontent.com

1.3. Toad C respecte maintenant la limite de l’inférence

La comparabilité des seuils renseigne sur la sensibilité des neurones étudiés dans les conditions de la tâche. Elle ne permet pas, à elle seule, d’identifier le nombre de neurones dont les signaux déterminent effectivement la décision de l’animal.

Cette prudence est justifiée par l’article lui-même : les simulations montrent que l’interprétation dépend notamment des hypothèses de sélection des neurones, de corrélation de leurs réponses et de combinaison des signaux. Plusieurs configurations peuvent être compatibles avec les observations. 
CNS NYU
+1

La nouvelle rétroaction évite les deux surinterprétations : elle ne conclut ni à une commande exclusive par un neurone unique, ni à une démonstration directe d’une architecture distribuée particulière. La compatibilité avec un décodage de population est correctement distinguée de sa preuve exclusive.

Décision : Q08, sa clé et ses quatre diagnostics répondent aux correctifs demandés. Aucune nouvelle refonte de cet item n’est requise pour clôturer la réserve de passe 10.

2. Préambule métrique : réconciliation confirmée
2.1. Méthode du contrôle

Le comptage principal porte sur les unités séparées par des blancs, lettres A–D exclues et expressions LaTeX conservées. Il ne s’agit donc ni d’un décompte linguistique strict des mots ni d’une mesure de largeur après rendu.

Les mesures reposent sur une transcription locale confrontée aux options publiées. Le téléchargement binaire direct n’ayant pas abouti, je ne présente pas cette transcription comme une copie brute certifiée du dépôt. L’annexe contient la méthode, les vingt lignes de résultats et le script reproductible.

2.2. Résultat exhaustif par catégorie
Situation de la clé	Questions	Effectif
Seule option la plus longue	Q03, Q05, Q09, Q20	4/20 — 20 %
À égalité à la longueur maximale	Q01, Q06, Q07, Q08, Q19	5/20 — 25 %
Plus courte qu’au moins une option	Les onze autres	11/20 — 55 %

Pour la nouvelle Q08, le comptage donne :

A=46,B=46,C=41,D=40.

La clé A reste donc à égalité maximale avec B. La réécriture n’a pas modifié la catégorie métrique de cet item.

2.3. Espérance exacte avec départage uniforme

Les cinq égalités comprennent respectivement deux, quatre, quatre, deux et deux options maximales.

E[S]=4+
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

Ainsi :

E[S]/20=30,0%.
	​


Le décompte 4–5–11 et l’espérance de 30 % sont confirmés. Selon le départage des égalités, la stratégie produit entre quatre et neuf concordances avec les clés annoncées.

Cette espérance décrit une règle appliquée aux options. Elle ne mesure pas son utilisation réelle par les étudiants et ne démontre pas l’absence de tout biais rédactionnel. En revanche, le raccourci déterministe permettant de reproduire les vingt clés reste supprimé.

La nouvelle formulation d’équilibre des fréquences, plutôt que de « biais nul », est également appropriée :

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

=5.
	​

3. Maintien des validations antérieures
3.1. Calculs de contrôle

Aucune régression n’est relevée dans les résultats numériques centraux vérifiés :

Item	Résultat maintenu
Q06	d
′
=1,48, c=−0,74, β=e
−1,0952
≈0,33447.
Q07 — clé C	β
∗
=4,95, c
∗
=ln(4,95)/2≈0,799694, F
∗
≈3,595%.
Q07 — options A et D	42,1 % et 69,1 %, calculés à partir des valeurs arrondies de c affichées.
Q09	w
s
	​

=0,20 et w
p
	​

=0,80, pour les précisions fournies.

Pour Q07, la validation reste celle déjà précisée en passe 10 : les pourcentages sont cohérents avec la chaîne d’arrondis annoncée. Il n’y a pas lieu d’exiger simultanément une égalité exacte entre tous les nombres arrondis de chaque triplet.

3.2. Cartographie taxonomique

La répartition demeure complète :

11 items au palier 1+6 au palier 2+3 au palier 3=20.

Les neuf items supérieurs sont :

Q01, Q02, Q03, Q06, Q07, Q08, Q09, Q15, Q16.

Ils représentent :

20
9
	​

=45%.

La classification interne déjà admise est maintenue. La nouvelle Q08 renforce désormais la correspondance entre l’opération annoncée et les alternatives proposées. La présence des huit piliers reste également acquise. 
GitHub

Ces constats portent sur la couverture et la conception. Ils ne transforment pas les catégories taxonomiques en estimations de difficulté observée.

4. Observation de mise en forme non bloquante

Dans la restitution textuelle consultée, la formule d’espérance du préambule présente encore des commandes de fraction tronquées. Les valeurs sont correctes ; c’est leur affichage qui doit être sécurisé. Je ne conclus pas à l’origine binaire exacte de cette anomalie à partir du seul rendu de l’outil. 
GitHub

Une ligne de remplacement évitant ce problème serait :

Espérance de concordance de la stratégie de longueur maximale, avec choix uniforme parmi les options ex æquo : 4 + 0,5 + 0,25 + 0,25 + 0,5 + 0,5 = 6 réponses sur 20, soit 30,0 %.

Cette reprise relève de la préparation de la version distribuée. Elle ne modifie ni le calcul, ni les clés, ni la décision de clôture et n’appelle pas une nouvelle passe scientifique.

5. Portée exacte du sceau accordé

La désignation demandée est maintenant correctement circonscrite : contenu et conception sommative de la séance 1. Le préambule distingue cette évaluation d’une validation psychométrique fondée sur les résultats d’une cohorte. 
GitHub

L’octroi signifie que les réserves bloquantes suivies en passe 10 sont levées, avec maintien des acquis précédemment acceptés. Il ne signifie pas que l’instrument serait soustrait à toute amélioration ultérieure.

La difficulté réelle, la discrimination des items, la fidélité du score et le fonctionnement observé des distracteurs restent à estimer à partir des passations. Cette distinction ne constitue plus un motif de refus : elle fait désormais partie du périmètre expressément accepté de la certification.

La décision ne s’étend pas à la séance 2, qui n’est pas examinée ici, ni à toute modification future du fichier sur main.

Prononcé final

Le Sceau d’Excellence « Étalon-Or » de contenu et de conception sommative est accordé, dans le cadre de cet audit interne, à la banque de la séance 1 — Dave Saint-Amour — dans sa version Passe 11 examinée le 25 septembre 2026.

Les réserves bloquantes de passe 10 sont clôturées. L’observation typographique signalée est non bloquante. La validation psychométrique empirique demeure une évaluation distincte.

Le 
rapport de décision archivable et l’annexe reproductible complète sont disponibles. Le 
tableau des vingt contrôles de longueur permet également de vérifier séparément le décompte final.