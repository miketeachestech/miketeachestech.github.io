+++
author = "Michael Grassi"
title = "HSC Software Engineering (Year 12) - The CIA Triad"
date = "2024-10-12"
description = "Learn about the fundamental software design security concept called the CIA triad."
tags = [
    "hsc",
    "software",
    "software engineering",
    "year 12",
    "developing secure code",
    "secure software architecture",
    "cia",
    "confidentiality",
    "integrity",
    "availability"
]
+++

# The CIA Triad | Developing Secure Code | HSC Software Engineering

When developing secure software, it's essential to understand some core security principles. These principles are the foundation for protecting sensitive information, ensuring data integrity, and keeping systems accessible to those who need them. One of the most fundamental models for understanding software security is the **CIA Triad**—**Confidentiality, Integrity, and Availability**. Let's break down what each of these terms means and how you can apply them when writing secure code.

### 1. Confidentiality
Confidentiality is about making sure that sensitive information is only accessible to those who are authorized to see it. Think of it like keeping secrets safe—if you're not meant to know, you shouldn't be able to see it.

**How to Implement Confidentiality in Code:**
- **Data Encryption**: Use encryption to keep sensitive data secure, whether it's stored in a database or being sent over the internet.
- **Access Control**: Only allow authorized users to access specific parts of the app by using techniques like **role-based access control (RBAC)**.
- **Secure Data Storage**: Store sensitive data, like passwords, securely using hashing instead of saving them as plain text.

### 2. Integrity
Integrity is all about keeping data accurate and unchanged unless it's meant to be changed. Imagine if someone could tamper with your bank account balance—that's a breach of integrity.

**How to Implement Integrity in Code:**
- **Checksums and Hashing**: Use hashing to check if data has been altered by comparing the hash of the original data with the received version.
- **Digital Signatures**: Use digital signatures to verify that messages or documents haven’t been tampered with.
- **Input Validation**: Always validate user inputs to prevent attacks like **SQL injection** or **cross-site scripting (XSS)**, which could compromise data integrity.

### 3. Availability
Availability means that the system and its data should always be accessible to authorized users when they need it. Imagine not being able to access an important document because the system is down—that's an availability issue.

**How to Implement Availability in Code:**
- **Redundancy and Backup Systems**: Keep backup systems and redundant servers ready to make sure your app stays online even if something goes wrong.
- **Rate Limiting and Throttling**: Protect against **Distributed Denial of Service (DDoS)** attacks by limiting how much traffic your app can receive at once.
- **Error Handling**: Write strong error-handling code to prevent crashes when the system faces unexpected inputs or situations.

### Wrapping It Up
The **CIA Triad**—Confidentiality, Integrity, and Availability—helps you understand what’s essential when designing secure software. By keeping data safe, making sure it’s accurate, and ensuring the system is accessible, you’re well on your way to building resilient and secure software. Remember, secure software doesn’t just work well—it keeps users’ data safe and builds trust.

Apply these principles in your code, and you'll be creating secure, dependable applications that users can count on.