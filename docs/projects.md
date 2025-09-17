# Projects/ Assesments 

**1. Manual Pentesting**

<img width="300" height="150" alt="Vulnerability Chart" align="right" width="400" src="https://github.com/user-attachments/assets/31d23919-8840-44c8-8a5b-5d75a310512d" /> As part of my MSc Cybersecurity portfolio at Roehampton University, I carried out a **manual penetration test** on the *“Maisie: The Cat”* PHP/MySQL web application.
This application, designed to let users interact with Maisie the cat, send fan messages, and explore related content, provided an ideal environment to simulate **real-world attack scenarios**.  

The assessment was conducted using **Burp Suite** and **cURL**, with a strict **manual-only approach** (no automated vulnerability scanners) to ensure accuracy and hands-on analysis. The testing process was guided by the **OWASP Top 10** framework, and each vulnerability discovered was carefully evaluated and classified according to the **CVSS v3.1 severity scoring system**, ensuring industry-standard reporting of risk levels.

[Read More...](projectlist/pentest.md) 


**2. Cyber Risk Assessment**

<img width="300" height="200" alt="cyber-risk-management-diagram" align="right" width="400" src="https://github.com/user-attachments/assets/3376891f-9df8-4c3e-af45-fc837232dde4" /> During my MSc Cybersecurity journey at Roehampton University, I have worked on **real-world projects** addressing challenges in **data privacy, regulatory compliance, cyber risk management, and threat mitigation**. 

These projects combined technical depth with governance frameworks, delivering solutions that resonate with both technical and business stakeholders.  

**GDPR & Data Governance (Post-Brexit):** Assessed non-compliance risks and proposed frameworks using **ISO 27001** and **COBIT**, emphasizing robust data retention policies to prevent regulatory penalties.
**Phishing & Identity Security:** Explored phishing detection strategies through the **NIST Cybersecurity Framework (CSF)**, with a strong focus on **Multi-Factor Authentication (MFA)** and its impact on reducing account compromise.
**Insider Threat Mitigation:** Investigated high-profile cases (e.g., Tesla, Capital One) and built actionable models leveraging **RBAC, monitoring, and auditing** to minimize misuse of privileged access.  
**CRM & Global Data Breaches:** Identified risks from poor encryption, misconfigured APIs, and weak streaming app integrations, recommending **secure API configurations, end-to-end encryption, and GDPR-aligned controls**. 

[Read More...](projectlist/crm.md)


**3. Capture the Flag (CTF) – OverTheWire: Bandit Challenge** 

<img width="300" height="150" alt="Over The Wire" align="right" width="400" src="https://github.com/user-attachments/assets/c294d6a4-df25-4186-bb11-091be97a899c" />
To strengthen my practical cybersecurity skills, I participated in the **OverTheWire: Bandit CTF challenge** and successfully solved **22 levels**. This hands-on experience provided a deeper understanding of **Linux fundamentals, privilege escalation, file system navigation, and secure authentication practices**.  

Each level required creative problem-solving — from decoding hidden files and bypassing permissions to leveraging secure shell (SSH) for remote access. By progressing through increasingly complex challenges, I gained the ability to think like an attacker while sharpening my defensive mindset.  

This experience not only enhanced my **Linux proficiency** but also honed critical skills in **problem-solving, persistence, and real-world system exploitation techniques**. It demonstrated how small oversights in system configuration can be exploited, reinforcing the importance of strong security practices in everyday IT operations.  

[Read More...](projectlist/ctf.md)


**4. Digital Forensics**

<img width="300" height="150" alt="Forensics" align="right" width="400" src="https://github.com/user-attachments/assets/71b1ff83-4d34-425b-9137-b2f731b8ea8f" />
This assessment examines a suspected insider threat on a Windows 10 VM by analysing a virtual disk (**win10_Portfolio-disk.vhd**) and a memory image (**win10-memory.raw**).  
The objectives were to surface indicators of compromise, reconstruct user actions, assess scope/severity, and present repeatable, admissible findings.  
Acquisition and handling followed **ACPO** best practice with pre/post **hash** verification and a documented **chain of custody**.  
Methods blended volatile-memory triage, registry and filesystem artefact parsing, and multi-source timeline correlation to cross-validate events.  
**Volatility** was used to enumerate processes/DLLs, inspect network artefacts, and build **pslist/psscan/timeliner** views with SID ownership checks.  
**Autopsy** supported registry hive analysis (NTUSER, SAM, SYSTEM, USRCLASS), filesystem traversal, and extraction of user activity traces.  
**Eric Zimmerman’s tools** parsed **Amcache/Prefetch/ShellBags**, produced concise timelines, and validated persistence/execution points.  
Supporting utilities included **WSL (Ubuntu)** for scripting, **Rapid Table** for hex/decimal checks, **Filetime Convertor** for timestamp normalisation, and hashing utilities for integrity.  

[Read More...](projectlist/forensics.md)

