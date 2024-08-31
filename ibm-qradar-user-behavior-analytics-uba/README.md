# IBM QRadar User Behavior Analytics (UBA)

#### Overview:

* **UBA vs. UEBA**: UBA stands for User Behavior Analytics, while UEBA includes "Entity," referring to non-user entities like machines or accounts. Both terms refer to monitoring and analyzing behavior for security purposes.
* **SIEM Integration**: UBA is integrated with Security Information and Event Management (SIEM) systems, particularly IBM QRadar. It evaluates risks by analyzing user behavior across various data sources.

#### Data Sources:

* **Threat Intelligence**: Utilizes sources like IBM's X-Force for threat intelligence.
* **Network Infrastructure**: Monitors firewalls, switches, routers, etc.
* **Cloud Systems**: Analyzes systems and applications in the cloud.
* **Identity & Access Management**: Tracks privileged account access and login activities.
* **Data**: Focuses on protecting sensitive data, including customer information.
* **Applications & Mobile Devices**: Monitors both enterprise and homegrown applications, especially in remote work scenarios.
* **Endpoints**: The actual devices used to access corporate resources.

<figure><img src="../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>

#### Advantages of Integrated UBA:

* **Visibility**: Provides comprehensive visibility across endpoints, networks, and cloud infrastructure.
* **Network Data Reliability**: Network data is crucial as it remains unaffected by actions like disabling logging.
* **Faster Insights**: UBA offers faster detection and response, freeing up resources for other tasks.
* **AI Integration**: Leverages AI through QRadar Advisor for enhanced analysis.
* **Compatibility**: Integrates with third-party analytics models and existing insider threat use cases.

#### Use Cases:

* **Compromised Credentials**: Detects stolen or compromised credentials using behavioral analysis.
* **Insider Threats**: Monitors activities like abnormal login times, file access, and potential escalation of privileges.
* **Malware Takeover**: Detects malware activities and accounts compromised by malware.

#### Example Rules:

* QRadar UBA includes over 160 rules and machine learning models, mapped to the MITRE ATT\&CK framework. It covers vectors like phishing, data exfiltration, and command and control communications.

<figure><img src="../.gitbook/assets/image (75).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (76).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (77).png" alt=""><figcaption></figcaption></figure>

#### Implementation and Maturity:

* **SIEM Configuration**: Successful UBA deployment requires a well-configured SIEM, with properly parsed log sources, LDAP setup, and user ID coalescing.
* **Tuning**: Continuous tuning is necessary to avoid false positives and align with business needs.
* **Maturity Curve**: Organizations need a mature security setup to fully leverage UBA.

<figure><img src="../.gitbook/assets/image (78).png" alt=""><figcaption></figcaption></figure>

#### Outcomes and Benefits:

* **Account Anomalies & Access Deviations**: Detects deviations in user behavior, such as unexpected data downloads or abnormal access times.
* **Behavior Comparison**: Compares individual behavior to peer groups to identify anomalies.
* **Positive ROI**: UBA enhances SOC efficiency, reduces detection time, and provides a good return on investment.
* **Quick Deployment**: QRadar UBA is easy to deploy and configure, with a short time to value.

<figure><img src="../.gitbook/assets/image (79).png" alt=""><figcaption></figcaption></figure>

#### Deployment:

* **Easy Integration**: Available as a free add-on for QRadar users, UBA can be downloaded from the IBM App Exchange, installed, and quickly configured for use.
