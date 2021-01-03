# ERC-20-Token-ETH-Swap

Creates an ERC-20 Token and a smart contract that swaps this token for a fixed rate of ETH. 

With a user interface in React

## Make it run

Install all the node packages:
```Bash
npm install
```
Launch [Ganache](https://www.trufflesuite.com/ganache), exposing the port 7545 normally.
<br>Then migrate the smart contracts to the blockchain:
```Bash
truffle migrate --reset
```
Launch the webserver(Hosted locally on port 3000):
```Bash
npm run start
```
