# Certified Red Team Analyst (CRTA) Exam Review

<img width="1400" height="990" alt="CRTA" src="https://github.com/user-attachments/assets/14b5864e-fcb1-4048-b026-015119efe198" />


## Overview
On **23 November 2025**, I undertook the **Certified Red Team Analyst (CRTA)** exam provided by **CyberWarfare Labs (CWL)**. The exam is a **6-hour hands-on assessment**, designed to evaluate practical red teaming skills within a realistic **Active Directory (AD)** environment. I successfully completed the exam in **2.5 hours**, fully exploiting the lab environment and accomplishing all objectives.

This repository documents my preparation, workflow, and reflections, providing a detailed reference for aspiring red team professionals.

---

## Exam Structure

- **Total Duration:** 6 hours  
- **Personal Completion Time:** 2.5 hours  
- **Format:** Practical lab; no multiple-choice questions  
- **Focus Areas:** Active Directory enumeration, privilege escalation, lateral movement, and sensitive data access  

Candidates are required to:

- Enumerate users, groups, and permissions within an AD environment.
- Identify and exploit misconfigurations, ACLs, and replication permissions.
- Escalate privileges and move laterally through the network.
- Access sensitive files, such as `secret.xml`, representing critical assets.

---

## Key Insights

1. **Exam Strategy**
   - Success depends on **structured enumeration** and understanding AD relationships.
   - Usernames, group memberships, and object privileges often provide the necessary operational clues.
   - Automated tools are useful, but careful analysis of results is more valuable.

2. **Tools & Techniques**
   - **Enumeration:** `nmap`, `ldapsearch`, `crackmapexec`  
   - **Active Directory Analysis:** `BloodHound`, `Rubeus`, `Mimikatz`  
   - **Pivoting & Tunneling:** `ligolo-ng`, `proxychains`, `chisel`  
   - **Documentation:** Detailed screenshots and organized notes facilitated post-exam report submission

3. **Critical Exam Elements**
   - Exploitation of AD misconfigurations and ACLs.
   - Credential attacks, including DCSync and Pass-the-Hash techniques.
   - Lateral movement paths and privilege escalation to access sensitive files (`secret.xml`).

4. **Preparation Focus**
   - In-depth understanding of AD structure and logic.
   - Mastery of ACL abuse, replication attacks, and permission analysis.
   - Methodical approach to enumeration and attack path identification.

---

## Reflection & Takeaways

The CRTA exam rewards **methodical thinking and strategy**:

- **Enumeration discipline** is paramount; collecting accurate data drives successful exploitation.
- **AD comprehension** surpasses tool dependency—knowing how permissions and replication work is essential.
- **Documentation and reporting** are integral, ensuring clarity and reproducibility of findings.

Completing the exam in **less than half the allotted time** highlighted the value of preparation, precision, and strategic workflow.

---

## Recommendations for Aspiring CRTA Candidates

- Focus on **AD structure, ACLs, and replication permissions**.  
- Master attacks such as **DCSync**, **Pass-the-Hash**, and **lateral movement techniques**.  
- Automate judiciously; understanding the underlying logic is more important than relying solely on scripts.  
- Take detailed notes and screenshots—this streamlines report creation post-exam.  

---

**Achievement:** Successfully completed the **CRTA exam**, demonstrating practical proficiency in Active Directory red teaming and offensive security operations.
