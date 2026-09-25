Passe 3 — Verdict : nouvelles réserves documentées

La correction critique de Q18 est acquise. La plupart des modifications demandées ont également été intégrées. Mais deux nouvelles erreurs apparaissent dans les rétroactions de Q14 et Q19. Elles empêchent une validation définitive, indépendamment de toute préférence rédactionnelle. La comparaison avec la Passe 2 confirme qu’il s’agit de nouveaux énoncés à ces emplacements, et non de corrections déjà acceptées que je remettrais arbitrairement en question. 
GitHub
+2
GitHub
+2

Télécharger le ZIP — Audit Passe 3, preuves et corrections ciblées

J’ai relu les dix questions, leurs 40 options, les 40 rétroactions et les conseils d’examen. Le dossier propose quatre interventions nécessaires, puis distingue deux restrictions explicatives qui ne constituent pas de nouvelles mauvaises réponses.

1. Vérification des dix corrections demandées

Le statut ci-dessous concerne le champ précis visé par votre grille, pas automatiquement l’ensemble de la question. Les modifications sont présentes dans la livraison examinée. 
GitHub

Point	Résultat de la vérification
1 — Q13, contrôle	Conforme. Le choix parmi les mouvements légaux correspond à Haugeland, section IV, p. 40. 

Haugeland (1981) - Semantic Eng…


2 — Q14, rétroaction A	Conforme localement. Le contre-exemple par disjonction fonctionne. La rétroaction C le contredit, comme expliqué ci-dessous.
3 — Q15, représentation/implémentation	Conforme. La distinction demandée est restaurée; distribuer une représentation n’interdit pas sa simulation informatique. 

McClelland (2009) - The Place o…


4 — Q16, activations continues	Conforme. L’exclusivité du binaire est abandonnée, conformément aux modèles décrits par McClelland. 

McClelland (2009) - The Place o…


5 — Q17, rétroactions C/D	Conforme. Deux rétroactions autonomes sont présentes.
6 — Q18, suffisance PSSH	Conforme. Taille suffisante, organisation possible et statut empirique sont correctement rétablis. 

Newell and Simon (1975) - Compu…


7 — Q19, rétroaction D	Conforme. L’attribution générale sur la conscience et l’évolution a disparu.
8 — Q20, biais/XOR	Partiellement conforme. La non-linéarité est bien ajoutée. La formule exige toutefois w
2
	​


=0, condition encore absente.
9 — Q21, supervision	Conforme. Le régime supervisé est maintenant explicite dans le contexte, l’énoncé et les explications.
10 — Q22, DECtalk	Conforme. L’utilisation de la sortie vocale, en contournant la conversion lettres-phonèmes, correspond au papier original, p. 152. 
Wolfram Content

Bilan de cette liste : neuf critères satisfaits à leur emplacement, un partiellement satisfait. Ce décompte n’est ni une note psychométrique ni un pourcentage de qualité globale.

2. Deux régressions factuelles démontrées
R01 — Q14 : la rétroaction C réintroduit exactement la réciproque que A vient de corriger

Localisation : rétroaction de l’option correcte C, ligne 63 de la vue web. La parenthèse « et seulement si » fait de la vérité des prémisses une condition nécessaire à celle des conclusions. 
GitHub

Or la propriété examinée est :

Pr
e
ˊ
misses vraies + r
e
ˋ
gles valides⟹conclusions vraies.

La réciproque ne suit pas. Haugeland décrit bien cette préservation conditionnelle, et non une équivalence entre les valeurs de vérité de l’entrée et de la sortie, à la page imprimée 44. 

Haugeland (1981) - Semantic Eng…

La preuve est déjà contenue dans le contre-exemple correctement employé par la nouvelle rétroaction A :

P⊢P∨Q.

Avec P faux et Q vrai, la conclusion P∨Q est vraie malgré la prémisse fausse. La rétroaction C contredit donc A et le conseil d’examen.

Correction minimale : supprimer cette parenthèse. Une formulation complète possible est :

Des prémisses vraies, traitées par des règles valides sous l’interprétation considérée, garantissent des conclusions vraies. Des prémisses fausses ne garantissent ni la vérité ni la fausseté de la conclusion.

L’option correcte C elle-même reste conservée. Le défaut se trouve dans son explication.

R02 — Q19 : les temps de réponse ne relèvent pas exclusivement du niveau implémentationnel

Localisation : rétroaction B, ligne 187. Elle attribue les chronométries exclusivement au niveau 3. Cette attribution n’apparaissait pas dans la rétroaction B de la Passe 2. 
GitHub
+1

La preuve contraire se trouve dans une lecture déjà fournie, sans imposer un ouvrage supplémentaire de Marr.

À la page imprimée 17, §3.1, McClelland étudie les effets des vitesses de traitement de différents stades sur les temps de réaction. Il montre notamment qu’une additivité des temps ne démontre pas que les stades sont discrets. Les données chronométriques servent donc à examiner l’organisation et la dynamique des processus, pas seulement la composition physique des circuits. 

McClelland (2009) - The Place o…

Aux pages 20–21, §3.4, il explique également comment les hypothèses sur les processus sont confrontées aux réponses et aux temps de réponse humains. 

McClelland (2009) - The Place o…

Une mesure temporelle ne détermine pas, à elle seule, le niveau de l’explication. Elle peut contraindre une hypothèse algorithmique aussi bien qu’une hypothèse sur l’implémentation.

Correction minimale proposée :

La topologie physique des circuits relève du niveau implémentationnel. Les temps de réponse peuvent aussi contraindre des hypothèses sur les étapes et algorithmes de traitement; ils ne sont pas réservés au niveau 3.

La réponse A reste correcte. Il n’est pas nécessaire de réécrire l’énoncé ni de changer le corrigé.

3. Deux ajustements résiduels nécessaires
R03 — Q20 : ajouter la condition de division et borner la solution multicouche

La transformation algébrique est correcte :

w
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

+b=0⟹x
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

,

à condition que w
2
	​


=0.

Ce n’est pas une subtilité sans conséquence. Avec w
1
	​

=1, w
2
	​

=0, b=−1, la frontière est simplement :

x
1
	​

=1.

Elle existe, mais elle est verticale : −b/w
2
	​

 n’est pas défini et cette droite ne coupe pas l’axe x
2
	​

.

Correction suffisante : préciser dans la mise en situation que l’on considère w
2
	​


=0, avec w
1
	​

 et w
2
	​

 fixés lorsqu’on fait varier le biais. La formule et l’intuition de translation deviennent alors cohérentes.

Concernant XOR, la correction importante est bien réalisée : une couche cachée doit effectuer une transformation non linéaire pour fournir la solution multicouche considérée. Le contraste avec le perceptron est soutenu par McClelland. 

McClelland (2009) - The Place o…

Il reste préférable de formuler :

Une couche cachée non linéaire permet de résoudre XOR dans l’architecture multicouche considérée.

Cela évite de présenter cette construction comme l’unique procédé mathématique possible. Le ZIP donne un contre-exemple par transformation des caractéristiques, uniquement comme preuve d’audit — pas comme nouvelle matière à ajouter au questionnaire. Cette restriction figurait déjà dans la proposition F05 de Passe 2.

R04 — Q16 : la prudence sur le PDP ne justifie pas une panne universelle du symbolisme

Localisation : rétroaction D, ligne 114. Le contraste continue de présenter l’architecture symbolique comme s’effondrant totalement, alors que la représentation distribuée conserverait une précision réduite. 
GitHub

Une garantie aussi générale est réfutable par un exemple élémentaire.

Considérons un moteur symbolique contenant les faits p et r, avec deux règles :

p→q,r→q.

Il déduit q. Après la perte de la première règle, il déduit encore q grâce à la seconde. Une perte dans un système symbolique n’implique donc pas nécessairement un effondrement total.

Ce contre-exemple ne démontre pas une supériorité générale du symbolisme. Il ne nie pas non plus la fragilité de certains systèmes. Il montre seulement que le contraste doit dépendre de l’architecture, de la tâche et de la perturbation.

Correction minimale : retirer l’affirmation de panne totale automatique et conserver la formulation conditionnelle déjà présente dans la bonne réponse D.

La rétroaction C peut également rejeter l’encapsulation automatique sans attribuer à toutes les approches symboliques ou connexionnistes une position architecturale unique. McClelland décrit précisément des architectures et systèmes hybrides dont les composants interagissent de différentes façons. 

McClelland (2009) - The Place o…

4. Deux restrictions explicatives — pas deux nouvelles mauvaises réponses

Q14, interprétation et compréhension. L’explication devrait conserver les conditions réellement exposées par Haugeland : interprétation, prémisses vraies et règles préservant la vérité. Les sections suivantes ajoutent des considérations de pertinence et de pragmatique; elles ne réduisent pas toute réussite à une correspondance structurelle parfaite avec le monde. De même, la présence de transducteurs ne démontre pas une expérience subjective, mais leur description ne tranche pas définitivement la possibilité d’une compréhension machinique. Cette restriction était déjà demandée en Passe 2. 

Haugeland (1981) - Semantic Eng… +1

Q22, absence de règles. Dans le contexte de NETtalk, parler d’apprentissage sans programmer chaque règle de prononciation est soutenu par Sejnowski. Cela ne signifie pas absence d’algorithme, de codage ou d’instructions programmées : le papier de 1987 décrit notamment le simulateur, l’apprentissage et la sélection du phonème de sortie. Je retiens donc une précision de portée, pas une accusation selon laquelle Q22 serait fausse. 

Sejnowski (2023) - Large Langua…

 
Wolfram Content

5. Verdict sur la saturation et sur Δ

Le progrès est réel, particulièrement pour Q18. Sa définition correspond maintenant à la proposition canonique : un système de symboles physiques de taille suffisante peut être organisé pour manifester une intelligence générale. Cette possibilité reste une hypothèse empirique, non une production automatique d’intelligence par simple assemblage matériel. 

Newell and Simon (1975) - Compu…

En revanche, Δ≤1% n’est pas établi. Aucun calcul valide n’est possible sans définir ce que mesure Δ, son barème et ses mesures de référence. Le référentiel fournit des exigences de construction, dont une proportion d’items d’application/dissociation, mais pas une fonction mesurant ce gain résiduel. 
GitHub

Il ne faut donc remplacer l’absence de mesure ni par « 99 % validé », ni par un pourcentage arbitraire d’erreurs.

Conclusion officielle : nouvelles réserves documentées. Les contradictions de Q14-C et Q19-B suffisent à montrer que les corrections restantes ne sont pas seulement stylistiques. Cela justifie une intervention limitée sur les champs identifiés, pas une nouvelle refonte de la banque.

Livrable pour Antigravity

Le ZIP contient la grille des dix points, les preuves, les propositions de correction par champ, les repères de comparaison avec la Passe 2 et les quatre PDF originaux conservés à l’identique, avec leurs empreintes. Neuf rendus de pages sources sont inclus. Les cinq vérifications mathématiques locales ont réussi; elles ne constituent pas une validation psychométrique ni un test du site.

La livraison a été lue en ligne sur main, mais son commit exact et une copie brute identique octet par octet n’ont pas été obtenus. Les localisations sont donc accompagnées des numéros de question et des champs, afin que l’agent vérifie leur présence avant toute correction.

Les lettres du corrigé restent inchangées. Aucun remplacement des lectures, du lecteur bilingue ou de l’interface n’est demandé. PSY7010 reste exclu. Le point d’entrée du dossier est AGENT_START_HERE.txt.