# 🛡️ Cybersecurity Notes (TryHackMe Journey)

## 📍 About Me
I am currently learning cybersecurity and IT support fundamentals using TryHackMe and hands-on labs. This repository documents my progress, notes, and practical skills.

---

## 🧠 Topics Covered
- Encryption (Symmetric vs Asymmetric)
- CIA Triad (Confidentiality, Integrity, Availability)
- Networking Basics
- Linux Fundamentals
- Security Concepts (Vulnerabilities, Exploits)
- Web Security (OWASP basics)

--- 🧠 Cybersecurity Notes
## 🔐 Encryption Notes

- Symmetric encryption uses one shared key
- Asymmetric encryption uses a public and private key pair

- HTTPS:
  - HTTPS uses asymmetric encryption to securely exchange a key
- Then uses symmetric encryption for fast data transfer

---

## 🧠 CIA Triad

- Confidentiality → Prevent unauthorized access to sensitive data
- Integrity → Ensure data is not altered without permission
- Availability → Ensure systems and services remain accessible

### 📌 Example

- DDoS attack → affects **Availability**

---

## 🧩 Security Concepts

- Vulnerability → weakness in system
- Exploit → method to use vulnerability
- Scope → what can be tested
- Dictionary attack → password guessing using wordlist## 💻 Terminal Basics
```bash
cd folder_name   # move into folder
ls               # list files (Linux)
dir              # list files (Windows)
cd ..            # go back   

---

## 🌐 SSH
ssh user@ip      # connect to remote machine  

---

## 👤 Users
whoami           # current user  
su username      # switch user  
su - root        # admin access  

---

## 🔍 Finding Files
find / -name file.txt  
dir /s filename  

---

## 🔐 Security Concepts
- Weak passwords are common  
- Password reuse is dangerous  
- History can leak passwords  

---

## 🔢 Encoding Basics
ASCII: A = 65  
Hex: AB = 171  
Base64: SGVsbG8= → Hello  

---

## 🌍 Unicode
U+30B7 = シ  
UTF-16: 30B7  
UTF-32: 0001F60C

---

## 🧪 Practical Skills (TryHackMe)

- Completed beginner rooms on:
  - Encryption basics
  - Web attacks (login brute force)
  - Networking fundamentals
- Used tools like:
  - Hydra (password attacks)
  - Linux terminal commands
