# Recommendations

Based on the findings of this investigation, the following actions are recommended to reduce the risk of similar incidents and improve the organization’s overall security posture.

## Removable Media Controls
- Restrict the use of removable storage devices through endpoint control policies.
- Implement monitoring and logging for USB device connections and file transfers.
- Require approval or justification for the use of external storage devices in corporate environments.

## Endpoint Detection and Monitoring
- Enhance endpoint detection and response (EDR) capabilities to identify unauthorized executable activity.
- Monitor process execution and file creation events associated with removable media usage.
- Conduct regular endpoint reviews for indicators of compromise.

## Email and Attachment Security
- Strengthen email filtering controls to block high-risk file attachments, including executable and script-based formats.
- Enforce attachment scanning and sandboxing to detect malicious payloads before delivery.
- Implement sender authentication mechanisms such as SPF, DKIM, and DMARC to reduce phishing risks.

## User Awareness and Access Controls
- Provide recurring security awareness training focused on phishing, removable media risks, and safe file handling.
- Enforce the principle of least privilege to limit the impact of compromised user accounts.
- Implement multi-factor authentication (MFA) to reduce the risk of credential misuse.

## Post-Incident Review
- Conduct a targeted review of systems associated with the identified user account to assess potential lateral movement.
- Review incident response procedures and update playbooks to address removable media-related threats.
- Document lessons learned to improve detection and response timelines in future incidents.
