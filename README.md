# 🪙 CryptoLwei Token — Custom ERC-20

A custom ERC-20-style token contract built on Ethereum. Built as part of the HackQuest Web3 developer certification.

## What It Does
- Owner-controlled minting — only the deployer can create tokens
- Balance tracking — any address can query any balance  
- Token transfers — holders can send tokens to others
- Total supply publicly readable

## Functions
| Function | Access | Description |
|----------|--------|-------------|
| `mint(address, uint256)` | Owner only | Creates new tokens |
| `balanceOf(address)` | Public | Returns token balance |
| `transfer(address, uint256)` | Public | Sends tokens to recipient |

## Tech Stack
- Solidity `0.8.17` · Ethereum · HackQuest

## Deploy & Test (Remix IDE)
1. Open remix.ethereum.org
2. Paste contract → compile `0.8.17`
3. Deploy → call `mint()` → verify with `balanceOf()`
