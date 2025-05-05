# BankAccount_management
A simple C++ console application to simulate basic bank account operations like creating an account, adding cash, and withdrawing money.
Data is stored in a local file (Account.txt).

✨ Features
Create a new account with an Account Number and Password

Deposit (Add) cash to an existing account

Withdraw cash after verifying credentials

Basic file handling for data persistence

Simple, user-friendly console interface

🛠️ Technologies Used
C++ (Standard Library)

File Handling (fstream)

Console UI (iostream)

Windows-specific commands (windows.h, system("cls"), Sleep())

📂 How It Works
Open New Account

Enter your account number and password.

Initializes the balance to 0.

Add Cash

Provide your account number.

Deposit cash into your account.

Withdraw Cash

Enter your account number and password.

Withdraw cash if the balance is sufficient.

Exit

Cleanly exit the program.

📁 File Structure
D:/Account.txt — Main data file storing account information.

D:/Account Temp.txt — Temporary file used during updating operations.

⚡ Important:

File paths are hardcoded (D:/). Ensure the D: drive exists, or modify the code to use a more flexible path.

🧠 Concepts Demonstrated
OOP (Object-Oriented Programming): Using a class Account with private attributes and public getter/setter methods.

File Handling: Reading and writing user data to text files.

Basic Error Handling: Checking file open operations.

Console UI: Handling user interaction with simple menus and prompts.

📝 How to Run
Compile the program using a C++ compiler that supports Windows headers (like g++ with MinGW).

bash
Copy
Edit
g++ -o BankAccount BankAccount.cpp
Run the executable:

bash
Copy
Edit
BankAccount.exe
⚠️ Known Limitations
No encryption: Passwords are stored in plain text.

Hardcoded file path (D:/) can cause issues on machines without a D: drive.

No input validation for invalid data types (e.g., letters when expecting numbers).

🚀 Future Improvements
Dynamic file paths or relative paths.

Password encryption.

Better error handling and input validation.

A GUI version using libraries like Qt.

Multi-user login session management.

