# Waver — Offline Desktop Music Player

**Waver** is a modern, lightweight, and feature-rich offline desktop music player built with **Electron**, **HTML**, **CSS**, and **JavaScript**. Designed with a sleek dark neon interface, it combines effortless local music library management with a **Pro 18-Band DSP Audio Engine**, **RGB Neon Wave Equalizer**, audiophile-grade **IEM & Spatial Sound modes**, and offline listening analytics.

---

## Key Features

### 1. Local Music Library & Smart Organization
* **100% Offline Playback:** Load entire music folders or individual audio files directly from your computer with zero internet dependency.
* **Quick Library Scan & Search:** Instantly search tracks by song title or artist name, or use **Scan All** to index your local folders.
* **Flexible Sorting:** Organize your music list by **System**, **Newest**, **Oldest**, or **A–Z**.
* **Track Tracker:** Quickly jump back to the currently playing song from anywhere in your library with the one-click **Locate** button.
* **Favorites & Playlists:** Save your favorite tracks to **Liked Songs** with a single click and organize custom **Playlists**.

### 2. Pro Audio Engine & Mix Lab (18-Band DSP)
* **Real-Time RGB Neon Wave Visualizer:** A smooth, dynamic multi-band neon wave visualizer that reacts in real time to your music's frequencies.
* **10-Band Graphic Equalizer (-12 dB to +15 dB):** Fine-tune individual frequency bands (`62 Hz`, `125 Hz`, `250 Hz`, `500 Hz`, `1 kHz`, `2 kHz`, `4 kHz`, `8 kHz`, `16 kHz`) with a one-click **Reset Flat** option.
* **Sound & Spatial Modes:** Switch seamlessly between **Stereo Direct (Clean)**, **Dolby Atmos**, and **3D Surround**.
* **Bluetooth Codec & Frequency Style Simulation:** Optimize output character with **LDAC 96kHz** (*Studio-level Air*), **aptX HD** (*Dynamic Punch*), and **AAC / SBC** (*Balanced Stream*), backed by **Auto Direct** processing.

### 3. Studio IEM & Music Flow Engine (Audiophile Grade)
* **Custom DSP Enhancements:**
  * **IEM Natural Crossfeed:** Blends natural speaker-angle cues between left and right channels for comfortable, fatigue-free In-Ear Monitor (IEM) staging.
  * **Analog Tube Warmth:** Adds subtle even-order harmonic saturation for a rich, warm, liquid musical tone.
  * **Silk Music Flow & Clarity:** Refines low-end clarity and smooth vocal-instrument separation.
  * **Studio Master Preamp:** Dedicated preamp gain slider for precise output volume control.
* **6 Audiophile IEM Presets:** `Harman IE - Silky Sub`, `Diffuse Field - True Neutral`, `IEM Warm Tube`, `IEM Micro Detail`, `Liquid Music Flow`, and `Open Stage Monitor`.
* **12 Studio & Genre Presets:** `Normal (Flat)`, `BT LDAC 96K`, `BT LDAC / aptX`, `Studio Reference`, `Acoustic`, `Bass Boost`, `Rock`, `Vocal`, `Pop`, `EDM / Club`, `Classical`, and `Hip-Hop`.

### 4. Immersive Now Playing View
* **Interactive Waveform Seekbar:** Scrub smoothly through any track with live elapsed and total duration timestamps.
* **Live Audio Technical Badges:** Displays real-time file format, bitrate, and sample rate info (e.g., `MP3 • 320 kbps • 44.1 kHz`).
* **Full Playback Controls:** Shuffle, Previous, Play/Pause, Next, Repeat, Volume control, **Up Next** queue preview, and a persistent bottom mini-player across all tabs.

### 5. Offline Listening Stats & Analytics
* **Session & Lifetime Tracking:** View total **Time Listened** (in minutes) and total **Plays** stored locally offline.
* **Top Tracks Leaderboard:** Automatically ranks your most-played songs along with their exact play counts.

---

## Tech Stack

* **Framework:** Electron (Desktop Runtime)
* **Frontend:** HTML5, CSS3 (Custom Dark Neon UI)
* **Audio & Logic:** Vanilla JavaScript, Web Audio API (DSP & Equalizer)

---

## Project Structure

```text
Waver-App/
├── main.js          # Electron main process & desktop window configuration
├── index.html       # Main UI layout, Mix Lab DSP, Stats, and Player views
├── icon.png         # Application icon
├── package.json     # Project metadata and dependencies
└── README.md        # Project documentation
