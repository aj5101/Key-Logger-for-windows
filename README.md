# 🛡️ Windows Keylogger – Python Project

This project is a basic **keylogger** written in Python, designed for educational and ethical hacking purposes. It records keystrokes on a **Windows** system and stores them locally in a log file.

> ⚠️ **Disclaimer**: This tool is for educational and authorized testing only. Unauthorized use of a keylogger is illegal and unethical.

---

## 🧠 What It Does

- Captures all keystrokes made on the system
- Logs them into a `.txt` file
- Can be extended for stealth mode or email delivery

---

## 📁 Project Files

- `keylogger.py`: The main Python script that logs keystrokes
- `log.txt`: Output file where keystrokes are recorded (auto-created)

---

## ⚙️ Requirements

- Python 3.x
- Windows OS (Tested on Windows 10)
- Required Python library:
  ```bash
  pip install pynput
🛠️ How to Run

1. Run Script
python keylogger.py
This will start capturing keystrokes and store them in log.txt in the same directory.

⌛ You may need to wait a few seconds for log updates.
2. (Optional) Convert to Executable
If you want to run this on another Windows machine without Python installed, use pyinstaller:

pip install pyinstaller
pyinstaller keylogger.py --onefile --noconsole
The compiled .exe will be found inside the dist/ folder.
--noconsole hides the terminal window to run stealthily.
🔐 Stealth Tips (Ethical Use Only)

Hide log.txt using file attributes
Add code to email logs periodically (for learning purposes)
Use task scheduler or registry entry to run on startup (learn responsibly)
⚠️ Important Notes

Running this script may trigger antivirus software.
It will not work on Linux or macOS unless modified.
You must have permission to use this on any device that isn’t your own.
📜 Legal Disclaimer

This software is intended solely for authorized security research, educational use, or testing in environments where you have explicit permission.

🛑 Never use keyloggers on devices or networks you do not own or have legal access to. Doing so is illegal and unethical.
✅ Sample Use Cases (Ethical Only)

Penetration testing on lab environments
Building understanding of cybersecurity vulnerabilities
Creating custom logging for usability testing
