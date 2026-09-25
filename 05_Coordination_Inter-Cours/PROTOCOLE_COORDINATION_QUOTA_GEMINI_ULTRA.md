# Protocole de Coordination Inter-Quartiers Généraux : Gestion du Quota Gemini Ultra (94%)

> **Date & Heure :** Nuit du 24 au 25 septembre 2026 — 03h55 EDT  
> **Mandat :** Michel Mercier  
> **Parties Prenantes :**
> - **Quartier Général PSY9613** (`7dc85196-1fd5-481e-8cd9-2a0e92d258e2`)
> - **Quartier Général PSY7010** (`d6fea03c-228d-438c-bb4e-541e2d0eaeac`)
> - **Session Contenu Web PSY9613** (`76989406-e739-4d56-85aa-9280b2a78eb4`)
> - **Session Contenu PSY7010** (`27764a31-5ff2-4a20-acc0-12446d624b09`)

---

## 1. Contexte & Métriques Critiques

- **Compte Partagé :** Google One AI Ultra (Michel Mercier) sur Chrome Port 9223.
- **Stations Utilisatrices :**
  1. `PSY9613 - Audit Station 1` (Dave Saint-Amour)
  2. `PSY9613 - Audit Station 2` (Pierre Poirier)
  3. `PSY7010 - Audit Station` (Human Factors / AF447)
- **Niveau de Consommation Actuel :** **94 % utilisé**.
- **Heure Officielle de Réinitialisation (Reset) :** **04h48 EDT** (dans ~50 minutes).
- **Distinction des Pools de Calcul :** Ce quota s'applique exclusivement à l'interface web Gemini (navigateur de débogage port 9223) et n'a aucun lien avec les crédits de tokens de l'environnement Antigravity (deux pools hermétiquement distincts).

---

## 2. Consignes Opérationnelles pour les Sessions Pédagogiques

1. **Poursuite Nominale jusqu'à Butée :**
   - Les sessions continuent leurs inférences dialectiques normalement tant que les serveurs Google répondent en mode `Pro Deep Think`.
2. **Conduite Immédiate en Cas de Blocage (Quota 100% / Rate Limit) :**
   - **Interdiction formelle de relancer en boucle :** Aucun spam de requêtes ni clics frénétiques sur *Réessayer* qui gaspilleraient des tokens réseau ou causeraient des timeouts serveur.
   - **Mise en Standby Calme :** Si Gemini affiche un message de limite atteinte, la session entre immédiatement en mode veille temporaire.
   - **Reprise Synchronisée à 04h48 EDT :** Dès que le compteur repasse à zéro à 04h48 EDT, les requêtes DeepThink reprennent immédiatement là où elles s'étaient arrêtées.

---

## 3. Protocole d'Alerte Réciproque Inter-HQ

- **Canal de transmission :** Passerelle `agentapi.bat send-message` entre Quartiers Généraux.
- **Notification de blocage :**
  * Si la station PSY7010 heurte la limite en premier, son agent Contenu alerte HQ PSY7010, qui transmet l'alerte à HQ PSY9613.
  * Si l'une des stations PSY9613 heurte la limite en premier, Contenu web PSY9613 alerte HQ PSY9613, qui transmet l'alerte à HQ PSY7010.
- **Visibilité totale :** Aucun quartier général ni agent de contenu ne sera surpris ou ne cherchera à diagnostiquer un prétendu bug réseau : la mise en pause sera comprise de part et d'autre comme l'attente programmée du reset de 04h48 EDT.
