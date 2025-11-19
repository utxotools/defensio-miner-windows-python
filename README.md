# Welcome to DefensioMiner! 🚀

Thank you for trying out **DefensioMiner**, a high-performance, multi-process miner for the Defensio network.

## Getting Started

1.  **Download**: Get the latest `DefensioMiner.exe` release.
2.  **Run**: Double-click the executable to start.

## First Run & Wallet Setup

When you run the miner for the first time, it will detect that you don't have a wallet configured.

*   **Automatic Generation**: The miner will automatically generate a new secure wallet for you.
*   **SAVE YOUR SEED**: You will see a **Seed Phrase** (12-24 words) displayed prominently.
    > ⚠️ **CRITICAL**: Write these words down or save them in a secure password manager. The miner saves them locally in `my_secret_wallet.txt`, but if you lose this file and your seed, your funds are **lost forever**.

## Configuration

Every time you start the miner, you can configure how it utilizes your hardware:

1.  **CPU Cores**: Enter the number of CPU cores you want to dedicate to mining.
2.  **Wallet Pool Size**: Enter how many unique wallet addresses to generate.
    *   *Recommendation*: Set this to at least the number of cores. The miner rotates through these addresses to maximize efficiency.

## How it Works

*   **Dashboard**: You'll see a real-time dashboard showing your hashrate, active workers, and solutions found.
*   **Smart Rotation**: When a worker finds a solution, it automatically switches to a fresh wallet address from your pool to continue mining without interruption.
*   **Dev Fee**: To support development, there is a 10% developer fee. This means roughly 10% of the time, a worker will mine for the developer's address.

## Troubleshooting

*   **Crash on Start?** Ensure you are connected to the internet.
*   **"API Error"**: The Defensio API connection might be congested. The miner will automatically retry.

Happy Mining! ⛏️


