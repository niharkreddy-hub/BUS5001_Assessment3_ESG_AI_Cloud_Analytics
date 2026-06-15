# Q2 Cloud Security Incident: Snowflake Customer Data Breach Campaign

## Incident Selected
The selected case is the 2024 Snowflake customer data breach campaign.

## What Happened
In 2024, a financially motivated threat actor gained unauthorised access to multiple Snowflake customer environments using stolen credentials. The attackers accessed customer Snowflake instances and exfiltrated data from cloud-hosted data warehouses.

## Who Was Affected
Mandiant and Snowflake reportedly notified approximately 165 potentially exposed customer organisations. Publicly reported affected organisations included Ticketmaster, Santander, LendingTree/QuoteWizard and other Snowflake customers.

## Data or Systems Compromised
The compromised systems were customer-managed Snowflake environments containing cloud-hosted business and customer data. The exact data varied by organisation but included sensitive customer and operational records.

## Root Cause
The root cause was not a direct compromise of Snowflake's core cloud infrastructure. The incident was mainly linked to:
- Stolen employee credentials
- Infostealer malware
- Snowflake accounts without multi-factor authentication
- Weak identity monitoring and access governance

## Cloud Model
This was primarily a Software-as-a-Service (SaaS) incident because Snowflake provides a cloud-hosted data platform. However, customers remain responsible for identity governance, MFA enforcement, role-based access, monitoring and protection of their data.
