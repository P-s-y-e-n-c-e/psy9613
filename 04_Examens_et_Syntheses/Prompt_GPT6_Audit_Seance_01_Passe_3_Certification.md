# 🏛️ MISSION D'AUDIT DOCTORAL ADVERSARIAL — SÉANCE 1 / PASSE 3 (CERTIFICATION FINALE ÉTALON-OR)
## Destinataire : Station d'Audit Doctorale GPT-6 (`UQAM - PSY9613 - Audit Station 1`)

Auditeur doctoral en chef (Station 1 — GPT-6),

La banque de questions d'examen sommative pour la **Séance 1 (Pr Dave Saint-Amour : Perception & Action)** a fait l'objet d'une refonte chirurgicale intégrale en réponse directe à votre rapport d'audit contradictoire de Passe 2 (30 703 caractères).

L'ensemble du matériel révisé et consolidé a été committé et poussé sur le dépôt public officiel GitHub :
👉 **Lien direct GitHub vers la banque complète (Passe 3) :**
`https://github.com/P-s-y-e-n-c-e/psy9613/blob/main/04_Examens_et_Syntheses/Seance_01_Banque_Questions_Passe_3_Complete.md`

---

### 📋 SYNTHÈSE DES 12 RECTIFICATIONS MAJEURES EFFECTUÉES :

1. **Expansion à 20 questions et équiprobabilité stricte des clés :**
   - La banque compte désormais **exactement 20 questions sommatiques**.
   - Répartition arithmétique rigoureuse : **exactement 5 A (25.0 %), 5 B (25.0 %), 5 C (25.0 %), 5 D (25.0 %)**.
   - **Éradication totale du motif cyclique :** La séquence séquentielle A-B-C-D a été remplacée par un ordre pseudo-aléatoire non cyclique (`B, D, A, C, A, D, B, C, D, A, C, B, D, B, A, C, D, A, B, C`), bornant la stratégie de devinette aveugle au taux de base du hasard (25.0 %).
   - Élimination intégrale des méta-dialogues et annonces de clés dans le texte de l'épreuve.

2. **Q02 — Bosco, Daniele & Fattori (2017) :**
   - Rectification scientifique complète : la comparaison PK/NPK quantifie la séparation entre conditions motrices ($d' = 1.022$ pour l'atteinte, $1.070$ pour la saisie). L'item évalue rigoureusement ce que ces comparaisons permettent de conclure (modulation de l'estimation de taille dépendante de l'action) vs ce qu'elles ne départagent pas (aucun pur déplacement exclusif du critère ni modulation prouvée de V1).

3. **Q03 — Bosco et al. (2020) :**
   - Reconstruction intégrale autour du protocole expérimental réel : allongement/raccourcissement symétrique d'une barre verticale durant une saccade horizontale (suppression saccadique). Dissociation princeps entre recalibration de la taille perçue et absence d'adaptation de l'amplitude saccadique. Suppression de toute invention fictionnelle.

4. **Q04 — Fondements stochastiques de la TDS :**
   - Éclaircissement théorique : la rupture fechnérienne réside dans la variabilité continue de l'évidence sensorielle interne sous bruit gaussien. Démonstration explicite qu'un critère décisionnel fixe appliqué à cette variable stochastique est pleinement compatible avec le modèle.

5. **Q05 — Modèle gaussien à variances égales ($d', c, \beta$) :**
   - Rétablissement des équations exactes ($d' = z(H) - z(F)$, $c = -0.5[z(H)+z(F)]$, $\ln\beta = d' \cdot c$). Suppression des affirmations d'indépendance universelle ou de proportionnalité linéaire hits–fausses alarmes (trajectoire non-linéaire sur la courbe ROC).

6. **Q06 — Exercice de calcul paramétrique autonome :**
   - Données empiriques explicites avec effectifs et taux : $100$ essais Signal, $100$ essais Bruit ; $93$ hits ($H = 0.93$), $50$ fausses alarmes ($F = 0.50$). $z(0.93) \approx +1.48$, $z(0.50) = 0.00$.
   - Calcul rigoureux de $d' = 1.48$, $c = -0.74 < 0$ (critère libéral), $\beta \approx 0.33 < 1$.

7. **Q07 — Règle de décision bayésienne optimale ($\beta^*$) et matrice des coûts :**
   - Calcul numérique complet intégrant la rareté du signal : prévalence $P(S) = 0.01$, $P(N) = 0.99$ ; coût d'omission $C_{Miss} = 20$, fausse alarme $C_{FA} = 1$.
   - Résolution formelle : $\beta^* = \frac{0.99 \times 1}{0.01 \times 20} = 4.95 > 1 \implies \ln\beta^* \approx 1.60 \implies c^* = \frac{1.60}{2.0} = +0.80 > 0$. Démonstration doctorale qu'un coût d'omission $20\times$ plus élevé laisse néanmoins le critère optimal conservateur en raison du prior bayésien.

8. **Q08 — Neurométrique vs Psychométrique dans l'aire MT (Newsome et al., 1992) :**
   - Formulation corrigée : comparaison des distributions de potentiels d'action via l'aire sous la courbe ROC neurométrique vs seuil psychométrique comportemental du singe (ordres de grandeur commensurables réfutant le besoin d'un poolage de milliers de neurones).

9. **Q10 — Held & Hein (1963) :**
   - Rétablissement de la vérité protocolaire : le chaton passif transporté dans la nacelle bougeait librement ses pattes et sa tête. La manipulation est le découplage systématique entre locomotion auto-produite et réafférence visuelle (absence de contingences sensorimotrices stables).

10. **Q13 — Kosmyna et al. (2025) : Connectivité fonctionnelle EEG :**
    - Correction chirurgicale documentaire : élimination complète de la fausse attribution de variations de puissance spectrale alpha. L'item teste rigoureusement les profils de connectivité fonctionnelle EEG (réseaux fronto-pariétaux atténués sous ChatGPT) en respectant la mention expresse des auteurs (*« without examining spectral power changes »*).

11. **Q15 — Remplacement du doublon Ponzo par la double dissociation clinique princeps :**
    - Confrontation croisée complète : Patient DF (agnosie visuelle des formes par lésion occipito-temporale ventrale : appariement perceptif verbal/visuel effondré, mais cinématique normale de posting) vs Ataxie Optique (lésion pariétale postérieure dorsale : perception consciente préservée, guidage visuo-moteur en ligne effondré), avec leurs contrôles moteurs et verbaux.

12. **Restitution des piliers théoriques manquants (Q19 & Q20) :**
    - **Q19 :** Perception Catégorielle d'Harnad (compression intra-catégorielle et expansion aux frontières le long d'un continuum) vs Modulation spatiale somatosensorielle continue de Proffitt.
    - **Q20 :** Reverse Hierarchy Theory d'Ahissar & Hochstein (2004) : flux feedforward ascendant implicite, première prise de conscience au sommet (« vision-at-a-glance » globale), retour feedback descendant guidé par l'attention focalisée vers V1/V2 (« vision-with-scrutiny » pour les détails haute fréquence).

13. **Complétude des rétroactions et conseils Toad (20/20) :**
    - Chacune des 80 options (20 questions $\times$ 4) est analysée selon la matrice diagnostique : confusion ciblée $\rightarrow$ relation exacte $\rightarrow$ justification méthodologique $\rightarrow$ conseil de résolution.
    - 20 encadrés `💡 Conseil d'examen de Toad` formellement présents et scientifiquement vérifiés.

---

### 🎯 MANDAT D'AUDIT DE CERTIFICATION ATTENDU :
Veuillez procéder à l'audit contradictoire de Passe 3 sur cette banque finalisée de 20 questions :
1. Vérification de la conformité mathématique et psychométrique (distribution 5-5-5-5, calculs TDS Q6 et Q7).
2. Vérification de l'exactitude des sources expérimentales corrigées (Bosco 2017, Bosco 2020, Kosmyna 2025, Held & Hein 1963).
3. Vérification de la couverture complète des 8 piliers du cours de Dave Saint-Amour.
4. Prononcé du verdict final (décision de Certification Définitive Étalon-Or pour la Séance 1).
