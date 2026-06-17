| [Home](../README.md) |
 | -------------------------------------------- |

# Contents

The **Outbreak Response - Palo Alto Networks PAN-OS GlobalProtect Auth Bypass** solution pack contains the following resources.

## Outbreak Alerts Record Set

| Name | Description |
|:-------------------------|:------------------|
| Palo Alto Networks PAN-OS GlobalProtect Auth Bypass | Attackers are actively exploiting a PAN-OS GlobalProtect authentication bypass vulnerability to gain unauthorized VPN access to exposed Palo Alto Networks firewalls. An attacker who successfully exploits CVE-2026-0257 can:

- Establish unauthorized VPN sessions through affected GlobalProtect gateways.
- Bypass authentication controls without valid user credentials.
- Gain network-level access typically reserved for authenticated VPN users.
- Potentially facilitate further reconnaissance, lateral movement, or follow-on attacks within the victim environment. |

## Threat Hunt Rules Record set

| Name | Rule Type |
|:-------------------------|:------------------|
| FortiAnalyzer Threat Hunting - PAN-OS GlobalProtect Auth Bypass Event-Handler | Fortinet Fabric |


 <table><th>NOTE</th><td>These SIGMA and Yara rules are sourced from public community repositories are not independently verified or validated by Fortinet. While community-contributed rules can be valuable for timely threat detection, they may vary in quality, accuracy, and relevance. Fortinet is not responsible for any inaccuracies, errors, or omissions in these rules, nor for any damage or loss that may result from their application. We encourage users to conduct their own validation and adapt these rules as necessary to meet specific security needs and contexts</td></table> 

# Next Steps
| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
| ----------------------------------------- | ------------------------------------------- | --------------------- |