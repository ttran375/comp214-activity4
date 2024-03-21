# Group Lab Activity #2 – March 21, 2024

## Question 1

1. Assignment 7-2 from text: Using Program Units in a Package
In this activity, you use program units in a package created to store basket information. The
package contains a function that returns the recipient’s name and a procedure that retrieves the
shopper ID and order date for a basket.
a. In SQL Developer, create the ORDER_INFO_PKG package, using the Assignment07-
02.txt file located in eCentennial. Review the code to become familiar with the two
program units in the package.
b. Create an anonymous block that calls both the packaged procedure and function with
basket ID 12 to test these program units. Use DBMS_OUTPUT statements to display
values returned from the program units to verify the data.
c. Also, test the packaged function by using it in a SELECT clause on the BB_BASKET
table.
d. Use a WHERE clause to select only the basket 12 row.

## Question 2

2. Assignment 7-3 from text: Creating a Package with Private Program Units
In this activity, you modify a package to make program units private. The Brewbean’s
programming group decided that the SHIP_NAME_PF function in the ORDER_INFO_PKG
package should be used only from inside the package. Follow these steps to make this
modification:
a. In Notepad, open the Assignment07-03.txt file in the Chapter07 folder, and review the
package code.
b. Modify the package code to add to the BASKET_INFO_PP procedure so that it also
returns the name an order is shipped by using the SHIP_NAME_PF function. Make the
necessary changes to make the SHIP_NAME_PF function private.
c. Create the package by using the modified code.
d. Create and run an anonymous block that calls the BASKET_INFO_PP procedure and
displays the shopper ID, order date, and shipped-to name to check the values returned.
e. Use DBMS_OUTPUT statements to display the values.
