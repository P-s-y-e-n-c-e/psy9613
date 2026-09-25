# 🧠 SYNTHÈSE PÉDAGOGIQUE MAÎTRESSE — SÉANCE 2 (PSY9613)
**Cours :** Perception, cognition et intelligence artificielle (Automne 2026)  
**Enseignants :** Pr Pierre Poirier & Pr Dave Saint-Amour (Département de philosophie & Département de psychologie, UQAM)  
**Thématique officielle :** Intelligence artificielle : Perspectives historiques (problématiques et conceptuelles)  
**Supports certifiés de référence :**
* `PSY9613-02_GOLD.md` (Transcription GOLDEN ENCORA intégrale du cours magistral de Pierre Poirier, 1 286 lignes, 21 septembre 2026)
* `notes_seance_02_2026-09-21.md` (Horodatages EDT réels, repères mot à mot et transitions de diapositives)
* `Introduction générale au cours PSY9613-2026.pdf` (Diapositives 1 à 114)
* **Lectures obligatoires & suggérées du corpus :**
  * Haugeland, J. (1981). *Semantic Engines: An Introduction to Mind Design*.
  * Newell, A. & Simon, H. A. (1975). *Computer Science as Empirical Inquiry: Symbols and Search* (Turing Award Lecture).
  * McClelland, J. L. (2009). *The Place of Modelling in Cognitive Science*.
  * Sejnowski, T. J. (2023). *Large Language Models and the Reverse Turing Test* (Sections 6 & 7).

---

## 🧭 Cadrage Épistémologique & Règle d'Or de l'Examen

> [!IMPORTANT]
> **Consigne solennelle du Pr Pierre Poirier aux étudiants (Vérité terrain `PSY9613-02_GOLD.md` à 02:26:06) :**  
> *« Les examens portent principalement sur la matière vue en cours, et les lectures servent à réviser et à structurer ces notions. Aucune question d'examen ne portera sur un point abordé uniquement dans un texte sans avoir été discuté en classe. »*  
> Cette synthèse et la banque de questions associée se concentrent donc exclusivement sur les concepts, distinctions, démonstrations formelles et controverses que le professeur a explicitement exposés et approfondis en classe.

---

## 🏛️ SECTION 1 : LE PARADOXE CARTÉSIEN & LE PROBLÈME FONDAMENTAL DE L'ESPRIT (1634)

### 1. Contexte historique et genèse : René Descartes aux Pays-Bas
En 1634, exilé aux Pays-Bas, René Descartes achève la rédaction conjointe de deux ouvrages fondateurs :
1. Le *Traité du monde* (physique mécaniste, cosmologie héliocentrique).
2. Le *Traité de l'homme* (physiologie mécaniste et première tentative de naturalisation des fonctions corporelles et psychologiques).

Suite à la condamnation de Galilée par l'Inquisition à Rome en 1633, Descartes choisit de ne pas publier ces textes de son vivant. Le *Traité de l'homme* ne paraîtra qu'à titre posthume en 1662 (latin) et 1664 (français).

### 2. Le corps comme machine hydraulique
Inspiré par les automates hydrauliques royaux des grottes des jardins de Saint-Germain-en-Laye (conçus par les frères Francini, où les visiteurs marchaient sur des dalles cachées déclenchant des mouvements de fontaines et de statues articulées), Descartes applique cette machinerie au vivant :
* **Tuyaux :** Les nerfs sont des conduits creux traversés par un fluide subtil.
* **Fluide sous pression :** Les « esprits animaux » (*spiritus animalis*), particules matérielles très fines et rapides distillées par la chaleur du cœur.
* **Muscles et réservoirs :** Les cavités cérébrales (ventricules) et la glande pinéale régulent l'afflux des esprits vers les muscles pour commander les contractions réflexes.
* **Capacité des automates :** Pour Descartes, un automate physique sophistiqué peut parfaitement accomplir la digestion, la circulation sanguine, la respiration, la veille, le sommeil, les réflexes d'évitement de la douleur (retrait de la jambe face au feu) et même la mémoire associative animale.

### 3. Les deux critères de démarcation cartésienne (L'irréductibilité de l'esprit)
Dans la cinquième partie du *Discours de la méthode* (1637) reprise dans les diapositives 5 à 7, Descartes pose formellement qu'une machine matérielle, même infiniment complexe, échouera toujours à deux tests discriminants :

#### A. Le premier moyen : L'argument du langage et de la productivité
> *« Jamais elles ne pourraient user de paroles, ni d'autres signes en les composant, comme nous faisons pour déclarer aux autres nos pensées. »*
* Une machine peut émettre des sons ou prononcer des mots isolés par déclenchement mécanique (ex: appuyer sur un bouton pour entendre une phrase).
* En revanche, aucune machine ne peut combiner dynamiquement et réarranger des mots pour répondre de façon appropriée au sens infini des situations de la vie courante, ce que même « les hommes les plus hébétés » ou idiots sont capables de faire.

#### B. Le second moyen : L'argument de la raison universelle vs la disposition particulière des organes
> *« La raison est un instrument universel, qui peut servir en toutes sortes de rencontres, au lieu que ces organes ont besoin de quelque particulière disposition pour chaque action particulière. »*
* Dans un automate physique, chaque comportement requiert une configuration matérielle dédiée (un rouage, une came, un levier ou un canal spécifique).
* Face à la variété infinie des circonstances de l'existence, il est moralement et physiquement impossible à un mécanisme matériel fini de contenir assez de dispositions particulières pour réagir de façon judicieuse à toutes les occurrences de la vie.
* La raison humaine, étant immatérielle (âme raisonnable / *res cogitans*), n'est pas contrainte par la finitude géométrique des rouages.

### 4. La formulation moderne du Paradoxe Cartésien
Pierre Poirier formalise ce dilemme sous la forme d'un affrontement entre deux contraintes cognitives majeures (Diapos 12 à 14) :
$$\begin{cases}
\textbf{Contrainte 1 (Mécaniste / Physique) :} & \text{Le système cognitif est incarné dans un substrat matériel fini (cerveau/ordinateur).} \\
\textbf{Contrainte 2 (Représentationnelle / Cognitive) :} & \text{L'esprit fait preuve d'une productivité infinie (infinité de pensées et de phrases possibles).}
\end{cases}$$
* **Le problème de la cognition :** Comment un mécanisme matériel strictement fini peut-il engendrer, stocker et manipuler une infinité de représentations distinctes ?

---

## 🕹️ SECTION 2 : TURING, CHOMSKY & LA SOLUTION COMPUTATIONNELLE SYMBOLIQUE

### 1. Alan Turing (1950) et le Jeu de l'Imitation
Dans son article princeps *Computing Machinery and Intelligence* (*Mind*, 1950, Diapos 9–10) :
* Turing remplace la question métaphysique « Les machines peuvent-elles penser ? » par un test opérationnel empirique : le Jeu de l'Imitation (*The Imitation Game*).
* Si un interrogateur humain communique par téléscripteur (texte pur) avec deux interlocuteurs cachés (un humain et une machine) et ne parvient pas à distinguer les réponses de la machine de celles de l'humain à un taux significativement supérieur au hasard, la machine doit être considérée comme intelligente.
* **Poirier réactualise le test pour les étudiants :** Le test de Turing évalue nos intuitions profondes d'attribution d'esprit. Face à une copie d'étudiant corrigée sans savoir si elle a été rédigée par un humain ou ChatGPT, à quel moment accorde-t-on le statut d'intelligence ?
* **Turing vs Descartes :** Descartes affirmait qu'aucune machine ne passerait jamais ce test linguistique. Turing affirme qu'un ordinateur doté d'une capacité de mémoire d'environ $10^9$ bits pourra tromper l'interrogateur dans 30 % des cas après 5 minutes de dialogue.

### 2. Noam Chomsky et la linguistique cartésienne (1966)
Comment briser le paradoxe cartésien ? Noam Chomsky (*Cartesian Linguistics*, 1966, Diapos 18–20) redécouvre la formule du philosophe et linguiste Wilhelm von Humboldt :
> *« La langue fait un usage infini de moyens finis. »*
* **La solution formelle : Les systèmes de processus récursifs.**
* Une grammaire générative est constituée d'un ensemble fini de règles syntaxiques capables de s'appliquer à leurs propres résultats (récursivité).
* Exemple du cours (Diapo 19) : L'emboîtement propositionnel :
  $$\text{Phrase} \to \text{Chatterer said } [\text{Buster thought } [\text{the tree was tall}]]$$
* **Conclusion théorique :** La computationnalité et la récursivité fournissent le pont conceptuel permettant à un mécanisme fini de produire une infinité de représentations !

---

## ⚙️ SECTION 3 : SYSTÈMES FORMELS, SFA & MOTEURS SÉMANTIQUES (HAUGELAND, 1981)

### 1. La Machine de Turing (1936)
Dans *On Computable Numbers* (1936, Diapos 17 & 23) :
* Turing formalise la notion de calculabilité mécanique :
  1. Un ruban de mémoire infini divisé en cases contenant des symboles d'un alphabet fini $\Sigma$.
  2. Une tête de lecture/écriture capable de lire, effacer, écrire un symbole, et se déplacer d'une case vers la gauche ou la droite.
  3. Un registre d'états internes finis $Q$.
  4. Une table de transition discrète (programme).
* **Machine de Turing Universelle (UTM) :** Une machine capable d'exécuter n'importe quel calcul en lisant le code descriptif d'une autre machine de Turing encodé sur son propre ruban.

### 2. Définition rigoureuse d'un Système Formel (Haugeland, 1981)
Selon John Haugeland (*Semantic Engines*, 1981) et Pierre Poirier (Diapos 24 à 28), un jeu ou système formel repose sur une triade indissociable :
1. **Un ensemble fini de pièces discrètes ($\Sigma$) :** Symboles ou pions physiques/abstraits clairement discriminables.
2. **Une ou des positions de départ autorisées :** État initial légitime du système.
3. **Un ensemble de règles formelles de transition :** Lois mécaniques déterminant sans ambiguïté les coups légaux pour passer d'un état à un autre.

#### Exemples paradigmatiques analysés en classe :
* **Le Tic-Tac-Toe (Morpion) :** Pièces $\Sigma = \{X, O\}$, position de départ = grille vide $3 \times 3$ $\langle 1,\dots,9 \rangle$, règles de transition = alternance stricte des joueurs sans écrasement de case.
* **Le jeu d'Échecs :** Pièces aux géométries et mouvements différenciés.
* **La Logique Propositionnelle formelle :** Pièces = variables propositionnelles ($p, q, r$) et connecteurs ($\land, \lor, \neg, \to$), position de départ = axiomes, règles = Modus Ponens et substitution.

### 3. Le principe d'Indépendance par rapport au Médium (Medium Independence)
> *« Un système formel est indépendant de son substrat physique d'implémentation. »* (Diapo 26)
* Le jeu de Tic-Tac-Toe ou d'échecs reste strictement le même qu'il soit joué avec des morceaux de bois sculptés, tracé au doigt dans le sable, gravé sur du marbre, ou simulé électroniquement par des impulsions de tension dans des transistors en silicium.
* L'esprit, s'il est un système formel, peut être réalisé dans du tissu neuronal biologique comme dans un circuit informatique : c'est la thèse de la **réalisabilité multiple** (*multiple realizability*).

### 4. Systèmes Formels Automatiques (SFA) & Automates à États Finis (FSA)
Un SFA est un système formel qui manipule ses pièces de façon entièrement mécanique et autonome, sans intervention d'un arbitre humain.
* **Modèle mathématique d'un automate à états finis (Diapo 31) :**
  $$M = \langle \Sigma, Q, q_0, F, \delta \rangle$$
  * $\Sigma$ : Alphabet fini d'entrée.
  * $Q$ : Ensemble fini d'états internes.
  * $q_0 \in Q$ : État initial.
  * $F \subseteq Q$ : Ensemble des états finaux ou acceptants.
  * $\delta : Q \times \Sigma \to Q$ : Fonction de transition déterministe.
* **Exemples concrets présentés par le professeur :**
  1. *La porte automatique de supermarché (Diapo 32) :* États $Q = \{\text{Fermé}, \text{Ouvert}\}$. Entrées $\Sigma = \{\text{Personne devant}, \text{Personne derrière}, \text{Rien}\}$. Transitions de sécurité.
  2. *La machine distributrice de Coca-Cola (Diapo 33) :* États monétaires accumulés (0¢, 25¢, 50¢, 75¢, 1$). La pièce de monnaie fait transiter la machine vers un état supérieur jusqu'au relâchement mécanique de la canette.
* **Pourquoi les FSA sont-ils insuffisants pour modéliser l'esprit humain ? (Diapo 34–35)**
  * Un automate fini ne possède qu'une mémoire interne bornée par $|Q|$.
  * Il est incapable de reconnaître des langages à dépendances récursives arbitrairement longues comme $a^n b^n$ (il ne peut pas compter un nombre infini de parenthèses fermantes correspondant aux parenthèses ouvrantes).
  * Il faut l'adjonction d'une mémoire externe (pile ou ruban infini) pour atteindre la puissance d'une Machine de Turing.

### 5. La Fonction d'Interprétation & Les Moteurs Sémantiques (Haugeland, 1981)
Comment un mécanisme aveugle qui ne fait que pousser des symboles selon des règles purement syntaxiques peut-il avoir du sens ?
* **La maxime de Haugeland (1981) :**
  > *« Take care of the syntax, and the semantics will take care of itself. »*  
  > *(Prenez soin de la syntaxe, et la sémantique prendra soin d'elle-même).*
* **Fonction d'interprétation ($f$) :** Homomorphisme mathématique qui associe à chaque symbole formel syntaxique (domaine) un objet, une propriété ou un fait du monde réel (co-domaine).
* **L'analogie du terrain de soccer (Diapo 43) :**
  * Pierre Poirier illustre la fonction d'interprétation par un simulateur tactique de soccer :
  * Les symboles $J_1, J_2$ représentent des joueurs réels.
  * L'opération syntaxique formelle $\text{Passe}(J_1, J_2)$ sur le tableau correspond à l'événement physique du ballon projeté sur le gazon entre les deux athlètes.
* **Moteur Sémantique :** Machine automatique formelle dont la manipulation syntaxique interne préserve mécaniquement la vérité des interprétations sémantiques dans le monde extérieur.

---

## 📐 SECTION 4 : COMPUTATIONNALISME, PSSH & LES TROIS NIVEAUX DE DAVID MARR

### 1. Physical Symbol System Hypothesis (PSSH — Newell & Simon, 1975)
Dans leur conférence de réception du Prix Turing (1975), Allen Newell et Herbert Simon formulent la charte de l'intelligence artificielle classique :
> *« A physical symbol system has the necessary and sufficient means for general intelligent action. »*
1. **Condition nécessaire :** Tout système biologique ou artificiel capable d'intelligence générale est obligatoirement un système physique de manipulation de symboles.
2. **Condition suffisante :** Tout système physique de symboles, pourvu qu'il soit d'une échelle et d'une organisation adéquates, est capable de produire une action intelligente générale.

### 2. Les Trois Niveaux d'Explication de David Marr (1982, *Vision*)
David Marr (neurobiologiste passé par le laboratoire de Minsky au MIT) formalise trois niveaux d'analyse indispensables pour expliquer un système de traitement de l'information (Diapos 46 à 53) :
1. **Niveau Computationnel (Niveau 1 — *What & Why*) :**
   * Quel est le but de la computation ? Pourquoi cette stratégie est-elle adaptée à la survie ou à la tâche ? Quelle est la logique formelle du problème ?
   * Ex: Le but de la vision est de déduire la géométrie 3D invariante des objets à partir des flux de luminance 2D captés par la rétine.
2. **Niveau Algorithmique / Représentationnel (Niveau 2 — *How*) :**
   * Quel système de représentations encode les entrées et les sorties ? Quel algorithme séquentiel précis transforme la représentation d'entrée en représentation de sortie ?
   * Ex: Représentation en esquisse brute (*primal sketch*), esquisse 2.5D centrée sur l'observateur, puis modèle 3D centré sur l'objet.
3. **Niveau Physique / Implémentationnel (Niveau 3 — *Hardware*) :**
   * Comment les représentations et les algorithmes sont-ils physiquement réalisés dans la matière biologique ou le silicium ?
   * Ex: Les champs récepteurs des neurones de V1, les colonnes d'orientation, les canaux ioniques, les synapses.

### 3. La distinction Poirier : Explanandum vs Explanans
* **Explanandum (La chose à expliquer) :** La capacité cognitive globale de l'organisme, décrite formellement comme une fonction mathématique calculable liant des entrées sensorielles à des comportements ($y = f(x)$).
* **Explanans (Ce qui explique) :** Le schéma fonctionnel causal décomposant cette capacité en sous-capacités algorithmiques ordonnées et leur implémentation physique matérielle.

### 4. L'anecdote de Marvin Minsky et le mythe du projet d'été (1966)
Pierre Poirier raconte l'anecdote emblématique de Marvin Minsky au MIT (Diapo 51) :
* À l'été 1966, Minsky recrute Gerald Sussman (étudiant de premier cycle) pour un stage d'été avec pour mandat de « relier une caméra à un ordinateur et de faire décrire par la machine les objets posés sur la table ».
* Minsky pensait que la vision n'était qu'un problème d'interface périphérique trivial qui serait réglé en trois mois par un stagiaire !
* Soixante ans plus tard, la vision computationnelle mobilise toujours des milliers de chercheurs mondiaux, prouvant l'immense complexité algorithmique des processus sensoriels par rapport au raisonnement logique abstrait.

---

## 🧠 SECTION 5 : LA SOLUTION CONNEXIONNISTE — MCCULLOCH, PITTS ET LE PERCEPTRON

### 1. Warren McCulloch & Walter Pitts (1943) : Le calcul logique de l'activité nerveuse
* Article séminal : *A Logical Calculus of the Ideas Immanent in Nervous Activity* (Diapo 63).
* Modélisent pour la première fois le neurone biologique comme une unité logique binaire tout-ou-rien :
  * Les impulsions nerveuses sont représentées par des variables propositionnelles valant 0 ou 1.
  * Des synapses excitatrices et inhibitrices convergent sur le corps cellulaire.
  * Si la somme excitatrice dépasse le seuil et qu'aucune inhibition n'est active, le neurone émet un potentiel d'action.
* **Preuve mathématique :** Tout réseau fini de neurones formels de McCulloch-Pitts est capable de calculer les fonctions logiques booléennes fondamentales (ET, OU, NON).

### 2. Frank Rosenblatt (1958) et le Perceptron
Frank Rosenblatt (Cornell Aeronautical Laboratory) crée la machine Mark I Perceptron (Diapos 65–68) :
* **Révolution conceptuelle :** Contrairement aux systèmes symboliques programmés à la main, le Perceptron **apprend par l'expérience** en ajustant ses poids synaptiques de façon adaptative !
* **Modélisation mathématique du Perceptron Monocouche (*Single Layer Perceptron*) :**
  $$\text{net} = \sum_{i=1}^{n} w_i x_i - \theta = \mathbf{w} \cdot \mathbf{x} + b$$
  $$y = \begin{cases} 1 & \text{si } \text{net} \ge 0 \\ 0 & \text{si } \text{net} < 0 \end{cases}$$
* **Séparabilité linéaire géométrique ($y = mx + b$) :**
  * Dans le plan bidimensionnel ($x_1, x_2$), l'équation $\text{net} = 0$ définit une droite affine :
    $$w_1 x_1 + w_2 x_2 + b = 0 \implies x_2 = -\frac{w_1}{w_2} x_1 - \frac{b}{w_2}$$
  * Cette droite (ou hyperplan en dimension $N$) partitionne l'espace d'entrée en deux demi-plans : les entrées activant la sortie (1) et celles la désactivant (0).
  * Le Perceptron apprend avec succès les fonctions booléennes ET (*AND*) et OU (*OR*).

---

## ⚡ SECTION 6 : LA CRISE DU XOR (MINSKY & PAPERT, 1969) & LA RENAISSANCE PDP (1986)

### 1. Le coup de grâce de Minsky & Papert (1969)
Dans leur monographie mathématique *Perceptrons* (1969, Diapo 68) :
* Marvin Minsky et Seymour Papert démontrent formellement les limites intrinsèques des perceptrons sans couches cachées.
* **Le problème du OU Exclusif (XOR) :**
  $$\begin{array}{|c|c|c|}
  \hline
  x_1 & x_2 & \text{XOR}(x_1, x_2) \\
  \hline
  0 & 0 & 0 \\
  1 & 0 & 1 \\
  0 & 1 & 1 \\
  1 & 1 & 0 \\
  \hline
  \end{array}$$
* **Impossibilité géométrique :** Les points $(0,1)$ et $(1,0)$ de classe 1 forment des sommets diagonalement opposés d'un carré unitaire, tandis que $(0,0)$ et $(1,1)$ de classe 0 occupent l'autre diagonale. **Il est mathématiquement impossible de tracer une seule ligne droite séparant les 1 des 0 !**
* **Conséquence historique :** Le livre gèle les subventions gouvernementales et provoque le premier grand « hiver de l'intelligence artificielle » (*AI Winter*) pour le paradigme neuromorphique pendant près de quinze ans.

### 2. La Renaissance : Réseaux Multicouches & Traitement Distribué Parallèle (1986)
David Rumelhart, James McClelland et le groupe PDP publient en 1986 *Parallel Distributed Processing* (Diapos 69–70) :
1. **L'adjonction de couches cachées (*Hidden Layers*) :**
   * Les unités cachées opèrent un changement de coordonnées non-linéaire qui projette les entrées dans un espace de dimension supérieure où les classes disjointes deviennent linéairement séparables !
2. **L'algorithme de Rétropropagation du Gradient (*Backpropagation*) :**
   * Formalisé par Rumelhart, Hinton et Williams (1986).
   * Calcule le gradient de l'erreur quadratique globale par rapport à chaque poids synaptique du réseau en appliquant la règle de dérivation en chaîne (*chain rule*) depuis la sortie vers l'entrée :
     $$\Delta w_{ij} = -\eta \frac{\partial E}{\partial w_{ij}}$$
   * Les poids descendent la surface d'erreur 3D (*gradient descent*) vers un minimum d'erreur.
3. **Le passage obligatoire aux fonctions d'activation continues et différentiables :**
   * La fonction seuil binaire de McCulloch-Pitts n'étant pas différentiable (dérivée nulle partout et discontinue en zéro), elle interdisait tout calcul de gradient.
   * L'utilisation de fonctions sigmoïdes logistiques $F(\text{net}) = \frac{1}{1 + e^{-\text{net}}}$ (puis plus tard Tanh et ReLU) a débloqué l'apprentissage automatique dans les réseaux profonds.

---

## 🔬 SECTION 7 : FORMALISATION MATHÉMATIQUE & ARCHITECTURES NEURONALES

### 1. Du neurone biologique au neurone artificiel
Pierre Poirier détaille la correspondance morpho-fonctionnelle (Diapos 72 à 76) :
* **Dendrites $\to$ Vecteur d'entrées ($a_i$ ou $x_i$) :** Réception des signaux des neurones en amont.
* **Synapses $\to$ Matrice des poids synaptiques ($w_{ji}$) :** Modulation de l'amplitude du signal. Poids positifs = synapses excitatrices (potentiels post-synaptiques excitateurs - PPSE) ; poids négatifs = synapses inhibitrices (PPS-I).
* **Corps cellulaire (Soma) $\to$ Fonction d'intégration nette ($\text{net}_j$) :**
  $$\text{net}_j = \sum_{i} a_i w_{ji} + \theta_j$$
* **Zone gâchette de l'axone $\to$ Fonction d'activation ($F$) :**
  $$y_j = F(\text{net}_j)$$

### 2. Niveaux de modélisation dans la boîte à outils connexionniste
* **Modèles à taux de décharge (*rate-coded networks*) :** L'activation continue représente la fréquence moyenne de décharge du neurone (potentiels d'action par seconde), sans modéliser chaque impulsion individuelle. C'est le standard de l'IA cognitive.
* **Modèles réalistes impulsionnels (*spiking neural networks*) :** Intègrent la milliseconde près du timing des potentiels d'action.
* **Architecture LEABRA (O'Reilly & Munakata, Diapo 83) :** *Local, Error-driven and Associative, Biologically Realistic Algorithm*. Combine dans un même modèle cortical la plasticité locale hebbienne et l'apprentissage guidé par l'erreur.

---

## ⚖️ SECTION 8 : LES DEUX FORMES D'APPRENTISSAGE SELON PIERRE POIRIER

> [!IMPORTANT]
> **Théorie maîtresse de Pierre Poirier (Diapos 84 à 98) :**  
> Les systèmes cognitifs et artificiels mobilisent deux formes fondamentales et complémentaires d'apprentissage qu'il ne faut en aucun cas confondre : l'apprentissage corrélationnel et l'apprentissage pragmatique.

### 1. L'Apprentissage Corrélationnel (Associatif / Non-supervisé / Hebbien)
* **Origine théorique :** La règle synaptique de Donald Hebb (1949, *The Organization of Behavior*) :
  > *« Neurons that fire together wire together. »*  
  > *(Des neurones qui déchargent ensemble se connectent ensemble).*
  $$\Delta w_{ij} = \eta \cdot a_i \cdot a_j$$
* **Mécanisme :** Renforcement de la force synaptique proportionnel à la co-activation simultanée des unités pré- et post-synaptiques.
* **Finalité :** L'apprentissage est **intrinsèque et non-supervisé**. Le système ne reçoit aucune consigne de tâche, aucun retour d'erreur ni professeur externe. Il extrait passivement les régularités statistiques, les co-occurrences et la structure latente de l'environnement (ex: auto-encodeurs, cartes de Kohonen, réseaux de Hopfield).

### 2. L'Apprentissage Pragmatique (Supervisé / Guidé par l'erreur et la tâche)
* **Origine théorique :** Le pragmatisme épistémologique et la rétropropagation de l'erreur (Rumelhart et al., 1986).
* **Mécanisme :** L'apprentissage est entièrement subordonné à l'atteinte d'un **but moteur ou d'une tâche extérieure spécifique**.
* **Le calcul d'erreur :** L'environnement ou l'expérimentateur fournit pour chaque entrée une cible attendue ($t_k$). Le réseau calcule l'écart quadratique :
  $$E = \frac{1}{2} \sum_{k} (t_k - y_k)^2$$
* Les poids synaptiques sont modifiés de manière téléologique pour annuler l'erreur de tâche.
* **Distinction philosophique :** Le corrélationnel modélise *« ce qui est souvent ensemble dans le monde »* ; le pragmatique modélise *« ce qu'il faut faire avec succès face à la contrainte de la tâche »*.

---

## 🗣️ SECTION 9 : PARADIGME PRINCEPS — NETTALK (SEJNOWSKI & ROSENBERG, 1987)

### 1. La Tâche et l'Architecture de NETtalk
Terry Sejnowski et Charles Rosenberg (1987, Diapos 96 à 98) conçoivent l'un des plus grands chefs-d'œuvre de la modélisation cognitive connexionniste :
* **Tâche cognitive :** Apprendre à lire à haute voix un texte écrit en anglais (conversion graphème ➔ phonème).
* **Architecture réseau :**
  1. *Couche d'entrée (Input) :* Une fenêtre glissante de 7 lettres textuelles. Le réseau doit prononcer la lettre centrale (la 4e), tout en utilisant les 3 lettres précédentes et les 3 suivantes comme contexte graphémique. Chaque lettre est encodée sur 26 unités binaires (29 avec espaces et ponctuations), soit $7 \times 29 = 203$ neurones d'entrée.
  2. *Couche cachée (Hidden Layer) :* 120 unités entièrement interconnectées aux entrées et aux sorties.
  3. *Couche de sortie (Output) :* 26 unités d'articulation phonétique (traits articulatoires : voisé, bilabial, nasal, occlusif...) dont les activations continues pilotent directement un synthétiseur vocal électronique (DECtalk).

### 2. La dynamique d'apprentissage de NETtalk
* **Entraînement :** Corpus d'un texte d'enfant de 1 024 mots lu en boucle. Les poids sont initialisés avec des valeurs aléatoires.
* **Chronologie développementale :**
  1. *Phase initiale :* Babillage informe et bruits stochastiques d'un nouveau-né.
  2. *Deuxième phase :* Distinction globale entre consonnes et voyelles ; émission d'un rythme pseudo-linguistique.
  3. *Phase terminale :* Prononciation fluide et intelligible avec gestion correcte des règles phonologiques et des irrégularités morphologiques de l'anglais.

### 3. La découverte des représentations internes (Diapo 98)
* Pourquoi NETtalk a-t-il marqué l'histoire des sciences cognitives ?
* Sejnowski a appliqué une analyse mathématique de regroupement hiérarchique (*hierarchical cluster analysis* / dendrogramme) sur les vecteurs d'activation de la couche cachée de 120 neurones.
* **Résultat spectaculaire :** Sans qu'aucune règle de grammaire ou de phonétique n'ait été programmée dans le système, le réseau a forgé dans ses couches cachées un espace géométrique interne qui regroupe spontanément les voyelles d'un côté et les consonnes de l'autre, et sous-divise les consonnes selon leur point et mode d'articulation (occlusives vs fricatives) !
* **Preuve expérimentale :** Un réseau connexionniste pragmatique guidé par l'erreur découvre de façon autonome des catégories linguistiques abstraites.

---

## 🔮 SECTION 10 : LE TEST DE TURING INVERSÉ & LES LLM (SEJNOWSKI, 2023)

Dans son article *Large Language Models and the Reverse Turing Test* (2023, Sections 6 & 7) discuté en classe par Pierre Poirier :
1. **Filiation directe :** Les modèles de fondation contemporains (GPT-4, Claude, Gemini) ne sont pas des architectures symboliques GOFAI : ce sont les descendants directs et directs du connexionnisme des années 1980 (NETtalk), poussés à l'échelle de milliards de paramètres grâce aux réseaux Transformeurs (*Transformers*) et à l'attention multi-têtes.
2. **Le Test de Turing Inversé (*Reverse Turing Test*) :**
   * Traditionnellement, le test de Turing évalue si la machine est humaine.
   * Sejnowski démontre que face aux LLM, c'est la machine qui teste et reflète l'humain ! Un LLM agit comme un miroir psychologique :
     * Si l'utilisateur pose une question rigoureuse et structurée, le LLM répond avec pertinence et profondeur.
     * Si l'utilisateur est prompté avec des affirmations absurdes, biaisées ou complotistes, le modèle s'adapte en miroir et génère des hallucinations délirantes.
3. **Implication épistémologique :** L'intelligence apparente d'un système génératif moderne résulte de la rencontre interactive entre l'invite de l'opérateur humain et la distribution de probabilités du réseau.

---

## 🎯 TABLEAU SYNOPTIQUE DE RÉVISION — SÉANCE 2 (PSY9613)

| Thématique / Auteur | Dates clés | Concepts fondamentaux | Rôle dans l'explication cognitive | Piège classique d'examen |
| :--- | :---: | :--- | :--- | :--- |
| **René Descartes** | 1634 / 1637 | *Traité de l'homme*, esprits animaux, automates hydrauliques. | Mécanisation des fonctions corporelles et réflexes. | Confondre l'argument du langage avec une incapacité à faire des bruits physiques. |
| **Les 2 Critères Cartésiens** | 1637 | 1) Langage déclaratif dynamique<br>2) Raison universelle vs organes particuliers. | Démarcation infranchissable entre homme et machine. | Croire que Descartes pensait que les machines ne pouvaient pas bouger ou réagir. |
| **Le Paradoxe Moderne** | XXe siècle | Mécanisme physique fini ↕ Infinité de représentations. | Problématique fondatrice des sciences cognitives. | Penser que la récursivité nécessite une infinité de matière physique. |
| **Noam Chomsky** | 1966 | *Linguistique cartésienne*, systèmes de processus récursifs. | Résolution formelle du paradoxe cartésien par la récursivité. | Attribuer à Chomsky le refus des représentations mentales symboliques. |
| **Alan Turing** | 1936 / 1950 | Machine de Turing universelle, *Imitation Game* (Mind 1950). | Formalisation du calcul mécanique et test opérationnel d'esprit. | Confondre l'automate à états finis (FSA) avec la machine de Turing universelle. |
| **John Haugeland** | 1981 | Système formel, Indépendance du médium, Moteur Sémantique. | Préservation de la sémantique par pure manipulation syntaxique. | Oublier que la vérité est une propriété sémantique et non purement syntaxique. |
| **Newell & Simon** | 1975 | Physical Symbol System Hypothesis (PSSH). | Thèse fondatrice GOFAI (condition nécessaire et suffisante). | Penser que la PSSH s'applique exclusivement aux ordinateurs électroniques. |
| **David Marr** | 1982 | 3 niveaux : Computationnel (1), Algorithmique (2), Implémentationnel (3). | Cadre tri-étagé d'analyse des systèmes de traitement d'information. | Inverser le niveau computationnel (le quoi/pourquoi) avec le niveau algorithmique (le comment). |
| **Pierre Poirier** | 2026 | Explanandum (capacité) vs Explanans (schéma causal + mécanisme). | Démarcation épistémologique de l'explication cognitive. | Confondre la fonction mathématique d'entrée-sortie avec le mécanisme causal interne. |
| **McCulloch & Pitts** | 1943 | Neurone formel binaire tout-ou-rien (*Logical Calculus*). | Première preuve que des neurones interconnectés calculent la logique. | Croire que leur modèle incluait un algorithme d'apprentissage automatique des poids. |
| **Frank Rosenblatt** | 1958 | Perceptron monocouche (*Mark I*), droite affine $y = mx + b$. | Première machine apprenante bio-inspirée avec poids synaptiques plastiques. | Oublier que le Perceptron monocouche est strictement borné à la séparabilité linéaire. |
| **Minsky & Papert** | 1969 | Livre *Perceptrons*, réfutation formelle du XOR. | Déclenchement du Premier Hiver de l'IA (coupure des budgets connexionnistes). | Penser que Minsky a réfuté les réseaux multicouches (il a réfuté le monocouche). |
| **Rumelhart & McClelland** | 1986 | Réseaux multicouches (PDP), Rétropropagation du gradient. | Résolution du XOR par projection non-linéaire en couche cachée. | Croire que la backprop fonctionne avec des fonctions d'activation discontinues à seuil. |
| **Apprentissage Corrélationnel** | 1949 (Hebb) | Hebbien, co-activation synaptique, non-supervisé, passif. | Capture de la structure statistique et des co-occurrences environnementales. | Confondre la règle hebbienne avec une minimisation d'erreur de tâche. |
| **Apprentissage Pragmatique** | 1986 | Guidé par l'erreur de tâche ($E = \frac{1}{2}(t-y)^2$), supervisé, téléologique. | Optimisation d'un comportement moteur orienté vers un but spécifique. | Croire que l'apprentissage pragmatique n'a pas besoin de rétroaction externe d'erreur. |
| **NETtalk (Sejnowski)** | 1987 | Lecture de texte en phonèmes, 120 unités cachées, DECtalk. | Découverte autonome de structures abstraites (voyelles vs consonnes). | Croire que Sejnowski a encodé les règles de phonétique à la main dans le réseau. |
| **Terry Sejnowski** | 2023 | *Reverse Turing Test*, LLM comme miroirs psychologiques. | Analyse critique de la cognition des transformeurs contemporains. | Penser que les LLM actuels sont des machines symboliques cartésiennes. |
