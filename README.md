# FAST-FOOD-OREDERING-SYSTEM

Fast-food Ordering System is a simple, menu-based console application written in Assembly Language, designed for simulating the order process at a fast-food restaurant. The project offers users an interactive way to select food combos, meals, drinks, and fries, allowing them to customize their orders and calculate their total bill. The program is designed to handle different types of food items, each with its own price and customizable quantity.

Key Features
Menu Selection:

Users can choose from different combos, meals, and drinks, such as Combo 1, Breakfast Combo, Happy Meals, Combo 2, and various drink options like Pakola, Cola NEXT, and Big Apple.
Each item has a predefined price, and users can customize their orders by selecting the quantity they want.
Order Customization:

For each food item, the user can select specific options (e.g., choosing a drink with a combo) from a list of available choices.
Quantities of each item can be entered, and the total price is calculated accordingly.
Interactive Console Interface:

The system uses a menu-driven interface where the user interacts by selecting options, confirming choices, and inputting quantities.
Error handling ensures users are prompted with appropriate messages in case of invalid inputs.
Order Summary & Checkout:

After making all the selections, users can proceed to checkout where the total bill is displayed, and they have the option to confirm their order.
The program also supports order saving by generating a file with the order details, which includes the order number, customer name, and itemized bill.
Bill Generation & File Handling:

The application generates a text file containing the order details (including items, quantity, and total price) once the user confirms their order.
This feature mimics a real-world scenario where the order is saved for future reference or printing.
Technologies Used

Assembly Language: The entire program is written in assembly, utilizing basic system calls to handle input/output operations.
File Handling: The application generates text files to save the order details, providing a realistic checkout experience.
Menu Navigation: The application offers easy navigation through a menu-driven interface with multiple levels of selection.
How It Works
The user is presented with a welcoming message and a list of menu options.
They select from different combos, meals, or drinks.
After selecting their items, they specify the quantities they want.
Once the selection is complete, the program calculates the total bill and asks if the user wants to proceed to checkout.
Upon confirming the checkout, the order details are saved to a text file, and the user is given a summary of their order.

Example Use Case
Launch the Application: When you start the program, you will see the main menu with different food items and options.
Make Selections: You can select from combos (like Combo 1), meals (such as the Happy Meal), or individual items (drinks, fries).
Confirm Your Order: Once you make your selection, the program will ask you to specify how many of each item you want.
Checkout: At the end, you’ll be presented with your total bill and a prompt to confirm your order.
Save to File: After confirming, the order is saved to a file with your name and the order details.


Conclusion
This project serves as a example of an interactive assembly program that simulates a fast-food ordering system. It introduces key concepts such as menu handling, user input/output, and file operations, providing a hands-on learning experience for those interested in assembly programming.
