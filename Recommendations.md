# Recommendations

Based on the findings of this investigation, the following recommendations are provided to reduce the risk of removable media–related incidents and strengthen the organization’s overall security posture. These actions align with best practices for endpoint security, incident response, and user risk reduction.

---

## Strengthen Removable Media Controls

Restrict and tightly control the use of removable storage devices within the corporate environment. Where business use is required, implement approval-based access and enforce logging of USB device connections and file transfer activity.

Monitoring removable media usage provides early visibility into potential policy violations and reduces the risk of unauthorized executable introduction.

---

## Enhance Endpoint Detection and Monitoring

Improve endpoint detection and response (EDR) capabilities to identify suspicious executable activity originating from removable media. Monitoring should prioritize:
- Execution of binaries from external storage
- File creation events associated with USB devices
- Abnormal process behavior linked to removable media usage

Regular endpoint review for indicators of compromise supports early detection and containment.

---

## Improve File Delivery and Attachment Security

Strengthen controls around file delivery mechanisms that commonly introduce malicious executables. This includes:
- Blocking or restricting high-risk attachment types
- Enforcing attachment scanning and sandboxing
- Maintaining strong sender authentication controls (SPF, DKIM, DMARC)

Reducing exposure at the delivery stage lowers the likelihood of malicious files reaching endpoints.

---

## Reinforce User Awareness and Access Controls

Provide recurring security awareness training focused on removable media risks, phishing techniques, and safe file handling practices. Reinforce the principle of least privilege to limit the impact of compromised accounts.

Implementing multi-factor authentication (MFA) further reduces the risk of credential misuse and unauthorized access.

---

## Conduct Post-Incident Review and Validation

Perform a targeted review of systems associated with the identified user account to assess potential lateral movement or secondary exposure. Incident response procedures and playbooks should be reviewed and updated to explicitly address removable media–related threats.

Documenting lessons learned from this investigation will improve detection efficiency and response timelines in future incidents.

---

## Conclusion

While this investigation identified malicious artifacts on removable media, proactive implementation of these recommendations will significantly reduce organizational exposure to similar threats. Strengthening controls around removable media usage, endpoint monitoring, and user behavior enhances overall security resilience and incident response readiness.
