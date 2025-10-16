# debian-firewall-security
## Objective
Strengthen SSH security by configuring Fail2Ban and a firewall (UFW) to automatically block brute-force attacks and unauthorized login attempts.
This project demonstrates real-world Linux hardening and security operations skills.
## Tools & Tech
Debian Linux

Fail2Ban

UFW (Uncomplicated Firewall)

SSH (Secure Shell)
## What I Learned
How to configure SSH securely using key-based authentication

How to set up Fail2Ban to detect and block repeated failed logins

How to manage and monitor firewall rules with UFW

How to verify and test lockouts safely

## Steps
Installed and Verified Fail2Ban
```bash
sudo apt install fail2ban -y
sudo systemctl enable --now fail2ban
sudo systemctl status fail2ban
```
Configured SSH Jail
```bash
sudo nano /etc/fail2ban/jail.local
```




## Screenshots
