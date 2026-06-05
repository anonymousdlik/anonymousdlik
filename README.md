<div align="center">

  <!-- 3D Robot Head SVG -->
  <svg width="180" height="180" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="bodyGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" style="stop-color:#2a2d3e;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#1a1c2e;stop-opacity:1" />
      </linearGradient>
      <linearGradient id="glowGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" style="stop-color:#00d4ff;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#7b2ff7;stop-opacity:1" />
      </linearGradient>
      <radialGradient id="eyeGlow" cx="50%" cy="50%" r="50%">
        <stop offset="0%" style="stop-color:#00d4ff;stop-opacity:1" />
        <stop offset="70%" style="stop-color:#0088cc;stop-opacity:0.6" />
        <stop offset="100%" style="stop-color:#004466;stop-opacity:0" />
      </radialGradient>
      <filter id="glow">
        <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
        <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
      <filter id="shadow">
        <feDropShadow dx="0" dy="4" stdDeviation="6" flood-color="#00d4ff" flood-opacity="0.15"/>
      </filter>
    </defs>

    <!-- Antenna -->
    <line x1="100" y1="28" x2="100" y2="15" stroke="#4a4d6e" stroke-width="3" stroke-linecap="round"/>
    <circle cx="100" cy="12" r="5" fill="url(#glowGrad)" filter="url(#glow)"/>

    <!-- Head -->
    <rect x="45" y="35" width="110" height="90" rx="20" ry="20" fill="url(#bodyGrad)" stroke="#3a3d5e" stroke-width="2" filter="url(#shadow)"/>

    <!-- Face plate -->
    <rect x="58" y="48" width="84" height="64" rx="12" ry="12" fill="#12142a" stroke="#2a2d4e" stroke-width="1"/>

    <!-- Left eye -->
    <circle cx="78" cy="75" r="12" fill="#0a0c1e" stroke="#00d4ff" stroke-width="1.5" opacity="0.8"/>
    <circle cx="78" cy="75" r="7" fill="url(#eyeGlow)" filter="url(#glow)"/>
    <circle cx="75" cy="72" r="2.5" fill="white" opacity="0.8"/>

    <!-- Right eye -->
    <circle cx="122" cy="75" r="12" fill="#0a0c1e" stroke="#00d4ff" stroke-width="1.5" opacity="0.8"/>
    <circle cx="122" cy="75" r="7" fill="url(#eyeGlow)" filter="url(#glow)"/>
    <circle cx="119" cy="72" r="2.5" fill="white" opacity="0.8"/>

    <!-- Mouth / Speaker grille -->
    <rect x="82" y="93" width="36" height="10" rx="5" ry="5" fill="#0a0c1e" stroke="#2a2d4e" stroke-width="1"/>
    <line x1="88" y1="98" x2="92" y2="98" stroke="#00d4ff" stroke-width="1.5" stroke-linecap="round" opacity="0.6"/>
    <line x1="96" y1="98" x2="100" y2="98" stroke="#00d4ff" stroke-width="1.5" stroke-linecap="round" opacity="0.6"/>
    <line x1="104" y1="98" x2="108" y2="98" stroke="#00d4ff" stroke-width="1.5" stroke-linecap="round" opacity="0.6"/>

    <!-- Ear panels -->
    <rect x="33" y="55" width="14" height="40" rx="5" ry="5" fill="#1e2040" stroke="#3a3d5e" stroke-width="1.5"/>
    <rect x="153" y="55" width="14" height="40" rx="5" ry="5" fill="#1e2040" stroke="#3a3d5e" stroke-width="1.5"/>
    <circle cx="40" cy="75" r="3" fill="#00d4ff" opacity="0.4"/>
    <circle cx="160" cy="75" r="3" fill="#00d4ff" opacity="0.4"/>

    <!-- Neck -->
    <rect x="80" y="125" width="40" height="18" rx="4" ry="4" fill="#1e2040" stroke="#2a2d4e" stroke-width="1"/>
    <line x1="88" y1="132" x2="112" y2="132" stroke="#3a3d5e" stroke-width="1"/>
    <line x1="88" y1="137" x2="112" y2="137" stroke="#3a3d5e" stroke-width="1"/>

    <!-- Shoulders hint -->
    <path d="M 55 143 Q 100 155 145 143" stroke="#2a2d4e" stroke-width="2" fill="none"/>
    <path d="M 50 148 Q 100 162 150 148" stroke="#1a1c2e" stroke-width="3" fill="none"/>

    <!-- Status LED -->
    <circle cx="100" cy="155" r="3" fill="#64ffda" filter="url(#glow)">
      <animate attributeName="opacity" values="1;0.3;1" dur="2s" repeatCount="indefinite"/>
    </circle>
  </svg>

  <h1>Fadli Yeh</h1>
  <p><em>IoT × AI Engineer — Building smart things that think.</em></p>

  <p>
    <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=ffd343" />
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
    <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  </p>

</div>

---

## 👋 About

Mahasiswa **Teknik Elektro** di Universitas Bina Darma, Palembang.
Fokus di perpotongan **IoT** dan **Deep Learning** — dari sensor sampai neural network.

Suka bikin hal-hal yang *terlihat sederhana tapi di dalamnya ada otak*.

---

## 🛠️ Featured Projects

| Project | What | Stack |
|---|---|---|
| **Jarvis-ID** | AI asisten pribadi berbahasa Indonesia | Python |
| **Fakhara AI** | Platform audit ESG otomatis untuk UMKM | TypeScript |
| **Math AI Assistant** | Pemecah soal matematika bertenaga AI | JavaScript |
| **Linux AI Assistant** | Troubleshooting Linux via AI + Groq API | Python |
| **Simulasi Energi** | Simulasi & analisis sistem energi | Python |
| **Electrical AI Assistant** | Asisten AI untuk teknik elektro | Python |

---

## 📊 Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=anonymousdlik&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d4ff&icon_color=7b2ff7&text_color=b4c2e0)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anonymousdlik&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d4ff&text_color=b4c2e0)

---

<div align="center">
  <sub>⚡ Palembang, Indonesia — Universitas Bina Darma</sub>
</div>
