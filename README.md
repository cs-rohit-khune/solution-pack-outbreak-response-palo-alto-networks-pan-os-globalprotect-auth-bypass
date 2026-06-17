# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

Attackers are actively exploiting a PAN-OS GlobalProtect authentication bypass vulnerability to gain unauthorized VPN access to exposed Palo Alto Networks firewalls. An attacker who successfully exploits CVE-2026-0257 can:

- Establish unauthorized VPN sessions through affected GlobalProtect gateways.
- Bypass authentication controls without valid user credentials.
- Gain network-level access typically reserved for authenticated VPN users.
- Potentially facilitate further reconnaissance, lateral movement, or follow-on attacks within the victim environment. 

 The **Outbreak Response - Palo Alto Networks PAN-OS GlobalProtect Auth Bypass** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.3.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/pan-os-globalprotect-auth-bypass) contains information about the outbreak alert **Outbreak Response - Palo Alto Networks PAN-OS GlobalProtect Auth Bypass**. 

## Background: 

CVE-2026-0257 is a high-severity authentication bypass vulnerability affecting the GlobalProtect portal and gateway components of Palo Alto Networks PAN-OS and certain Prisma Access deployments. Successful exploitation allows an unauthenticated remote attacker to bypass security controls and establish unauthorized VPN connections without valid credentials. Palo Alto Networks, Unit 42, Rapid7, and other security researchers have confirmed active exploitation in the wild, prompting inclusion in CISA's Known Exploited Vulnerabilities (KEV) catalog.

The vulnerability impacts deployments that use GlobalProtect authentication override cookies in combination with specific certificate configurations. Threat actors can forge or manipulate authentication cookies to circumvent normal authentication requirements and gain network access. 

## Announced: 

 

## Latest Developments: 



June 9, 2026: Ongoing exploitation activity continues targeting exposed GlobalProtect services.
https://unit42.paloaltonetworks.com/active-exploitation-of-pan-os-cve-2026-0257

May 29, 2026: Added to CISA Known Exploited Vulnerabilities (KEV) catalog.

May 17, 2026: Earliest exploitation activity observed by Rapid7 MDR.

May 13, 2026: Palo Alto Networks publishes advisory and CVE-2026-0257 is disclosed.

 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|
