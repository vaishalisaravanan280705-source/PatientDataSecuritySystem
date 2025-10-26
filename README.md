
Project Title: Smart Patient Data Security System


Technology Used: Python, Flask, HTML, CSS, Bootstrap, SQLite Database



1. SOFTWARE REQUIREMENTS
   
• Python (Version 3.8 or above)
• Visual Studio Code / PyCharm / Any Code Editor
• Flask Framework
• pip Package Installer



2. INSTALLATION STEPS


Step 1: Open the project folder in VS Code
Example:
C:\Users\<YourName>\Desktop\SmartPatientSystem

Step 2: Open Terminal in VS Code
Terminal → New Terminal

Step 3: Create Virtual Environment (only first time)
Type:
python -m venv venv

Step 4: Activate the Virtual Environment
Windows:
venv\Scripts\activate

Step 5: Install Required Dependencies
Type:
pip install flask flask_sqlalchemy flask_login bcrypt cryptography

Step 6: Run the Project
Type:
python app.py

Step 7: Open the Application in Web Browser
Go to:
http://127.0.0.1:5000/




3. LOGIN / REGISTRATION

• New users must register first using REGISTER button.
• Then login using the registered email and password.




4. STOPPING THE APPLICATION

• Press CTRL + C in the terminal.
• To deactivate virtual environment:
deactivate



5. TROUBLESHOOTING

• If python not detected → Install Python & restart system
• If dependency missing → Run: pip install <package_name>
• If page not opening → Ensure app is running and correct port is used


