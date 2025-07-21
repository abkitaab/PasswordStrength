
# 🔐 Password Strength Checker on Windows 11

## 🎯 Project Overview

This project is a *Password Strength Checker* built for use on *Windows 11* systems. It allows users to input a password and receive real-time feedback on its strength — identifying weak, moderate, or strong passwords using custom rules and metrics.

---

## 🧰 Tools & Environment

| Component            | Specification                             |
| -------------------- | ----------------------------------------- |
| *Operating System* | Windows 11                                |
| *Programming Lang.*| Python 3.x                                |
| *Libraries Used*   | tkinter, re, string, colorama     |
| *Editor*           | VS Code / IDLE / PyCharm (recommended)    |

---

🔍 Scanning Workflow
✅ Step 1: Password Input
The user enters a password through:

A Command Line Interface (CLI), or

A Graphical Interface (GUI) (optional version using tkinter).

✅ Step 2: Rule-Based Validation
The entered password is checked using the following validation rules:

Validation Rule	Description
Length Check	Minimum 8 characters
Uppercase Letter	Must include at least one capital letter (A–Z)
Lowercase Letter	Must include at least one lowercase letter (a–z)
Numeric Digit	At least one number (0–9)
Special Character	At least one symbol (@, #, $, !, etc.)
Common Password Filter	Detects weak passwords like 123456, password, etc.

✅ Step 3: Scoring & Strength Evaluation
Each rule met contributes to a total score.

The final score determines the password's strength:

Score Range	Strength Rating
0–2	Weak ❌
3–4	Moderate ⚠
5–6	Strong ✅

✅ Step 4: Feedback Output
In CLI, results are displayed with colored text using colorama.

In GUI, results are shown in a color-coded message box or label.

✅ Step 4: Screenshot
Below is a sample screenshot of the tool running in terminal:

(![Password Checker Screenshot](passwordstrength.png))

---

## 🚧 Challenges & Resolutions

| Challenge                       | Mitigation Strategy                         |
| ------------------------------- | --------------------------------------------|
| Windows cmd encoding issue      | Used colorama for ANSI support              |
| Regex false positives           | Refined patterns with testing               |
| GUI freezing on long input      | Added event debouncing in tkinter           |

---

## 📘 Key Takeaways

* Developed a functional password strength checker compatible with Windows 11.

* Gained practical experience with Python string handling, regex, and input validation techniques.

* Learned how to evaluate password complexity based on industry-recommended rules (length, character variety, and uniqueness).

* Implemented color-coded feedback in the command line using colorama for better user experience.

* Explored GUI creation with tkinter, enhancing the project with a visual interface.

* Understood the importance of secure password practices and how to detect weak patterns commonly used by users.

---

## 🚀 Future Enhancements

* Add password breach check using HaveIBeenPwned API

* Implement clipboard blocker for secure entry

* Convert into standalone .exe using pyinstaller

---

| Name                 | GitHub Username       | 
|----------------------|-----------------------|
| *Srijeeta Goswami* | @Srijeeta1907       |
| *Ankita Biswas*    | @ankitaab           |
| *Sristi Das*       | @SRISTI-25          |
| *Shreya Mondal*    | @shreyamondal409    | 

---

## 🙏 Acknowledgment

Special thanks to [Biswadeb Mukherjee](https://github.com/official-biswadeb941) for technical guidance and strategic input throughout this lab simulation. His expertise in offensive security, enumeration tactics, and adversarial tooling played a vital role in this project’s successful execution.

---

## 🗂 Project Snapshot

| Field                  | Description                                                      |
| ---------------------- | ---------------------------------------------------------------- |
| *Status*             | ✅Completed                                                              
| *Version*            | 1.0                                                              |
| *Completion Date*    | 17 July 2025                                                     |
| *Domain*             | Passsword Strength checker                                       |
| *Primary Tools*      | VS code, Windows 11                                              |
| *Objective Achieved* | Successfully checked the strength of password                    |
| *Next Phase*         | Workflow automation and toolchain expansion                      |

---

## 📎 References & Resources

* 📘 [Nmap Official Documentation](https://nmap.org/book/man.html)
* 📓 [Comprehensive Nmap Command Guide (PDF)](https://archive.org/details/comprehensive-nmap-command-guide)
* 💡 [TryHackMe: Nmap Room](https://tryhackme.com/room/nmap)

---

## 📁 Directory Structure


password-checker/
├── README.md
├── password_checker.py
├── gui_version.py
├── requirements.txt
└── screenshots/
    └── sample_output.png


---

## 👤 Author

**Ankita Biswas
| Name                 | GitHub Username       |
|----------------------|-----------------------|
| *Srijeeta Goswami* | @Srijeeta1907       |                                     
| *Ankita Biswas*    | @ankitaab           |  
| *Sristi Das*       | @SRISTI-25          |  
| *Shreya Mondal*    | @shreyamondal409    | 
-

• [GitHub](https://github.com/Srijeeta1907/SRIJEE.git) 

> “Security begins with strong passwords.”