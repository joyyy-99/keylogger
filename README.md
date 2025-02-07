# Keylogger - Duckling.exe

## Description
This is a Python-based keylogger that logs keystrokes and sends reports via email. The script was converted into an executable file named **Duckling.exe**, which is located in the `dist` folder. 

## Features
- Logs all keystrokes.
- Supports email reporting via SMTP.
- Runs at a set interval (default: 60 seconds).
- Converted into an executable file for ease of use.

## Requirements
- Python 3.x
- Required Libraries:
  - `keyboard`
  - `smtplib`
  - `threading`
  - `datetime`
  - `email.mime`

## Setup & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/joyyy-99/keylogger.git
   cd keylogger
   ```

2. Install dependencies:
   ```sh
   pip install keyboard
   ```

3. Run the script:
   ```sh
   python keylogger.py
   ```

4. To use the executable version, navigate to the `dist` folder and run:
   ```sh
   ./Duckling.exe  # or double-click Duckling.exe
   ```

## Converting to .exe
The script was converted into an executable using PyInstaller:
```sh
pyinstaller --onefile --noconsole --icon=duck.jpg keylogger.py
```

## Disclaimer
This keylogger is intended for educational and ethical use only. Unauthorized use of keyloggers is illegal and may result in severe consequences. Use responsibly.



