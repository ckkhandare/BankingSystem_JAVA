# BankingSystem_JAVA
OOPs JAVA project

### Problem Statement
Simple Banking system.
Create BankAccount class to store
acctNo(int), customer name, account type (enum : SAVING,CURRENT,FD,LOAN) , creationDate(Date),balance.
Unique ID : acctNo
Add suitable constructor & toString.
Add business logic methods for the following
Withdraw funds
Deposit funds
Transfer Funds
Apply interest (Use Simple interest formula = period*principle*rate /100) 


Validation Rules 
1. In any transaction(eg withdraw or transfer ) or while opening an account ,balance should be always > 1000 
(min balance condition should be checked) Otherwise throw custom exception.
2. Account type must be valid
3. A/C creation date must be in the current financial year.



Store bank account details in a suitable data structure ,which ensures constant time performance
for adding data n retrieving data or for searching.

Supply these options



1.  Create new account
Input : account details

2.  Display  details of all accounts 

3. Get acct summary --- 
Input  : acct number 
o/p --- error via custom exception if account doesn't exist OR  account details

4.Close account
Input  : acct number 
o/p --- error via custom exception if account doesn't exist OR  account details

5. Transfer Funds
Inputs : src acct no, dest acct no , transfer amount

6.Apply interest on all saving type of a/cs.

7. Exit

### Files added
1)BankAccount.java -> This file contains private variables , parameterized constructor, getters setters and tostring
2)AccountType.java -> enum -> contains types of bank accounts
3)CustomExceptions.java -> centralized exception handling
4)BankingValidations.java -> Rules to perform the CRUD operations are added in this file as methods which are then called in the tester
5)BankingTester.java -> Contains the main method 
