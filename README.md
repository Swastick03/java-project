# Bank Management System

## Overview

The Bank Management System is designed to streamline and automate the operations of a bank, ensuring efficiency and reducing manual workload. It offers a virtual platform where customers can safely manage their accounts, while administrators can easily oversee banking activities. The system is built using Java and utilizes Java Database Connectivity (JDBC) to interact with a MySQL database. It covers a range of functionalities including account creation, balance inquiries, deposits, withdrawals, money transfers, and transaction history management.

## Problem Statement

In today's fast-paced world, managing a bank manually has become increasingly tedious. A Bank Management System is necessary to help manage bank operations more efficiently. This system includes features for both bank administrators and customers. Administrators can create new accounts, manage transactions, and oversee the banking operations, while customers can perform transactions such as deposits, withdrawals, and transfers with ease.

## Features

### Administrator Functions
- **Login**: Admins log into their accounts using credentials stored in the database. Access is restricted to authorized users.
- **Main Menu**: From here, administrators can manage customers, create accounts, process deposits and withdrawals, transfer money, generate reports, and check balances. They can also add or remove administrators.
- **Add Customer**: Admins can add new customers to the bank database.
- **Create Account**: After adding a customer, the admin can create a new bank account for them.
- **Transaction Management**: The system allows admins to process withdrawals and deposits. The account number must be validated against the database before proceeding.
- **Money Transfer**: Admins can transfer money between two accounts after validating both account numbers.
- **Reports**: Admins can view detailed reports of customer accounts and transactions.
- **Balance Check**: The current balance of any customer's account can be displayed.
- **Admin Management**: Existing admins can create new admin accounts or delete existing ones.

### Customer Functions
- **Balance Inquiry**: Customers can check their account balance.
- **Deposit**: Customers can deposit money into their accounts.
- **Withdrawal**: Customers can withdraw money from their accounts.
- **Transfer**: Customers can transfer money between accounts.
- **Transaction History**: Customers can view their transaction history.

## System Design

### Flow Chart
The system design and flowchart outline the step-by-step operations and interactions between the administrator and customer interfaces. It demonstrates the logical flow of actions such as logging in, managing customer accounts, processing transactions, and generating reports.

## Screenshots

### Login Page
**Description**: The administrator logs in using their credentials. Access is denied if credentials do not match the database.


![image](https://github.com/user-attachments/assets/6cc3ac30-a3d4-4177-8e6b-ceda8d396f1a)


### Main Menu
**Description**: Central hub for all administrative actions including customer management, account creation, transactions, and reports.


![image](https://github.com/user-attachments/assets/2a513a50-f07b-4228-b7f7-882cad04dbfd)


### Add Customer & Account Creation
**Description**: Admins can add new customers and create accounts for them in the system.


![image](https://github.com/user-attachments/assets/804a0b44-bde7-42d8-b92e-70862bb693b9)


### Transaction Page
**Description**: Admins can process deposits and withdrawals. Account numbers are validated against the database.


![image](https://github.com/user-attachments/assets/3c4b0d1f-a309-4ba3-8a71-34b64f95402e)


### Transfer Page
**Description**: Money can be transferred between two accounts. Both account numbers are required for validation.


![image](https://github.com/user-attachments/assets/aab69102-e9c9-49ab-a0b1-f1b25ca4ed9e)


### Report Page
**Description**: Displays detailed customer account information to the admin.


![image](https://github.com/user-attachments/assets/b7511bdc-c7a6-4131-9109-de2f1bce1db3)


### Balance Page
**Description**: Shows the current balance of a selected customer account.


![image](https://github.com/user-attachments/assets/91ad83e1-a34c-4eee-9e7f-14fe70a29c7f)


### Admin Page
**Description**: Allows the addition and removal of admin accounts.
![image](https://github.com/user-attachments/assets/0a7ab482-d3d7-4740-aa2c-6123722cf4f4)


