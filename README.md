# coffeeMachine
## Coffee Machine app
## Coffee Machine
This code simulates the operation of a coffee machine. It has a menu of drinks (espresso, latte, and cappuccino), and the user can select a drink by inputting its name. The machine will then check if it has sufficient resources to make the drink and ask the user for payment. If the payment is successful, the machine will dispense the drink and return any change.

# Menu
The menu contains three drinks:

Espresso: made with 50ml water and 18g coffee, costs $1.5
Latte: made with 200ml water, 150ml milk, and 24g coffee, costs $2.5
Cappuccino: made with 250ml water, 100ml milk, and 24g coffee, costs $3.0
Resources
The machine has the following resources:

* Water: 300ml
* Milk: 200ml
* Coffee: 100g
# How to Use
* To use the coffee machine, the user can input the name of the desired drink or other commands:

* "espresso": dispenses an espresso
* "latte": dispenses a latte
* "cappuccino": dispenses a cappuccino
* "report": prints a report of the current resources and profits
* "off": turns off the machine
When the user selects a drink, the machine will check if it has enough resources to make the drink. If not, it will inform the user and ask for a different selection. If there are enough resources, the machine will ask for payment.

The user can input the number of quarters, dimes, nickels, and pennies they want to use for payment. The machine will calculate the total payment and check if it is sufficient. If the payment is sufficient, the machine will dispense the drink and return any change. If not, it will inform the user and ask for more payment.

Examples
Here are some examples of using the coffee machine:
What would you like? (espresso/latte/cappuccino): latte
* Please insert coins.
* how many quarters?: 2
* how many dimes?: 0
* how many nickles?: 0
* how many pennies?: 0
* Here is $0.5 in change.
* Here is your latte ☕️. Enjoy!
* What would you like? (espresso/latte/cappuccino): cappuccino
* ​Sorry there is not enough water.
* What would you like? (espresso/latte/cappuccino): report
* Water: 50ml
* Milk: 50ml
* Coffee: 76g
* Money: $2.5
* What would you like? (espresso/latte/cappuccino): off
