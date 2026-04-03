# ⚙️ Services

This folder contains documentation for each self-hosted service running in my homelab.

## 📁 Structure
```
services/
├── README.md
├── home-assistant/
│   └── README.md
├── jellyfin/
│   ├── README.md
│   ├── jellyfin.md
│   └── jellyseerr.md
├── arr-stack/
│   ├── README.md
│   ├── radarr.md
│   ├── prowlarr.md
│   └── qbittorrent.md
├── pihole/
│   └── README.md
├── grocy/
│   └── README.md
├── seerr/
│   └── README.md
└── pterodactyl/
    └── README.md
```
## 📊 Overview

| Service        | Type | Port  | Description                    |
|----------------|------|-------|--------------------------------|
| Home Assistant | VM   | 8123  | Smart home automation          |
| Jellyfin       | LXC  | 8096  | Media server                   |
| Seerr          | LXC  | 5055  | Media request management       |
| Pi-hole        | LXC  | 90    | DNS ad blocker                 |
| Grocy          | LXC  | 80    | Household management           |
| Pterodactyl    | LXC  | 90    | Game server panel              |
| Radarr         | LXC  | 7878  | Movie automation               |
| Prowlarr       | LXC  | 9696  | Indexer management             |
| qBittorrent    | LXC  | 8080  | Torrent client                 |


## 📝 Each service folder contains
- Installation steps
- Configuration notes
- Issues encountered and how I fixed them
