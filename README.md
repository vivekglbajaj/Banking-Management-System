BankAccount Encapsulation Example
This project demonstrates the Encapsulation concept in Java by designing a BankAccount class. The balance attribute is kept private, and methods are provided to perform secure operations like depositing, withdrawing, and checking the balance.

📝 About the Project
The goal of this project is to showcase how Encapsulation can secure sensitive data and enforce rules for data manipulation.
Key highlights include:

Keeping the balance attribute private.
Providing controlled access to modify or retrieve the balance through methods.
Implementing logic to prevent invalid transactions (e.g., withdrawals exceeding the balance).
🚀 Features
Encapsulation: The balance attribute is private, accessible only via public methods.
Secure Transactions:
Deposit funds into the account.
Withdraw funds with validation to prevent overdrafts.
Check the current balance securely.
Input Validation: Ensures no invalid transactions.
🛠️ Technology Stack
Programming Language: Java
IDE: Any Java-supported IDE (e.g., IntelliJ IDEA, Eclipse, VS Code)
📂 Project Structure
graphql
Copy
Edit
BankAccountEncapsulation/
├── BankAccount.java       # Contains the BankAccount class with encapsulation
├── Main.java              # Entry point to demonstrate BankAccount operations
└── README.md              # Project documentation

How to Run the Project
Prerequisites
Install the Java Development Kit (JDK) version 8 or higher.
Set up an IDE or text editor to compile and run Java code.
Steps to Run
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/your-username/BankAccountEncapsulation.git
cd BankAccountEncapsulation
Compile the Code:

bash
Copy
Edit
javac BankAccount.java Main.java
Run the Program:

bash
Copy
Edit
java Main
