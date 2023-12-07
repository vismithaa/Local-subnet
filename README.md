# Local-subnet(Defi)

A local Avalanche subnet is created and a Defi game contract is deployed to that subnet. Interaction with the functions is shown in the video.

## Description

The user can perform all the ERC20 contract functions like mint, burn , transfer, transferfrom, approve and allowance. Along with these functions , the user can also gift another player some tokens but he has to make sure that he has a minimum balance of 3000 tokens . The sender also gets a bonus of 500 tokens for gifting. These transactions are carried out using local subnet connected to metamask and using our own tokens.

 ## Getting Started
 
### Executing the code

### Connect to MetaMask:

Ensure that you have MetaMask installed in your browser.
Connect MetaMask to your Avalanche subnet by adding the custom RPC URL.
Execute Transactions:

Use MetaMask to interact with your deployed contracts.
Perform transactions such as minting, burning, depositing, withdrawing,gifting.
### Creating and Deploying Contract:
In order to create a avalanche subnet , you need to install the CLI which runs only on Linux and Mac:
 
[ https://docs.avax.network/tooling/cli-guides/install-avalanche-cli](https://github.com/ava-labs/avalanche-cli/blob/main/README.md)

### Interacting with the functions:

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., gift_subnet.sol).

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.17" (or another compatible version), and then click on the "Compile gift_subnet.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "gift_subnet" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it .

## Authors
 
Vismitha P
 
@vismithaaap@gmail.com
 
## License
 
This project is licensed under the MIT License - see the LICENSE.md file for details
 
 
