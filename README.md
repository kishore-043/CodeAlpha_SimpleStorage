# CodeAlpha_SimpleStorage
A SimpleStorage Smart Contract developed using Solidity as part of the CodeAlpha Blockchain internship.
# CodeAlpha - SimpleStorage Smart Contract

## Description
This project is a Simple Storage Smart Contract developed using Solidity as part of the CodeAlpha Blockchain Development Internship.

## Technologies Used
- Solidity
- Remix IDE
- Ethereum Blockchain

## Features
- Stores an integer value.
- Allows the value to be increased using the `increment()` function.
- Allows the value to be decreased using the `decrement()` function.
- Prevents the value from becoming negative.
- Allows the stored value to be viewed publicly.

## Smart Contract Functions

### value
Displays the current stored integer value.

### increment()
Increases the stored value by 1.

### decrement()
Decreases the stored value by 1 and prevents the value from becoming negative.

## How to Run
1. Open the `SimpleStorage.sol` file in Remix IDE.
2. Compile the smart contract using Solidity Compiler.
3. Go to the Deploy & Run Transactions section.
4. Select Remix VM as the environment.
5. Deploy the SimpleStorage contract.
6. Test the `value`, `increment`, and `decrement` functions.

## Project Testing
The smart contract was successfully tested with the following results:

- Initial value: 0
- After increment: 1
- After decrement: 0

## Author
Kishore T

## Internship
CodeAlpha Blockchain Development Internship
