# Findings Summary

## Critical Findings
1. **SSH Weak Credentials** – Default password "puppet" for root
2. **Privileged Access** – Direct root SSH login enabled

## High Findings
3. **Sensitive Data Exposure** – Flag file accessible in `/root`

## Medium Findings
4. **Outdated Services** – OpenSSH 6.0p1, Debian 7 (EOL)

## Remediation
- Change all credentials
- Disable root SSH login
- Update OS and services
- Implement logging/monitoring