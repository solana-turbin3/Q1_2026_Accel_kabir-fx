# Turbin3 Accelerated Program - Proof of Work (PoW)

This repository is created under the **Turbin3 Accelerated Program** (Q1 2026), serving as a portfolio of projects, challenges, and assignments completed during the program, demonstrating proficiency and progress in Solana smart contract development.

## Repository Structure

This repository is structured using Git submodules for each individual project to keep their individual codebases and commits independent, while still easily accessible from this main directory.

Here is an overview of the projects included in this Proof of Work:

- **Serialization-enabled-storage**: Implementation of custom data serialization and storage using Borsh, Wincode and JSON in pure Rust.
- **accel-week2-challenge**: A Solana GPT Oracle program that allows users to interact with an LLM and delegate interactions using Magicblock's Ephemeral Rollups with autonomous scheduling using Tuktuk.
- **escrow-litesvm**: An escrow program implementation utilizing `litesvm` for fast and efficient local testing.
- **magicblock-er-example**: An example implementation exploring Magicblock Ephemeral Rollup (ER) features.
- **transfer_enabled_vault**: A Token-2022 Transfer Hook program implementing a secure vault, utilizing `litesvm` for fast and efficient local testing.
- **whitelist-transfer-hook**: A Token-2022 transfer hook implementation designed to restrict token transfers to a whitelist of approved addresses with autonomous instruction scheduling using Tuktuk.

## Getting Started

Since this repository utilizes Git submodules, make sure you clone it with the `--recursive` flag to pull all the linked projects:

```bash
git clone --recursive https://github.com/solana-turbin3/Q1_2026_Accel_kabir-fx.git
```

If you have already cloned the repository normally, you can fetch and initialize the submodules by running:

```bash
git submodule update --init --recursive
```

To explore any specific project, change directories into the respective folder and follow its individual `README.md` instructions (if available) for building and testing.
