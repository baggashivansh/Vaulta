# Vaulta

Vaulta is a simple ATM simulation built in Java to practice core banking logic, clean code structure, and object oriented design. The project focuses on how an ATM system handles login, balance checks, deposits, and withdrawals in a structured and understandable way.

## Overview

This project was created to explore how basic banking systems work from a software perspective. Instead of just making a demo program, the goal was to keep responsibilities separated so the system stays clear, maintainable, and easy to expand later.

The project is organized into three main parts:

Model layer manages account data and transaction logic  
Service layer handles authentication and account operations  
UI layer manages user interaction through the console  

This approach keeps business logic separate from user input and display.

## Features

Secure login using customer number and PIN  
Checking and savings account handling  
Deposit and withdrawal functionality  
Balance viewing  
Basic input validation  
Structured object oriented design  

## Project Structure

Vaulta

model  
Account.java  

service  
BankService.java  

ui  
ATM.java  

util  
Helper utilities and format related classes  

## Technologies Used

Java  
Object oriented programming principles  
HashMap for temporary account storage  
Console based interaction  

## Design Approach

Account class focuses only on financial data and transaction rules.  
Service layer manages authentication and account access.  
UI layer handles all interaction with the user.

This separation makes the project easier to maintain and extend.

## Possible Future Improvements

Persistent storage using files or a database  
Transaction history tracking  
Multiple account handling simulation  
Accurate financial calculations using BigDecimal  
REST API version using Spring Boot  
Unit testing support  

## How to Run

Clone the repository  
Open it in any Java compatible IDE  
Run the ATM main class  
Use the sample credentials below to test the system  

## Sample Credentials

Customer Number 952141  
PIN 191904  

Customer Number 989947  
PIN 717976  

Vaulta is intended as a learning project that demonstrates structured backend thinking through a simple ATM simulation.

Built by Shivansh Bagga
