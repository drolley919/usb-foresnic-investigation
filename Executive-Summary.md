# Executive Summary

## Case Overview
This project documents a digital forensic investigation involving a USB flash drive recovered from a corporate environment following reports of suspicious activity within the Sales and Marketing department. The objective of the investigation was to determine whether the device contained malicious content, validate the integrity of the evidence, and assess potential user attribution and organizational risk.

## Scope of Investigation
The investigation included forensic acquisition and analysis of a USB device image, identification and examination of executable files, cryptographic hash validation, correlation with threat intelligence sources, and review of file system metadata and timestamps. Additional analysis focused on reconstructing activity timelines and assessing potential linkage to a specific user account.

## High-Level Findings
Analysis identified multiple executable files exhibiting characteristics consistent with malicious behavior. Several cryptographic hashes matched known malicious indicators documented in recent threat intelligence reporting. Timestamp analysis indicated the files were introduced within a narrow timeframe consistent with the reported incident window. Security identifier (SID) and metadata correlation linked the USB device to an employee account within the Sales and Marketing department.

## Risk and Impact
The presence of malicious executables on removable media represented a credible risk of malware introduction, endpoint compromise, and potential lateral movement within the corporate environment. Uncontrolled use of external storage devices increased exposure to unauthorized code execution and data exfiltration if adequate controls were not enforced.

## Recommended Actions
Based on the investigation results, recommended actions included restricting and monitoring removable media usage, enhancing endpoint detection and logging capabilities, strengthening file execution and attachment security controls, and reinforcing user security awareness training. Additional review of affected endpoints and related systems was advised to assess the full scope of potential exposure.
