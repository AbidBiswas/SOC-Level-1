
# SOC Level 1 – Security Analyst Notes

Junior Security Analyst | SOC Fundamentals

---

## 1. SOC L1 Responsibilities

![Q1](https://img.shields.io/badge/Q1-red?style=flat-square) **What is the role of a SOC Level 1 Analyst?**

A SOC Level 1 Analyst is the first line of defence in a Security Operations Centre.

**Main responsibilities:**
- Monitor security alerts using SIEM and EDR.
- Triage and investigate suspicious activities.
- Identify true positives and false positives.
- Document investigation findings.
- Escalate serious or complex incidents to SOC L2.

---

## 2. Daily SOC Operations

![Q2](https://img.shields.io/badge/Q2-red?style=flat-square) **What are the daily responsibilities of a SOC L1 Analyst?**

An L1 analyst monitors security alerts, investigates suspicious activities and follows established security procedures.

**Daily workflow:**

Monitor → Triage → Investigate → Document → Escalate or Close

---

## 3. Security Alert Classification

![Q3](https://img.shields.io/badge/Q3-red?style=flat-square) **What is the difference between a true positive and a false positive?**

- **True Positive:** A genuine threat is correctly detected.
- **False Positive:** Legitimate activity incorrectly triggers a security alert.
- **False Negative:** A genuine threat is not detected.
- **True Negative:** Legitimate activity correctly generates no malicious alert.

**Example:** An EDR correctly detecting ransomware is a true positive.

---

## 4. Alert Investigation

![Q4](https://img.shields.io/badge/Q4-red?style=flat-square) **How do you investigate a security alert?**

1. Review the alert name, severity and timestamp.
2. Identify the affected user, IP address or hostname.
3. Analyse relevant SIEM and EDR logs.
4. Check related events and verify suspicious activity.
5. Document findings and escalate if necessary.

**Example:** For multiple failed login attempts, examine the source IP, affected account and any subsequent successful logins.

---

## 5. SOC Monitoring Tools

![Q5](https://img.shields.io/badge/Q5-red?style=flat-square) **What tools does a SOC Analyst use?**

**SIEM**
- Microsoft Sentinel
- Splunk
- Collects and analyses security logs.

**EDR**
- Microsoft Defender for Endpoint
- CrowdStrike Falcon
- Monitors and investigates endpoint activity.

**Threat Intelligence**
- VirusTotal
- AbuseIPDB
- Helps investigate suspicious IPs, domains and file hashes.

---

## 6. SOC Teamwork

![Q6](https://img.shields.io/badge/Q6-red?style=flat-square) **Why is teamwork important in a SOC?**

SOC analysts cooperate with other security and IT teams to investigate threats and coordinate incident response.

- **SOC L2:** Handles complex investigations.
- **IT Team:** Supports technical remediation.
- **Threat Hunting:** Proactively searches for hidden threats.
- **Incident Response:** Coordinates containment and recovery.

---

## 7. Continuous Learning

![Q7](https://img.shields.io/badge/Q7-red?style=flat-square) **Why should SOC analysts continuously learn about new threats?**

Cyber threats constantly evolve. SOC analysts must improve their knowledge to recognise emerging attacks.

**Important learning areas:**
- Malware and phishing
- Emerging attack techniques
- Threat intelligence
- SIEM queries and EDR investigations
- Network and endpoint security

---

## 8. SOC Workshops

![Q8](https://img.shields.io/badge/Q8-red?style=flat-square) **What is the purpose of SOC brainstorming sessions and workshops?**

SOC workshops help analysts share knowledge, discuss threats and improve investigation skills.

**Common activities:**
- Review previous incidents.
- Discuss emerging threats.
- Improve detection rules.
- Share investigation techniques.
- Practise incident response through tabletop exercises.

---

## Quick Reference

| Term | Meaning |
|---|---|
| SOC L1 | Monitor, triage, investigate and escalate |
| SIEM | Collect and analyse security logs |
| EDR | Monitor and investigate endpoint activity |
| True Positive | A genuine threat is correctly detected |
| False Positive | Legitimate activity incorrectly triggers an alert |
| Escalation | Transfer an incident to the appropriate team |
| Playbook | Documented investigation and response steps |

**SOC Workflow:** Detect → Investigate → Document → Escalate
