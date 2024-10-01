# A C++ Password Manager and Generator

  This is a simple command-line password manager and generator written in C++. It allows you to store your passwords securely and generate random, strong passwords.

## Features
- Store and manage passwords for different accounts
- Generate random passwords of a specified length (with the option to copy to the clipboard)
- View a list of all saved accounts and passwords
- Encrypt passwords for added security

## Getting Started

### Prerequisites:

  To run this program, you must have a C++ compiler installed on your computer.

### Installation

- Clone this repository to your local machine using git clone https://github.com/yourusername/PasswordManager.git
- Compile the program using your C++ compiler.
- Run the executable file.

## Usage
When you run the program, you will be presented with a menu of options:

Password Manager Menu:
1. Login
2. Create an account
3. Get a strong one-time password
4. Exit

## Create an account
  To create, select option 2 and provide a desired username and master password. This will be your master key to view your saved passwords. This master key is securely saved as a hash in the database.

## Generate a strong one-time password
  Choose option 3 from the menu to generate a new password and enter the desired password length. The program will generate a random, strong password of the specified length and display it on the screen.

## Security
This program encrypts the saved passwords using a simple encrypting algorithm. While this provides some level of security, it is not recommended for storing highly sensitive passwords.

## Contributors
  The contributors to this project is: Darsh Dujrai
