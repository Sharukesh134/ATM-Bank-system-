ATM Banking System in Java

Description

The ATM Banking System is a simple console-based application developed in Java that simulates the core functionalities of an ATM. The system allows users to perform various banking operations such as:

Checking balance
Depositing money
Withdrawing money
Transferring money between accounts
Users authenticate themselves by entering their account number and PIN. After successful authentication, they can perform different operations as per their choice. The system validates the operations, ensuring users cannot withdraw more than their available balance and can only transfer funds to valid accounts.

Features

User Authentication: The user must enter their correct account number and PIN to gain access to their account.
Menu-Driven Interface: After successful login, the user is presented with a menu that allows them to choose between different banking operations.
Balance Check: Users can view their current account balance.
Deposit Money: Users can deposit money into their account, which increases the balance.
Withdraw Money: Users can withdraw money, with the system ensuring they have enough balance.
Transfer Money: Users can transfer money to another account, with updates to both accounts.
Exit Option: Users can exit the system when they are finished with their operations.
Requirements

Java 8 or later is required to run the program.
Basic knowledge of Java programming (such as control structures, input/output handling, and methods).
How to Run the Program

Clone or Download the repository containing the Java file.

Open the program in an Integrated Development Environment (IDE) such as IntelliJ IDEA, Eclipse, or use a simple text editor.

Compile and Run the program. You can compile using the following command:

bash
Copy code
javac ATMSystem.java
java ATMSystem
Follow the prompts to enter the account number and PIN. Then, you can choose from the available operations (Check Balance, Deposit, Withdraw, Transfer, Exit).

Example

yaml
Copy code
Enter your account number: 123456789
Enter your PIN: 1234

Select an operation:
1. Check Balance
2. Deposit Money
3. Withdraw Money
4. Transfer Money
5. Exit
Enter choice: 1
Your balance is: 5000.0

Select an operation:
1. Check Balance
2. Deposit Money
3. Withdraw Money
4. Transfer Money
5. Exit
Enter choice: 2
Enter the amount to deposit: 1500
Deposit successful. Your new balance is: 6500.0
File Structure

ATMSystem.java: Main program file containing the ATM Banking System's logic.
README.md: This file containing instructions and details about the ATM system.
Conclusion

This ATM Banking System provides a simple yet effective way to simulate basic banking operations. It can be expanded to include more features like account creation, error handling, and data persistence. The system demonstrates the usage of Java basics such as input handling, arithmetic operations, and object-oriented programming principles like methods and variables.










