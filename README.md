# Security Policy

## 1. Overview
This app (“the App”) is developed and maintained by an individual developer.  
The App provides Earned Value Management (EVM) visualization inside Jira.  
The App does not process or store customer data outside the Atlassian environment.

---

## 2. Data Access and Storage
- The App runs on **Atlassian Forge** and operates within Forge’s secure sandbox environment.  
- The App only reads Jira issue data required to calculate and display EVM metrics.  
- **No data is stored** on external servers.  
- **No data is transmitted** outside Atlassian’s infrastructure.  
- The App does not collect personal information.

---

## 3. Data Transmission
All communication between the App and Atlassian APIs is performed securely over HTTPS, using Atlassian’s built-in communication channels.

---

## 4. Permissions
The App requests only the minimum permissions required to display EVM data:

- `read:jira-work`  
- `read:project:jira`

No administrative or unnecessary permissions are requested.

---

## 5. Security Practices
- The App runs in Atlassian Forge’s sandboxed runtime, ensuring isolated and secure code execution.  
- Dependencies are regularly reviewed and updated as needed.  
- Any reported security vulnerabilities will be addressed promptly.

---

## 6. Vulnerability Reporting
If you discover a security issue, please contact:

info.app.helpdesk@gmail.com

Reports will be acknowledged within **5 business days**, and updates will be provided until the issue is resolved.

---

## 7. Compliance
The App complies with Atlassian Marketplace security requirements and Forge security guidelines.  
The App does not store customer data externally and relies on Atlassian's secure execution environment.

