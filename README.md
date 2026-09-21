Movie Ticket Calculator

A simple Python console-based Movie Ticket Calculator that
calculates the final ticket price based on:

Customer age

Seat type

Show time

Membership status

Weekend status

Discounts

Extra charges

Service charges

Features

Takes ticket details from the user using input()

Checks age-based booking eligibility

Handles different seat types:

Premium

Gold

Normal

Calculates membership discount

Adds evening/weekend extra charges

Calculates service charges based on seat type

Calculates the final ticket price

Accepts input in different letter cases using .lower()

Technologies Used:

Python 3

Conditional statements (if, elif, else)

Logical operators (and, or)

User input with input()

Type conversion with int()

String methods such as .lower()

How to Run

1. Install Python

Make sure Python 3 is installed on your computer.

Check the installation:

python --version

2. Open the Project Folder

Open the project folder in VS Code or another Python editor.

3. Run the Program

Use:

python ticket.py

Or run the file directly from VS Code.

User Input

The program asks for:

Enter your age:
Enter seat type (Premium/Gold/Normal):
Enter show time (Morning/Afternoon/Evening):
Are you a member? (True/False):
Is it weekend? (True/False):

Example Input

Enter your age: 22
Enter seat type (Premium/Gold/Normal): Premium
Enter show time (Morning/Afternoon/Evening): Evening
Are you a member? (True/False): True
Is it weekend? (True/False): False

Pricing Logic

The basic ticket price is:

Base Price = 15

Membership Discount

If the user is a member and their age is 21 or above:

Discount = 3

Otherwise:

Discount = 0

Extra Charges

Extra charges are applied when:

It is a weekend, OR

The selected show time is Evening

Extra Charges = 2

Otherwise:

Extra Charges = 0

Service Charges

Seat Type   Service Charge

Premium     5
Gold        3
Normal      1

Final Price Formula

The final ticket price is calculated as:

Final Price = Base Price - Discount + Extra Charges + Service Charges

Example

For:

Base Price = 15
Discount = 3
Extra Charges = 2
Service Charges = 5

The final price is:

15 - 3 + 2 + 5 = 19

Input Case Handling

The program uses .lower() so inputs such as:

Premium
premium
PREMIUM
pReMiUm

are treated the same way.

The same approach is used for show time and membership/weekend inputs.

Learning Concepts

This project is useful for practicing:

Variables

Data types

input()

int()

Strings

Boolean values

if-elif-else

and / or

Comparison operators

Logical conditions

Basic calculation

User input validation concepts

Future Improvements

Possible improvements include:

Add multiple movie selections

Add different base prices for different movies

Add child/senior citizen discounts

Add GST/tax calculation

Add quantity of tickets

Add movie names and show numbers

Add better input validation

Store booking details in a file or database

Create a graphical user interface (GUI)

output:
<img width="777" height="340" alt="image" src="https://github.com/user-attachments/assets/9ca24ed2-7064-4efa-b964-dd3cc153c2c1" />
<img width="711" height="332" alt="image" src="https://github.com/user-attachments/assets/495d5d88-40d8-4876-b667-b70aa6b3752b" />


created by:

Tanisha

BCA Student

This project was created as a Python practice project to understand
conditional statements, logical operators, user input, and basic
calculations.
