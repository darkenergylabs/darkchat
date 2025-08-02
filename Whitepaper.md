# DarkChat White Paper

**Version 0.1 — August 2025**  
Dark Energy Labs

---

## 🔰 Introduction

DarkChat is a decentralized, metadata-free messaging system built on SimpleX architecture and integrated exclusively with DarkPhone — a hardened GrapheneOS-based mobile device.

Unlike mainstream messengers, DarkChat requires no phone numbers, no accounts, and no app store involvement. All messages are routed via encrypted, ephemeral relays with no logging, no identifiers, and no metadata exposure.

Relay infrastructure is hosted on VPS servers hardened for security and based in privacy-first jurisdictions like Iceland.

---

## 🧭 Design Philosophy

DarkChat is built on five core principles:

- **Zero Identity** – No usernames, accounts, or phone numbers
- **No Metadata** – Messages are stripped of IPs, timestamps, and relationships
- **Trustless Infrastructure** – Relays don’t retain logs and are decentralized
- **Device-Level Hardening** – Available only via DarkPhone
- **Disappearability** – Messages and relationships vanish without a trace

Our goal is not just privacy — but **invisibility**.

---

## 🏗️ Architecture Overview

DarkChat uses the SimpleX protocol as its foundation. All communication occurs over temporary, unlinked relay sessions. Each user’s client negotiates connections through relay nodes that forward encrypted payloads without knowing sender or recipient.

**Relays**:
- Hosted on hardened VPS nodes (Iceland)
- Transmit messages only — no user storage, no logs
- Accept encrypted payloads and destroy data immediately

**Clients**:
- Only available via DarkPhone
- Use temporary invitations (QR codes, links)
- Run a modified SimpleX core with enforced routing

There are no user accounts, usernames, or contact syncing. Each session is temporary and peer-generated.

---

## 🔐 Encryption Stack

- **XChaCha20-Poly1305** for message encryption
- **X25519** for key exchange
- **Ed25519** for signatures
- Based on the Double Ratchet Protocol for forward secrecy
- Modular and ready for post-quantum algorithms in future updates

---

## 🔄 Comparison to Other Messengers

| Feature                    | Signal | Telegram | WhatsApp | DarkChat |
|---------------------------|--------|----------|----------|----------|
| Phone Number Required     | ✅     | ✅       | ✅       | ❌       |
| Centralized Infrastructure| ✅     | ✅       | ✅       | ❌       |
| Open Source               | Partial| ❌       | ❌       | ✅       |
| Metadata-Free             | ❌     | ❌       | ❌       | ✅       |
| Available on App Stores   | ✅     | ✅       | ✅       | ❌       |
| Self-Hosted Relays        | ❌     | ❌       | ❌       | ✅       |

---

## 🧱 Deployment Model

DarkChat is currently **only available on DarkPhone**, a pre-hardened mobile device distributed by Dark Energy Labs. Enterprise and advanced users may request isolated relay infrastructure for private deployments.

APK distribution and secure updates are handled through our own infrastructure — not via public stores.

---

## 🚧 Roadmap (Planned Features)

- 🔗 Meshtastic support for radio-based mesh messaging
- 🛰️ On-device peer relays for LAN/off-grid use
- 🧠 Post-quantum encryption rollout
- 🧰 Enterprise admin tooling for isolated deployments

---

For inquiries or partnerships, contact us securely via Signal.  
Website: [https://darkenergylabs.com](https://darkenergylabs.com)

