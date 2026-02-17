🧮 GUI-Based-Calculator
A simple, functional desktop calculator. Follow these steps to bundle your script into a standalone executable and create a desktop icon.

🚀 Installation & Setup
1. Install PyInstaller
Open your terminal or command prompt and run the following command to install the packaging tool:

Bash
pip install pyinstaller
Wait until the installation finishes before proceeding.

2. Navigate to the Folder
Change your directory to where your calculator.py file is located (e.g., the Desktop):

Bash
cd %USERPROFILE%\Desktop
3. Build the Executable
Run this command to compile your script into a single, windowed application:

Bash
pyinstaller --onefile --windowed calculator.py
4. Locate Your App
Once the process is complete, follow these steps to find your app:

Open the dist folder on your Desktop.

Find the file named calculator.exe.

Right-click the file → Select Send to → Desktop (create shortcut). 
