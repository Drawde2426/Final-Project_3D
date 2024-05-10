# Ethical Hacking Technical Report

##### Client: XYZ Corporation

###### Date: May 10, 2024

###### Prepared by: Edward B. Sarte and Nikki Sasaluya
#### Executive Summary:
This report outlines the results of an ethical hacking assessment conducted for XYZ Corporation. Our assessment aimed to identify vulnerabilities within the organization's network infrastructure, applications, and systems. Through various testing methodologies such as penetration testing and vulnerability scanning, critical and high-risk issues were discovered. This report provides detailed descriptions of these findings and offers actionable recommendations for remediation.

### Vulnerability Summary:

#### Network Infrastructure:
**Critical:** Remote Code Execution vulnerability (CVE-XXXX-XXXX) in the Apache Struts framework (version X.X.X) running on XYZ's main server, allowing remote attackers to execute arbitrary code.
**High:** Misconfigured firewall rules permit unrestricted external access to sensitive internal services (e.g., SSH, RDP) on the main server.
#### Web Applications:
**Critical:** SQL Injection vulnerability in the login form of XYZ's customer portal, potentially enabling attackers to extract sensitive data from the database.
**High**: Cross-Site Scripting (XSS) vulnerability in XYZ's blog platform, enabling attackers to execute malicious scripts in users' browsers.
#### Operating Systems:
**Critical:** Outdated and unpatched Windows Server 2008 R2 on critical servers, exposing them to known exploits and malware.
**High:** Weak password policies on domain user accounts, facilitating brute-force attacks and unauthorized access.
#### Wireless Networks:
**Critical:** Weak encryption (WEP) used in wireless networks, allowing attackers to intercept and decrypt wireless traffic, exposing sensitive data.
Social Engineering:
**High:** Several employees fell victim to phishing emails, providing credentials and sensitive information.
## Recommendations:

#### Network Infrastructure:
Immediately patch Apache Struts to the latest version to mitigate the Remote Code Execution vulnerability.
Review and update firewall rules to restrict access based on the principle of least privilege.
#### Web Applications:
Conduct a thorough code review and implement input validation to prevent SQL Injection and XSS attacks.
Implement security headers (e.g., Content Security Policy) to mitigate XSS vulnerabilities.
#### Operating Systems:
Develop a patch management process to regularly update and secure operating systems against known vulnerabilities.
Enforce strong password policies and consider implementing multi-factor authentication for domain user accounts.
#### Wireless Networks:
Upgrade wireless network encryption to WPA2 or WPA3 to ensure confidentiality and integrity of wireless communications.
#### Social Engineering:
Conduct regular security awareness training for employees to educate them about the risks of phishing attacks and how to identify and report suspicious emails.
## Conclusion:
The ethical hacking assessment has uncovered critical vulnerabilities and security weaknesses within XYZ Corporation's infrastructure and applications. By implementing the recommended remediation measures, XYZ Corporation can significantly enhance its security posture and mitigate the risk of cyber threats and data breaches.

 **Signature:** Edward B. Sarte and Nikki Sasaluya
