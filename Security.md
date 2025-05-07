# Microsoft Security

## Defender
aka Microsoft 365 Defender
comprised of:
- Microsoft Defender for Endpoints
- Microsoft Defender for Office 365
- Microsoft Defender for Identity
- Microsoft Defender for Cloud Apps [managed in azure portal](https://portal.azure.com/#view/Microsoft_Azure_Security/SecurityMenuBlade/~/0)

Policies
- File
- Activity
- App Discovery
- Access
- Session
- OAuth App


## Sentinel
In its simplest form, a SIEM system allows you to:
- Collect and query logs.
  - Use Data Connectors to Azure Activity etc
- Do some form of correlation or anomaly detection.
- Create alerts and incidents based on your findings.
Functionality
- Log Management
- Alerting
- Visualisation
- Incident Management
- Query Data

Features
- Workbooks -> ie a dashboard
- Notebooks
- Watchlist
- Automation
  - Automation rule
  - Playbook with incident/alert/entity trigger
- Analytics -> create queries or incident creation rules. NRT & Schedule can see rule logic

![image](https://github.com/user-attachments/assets/f3fb8a40-88c9-465f-ace4-1c47cdc9454b)


## EntraID Protection
Risk Users, Risky sign-in, Risky Apps
Identity based risks. Can feed Conditional Access & SIEM

## Others
Additional integrations to:
- Microsoft Defender for Cloud
- Microsoft Information Protection
