# 👋 Agent Vaedah

> **Precision Engineering** × **Mobile-First Design** × **Offline-Resilient Systems**

Building production-grade telemetry platforms and intelligent automation layers for resource-constrained environments.

---

## 📊 Activity & Impact

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=agentvaedah&show_icons=true&theme=dark&bg_color=1a1a2e&title_color=16c784&icon_color=16c784)

---

## 🛠️ Tech Stack

### **Languages & Runtimes**
![Kotlin](https://img.shields.io/badge/Kotlin-2.1.0-purple?style=flat-square&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.9+-3776ab?style=flat-square&logo=python&logoColor=white)
![JVM](https://img.shields.io/badge/JVM-17-orange?style=flat-square&logo=java&logoColor=white)

### **Mobile & UI**
![Android](https://img.shields.io/badge/Android-14--15-3DDC84?style=flat-square&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-Latest-4285F4?style=flat-square)
![Material 3](https://img.shields.io/badge/Material_Design-3-0D47A1?style=flat-square)

### **Backend & Networking**
![Ktor](https://img.shields.io/badge/Ktor-3.0.3-087CFA?style=flat-square&logo=ktor)
![OkHTTP](https://img.shields.io/badge/OkHTTP-Latest-4CAF50?style=flat-square)
![Requests](https://img.shields.io/badge/Requests-2.31+-FFD43B?style=flat-square)

### **Database & Storage**
![Room](https://img.shields.io/badge/Android_Room-6.1-00C853?style=flat-square)
![SQLite](https://img.shields.io/badge/SQLite-Latest-003B57?style=flat-square&logo=sqlite)
![DataStore](https://img.shields.io/badge/DataStore-1.1.1-5C6BC0?style=flat-square)

### **Geolocation & Maps**
![MapLibre](https://img.shields.io/badge/MapLibre-11.8.0-E74C3C?style=flat-square)
![GPS/GNSS](https://img.shields.io/badge/GPS_GNSS-500ms_polling-FF6B6B?style=flat-square)

### **IoT & Sensors**
![BLE/GATT](https://img.shields.io/badge/Bluetooth_LE-0x180D_0x1816-0073E6?style=flat-square)
![IMU](https://img.shields.io/badge/IMU_Accelerometer-Dead_Reckoning-FF9800?style=flat-square)

### **DI & Architecture**
![Dagger Hilt](https://img.shields.io/badge/Dagger_Hilt-2.54-FFC400?style=flat-square)
![Coroutines](https://img.shields.io/badge/Coroutines-1.9.0-6C63FF?style=flat-square)

### **Build & CI/CD**
![Gradle](https://img.shields.io/badge/Gradle-8.7.3-02303A?style=flat-square&logo=gradle)
![KSP](https://img.shields.io/badge/KSP-2.1.0-9C27B0?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-Auto_Build-2088FF?style=flat-square&logo=github-actions)

### **Testing**
![JUnit 5](https://img.shields.io/badge/JUnit5-89_tests-25A162?style=flat-square)
![Kotlin Serialization](https://img.shields.io/badge/kotlinx.serialization-1.7.3-7F52FF?style=flat-square)

---

## 📦 Projects

### **1️⃣ Strideway** — *Endurance Tracker & Cycling Head Unit*

```
┌─────────────────────────────────────────────────────────┐
│ 🚴 Smart Offline-First Android Cycling Computer        │
│                                                          │
│ ✨ Features:                                            │
│   • Dual BLE Hub (HR + Cadence/Speed sensors)          │
│   • 3D Vector Maps (MapLibre offline navigation)       │
│   • AI Coach Integration (OpenAI/Gemini/Claude)        │
│   • Telemetry: Keytel 2005 calorie formula            │
│   • Auto-Pause + IMU Dead Reckoning (GPS loss)        │
│   • Social Share Cards (visual export)                 │
│                                                          │
│ 🏗️ Stack:                                              │
│   Kotlin 2.1.0 | Jetpack Compose | Room 6.1            │
│   Ktor 3.0.3 | MapLibre 11.8.0 | Dagger Hilt           │
│   Coroutines | JUnit 5 (89 tests)                      │
│                                                          │
│ 📱 Platform:                                            │
│   Android 8.0–15 (API 26–35) | 100% Offline-First      │
│   Tested: Nokia 5.3 (resource-constrained)             │
│                                                          │
└─────────────────────────────────────────────────────────┘

Tech Detail:
├─ :core (Pure JVM/Kotlin — KMP-ready)
├─ :app (Compose UI layer)
├─ BLE GATT Handlers (0x180D, 0x1816 profile support)
├─ Fisiologi Calculations (real-time HR zones)
├─ GPX/TCX/FIT Route Parser
└─ CI/CD: GitHub Actions (auto APK)
```

**Badges:**
![Build](https://github.com/agentvaedah/strideway/actions/workflows/android.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Tests: 89](https://img.shields.io/badge/Tests-89%20passed-brightgreen.svg)

---

### **2️⃣ ApiBor** — *TokenHarbor Auto-Register Bot*

```
┌─────────────────────────────────────────────────────────┐
│ 🤖 API Key Farming & Account Pooling Automation        │
│                                                          │
│ ✨ Features:                                            │
│   • Automated account registration (TokenHarbor)       │
│   • Batch processing (N accounts in parallel)          │
│   • API key testing (mimo-v2.5:free validation)        │
│   • 9Router injection (live pool management)           │
│   • Proxy rotation support (environment-aware)         │
│   • Code obfuscation (XOR + zlib + base85)            │
│                                                          │
│ 🏗️ Stack:                                              │
│   Python 3.9+ | Requests 2.31+ | SQLite                │
│   argparse | urllib | json | sqlite3                   │
│   Async batch processing | Environment management      │
│                                                          │
│ 🔐 Security:                                            │
│   • Encoded source (anti-inspection)                   │
│   • SQLite accounts DB (persistent state)              │
│   • Proxy-aware (no direct exposure)                   │
│   • Machine ID licensing (per-install verification)    │
│                                                          │
└─────────────────────────────────────────────────────────┘

Tech Detail:
├─ Entry: bot.py (CLI + menu-driven)
├─ Core: _core.py (obfuscated logic)
├─ Signup Flow: multipart form-data + Turnstile CAPTCHA
├─ Injection: SQLite DB → 9Router entries
├─ Scaling: Batch mode (10–100 accounts)
└─ License: @machine_id_bot (Telegram verification)
```

---

## 🎯 Development Principles

| Principle | Application |
|-----------|-------------|
| **Offline-First** | Strideway: zero internet required for core functionality |
| **Resource-Constrained** | Runs on Nokia 5.3, ~2GB RAM, intermittent connectivity |
| **Modular Architecture** | Separate `:core` (pure JVM) from UI — enables KMP migration |
| **Type-Safe** | 100% Kotlin + serialization + Room migrations |
| **Tested** | 89 unit tests in :core, CI/CD auto-validation |
| **Secure by Default** | Keystore-backed API keys, no plaintext secrets |

---

## 🔗 Quick Links

- **GitHub:** [agentvaedah](https://github.com/agentvaedah)
- **Strideway Issues:** [Report bugs](https://github.com/agentvaedah/strideway/issues)
- **ApiBor Licensing:** [@machine_id_bot](https://t.me/machine_id_bot) on Telegram

---

## 📈 Current Focus

- [ ] Strideway v0.5: Kotlin Multiplatform (KMP) migration
- [ ] ApiBor: Enhanced anti-detection (header spoofing, request timing)
- [ ] Telemetry: Garmin/Wahoo device parity testing
- [ ] Social: In-app activity sharing (Strava, Komoot import)

---

**Last Updated:** October 2026  
**Status:** Active Development  
**License:** MIT (Strideway) | Custom (ApiBor)
