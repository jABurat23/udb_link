# USB Internet Bridge 🚀

A high-performance USB-based internet bridge that routes your laptop's internet connection to your Android device — optimized for stability, efficiency, and low-latency use cases.

> Inspired by Gnirehtet by Genymobile.

---

## 📌 Overview

USB Internet Bridge enables Android devices to access internet through a wired USB connection from a laptop or desktop.

Unlike traditional hotspot sharing, this approach:

* avoids wireless interference
* provides more stable connectivity
* enables deeper control over traffic routing and optimization

---

## 🎯 Goals

* Provide reliable USB-based internet sharing
* Optimize performance over ADB transport
* Build a modular and extensible networking engine
* Enable future features like compression and smart routing

---

## 🧠 Architecture

```
[ Internet ]
     ↓
[ Laptop Network ]
     ↓
[ Rust Core Engine ]
     ↓
[ ADB (USB Bridge) ]
     ↓
[ Android Client ]
     ↓
[ Phone Applications ]
```

---

## 🧩 Project Structure

```
core-engine/        Rust-based networking engine
desktop-app/        Tauri desktop controller
android-client/     Kotlin Android client
scripts/            ADB and development utilities
docs/               Technical documentation
```

---

## ⚙️ Tech Stack

* **Rust** — core networking engine
* **ADB (Android Debug Bridge)** — USB communication
* **Kotlin (Android)** — client application
* **Tauri** — lightweight desktop UI

---

## 🚧 Current Status

> 🚧 Early Development (Planning / MVP Stage)

Planned milestones:

* [ ] Basic USB connection via ADB
* [ ] Minimal packet forwarding
* [ ] Android VPN client
* [ ] Stable connection loop

---

## ⚡ Roadmap

### Phase 1 — Core Connectivity

* Establish ADB tunnel
* Route traffic from phone → laptop → internet

### Phase 2 — Stability

* Handle disconnects
* Improve reliability

### Phase 3 — Optimization

* MTU tuning
* Packet handling improvements

### Phase 4 — Advanced Features

* Compression
* Low latency mode
* Smart traffic prioritization

---

## 🙏 Credits

This project is inspired by:

* Gnirehtet (Genymobile)
  https://github.com/Genymobile/gnirehtet

We aim to explore alternative optimizations and architectural improvements while respecting the original project's contributions.

---

## ⚠️ Disclaimer

This project uses ADB as a transport layer, which introduces inherent limitations in throughput and latency. Performance may vary depending on hardware and system configuration.

---

## 📄 License

To be decided (MIT recommended for open-source projects).

---

## 🤝 Contributing

Contributions, ideas, and discussions are welcome.
This project is currently in early-stage development.

---
