# Keylogger

## Description
This is a Python-based keylogger that logs keystrokes and sends reports via email. The project folder is named `keylogger`, and it includes an image file named `duck.jpg`.

## Features
- Logs all keystrokes.
- Supports email reporting via SMTP.
- Runs at a set interval (default: 60 seconds).
- Can be stopped by pressing **Ctrl + C**.

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

4. Stop the keylogger by pressing **Ctrl + C**.

## Creating an Executable File
To create an executable version of the keylogger, follow these steps:

1. Install PyInstaller if not already installed:
   ```sh
   pip install pyinstaller
   ```

2. Navigate to the project directory and run:
   ```sh
   pyinstaller --onefile --noconsole --icon=duck.jpg --name=Duckling.exe keylogger.py
   ```

3. The executable file `Duckling.exe` will be generated in the `dist/` folder.

## Disclaimer
This keylogger is intended for educational and ethical use only. Unauthorized use of keyloggers is illegal and may result in severe consequences. Use responsibly.



