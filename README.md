# aetheris-public
[Read Aetheris White Paper v1.1 (Online)](WHITEPAPER.md)
# Aetheris Network

A Quantum-Resistant Layer 1 Distributed Ledger Architecture powered by a Block-DAG framework, WebAssembly (WASM) execution, and egalitarian network governance.

## 📄 Documentation
Read our official comprehensive technical specifications regarding module-lattice cryptography (ML-DSA), post-quantum identity layers, and anti-whale quadratic voting frameworks:
* [Read Aetheris White Paper v1.1 (Online)](WHITEPAPER.md)

## 🛠️ Devnet Mining
Our initial distributed verification network (Devnet) is officially live. The infrastructure consists of a centralized Master Node hosted in Germany, allowing remote user hardware to safely participate in parallel block validation tests.

### Quick Start Guide

1. Navigate to the **Releases** tab on the right side of this page and download the latest compiled `miner.exe` binary for Windows.
2. Download the default `config.json` file from the main repository into the exact same folder as your miner.
3. Open `config.json` with any text editor (like Notepad):
   * Replace the placeholder `0x0000...` address in `"mining_wallet_address"` with your personal Aetheris wallet address to claim your block rewards.
   * Adjust `"allocated_threads"` based on your CPU capability.
4. Launch the application by executing the binary. The core engine will automatically parse the local json matrix and establish a secure WAN pipeline to the target node:
```bash
   ./miner.exe
