# python-challenge-1
# Instructions for this challenge
 Create an empty list to store customer's order as below

    ```python
    [
      {
        "Item name": "string",
        "Price": float,
        "Quantity": int
      },
      {
        "Item name": "string",
        "Price": float,
        "Quantity": int
      },
    ]
    ```



print the submenu and prompt the customer to enter their selection save value in menu_selection variable

check if the variable is a digit else print error. convert the variable into number and use it to in keys of menu_items

if user input is not in the menu_items print error "Item selected is not in the menu, please enter the correct Item "
Ask for the quantity of item and mention default value is 1, check if input is a number if so convert to an integer.

Append the customer_order in dictionary format with following keys: Item name, Price and Quantity

Note : Price if found in menu_items dictionary

Inside While loop prompt the customer to keep ordering write match:case statement for y or n include option to enter the right option if neither are entered.

If customer entered Y / y set place order varibale to True break the contunous while loop
if customer entered N / n set place order variable to False; print "Thank you for your order" break the continous while loop

Create an Order Reciept using for loop inside display item name, price and quatity in table format 

Upon exiting the for loop, use list comprehension and sum() to calculate the total price of the order and display it to the customer. 

    ```text
      Item name                 | Price  | Quantity
      --------------------------|--------|----------
      Apple                     | $0.49  | 1
      Tea - Thai iced           | $3.99  | 2
      Fried banana              | $4.49  | 3
      ```

