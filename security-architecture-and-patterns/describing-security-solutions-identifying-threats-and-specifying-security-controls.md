# Describing Security Solutions, Identifying Threats, and Specifying Security Controls

**1. Solution Architecture Overview**

<figure><img src="../.gitbook/assets/image (53).png" alt=""><figcaption></figcaption></figure>

* **Architecture Development**: The process of developing security architecture begins with a broad enterprise architecture and gradually narrows down to specific solutions. This involves decomposing the architecture into various levels of detail.
* **Overlap in Architecture**: There can be an overlap between different architectural levels, sometimes leading to hybrid versions of diagrams.

**2. Architecture Perspectives**

* **Two Main Perspectives**:
  1. **Security Architect Supporting a Solution**: Collaborating with a broader team to develop security solutions.
  2. **Security Architect Designing a Security Service**: Focusing solely on IT architecture aspects relevant to security services.

**3. Specifying Security for a Solution**

<figure><img src="../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (62).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (63).png" alt=""><figcaption></figcaption></figure>

* **Architecture Overview**:
  * Start with a high-level conceptual diagram to initiate the project. This diagram should communicate the general concepts but doesn't include security details initially.
* **System Context**:
  * Identify system boundaries and external actors (human or system actors).
  * **Use Cases**: Describe activities performed by actors and the data flow involved. Security controls are meant to protect this data and its availability.
  * **Data Classification**: Classify the data being processed to guide necessary security controls based on policy and environment.

**4. Functional Model and Operational Model**

* **Functional Components**:
  * Document the functional components of the system and their interactions. Each interaction involves data flow, which must be protected.
  * Identify threat actors and necessary controls to safeguard data in transit and at rest.
* **Operational Model**:
  * Define capabilities needed to implement the system. Components are categorized into zones based on data classification and organizational policies.
  * Security controls are identified, and decisions regarding specific technologies or products are made.

**5. Considering New Actors and Environments**

* As the architecture is elaborated, consider new actors, such as security operations, which may affect the security context.
* **Outsourcing Considerations**:
  * If a capability is outsourced, update the security context to include the new actor, defining their use cases and the data that needs protection.

**6. Iterative Process and Questions**

* **Stakeholder Identification**:
  *   Continuously ask key questions during the architecture process:

      * Who are the stakeholders or actors enforcing security?
      * Where are the system's components and actors located?
      * When are security controls required, and what are their implementation priorities?
      * Why is the system needed, and what requires protection?
      * How will the data be protected?

      <figure><img src="../.gitbook/assets/image (56).png" alt=""><figcaption></figcaption></figure>
* **Iterative Updates**:
  * As the architecture evolves, diagrams and models should be iteratively updated to reflect new requirements and improvements.

These provide a systematic approach to developing security solution architecture by gradually refining and detailing the architecture, considering both external and internal actors, and iteratively updating the architecture to meet evolving security needs.
