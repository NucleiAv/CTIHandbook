# DevSecOps Deployment

* **Continuous Monitoring**:
  * Essential for adapting to changes in security status post-release.
  * Helps in enforcing policies and managing future deployments.
* **Dynamic Cloud Environments**:
  * Deployments and decommissioning are frequent and require controlled, secure processes.
  * Data cleansing and retention must be factored in.
  * Assets must be certified to withstand scrutiny upon destruction.
* **Component Scanning and Registries**:
  * Regular scanning and updates are necessary to assess vulnerabilities and licensing.
  * Scanning results guide whether remedial actions are needed.
* **Versioning and CMDB**:
  * Components are versioned and details stored in a Component Management Database (CMDB).
  * CMDB helps in tracking the environment state and generating security reports.
* **Deployment Control**:
  * Use a toolchain for deployments to ensure consistency and control.
  * Infrastructure as Code (IaC) with parameterized patterns ensures repeatable processes.
* **Immutable Images**:
  * Components should be treated as immutable images that are created and destroyed as needed.
* **IAM Controls**:
  * Manage who or what can control services through regulated IAM policies.
* **SaaS Data Disposal**:
  * Different procedures are needed for secure data disposal in SaaS offerings.
* **Integrated Security and Operations**:
  * Combine security and operations throughout the monitoring phase.
  * Use visualization for context and clarity in detection.
* **Playbooks as Code**:
  * Automate responses to detected issues.
  * Standardized playbooks drive controlled response and recovery.
* **Effective Security Operations**:
  * Include secret rotation, re-validation, and inventory maintenance.
  * Acknowledge that breaches are inevitable, focus on effective response.
* **Key Terms**:
  * **RASP (Runtime Application Self-Protection)**: Uses runtime instrumentation to detect and block attacks.
  * **Blue Team vs. Red Team**: Blue Team is internal cybersecurity, Red Team is external attackers.
  * **Mean-Time Between Failures (MTBF)** and **Mean-Time to Repair (MTTR)**: Metrics for system reliability and response.
* **SOAIR (Security Orchestration Automation and Incident Response)**:
  * Integrate DevOps and security early (DevSecOps) to reduce risk and cost, improve quality, and enhance compliance.
