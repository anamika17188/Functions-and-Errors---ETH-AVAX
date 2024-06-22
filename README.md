# Smart contract Example

This repository contains a simple Solidity smart contract smart.sol that demonstrates basic error handling using require(), assert(), and revert() statements.

## Description
Functions
1.setData(uint newData)

Description: Sets the data variable to a new value newData.
Error Handling:
Uses require(newData != 0, "Data cannot be zero") to ensure newData is not zero.
Uses assert(newData != 999) to assert that newData is not 999.
Visibility: Public.
Parameters: newData (uint): The new value to set for datagetData()

2. getdata()

Description: Retrieves the current value of data.
Visibility: Public view.
Returns: (uint) The current value of data.

3.Revert()

Description: Manually triggers a revert with a custom error message.
Visibility: Public pure.
Revert Reason: "revert called".

### Executing program

Remix IDE: Utilize Remix IDE's Solidity compiler and deploy features to compile and deploy the contract. Interact with the contract using Remix's UI.

## Authors
Contributors names and contact info

Anamika Sharma
anamika123sha@gmail.com

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details
