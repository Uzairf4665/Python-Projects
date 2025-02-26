🚀 SSH Brute Force Script (For Educational & Testing Purposes Only)
This script attempts to brute-force SSH authentication using a list of common passwords. It utilizes the paramiko and pwn libraries to automate SSH login attempts.

⚠️ Disclaimer
This project is intended for educational and ethical penetration testing purposes only. Unauthorized access to systems is illegal. Use this script only on systems you own or have explicit permission to test.

🛠 Features
✅ Attempts SSH login using a wordlist
✅ Uses paramiko for secure SSH connections
✅ Stops execution once a valid password is found
✅ Handles authentication exceptions gracefully

📌 Requirements
Python 3.x
pwn module (pip install pwntools)
paramiko module (pip install paramiko)
A wordlist file (ssh-common-passwords.txt)
🚀 Usage
Clone the repository:
bash
Copy
Edit
git clone https://github.com/yourusername/ssh-brute-force.git
cd ssh-brute-force
Install dependencies:
bash
Copy
Edit
pip install paramiko pwntools
Run the script:
bash
Copy
Edit
python ssh_bruteforce.py
Modify host and username variables to match your target system.
📝 License
This project is licensed under the MIT License.
