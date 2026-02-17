# 🧮 GUI-Based Calculator

A simple, user-friendly desktop calculator built with Python. Follow the instructions below to convert the script into a standalone Windows application and create a desktop shortcut.

---

## 🚀 How to Create a Desktop App

Follow these four steps to bundle your script into a single `.exe` file.

### 1. Install PyInstaller
Open your Command Prompt or Terminal and install the necessary packaging tool:
```bash
pip install pyinstaller2. Navigate to Your Folder
Change your directory to where your calculator.py file is located. (Example for Desktop):

Bash
cd %USERPROFILE%\Desktop
3. Build the Executable
Run the following command to create the app.

--onefile: Bundles everything into one file.

--windowed: Ensures the app opens without a background console window.

Bash
pyinstaller --onefile --windowed calculator.py
4. Locate Your App & Create Shortcut
Once the process finishes:

Open the dist folder (created in your project directory).

Right-click calculator.exe.

Select Send to → Desktop (create shortcut).2. Navigate to Your Folder
Change your directory to where your calculator.py file is located. (Example for Desktop):

Bash
cd %USERPROFILE%\Desktop
3. Build the Executable
Run the following command to create the app.

--onefile: Bundles everything into one file.

--windowed: Ensures the app opens without a background console window.

Bash
pyinstaller --onefile --windowed calculator.py
4. Locate Your App & Create Shortcut
Once the process finishes:

Open the dist folder (created in your project directory).

Right-click calculator.exe.

Select Send to → Desktop (create shortcut).
