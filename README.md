# superMarketBillingSystem-withFileHandling
This is a simple Supermarket Billing System implemented in C++ with file handling capabilities. It allows the user to add, modify, delete, and display items in the inventory, calculate the bill for a customer's purchase, and generate a sales report

Features
Add new items to the inventory
Modify existing items
Delete items from the inventory
Calculate the total bill for a customer's purchase
Generate a sales report with details of each transaction


File Structure
main.cpp: Contains the main program logic
item.h and item.cpp: Define the Item class for managing inventory items
bill.h and bill.cpp: Define the Bill class for calculating the total bill
file_handling.h and file_handling.cpp: Define functions for reading from and writing to files
inventory.txt: File to store the inventory data
sales_report.txt: File to store the sales report data

How to Use
Compile the program using a C++ compiler (e.g., g++)
bash
g++ main.cpp item.cpp bill.cpp file_handling.cpp -o SuperMarketBillingSystem

g++ main.cpp item.cpp bill.cpp file_handling.cpp -o SuperMarketBillingSystem
Run the compiled executable
bash
./SuperMarketBillingSystem


./SuperMarketBillingSystem
Follow the on-screen instructions to interact with the system
Usage Examples
Add a new item to the inventory
yaml

Enter item details:
Item ID: 101
Name: Rice
Price: 50
Quantity: 100
Item added successfully!

Enter item details:
Item ID: 101
Name: Rice
Price: 50
Quantity: 100
Item added successfully!
Calculate the bill for a customer's purchase
mathematica
Enter item ID: 101
Enter quantity: 2
Total bill: 100

Enter item ID: 101
Enter quantity: 2
Total bill: 100
Generate a sales report
yaml
Sales Report
------------
Date: 2024-05-08
Item ID: 101, Name: Rice, Quantity: 2, Total Price: 100

Sales Report
------------
Date: 2024-05-08
Item ID: 101, Name: Rice, Quantity: 2, Total Price: 100
Contributors
Your Henok
