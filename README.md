#ATM Banking System

A comprehensive C++ console application that simulates ATM banking operations with secure user authentication and transaction processing.

#Features

* User Authentication - Secure login with account number and PIN

* Quick Withdraw - Predefined withdrawal amounts (20, 50, 100, 200, 400, 600, 800, 1000)

* Normal Withdraw - Custom withdrawal amounts (multiples of 5)

* Deposit - Add funds to account with validation

* Balance Check - View current account balance

* Data Persistence - File-based storage of client data

* Transaction Security - Confirmation prompts for all transactions

#Technologies Used

* C++ 11/14

* File I/O operations

* Object-oriented programming

* Data structures (vectors, structs)

* Console-based user interface

#Project Structure

ATM_System( Linked to Bank )/
├── .git/                           # Git version control
├── bin/                            # Compiled binaries
├── obj/                            # Object files
├── main.cpp                        # Main source code (11 KB)
├── Clients.txt                     # Client database file
├── README.md                       # Project documentation
├── ATM_System( Linked to Bank ).cbp  # Code::Blocks project file
└── ATM_System( Linked to Bank ).depend # Code::Blocks dependencies


#How to Use

1 Run the application: codeblocks recommanded

2Login:

-- Enter your account number [002]

-- Enter your PIN code [2222]
check file 

3Main Menu Options:

-- 1 Quick Withdraw - Fast cash withdrawal

-- 2 Normal Withdraw - Custom amount withdrawal

-- 3 Deposit - Add money to account

-- 4 Check Balance - View current balance

-- 5 Logout - Return to login screen


#Core Functions

Login() - User authentication system

ShowMainMenue() - Main navigation interface

ShowQuickWithdrawScreen() - Quick cash withdrawal

ShowNormalWithDrawScreen() - Custom withdrawal

ShowDepositScreen() - Deposit processing

ShowCheckBalanceScreen() - Balance display

LoadCleintsDataFromFile() - Data loading

SaveCleintsDataToFile() - Data persistence


#Security Features

PIN-based authentication

Transaction confirmation prompts

Balance validation before withdrawals

File-based data encryption (through serialization)

#License
This project is open source and available under the MIT License.

#Author
Developed as a C++ learning project demonstrating file I/O, data structures, and console application development.

Note: This is a simulation for educational purposes. Not intended for real banking operations.

