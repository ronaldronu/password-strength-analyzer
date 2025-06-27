# 🔐 Password Strength Analyzer with Custom Wordlist Generator

## 📌 Project Overview

This project is a Python-based security tool that helps users evaluate the strength of their passwords using the `zxcvbn` algorithm and generates custom wordlists for ethical password testing. It includes both a command-line interface and a GUI built with `tkinter`, allowing easy access for both beginners and cybersecurity learners.

---

## 🛠 Tools & Technologies Used

- Python 3
- [zxcvbn-python](https://pypi.org/project/zxcvbn-python/) (for password strength analysis)
- Tkinter (for GUI)
- Custom modules for:
  - Leetspeak conversion
  - Wordlist generation

---

## 🧪 Features

- Analyze passwords and get feedback on strength (score, suggestions, warnings)
- GUI interface with real-time feedback
- Custom wordlist generation using:
  - Name
  - Pet name
  - Birth year
  - Leetspeak variations
- Outputs wordlist to `sample_wordlist.txt`

---

## 🧰 How to Install

```bash
# Clone the repository
git clone https://github.com/ronaldronu/password-strength-analyzer.git
cd password-strength-analyzer

# Install the required library
pip install zxcvbn-python

