# ⚡ PowLayer

**PowLayer** is a next-generation **Proof-of-Work Layer 1 blockchain**, built on **Ethash** with full **EVM compatibility**.  
It is designed for developers, miners, and communities who believe in decentralization, fair distribution, and censorship resistance.

🌐 Website: [https://powlayer.com](https://powlayer.com)

---

## ✨ Features

- ⛏️ **Proof-of-Work** — Ethash consensus, battle-tested and secure.
- 💠 **EVM Compatible** — Fully supports Ethereum tooling, dApps, and smart contracts.
- 📦 **Fixed Supply** — Transparent and predictable emission.
- 🔒 **No Dev Fees** — 100% of block rewards go to miners.
- 🚫 **No Uncle Rewards** — Simplified and fair issuance.
- 🌍 **Open for DeFi, NFTs, GameFi, SocialFi** — Build anything on chain.

---

## 📊 Emission Schedule

| Block Range             | Reward (XPL) | Total Supply in Range |
|--------------------------|--------------|------------------------|
| 1 → 500,000             | 1.0 XPL      | 500,000 XPL            |
| 500,001 → 1,500,000     | 0.5 XPL      | 500,000 XPL            |
| 1,500,001 → 71,500,000  | 0.1 XPL      | 7,000,000 XPL          |
| **Total**               | —            | **8,000,000 XPL**      |

⚠️ After block **71,500,000**, block reward drops to **0**.  
This makes XPL a **hard-capped, deflationary** supply currency.

---

## 🚀 Getting Started

### 🔧 Build from source
```bash
git clone https://github.com/PowLayer/go-PowLayer
cd go-PowLayer
go build -o build/bin/geth ./cmd/geth
````

### ⛏️ Run a node

```bash
./build/bin/geth --networkid 70707 --datadir ./data --http --http.api "eth,net,web3,miner"
```

### ⛏️ Start mining

```bash
./build/bin/geth --mine --miner.threads=4 --miner.etherbase=0xYourAddressHere
```

---

## 🌍 Community

* 🐦 [Twitter / X](https://x.com/Pow_Layer)
* 💬 [Discord](https://discord.gg/x3Spx5GMjs)
* 📢 [Telegram](https://t.me/PowLayerChat)

---

⛏️ **Mine. Build. Decentralize.** ⚡
