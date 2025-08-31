# SolanaNFTMarket

SolanaNFTMarket is an NFT marketplace built on Solana using Rust smart contracts.  
This project allows users to mint, list, and sell NFTs on the Solana devnet.

---

## Prerequisites
Make sure you are using a Linux environment.  
Windows users should use WSL (Windows Subsystem for Linux).  

You need the following installed:
- Rust (latest stable version recommended)  
- Solana CLI tools  
- Yarn (for frontend dependencies)  
- Phantom Wallet (or any Solana-compatible wallet in the browser)  
- A Solana wallet with SOL tokens (for devnet testing)  

---

## Devnet Configuration

Set Solana CLI to use devnet:

```bash
solana config set --url devnet
