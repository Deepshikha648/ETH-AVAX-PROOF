# ETH-AVAX-PROOF
+ Module_1
# Detecterror Contract
This is a Solidity smart contract that demonstrates different error handling techniques using assert, revert, and require functions.

# License
This contract is using the MIT License.

# Prerequisites
Solidity ^0.8.17
# Contract Details
The detecterror contract provides the following functions:

# Average_marks(uint number)
+ It takes a number parameter and checks if it is not equal to zero using the assert statement.
  
# total_marks(uint_a, uint _b)
+ This function demonstrates the usage of the revert function.
+ If the _a is less than _b, it reverts the transaction with a custom error message .
+ If the condition is satisfied, it returns the result .
# passing_marks(uint l)
+ This function demonstrates the usage of the require function.
+ It first checks if l is greater than zero using the require statement.
+ If the condition fails, it reverts the transaction with a custom error message.
+ If the condition is met, it returns the result .
  
# walkthrough video
https://www.loom.com/share/f6570e65014640da9b3ba9b7be31fe5d

