# Hi, I'm Muhammad Hakim 👋

Diploma in Information Technology student at UTHM — building real systems, not just projects.

I focus on **infrastructure, networking, and system operations**, with hands-on experience running production-like environments, designing resilient architectures, and managing real users.

My approach is simple:
**build → deploy → break → monitor → fix → document → improve**

---

## 🔥 Featured Projects

### 🚀 StudexHub (Production System)

A live student productivity platform designed, deployed, and operated with real infrastructure practices.

**What makes this different:**

* Deployed with **Docker + Nginx + Cloudflare Tunnel**
* Real users (live system, not just localhost)
* Designed with **operational thinking (runbooks, monitoring, recovery)**

**Key implementations:**

* Containerized app + PostgreSQL with Docker Compose
* Reverse proxy with Nginx
* Custom-built authentication system
* Monitoring stack: **Prometheus + Grafana + Alertmanager**
* Telegram-based control plane (restart, backup, alerts)
* Email notification system (Gmail API integration)
* CI pipeline (lint, build, secret scanning)

**Ops mindset:**

* Defined **MTTD (~10s), MTTR (~5 min)**
* Structured logging + incident handling
* Backup & recovery workflows
* Clear separation between app layer and infrastructure

---

### 🌐 Enterprise Campus Network Design

A full-scale simulated campus network built with enterprise architecture principles.

**Architecture:**

* Three-tier model: **Core / Distribution / Access**
* VLAN segmentation: Staff, Guest, VoIP, Management

**Key implementations:**

* Inter-VLAN routing (L3 + Router-on-a-stick)
* **HSRP** for gateway redundancy
* **OSPF** dynamic routing
* Centralized DHCP with relay
* VoIP with CME + Option 150
* ACL-based network security (Guest isolation)

**Focus areas:**

* Fault tolerance & failover testing
* Realistic traffic flow design
* CLI-based troubleshooting

---

### 🤖 Mini Control Plane (Telegram Bot)

A lightweight system operations tool for managing infrastructure remotely.

**Capabilities:**

* Service restart with confirmation flow
* Backup trigger system
* Health status checks
* Alert forwarding from monitoring stack

**Design principles:**

* Runs under a **low-privilege system user**
* Strict command allowlist
* Action logging for auditability

---

## 🛠️ Technical Skills

**Infrastructure & Systems**

* Linux (Debian / Ubuntu Server)
* Systemd, SSH, server management

**Networking**

* VLAN, OSPF, ACL, HSRP
* Network design & troubleshooting

**DevOps / Platform**

* Docker & Docker Compose
* Nginx (reverse proxy)
* Cloudflare Tunnel & Access
* GitHub Actions (CI basics)

**Monitoring & Operations**

* Prometheus, Grafana, Alertmanager
* Logging & incident handling
* Runbooks & operational workflows

**Programming**

* TypeScript (Next.js)
* Python (automation, bots)
* SQL (PostgreSQL, Prisma ORM)

---

## 🎯 Current Focus

* Strengthening **Linux system administration (deep level)**
* Advancing **networking → infrastructure → cloud pathway**
* Improving **observability, reliability, and automation**
* Scaling systems from **homelab → production-grade practices**

---

## 🧠 Mindset

I don’t just build features. I think in terms of:

* Failure scenarios
* Recovery speed
* System reliability
* Long-term maintainability

---

## 📫 Contact

* LinkedIn: https://www.linkedin.com/in/muhammad-hakim-zaaba-27b22a3b8
* Email: [hakimz.7117@gmail.com](mailto:hakimz.7117@gmail.com)
