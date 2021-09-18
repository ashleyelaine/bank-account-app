# Bank Account App
A sample bank account app to handle new customer account requests written in Java.

## This application does the following: 
- Reads a .csv file of names, social security numbers, account type, and initial deposit
- Uses proper data stucture to hold all these accounts
- Both Savings and Checkings accounts have the following properties: 
  - deposit()
  - withdraw()
  - transfer()
  - showInfo()
  - 11 Digit Account Number (generated with 1 or 2 depending on Savings or Checking, last two digits of SSN, unique 5-digit number, and a random 3-digit number)
  - Savings Acount holders are given Safety Deposit Box, identified by a 3-digit number and accessed with a 4 digit code
  - Checking Account holders are assigned a Depit Card with a 12-digit number and 4 digit PIN
  - Will use an interface that determines the base interest rate.
  - The ShowInfo method should reveal relevant account information

## Learning Objectives
- To develop a robust application architecture
- Learn when to use abstract classes and abstract methods
- Use an interface API to receive information from a developer's application
- Explore constructors deeper and user the super() keyword
- Explore access modifiers and when to use public, private, or protected
- Read data from a file and store in an appropriate data structure
- Generate random number and work the String API


