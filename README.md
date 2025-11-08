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

## 🧩 Tokenomics Overview

| Allocation           | Percentage | Description                                |
|----------------------|-----------|--------------------------------------------|
| Mining / Reward Pool | 60%       | Distributed to users via mining and staking |
| Team & Founder       | 10%       | With vesting (2–3 years)                  |
| Early Investors      | 10%       | 10% unlocked every 6 months               |
| Airdrop & Community  | 10%       | For marketing & community growth          |
| Treasury / Reserve   | 10%       | Ecosystem & development fund              |

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
```

---

## 🔹 Validators

To join the network as a validator, add your enode and address in the mainnet.json under the validators section. Each validator must follow IBFT rules for block signing.

---

## ⏱️ Epoch & Block Configuration

- Block Time: ~5 seconds
- Epoch Length: Configurable in genesis, determines when validator votes are applied
- Chain ID: 8824

---

## 📞 Contact & Resources

- 🌍 Website: [https://idnetwork.asia](https://idnetwork.asia)
- 💬 Telegram: [https://t.me/idnetworkchain](https://t.me/idnetworks)
- 🐙 GitHub: [https://github.com/idnetworkchain](https://github.com/idnetworkchain)

---

## 💼 Wallet

- **Mobile App (Android)**: [Download Here](https://apps.idnetwork.asia/invite/UGKWSC)
- **Supported Wallets**: MetaMask, WalletConnect, TrustWallet


