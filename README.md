A simple yet effective Python tool to check the strength of a password based on common security requirements.

📌 Project Overview
This project is a command-line password strength checker built with Python. It evaluates a password against five essential security criteria and provides instant feedback on whether the password is **Weak**, **Medium**, or **Strong**.

The goal is to help users understand what makes a password secure and encourage better password hygiene.

🎯 Features
- **Real-time checking** – Each password is checked immediately after entry.
- **Five security requirements** – Length, digit, uppercase, lowercase, and special character.
- **Clear feedback** – Returns a specific message indicating what is missing.
- **Exit command** – Type `exit` to quit the tool.
- **Simple and lightweight** – No external libraries required (only `re` from standard library).

---

## 📋 Password Requirements

| Requirement | Description |
|-------------|-------------|
| **Length** | At least 8 characters |
| **Digit** | At least one number (0–9) |
| **Uppercase** | At least one uppercase letter (A–Z) |
| **Lowercase** | At least one lowercase letter (a–z) |
| **Special Character** | At least one of: `!@#$%^&*(){}<>.?` |

If any requirement is not met, the tool returns a **Weak** or **Medium** message specifying the missing criterion. Only when all requirements are satisfied does it return **Strong**.

---

## ⚙️ Requirements

- Python 3.6 or higher
- No external packages needed

---

## 🚀 How to Run

1. Clone the repository or download the `password_checker.py` file.
2. Open a terminal/command prompt and navigate to the project folder.
3. Run the script:

```bash
python password_checker.py
