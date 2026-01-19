# Necro_Scanner
# 📡 Coop-Scanner | Wifi Pentest & Recon Tool

**Coop-Scanner** est un outil de reconnaissance Wi-Fi furtif et collaboratif développé en Python. Il utilise le scan passif (mode monitor) pour cartographier les réseaux environnants sans émettre de paquets, le rendant invisible pour les systèmes de détection d'intrusion (WIDS).

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.10%2B-blue)
![Platform](https://img.shields.io/badge/platform-Linux-lightgrey)

---

## ✨ Fonctionnalités

- 🕵️ **Scan Furtif (Stealth) :** Capture passive via Scapy. Aucune requête "Probe" n'est envoyée.
- 🔍 **Découverte de SSID Cachés :** Identifie automatiquement les noms des réseaux masqués lorsqu'un client s'y connecte.
- 🏭 **Identification du Matériel :** Analyse du BSSID pour déterminer le fabricant du routeur (Nmap-style).
- 📊 **Interface Graphique (GUI) :** Dashboard en temps réel basé sur Tkinter avec gestion de threads pour une fluidité maximale.
- 📡 **Channel Hopping :** Saut automatique entre les canaux 1 et 14 (spectre 2.4GHz).
- 🤝 **Architecture Coopérative :** Structure modulaire prête pour l'intégration d'une base de données centralisée.

---

## 📸 Aperçu de l'interface



---

## 🚀 Installation & Utilisation

### Prérequis
- Un système **Linux** (Kali Linux, Parrot OS, ou Ubuntu).
- Une carte Wi-Fi supportant le **Mode Monitor** et l'injection de paquets.
- Privilèges **Root** (sudo).

### 1. Cloner le projet
```bash
git clone [https://github.com/votre-username/coop-scanner.git](https://github.com/votre-username/coop-scanner.git)
cd coop-scanner
