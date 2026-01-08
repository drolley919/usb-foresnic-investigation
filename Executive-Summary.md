# Executive Summary

## Case Overview
This project documents a digital forensic investigation involving a USB flash drive recovered from a corporate environment following reports of suspicious activity within the Sales and Marketing department. The investigation was conducted to determine whether the device contained malicious content, validate the integrity of digital evidence, and identify potential user attribution.

## Scope of Investigation
The scope of this investigation included forensic acquisition and analysis of a USB device image, identification and examination of executable files, validation of file integrity using cryptographic hashing, correlation of findings with threat intelligence, and analysis of metadata and timestamps to reconstruct activity and determine likely ownership.

## High-Level Findings
Analysis revealed multiple executable files with characteristics consistent with malicious activity. Several file hashes matched known malicious indicators listed in a recent threat intelligence report. Timestamp analysis indicated the files were introduced within a short timeframe consistent with reported suspicious activity. Metadata and security identifier analysis linked the USB device to a specific employee account within the Sales and Marketing team.

## Risk and Impact
The presence of malicious executables on removable media posed a potential risk of malware introduction and data exfiltration within the corporate environment. Unauthorized use of external storage devices increased the likelihood of endpoint compromise and lateral movement if controls were insufficient.

## Recommended Actions
Based on the findings, recommendations included restricting and monitoring removable media usage, enhancing endpoint detection and logging, strengthening email and attachment security controls, and reinforcing user awareness training. Additional review of endpoint activity and associated systems was advised to assess the scope of potential exposure.
