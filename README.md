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

