# vemius-node - MEV-Optimized Sui Node

**vemius-node** is a customized fork of `sui-node`, specifically optimized for MEV (Maximal Extractable Value) scenarios. It aims to provide validators, arbitrageurs, and block builders with enhanced transaction capture and execution capabilities.

## 🚀 Features

- Full compatibility with standard `sui-node` configuration
- Extended configuration options for MEV operations:
  - `unix-socket-path` - For high-performance local IPC
  - `geyser` - Plugin interface for real-time account updates

## ⚙️ Usage

You can execute it just like the regular [sui-node](https://docs.sui.io/guides/operator/sui-full-node)
```bash
vemius-node --config-path fullnode.yaml
