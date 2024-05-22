# BuyAndSell Contract Overview
The BuyAndSell contract is a simple Solidity smart contract that facilitates buying and selling operations. Below is a brief overview of its functions:

# Contract Variables
wallet: Address variable representing the owner of the contract.
buy: Unsigned integer variable representing the initial buy value, defaulted to 5000.
sell: Unsigned integer variable representing the initial sell value, defaulted to 5000.
Constructor
constructor(): Initializes the wallet variable with the address of the contract deployer.

# Functions
AddInterest:
This function allows adding interest to the current buy value.
It requires the interest value to be greater than 500 and the current buy value not to exceed 300.
The function returns the updated buy value after adding the interest.

MonthlySell:
This function executes monthly selling operations.
It deducts the specified monthly expense from the current sell value.
The function requires the expense value to be greater than 80 and the current sell value to be sufficient.
It returns the updated sell value after deducting the monthly expense.

updateBuy:
This function enables the contract owner to update the buy value.
Only the contract owner can call this function.
It updates the buy value to the specified new buy value.

updateSell:
Similar to updateBuy, this function allows the contract owner to update the sell value.
Only the contract owner can call this function.
It updates the sell value to the specified new sell value.

These functions collectively enable the contract owner to manage buying and selling operations, including adding interest, deducting monthly expenses, and updating buy/sell values as needed.

# Owner
METACRAFTERS RODRIGO MACABUDBUD
