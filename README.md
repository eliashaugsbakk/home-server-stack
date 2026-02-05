### Server Stack deployd on my Banana Pi BPI-M5

### Pi (host)
- Armbian (OS)
- Docker
- openSSH
- ufw
- fail2ban
- log2ram
- logrotate
- unattended-upgrades
- tmux

### Containers
- Tor - SSH (host) & http (spring-web-app)
- Tailscale - vpn (lan)
- Spring - website
