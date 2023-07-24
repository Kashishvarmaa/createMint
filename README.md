# Creating and Minitng tokens

This Solidity program is demonstrates  how to create and mint tokens  and has the syntax and functionality of the Solidity programming language. The purpose of this program is to get a brief understanding on how this whole processof minting and creating token occursand thus can also give us the feel on how this happens.

## Description

This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contrct here has token named Barbie with the symbol BRB and this code aloows the contract devolper to mint, burn transfer token and aloows the owner to distrubute additional tokens as well this contract inherits the functionaliy of a few contracts like that of ERC20, ERC20Burnable and Ownable.

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., Create_mint.sol).Paste the code 

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.9" (or another compatible version), and then click on the "Compile create_mint.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "create_mint" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the burn, tranfer and mint  function. Click on the "mint" and add the address that is present on the top and put in any value you want to mint and click on trasnact, you can do the same with burn and tranfer. 
To deploy the token on local hardhat network we need to run the command 
```shell
npx hardhat run scripts/deploy.js
```
and you can see your token is delpoyed locally to the hardhat network


## Authors

Kashish Varma  
[@kashishvarmaa@gmail.com]


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
