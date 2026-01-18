# 🔐 Password Manager (Python GUI)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Challenge](https://img.shields.io/badge/Challenge-90DaysOfCode-orange)

---
# 📌 Overview

The Password Manager is a Python-based desktop application built using Tkinter that allows users to securely generate, store, and manage passwords for different websites.

This project was developed as part of my #90DaysOfCode journey to strengthen Python fundamentals, practice GUI development, and understand real-world application logic such as input validation, file handling, and clipboard integration.

---
# 🚀 Key Features

🔐 Strong random password generation (letters, numbers, symbols)

📋 Automatic clipboard copy for generated passwords

🖥️ Clean and user-friendly Tkinter GUI

🧾 Secure local storage of credentials in a text file

⚠️ Input validation with confirmation dialogs

🔄 Quick reset and focus handling for efficient data entry

---
# 📁 Project Structure
```
password-manager-tkinter/
│
├── main.py
│   └── Core password manager logic and Tkinter GUI
│
├── logo.png
│   └── Application logo used in the UI
│
├── data.txt
│   └── Locally stored credentials (auto-generated)
│
└── README.md
    └── Project documentation
```
---
# 🛠️ Application Workflow

The application launches with a clean input form.

When the user clicks Generate Password:

A strong random password is created

The password is automatically copied to the clipboard

When the user clicks Add:

Inputs are validated

A confirmation dialog is shown

Data is saved locally in a structured format

The Website and Password fields are then cleared, allowing quick entry of the next record.

This demonstrates practical GUI state handling and real-world desktop application behavior.

---
# ▶️ Execution Instructions

1️⃣ Clone the Repository
```
git clone https://github.com/your-username/password-manager-tkinter.git
cd password-manager-tkinter
```
2️⃣ Run the Application
```
python main.py
```
---
# ⚠️ Important Notes

Python 3.x is required

Tkinter is included with most Python installations

The logo.png file must remain in the same directory as main.py

Credentials are stored locally in data.txt (no cloud or encryption yet)

---
# 🧠 Concepts Demonstrated

Tkinter GUI development

Event-driven programming

Password generation algorithms

Clipboard handling using pyperclip

File handling and data persistence

Input validation and user confirmation dialogs

Clean and readable Python code structure

---
# 🎯 Project Significance

This project simulates a real-world utility application and demonstrates how Python can be used to build practical desktop tools. It highlights core software development skills such as UI design, user interaction handling, and secure data management fundamentals—essential for automation projects and entry-level development roles.

---
# 👨‍💻 Author

Faiz Hasan

BCA Final Year — Graphic Era University

🚀 Python Learner | #90DaysOfCode

---
*“Security starts with good habits — and strong passwords.”*
