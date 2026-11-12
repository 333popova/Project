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
4. Error handling.
## Technologies Used
1. Programming language Python.
2. Library: hashlib (used to calculate SHA-256 hashes)
## How to Run
1. Open the GitHub repository https://github.com/333popova/Project.
2. Find File_Integrity_Verification.ipynb
3. Open the notebook using Google Colab (you can use the Open in Colab option if available).
4. In Google Colab, upload the test file in the Colab session before running the program otherwise, the program may display: File not found!
5. Run the code cells in order.
## How to Use
The menu has four options:
1. Calculate file hash (SHA-256): calculates and displays the file's SHA-256 hash or displays an error message if a problem occurs.
2. Save original hash: saves the file's SHA-256 hash and displays a success or error message.
3. Verify the integrity: verifies and displays whether the file is unchanged or has been modified (compares the original hash with the newly calculated hash); displays an error message if a problem occurs.
4. Exit: exits the program.

