# pump-arena-protocol

# The Arena (Arena.fun)

**Turning the pump.fun PVP experience into a high-stakes, skill-based prediction market.**

Building for the **$3,000,000 pump.fun "Build in Public" Hackathon**. 

The Arena is a decentralized prediction layer where users bet on the outcome of bonding curves in real-time. Don't just trade the tokens—bet on the builders, the momentum, and the graduation to Raydium.

---

## 🏗️ Technical Architecture

### 1. The Oracle (Data Ingestion)
Using the **PumpPortal API** via WebSockets to listen to:
* `subscribeNewToken`: Automatic listing of Arena betting pools.
* `subscribeTokenTrade`: Real-time odds shifting based on buy/sell volume.

### 2. The Betting Engine (Solana/Rust)
A custom Anchor program that handles:
* **Vaults:** Securely holding $ARENA/SOL stakes.
* **Settlement:** Automated payouts triggered by the bonding curve reaching the "graduation" address.

### 3. High-Performance Frontend
* **Framework:** Next.js 14 (App Router)
* **Styling:** Tailwind CSS + Framer Motion (for that "Arena" feel)
* **Wallet:** @solana/wallet-adapter for seamless 1-click betting.

---

## 🤝 Build In Public
This project is being built entirely in public. Check the commit history for daily updates and follow our journey on X.

---
Created with ⚔️ by [@scarfacepog]
