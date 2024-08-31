# Critical Data Protection Capabilities

<figure><img src="../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

1. **Data Discovery**
   * **Purpose**: Identify all data sources within an organization.
   * **Process**: Discover databases and file systems containing sensitive or regulated data, including production, development, testing, and unauthorized sources.
   * **Outcome**: Creation of a data catalog or inventory.
   * **Methods**:
     * Consulting with business owners, DBAs, and network admins.
     * Employing tools to scan networks and servers.
2. **Data Classification**
   * **Purpose**: Determine the nature and sensitivity of discovered data.
   * **Process**: Parsing data and assigning labels or keywords based on type.
   * **Importance**: Helps in applying the correct security policies to different data types, considering standards, regulations, and organizational needs.
3. **Vulnerability Assessment**
   * **Purpose**: Identify vulnerabilities in hardware, software, and networks.
   * **Process**:
     * Consistent and automated assessment.
     * Compare system configuration against a recommended baseline.
   * **Focus Areas**: Disabled user accounts, inappropriate privileges, insecure authentication, shared accounts, misconfigurations, missing security patches.
   * **Approach**: Phased, prioritizing urgent risks and seeking constant improvement.
4. **Data Risk Analysis**
   * **Purpose**: Assign risk levels to data sources and prioritize efforts.
   * **Process**:
     * Analyze data type, threats, probability of threats, potential damage, mitigation methods, and costs.
   * **Outcome**:
     * Helps refine data discovery, classification, and vulnerability assessment.
     * Informs monitoring policies.
5. **Data and File Activity Monitoring**
   * **Purpose**: Detect suspicious activity and breaches promptly.
   * **Challenges**:
     * Monitoring billions of transactions.
     * Filtering to identify a few suspicious events.
   * **Business Perspective**: Use risk analysis to develop monitoring policies.
   * **Technical Perspective**:
     * Avoid overburdening resources (CPU, RAM, Disk, Network).
     * Address varied data access methods.
   * **Iterative Process**: Continuous feedback into vulnerability assessment and risk analysis.
6. **Real-Time Alerting**
   * **Purpose**: Respond quickly to suspicious activity.
   * **Process**:
     * Centralize and correlate relevant information.
     * Automate the alerting process, integrating with security intelligence and event management consoles.
   * **Importance**: Ensures timely and appropriate action on identified threats.

&#x20;**7. Blocking, Masking, and Quarantining**

* **Purpose**: Limits access to sensitive data by responding to suspicious actions.
* **Blocking**:
  * Prevents suspicious data requests from completing (e.g., viewing, changing, adding, or deleting data).
  * Request fails to complete, and no data is affected or returned.
* **Masking**:
  * Modifies how data is returned, showing only partial data (e.g., replacing digits with asterisks).
  * Useful when the requester needs limited access, like troubleshooting by a database admin.
* **Query Modification**:
  * Alters the actual command sent to the database, redirecting it to a different table or column.
* **Quarantining**:
  * Temporarily or permanently terminates user access when suspicious activity is detected.
  * Usually combined with alerting and logging for auditing purposes.

**8. Active Analytics**

* **Purpose**: Analyzes data activity to identify and provide insights into threats.
* **Threats**:
  * SQL injections, malicious stored procedures, denial of service, data leakage, account takeovers, schema tampering, etc.
* **Function**:
  * Provides recommendations for countermeasures to mitigate risks.

**9. Encryption**

* **Purpose**: Transforms data into an unintelligible form to protect its meaning from unauthorized users.
* **Encryption in Transit**:
  * Prioritizes speed and resource efficiency.
* **Encryption at Rest**:
  * Focuses on the strength of encryption and long-term preservation.
* **Symmetric Encryption**:
  * Decryption key is easily derivable from the encryption key (faster, less resource-intensive).
* **Asymmetric Encryption**:
  * Decryption key is not easily derivable (encryption key can be public, decryption key must remain private).

**10. Tokenization**

* **Purpose**: Substitutes sensitive data with a token that can be used as a proxy.
*   **Function**:

    * The token is issued by a trusted party and cannot be redeemed by untrusted parties.
    * Used in scenarios like a shopper providing a token instead of credit card information.



    <figure><img src="../.gitbook/assets/image (45).png" alt=""><figcaption></figcaption></figure>

**11. Key Management**

* **Purpose**: Centralizes the creation, management, and protection of encryption keys.
* **Importance**:
  * Ensures data confidentiality, integrity, and availability.
  * Prevents exposed keys from compromising data security.

**12. Automated Compliance Reporting**

* **Purpose**: Supports compliance with regulations and standards through automation.
* **Features**:
  * Pre-built classification patterns to identify sensitive data.
  * Preconfigured reports for regulatory data.
  * Workflows to implement mandated processes and auditing resources.
* **Benefit**:
  * Makes compliance with regulations feasible by reducing the resources required.
