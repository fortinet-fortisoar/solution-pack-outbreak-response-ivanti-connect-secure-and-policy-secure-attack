# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 
 

# Overview 
Ivanti Connect Secure is a Secure Sockets Layer (SSL) Virtual Private Network (VPN) solution that allows remote and mobile users to securely access corporate resources from any web-enabled device, anytime and anywhere. Ivanti Connect Secure and Policy Secure Attack is the Widespread exploitation of two zero-day vulnerabilities affecting Ivanti Connect Secure (ICS) and Policy Secure gateways underway.

The **Outbreak Response - Ivanti Connect Secure and Policy Secure Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/1.0.0/README.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*, *QRadar*, *Splunk*, and *Azure Log Analytics*.

The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/ivanti-authentication-bypass) contains information about the outbreak alert **Outbreak Response - Ivanti Connect Secure and Policy Secure Attack**.

## Background
CVE-2023-46805 is a vulnerability found in the web component of Ivanti Connect Secure (9.x, 22.x) and Ivanti Policy Secure. This authentication bypass vulnerability allows a remote attacker to access restricted resources by bypassing control checks. CVE-2024-21887 is a command injection vulnerability in web components of Ivanti Connect Secure (9.x, 22.x) and Ivanti Policy Secure. If CVE-2024-21887 is used in conjunction with CVE-2023-46805, exploitation does not require authentication and enables a threat actor to craft malicious requests and execute arbitrary commands on the system.

## Announced:
Jan 10, 2024: Ivanti disclosed two new vulnerabilities in their Ivanti Connect Secure (ICS) and Ivanti Policy Secure gateways: CVE-2023-46805 and CVE-2024-21887.
https://forums.ivanti.com/s/article/KB-CVE-2023-46805-Authentication-Bypass-CVE-2024-21887-Command-Injection-for-Ivanti-Connect-Secure-and-Ivanti-Policy-Secure-Gateways?language=en_US

Jan 18, 2024: FortiGuard Labs released a Threat Signal on Ivanti Connect Secure and Policy Secure Gateways Zero-day Vulnerabilities (CVE-2023-46805 and CVE-2024-21887).
https://www.fortiguard.com/threat-signal-report/5371/


## Latest Developments:
Jan 19, 2024: CISA Issues Emergency Directive to Federal Agencies on Ivanti Zero-Day Exploits. This Directive requires agencies to implement Ivantiâ€™s published mitigation immediately to the affected products in order to prevent future exploitation. https://www.cisa.gov/news-events/directives/ed-24-01-mitigate-ivanti-connect-secure-and-ivanti-policy-secure-vulnerabilities . FortiGuard Labs has released an IPS signature to detect and block Authentication Bypass Attack (CVE-2023-46805) and is observing high IPS activity since the release of the signature.

Jan. 22, 2024: Ivanti plans to begin releasing patches addressing these vulnerabilities on a schedule. Until patches are available, Ivanti has provided a workaround for the users to mitigate exploitation risks https://forums.ivanti.com/s/article/KB-CVE-2023-46805-Authentication-Bypass-CVE-2024-21887-Command-Injection-for-Ivanti-Connect-Secure-and-Ivanti-Policy-Secure-Gateways

# Next Steps

| [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) |
|----------------------------------------------|------------------------------------------------|--------------------------|--------------------------------|