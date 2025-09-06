# Keylogger using Tkinter

## 📜 Project Description

This is a simple keylogger built with Python's Tkinter library. It captures keystrokes entered into the Tkinter window and stores them in a text file (KeyLoggerHistory.txt). The project demonstrates event binding, file handling, and basic GUI concepts in Python.

## ⚡ Features
1. Captures all printable key presses.
2. Stores keystrokes in a log file (KeyLoggerHistory.txt).
3. Ignores special keys like Shift, Ctrl, Alt, etc.
4. Simple, lightweight, and beginner-friendly.
5. Works using Python's built-in libraries (no external dependencies).

## 🛠️ Tech Stack
Python 3.x
Tkinter (GUI library)
String (for character sets)

## 📂 Project Structure
Keylogger-Tkinter/
│
├── keylogger.py          # Main Python script
├── KeyLoggerHistory.txt  # Keystroke log file (auto-created)
└── README.md             # Project documentation

## 🚀 How to Run
Clone the repository:
git (clone https://github.com/MEGAVARSHINI2004/Keylogger-Tkinter.git)
cd Keylogger-Tkinter


## Run the script:
python keylogger.py
Start typing inside the Tkinter window.
Keystrokes will be saved in KeyLoggerHistory.txt.

## 📜 Code Overview
Tkinter Window: Used to capture keyboard events.
Event Binding: Each key press triggers the writeIt() function.
File Handling: Keystrokes are appended to a text file for storage.

## ⚠️ Disclaimer
This project is for educational purposes only.
Do not use it for malicious or illegal activities.

## 💡 Future Improvements
Add timestamp logging for each keystroke.
Include a GUI-based Start/Stop button.
Add support for global keylogging (outside Tkinter window) using libraries like pynput.
