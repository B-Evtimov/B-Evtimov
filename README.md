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
- **Unity Basic** — co-author of a beginner textbook on Unity game development

### 🛠️ Tech

**Languages:** C# · Python ·  JavaScript / TypeScript · SQL  
**Hardware:** ESP32 · ESP8266 · Arduino · micro:bit · Raspberry Pi · 3D printing (parametric CAD)  
**Backend:** FastAPI · Node.js / Express · PostgreSQL · SQLite · MQTT · Docker / Podman  
**Mobile:** Android (Jetpack Compose) · React Native (Expo)  
**AI / ML:** PyTorch · MediaPipe · OpenAI & Gemini APIs · RAG / vector DBs  
**Security & infra:** Linux · threat modelling · E2E encryption · Ed25519 · GitHub Actions  
**Other:** Unity · Blender · Shopify

### 🎓 Learning

SoftUni — Programming Basics (Python), Programming Fundamentals (C#), AI Integrations for Developers.

### 💼 Open to work

Looking for a junior / intern role in **embedded, IoT, backend or AI** — Bulgaria or remote.  
📫 **borisevtimov1980@gmail.com** · [Instagram](https://www.instagram.com/__evtimov_)

---

<p align="center"><i>If it has a microcontroller or an API, I'm probably trying to connect it to something.</i></p>
