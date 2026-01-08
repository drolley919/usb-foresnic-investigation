# Forensic Analysis

## Analysis Overview
The forensic analysis focused on identifying potentially malicious artifacts present on the USB device, validating file authenticity, reconstructing user activity through metadata and timestamps, and correlating findings with available threat intelligence. All analysis was conducted using forensically sound methods to preserve evidence integrity.

## File System and Signature Analysis
The mounted forensic image was examined to enumerate files present on the USB device. File signature analysis was performed to compare file headers against their extensions in order to identify discrepancies indicative of file masquerading or obfuscation. Several files were identified with mismatched extensions, prompting further examination.

## Executable File Examination
Executable files identified during enumeration were isolated for closer review. File properties, including size, structure, and headers, were analyzed to assess legitimacy. Hash values were generated for identified executables and prepared for correlation against threat intelligence sources.

## Threat Intelligence Correlation
Hashes of suspicious executable files were compared against indicators provided in a recent threat intelligence report. This process identified matches between files recovered from the USB device and known malicious signatures, increasing confidence that the artifacts posed a security risk.

## Timestamp and Metadata Analysis
File metadata was analyzed to reconstruct activity related to file creation, modification, and access. Timestamp analysis indicated that multiple files were introduced within a narrow timeframe consistent with reported suspicious activity. Metadata and security identifier information was used to assess likely user attribution.

## Validation and Integrity Checks
Hash verification was conducted at multiple stages throughout the investigation to ensure that evidence integrity was maintained. Final hash values matched initial acquisition values, confirming that no alterations occurred during analysis.
