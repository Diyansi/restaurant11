# DIYANSI'S Restaurant Billing System

## Description
This program simulates a restaurant billing system that allows users to:
- Generate invoices for customers.
- View and search for previous invoices.
- Store invoices in a file for future access.

The program allows the user to enter customer details, items with their quantities and prices, and generates a bill with tax calculations, discounts, and total amounts. It also provides an option to save the invoice to a file and retrieve it later.

## Features
1. **Generate Invoice**: The user can enter the customer name, item details (name, quantity, price), and generate an invoice.
2. **View All Invoices**: View all saved invoices in a file.
3. **Search Invoice**: Search for a specific customer's invoice by name.
4. **Save Invoice**: Save the generated invoice to a file for future reference.
5. **Invoice Footer**: Displays subtotal, discounts, net total, taxes (CGST and SGST), and the grand total.

## Program Workflow
1. **Generate Invoice**: The user provides customer name, item details (name, quantity, price), and the program generates the invoice, calculates the total, and provides an option to save it.
2. **Show All Invoices**: The user can choose to view all previously saved invoices.
3. **Search Invoice**: The user can search for a specific invoice by entering the customer’s name.
4. **Exit**: Exits the program.

## Example
============DIYANSI'S. RESTAURANT============ Please select your preferred operation:

Generate Invoice
Show all Invoices
Search Invoice
Exit
Your choice: 1

Please enter the name of the customer: John Doe Please enter the number of items: 2

Item 1: Pizza Quantity: 2 Price: 10.50

Item 2: Coke Quantity: 1 Price: 2.00

Invoice Generated Successfully

Do you want to save the invoice [y/n]: y Successfully saved


## File Storage
Invoices are saved in a file named `RestaurantBill.dat`. Each invoice includes customer details, items, quantities, prices, and calculated totals.

## Code Overview
The program consists of the following functions:
- **generateBillHeader**: Displays the header of the invoice, including customer name and date.
- **generateBillBody**: Displays each item with its quantity, price, and total.
- **generateBillFooter**: Calculates and displays the subtotal, discount, CGST, SGST, and grand total.
- **main**: Handles user input for selecting operations and interacting with the system.

## Requirements
- C Compiler (e.g., GCC)

## Author
Created by **Diyansi Chaudhary**
