# ⏱️ Counter-Automation

A time-based smart contract that automatically increments a counter using Chainlink Automation. This project demonstrates how to schedule decentralized function calls using Solidity and Chainlink’s `AutomationCompatibleInterface`.

## 📌 Overview

This contract uses Chainlink Automation to:
- Trigger a function (`count()`) at regular time intervals.
- Increment a `counter` variable on-chain.
- Showcase how to build and register time-based upkeeps using Chainlink’s decentralized network.

## 🧠 How It Works

1. `checkUpkeep()` checks if the scheduled time has passed.
2. `performUpkeep()` is called by Chainlink nodes to increment the counter.
3. The contract is registered with a cron-like schedule (e.g., every 5 minutes) via Chainlink Automation.

## 🛠 Tech Stack

- **Solidity** `v0.8.26`
- **Chainlink Automation**
- **Sepolia Testnet**
- **Remix IDE**
- **Etherscan**
- **GitHub**

## 🚀 Deployment

1. Compile the contract in Remix using `v0.8.26`, with optimization disabled.
2. Deploy to Sepolia.
3. Register the contract on [Chainlink Automation](https://automation.chain.link/) with a time-based trigger.
4. Verify the contract on [Etherscan](https://sepolia.etherscan.io/).

## 🔍 Contract Details

- **Address**: `0xE8A647D13EAbb8bdB73B3eD9C54C9e4705aE3d38`
- **Upkeep ID**: `47202059062571190644072478805907025795123128743570400215785385153495049321271`
- **Automation Type**: Time-based (cron)

## 📚 Learning Goals

- Understand Chainlink’s Automation Execution Cycle.
- Practice writing and verifying smart contracts.
- Document workflows for peer learning and public sharing.

## 🧑‍🏫 Author

Sayed Ali Mohamed — Blockchain developer in progress

