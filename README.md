# ATM System

A console-based ATM System developed using C++.

This project simulates basic ATM operations and manages client account information using a text file.

## Features

* Secure login using Account Number and PIN Code
* Quick Withdraw
* Normal Withdraw
* Deposit
* Check Account Balance
* Logout
* Client data storage using a text file
* Balance updates after transactions

## ATM Operations

After successful login, the user can access the following options:

1. Quick Withdraw
2. Normal Withdraw
3. Deposit
4. Check Balance
5. Logout

## Quick Withdraw

The system provides predefined withdrawal amounts:

* 20
* 50
* 100
* 200
* 400
* 600
* 800
* 1000

The user can also exit the Quick Withdraw screen.

## Normal Withdraw

The user can enter a custom withdrawal amount.

The amount must be a multiple of 5.

The system also checks whether the requested amount exceeds the current account balance.

## Deposit

The user can enter a deposit amount.

The system requires the amount to be greater than zero before processing the transaction.

## Check Balance

The current account balance is displayed after the user selects the Check Balance option.

## Login System

The user logs in using:

* Account Number
* PIN Code

The system validates the entered credentials against the client data stored in `Clients.txt`.

## Data Storage

Client information is stored in:

```text
Clients.txt
```

Each client record contains:

* Account Number
* PIN Code
* Name
* Phone
* Account Balance

The program converts client records between text lines and C++ structures for reading and writing data.

## Technologies

* C++
* File Handling
* Structures
* Vectors
* Functions
* Enums
* String Manipulation
* Input Validation

## Project Structure

```text
ATM-System/
│
├── ATMsystem.cpp
├── ATMsystem.slnx
├── ATMsystem.vcxproj
├── Clients.txt
├── .gitignore
└── README.md
```

## How to Run

### Using Visual Studio

1. Clone the repository:

```bash
git clone https://github.com/USERNAME/ATM-System.git
```

2. Open:

```text
ATMsystem.slnx
```

3. Select the required platform, such as `x64` or `x86`.

4. Build the project.

5. Run the application.

## Example Login

Use an account and PIN available in `Clients.txt`.

```text
Account Number: XXXXX
PIN: XXXX
```

After successful authentication, the ATM Main Menu will be displayed.

## Learning Purpose

This project was developed as a practical application of C++ programming concepts, including:

* Structures
* Functions
* Vectors
* File Handling
* String Manipulation
* Enums
* References
* Input Validation
* Basic data management

## Author

Abdulrahman Aghbash

GitHub: `ABDRHMA41`
