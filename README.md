## Home Server Documentation

A $0 server, built on a 2010 ThinkPad

![Linux](https://img.shields.io/badge/Linux-OS-FCC624?logo=linux&logoColor=black)
![Ubuntu Server](https://img.shields.io/badge/Ubuntu_Server-26.04_LTS-E95420?logo=ubuntu&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-containers-2496ED?logo=docker&logoColor=white)
![Samba](https://img.shields.io/badge/Samba-file_sharing-CC0000?logo=samba&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-remote_access-242424?logo=tailscale&logoColor=white)


### Why I Built This

- **Learn the IT side of computing:** Linux, networking, containers, self-hosting, and remote access
- **Run a personal media server** for my music, movies, and TV shows

Inspired by [The $0 Home Server – Kalos Likes Computers](https://youtu.be/IuRWqzfX1ik)


### Hardware
| Part | Specs |
|------|------|
| Machine | Lenovo ThinkPad X201 (12", released 2010) |
| CPU | Intel Core i5 |
| RAM | 2 GB |
| Storage | 320 GB |
| Network | Ethernet |
| Power | Charger only (battery removed) |

<img width="532.5" height="219.5" alt="image" src="https://github.com/user-attachments/assets/d6330aea-0a13-4c18-ac1b-16ceea37b098" />



### Modification/Changes made before starting (and other useful info)
The laptop crashed whenever it was under load.
 
- **Cause:** Overheating. The old thermal paste was caked on, and a previous owner had put a piece of clear red tape between the heatsink and the CPU.
- **Fix:** Removed the tape, cleaned off the old paste, and applied new thermal paste.
- **Result:** No more crashes, and temperatures dropped.


### Operating System
- OS: Ubuntu Server
- Version: 26.04 LTS


### Users
- **OS:** Ubuntu Server 26.04 LTS
- **Users:** Just me
- **SSH Enabled?:** Yes (password enabled)
- **Remote Access:** Tailscale


### Installed Services
| Service | What it does |
|---------|--------------|
| SSH | Remote access |
| Samba | File sharing between Linux and Windows |
| Docker | Runs apps in containers |
| Navidrome | Music streaming |
| Jellyfin | Music, movies, and TV |
| Tailscale | Secure remote access |
| Fastfetch | System info in the terminal |
| Ncdu | Disk usage in the terminal |


### Change Logs
| Date | Change |
|------|--------|
| 2026-04-29 | Installed Ubuntu Server 26.04 LTS |
| 2026-04-29 | Installed Samba |
| 2026-04-29 | Installed Docker (replaced the outdated version with the official one) |
| 2026-04-30 | Installed Fastfetch |
| 2026-04-30 | Installed Navidrome in Docker after a few failed attempts |
| 2026-05-01 | Uploaded music to Navidrome |
| 2026-05-02 | Installed Jellyfin in Docker |
| 2026-05-04 | Installed Ncdu |
| 2026-05-07 | Set up Tailscale |

### Future Plans:
- [ ] Add monitoring (Uptime Kuma)
- [ ] Add a dashboard
- [ ] Install Gitea
- [ ] Install and set up Vaultwarden
