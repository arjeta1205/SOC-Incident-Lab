
# Phase 1 — Virtual Machine Setup

## 🎯 Objective
Build a virtual SOC environment consisting of attacker and victim machines connected via an isolated network.

---

## 🖥️ Virtual Machines Created

### Windows 11 (Victim Endpoint)
- RAM: 6 GB
- CPU: 2 cores
- Role: Endpoint system for monitoring and attack simulation

### Kali Linux (Attacker)
- RAM: 3 GB
- CPU: 2 cores
- Role: Simulated attacker machine

---

## 🌐 Network Configuration

- Adapter 1: NAT (internet access)
- Adapter 2: Host-only network (internal lab communication)

This allows isolated communication between attacker and victim systems.

---
## 📌 Outcome

- Both machines are isolated from external systems
- Internal network communication is established
- Lab is ready for endpoint monitoring setup (Sysmon phase)

