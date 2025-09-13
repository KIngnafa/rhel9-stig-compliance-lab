# RHEL9-STIG-compliance-lab
🔸 Project Overview

* This project demonstrates end-to-end DISA STIG compliance for a RHEL9 EC2 instance in AWS. It includes baseline scanning, automated hardening with Ansible, post-hardening validation with OpenSCAP, continuous monitoring with AIDE, and documentation of residual findings in a POA&M.

🔸 Tools & Frameworks

OpenSCAP – scanning/assessment

Ansible STIG Role – automated remediation

AIDE – file integrity monitoring (SI-7)

scap-security-guide – DISA STIG checklists

POA&M tracking – compliance documentation

🔸 Workflow

Baseline Scan – captured baseline-report.html and compliance breakdown (~50–60% pass).

Hardening with Ansible – applied STIG role.

Post-Hardening Scan – improved compliance (~82%).

Continuous Monitoring – installed/configured AIDE, scheduled daily checks.

POA&M – documented residual fails with remediation milestones.

🔸 Evidence (Screenshots / Reports)

Link to or embed:

Baseline and hardened reports (HTML or screenshots).

Scoreboard (grep -o "<result>.*</result>" results.xml | sort | uniq -c).

Mock POA&M table.

🔸 Key Takeaways

Automated compliance scanning & remediation.

Demonstrated the full RMF cycle: Scan → Remediate → Validate → Monitor → Document.

Learned how to handle residual findings with a POA&M.

This workflow mirrors what DoD/FedRAMP teams use in production.
