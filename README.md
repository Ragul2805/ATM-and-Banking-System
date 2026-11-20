# ATM AND BANKING SYSTEM

## Reg No:212225230221
 
## Name:Ragul D

## Date:20/11/2026

## AIM:

To design and develop an ATM and Banking System using StarUML by representing its functionalities and interactions through UML diagrams.

## PROBLEM STATEMENT:

1. Customers need a convenient way to access banking services without visiting the bank.
2. Manual banking operations consume more time and increase workload.
3. Customers require secure authentication to access their bank accounts.
4. ATM systems should support basic banking transactions such as cash withdrawal and balance enquiry.
5. Customers need access to banking services 24/7.
6. The system should provide reliable and efficient transaction processing.
7. The ATM should validate the user's PIN before allowing transactions.
8. The system should check the available account balance before withdrawing money.
9. The system should generate receipts for completed transactions.
10. The system should ensure secure communication between the ATM and the bank server.

## UML DIAGRAMS

### 1. USE CASE DIAGRAM

A Use Case Diagram represents the interaction between users and the ATM system. It describes the different functionalities available to the customer.

**Main Use Cases:**
- Insert ATM Card
- Enter PIN
- Validate PIN
- Check Balance
- Withdraw Cash
- Deposit Money
- View Mini Statement
- Change PIN
- Print Receipt
- Eject Card

![alt text](<images/Screenshot 2026-10-29 153909.png>)

### 2. CLASS DIAGRAM

A Class Diagram represents the static structure of the ATM and Banking System. It shows the classes, attributes, methods, and relationships between different objects.

**Main Classes:**
- Customer
- ATM
- Bank Account
- Bank Server
- Transaction
- Receipt
- Card

![alt text](<images/Screenshot 2026-11-19 155900.png>)

### 3. SEQUENCE DIAGRAM

A Sequence Diagram represents the order of interactions between the customer, ATM, and bank server during a banking transaction.

**Sequence of Operations:**
1. Customer inserts the ATM card.
2. ATM requests the PIN.
3. Customer enters the PIN.
4. ATM sends the PIN for validation.
5. Bank server verifies the PIN.
6. Customer selects a transaction.
7. ATM requests transaction details.
8. Bank server processes the transaction.
9. ATM displays the transaction result.
10. ATM ejects the card.

![alt text](<images/Screenshot 2026-11-19 162230.png>)

### 4. COMMUNICATION DIAGRAM

A Communication Diagram represents how different objects communicate with each other through messages during an ATM transaction.

**Main Objects:**
- Customer
- ATM
- Bank Server
- Cash Dispenser
- Receipt Printer

It shows the exchange of messages between objects, such as card insertion, PIN validation, balance checking, cash dispensing, and receipt generation.

![alt text](<images/Screenshot 2026-11-20 164858.png>)

### 5. PACKAGE DIAGRAM

A Package Diagram represents the organization of different modules in the ATM and Banking System. It groups related functionalities into separate packages.

**Main Packages:**
- Customer Management
- Authentication
- Account Management
- Transaction Management
- ATM Operations
- Receipt Management

![alt text](<images/Screenshot 2026-11-20 160956.png>)

### 6. ACTIVITY DIAGRAM

An Activity Diagram represents the workflow of the ATM cash withdrawal process from card insertion to card ejection.

**Activity Flow:**

1. Insert ATM Card.
2. Enter PIN.
3. Validate PIN.
4. Select Transaction.
5. Enter Withdrawal Amount.
6. Check Account Balance.
7. Deduct Amount.
8. Dispense Cash.
9. Print Receipt.
10. Eject Card.

![alt text](<images/Screenshot 2026-11-20 162545.png>)

## ADVANTAGES

1. Provides convenient banking services.
2. Reduces waiting time for customers.
3. Provides secure PIN-based authentication.
4. Supports multiple banking transactions.
5. Improves transaction efficiency.
6. Provides access to basic banking services at any time.

## RESULT

Thus, the ATM and Banking System was successfully designed using StarUML. The required UML diagrams were created to represent the system structure, activities, and interactions between different components.