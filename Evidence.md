# Evidence and Integrity Validation

## Evidence Description
The primary evidence examined in this investigation consisted of a forensic image of a USB flash drive recovered from a corporate environment near shared workspaces used by the Sales and Marketing department. The device was collected following reports of suspicious activity and potential unauthorized software usage.

## Evidence Inventory
| Evidence Item | Description |
|--------------|-------------|
| USB Flash Drive Image | Forensic image of removable storage device (E01 format) |

## Hash Verification
To ensure evidence integrity, cryptographic hash values were generated prior to analysis and verified upon completion.

### Screenshot: Image Hash Verification
![FTK Imager hash verification showing MD5 and SHA1 match](Assets/screenshots/hash-verification-ftk.png)

### Screenshot: Image Acquisition Summary
![FTK Imager image summary showing acquisition and verification details](Assets/screenshots/image-summary-acquisition-details.png)

| Artifact | MD5 | SHA-1 |
|--------|-----|-------|
| USB Image (Initial) | *documented* | *documented* |
| USB Image (Post-Analysis) | *matched* | *matched* |

Matching hash values confirmed that the evidence remained unchanged throughout the investigation.

## Acquisition Method
The USB device was forensically imaged using industry-standard tools in a controlled environment. Hashes were calculated at acquisition and re-verified after analysis to preserve forensic soundness and maintain evidence reliability.

## Chain of Custody
A documented chain of custody was maintained throughout the investigation. The device was transferred from initial collection through analysis following established evidence handling procedures to ensure accountability and integrity.

## Validation Summary
Evidence integrity was preserved throughout the investigation. All forensic actions were conducted using accepted digital forensics best practices, ensuring the reliability and admissibility of findings.
