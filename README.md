# 📌 RHEL9 STIG Compliance Lab

🔸 **Project Overview**  
This project demonstrates end-to-end DISA STIG compliance for a RHEL9 EC2 instance in AWS. It includes baseline scanning, automated hardening with Ansible, post-hardening validation with OpenSCAP, continuous monitoring with AIDE, and documentation of residual findings in a POA&M.

---

🔸 **Tools & Frameworks**
- **OpenSCAP** – scanning/assessment  
- **Ansible STIG Role** – automated remediation  
- **AIDE** – file integrity monitoring (SI-7)  
- **scap-security-guide** – DISA STIG checklists  
- **POA&M tracking** – compliance documentation  

---

🔸 **Workflow**
1. **Baseline Scan** – captured `baseline-report.html` and compliance breakdown (~50–60% pass).  
2. **Hardening with Ansible** – applied STIG role.  
3. **Post-Hardening Scan** – improved compliance (~82%).  
4. **Continuous Monitoring** – installed/configured AIDE, scheduled daily checks.  
5. **POA&M** – documented residual fails with remediation milestones.  

---

🔸 **Evidence (Screenshots / Reports)**
- [Baseline Scan Report](baseline-report.html)  
- [Post-Hardening Report](hardened-report.html)  
- [Scoreboard Output](docs/scoreboard.png)  
- [Mock POA&M Table](mock-poam.csv)  

---

🔸 **Key Takeaways**
- Automated compliance scanning & remediation.  
- Demonstrated the full RMF cycle: **Scan → Remediate → Validate → Monitor → Document**.  
- Learned how to handle residual findings with a POA&M.  
- This workflow mirrors what DoD/FedRAMP teams use in production.  

---

## 📜 Certifications
- **AWS Certified Solutions Architect – Associate** (2023)  
- **CompTIA Security+** (Earned 2022)  
- **CompTIA Cloud+** (Earned 2021)  
- **AWS Certified DevOps Engineer – Professional** (In Progress)  
- **Microsoft Azure Administrator Associate (Planned 2025)**  

---

## 📚 References & Documentation
- [DISA STIG for RHEL9](https://public.cyber.mil/stigs/)  
- [OpenSCAP Documentation](https://www.open-scap.org/getting-started/)  
- [Ansible Lockdown RHEL9-STIG Role](https://github.com/ansible-lockdown/RHEL9-STIG)  
- [Google Doc – Full Project Documentation](https://docs.google.com/document/d/your-doc-id/view)  

