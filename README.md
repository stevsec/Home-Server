### CURRENT PROJECT:

# Home Server Documentation

### Overview

- The purpose for this is to learn more about the IT side of computing. The 2nd reason is set up media server.
  - The $0 Home Server - Kalos Likes Computers
  - https://youtu.be/IuRWqzfX1ik?si=NFn_1WRt_5dBWWkG
---
### Hardware
- Machine: 12" Lenovo Thinkpad x201 (released in 2010)
- CPU: Intel Core i5
- Ram: 2gb
- Storage: 320gb
- Network: Ethernet
- 64 bit Operating System
---
### Modification/Changes made before starting (and other useful info)
  - Computer used to crash when stressed out. Diagnosed the issue. Bought some Thermal Paste to replaced the old Thermal paste. Turns out whoever owned this laptop before me added a red clear piece of tape between the heatsink and the CPU. Also the Thermal Paste was caked on. Replaced it and the laptop stopped crashing. Tempature also dropped. Does not overheat anymore.
  - Battery was removed. Will only operate with the charger. Uses Ethernet.
---
### Operating System
- OS: Ubuntu Server
- Version: 26.04 LTS
---
### Users
- Primary User: Me
- Other Users: No
- SSH Enabled?: Yes
- Auth Method: Password
---
### Installed Services
- **SSH:** For remote access
- **Samba:** To share files between Linux and Windows
- **Docker:** To run apps in containers to not mess up the server
- **Navidrome:** To self-host my music file
- **Jellyfin:** To self-host music, movies, TV shows, and other personal media
- **Substreamer:** To listen to self-hosted music from **Navidrome** on my ios device
- **Fastfetch:** To display system information in the terminal
- **Ncdu:** To display disk usage in the terminal
---
### Change Logs
- **04-29-2026:** Installed Ubuntu Sever 26.04 LTS
- **04-29-2026:** Installed Samba
- **04-29-2026:** Installed Docker
- **04-29-2026:** Deleted old Docker since it was outdated and reinstalled Docker from their official repository
- **04-30-2026:** Installed Fastfetch
- **04-30-2026:** Successfully installed Navidrome after a couple failed attempts (Installed in Docker)
- **05-01-2026:** Uploaded music files to Navidrome
- **05-02-2026:** Installed Jellyfin on Docker
- **05-04-2026:** Installed Ncdu
- **05-07-2026:** Set up Tailscale
---
### Notes:
