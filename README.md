# BankManagementSystem
#Bank Management System

Overview
The Bank Management System is a simple console-based application designed to manage basic banking operations. Users can create accounts, deposit and withdraw funds, check balances, view account details, modify account information, and close accounts.
System Requirements
⦁	Operating System: The system is designed to run on any operating system that supports C++ compilation.
⦁	C++ Compiler: Ensure you have a C++ compiler installed to compile and execute the code.
⦁	Console or Terminal: The application is console-based, so a command-line interface is required for interaction.

Getting Started
⦁	Compile the Code:
Use a C++ compiler to compile the provided code.
(g++ test.cpp -o test)
⦁	Run the Executable:
Execute the compiled program.
(./test.exe)
⦁	Follow On-screen Instructions:
The program will present a menu-driven interface. Follow the on-screen instructions to perform various banking operations.

Features
⦁	Create New Account ('1'): Generates a new account with a random account number.
⦁	Deposit Funds ('2'): Deposits funds into an existing account.
⦁	Withdraw Funds ('3'): Withdraws funds from an existing account.
⦁	Check Balance ('4'): Displays the balance of a specific account.
⦁	View All Account Holders ('5'): Displays details of all account holders (password-protected).
⦁	Close an Account ('6'): Closes an existing account.
⦁	Modify an Account ('7'): Modifies information for an existing account.
⦁	Exit the Program ('8'): Exits the Bank Management System.

Password Protection
⦁	To view all account holders ('5'), a predefined bank password is required. Enter the correct password when prompted. which is "111".
Important Precautions
⦁	Account Number Generation: The system uses a simple random number generator for account numbers. In a real-world scenario, a more robust approach is recommended.
⦁	Data Integrity: Ensure proper data input to avoid unexpected behavior. Follow the specified account balance requirements for savings and credit accounts.
⦁	Security: This application is designed for educational purposes and may lack advanced security features. Do not use it for real banking operations.

Additional Notes
⦁	The code provides a basic structure for a bank management system. Consider additional enhancements for a production environment.


