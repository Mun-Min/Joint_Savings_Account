# Soldity Smart Contract Execution Results

<p align="center">
  <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fazcoinnews.com%2Fwp-content%2Fuploads%2F2020%2F06%2Fethereum-wallets-with-at-least-32-eth-the-amount-required-for-eth-2-0-staking-have-grown-by-13-this-year.jpg&f=1&nofb=1&ipt=a2b78255efe74c8f3d0821c58e1a392548b6da26c9de1e59e5aac5453473be86&ipo=images"/>
</p>


## Table of Contents
  - [Deploying Compiled Solidity Smart Contract](#deploying-compiled-solidity-smart-contract)
  - [Depositing Ether for Testing Contract Functions](#depositing-16-ether-for-testing-contract-functions)
  - [Transaction 1 -- Withdraw 1 Ether as Wei](#transaction-1----withdraw-1-ether-as-wei)
  - [Transaction 2 -- Withdraw 10 Ether as Wei](#transaction-2----withdraw-10-ether-as-wei)
  - [Transaction 3 -- Withdraw 5 Ether as Wei](#transaction-3----withdraw-5-ether-as-wei)
  - [Conclusion](#conclusion)


## Deploying Compiled Solidity Smart Contract

* To deploy the solidity smart contract [ [joint_savings.sol](./joint_savings.sol) ] , hit the deploy button after successfully compiling the contract using Remix IDE.

![alt=“”](./Deploying_Compiled_Solidity_Contract.png)

---

## Depositing 16 Ether for Testing Contract Functions

* Here the deposit function was initially used to deposit 16 Ether for testing. The addresses of Account 1 & 2 were also appointed using the setAccounts function.

![alt=“”](./Depositing_Ether_and_Defining_Ethereum_Addresses.png)

---

## Transaction 1 -- Withdraw 1 Ether as Wei

* Here the withdraw function was used to withdraw 1000000000000000000 Wei, which is equivalent to 1 Ether, to Account 1.
* The withdraw function has three outputs:
  * contractBalance
  * lastToWithdraw
  * lastWithrawAmount
* Outputs can be seen by clicking on each of the options. The smart contract balance decreased from 16 Ether to 15 Ether.

![alt=“”](./Transaction_1.png)

---

## Transaction 2 -- Withdraw 10 Ether as Wei

* Here the withdraw function was used to withdraw 10000000000000000000 Wei, which is equivalent to 10 Ether, to Account 2.
* The withdraw function has three outputs:
  * contractBalance
  * lastToWithdraw
  * lastWithrawAmount
* Outputs can be seen by clicking on each of the options. The smart contract balance decreased from 15 Ether to 5 Ether.

![alt=“”](./Transaction_2.png)

---

## Transaction 3 -- Withdraw 5 Ether as Wei

* Here the withdraw function was used to withdraw 5000000000000000000 Wei, which is equivalent to 5 Ether, to Account 2.
* The withdraw function has three outputs:
  * contractBalance
  * lastToWithdraw
  * lastWithrawAmount
* Outputs can be seen by clicking on each of the options. The smart contract balance decreased from 5 Ether to 0 Ether.

![alt=“”](./Transaction_3.png)

---

## Conclusion

The [joint_savings.sol](./joint_savings.sol) file holds a Solidity Smart Contract that mimics the action of a joint savings account such as the ability to deposit/withdraw funds from the account. The contract also allows the user to view the current balance of the smart contract as well as the withdrawl addresses and amount withdrawn (in Wei), after each transaction.

    Compiling & Deploying to JavaScript VM using Remix IDE: 

      - Import the joint_savings.sol file into the Remix IDE 
      - Compile the contract 
      - After successful compilation, deploy the contract using VM environment on Remix 
      - Once deployed, deposit test Ether using the deposit function and begin testing contract functionality!

---
