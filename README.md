# Liberty Project Miner

Welcome to the **Liberty Project Miner**! This repository contains the miner for the Liberty Project testnet. The testnet coin is **tLBRT**, and this miner enables participants to contribute to the network by mining blocks and earning rewards.

---

## Downloads

**Latest Release v0.3.5:**

- [Linux (amd64)](https://github.com/LibertyProject-chain/Liberty-miner-testnet-phase-3/releases/download/v0.3.5/liberty-linux-amd64)
- [Windows (amd64)](https://github.com/LibertyProject-chain/Liberty-miner-testnet-phase-3/releases/download/v0.3.5/liberty-windows-amd64.exe)

---

## How to Start Mining

### Basic Command

```bash
./miner <url-rpc> <number-of-threads> <wallet-address>
```

### Example

```bash
./miner http://78.29.35.87:9945 24 0xF4bd729Bb35B3741B465DCEA284E776Cf0444Dc2
```

### Parameters

- **`<url-rpc>`**: The RPC URL of the node you want to connect to.
- **`<number-of-threads>`**: The number of CPU threads to use for mining.
- **`<wallet-address>`**: Your wallet address to receive mining rewards.

---

## Public RPC URLs

We provide public RPC endpoints for different regions to ensure low latency and reliable connections:

- **FIN**: [https://rpc.libertyproject.space/](https://rpc.libertyproject.space/)
- **RUS**: [https://rpc2.libertyproject.space/](https://rpc2.libertyproject.space/)
- **USA**: [https://rpc3.libertyproject.space/](https://rpc3.libertyproject.space/)

Use the appropriate RPC URL based on your geographical location.

---

## Requirements

- **Hardware**: x86-64 CPU
- **Operating System**: Linux or Windows (amd64)
- **Dependencies**: Ensure that your environment supports the provided binaries.

---

## Contribution

This miner is part of the Liberty Project's **testnet phase 3**. We welcome feedback and contributions to improve the miner and the ecosystem.

Feel free to create issues or submit pull requests for enhancements.

---

### License

This project is licensed under the [MIT License](LICENSE).

---

Happy mining! 🚀

