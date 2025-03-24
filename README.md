# linux-password-cracking-johntheripper
Cracking Linux password hashes with John the Ripper (Network Security Lab)

# Linux Password Cracking Lab (John the Ripper)

## Lab Overview
This lab demonstrates the ethical use of **John the Ripper**, an open-source password-cracking tool used by security professionals to test password strength.

## Objectives
- Understand how John the Ripper works.
- Run password cracking against Linux password hashes.
- Verify cracked passwords for validation.

## 🛠Tools Used
- **John the Ripper** (dictionary and brute-force attacks)
- **Linux Terminal**

## Skills Practiced
- Cryptanalysis
- Ethical hacking fundamentals
- Password hash recognition
- Linux command-line operations

## Lab Prerequisites
- Basic Linux terminal knowledge
- Pre-installed John the Ripper tool

## Example Commands
```bash
john --wordlist=/usr/share/wordlists/rockyou.txt shadow.txt
john --show shadow.txt
