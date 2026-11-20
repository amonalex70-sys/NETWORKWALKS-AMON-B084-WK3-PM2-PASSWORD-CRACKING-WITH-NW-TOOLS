 <div align="center">

# Password Cracking with NetworkWalks Tools

Extracting PDF password hashes and attempting password recovery using NetworkWalks online tools.

<p align="center">
  <img src="https://img.shields.io/badge/Project-Password%20Cracking-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Tools-NetworkWalks-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Platform-Web%20Browser-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Operating%20System-Kali%20Linux-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Technique-Hash%20Extraction-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Focus-Password%20Security-C00000?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Technology-Online%20Tools-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Platform-GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Project%20Module-W3--PM2-E87500?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Program-NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Practice-Ethical%20Hacking-E87500?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Mentor-Waqas%20Karim%20(CCIE)-C00000?style=flat-square" />
</p>
</div>

## 🔐 Password Cracking Overview

This project documents practical password-cracking techniques using **NetworkWalks online tools** as part of the cybersecurity training program.

The exercise focuses on extracting password-hash information from a password-protected PDF document using the **NetworkWalks Hash Calculator** and attempting password recovery through the **NetworkWalks Password Cracker**.

It also explores PDF password protection, hash extraction, online password recovery, and the importance of strong password security.

## 🎯 Password Cracking Objectives

The primary objectives of this project are to:

- Understand the fundamentals of password cracking and PDF password protection.
- Download and prepare the password-protected PDF document for testing.
- Use the NetworkWalks Hash Calculator to extract the PDF password hash.
- Copy and identify the complete `$pdf$` hash value.
- Use the NetworkWalks Password Cracker to perform a dictionary attack.
- Explore the built-in password list and custom wordlist options.
- Retrieve and examine the recovered password.
- Verify the recovered password by unlocking the protected PDF document.
- Capture the first cybersecurity flag after successfully opening the PDF.
- Understand the importance of strong passwords and effective password security.

## 🛡️ Lab Purpose and Security Scope

This lab provides a practical environment for understanding password security, PDF password protection, hash extraction, and dictionary-based password recovery using NetworkWalks online tools.

It supports hands-on practice in the following areas:

- Understanding password hashing and PDF encryption.
- Extracting password hashes from protected PDF documents.
- Using online hash calculation tools.
- Performing dictionary-based password attacks.
- Exploring built-in and custom password wordlists.
- Recovering and verifying PDF passwords.
- Understanding password strength and security.

**⚠️ Security Notice:** Password recovery activities must only be performed on files you own or have explicit permission to test. Never use these techniques to access unauthorized documents or information.

## ⚙️ Cybersecurity Lab System Specifications

| 🧩 Component | ⚙️ Configuration |
|---|---|
| 🖥️ Operating System | Kali Linux 2026.3 |
| 🧠 System RAM | 8 GB |
| ⚡ Processor | Intel Core i5 |
| 🌐 Platform | Web Browser |
| 🔐 Hash Extraction Tool | NetworkWalks Hash Calculator |
| 🔓 Password Recovery Tool | NetworkWalks Password Cracker |
| 📄 Target Document | My Locked PDF1.pdf |
| 🔑 Hash Format | PDF Hash (`$pdf$`) |
| ⚔️ Attack Technique | Dictionary Attack |
| 📚 Password Wordlist | Built-in List (100 Passwords) / Custom Wordlist |
| 🌍 Internet Connection | Required |

## ⚙️ Password Cracking Implementation Steps

## Step 1: Download the Password-Protected PDF

A password-protected PDF document was obtained and saved locally to serve as the target file for the password recovery exercise.

**Target File:**

```text
My Locked PDF1.pdf
```

The document was prepared for hash extraction and subsequent password recovery using the available online tools.


## Step 2: Access the NetworkWalks Hash Calculator

The NetworkWalks Hash Calculator was opened in a web browser to prepare for extracting the password hash from the protected PDF document.

<img width="853" height="587" alt="Networkwalk-Tool" src="https://github.com/user-attachments/assets/afc8175a-2713-4040-a2a8-71a6faba7f76" />


## Step 3: Extract the PDF Password Hash

The downloaded PDF document was uploaded to the NetworkWalks Hash Calculator using the file upload option.

The tool processed the document and generated an extractable password hash in PDF format, beginning with the `$pdf$` identifier.


## Step 4: Copy the Extracted PDF Hash

The complete PDF password hash was copied from the Hash Calculator output.

**Important:** The entire hash value, starting with `$pdf$`, must be copied without missing or modifying any characters.


## Step 5: Access the NetworkWalks Password Cracker

The NetworkWalks Password Cracker was opened in a new browser tab to perform the password recovery process.

<img width="1077" height="600" alt="NTC" src="https://github.com/user-attachments/assets/96db33c3-300d-49bc-89bf-0e0d1c48d3bc" />


## Step 6: Submit the Hash and Start the Dictionary Attack

The extracted PDF hash was pasted into the password input field of the NetworkWalks Password Cracker.

The built-in password list containing 100 password candidates was selected for the exercise. The attack was initiated by clicking the **START CRACKING** button.

The tool tested the available password candidates against the submitted PDF hash.


## Step 7: Retrieve the Recovered Password

The password recovery process was allowed to complete. The tool successfully identified a matching password and displayed the recovery result.

**Recovered Password:**

```text
password1
```

The recovery time depends on the password candidates and the complexity of the target password.


## Step 8: Enter the Recovered Password

The original password-protected PDF document was opened using a PDF reader.

When prompted, the recovered password was entered to unlock the document.

```text
Password: password1
```

## Step 9: Verify Successful PDF Access

After entering the recovered password, the PDF document opened successfully and displayed the NetworkWalks congratulations message.

The document confirmed that the first cybersecurity flag had been captured, marking the successful completion of the lab.

**Result:** Successfully recovered the PDF password and accessed the protected document.dance, mentorship, and support throughout this learning journey.**


# 🐞 Problems Encountered & Solutions

Documenting challenges and solutions helps improve troubleshooting skills and provides useful references for future password-security exercises.

## Problem 1: Extracting the PDF Password Hash

The password-protected PDF needed to be processed correctly before its hash could be used for password recovery.

**Solution:** The NetworkWalks Hash Calculator was used to upload and process the PDF document. The complete hash value beginning with `$pdf$` was copied for the next stage.

## Problem 2: Submitting the Complete Hash

The password recovery process requires the complete extracted PDF hash. Missing characters or incomplete hash values may prevent the tool from processing the submission correctly.

**Solution:** The extracted hash was copied in full from the Hash Calculator and pasted into the NetworkWalks Password Cracker.

## Problem 3: Password Recovery

The password recovery process required testing available password candidates against the submitted PDF hash.

**Solution:** The built-in password list was used to perform a dictionary attack. The tool identified the matching password, `password1`, which was subsequently used to unlock the PDF document.

---

# 💡 What I Learned

Through this project, I gained practical experience in password recovery using NetworkWalks online cybersecurity tools.

The most important concepts I learned include:

### 1. Password Hashing and PDF Protection

I learned how password-protected PDF documents use encryption and how password hashes can be extracted for security testing and password recovery.

### 2. Hash Extraction

I learned how to use the NetworkWalks Hash Calculator to process a protected PDF document and extract its password hash in the `$pdf$` format.

### 3. Online Password Cracking Tools

I gained experience using the NetworkWalks Password Cracker to process extracted hashes and attempt password recovery through a web-based interface.

### 4. Dictionary Attacks

I learned how dictionary-based attacks work by testing password candidates against an extracted hash until a matching password is identified.

### 5. Password Recovery and Verification

I learned how to examine password recovery results and verify the recovered password by opening the original protected PDF document.

### 6. Troubleshooting and Documentation

I improved my ability to follow a structured password recovery workflow, identify potential issues during hash extraction and submission, and document practical results using screenshots and explanations.

### 7. Password Security Awareness

I developed a better understanding of why weak and commonly used passwords are vulnerable to dictionary attacks and why strong, unique passwords are essential for protecting sensitive information.

---

# 🔐 Security & Ethical Use

This project was conducted strictly for educational purposes as part of the NetworkWalks Cybersecurity Program.

Password-cracking techniques should only be applied to documents you own or have explicit authorization to test.

Never use these tools to access protected files, confidential information, or documents without permission.

---

# 🔗 Tools & Resources

- **NetworkWalks Project Task:** https://networkwalks.com/project-task-lab-password-cracking-with-networkwalks-tools/
- **NetworkWalks Hash Calculator:** https://networkwalks.com/hash-calculator/
- **NetworkWalks Password Cracker:** https://networkwalks.com/password-cracker/
- **NetworkWalks:** https://networkwalks.com/

---

# 👤 Author

**Amon Alex**  
Cybersecurity Student B084 | Electronics, Telecommunications & Cybersecurity

**LinkedIn:** [Amon Alex](https://www.linkedin.com/in/amon-lowasa-60877a42a/)

## 📌 Project Information

**Program Name:** Cybersecurity at NetworkWalks | **Week:** 03 | **Project Module:** W3-PM2 | **Project:** Password Cracking with NetworkWalks Tools | **Repository:** GitHub



