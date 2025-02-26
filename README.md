# SSH Brute Force Attack Script 🚀

This script attempts to brute-force an SSH login using a list of common passwords. It utilizes the `paramiko` library for SSH connections and iterates through a password list to find a valid credential.

## 📜 Features
- Tries multiple passwords from a wordlist (`ssh-common-passwords.txt`).
- Uses `paramiko` for SSH authentication.
- Prints valid credentials upon success.
- Handles authentication failures gracefully.

## 🛠️ Requirements
- Python 3.x
- `paramiko` library (install via `pip install paramiko`)
- A wordlist (`ssh-common-passwords.txt`)

## 📌 Usage
### 1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repo-name.git
   cd repo-name

## Install Dependencies:
```bash
pip install paramiko
```

## Run the Script:
```bash
python ssh_bruteforce.py
```
### ⚠️ Disclaimer
This script is for educational purposes only. Unauthorized use against systems without permission is illegal and unethical. The author is not responsible for any misuse.
