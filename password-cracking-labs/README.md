# Password Cracking Labs — Cybersecurity & Ethical Hacking

Hands-on lab exercises exploring password recovery techniques against password-protected PDF files, completed as part of a Cybersecurity & Ethical Hacking training program (Week 3 project modules).

## 📋 Overview

These labs demonstrate how weak passwords can be recovered from encrypted files, reinforcing why strong, complex passwords matter. Each lab follows the same general workflow:

1. Extract a crackable hash from a password-protected PDF
2. Run that hash through a password-cracking tool against a wordlist
3. Use the recovered password to unlock the original file

## 🧪 Modules

| Module | Tooling | Description |
|---|---|---|
| [Module 1 — JTR](docs/module1-jtr.md) | John the Ripper (CLI) + Johnny (GUI) | Industry-standard offline password cracker |
| [Module 2 — NetworkWalks Tools](docs/module2-networkwalks-tools.md) | NetworkWalks Hash Calculator + Password Cracker (browser-based) | Lightweight in-browser hash extraction and dictionary attack |

## 🛠️ Skills Demonstrated

- Hash extraction from encrypted PDF files (`pdf2john` / hashcat-compatible format)
- Dictionary / wordlist-based password attacks
- Difference between **encryption** (reversible, key-based) and **hashing** (one-way)
- Practical understanding of password strength and why 8-character lowercase-only passwords fail quickly
- Use of both CLI and GUI tooling for the same underlying task

## 📂 Repository Structure

```
password-cracking-labs/
├── README.md
├── docs/
│   ├── module1-jtr.md
│   └── module2-networkwalks-tools.md
└── screenshots/
    ├── module1-jtr-flag-captured.png
    ├── module2-networkwalks-tools-flag-captured.png
    └── bonus-flag-captured.png
```

## ⚠️ Disclaimer

This work was performed in a controlled training/lab environment against a provided sample file (`My Locked PDF1.pdf`) for educational purposes only. Password cracking techniques should only ever be used on systems and files you own or have explicit authorization to test.

## 🙏 Acknowledgment

Lab materials and tooling (Hash Calculator, Password Cracker) provided by [NetworkWalks Academy](https://www.networkwalks.com) as part of their Cybersecurity & Ethical Hacking training course.
