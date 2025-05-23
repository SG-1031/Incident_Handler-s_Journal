# Incident Handler's Journal (2024–2025)

---

## Journal Entry 1: Tietoevry Ransomware Attack (Sweden)  
**Date:** January 19–20, 2024  
**Entry:** 1  
**Description:**  
In January 2024, Finnish IT provider Tietoevry suffered a ransomware attack targeting its Swedish data center. The Akira ransomware gang encrypted virtualization servers hosting services for approximately 120 clients, including government agencies and universities. The breach was detected overnight, leading to immediate isolation and recovery efforts. The attack exploited VPN vulnerabilities, emphasizing the importance of patch management and network segmentation.  
**Tool(s) Used:** Monitoring systems, forensic tools, backup recovery solutions  
**The 5 W's:**  
- **Who:** Akira ransomware gang  
- **What:** Ransomware encryption of servers  
- **When:** January 19–20, 2024  
- **Where:** Swedish data center managed by Tietoevry  
- **Why:** Ransom/Extortion via exploiting VPN weaknesses  
**Additional Notes:**  
Recovery involved system isolation and restoration from backups. This incident highlights critical VPN patching and incident containment practices aligned with the NIST Incident Response Lifecycle phases.

---

## Journal Entry 2: Microsoft "Midnight Blizzard" Email Breach  
**Date:** Detected January 12, 2024 (initial intrusion November 2023)  
**Entry:** 2  
**Description:**  
Microsoft disclosed a breach by the Nobelium (APT29) group that compromised internal corporate email accounts through password-spray attacks. The attackers accessed emails of senior leadership and cybersecurity teams, aiming for espionage. The breach was identified by Microsoft's security team who promptly locked affected accounts and enforced multi-factor authentication. No customer systems were impacted.  
**Tool(s) Used:** Security Information and Event Management (SIEM), Multi-Factor Authentication (MFA), forensic analysis tools  
**The 5 W's:**  
- **Who:** Nobelium (APT29) Russian state-sponsored hackers  
- **What:** Email account compromise via password spraying  
- **When:** Initial intrusion Nov 2023; detected Jan 12, 2024  
- **Where:** Microsoft corporate email environment  
- **Why:** Espionage and information gathering  
**Additional Notes:**  
The incident emphasized strict password policies and MFA adoption. It involved identification, containment, eradication, and recovery phases of the NIST framework.

---

## Journal Entry 3: CDK Global Auto Dealer Ransomware Attack  
**Date:** June 18, 2024  
**Entry:** 3  
**Description:**  
CDK Global, a software provider for 15,000+ North American auto dealerships, experienced a ransomware attack by the BlackSuit group that forced dealerships to revert to manual processes. The attack resulted in service outages and a phased recovery beginning four days after detection. Restoration from backups was prioritized, and a possible ransom payment was reported.  
**Tool(s) Used:** SIEM, backup and restore tools, incident response playbooks  
**The 5 W's:**  
- **Who:** BlackSuit ransomware group (suspected)  
- **What:** Ransomware encryption causing system outages  
- **When:** June 18, 2024  
- **Where:** CDK Global dealer management systems, North America  
- **Why:** Financial extortion via ransomware  
**Additional Notes:**  
This event highlighted the need for tested backups, network segmentation, and incident playbooks to reduce downtime.

---

## Journal Entry 4: Ascension Health Black Basta Ransomware Attack  
**Date:** May 8, 2024  
**Entry:** 4  
**Description:**  
Ascension Health, a major U.S. hospital system, suffered a Black Basta ransomware attack impacting electronic health records across multiple states. The attack was initiated via a malicious email attachment. Immediate network isolation and collaboration with federal agencies led to eventual restoration after six weeks. Patient care workflows were disrupted, showcasing the critical need for healthcare cyber resilience.  
**Tool(s) Used:** Endpoint Detection and Response (EDR), Security Information and Event Management (SIEM), forensic tools, backup recovery  
**The 5 W's:**  
- **Who:** Black Basta ransomware group  
- **What:** Ransomware encryption of EHR servers  
- **When:** May 8, 2024  
- **Where:** Ascension Health hospital network, U.S.  
- **Why:** Ransom/Extortion via malicious email  
**Additional Notes:**  
Recovery involved coordination with FBI/CISA, restoring systems from backups, and enhanced email filtering policies. The incident highlights critical NIST phases: containment, eradication, and recovery.

---

## Reflections/Notes  
- Some activities like incident investigation and tool usage analysis were challenging due to the complexity of real-world attack vectors and response tactics.  
- My understanding of incident detection and response has deepened, especially in recognizing the importance of layered defenses like MFA, patching, and backup strategies.  
- I particularly enjoyed learning about SIEM and forensic tools as they provide vital insights for threat detection and incident remediation.

---

### References  
- [Tietoevry Ransomware Incident - Finnish NCSC Report](https://www.ncsc.fi/en/news/akiran-ransomware-attack-tietoevry)  
- [Microsoft Nobelium Breach Report - Microsoft Security Blog](https://www.microsoft.com/security/blog/2024/01/12/nobelium-midnight-blizzard-email-breach)  
- [CDK Global Ransomware Attack - Cybersecurity News](https://cybersecuritynews.com/cdk-global-ransomware-attack-june-2024)  
- [Ascension Health Ransomware Incident - Health Sector Cybersecurity](https://healthsectornews.com/ascension-health-black-basta-attack-2024)  
