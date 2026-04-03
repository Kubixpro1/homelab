# 🏠 Homelab

This repository documents my personal homelab environment used for learning system administration, networking, and self-hosting.

## 🧠 Overview

My homelab is built on a Proxmox-based setup running multiple services for automation, media, and network management.

This project demonstrates my practical skills in:

- Linux administration
- Networking
- Virtualization
- Self-hosting

## 🖥️ Hardware

- Raspberry Pi 5
- Storage: 64GB
- Role: Main server

## 🧱 Virtualization

- Proxmox VE (bare metal)
- LXC containers and virtual machines

## 🌐 Network

- Subnet: `192.168.8.0/24`
- Main server IP: `192.168.8.103`
- Local network (LAN)

## ⚙️ Services

| Service        | Description              |
|----------------|--------------------------|
| Home Assistant | Smart home automation    |
| Jellyfin       | Media server             |
| Jellyseerr     | Media request management |
| Pi-hole        | DNS ad blocker           |
| Grocy          | Household management     |
| Pterodactyl    | Game server panel        |
| Radarr         | Movie automation         |
| Prowlarr       | Indexer management       |
| qBittorrent    | Torrent client           |

## 🧩 Architecture

The system consists of:

- Proxmox host
- LXC containers for services
- Internal network communication

Internet
|
Router
|
Proxmox (Raspberry Pi 5)
├── Home Assistant
├── Jellyfin
├── Jellyseerr
├── Pi-hole
├── Grocy
├── Pterodactyl
├── Radarr
├── Prowlarr
├── qBittorrent
└── Seerr

## 🛠️ Skills Demonstrated

- Linux system administration
- Networking (IP, subnetting)
- Virtualization (Proxmox)
- Containerization (LXC, Docker basics)
- Self-hosted services

## 🔒 Security

- No sensitive data stored in repository
- Credentials managed externally

## 🚀 Goal

This homelab is used to:

- Learn infrastructure management
- Practice real-world IT scenarios
- Build a portfolio for future job opportunities

## 💬 Contact

If you have any questions or need help, you can reach me on Discord:

- Discord: **beton_pro1**
