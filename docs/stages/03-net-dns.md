## Objective
Design and deploy a private internal DNS for the homelab, allowing name-based access to on-prem services without affecting the home router or other users.

---

## Architecture Overview

- On-Prem Debian Server acts as:
  - Internal DNS authority
  - Local name resolution provider
- Client devices explicitly configured to use this DNS
- No changes applied to the home router

## 1. DNS Strategy

### Key Decisions
- Use a **non-public internal domain**
- Chosen domain: `homelab.lan`


# DNS Config
![dns config](/docs/assets/dns_conf.png)

# Testing SSH with DNS
(temp fix until I setup vpn connection)
![dns testing ssh conn](/docs/assets/dns_test_ssh.png)

---

Previous: [Stage 02 – Security Hardening](02-hardening.md)
