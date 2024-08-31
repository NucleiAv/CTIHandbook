# Application Security Threats and Attacks

1. **Supplier Risk Assessment**
   * **Definition**: Evaluating the risks associated with acquiring third-party software.
   * **Process**:
     * Identify potential impacts (financial, operational, strategic).
     * Assess the likelihood of disruption.
     * Evaluate the impact on business operations.
2. **Web Application Firewall (WAF)**
   * **Function**: Filters, monitors, and blocks HTTP traffic to/from a web application.
   * **Difference from Regular Firewall**: WAF focuses on specific web application content, while regular firewalls handle overall network traffic.
3. **Common Application Security Threats and Attacks**
   * **Input Validation**:
     * **Attacks**: Cross-site scripting (XSS), SQL injection, buffer overflow.
   * **Authentication**:
     * **Attacks**: Brute force attacks, credential theft, network eavesdropping.
   * **Authorization**:
     * **Attack**: Elevation of privilege.
4. **Configuration Management Threats**
   * **Common Attacks**: Unauthorized access to admin interfaces, configuration stores, clear text data, lack of accountability, over-privileged accounts.
5. **Exception Management Threat**
   * **Example**: Denial-of-service (DoS) attacks, which disrupt service availability.
6. **Auditing and Logging Threats**
   * **Common Issues**: User denies performing actions, lack of traceability, attackers covering their tracks.

#### OWASP Top 10 Application Security Risks

1. **Injection**
   * **Issue**: Untrusted data sent to an interpreter can execute unintended commands or access unauthorized data.
2. **Broken Authentication**
   * **Issue**: Flaws in authentication and session management can lead to compromised credentials and unauthorized user access.
3. **Sensitive Data Exposure**
   * **Issue**: Inadequate protection of sensitive data (e.g., financial, healthcare) can lead to theft or modification.
4. **XML External Entities (XXE)**
   * **Issue**: Poorly configured XML processors can lead to internal file disclosure, remote code execution, and denial-of-service attacks.
5. **Broken Access Control**
   * **Issue**: Improper enforcement of user access restrictions can lead to unauthorized data access or functionality.
6. **Security Misconfiguration**
   * **Issue**: Insecure default configurations, incomplete setups, or misconfigured settings can expose vulnerabilities.
7. **Cross-Site Scripting (XSS)**
   * **Issue**: Untrusted data included in webpages can lead to script execution in users' browsers, session hijacking, and defacement.
8. **Insecure Deserialization**
   * **Issue**: Flaws in deserialization can lead to remote code execution, replay attacks, or privilege escalation.
9. **Using Components with Known Vulnerabilities**
   * **Issue**: Components with known vulnerabilities can lead to data loss or server takeover.
10. **Insufficient Logging and Monitoring**
    * **Issue**: Inadequate logging and ineffective incident response can delay breach detection and enable further attacks.
