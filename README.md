# Solidity

## How to Start

1. Navigate to the Remix IDE and create three new contracts called AssociateProfitSplitter.sol, TieredProfitSplitter and DeferredEquityPlan.

2. To develop and test these contracts, use the Ganache development chain, and point MetaMask to localhost:8545, or replace the port with what you have set in your workspace.

### Level One : Associate Profit Splitter Contract

This contract ease the process of paying multiple employees through a single input. It accepts deposits of Ether and distributes them evenly when deployed.

1. In the Deploy tab in Remix, deploy the contract to your local Ganache chain by connecting to Injected Web3 and ensuring MetaMask is pointed to localhost:8545.

2. You will need to fill in the constructor parameters with your designated employee addresses.
![employee](https://github.com/elijahchandra/Solidity/blob/main/Screenshots/employee.png)

3. Test the deposit function by sending various values. Keep an eye on the employee balances as you send different amounts of ether to the contract and ensure the logic is executing properly.
![1](https://github.com/elijahchandra/Solidity/blob/main/Screenshots/1.jpg)


### Level Two : Tiered Profit Splitter Contract

This contract distributes Ether to employees based on their positions. A CEO in this scenario is payed 60% of the total Ether aquired by the company. Tiers are  defined in the contract alongside how Ether is distributed.
![2](https://github.com/elijahchandra/Solidity/blob/main/Screenshots/2.jpg)

### Level Three : Defered Equity Plan Contract

This contract allows equal distribution of shares over a time period. For this example, an active employee is transferred 250 shares annually over 4 years.
![3](https://github.com/elijahchandra/Solidity/blob/main/Screenshots/3.jpg)
