# Tethra DEX 🚀

![Solidity](https://img.shields.io/badge/Solidity-0.8.20-blue)
![Next.js](https://img.shields.io/badge/Next.js-15-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![Flow](https://img.shields.io/badge/Flow-EVM-00EF8B)
![Base](https://img.shields.io/badge/Base-Sepolia-0052FF)

> Multi-chain perpetual futures trading platform with up to 100x leverage. Built on Flow EVM & Base Sepolia.

## ✨ Features

- ⚡ **100x Leverage** on BTC/ETH perpetual futures
- 🌐 **Multi-Chain** - Flow EVM & Base Sepolia
- 💵 **USDC Gas Payments** via Account Abstraction
- 🎯 **Advanced Orders** - Limit, Stop-Loss, Take-Profit
- 🔐 **Social Login** with Privy (email/social + embedded wallets)
- 📊 **12+ Assets** - BTC, ETH, SOL, AVAX, NEAR, and more

## 🏗️ Architecture

```
tethrafi/
├── smartcontract/     # Solidity contracts (Foundry)
├── backend/           # Node.js API + Keeper services
└── frontend/          # Next.js 15 trading interface
```

## 🚀 Quick Start

```bash
# Smart Contracts
cd smartcontract && forge build && forge test

# Backend
cd backend && npm install && npm run dev

# Frontend
cd frontend && npm install && npm run dev
```

📖 Detailed docs: [Smart Contracts](./smartcontract/README.md) | [Backend](./backend/README.md) | [Frontend](./frontend/README.md)

## 🌐 Networks

| Network | Chain ID | Explorer |
|---------|----------|----------|
| Flow EVM Testnet | 545 | [flowscan.io](https://evm-testnet.flowscan.io/) |
| Base Sepolia | 84532 | [basescan.org](https://sepolia.basescan.org/) |

## 🛠️ Tech Stack

**Contracts:** Solidity 0.8.20, Foundry, OpenZeppelin  
**Backend:** Node.js, Express, TypeScript, Pyth Oracle  
**Frontend:** Next.js 15, React 19, TailwindCSS 4, Privy, Wagmi

## 📄 License

MIT License

---

**Built with ❤️ by Tethra Team**
