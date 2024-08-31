# SIEM Solutions - Vendors

#### **1. Overview of SIEM Solutions:**

* **SIEM (Security Information and Event Management)** solutions help in analyzing security event data in real-time, supporting early detection of attacks and breaches.
* These tools are used for collecting, storing, investigating, mitigating, and reporting on security data, essential for incident response, forensics, and regulatory compliance.

#### **2. Gartner's Magic Quadrant:**

* Vendors like **IBM QRadar, Splunk, Exabeam, LogRhythm, and Rapid7** are positioned in the Magic Quadrant for their robust SIEM solutions.
* The discussion focuses on IBM QRadar, Splunk, Exabeam, and LogRhythm.

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

#### **3. Deployment Sizes:**

* **Small Deployment:** Around 300 log sources and 1500 Events Per Second (EPS).
* **Medium Deployment:** About 1000 log sources and 7000 EPS.
* **Large Deployment:** About 1000 log sources and 15,000 EPS.
* **Flows:** Communication between devices on a network is also crucial, though not all SIEM solutions handle them effectively.

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

#### **4. SIEM Concepts:**

* **Rules:** Procedures that correlate events into a report or incident.
* **Rule Threshold:** Point at which the rule is triggered.
* **Event Threshold:** Number of times an event must occur before triggering a rule.
* **Rule Action:** Procedure that occurs when conditions and thresholds are met.
* **Trends:** Define how and over what time data will be aggregated and evaluated.

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

#### **5. Data Collection and Normalization:**

* **Data Collection:** Process of collecting flows and logs from various sources.
* **Normalization:** Raw events are turned into readable fields like IP addresses, making them easier to analyze.

#### **6. IBM QRadar:**

* **Components:** Vulnerability Manager, User Behavior Analytics, QRadar Network Insights.
* **Focus:** Started with network behavior anomaly detection.
* **Differentiator:** Focuses on flow data, which is not natively handled by most SIEM solutions.

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

#### **7. ArcSight:**

* **Components:** ArcSight Manager, CORR-Engine, Console, Command Center, APIs.
* **Focus:** Event correlation and security analytics.

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

#### **8. Splunk:**

* **Unique Value Proposition:** Operational intelligence, aiming to make machine data accessible and usable.
* **Architecture:** Data collection, indexing, and presentation layers.
* **Growth:** Initially not a SIEM, but expanded into the SIEM space.

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption><p>Friendly Representation of Splunk Services</p></figcaption></figure>

#### **9. LogRhythm:**

* **Components:** Platform Manager, Data Processor, Data Indexer, AI Engine.
* **Focus:** Centralized management, network monitoring, and deep analysis of network traffic.
* **All-in-One Appliance:** For smaller implementations, combining all solutions into a single appliance.

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>
