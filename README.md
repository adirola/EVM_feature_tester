## EVM Test Truffle suit

## How to get started

* Install truffle globally if not installed using the command `npm install -g truffle`
* Clone the project and then use the command `npm i` to install all the dependencies
* Create a `secrets.json` file with contents as
```js
{
    "mnemonic": "<12 word mnemonic>"
}
```
* add the network provider details in truffle-config.js 
* Run the contracts on added netowrk using the command `truffle migrate --network <network_name> --reset`

## Test Covered More to be added soon 

* get Chain ID
* ERC20 token test
* State Update
* Gas utilisation and return excess 
* Low Level contract calls
* (UUPS upgrdeable) 
* Self destruct 
* Facotry Contracts

## Contributions

Contributions are welcomed. Feel free to raise PR with more contracts and test situations in migrations file. 
