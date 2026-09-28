# SOC Alert Investigation – 28 September 2026

## Overview

Today I practiced SOC alert triage and incident investigation using a security monitoring environment.

The exercise involved analyzing phishing and firewall alerts, classifying alerts as True Positive or False Positive, determining whether escalation was required, and documenting recommended remediation actions.

## Alerts Investigated

| Alert ID | Alert Rule | Severity | Type | Classification |
|---|---|---|---|---|
| 8814 | Inbound Email Containing Suspicious External Link | Medium | Phishing | True Positive |
| 8815 | Inbound Email Containing Suspicious External Link | Medium | Phishing | True Positive |
| 8816 | Access to Blacklisted External URL Blocked by Firewall | High | Firewall | True Positive |
| 8817 | Inbound Email Containing Suspicious External Link | Medium | Phishing | True Positive |
| 8818 | Inbound Email Containing Suspicious External Link | Medium | Phishing | True Positive |

## Alert 8818 Investigation

### Alert Details

- Alert ID: 8818
- Alert Type: Phishing
- Severity: Medium
- Detection: Inbound Email Containing Suspicious External Link
- Time: 28 September 2026 at 18:11
- Classification: False Positive
- Escalation: NO

### Investigation

The alert was triggered by an inbound email containing a suspicious external link.

The activity matched the phishing detection rule and was classified as a True Positive because it represented suspicious phishing-related activity.

### Potential Risks

The suspicious link could potentially lead to:

- Credential theft
- Credential harvesting
- Malware delivery
- Unauthorized account access
- Further compromise

### Recommended Remediation

1. Quarantine or remove the suspicious email.
2. Block the identified malicious URL or domain.
3. Investigate the affected mailbox/user.
4. Review authentication logs for suspicious activity.
5. Reset credentials if compromise is suspected.
6. Monitor for related phishing activity.

### Attack Indicators

- Alert ID: 8818
- Phishing alert
- Inbound email
- Suspicious external link
- Medium severity

## SOC Investigation Workflow

1. Review the alert.
2. Identify the alert type and severity.
3. Examine the triggering activity.
4. Determine whether the alert is a True Positive or False Positive.
5. Assess potential impact.
6. Determine whether escalation is required.
7. Recommend containment and remediation.
8. Document the investigation.

## Skills Practiced

- SOC alert triage
- Phishing detection
- True Positive / False Positive classification
- Alert severity analysis
- Incident escalation
- IOC identification
- Incident documentation
- Security remediation
- Firewall alert analysis

## Lessons Learned

Today's exercise helped me understand the workflow followed by a SOC analyst when investigating security alerts.

I practiced moving from alert detection to classification, escalation, remediation, and incident documentation.

This is part of my ongoing cybersecurity learning journey.
