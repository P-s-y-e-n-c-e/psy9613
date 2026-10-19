# 📌 Suivi et Synthèse du Forum Q&R (Octobre 2026)

Ce document consigne les clarifications théoriques et organisationnelles publiées sur le Forum Q&R de Moodle par les professeurs et étudiants à la suite de la Séance 3.

---

## 1. Organisation des Débats & Rôle du Modérateur (Dave Saint-Amour — 29 sept. 2026)

* **Contexte :** Alexandrea Kelly a soulevé la question du partage préalable des questions de débat avec le modérateur pour faciliter son animation (référence à la présidence de Michel lors du Débat 1).
* **Directives officielles de Dave Saint-Amour :**
  1. **Envoi de la question :** La formulation exacte de la question de débat continuera d'être transmise aux débatteurs et au modérateur. Elle pourra également être élargie à l'ensemble du groupe.
  2. **Attentes envers le modérateur :** Le modérateur n'est **pas obligé de préparer ou poser des questions formelles et pointues** aux présentateurs. Son mandat prioritaire consiste à :
     - Gérer équitablement les tours de parole et les interventions de la classe.
     - Formuler des synthèses brèves des points de convergence et de divergence lorsque approprié.
     - Relancer la plénière si nécessaire, tout en encourageant les questions spontanées de l'auditoire.
  3. **Appel à volontaire :** Les professeurs recherchent toujours un.e étudiant.e volontaire pour présider/modérer le débat de la **Séance 6 (19 octobre 2026)** sur le thème du *Cerveau prédictif*.

---

## 2. Clarifications Théoriques & Liens Complémentaires

### A. Modèle de Shannon et rétroaction (Feedback Loop)
* **Échange :** Alexandrea Kelly & Dave Saint-Amour (2 octobre 2026).
* **Constat :** Dans sa formulation canonique d'origine (Shannon & Weaver 1948, 1956), le modèle de la théorie de l'information est un système sans mémoire et sans boucle de rétroaction (*feedback*), initialement conçu pour la transmission de signaux dans des machines. L'intégration de la boucle de rétroaction dans la communication humaine et la cybernétique s'est formalisée ultérieurement (années 1960).

### B. Ressources partagées sur les modèles prédictifs et connexionnistes
* **Circuit thalamo-cortical et historique sensoriel :**
  - Référence signalée : *A thalamocortical circuit encoding deviations from sensory history* (*Science*, DOI : `10.1126/science.aeg4720`), accessible via Sofia / Bibliothèques UQAM (en complément aux modèles d'apprentissage de McClelland).
* **Créativité et raisonnement des modèles d'IA :**
  - Vidéo YouTube d'Adam Brown (Perimeter Institute) : *« Training sand to think »* (exploration des LLM et des systèmes multi-agents appliqués à la résolution de conjectures mathématiques).

---

## 3. Intervention de Michel Mercier — Séance 6 : Le cerveau prédictif (19 oct. 2026)

* **Lien direct Moodle :** [`https://ena01.uqam.ca/mod/forum/discuss.php?d=503377`](https://ena01.uqam.ca/mod/forum/discuss.php?d=503377)
* **Sujet :** `Réflexions sur le cerveau prédictif : somme d'activité neuronale, récursion du bruit et limites du concept d'attention`
* **Statut :** Publié le lundi 19 octobre 2026 (vérifié dans le DOM Moodle : 11 paragraphes `<p>` distincts).
* **Texte intégral publié :**

> Bonjour à tous, voici quelques pistes de réflexion en amont du cours d'aujourd'hui sur le cerveau prédictif :
>
> **1. Somme d'activité neuronale et paradoxe de l'atténuation (de Lange et al., 2018)**
>
> Lorsque l'on mesure l'activité cérébrale globale (en IRMf ou MEG), on observe principalement une somme d'activité. Si un stimulus attendu génère moins d'activité globale, cela ne signifie pas nécessairement que la représentation est affaiblie : une hypothèse alternative est que l'attente permet justement d'inhiber ou de réduire le bruit neuronal environnant pour ne laisser actif que le sous-réseau strictement pertinent (affinement ou *sharpening*).
>
> Dans cette perspective, la baisse du signal macroscopique refléterait l'économie métabolique d'un tri réussi plutôt qu'une baisse de fidélité perceptive. À l'inverse, face à un stimulus inattendu, le système doit recruter davantage de ressources pour résoudre l'incertitude et mettre à jour son modèle, ce qui fait grimper la somme d'activité mesurée.
>
> **2. Boucle de rétroaction et amplification du bruit (cerveau vs IA générative)**
>
> Si la perception repose sur une intégration continue entre les prédictions descendantes (*top-down*) et le signal sensoriel ascendant (*bottom-up*), il existe un risque structurel : celui qu'un bruit initial soit réinjecté dans la boucle et amplifié de manière récursive jusqu'à produire une hallucination ou une dérive.
>
> On observe d'ailleurs un phénomène analogue dans les grands modèles de langage (LLM) lors de l'auto-bavardage ou de l'entraînement récursif sur données synthétiques (*model collapse*) : lorsque le système s'alimente de ses propres prédictions sans ancrage externe fort, les erreurs s'accumulent et le signal se dégrade. Chez l'humain, ce sont l'action motrice et la friction physique avec l'environnement réel qui semblent jouer le rôle de garde-fou pour briser cette récursion et recalibrer le modèle interne.
>
> **3. Déconstruire le mot « attention » au profit de mécanismes de circuit**
>
> Dans le langage courant, on traite souvent l'attention comme une faculté unifiée ou une forme de volonté consciente (*willpower*), ce qui peut s'avérer culpabilisant lorsque cette régulation fait défaut (comme dans le TDAH). Or, à l'échelle computationnelle et neurobiologique, ce que l'on regroupe sous le terme d'« attention » correspond plutôt à un ensemble de mécanismes d'optimisation et de pondération du gain (filtrage du rapport signal/bruit, allocation métabolique, neuromodulation).
>
> De la même manière qu'en apprentissage profond (*deep learning*) le mécanisme d'attention désigne un calcul matriciel de pondération contextuelle sans faire appel à un homoncule, gagnerait-on en précision théorique et clinique à décomposer ce terme générique en processus de régulation distincts ?
>
> Au plaisir d'en discuter tout à l'heure en classe !

