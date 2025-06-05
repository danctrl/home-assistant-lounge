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
