# CAS

**CAS** stands for **Content Addressed Storage**. It's a type of storage system where data is stored based on its content rather than its location. In a CAS system, data is identified by a unique hash or address derived from the content itself, rather than by a file name or directory path.

#### Key Features of CAS:

* **Immutability:** Once data is stored, it cannot be modified, ensuring data integrity and making it suitable for archiving.
* **Content-Based Addressing:** Each piece of data is given a unique identifier (hash) based on its content. This ensures that even if two files have the same name but different content, they will be stored separately.
* **Efficiency:** CAS systems can eliminate duplicate data (deduplication) by recognizing that identical content has already been stored.
* **Scalability:** Designed to handle large volumes of data, CAS systems are often used for archiving, backup, and regulatory compliance purposes.

#### Use Cases:

* **Archiving:** CAS is commonly used for long-term data storage, such as legal documents, medical records, and emails, where data integrity is critical.
* **Compliance:** Industries that need to comply with regulations requiring data to be stored unaltered for long periods (e.g., healthcare, finance) often use CAS.
* **Data Deduplication:** Reduces storage costs by eliminating redundant copies of data.

CAS systems are often part of enterprise storage solutions, providing secure, reliable, and scalable storage for critical data.
