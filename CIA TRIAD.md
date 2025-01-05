# **CIA Triad**

The **CIA Triad** is a foundational model in information security, representing the core principles to protect sensitive data and systems. It stands for:

1. **Confidentiality**
2. **Integrity**
3. **Availability**

---

## **1. Confidentiality**
- **Definition:** Ensures that sensitive information is accessible only to authorized users and not disclosed to unauthorized parties.
- **Key Measures:**
  - Encryption (e.g., AES, RSA)
  - Access controls (e.g., role-based access control, least privilege)
  - Data masking and anonymization
  - Secure authentication mechanisms (e.g., passwords, biometrics)
- **Threats:** Unauthorized access, social engineering, data breaches.

---

## **2. Integrity**
- **Definition:** Ensures that data is accurate, complete, and protected from unauthorized modification.
- **Key Measures:**
  - Checksums and hashing (e.g., SHA-256)
  - Digital signatures
  - Version control systems
  - Regular data validation and audits
- **Threats:** Data tampering, man-in-the-middle (MITM) attacks, malware.

---

## **3. Availability**
- **Definition:** Ensures that systems, applications, and data are available to authorized users when needed.
- **Key Measures:**
  - Redundancy (e.g., failover systems, load balancing)
  - Disaster recovery and business continuity plans
  - Regular system maintenance and updates
  - Protection against denial-of-service (DoS) attacks
- **Threats:** Hardware failure, natural disasters, cyberattacks (e.g., DDoS).

---

## **Balancing the CIA Triad**
Achieving a balance between **Confidentiality**, **Integrity**, and **Availability** is critical for building a secure system. Overemphasizing one aspect can compromise the others. For example:
- Increasing **Confidentiality** (e.g., stringent access controls) may reduce **Availability**.
- Prioritizing **Availability** without proper controls can weaken **Integrity** and **Confidentiality**.

The CIA Triad serves as a guiding principle for designing, implementing, and evaluating security measures across all industries.
