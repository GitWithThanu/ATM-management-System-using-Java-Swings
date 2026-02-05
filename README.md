🏦 E-Banking System (Java GUI)
A secure, Java-based E-Banking System built using Java Swing (GUI) that simulates real-world banking operations such as user registration, authentication, transactions, loan processing, and account management. The system focuses on security, usability, and practical banking workflows.

📌 Features
🔐 User Registration & Login

Card number and PIN-based authentication

💰 Account Management

Deposit and withdraw money

Balance inquiry

PIN change functionality

🧾 Transaction History

View detailed transaction logs with timestamps

🏧 Cash Withdrawal with Denominations

Withdraw money using selected currency denominations

💳 Loan Management

Apply for different loan types:

Education Loan

Personal Loan

Gold Loan

Home Loan

Vehicle Loan

View active loans with interest details

📁 Persistent Storage

User data stored and updated in a CSV file

🖥️ Interactive GUI

Built using Java Swing and AWT components

🛠️ Technologies Used
Java

Java Swing & AWT (GUI)

File Handling (CSV)

Collections Framework (HashMap, ArrayList)

Event Handling

🧱 Project Structure
User – Handles user details, balance, transactions, loans

ATM – Manages users and CSV persistence

Login – Login GUI

Register – User registration GUI

Home – Main banking dashboard

Loan – Inner class for loan details

ExitPage / SuccessPage – Navigation and exit handling

Main – Application entry point

▶️ How to Run
Clone or download the repository

Open the project in Eclipse / IntelliJ / VS Code

Make sure Java is installed (JDK 8 or above)

Compile and run:

javac Main.java
java Main
Use the GUI to register or login and start banking operations

📂 Data Storage
User data is stored in a file named users.csv

Automatically updated on:

Deposit

Withdrawal

PIN change

Loan application

🔒 Security Considerations
PIN-based authentication

Input validation for transactions and loans

Controlled GUI workflows to prevent invalid operations

🎯 Learning Outcomes
Practical understanding of Java GUI development

Hands-on experience with file handling and data persistence

Application of OOP concepts in a real-world system

Improved problem-solving and system design skills

🚀 Future Enhancements
Password hashing & encryption

Database integration (MySQL)

Admin dashboard

Improved UI/UX design

Multi-user session handling

👩‍💻 Author
Thanusha

