# 🔐 Ransomware Simulation & Decryption Project

**Educational Purpose Only** - A safe ransomware simulation to understand cybersecurity threats, encryption mechanisms, and defense strategies. Runs entirely on Google Colab with Google Drive storage.

---

## 📋 Project Overview

This project simulates ransomware behavior in a completely safe, isolated environment. It demonstrates:

| Module | Description |
|--------|-------------|
| **Key Manager** | Generates and manages AES-128 encryption keys |
| **Encryption Simulator** | Safely encrypts test files (simulated ransomware) |
| **System Monitor** | Tracks CPU, memory, and file changes |
| **Decryption & Recovery** | Restores encrypted files using the correct key |

---

## 🎓 Educational Purpose

This project was created to:

1. Understand how ransomware encrypts files
2. Learn encryption and decryption algorithms
3. Monitor system behavior during security events
4. Analyze attack patterns using the Cyber Kill Chain
5. Develop recovery strategies

> ⚠️ **IMPORTANT**: This is a SAFE EDUCATIONAL SIMULATION. No real systems or data are at risk.

---

## 🤖 AI Assistance Disclosure

This project was developed with AI assistance to ensure code safety, educational clarity, and best practices.

| Aspect | AI Contribution |
|--------|-----------------|
| **Code Safety** | Proper cryptographic implementation, error handling |
| **Educational Clarity** | Clear documentation and explanatory notes |
| **Best Practices** | Industry standards for encryption and file handling |

> All AI-generated code was reviewed, tested, and validated for educational use.

---

## ⚠️ Safety Notice

| ✅ Safe Practices | ❌ Never Do |
|------------------|------------|
| Run only in Google Colab | Run on personal computer |
| Use only test files | Encrypt real files |
| Store keys securely | Share encryption keys |
| Verify recovery works | Use on production systems |

---

## 📁 Project Structure

Ransomware_Simulation_Project/
│
├── notebooks/ # 4 Colab notebooks (run in order)
│ ├── Folder_Setup.ipynb
│ ├── 1_Key_Manager.ipynb
│ ├── 2_Encryption_Simulator.ipynb
│ └── 3_Decryption_Recovery.ipynb
│
├── scripts/ # Encryption keys
├── test_files/ # Original test files
├── encrypted_files/ # Files after encryption
├── recovered_files/ # Files after recovery
├── screenshots/ # Documentation screenshots
├── reports/ # Recovery reports
└── RANSOM_NOTE.txt # Educational ransom note


---

## 🔧 Technical Stack

| Component | Technology |
|-----------|------------|
| Platform | Google Colab |
| Storage | Google Drive |
| Encryption | Fernet (AES-128) |
| Language | Python 3.10+ |

---

## 📦 Prerequisites

| Requirement | Details |
|-------------|---------|
| Google Account | Free, takes 2 minutes |
| Web Browser | Chrome, Firefox, or Edge |
| Internet | Stable connection |
| Storage | ~50 MB free in Google Drive |

**No installation needed!** Everything runs in the cloud.

---

## 🚀 How to Run

### Step 1: Access the Project

🔗 **[Google Drive Project Folder](https://drive.google.com/drive/folders/1xWu2Y8CUfGPaWPrHiFhmOkIqjx9-LifD)**

### Step 2: Open Google Colab

1. Go to: https://colab.research.google.com
2. Click **File → Open notebook → Google Drive**
3. Navigate to the `notebooks/` folder

### Step 3: Run Notebooks in Order

| Order | Notebook | What It Does |
|-------|----------|--------------|
| 1 | `Folder_Setup.ipynb` | Creates folder structure in Drive |
| 2 | `1_Key_Manager.ipynb` | Generates encryption key |
| 3 | `2_Encryption_Simulator.ipynb` | Encrypts test files |
| 4 | `3_Decryption_Recovery.ipynb` | Decrypts and verifies recovery |

---

## 📊 Results

### Performance Metrics

| Metric | Before | During | After |
|--------|--------|-------|-------|
| CPU Usage | 8% | 42% | 9% |
| Memory Usage | 34% | 38% | 35% |
| Encryption Speed | - | 21 files/sec | - |

### File Operations

| Operation | Time (5 files) |
|-----------|---------------|
| Key Generation | 0.01 seconds |
| Encryption | 0.23 seconds |
| Decryption | 0.19 seconds |

---

## 🔪 Cyber Kill Chain Analysis

| Stage | Description |
|-------|-------------|
| Reconnaissance | Scan test_files directory |
| Weaponization | AES encryption script |
| Delivery | Manual execution in Colab |
| Exploitation | Python execution |
| Actions | File encryption + extension change |

---

## 🚨 Indicators of Compromise

| Type | Indicator |
|------|-----------|
| CPU | Spike > 40% without user activity |
| Files | Bulk modifications (>20 files/minute) |
| Extensions | New .encrypted files |
| Disk I/O | Sustained high read/write activity |

---

## 🛡️ Defense Recommendations

### The 3-2-1 Backup Rule

- **3** copies of your data
- **2** different media types
- **1** copy offsite (air-gapped)

### Prevention Strategies

| Layer | Strategy |
|-------|----------|
| People | Security awareness training |
| Process | Regular backups |
| Technology | Endpoint protection, application whitelisting |

---

## 📸 Screenshots

| Stage | Screenshot |
|-------|------------|
| Before Encryption | `screenshots/before_encryption.png` |
| Encryption Running | `screenshots/encryption_running.png` |
| After Encryption | `screenshots/after_encryption.png` |
| After Decryption | `screenshots/after_decryption.png` |

---

## 📁 Google Drive Project

🔗 **[View Project on Google Drive](https://drive.google.com/drive/folders/1xWu2Y8CUfGPaWPrHiFhmOkIqjx9-LifD)**

| Folder | Contents |
|--------|----------|
| `notebooks/` | 4 Colab notebooks |
| `scripts/` | Encryption key |
| `test_files/` | Original test files |
| `encrypted_files/` | Encrypted files |
| `recovered_files/` | Recovered files |
| `screenshots/` | Project screenshots |
| `reports/` | Recovery reports |

---

## 📄 License

This project is licensed under the MIT License.


---

## 👤 Author

| | |
|---|---|
| **Name** | Zahabia Ahmed |
| **GitHub** | [@Zahab163](https://github.com/Zahab163) |
| **Project** | Ransomware Simulation & Decryption |
| **Purpose** | Educational - Cybersecurity |
| **Date** | May 2026 |

---

## 🙏 Acknowledgments

- Cryptography library developers
- Google Colab for free cloud resources
- MITRE ATT&CK Framework
- Lockheed Martin Cyber Kill Chain

---

## ⚠️ Final Reminder

╔══════════════════════════════════════════════════════════╗
║ EDUCATIONAL PURPOSE ONLY ║
╠══════════════════════════════════════════════════════════╣
║ ║
║ ✅ DO: Run only in Google Colab, use test files only ║
║ ║
║ ❌ NEVER: Run on real files or use maliciously ║
║ ║
╚══════════════════════════════════════════════════════════╝

text

---

*Understanding how ransomware works is the first step to building effective defenses.* 






