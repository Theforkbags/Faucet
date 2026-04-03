<p align="center">
  <img src="(https://i.imgur.com/SSmI7jm.png)" width="100%" alt="Faucet Banner" />
</p>

💧 $Faucet — Solana Token Faucet

A forked and extended Solana faucet built with Expo, Web3, and React Native — distributing $Faucet tokens to users who complete a CAPTCHA challenge.

Forked from moviendome/solana-faucet.

🧩 What Is This?
$Faucet is a community-driven Solana token faucet that lets users claim free $Faucet tokens on devnet by connecting their wallet and completing a simple CAPTCHA. It's designed to be lightweight, mobile-friendly, and easy to self-host — making it a great tool for projects that want to distribute tokens for testing, onboarding, or community engagement.

✨ Features

🔗 Connect Wallet — Supports Phantom and Solflare via @solana/wallet-adapter
🤖 CAPTCHA Verification — Users must solve a CAPTCHA before claiming tokens (bot protection)
🪙 $Faucet Token Distribution — Automatically sends $Faucet tokens to verified wallets
🌐 Devnet Ready — Built and tested on Solana devnet
📱 Cross-Platform — Runs on web, iOS, and Android via Expo


🛠 Tech Stack
TechnologyPurposeExpoCross-platform React Native frameworkReact NativeMobile UIWeb3.jsSolana blockchain interactions@solana/wallet-adapterWallet connection (Phantom, Solflare)TypeScript / JavaScriptApplication logic

🚀 Getting Started
Prerequisites

Node.js (v16+)
Yarn
Expo CLI

Installation
bash# Clone the repo
$ git clone https://github.com/Theforkbags/Faucet.git
$ cd Faucet

# Install dependencies
$ yarn install

# Start on web
$ expo web

# Or start on mobile
$ expo start

📖 How It Works

Connect your wallet — Click "Connect Wallet" and select Phantom or Solflare.
Complete the CAPTCHA — Solve the challenge to prove you're human.
Claim your tokens — The faucet automatically sends $Faucet tokens to your connected wallet address on devnet.


🗂 Project Structure
Faucet/
├── assets/          # Images and static assets
├── src/             # App source code (components, screens, hooks)
├── App.js           # Entry point
├── app.json         # Expo config
├── babel.config.js  # Babel config
├── package.json     # Dependencies
└── tsconfig.json    # TypeScript config

⚙️ Configuration
To configure the faucet for your own token, update the relevant constants in src/ (token mint address, airdrop amount, RPC endpoint, etc.).

⚠️ This project currently targets Solana Devnet. Do not use real funds.


🙏 Credits

Original project by moviendome
Abstract background by rawpixel.com on Freepik


📄 License
MIT — feel free to fork, modify, and build on top of this.
