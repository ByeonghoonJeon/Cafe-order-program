# Cafe-order-program
Program for cafe orders. From menu suggestion, to the total bill.

# How to use?
1. Pick a menu
2. Answer how many cups would you like to have.
3. If you need something else as well, input 'Y', otherwise input 'N'.

# Feature of this program
This program considered various potential responses of user.
For example, it user input "Latte" instead of full name "Caffe latte", program asks to user "Do you mean Cafe latte? or Thai tee latte?"
This function is available for every menu. Even user input only partial name of menu, program helps users to have exact menu they want.
The program counts total bill until user no longer want to order something.

Every responses from user are evaluated by the program. If user input meaningless answer when they are required to input menu name, program will continuously request to input valid answer. This error-safe function is applicated to all the user input and it prevents user from facing to unexpected errors.
