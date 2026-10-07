# Password Security and Cracking Assessment

## 📌 Project Overview

A hands-on Password Security and Cracking Assessment performed in a controlled virtual laboratory environment.

The project focused on password hashing, hash analysis, password-cracking techniques, and controlled Metasploit payload testing using self-controlled virtual machines.

## 🎯 Objectives

- Understand password hashing and password security
- Compare MD5 and SHA-256
- Analyze SHA-256 password hashes using John the Ripper
- Perform dictionary-based password cracking
- Perform brute-force password cracking
- Understand Rainbow Table attacks
- Create and test a Metasploit payload in a controlled VM
- Identify security impacts and recommend mitigations

## 🔐 Techniques & Security Areas

- SHA-256 Hash Analysis
- Dictionary Attack
- Brute-Force Attack
- Rainbow Tables
- MD5 vs SHA-256
- Metasploit Payload Creation
- Controlled Windows VM Testing
- Password Security Assessment
- Security Mitigations

## 🛠️ Tools & Technologies

- Kali Linux
- John the Ripper
- Metasploit Framework
- Windows Virtual Machine

## 🔎 Practical Work

### 1. SHA-256 Dictionary Attack

A controlled SHA-256 hash was analyzed using John the Ripper with a dictionary wordlist.

The dummy password `password123` was successfully recovered.

### 2. SHA-256 Brute-Force Attack

A separate controlled SHA-256 hash was tested using John the Ripper's incremental mode.

The dummy password `1234` was successfully recovered.

### 3. Rainbow Tables

Rainbow Tables were studied as a password-cracking technique based on precomputed hash-to-password mappings.

Their advantages and limitations were analyzed, including the effectiveness of unique salts against precomputed attacks.

### 4. Metasploit Payload Testing

A Windows Meterpreter reverse-TCP payload was generated and tested against a self-controlled Windows virtual machine in an authorized laboratory environment.

The controlled test resulted in a successful Meterpreter session, demonstrating the potential security impact of unauthorized payload execution.

## 🛡️ Key Recommendations

- Use strong and unique passwords
- Avoid password reuse
- Use secure, salted, password-specific hashing/KDF mechanisms
- Enable Multi-Factor Authentication (MFA)
- Implement rate limiting and account throttling
- Use endpoint protection and EDR
- Apply least-privilege access
- Use network segmentation
- Maintain security awareness and password-security best practices

## 📂 Repository Structure

```text
Password-Security-and-Cracking-Assessment/
│
├── README.md
│
├── Evidence/
│   ├── 01_John_SHA256_Dictionary_Attack.png
│   ├── 02_John_SHA256_BruteForce.png
│   ├── 03_Metasploit_Payload_Generation.png
│   ├── 04_Metasploit_Handler_Configuration.png
│   └── 05_Metasploit_Controlled_VM_Test_Result.png
│
└── Report/
    └── Module_7_Password_Security_and_Cracking_Assessment.pdf
