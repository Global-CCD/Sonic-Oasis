# Sonic Oasis

https://img.shields.io/badge/License-MIT-blue.svg
https://img.shields.io/badge/Web%20Audio-API-orange
https://img.shields.io/badge/PWA-Ready-brightgreen

Sonic Oasis is a therapeutic sound & frequency single-page application (SPA) that generates high-quality audio directly in your browser — no external files, no streaming, no subscriptions. Designed for meditation, deep focus, sleep, and sonic healing.

https://via.placeholder.com/800x400?text=Sonic+Oasis+UI

🔊 Live Demo: [Add your deployed link here]

---

🎯 Overview

Sonic Oasis combines binaural beats, Solfeggio frequencies, 8D audio, colored noise, and ambient soundscapes into one minimal, mobile-friendly interface. Every sound is synthesized in real-time using the Web Audio API, ensuring instant playback and zero latency.

Whether you need:

· 💤 Delta waves for deep sleep
· 📚 Gamma & Beta waves for concentration
· 🧘 528 Hz for transformation & healing
· 🌧️ Rain, forest, or city sounds for background ambience

Sonic Oasis delivers a professional-grade sonic environment right from your browser.

---

✨ Features

Core Audio Engine

Feature Description
🧠 Binaural Beats Theta (4–8 Hz), Delta (1–4 Hz), Beta (13–30 Hz), Gamma (30–50 Hz) with separate left/right oscillators
🌈 Noise Colors White, Pink, Brown noise – ideal for masking tinnitus or improving focus
🎵 Solfeggio Frequencies 528 Hz (Miracle), 432 Hz (Relaxation), 136 Hz (Tibetan Bowl)
🌀 8D Audio Moving stereo pan effect for immersive depth
🌊 Water & Rain Heavy rainfall, flowing stream, ocean waves via filtered noise
🌿 Ambient Scapes Forest birds, city rain, home fireplace
👂 ASMR Gentle tapping & crackle textures

UI & Experience

· 🎛️ Global volume control for master output
· 🔘 Per-sound toggle – tap any tile to play/stop individually
· ⏹️ Stop all sounds button for instant silence
· 📱 Fully responsive – works on desktop, tablet, and mobile
· 🎨 Dark, calming theme with glass-morphism cards
· 🔍 Real-time active sound indicator – see what's playing at a glance
· 🧩 Four main categories:
  · Sleep & Relaxation
  · Focus & Study
  · Meditation & Healing
  · General Ambience

Technical Highlights

· ✅ No external audio files – everything synthesized on-device
· ✅ Low latency – instant start/stop
· ✅ Efficient CPU usage – script processor nodes + oscillators
· ✅ Zero dependencies – pure HTML/CSS/JS
· ✅ PWA ready – can be installed as a standalone app

---

🚀 Quick Start

Run Locally

```bash
# Clone the repository
git clone https://github.com/yourusername/sonic-oasis.git

# Navigate into the folder
cd sonic-oasis

# Serve with any static server
# Using Python 3:
python -m http.server 8000

# Or using npx:
npx serve .

# Open your browser at http://localhost:8000
```

Deploy to Production

One-click deploy options:

https://www.netlify.com/img/deploy/button.svg
https://vercel.com/button

Or simply copy index.html to any static hosting service (GitHub Pages, Cloudflare Pages, AWS S3, etc.)

---

🗺️ Roadmap – Future Features

🧪 Experimental (v1.1 – v1.3)

· Save custom mixes – store combinations of sounds with volumes
· Timer & fade-out – set a sleep timer (e.g., 30 min with gentle fade)
· Individual sound volume sliders – adjust each playing tile independently
· Waveform visualizer – real-time audio reactivity using Canvas API
· Keyboard shortcuts – spacebar = stop all, number keys = trigger favorites

🚀 Upcoming (v1.4 – v2.0)

· User accounts & cloud sync – save presets across devices
· Ambient mix recording – export your session as a WAV/MP3 file
· Extended Solfeggio set – 174 Hz, 285 Hz, 396 Hz, 417 Hz, 639 Hz, 741 Hz, 852 Hz, 963 Hz
· Isochronic tones – pulse-based alternative to binaural beats (no headphones required)
· Breathwork pacer – visual guide for inhale/hold/exhale cycles synchronized to sound
· Offline mode – cache with Service Worker for full PWA functionality

🌟 Long-term Vision (v3.0+)

· AI-generated soundscapes – unique sound environments based on mood prompts
· Community sound library – upload and share custom frequency presets
· Integration with wearables – heart-rate guided sound adaptation (via Web Bluetooth)
· Spatial audio (WebXR) – 3D sound positioning for VR/AR headsets
· Multi-channel mixer – route different sounds to left/right ears independently
· Desktop app (Electron/Tauri) – native version with system media controls

---

🛠️ Built With

· HTML5 – semantic structure
· CSS3 – flexbox, grid, backdrop filters, responsive design
· Vanilla JavaScript – no frameworks, pure DOM manipulation
· Web Audio API – oscillators, gains, filters, channel merger, stereo panner, script processors
· LocalStorage (planned) – for saving user presets

---

📁 Project Structure

```
sonic-oasis/
├── index.html          # Single file application (all CSS/JS included)
├── README.md           # This file
├── LICENSE             # MIT License
└── assets/             # (optional) screenshots, icons
```

Note: Sonic Oasis is intentionally a single HTML file for maximum portability. You can host it anywhere, email it, or save it locally.

---

🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (git checkout -b feature/amazing-feature)
3. Commit your changes (git commit -m 'Add some amazing feature')
4. Push to the branch (git push origin feature/amazing-feature)
5. Open a Pull Request

Please ensure your code:

· Works in latest Chrome, Firefox, Safari, and Edge
· Uses Web Audio API efficiently (no memory leaks)
· Follows accessible design practices

---

📄 License

Distributed under the MIT License. See LICENSE file for more information.

---

🙏 Acknowledgments

· Inspired by apps like Ambience, Brain.fm, and MyNoise
· Web Audio API documentation from MDN Web Docs
· Binaural beat generation techniques from academic research on auditory beat stimulation

---

📬 Contact

Project Maintainer: [Your Name]
Email: [your.email@example.com]
GitHub: @yourusername

Report bugs or request features: Issues Page

---

Made with 🎧 for focus, sleep, and healing
