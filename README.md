# Project File Integrity Verification
## Authors Group D
1. Cian Kavanagh
2. Tetiana Popova
## Project Description
Use Case Scenario for Cryptography
15. File Integrity Verification:
Develop a tool to calculate and verify SHA-256 hash values of files, ensuring their integrity during transfer or storage. It saves the original hash and compares it with the current hash to determine whether the file is unchanged or has been changed.
## Features
1. A function to calculate the file's SHA-256 hash.
2. A function to save the file's SHA-256 hash.
3. A function to verify whether the file has been modified.
4. Multiple file verification.
5. Verification history.
6. Error handling.
## Technologies Used
1. Programming language Python.
2. Library: hashlib (used to calculate SHA-256 hashes).
3. csv: used to save verification history.
4. os: used to check whether files exist.
5. datetime: used to record the date and time of verification.
All libraries are included in Python's standart library.
## Generated Files
The application automatically creates:
1. ".sha256" files: store the original SHA-256 hash of each file.
2. "verification_history.csv": stores verification results, including filenames, dates and verification statuses.
## How to Run
### Option 1: Google Colab
1. Open the GitHub repository https://github.com/333popova/Project.
2. Find File_Integrity_Verification_Colab.ipynb
3. Open the notebook using Google Colab (you can use the Open in Colab option if available).
4. In Google Colab, upload the test file in the Colab session before running the program, otherwise the program may display: File not found!
5. Run the code cells in order after uploading the test files.
6. Follow the menu instructions to use the application.
### Option 2: Visual Studio Code (VS Code)
1. Open the GitHub repository https://github.com/333popova/Project.
2. Click the green Code button and copy the HTTPS repository link.
3. Open Visual Studio Code.
4. Install the Python and Jupyter extensions if they are not already installed.
5. Press Ctrl+Shift+P to open Command Palette.
6. Search for and select Git: Clone.
7. Paste the copied GitHub repository link and press Enter.
8. Choose a folder on your computer to save the project.
9. Click Open when VS Code asks whether you want to open the cloned repository.
10. Find and open File_Integrity_Verification.ipynb
11. Select a Python kernel if prompted.
12. Upload or place your test files in the project folder.
13. Run the code cells to start the application.
14. Follow the menu instructions to use the application.
## How to Use
The menu has six options:
1. Calculate file hash (SHA-256): calculates and displays the file's SHA-256 hash or displays an error message if a problem occurs.
2. Save original hash: saves the file's SHA-256 hash and displays a success or error message.
3. Verify the integrity: verifies and displays whether the file is unchanged or has been modified (compares the original hash with the newly calculated hash); displays an error message if a problem occurs.
4. Verify multiple files: allows users to enter multiple filenames separated by commas. Verifies and displays whether each file is unchanged or has been modified (compares the original hash with the newly calculated hash).
5. View verification history: displays all previous verification results, including filenames, dates and integrity statuses.
6. Exit: exits the program.

