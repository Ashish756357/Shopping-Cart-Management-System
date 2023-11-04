# Shopping-Cart-Management-System

This is a simple command-line shopping cart management system implemented in C. It allows customers to purchase products, view their cart, and generate bills. Managers can add and display products in stock. The system prevents duplicate product IDs and manages product stock quantities.

Features
Manage Product (Manager Functionality)

Add new products to the stock.
Display all products in the stock.
Remove products from the stock.
Purchase Product (Customer Functionality)

Add products to the cart with a limit of 10 products per customer.
Check product availability based on stock quantity.
View products in the cart.
Generate Bill

Modify the cart before checkout.
Calculate the total bill amount.
Proceed to checkout and update the stock.
How to Use
Run the program, and you will be presented with a menu to choose an option:

1: Manage Product (for managers)
2: Purchase Product (for customers)
3: Generate Bill (to finalize your purchase)
0: Exit
If you choose "Manage Product," you can:

1: Add a new product to the stock.
2: Display all products in the stock.
0: Go back to the main menu.
If you choose "Purchase Product," you can:

1: Buy a product.
0: Go back to the main menu.
When you add a product to your cart, you can choose a product by its ID and specify the quantity. The system will check if the product is available in stock.

To generate a bill, you can:

1: Modify your cart.
2: Proceed to checkout.
0: Go back to the main menu.
If you choose "Modify your cart," you can delete products from your cart or change the quantity.

After proceeding to checkout, the system will display the total bill amount and ask for confirmation. If you confirm, it will update the stock and clear your cart.

Code Structure
The code consists of several functions:

manageProduct(): Handles the manager's functionalities.
purchaseProduct(): Handles the customer's purchase process.
generateBill(): Handles the checkout process.
addProduct(): Adds a new product to the stock.
addToCart(): Adds a product to the cart.
viewCart(): Displays the content of the cart.
modifyCart(): Allows modification of the cart during checkout.
checkout(): Finalizes the purchase and updates the stock.
checkStock(): Checks the availability of a product in the stock.
updateStock(): Updates the stock after a purchase.
removeProduct(): Removes products from the stock.
deleteCart(): Removes products from the cart.
clearCart(): Empties the cart.
posProduct(): Finds the position of a product in the stock.
posCart(): Finds the position of a product in the cart.
displayAllProduct(): Displays all products in the stock.
The system includes error handling and prompts for user input. Managers can add new products and remove existing ones, while customers can add products to their cart, view their cart, and generate a bill.

Enjoy using this simple shopping cart management system!
