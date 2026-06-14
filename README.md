SIMPLE KEYLOGGER 

Overview

This project is a basic keyboard event logger developed using Python. It captures keyboard inputs, displays them in the terminal, and stores them in a log file with timestamps.

FEATURES
- Captures keyboard events
- Displays pressed keys in real time
- Logs keystrokes to a text file
- Records timestamps for each key press
- Stops logging when the ESC key is pressed

TECHNOLOGIES USED
- Python 3
- pynput library

PROJECT STRUCTURE
keylogger/
│
├── main.py
├── logger.py
├── requirements.txt
├── README.md
├── logs/
│   └── events.txt
└── screenshots/


INSTALLATION
1. Clone the repository

git clone <repository-url>

2. Install dependencies

pip install -r requirements.txt

3. Run the program

py main.py

OUTPUT
Logged keystrokes are stored in:

logs/events.txt

Example:

[2026-06-14 21:51:28] h
[2026-06-14 21:51:29] e
[2026-06-14 21:51:30] l


