<<<<<<< HEAD
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/a/ab/New_Home_Assistant_logo.svg" width="150" alt="Home Assistant Logo">
</p>

<h1 align="center">🏟️ Home Assistant – Lounge Instance</h1>

Welcome to my **Home Assistant configuration** for the `Lounge` environment — a focused, reliable, and self-hosted smart home setup built with automation, clarity, and resilience in mind.

This public repo serves as:
- 🧠 A version-controlled backup of my Stadium instance
- 📚 A reference for others looking to structure their HA config
- 🔄 A foundation for daily automated syncs to GitHub

> ⚠️ No sensitive information included — `secrets.yaml`, `.storage/`, tokens, and other private data are ignored via `.gitignore`.

---

## 📁 Structure

```bash
/config/
├── configuration.yaml       # Core config
├── automations.yaml         # Manual automations
├── scripts.yaml             # Reusable actions
├── scenes.yaml              # Lighting & moods
├── www/                     # Custom frontend assets
├── custom_components/       # Optional custom integrations
└── ...
```

---

## 🔄 Auto Backup

This configuration is:
- Automatically synced to GitHub **every night at 03:00**
- Using a custom `push.sh` script and `cron`
- Git commits are timestamped for full history traceability

---

## 🚧 Notes

- This is part of a dual-instance setup: see [home-assistant-lounge](https://github.com/danctrl/home-assistant-lounge) for the second zone.
- Everything here is tailored to **my specific hardware, network setup, and use cases** — feel free to fork and adapt.

---

## 🤝 Contributing / Feedback

This project is personal, but if you have **ideas, feedback or questions**, feel free to open an issue or discussion.

---

## 🧙‍♂️ Author

**danctrl** – [danctrl.dev](https://danctrl.dev)  
I build self-hosted systems, clean automations, and occasional chaos.

---
=======
# 🏡 Home Assistant – Lounge

Hi there! 👋
Welcome to my personal smart home project, codenamed **“Lounge”** – a local-first, privacy-respecting, and modular Home Assistant setup.

I'm running this on a Lenovo ThinkCentre M710q with RHEL 9.5, virtualized via KVM. The goal: reliable automation, native Apple Home integration, and a clean structure I can build on.

---

## 📊 Quick Stats

| Description               | Value                          |
|---------------------------|--------------------------------|
| Entities in total         | 286           |
| Number of sensors         | 115    |
| Installed add-ons         | 0           |
| HACS components (custom)  | 0  |}

---

## ⚙️ Hardware Overview

- 💻 **Device**: Lenovo ThinkCentre M910q (Intel i3)
- 🧠 **OS**: Red Hat Enterprise Linux 9.5
- 🖥️ **Hypervisor**: KVM + Home Assistant OS VM
- 📡 **Zigbee**: Sonoff Zigbee Dongle Plus (via ZHA)
- 🌐 **Thread / Matter**: Sonoff Zigbee Dongle E (Thread Border Router)

---

## 🧠 Architecture at a Glance

- Home Assistant OS in a dedicated KVM VM
- Reverse proxy managed via **Traefik**, protected with **Authentik (OIDC)**
- Zigbee (ZHA), Matter, MQTT and HomeKit all integrated
- Secure automation deployment and secrets handling
- Backup to Google Drive and config versioning with GitHub

---

## 🧩 Installed Add-ons
🚧 [Under Construction](https://github.com/custom-components/readme/issues/22) 🚧
---

## 🧬 HACS Integrations

These are custom components installed through HACS:

---

## 🎨 Lovelace Plugins

---

## 🎭 Themes

---

## 🤖 Favorite Automations

Here are some automations I use daily or am particularly proud of:

🔨 Work in progress!

---

## 🔒 Security & Backups

- 🔐 Access secured with Traefik + Authentik
- 📦 Daily encrypted backups pushed to Google Drive
- 🧾 Secrets are stored securely in `secrets.yaml`
- 🔍 Periodic checks with Lynis and SSH terminal access

---

## 📝 Final Notes

This README is automatically generated using the  
[custom-components/readme](https://github.com/custom-components/readme) integration.

If you’re reading this and are working on your own smart home — feel free to borrow ideas or reach out!
>>>>>>> f75025d (🔄 Automated sync on 2025-06-05 at 02:36)
