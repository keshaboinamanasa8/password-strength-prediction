# Password Strength Prediction Using Python

## 1. Project Overview

Password Strength Prediction is a cybersecurity project developed using Python to evaluate the strength of user-created passwords. The system analyzes password characteristics and classifies passwords as **Weak, Medium, or Strong**. It also provides suggestions to help users create more secure passwords and protect their digital accounts.

## 2. Objectives

- Evaluate password strength based on predefined rules.
- Analyze password length and character diversity.
- Identify common passwords and repeated character patterns.
- Classify passwords as Weak, Medium, or Strong.
- Provide suggestions to improve password security.
- Promote cybersecurity awareness and safe password practices.

## 3. Technologies Used

- **Programming Language:** Python 3
- **Libraries and Modules:** `re`, `string`, `getpass`
- **IDE:** Visual Studio Code or Python IDLE
- **Operating System:** Windows, Linux, or macOS

## 4. Features

- Password length checking
- Uppercase and lowercase letter detection
- Number and special character detection
- Basic repeated-character detection
- Detection of selected common passwords
- Password strength classification
- Suggestions for password improvement

## 5. Project Structure

```text
Password-Strength-Prediction/
│
├── password_strength.py
└── README.md
```

## 6. Installation

**Step 1:** Install Python 3 from https://www.python.org/downloads/

**Step 2:** Download or clone the project repository.

**Step 3:** Open the project folder in Visual Studio Code or Python IDLE.

The project uses Python's standard library, so no additional packages are required for the basic version.

## 7. How to Run

Open a terminal in the project folder and execute:

```bash
python password_strength.py
```

On some systems, use:

```bash
python3 password_strength.py
```

Enter a password when prompted. The program will display its estimated strength and suggestions for improvement.

## 8. Sample Output

```text
Enter your password: [password hidden]

Password Strength: Strong

No basic improvements suggested.
```

*Note: This is an illustrative example. Actual output depends on the password entered and the evaluation rules implemented in the program.*

## 9. Applications

- Cybersecurity education
- Password security awareness
- Basic password validation systems
- Student programming projects
- Introduction to secure authentication practices

## 10. Advantages

- Simple and easy to use
- Requires no external libraries
- Provides immediate feedback
- Helps users identify basic password weaknesses
- Suitable for beginners learning Python and cybersecurity

## 11. Limitations

- Uses predefined rules to estimate password strength.
- Does not reliably detect every predictable password.
- Does not verify whether a password has appeared in a data breach.
- A strong classification does not guarantee complete password security.

## 12. Future Enhancements

- Develop a graphical user interface.
- Add a visual password-strength meter.
- Integrate an advanced password-strength estimation library.
- Improve detection of dictionary words and predictable sequences.
- Add privacy-preserving checks for compromised passwords.

## 13. Conclusion

The Password Strength Prediction project demonstrates how Python can be used to evaluate password characteristics and promote better cybersecurity practices. By classifying passwords and providing improvement suggestions, the system encourages users to create longer, unique, and less predictable passwords.

## 14. References

1. Python Documentation: https://docs.python.org/3/
2. Python Regular Expressions: https://docs.python.org/3/library/re.html
3. NIST Digital Identity Guidelines: https://pages.nist.gov/800-63-4/sp800-63b.html
4. OWASP Authentication Cheat Sheet: https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html

---

**Project Title:** Password Strength Prediction Using Python  
**Domain:** Cybersecurity  
**Project Type:** Academic / Project-Based Learning (PBL)
