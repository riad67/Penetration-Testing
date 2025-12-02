# Penetration-Testing
# Penetration Testing Report – CMBD 328/26

## Report Details
- **Client:** Confidential
- **Engagement Date:** November 23–25, 2025
- **Author:** Riad Hossain

## Objectives
1. Network enumeration and service discovery
2. Vulnerability identification and exploitation
3. Privilege escalation to root
4. Flag capture and proof of compromise

## Key Findings
| Severity     | Finding                          |
|--------------|----------------------------------|
| Critical     | SSH Weak Credentials             |
| Critical     | Privileged Access                |
| High         | Sensitive Data Exposure          |
| Medium       | Outdated Services                |

## Tools Used
- Nmap
- Hydra
- Netdiscover
- OpenSSH Client

## Risk Summary
Overall Risk Rating: **CRITICAL**

## 📌 Flag Captured
`flag{edd310f8dcee631f7c747965c359629e}`

## PoC

Figure 1: Network Discovery using netdiscover 

![image alt](https://github.com/riad67/Penetration-Testing/blob/main/images/1.png?raw=true)



Figure 2: Nmap Scanning

![image alt](https://github.com/riad67/Penetration-Testing/blob/main/images/2.png?raw=true)



Figure 3: Brute force attack using Hydra

![image alt](https://github.com/riad67/Penetration-Testing/blob/main/images/3.png?raw=true)



Figure 4: SSH successful login in the root directory

![image alt](https://github.com/riad67/Penetration-Testing/blob/main/images/4.png?raw=true)



Figure 5: User and password extraction

![image alt](https://github.com/riad67/Penetration-Testing/blob/main/images/5.png?raw=true)



Figure 6: /etc/shadow file contents showing password 

![image alt](https://github.com/riad67/Penetration-Testing/blob/main/images/6.png?raw=true)




## Disclaimer
This report is for **educational and authorized testing purposes only**. Unauthorized use is prohibited.

---
