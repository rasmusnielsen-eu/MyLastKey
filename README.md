# 🔐 My Last Key

> **A simple, private, and offline-first way to organize and secure your family's essential information for the future.**

[![Security First](https://img.shields.io/badge/Security-First-4A90E2?style=for-the-badge)](#-security-first)
[![100% Open Source](https://img.shields.io/badge/100%25-Open%20Source-50C878?style=for-the-badge)](https://github.com/rasmusnielsen-eu/MyLastKey)
[![Client Side Only](https://img.shields.io/badge/Client%20Side-Only-F5A623?style=for-the-badge)](#-how-it-works)

---

## 🎯 **Why This Project Exists**

What happens to your digital accounts, documents, and other important information if something happens to you? My Last Key was created to solve this problem. It's not a password manager. It's a simple tool to create a single, secure document for your loved ones—a "digital last will" that gives them access and guidance when they need it most.

---

## ✨ **Core Features**

### 🔒 **Security First**
**Nothing Leaves Your Browser**
- All processing happens exclusively on your device
- No passwords or sensitive information ever sent to servers
- We store nothing because we never receive it
- Your security is at the core of the tool's design

### 🔍 **Full Transparency** 
**100% Open Source**
- Entire source code publicly available on GitHub
- Security experts can review and verify our implementation
- No backdoors, no secrets, complete transparency

### 📋 **Practical Application**
**Your Digital Emergency Plan**
- Physical, secure, and readable backup of critical information
- Built-in QR codes for quick digital access
- Print and store in a safe place
- Your offline lifeline when you need it most

---

## 🚀 **How It Works: Two Simple Steps**

### **Step 1: Create Your Document**
Use the "Create Your Plan" tool to list all your important information:
- Account logins and passwords
- Locations of physical documents  
- Instructions for your partner or family
- Emergency contacts and procedures
- Add, edit, and categorize everything you need

### **Step 2: Secure & Share**
Optionally encrypt your entire document with a single, strong Master Key:
- Export encrypted text or QR code
- Save on USB drive or print QR code
- Store in safe place with Master Key (shared separately)
- Complete peace of mind for your family

---

## 🛠️ **Advanced Features**

### 🎨 **Print Customization**
- **Font Selection**: Choose from 5 professional fonts
- **Size Options**: 4 different font sizes (10pt - 16pt)
- **Color Modes**: Full color or black & white printing
- **Live Preview**: See changes instantly before printing

### 🔐 **Enhanced Security**
- **AES-256 Encryption** with PBKDF2 key derivation
- **250,000 iterations** with SHA-256 hashing
- **Client-side processing** - nothing ever leaves your browser
- **SRI integrity hashes** for all external dependencies

### 📱 **Smart Formatting**
- **Color-coded passwords**: Visual distinction for different character types
- **QR code generation**: For quick digital access to any field
- **Responsive design**: Perfect on desktop, tablet, and mobile
- **Print optimization**: Professional document layout

### 🔄 **Data Management**
- **Import/Export**: Backup and restore your data
- **Encryption support**: Import encrypted data with Master Key
- **JSON format**: Standard, readable data structure

---

## 📁 **Project Structure**

```
MyLastKey/
├── 📄 index.html              # Main landing page
├── 🔧 create.html             # Document creation tool
├── 🔓 dekrypter.html          # Standalone decryption tool
├── 🔒 mylastkey-decrypt.html  # Offline decryption kit
├── 🛡️ security.html           # Security & privacy details
├── 📁 assets/
│   └── 🎨 css/style.css       # Main stylesheet
├── ⚙️ vercel.json             # Deployment configuration
└── 📖 README.md               # This file
```

---

## 🛡️ **Security & Privacy**

### **Your Offline Decryption Kit**
Download the self-contained decryption tool - a single HTML file that works forever, on any computer with a web browser, even if this website is offline.

### **Manual Decryption Support**
For technical users, decrypt your data using standard command-line tools:
- **Windows PowerShell** instructions included
- **macOS/Linux Bash** commands provided
- Proves your data isn't locked to our specific tool

### **Shared Responsibility**
While MyLastKey is secure by design, ultimate security depends on:
- Your device security (malware-free)
- Browser plugin awareness
- Strong Master Key selection
- Physical document security

[📖 **Read Full Security Details**](security.html)

---

## 🎯 **Use Cases**

### 👨‍👩‍👧‍👦 **Family Emergency Planning**
- Critical account access for spouse/children
- Location of important physical documents
- Emergency contact information
- Medical information and preferences

### 💼 **Business Continuity**
- Essential system passwords
- Vendor contact information
- License keys and certificates
- Backup procedures and locations

### 🏠 **Personal Organization**
- Home security codes
- Wi-Fi passwords for guests
- Insurance policy numbers
- Safe combinations and locations

---

## 🖨️ **Print Guidelines**

### **Optimal Settings**
- **Paper**: A4 or Letter size
- **Margins**: 2cm standard European margins
- **Quality**: High quality for QR code clarity
- **Colors**: Full color recommended for password coding

### **Security Storage**
- Store in fireproof safe or safety deposit box
- Consider multiple copies in different locations
- Keep Master Key separate from printed document
- Review and update annually

---

## 🔗 **Links & Resources**

- 🌐 **Live Application**: [mylastkey.rasmusnielsen.eu](https://mylastkey.rasmusnielsen.eu)
- 📂 **GitHub Repository**: [rasmusnielsen-eu/MyLastKey](https://github.com/rasmusnielsen-eu/MyLastKey)
- 🛡️ **Security Details**: [Security & Privacy Page](security.html)
- 👨‍💻 **Creator**: [rasmusnielsen.eu](https://rasmusnielsen.eu)

---

## 🤝 **Contributing**

This project is open source and welcomes contributions:
- 🐛 **Bug Reports**: Open an issue on GitHub
- 💡 **Feature Requests**: Discuss in GitHub issues
- 🔧 **Code Contributions**: Submit pull requests
- 🔍 **Security Reviews**: Always appreciated

---

## 📄 **License & Copyright**

© 2025 Rasmus Nielsen | [rasmusnielsen.eu](https://rasmusnielsen.eu) | All rights reserved.

---

## ⚠️ **Important Reminders**

> **🔑 Master Key**: Remember your encryption key! Without it, encrypted information cannot be decrypted.

> **🔄 Regular Updates**: Review and update your document annually or when circumstances change.

> **🛡️ Secure Storage**: Store printed documents in secure, fireproof locations.

---

*"This started as a personal project to ensure my own family would be looked after. I wanted a solution that was simple, trustworthy, and not reliant on a company that could disappear tomorrow. I'm sharing it in the hope it can help others too."* - Rasmus 