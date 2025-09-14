***

# 🛡️ Webcam Spyware Security App

A simple and secure **Tkinter-based desktop application** to manage webcam access on your Windows system. Protect your privacy by enabling or disabling your webcam via Windows privacy settings with password protection and activity logging.

***

## 🚀 Features

- 🔒 Set and verify a password to control access to webcam settings  
- 🎛️ Enable or disable the webcam by opening Windows' Camera Privacy Settings  
- 📝 Maintain an activity log of all enable/disable actions and password unlocks  
- 📖 View the activity log from within the app  
- 💻 User-friendly GUI built with Tkinter  

***

## 🛠️ Prerequisites

- Python 3.7
- Windows operating system  
- Tkinter (usually bundled with Python)  

***

## Installation

1. Download or clone this repository.

2. Install required packages (if needed):

```bash
pip install tk
```

*Note: Tkinter comes pre-installed with most Python distributions.*  

***

## Usage

1. Run the application:

```bash
python web.py
```

2. Set a secure password (8-64 characters) using the "Set Password" button.

3. Use the "Enable Camera" and "Disable Camera" buttons to open Camera Privacy Settings in Windows. You will be prompted to adjust the camera permission manually.

4. Use the "View Activity Log" button to see a record of all actions performed (enable/disable camera or password verification).

5. Each sensitive action will ask for the password you set, ensuring authorized access only.

***

## How It Works

- The app uses **Tkinter** to create a simple GUI for managing webcam permissions.
- Passwords restrict access to enabling/disabling the webcam and viewing logs.
- On click, the app opens Windows Camera Privacy Settings (`ms-settings:privacy-webcam`) where the user can manually allow or deny camera access.
- Each action (enable/disable/log view/unlock) is logged with a timestamp into `activity_log.txt`.
- Password input dialogs ensure safety before any action is executed.

***

## File Details

- `web.py`: Contains the full source code of the Webcam Spyware Security App using Tkinter.

***

## License

MIT License © 2025 Praneeth N.

See the [LICENSE](LICENSE) file for details.


***

Enjoy enhanced webcam privacy and control with this lightweight, secure desktop app! 🔐📹

***

This README matches the structure and functionality of your provided `web.py` code and explains usage clearly.
