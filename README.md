# 🔐 Sensitive Data Anonymization System

## 🏆 Achievement
🥈 Awarded 2nd place in the 2023 project excellence competition at the Israel National Cyber Directorate.

---

## 📌 Overview

Organizations often need to share internal data with external parties such as vendors, analysts, or partners.  
However, this creates a significant risk of exposing sensitive information (e.g., IP addresses, personal data, identifiers).

This project presents an automated solution for detecting and masking sensitive data within documents before they leave the organization.

---

## 🚀 Solution

We developed a system that processes a directory of files, automatically identifies sensitive data patterns, and replaces them with sanitized values.

Instead of manually reviewing and redacting documents, the system performs this process programmatically, improving efficiency, consistency, and security.

---

## ⚙️ How It Works

### Input
- A folder containing files with potentially sensitive information

### Processing
- Pattern detection using **Regular Expressions (Regex)**
- Identification of sensitive entities such as:
  - IP addresses  
  - Identifiers  
  - Structured patterns  
- Replacement (masking) logic:
  - Sensitive values are substituted with safe placeholders  
  - Example:
    - `192.168.1.1` → `123.123.123.123`

### Output
- A sanitized version of the original files  
- Structure and readability preserved  
- Sensitive data removed or anonymized  

---

## 🧠 Key Concepts & Techniques

- Regular Expressions (Regex) for pattern matching  
- Text processing and transformation  
- Data sanitization and anonymization strategies  
- Automation of manual security workflows  

---

## 🏗️ System Design (High-Level)

1. File ingestion from a directory  
2. Content parsing  
3. Pattern detection engine  
4. Masking / replacement module  
5. Output generation  

---

## 💡 Impact

- Eliminated the need for manual data redaction  
- Reduced human error in handling sensitive data  
- Improved speed and scalability of document processing  
- Enabled safer data sharing across organizational boundaries  

---

## 🔐 Confidentiality Notice

Due to the sensitive nature of this project and organizational security policies, the source code and real data cannot be publicly shared.

This repository is intended to present the system design, approach, and technical concepts behind the solution.

---

## 📚 Key Learnings

- Designing secure systems under real-world constraints  
- Translating business/security requirements into technical solutions  
- Working with pattern detection at scale  
- Balancing usability with data protection  

---

## 🚀 Future Improvements

- Integration with NLP models for advanced entity detection  
- Configurable masking rules per organization  
- Support for additional file formats  
- Logging and audit trails for compliance  

---

## 👩‍💻 About

This project was developed as part of a cybersecurity-focused program and reflects hands-on experience in building practical solutions for sensitive data protection in real-world environments.
