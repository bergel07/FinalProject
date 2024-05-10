# Ethical Hacking Technical Report
**Client:** [TeckMart]  
**Date:** [10-05-2024]  
**Prepared by:** [April Lyn Monte] and [Bergel Lumapag]  

## Executive Summary
The technical results of the TechMart ethical hacking assessment are presented in this paper. The evaluation's goal was to find weaknesses in the company's systems, apps, and network infrastructure. Critical and high-risk flaws were found using a variety of testing approaches, such as vulnerability scanning and penetration testing. Together with practical suggestions for correction, this study offers thorough explanations of these findings.

## Vulnerability Summary
1. **Network Infrastructure:**
   - **Critical:** Remote Code Execution vulnerability (CVE-2024-5678) in the Nginx web server (version 1.18.0) running on TechMart's main server, allowing an attacker to execute arbitrary code remotely.
   - **High:** Default credentials used for remote administration tools (e.g., SSH) on TechMart's internal network.
2. **Web Applications:**
   - **Critical:** SQL Injection vulnerability in the search functionality of TechMart's website, potentially allowing attackers to extract sensitive data from the database.
   - **High:** Cross-Site Scripting (XSS) vulnerability in the product review section of TechMart's website, enabling attackers to execute malicious scripts in users' browsers.
3. **Operating Systems:**
   - **Critical:** Outdated and unpatched operating systems (Linux kernel version 3.2) on TechMart's web servers, exposing them to known exploits and malware.
   - **High:** Weak password policies on user accounts, increasing the risk of unauthorized access to critical systems.
4. **Wireless Networks:**
   - **Critical:** Use of outdated and vulnerable encryption protocols (WEP) in TechMart's guest Wi-Fi network, allowing attackers to intercept and decrypt wireless traffic.
5. **Social Engineering:**
   - **High:** Lack of regular security awareness training for employees, leading to a higher likelihood of falling for social engineering tactics.

## Recommendations
1. **Network Infrastructure:**
- Apply the most recent Nginx patch right away to address the Remote Code Execution vulnerability.
- Use strong, one-of-a-kind passwords and alter the remote administration tools' default credentials.
- Segment the network according to user roles and responsibilities to limit access to sensitive systems.
2. **Web Applications:**
- To stop SQL Injection attacks, perform a thorough code review and use parameterized queries.
- To reduce the risk of cross-site scripting attacks, strictly enforce input validation and output encoding.
- Patch known vulnerabilities in web application frameworks and libraries on a regular basis.
3. **Operating Systems:**
- Create a patch management procedure to guarantee that operating systems and software components are updated on time.
Enforce strict guidelines for password complexity and, when practical, use multi-factor authentication.
- Use file integrity monitoring tools to find instances when important system files have been altered without authorization.
4. **Wireless Networks:**
To improve wireless communications security, update your wireless network encryption to WPA2 or WPA3.
- Put in place mutual authentication and robust encryption to ensure that POS devices and the central server can communicate.
5. **Social Engineering:**
- Provide staff with regular security awareness training to inform them about typical social engineering techniques and teach them how to spot and report suspicious activity.
- Clearly define policies and processes for managing private data and countering phishing scams.

## Conclusion
The results of the ethical hacking assessment point to a number of serious security flaws and vulnerabilities in TechMart's applications and infrastructure. TechMart can dramatically strengthen its security posture and lower the risk of cyberattacks and data breaches by putting the suggested repair measures into practice.

**Signature:** [April Lyn and Bergel Lumapag]
