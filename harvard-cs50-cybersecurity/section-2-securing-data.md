## Introduction
Data security is a core component of cybersecurity because information is constantly being stored, transmitted, accessed, modified, and deleted. This section explored the methods used to protect data from unauthorized access, maintain integrity, and preserve confidentiality.

The topics introduced both traditional and modern approaches to securing information through cryptography, encryption techniques, authentication methods, and secure data handling practices.

---

## Cryptography
Cryptography is the practice of protecting information by transforming readable data into forms that unauthorized users cannot understand.

Its major goals include:
- Confidentiality
- Integrity
- Authentication
- Non-repudiation

Cryptography serves as the foundation for many modern security technologies.

---

## Hashing
Hashing converts data into a fixed-length output known as a hash value.

Key characteristics:
- Designed to be one-way
- Used to verify integrity
- Commonly applied to password storage

Unlike encryption, hashing is generally intended to prevent original data recovery.

---

## Rainbow Tables
Rainbow tables are precomputed collections of hashes used to speed up attempts to match hashes to original values.

This demonstrates why relying only on hashing may be insufficient for protecting sensitive information.

---

## Salting
Salting strengthens password protection by adding random data before hashing.

Benefits include:
- Makes identical passwords produce different hashes
- Reduces effectiveness of rainbow table attacks
- Improves password storage security

---

## Encoding and Decoding
Encoding changes data into another format for compatibility or transmission.

Decoding restores encoded information into its original form.

Encoding is designed for usability and communication rather than security.

---

## Ciphers, Enciphering, and Deciphering
A cipher is a set of rules used to transform information.

- Encipher → convert plaintext into protected form
- Decipher → restore protected information into readable form

These ideas form the basis of encryption systems.

---

## Encryption and Decryption
Encryption converts readable information into unreadable ciphertext.

Decryption restores ciphertext into readable information using the appropriate key.

Encryption protects data against unauthorized access.

---

## Types of Encryption in Cryptography

### Symmetric Encryption (Secret Key)
Uses one shared key for both encryption and decryption.

Advantages:
- Faster performance
- Efficient for large data

Challenges:
- Secure key sharing

### Asymmetric Encryption (Public Key)
Uses two keys:
- Public key → encrypt
- Private key → decrypt

Advantages:
- Easier secure communication
- Supports identity verification

Challenges:
- Computationally slower

---

## Digital Signatures
Digital signatures verify:
- Identity of the sender
- Integrity of information
- Authenticity of communication

They help detect unauthorized modification.

---

## Passkeys
Passkeys represent a newer authentication approach designed to reduce dependence on traditional passwords.

Benefits:
- Resistant to phishing
- Improved convenience
- Reduced password reuse

---

## Protecting Data During Different Stages

### Encryption in Transit
Protects information while moving between devices or networks.

### End-to-End Encryption (E2EE)
Ensures only intended participants can access communication content.

### Encryption at Rest
Protects stored information such as files, databases, and backups.

### Secure Deletion
Proper deletion focuses on reducing the ability to recover removed data.

---

## Ransomware
Ransomware is malicious software that encrypts or restricts access to data and demands payment.

This topic highlighted:
- Importance of backups
- Data recovery planning
- Preventive security measures

---

## Quantum Computing and Future Security
Quantum computing introduces future challenges for current cryptographic systems because some existing encryption approaches may become easier to break under sufficiently advanced quantum systems.

This has increased interest in developing stronger future-resistant cryptographic methods.

---

## Personal Reflection
This section expanded my understanding of cybersecurity beyond account protection into information protection. I learned that securing data involves more than hiding information—it includes protecting how data is created, transmitted, stored, verified, and eventually removed.

---

## Key Takeaways
- Encryption protects confidentiality.
- Hashing supports integrity.
- Salting strengthens password security.
- Data requires protection both in storage and transmission.
- Future technologies such as quantum computing may reshape cybersecurity practices.
