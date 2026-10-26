# SWYNEX Security Assessment Report

**Task:** 4 — Security Assessment Report  
**Assessment type:** Defensive cybersecurity  
**Environment:** Authorized lab environments

## 1. Executive Summary

This report documents cybersecurity lab exercises covering security fundamentals, network traffic analysis, and web application security testing. It summarizes the methodology, observed findings, potential risks, and remediation recommendations.

## 2. Scope

The assessment covers:

- Security fundamentals lab exercises.
- Network traffic analysis using Wireshark.
- Web application security review using OWASP ZAP against a local OWASP Juice Shop instance.

Testing was restricted to authorized lab environments.

## 3. Methodology

### 3.1 Security Fundamentals

Document the exercise performed, the actual result observed, and the supporting evidence from Task 1.

### 3.2 Network Security Analysis

Use Wireshark to examine the collected packet capture. Document the protocols and traffic patterns actually observed, together with relevant screenshots.

### 3.3 Web Security Review

Use OWASP ZAP scan evidence to document the actual alerts, affected URLs or components, severity, and supporting details from Task 3.

## 4. Security Findings

For each verified finding, record its title, evidence, potential impact, risk rating, and recommended remediation.

Do not describe a vulnerability as confirmed unless the collected evidence supports that conclusion.

## 5. Risk Assessment

Evaluate findings based on potential impact, exploitability, affected assets, and available evidence. Distinguish confirmed vulnerabilities from informational observations.

## 6. Remediation Recommendations

- Strengthen authentication and password-recovery controls where applicable.
- Investigate suspicious network traffic in context.
- Validate web application security alerts before prioritizing remediation.
- Apply security updates and secure configuration practices.
- Retest confirmed vulnerabilities after remediation.
- Remove credentials, tokens, and sensitive personal information from public evidence.

## 7. Limitations

This assessment is limited to the authorized lab environments and evidence collected. It does not establish the security status of systems that were not tested.

## 8. Conclusion

These exercises provided practical experience in security assessment, network traffic analysis, web application testing, and defensive remediation planning.

## 9. References

- OWASP Juice Shop: https://owasp.org/www-project-juice-shop/
- OWASP ZAP: https://www.zaproxy.org/
- Wireshark: https://www.wireshark.org/
- OWASP Web Security Testing Guide: https://owasp.org/www-project-web-security-testing-guide/
