#Stage 01 – Bootstrap Server 

## Aim
Provide a minimal Debian server as a secure base for a hybrid home lab.

## Technical decisions
- Debian stable (stability > features)
- Minimal installation (no GUI)
- Remote access via SSH

## Steps taken
- Clean Debian installation
- Local red configuration
- Creation of users without root
- Disable root login via SSH

# Debian Installed
![debian_installed](/docs/assets/debian_installed.png)

# Config User
![config user](/docs/assets/sudo_conf.png)

---

Next: [Stage 02 – Security Hardening](02-hardening.md)

