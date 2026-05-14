# Findings

| ID | Finding | Evidence | Risk Level | Business Impact | Recommendation |
|---|---|---|---|---|---|
| F-001 | SSH service exposed on TCP port 22 | Nmap identified 22/tcp open ssh running OpenSSH 10.2p1 Ubuntu 2ubuntu3.2 | Low | SSH is necessary for remote administration, but if weak passwords or poor access controls are used, attackers could attempt unauthorized login. | Use strong passwords or SSH keys, disable root login, limit SSH access where possible, and keep OpenSSH updated. |

## Notes
The target VM has a minimal exposed attack surface. No unnecessary services were identified during the initial scan.
