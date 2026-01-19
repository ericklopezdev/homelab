# Stage 02 – Security Hardening 

## Objective
Secure the Debian on-prem server following baseline hardening practices used in real infrastructures.

This stage focuses on reducing attack surface, securing SSH access, and protecting the server from brute-force attacks.

## Sub-Stages

- [02.01 SSH Key Setup](02.01-ssh-key.md)
- [02.02 SSH Configuration](02.02-ssh-config.md)
- [02.03 Firewall Setup](02.03-firewall.md)
- [02.04 Fail2Ban Installation](02.04-fail2ban.md)

---

## Threat Model
- Unauthorized SSH access
- Brute-force attacks
- Credential-based attacks

# First Test SSH
![testing first ssh conn](/docs/assets/test_ssh.png)

# Test SSH as ROOT
![testing ssh as root](/docs/assets/test_ssh_root.png)

---

Previous: [Stage 01 – Bootstrap Server](01-setup.md) | Next: [Stage 03 – Network](03-network.md)
