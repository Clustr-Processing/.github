# 🌐 Clustr

### Decentralized Distributed Computing Platform

> Harness idle compute power across a decentralized network and execute workloads at scale.

---

## 🚀 Overview

**Clustr** is a decentralized distributed computing platform that aggregates idle compute resources across participant nodes.

It enables:
- ⚡ **Parallel execution** of arbitrary workloads  
- 🔒 **Isolated execution** via containerization  
- 🌍 **Scalable orchestration** across a distributed network  

Workloads are packaged into containers, dispatched to active nodes, executed locally, and reassembled into final results.

> Developed as part of the **Software Engineering Capstone (SFWRENG 4G06A)** at McMaster University.

---

## 🧠 Architecture

Clustr is built on a **modular, distributed system architecture** composed of three primary components:

### 🖧 Backend Orchestration
- **Framework:** Spring Boot  
- **Database:** MongoDB  
- **Communication:** RSocket over WebSockets  
- **Responsibilities:**
  - Job scheduling & distribution  
  - Node coordination  
  - Result aggregation  

---

### 💻 Participant Node (Execution Engine)
- **Tech Stack:** Kotlin + Compose Multiplatform  
- **Container Runtime:** Docker Engine API (Java Client)  
- **Responsibilities:**
  - Secure execution of workloads in containers  
  - Resource monitoring (CPU, memory)  
  - Communication with coordinator  

---

### 🌐 Web Dashboard
- **Frontend:** Next.js + React  
- **Responsibilities:**
  - Job submission & monitoring  
  - User interaction  

---

### 🔐 Shared Infrastructure
- **Authentication:** Firebase Auth  

---

## ⚙️ Key Features

- 🧩 **Decentralized Compute Network**
- 📦 **Containerized Workload Execution**
- 🔄 **Dynamic Job Distribution**
- 📡 **Low-latency Communication (RSocket)**
- 🔐 **Secure Node Isolation**
- 📊 **Scalable & Fault-Tolerant Design**

---

## 💻 Become a Participant

Contribute your machine’s idle compute power to the Clustr network.

### 📦 Prerequisites
- Install and run **Docker Desktop**
- Ensure Docker Engine is active before launching Clustr

👉 https://www.docker.com/products/docker-desktop/

---

### ⬇️ Download

| Platform | Installer | Format |
|----------|--------|--------|
| **macOS (Intel & Apple Silicon)** | [Download](../bin/Clustr-1.0.0.dmg?raw=true) | `.dmg` |
| **Windows (x64)** | [Download](../bin/Clustr-1.0.0.msi?raw=true) | `.msi` |
| **Linux (Debian/Ubuntu)** | [Download](../bin/clustr_1.0.0_amd64.deb?raw=true) | `.deb` |

---

## 🛠️ Tech Stack Summary

| Layer | Technologies |
|------|-------------|
| **Backend** | Spring Boot, MongoDB, RSocket |
| **Desktop Client** | Kotlin, Compose Multiplatform |
| **Frontend** | Next.js, React |
| **Infrastructure** | Docker, Firebase Auth |

---

## 📌 Future Improvements

- Intelligent workload scheduling (resource-aware distribution)
- Node reputation & trust scoring
- GPU workload support
- Secure task engine and containerization

---

## 👥 Contributors

Developed as part of McMaster University’s Software Engineering Capstone.

1. Abdallah Alqashqish
2. Omar Shehada
3. Beshoy Hezky
4. Noel Chungath Gregory
5. Muhammad Saad Salman