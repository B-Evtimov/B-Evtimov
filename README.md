<h1 align="center">Hi, I'm Boris 👋</h1>
<p align="center"><b>Hardware + software engineer from Bulgaria</b><br>
I build systems that <b>sense</b>, <b>think</b> and <b>stay secure</b> — from ESP32 firmware to AI models to hardened backends.</p>

---

### 🚪 Featured project

**[Doors Control System](https://github.com/B-Evtimov/doors-control)** — phone-only door access control: Android app (Kotlin, Jetpack Compose) + FastAPI + PostgreSQL + ESP32 controllers that dial out and never listen. Unlock commands are signed by an isolated process with no network access, controllers authenticate with Ed25519 challenge-response, and the audit log is append-only in three layers with a hash chain that detects tampering — proven by a test that attacks it as a database superuser. 34 tests, CI for backend, migrations, firmware and app.

### 🔭 What I'm building

- **📡 Wi-Fi 3D Human Tracking (CSI)** — estimating human pose from Wi-Fi signals alone. 8 ESP32 receiver nodes, 3-camera MediaPipe ground truth, HDF5 dataset pipeline, a custom PyTorch model (`CsiPoseNet`) and live radar-style inference. *In progress.*
- **☁️ Personal Cloud** — self-hosted file storage with end-to-end encryption: files are encrypted on the phone, the server only ever stores opaque blobs. Node.js backend + React Native (Expo) app. *Private.*
- **🏫 School OS** — building automation for a real school: ESP8266 nodes, MQTT, FastAPI and scheduled lighting, with Wi-Fi CSI occupancy detection planned for V2. *Private.*
- **📄 School Docs AI** — an AI assistant for school paperwork: document generation from templates, RAG over Bulgarian education law with source citations, validation of required fields. *In progress.*

### 🧪 Other things I've made

- **[GeminiInBlender](https://github.com/B-Evtimov/GeminiInBlender)** — an AI agent that controls a 3D scene in Blender from natural language
- **[Bluetooth radar](https://github.com/B-Evtimov/bluetooth_radar)** — real-time 3D radar of nearby BLE devices in Three.js
- **[Smart barrier](https://github.com/B-Evtimov/smart_barrier)** — parking barrier with license plate recognition (OpenCV + OCR)
- **[RFID door lock](https://github.com/B-Evtimov/RFID_Door_Lock)**, **[smart blinds](https://github.com/B-Evtimov/IoT-smart-blinds)** (Alexa / Google Assistant), **[gas detector](https://github.com/B-Evtimov/GasDetector)**
- **CodeQuest** — a gamified, Duolingo-style platform for learning to code (Node.js, PostgreSQL, Redis, Docker, Stripe). *Private.*
- **Unity Basic** — co-author of a beginner textbook on Unity game development: https://a.co/d/05W5goBN (With pen up name)

### 🛠️ Tech

**Languages:** C# · Python ·  JavaScript / TypeScript · SQL  
**Hardware:** ESP32 · ESP8266 · Arduino · micro:bit · Raspberry Pi · 3D printing (parametric CAD)  
**Backend:** FastAPI · Node.js / Express · PostgreSQL · SQLite · MQTT · Docker / Podman  
**Mobile:** Android (Jetpack Compose) · React Native (Expo)  
**AI / ML:** PyTorch · MediaPipe · OpenAI & Gemini APIs · RAG / vector DBs  
**Security & infra:** Linux · threat modelling · E2E encryption · Ed25519 · GitHub Actions  
**Other:** Unity · Blender · Shopify

### 🎓 Certificates
 
Earned at **[SoftUni](https://softuni.bg)** — all eight with the top grade, **6.00 / 6.00**. Click **verify** to open the official certificate on softuni.bg.
 
| Course | Date | Certificate |
|:--|:--|:--:|
| Programming Basics (Python) | July 2025 | [![verify][verify]][cert-basics] |
| Programming Fundamentals with C# | September 2025 | [![verify][verify]][cert-fundamentals] |
| C# Advanced | January 2026 | [![verify][verify]][cert-advanced] |
| C# OOP | February 2026 | [![verify][verify]][cert-oop] |
| MS SQL | May 2026 | [![verify][verify]][cert-mssql] |
| Entity Framework Core | June 2026 | [![verify][verify]][cert-efcore] |
| AI Integrations for Developers | June 2026 | [![verify][verify]][cert-ai] |
| ASP.NET Fundamentals | November 2026 | [![verify][verify]][cert-aspnet-fund] |
 
⏳ In progress: **ASP.NET Advanced**
 
<!-- SoftUni certificate links: softuni.bg → Сертификати → each certificate's verification URL -->
[verify]: https://img.shields.io/badge/SoftUni-verify-FFA02C?style=flat-square
[cert-basics]: https://softuni.bg/Certificates/Details/249772/59c3f588
[cert-fundamentals]: https://softuni.bg/Certificates/Details/254014/e67f5356
[cert-advanced]: https://softuni.bg/Certificates/Details/256757/4cc2a9f6
[cert-oop]: https://softuni.bg/Certificates/Details/259378/546e0910
[cert-mssql]: https://softuni.bg/Certificates/Details/262148/681c6906
[cert-efcore]: https://softuni.bg/Certificates/Details/263661/b6eef7ae
[cert-ai]: https://softuni.bg/Certificates/Details/264513/8b98712d
[cert-aspnet-fund]: https://softuni.bg/Certificates/Details/267124/ed46a01d

### 💼 Open to work

Looking for a junior / intern role in **embedded, IoT, backend or AI** — Bulgaria or remote.  
📫 **borisevtimov1980@gmail.com** · [Instagram](https://www.instagram.com/__evtimov_)

---

<p align="center"><i>If it has a microcontroller or an API, I'm probably trying to connect it to something.</i></p>
