# Vulnerability Remediation Scripts – Testing & Deployment

**Hi Team,**

Following our initial vulnerability assessment, we’ve prepared a set of remediation scripts designed to address key findings. These scripts can be integrated into your deployment tools (e.g., SCCM) and should be **tested in a staging environment** before being rolled out to production.

---

## Remediation Scripts

1. [**Third-Party Software Removal – Wireshark**](https://github.com/ayubhali/MISC/blob/main/vul-remediations/remediation-wireshark-uninstall.ps1)  
   Removes unauthorized or insecure third-party software such as Wireshark.

2. [**Windows OS Secure Configuration – Insecure Protocols**](https://github.com/ayubhali/MISC/blob/main/vul-remediations/toggle-protocols.ps1)  
   Disables deprecated and insecure network protocols.

3. [**Windows OS Secure Configuration – Insecure Ciphersuites**](https://github.com/ayubhali/MISC/blob/main/vul-remediations/toggle-cipher-suites.ps1)  
   Restricts use of weak encryption cipher suites.

4. [**Windows OS Secure Configuration – Guest Account Group Membership**](https://github.com/ayubhali/MISC/blob/main/vul-remediations/toggle-guest-local-administrators.ps1)  
   Removes unnecessary guest accounts from the Local Administrators group.

---

Let me know if you have any questions or would like modifications to these scripts.

Best regards,  
**Ayub Ali**  
Security Analyst  
Governance, Risk, and Compliance
