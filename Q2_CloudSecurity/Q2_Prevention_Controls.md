# Q2 Prevention Controls

## 1. Mandatory Multi-Factor Authentication
All Snowflake accounts, especially privileged accounts, should enforce MFA. This would reduce the risk of stolen credentials being used successfully.

## 2. Conditional Access and Risk-Based Login Controls
Access should be restricted based on location, device trust, impossible travel detection and suspicious login behaviour.

## 3. Least Privilege IAM
Users should only have access to the minimum data and roles required for their job. Administrative privileges should be limited and reviewed regularly.

## 4. Credential Rotation and Secret Management
Organisations should rotate passwords, remove unused accounts and monitor for exposed credentials from infostealer malware or dark web leaks.

## 5. Security Monitoring and SIEM Integration
Snowflake logs should be integrated with SIEM tools such as Microsoft Sentinel, Splunk or Google Security Operations to detect unusual access and large data exports.

## 6. Data Loss Prevention and Exfiltration Alerts
Alerts should be configured for abnormal query volumes, mass downloads, unusual IP addresses and high-risk access patterns.

## 7. Cloud Security Governance
Organisations should maintain a cloud security governance framework that includes shared responsibility awareness, account hardening, incident response planning and periodic security audits.
