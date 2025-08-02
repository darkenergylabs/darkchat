# DarkChat Architecture

DarkChat is built on the foundation of the **SimpleX protocol**, a messaging architecture designed to eliminate metadata, central directories, and persistent identifiers. Unlike traditional messengers, which rely on static user accounts and contact syncing, DarkChat enables dynamic, one-time session-based communication over a **decentralized mesh of relays**.

---

## 🔄 Relay Mesh

DarkChat operates within a global, decentralized network of relay nodes. These relays are:

- 📡 Based on the SimpleX relay specification (`simplexmq`)
- 🌍 Run by privacy-focused individuals, organizations, or trusted infrastructure providers
- 🛡️ Configurable — users and organizations can run their own relays and connect only to trusted peers
- 🚫 Non-logging — relays forward encrypted payloads only; they do not store user IDs, IPs, or messages

This mesh structure ensures there is **no central authority**, and allows DarkChat to scale as a collaborative privacy infrastructure — open to aligned entities, colleagues, and communities.

---

## 🔒 Session-Based Communication

Each interaction between users is established through a **one-time invitation** (QR code or link). Once accepted, a secure channel is created using **asymmetric key exchange**, and a **double ratchet encryption protocol** is used to protect all messages.

---

## 🔀 One-Way Messaging Channels

Messages in DarkChat are routed through **ephemeral, unidirectional relays**, reducing metadata and correlation risks. There are no persistent contact graphs, accounts, or centralized indexes.

---

## 🔍 No Global Directories

DarkChat does not maintain any searchable user directory or contact syncing feature. All relationships are initiated directly by the user through invitation links, making the network invisible and untraceable to outside observers.

---

DarkChat’s architecture allows individuals and organizations to participate in a global privacy-first communication network — without compromising decentralization, identity, or control.
