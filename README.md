# 🎲 Blockchain Lottery Smart Contract

This repository contains a simple **Lottery DApp** smart contract written in Solidity. It demonstrates the basic working of a decentralized lottery system on the Ethereum blockchain.

## 🔧 Features

- 📥 Anyone can enter the lottery by sending exactly **1 ETH**
- 🔐 Only the **manager** (deployer) can:
  - View the contract balance
  - Select the winner
- 🎰 Winner is selected using a **pseudo-random number generator**
- 💸 Entire balance is transferred to the winner
- ♻️ Lottery resets after each round

## 🚀 Tech Stack

- **Solidity** (v0.8.x compatible)
- **Remix IDE** for compilation and deployment
- **MetaMask** (optional for testing with injected Web3)

## 🧠 Concepts Demonstrated

- `receive()` function for direct ETH transfers
- Access control using `require`
- Random number generation using `keccak256` (not secure for production)
- Ether transfers and resetting dynamic arrays
- Basic smart contract structure

## ⚠️ Disclaimer

> This project is for **educational purposes only**. The randomness method used is **not secure** for real-world applications. Do not use in production without proper security audits and integration of trusted randomness (e.g., Chainlink VRF).

## 📂 Files

- `lottry.sol` – Main Solidity contract

## 📌 Next Improvements (WIP Ideas)

- Chainlink VRF integration for randomness
- Frontend with React + Web3.js or Ethers.js
- Participant limit customization
- Gas optimization

---

Feel free to clone, fork, or suggest improvements. Happy building! 💻
