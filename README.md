Download Link: https://assignmentchef.com/product/solved-lab-02-c-language-review-part-2
<br>
5/5 - (1 vote)

Create a C# console application for the following problem.  When you create a new C# project, Visual Studio will create a folder to hold every file and sub-folder for your project.  You need to locate this folder in your computer, zip this folder and then submit the zip file to Blackboard.



Write a program for a vending machine.  This machine only sells four snacks: potato chips, energy bars, popcorns and peanuts.  This program allows user to buy snacks until he wants to stop.

Create class VendingItem with the following specifications:

1. This class has three private instance variables:

description: a string variable that stores what snack it is

unitPrice: a double variable that stores the unit price of the snack

inventory: an integer variable that stores the quantity of the snack in the machine

2. Create a constructor that takes three arguments, one for each instance variable.  Initialize the instance variables with the arguments.

3. Create public property for each instance variable.  Each property only has get but no set.

4. Create a public void method SellItem. This method takes no argument.  It checks the inventory of the snack.  If the inventory is 0, displays the message “Sorry! Item sold out”.  If the inventory is higher than 0, reduce the inventory by one, display what snack is sold and the unit price of the snack.

Create another class to implement the rest of the program.  This class has three static methods.

1. In the Main method, create an array to store 4 instances of VendingItem with the following data:

DescriptionUnit priceInventoryPotato chips1.995Energy bar2.442Popcorns0.994Peanuts1.293

Call the DsiplayAll method (see below) and pass the array to it.  Then call the BuyItems method (see below) and also pass the array as an argument.  Finally, call the DisplayAll method one more time.

2. In the DisplayAll method, display description, unit price and inventory of each snack in the machine.

3. In the BuyItems method, write a loop for the user to buy snacks.  Inside the loop, show what snacks the machine sells and ask user to choose a snack by entering 1, 2, 3 or 4, or enter 5 to quit.

The following shows a test run of the program:

Description: Potato Chips  Unit price: 1.99  Inventory: 5

Description: Energy Bar  Unit price: 2.49  Inventory: 2

Description: Popcorns  Unit price: 0.99  Inventory: 4

Description: Peanuts  Unit price: 1.29  Inventory: 3

Enter 1 to buy Potato Chips

Enter 2 to buy Energy Bar

Enter 3 to buy Popcorns

Enter 4 to buy Peanuts

Enter 5 to quit

Snack choice: 2

Item sold: Energy Bar

Unit price: 2.49

Inventory: 1

Enter 1 to buy Potato Chips

Enter 2 to buy Energy Bar

Enter 3 to buy Popcorns

Enter 4 to buy Peanuts

Enter 5 to quit

Snack choice: 3

Item sold: Popcorns

Unit price: 0.99

Inventory: 3

Enter 1 to buy Potato Chips

Enter 2 to buy Energy Bar

Enter 3 to buy Popcorns

Enter 4 to buy Peanuts

Enter 5 to quit

Snack choice: 2

Item sold: Energy Bar

Unit price: 2.49

Inventory: 0

Enter 1 to buy Potato Chips

Enter 2 to buy Energy Bar

Enter 3 to buy Popcorns

Enter 4 to buy Peanuts

Enter 5 to quit

Snack choice: 2

Sorry! Item sold out

Enter 1 to buy Potato Chips

Enter 2 to buy Energy Bar

Enter 3 to buy Popcorns

Enter 4 to buy Peanuts

Enter 5 to quit

Snack choice: 1

Item sold: Potato Chips

Unit price: 1.99

Inventory: 4

Enter 1 to buy Potato Chips

Enter 2 to buy Energy Bar

Enter 3 to buy Popcorns

Enter 4 to buy Peanuts

Enter 5 to quit

Snack choice: 5

Description: Potato Chips  Unit price: 1.99  Inventory: 4

Description: Energy Bar  Unit price: 2.49  Inventory: 0

Description: Popcorns  Unit price: 0.99  Inventory: 3

Description: Peanuts  Unit price: 1.29  Inventory: 3

Press any key to continue . . .Grading

Creating instance variables of class VendingItem [13 pts]

Writing constructor of class VendingItem [13 pts]

Creating properties of class VendingItem [13 pts]

Writing SellItem method of class VendingItem [13 pts]

Writing Main method [13 pts]

Writing DisplayAll method [13 pts]

Writing BuyItems method [13 pts]