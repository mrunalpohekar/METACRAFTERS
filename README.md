## Mint and burn
This is a basic Solidity smart contract . 

## DESCIRPTION
The code represents a Solidity smart contract featuring two public variables for token name and abbreviation, as well as a variable indicating the total supply. The contract also incorporates a mapping variable called "balances" that associates addresses with corresponding token balances.
Furthermore, this contract encompasses two functions named "mint" and "burn." The "mint" function is responsible for augmenting the balance of a specified address by a given value. Conversely, the "burn" function reduces the balance of the specified address by a given value, subject to the condition that the address possesses an adequate balance to facilitate the requested reduction.

## COMPILER TO USE
Use remixIDE to compile/run and deploy the program.

## EXECUTING THE PROGRAM
* Create a new folder called "mytoken.sol."
* Write the contract using Solidity programming language.
* If Remix is set to auto compile and run, the code will be automatically compiled and executed. Otherwise, manually compile and run the code by selecting the "Compile and Run" option from the left menu.
* After compiling, deploy the contract to obtain the account address for further steps.
* If the contract is deployed successfully, verify the token name and abbreviation.
* Check the token abbreviation by clicking on "TokenAbbvr" and similarly verify the token supply and name.
* Initially, the account balance is zero.
* To mint tokens, click on the "Mint" button, paste the account address, enter the desired token quantity (e.g., 200), and click "Transact" to add tokens to the account.
* To check the balance, click on "Balances," paste the account address, and click "Call" to view the account balance.
* To burn tokens, click on "Burn," paste the account address, set the value to be burnt (e.g., 70), and click "Transact" to reduce tokens from the account.
* To check the balance again, press "Call" to obtain the latest balance (e.g., 200 - 70 = 130 tokens).
* These are all the steps involved in the contract.
   
