# Phishing Attack Response Playbook

> **Purpose:** This playbook provides step-by-step procedures for responding to phishing attacks in alignment with ISO 27001:2022 information security incident management requirements.

> **Scope:** Applicable to all employees and security personnel responding to suspected or confirmed phishing incidents.

---

## ISO 27001 Alignment
This playbook supports ISO 27001:2022 Control A.5.24 
(Information security incident management planning and preparation)

## When to Use This Playbook
A user reports a suspicious email, or email security tools 
flag a potential phishing attempt.

## Response Steps

### 1. INITIAL ASSESSMENT (5 minutes)
□ Ask user: Did you click any links or download attachments?
□ Examine the email for red flags (sender, urgency, requests)
□ Determine severity (see severity table below)

### 2. CONTAINMENT (Immediate)
□ Tell user: "Do not interact with this email further"
□ If they clicked/downloaded: Disconnect their device from network
□ Block the sender email address in email gateway
□ Search for same email in other mailboxes, delete all copies

### 3. INVESTIGATION (Within 1 hour)
□ Check if credentials were entered (review login attempts)
□ Scan affected device for malware if attachment opened
□ Identify how many users received the email

### 4. REMEDIATION (Within 4 hours)
□ Reset passwords if credentials compromised
□ Remove any malware found
□ Update email filtering rules to catch similar attempts

### 5. RECOVERY
□ Re-enable user's account after verification
□ Monitor account for unusual activity (24 hours)
□ Brief user on what happened and how to spot phishing

### 6. DOCUMENTATION (Within 24 hours)
□ Record incident details, timeline, actions taken
□ Calculate response metrics (time to detect, contain, recover)
□ Update threat intelligence database

### 7. REVIEW (Within 1 week)
□ Team meeting: What worked? What didn't?
□ Update this playbook if gaps found
□ Conduct additional security awareness training if needed

## Severity Classification
**High:** Credentials entered, malware executed, executive targeted
→ Response time: < 15 minutes

**Medium:** Link clicked, attachment downloaded
→ Response time: < 1 hour

**Low:** Email reported, no interaction
→ Response time: < 4 hours

## Tools Needed
- Email security gateway admin access
- Antivirus/EDR console
- User account management system
- Incident ticketing system

## Contacts
- Security Team: security@company.com
- IT Support: itsupport@company.com
- Management escalation: CISO/Security Manager (for high-severity incidents)

## References
- ISO/IEC 27001:2022 - Information Security Management
- NIST SP 800-61 Rev 2 - Computer Security Incident Handling Guide

## Usage Notes

**Customization Required:**
Organizations implementing this playbook should:
- Replace placeholder contacts with actual personnel
- Update tool names to match deployed security stack
- Adjust severity thresholds based on risk appetite
- Align response times with SLA commitments

## Disclaimer
This is a template playbook. Organizations should customize this based on their specific tools, team structure, and risk profile.

---
Version 1.0 | Last Updated: November 14, 2024
Author: Vishal Panda
Aligned with ISO 27001:2022 Controls A.5.24, A.5.26
