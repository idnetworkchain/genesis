# IDNetwork Genesis Configuration

Welcome to the official **Genesis repository** for **IDNetwork**, a high-performance **Proof of Authority (IBFT)** sidechain of Ethereum.

This repository hosts the **genesis configuration files** used to initialize and deploy IDNetwork nodes for mainnet and future testnet environments.

---

## 🌐 Genesis Files

| Network | File | Raw Link |
|---------|------|-----------|
| **Mainnet** | [`mainnet.json`](mainnet.json) | [📄 View Raw](https://raw.githubusercontent.com/idnetworkchain/genesis/main/mainnet.json) |
| **Testnet** | *(coming soon)* | — |

---

## 🏗️ About IDNetwork

**IDNetwork** is a blockchain network built for real-world utility, optimized for:

- ⚡ Ultra-fast transaction finality (~5 seconds per block)
- 💰 Near-zero gas fees
- 🔗 EVM compatible
- 👥 Community-driven mining and reward systems

**Total Supply:** 1,000,000,000 IDN  
**Consensus:** PoA IBFT (Hyperledger Besu)  
**Block Time:** ~5 seconds

---

## ⚙️ How to Use

To start an **IDNetwork** node with Hyperledger Besu (IBFT):

```bash
besu \
  --data-path=/opt/besu/data \
  --genesis-file=/opt/besu/genesis/mainnet.json \
  --rpc-http-enabled \
  --rpc-http-api=ETH,NET,WEB3,ADMIN,TXPOOL,IBFT \
  --host-whitelist="*" \
  --rpc-http-cors-origins="*"

---

## 🧩 Tokenomics Overview

| Allocation           | Percentage | Description                                |
|----------------------|-----------|--------------------------------------------|
| Mining / Reward Pool | 60%       | Distributed to users via mining and staking |
| Team & Founder       | 10%       | With vesting (2–3 years)                  |
| Early Investors      | 10%       | 10% unlocked every 6 months               |
| Airdrop & Community  | 10%       | For marketing & community growth          |
| Treasury / Reserve   | 10%       | Ecosystem & development fund              |


