# CS-Project
🏦 Simple Command Line Banking System

=======================================

A robust, menu-driven banking application built with Python. This project simulates real-world banking logic using core programming concepts like Data Structures (Lists of Dictionaries), Input Validation, and Exception Handling.

📖 Overview

The Simple Command Line Banking System allows users to create accounts, manage funds, and perform secure transactions like deposits, withdrawals, and transfers.

Unlike complex banking software that relies on graphical interfaces, this project focuses on the backend logic and data manipulation that powers financial systems. It is designed to be crash-resistant, ensuring a smooth user experience even when invalid data is entered.

✨ Features

🆕 Account Creation: Open a new account with a unique 4-digit Account ID, Name, and Initial Deposit.

🔒 Secure Authentication: Access financial operations only after verifying Account Number and PIN.

💸 Real-time Balance: View your current holdings formatted in Indian Rupee (₹).

💰 Deposit & Withdraw: Add or remove funds with strict validation (prevents negative deposits or overdrafts).

🔁 Fund Transfers: Transfer money between users safely.

🛡️ Smart Error Handling: A custom "Retry Mechanism" prevents the program from crashing if a user inputs text instead of numbers.

🛠️ Technologies Used

Language: Python 3.x

Core Concepts:

Lists & Dictionaries (Data Storage)

Functions & Modularity

Control Flow (Loops, Conditionals)

Exception Handling (try / except)

🚀 How to Install & Run

Clone the Repository (or download the ZIP):

git clone [https://github.com/your-username/simple-cli-bank.git](https://github.com/your-username/simple-cli-bank.git)


Navigate to the Project Directory:

cd simple-cli-bank


Run the Application:

python banking_system_simple.py


🧪 Instructions for Testing

You can test the system using the following scenarios:

🟢 Positive Testing (Happy Path)

Select Option 1 to create a user (e.g., Name: "Rahul", Deposit: 5000, PIN: 1234).

Login and use Option 3 to deposit ₹ 1000.

Use Option 5 to transfer ₹ 500 to another account.

Verify that the Balance matches your calculations.

🔴 Negative Testing (Edge Cases)

Input Validation: When asked for an amount, type "Five Hundred" (text). The system should warn you and give 3 retries.

Overdraft Check: Try to withdraw more money than you have (e.g., withdraw ₹ 10,000 from a ₹ 5,000 balance). The system should deny the transaction.

Self-Transfer: Try to transfer money to your own account number. The system should block it.

📸 Screenshots / Demo

1. Main Menu Interface

==================================================
Simple Command Line Bank
==================================================
Please choose an option:
1. Create New Account
2. View Balance
3. Deposit Funds
4. Withdraw Funds
5. Transfer Funds
6. Exit System
--------------------------------------------------


2. Successful Transaction

--- Deposit to Account 8492 ---
Enter amount to deposit: ₹ 1500

Successfully deposited ₹ 1,500.00.
New Balance: ₹ 6,500.00


👤 Author

Student Name: [Your Name]

Subject: Computer Science / Python Programming