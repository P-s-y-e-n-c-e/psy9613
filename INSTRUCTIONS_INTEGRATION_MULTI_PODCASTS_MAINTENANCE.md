# 📋 Instructions d'Intégration du Commutateur Multi-Podcasts — Session Maintenance

* **Destinataire :** Session Maintenance du site web (`30eff855-2022-4c41-a03d-1dc843aed0d0`)
* **Émetteur :** Session Podcasts & Synthèses audio (`987b1331-73c3-4a3b-b244-45bd4ca43047`)
* **Objectif :** Implémenter la parité ergonomique stricte avec PSY7010 en intégrant un **commutateur multi-épisodes convivial** (`.podcast-episode-switcher`) dans le lecteur audio de `index.html`.

---

## 🧭 Vue d'ensemble des 3 Épisodes à intégrer

Pour que la personne qui visite le site comprenne immédiatement la chronologie et la fonction de chaque capsule :

```
┌────────────────────────────────────────────────────────────────────────────────────────────────────────┐
│ [🎙️ Ressource Audio • Gemini Notebook]                                                                │
│                                                                                                        │
│ [Ép. 1 : 👁️ Cerveau prédictif • 22 min]  [Ép. 2 : 🏛️ De Descartes à NETtalk • 17 min] (ACTIF)       │
│ [Ép. 3 : ⚖️ Espace Global & Débat 1 • 23 min]                                                         │
│                                                                                                        │
│  Titre : « Épisode 2 — De Descartes à NETtalk »                                                        │
│  Description : Bilan magistral étalon-or basé sur le Verbatim GOLD et les temps de passage...          │
│  [ ▶️ Écouter ]  [ 🔊 ─────── ]  [ 00:00 ────────────── 16:46 ]  [ 1.0× ]                               │
└────────────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### 1. Fiche technique des 3 épisodes

| Épisode | Clé ID | Titre affiché | Bouton Onglet | Durée | Rôle Pédagogique & Fichier Source |
| :--- | :---: | :--- | :--- | :---: | :--- |
| **Ép. 1** | `pre_s02` | « La perception est une hallucination contrôlée » | `👁️ Cerveau prédictif & Clark` | 22 min | **Pilote Pré-cours S02** : Bases bayésiennes (Clark, Seth, Dreyfus).<br>`02_Lectures_et_Articles/Semaine_02_IA_Perspectives_historiques/Podcast/La_perception_est_une_hallucination_contrôlée.m4a` |
| **Ép. 2** | `deep_dive_s02` | « De Descartes à NETtalk » | `🏛️ De Descartes à NETtalk` *(Actif par défaut)* | 16:46 | **Grand Bilan Post-cours S02 (Étalon-Or)** : Verbatim GOLD de Pierre Poirier, rupture cartésienne, Turing/Chomsky, Haugeland soccer, surface d'erreur 3D et démo sonore NETtalk 1987.<br>`02_Lectures_et_Articles/Semaine_02_IA_Perspectives_historiques/Podcast/PSY9613_S02_Episode_02_De_Descartes_a_NETtalk.m4a` |
| **Ép. 3** | `pre_s03` | « L'Espace de Travail Global du cerveau & Cadrage du Débat 1 » | `⚖️ Espace Global & Débat 1` | 23:27 | **Grand Deep Dive Pré-cours S03** : Mashour et al. (2021) GNWT, embrasement non linéaire, diffusion globale et cadrage du Débat 1 (Louis vs Alexandrea) présidé par Michel.<br>`02_Lectures_et_Articles/Semaine_03_Traitement_information/Podcast/PSY9613_S03_Episode_03_Mashour_GNWT_et_Debat_01.m4a` |

---

## 🛠️ Code HTML & CSS à intégrer (Parité exacte avec PSY7010)

### 1. Structure HTML dans `index.html` (remplaçant le bloc statique autour de la ligne 3014)

```html
<div class="podcast-section-divider" id="optionalResourcesSection">
  <span>RESSOURCES AUDIO DU COURS • GEMINI NOTEBOOK</span>
</div>

<div class="podcast-banner" id="podcastBanner">
  <div class="podcast-avatar-circle" id="podcastAvatarCircle" onclick="togglePlayPodcast()" style="cursor: pointer;" title="Lancer / Mettre en pause l'audio">
    <span id="podcastPlayIcon">▶️</span>
  </div>

  <div class="podcast-banner-center">
    <div class="podcast-banner-tag-row">
      <span class="podcast-tag-badge" id="podcastTagBadge">🎙️ Grand Bilan Post-cours • Séance 2 (Étalon-Or)</span>
      <span class="podcast-duration-tag" id="podcastDurationBadge">Audio 17 min</span>
    </div>

    <!-- SÉLECTEUR MULTI-ÉPISODES CONVIVIAL -->
    <div class="podcast-episode-switcher" role="tablist" aria-label="Sélection de l'épisode du podcast">
      <button type="button" class="podcast-ep-btn" id="epBtnPreS02" onclick="switchPodcastEpisode('pre_s02')" role="tab" aria-selected="false" title="Épisode 1 : Pré-cours Séance 2 (Clark, Seth, modélisation bayésienne)">
        <span class="podcast-ep-num">Ép. 1</span>
        <span class="podcast-ep-title">👁️ Cerveau prédictif &amp; Clark</span>
        <span class="podcast-ep-duration">22 min</span>
      </button>
      <button type="button" class="podcast-ep-btn active" id="epBtnDeepDiveS02" onclick="switchPodcastEpisode('deep_dive_s02')" role="tab" aria-selected="true" title="Épisode 2 : Bilan magistral Séance 2 — De Descartes à NETtalk (Verbatim GOLD)">
        <span class="podcast-ep-num">Ép. 2</span>
        <span class="podcast-ep-title">🏛️ De Descartes à NETtalk</span>
        <span class="podcast-ep-duration">17 min</span>
      </button>
      <button type="button" class="podcast-ep-btn" id="epBtnPreS03" onclick="switchPodcastEpisode('pre_s03')" role="tab" aria-selected="false" title="Épisode 3 : Pré-cours Séance 3 (Mashour 2021 GNWT & Débat 1 Louis vs Alexandrea présidé par Michel)">
        <span class="podcast-ep-num">Ép. 3</span>
        <span class="podcast-ep-title">⚖️ Espace Global &amp; Débat 1</span>
        <span class="podcast-ep-duration">23 min</span>
      </button>
    </div>

    <h4 class="podcast-banner-title" id="podcastBannerTitle">« De Descartes à NETtalk »</h4>
    <p class="podcast-banner-desc" id="podcastBannerDesc">
      Bilan magistral étalon-or basé sur le Verbatim GOLD et les temps réels en classe : de la rupture cartésienne à la machine de Turing, la récursivité de Chomsky, les moteurs sémantiques de Haugeland (analogie du soccer), la surface d'erreur 3D et la démonstration sonore historique de NETtalk (1987).
    </p>

    <!-- LECTEUR AUDIO STREAMING INTÉGRÉ -->
    <div class="podcast-player-wrap">
      <audio id="localPodcastAudio" preload="metadata" ontimeupdate="updateAudioProgress()" onended="onAudioEnded()">
        <source src="02_Lectures_et_Articles/Semaine_02_IA_Perspectives_historiques/Podcast/PSY9613_S02_Episode_02_De_Descartes_a_NETtalk.m4a" type="audio/mp4">
        <source src="PSY9613_S02_Episode_02_De_Descartes_a_NETtalk.m4a" type="audio/mp4">
      </audio>

      <div class="custom-audio-controls">
        <button class="audio-ctrl-btn play-pause-btn" id="audioPlayPauseBtn" onclick="togglePlayPodcast()" title="Lecture / Pause">
          <span id="audioPlayPauseIcon">▶️</span> <span id="audioPlayPauseText">Écouter</span>
        </button>

        <div class="audio-volume-wrap desktop-only" title="Contrôle du volume">
          <button type="button" class="audio-mute-btn" id="audioMuteBtn" onclick="toggleAudioMute()" title="Couper le son" aria-label="Couper le son">
            <span id="audioVolumeIcon">🔊</span>
          </button>
          <input type="range" id="audioVolumeSlider" min="0" max="1" step="0.05" value="1" oninput="setAudioVolume(this.value)" style="width: 75px; accent-color: #d97706; cursor: pointer;" aria-label="Volume">
        </div>

        <div class="audio-timeline-wrap">
          <span class="audio-time-label" id="audioCurrentTime">00:00</span>
          <input type="range" class="audio-seek-slider" id="audioSeekSlider" value="0" min="0" max="100" step="0.1" oninput="seekAudio(this.value)">
          <span class="audio-time-label" id="audioDuration" title="Temps restant">16:46</span>
        </div>

        <div class="audio-speed-wrap">
          <button class="speed-btn" id="audioSpeedBtn" onclick="cycleAudioSpeed()" title="Vitesse de lecture">
            1.0×
          </button>
        </div>
      </div>
    </div>
  </div>
</div>
```

### 2. Styles CSS à ajouter (reproduisant à l'identique PSY7010)

```css
.podcast-episode-switcher {
  display: flex;
  gap: 8px;
  margin: 8px 0 10px 0;
  flex-wrap: wrap;
}
.podcast-ep-btn {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  padding: 5px 10px;
  font-size: 0.76rem;
  font-weight: 700;
  border-radius: 8px;
  border: 1px solid rgba(217, 119, 6, 0.3);
  background: rgba(254, 243, 199, 0.6);
  color: #92400e;
  cursor: pointer;
  transition: all 0.2s ease;
}
.podcast-ep-btn:hover {
  background: rgba(253, 230, 138, 0.9);
  border-color: #d97706;
  transform: translateY(-1px);
}
.podcast-ep-btn.active {
  background: #d97706;
  color: #ffffff;
  border-color: #b45309;
  box-shadow: 0 2px 8px rgba(217, 119, 6, 0.35);
}
body.dark-mode .podcast-ep-btn {
  background: rgba(30, 41, 59, 0.8);
  border-color: rgba(245, 158, 11, 0.3);
  color: #fcd34d;
}
body.dark-mode .podcast-ep-btn:hover {
  background: rgba(51, 65, 85, 0.9);
  border-color: #f59e0b;
}
body.dark-mode .podcast-ep-btn.active {
  background: #f59e0b;
  color: #0f172a;
  border-color: #fbbf24;
}
.podcast-ep-num {
  font-size: 0.68rem;
  text-transform: uppercase;
  letter-spacing: 0.5px;
  opacity: 0.85;
}
.podcast-ep-duration {
  font-size: 0.68rem;
  opacity: 0.75;
  margin-left: 2px;
}
```

### 3. Logique JavaScript (`switchPodcastEpisode`)

```javascript
const PODCAST_EPISODES = {
  pre_s02: {
    id: 'pre_s02',
    btnId: 'epBtnPreS02',
    tag: '🎙️ Podcast Pilote • Pré-cours Séance 2',
    title: '« La perception est une hallucination contrôlée »',
    desc: "Discussion préparatoire générée d'après le corpus théorique initial (Andy Clark, Anil Seth, Dreyfus) : perception bayésienne, modèles prédictifs et fondements de la modélisation cognitive.",
    durationTag: 'Audio 22 min',
    durationDisplay: '22:42',
    src: '02_Lectures_et_Articles/Semaine_02_IA_Perspectives_historiques/Podcast/La_perception_est_une_hallucination_contrôlée.m4a'
  },
  deep_dive_s02: {
    id: 'deep_dive_s02',
    btnId: 'epBtnDeepDiveS02',
    tag: '🎙️ Grand Bilan Post-cours • Séance 2 (Étalon-Or)',
    title: "« De Descartes à NETtalk »",
    desc: "Bilan magistral étalon-or basé sur le Verbatim GOLD et les temps réels en classe : de la rupture cartésienne à la machine de Turing, la récursivité de Chomsky, les moteurs sémantiques de Haugeland (analogie du soccer), la surface d'erreur 3D et la démonstration sonore historique de NETtalk (1987).",
    durationTag: 'Audio 17 min',
    durationDisplay: '16:46',
    src: '02_Lectures_et_Articles/Semaine_02_IA_Perspectives_historiques/Podcast/PSY9613_S02_Episode_02_De_Descartes_a_NETtalk.m4a'
  },
  pre_s03: {
    id: 'pre_s03',
    btnId: 'epBtnPreS03',
    tag: '🎙️ Grand Deep Dive Pré-cours • Séance 3 (Lundi 28 sept.)',
    title: "« L'Espace de Travail Global du cerveau & Cadrage du Débat 1 »",
    desc: "Grand Deep Dive (23 min 27) préparant la Séance 3 : les mécanismes de l'Espace de Travail Neuronal Global (GNWT de Mashour, Dehaene et al.), l'embrasement conscient vs la modularité sensorielle, la diffusion globale, et le cadrage du Débat 1 (Louis B [POUR] vs Alexandrea Kelly [CONTRE]) modéré par Michel.",
    durationTag: 'Audio 23 min',
    durationDisplay: '23:27',
    src: '02_Lectures_et_Articles/Semaine_03_Traitement_information/Podcast/PSY9613_S03_Episode_03_Mashour_GNWT_et_Debat_01.m4a'
  }
};

let currentPodcastEp = 'deep_dive_s02';

function switchPodcastEpisode(epKey, autoPlay = false) {
  const ep = PODCAST_EPISODES[epKey];
  if (!ep) return;
  currentPodcastEp = epKey;

  // Mise à jour des boutons d'onglets
  document.querySelectorAll('.podcast-ep-btn').forEach(btn => {
    btn.classList.remove('active');
    btn.setAttribute('aria-selected', 'false');
  });
  const activeBtn = document.getElementById(ep.btnId);
  if (activeBtn) {
    activeBtn.classList.add('active');
    activeBtn.setAttribute('aria-selected', 'true');
  }

  // Mise à jour des textes
  const tagEl = document.getElementById('podcastTagBadge');
  const titleEl = document.getElementById('podcastBannerTitle');
  const descEl = document.getElementById('podcastBannerDesc');
  const durationBadge = document.getElementById('podcastDurationBadge');
  const durationEl = document.getElementById('audioDuration');

  if (tagEl) tagEl.textContent = ep.tag;
  if (titleEl) titleEl.textContent = ep.title;
  if (descEl) descEl.textContent = ep.desc;
  if (durationBadge) durationBadge.textContent = ep.durationTag;
  if (durationEl) durationEl.textContent = ep.durationDisplay;

  // Mise à jour du lecteur audio
  const audio = document.getElementById('localPodcastAudio');
  if (audio) {
    const wasPlaying = !audio.paused && audio.currentTime > 0;
    audio.pause();
    audio.src = ep.src;
    audio.load();
    const progress = document.getElementById('audioSeekSlider');
    const curTime = document.getElementById('audioCurrentTime');
    if (progress) progress.value = 0;
    if (curTime) curTime.textContent = '00:00';

    if (autoPlay || wasPlaying) {
      audio.play().catch(e => console.warn("Lecture bloquée:", e));
    }
  }
}
```

---

## 🚀 Actions Git (Session Maintenance)
1. **`.gitignore` :** Autoriser les fichiers audio finaux des podcasts :
   ```gitignore
   !02_Lectures_et_Articles/Semaine_02_IA_Perspectives_historiques/Podcast/*.m4a
   !02_Lectures_et_Articles/Semaine_03_Traitement_information/Podcast/*.m4a
   ```
2. **Commit & Push :**
   ```bash
   git add index.html 02_Lectures_et_Articles/Semaine_02_IA_Perspectives_historiques/Podcast/ 02_Lectures_et_Articles/Semaine_03_Traitement_information/Podcast/
   git commit -m "feat(audio): commutateur multi-podcasts (Ep 1 Pilote 22m, Ep 2 De Descartes a NETtalk 16:46, Ep 3 Mashour & Debat 1 23:27)"
   git push origin main
   ```
