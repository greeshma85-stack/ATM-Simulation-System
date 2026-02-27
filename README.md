ATM Simulation System (Java)
A console-based ATM simulation application built using Java, demonstrating core programming concepts such as OOP, control flow, loops, and user input handling.
This project simulates basic ATM functionalities like depositing money, withdrawing money, and checking account balance.

Features
Deposit money into account
Withdraw money with balance validation
View current account balance
Menu-driven interface
Encapsulation for secure balance handling

Technologies Used
Language: Java

Concepts:
Object-Oriented Programming (OOP)
Classes & Objects
Encapsulation
Conditional Statements
Utilities: Scanner for user input

📂 Project Structure
ATM-Simulation/
│
├── Main.java
└── README.md
▶️ How to Run the Program

Clone the repository:
git clone https://github.com/greeshma85-stack/ATM-Simulation.git

Navigate to the project directory:
cd ATM-Simulation
Compile the program:
javac Main.java

Run the program:
java Main

Program Flow
User is shown ATM menu options
User selects an operation
Program performs the selected action
Menu repeats until user chooses Exit

Key Concepts Demonstrated
Encapsulation: Account balance is private and accessed only through methods
Menu-driven logic: Uses switch-case for user options
Input validation: Prevents withdrawal when balance is insufficient
Infinite loop control: Program exits safely using System.exit(0)

Sample Output
1.Deposite
2.Withdraw
3.Show Balance
4.Exit

Enter the choice: 1
Enter the amount to be deposited:
5000
Amount added successfully

Future Enhancements
Add PIN authentication
Store transaction history
Connect to a database (MySQL)
Convert to GUI-based application

Author
Greeshma G
BTech CSE (AI & ML) Student
Aspiring Java & Software Developer

Why This Project?
This project was built to strengthen Java fundamentals and understand how real-world systems like ATMs work using basic programming logic.
