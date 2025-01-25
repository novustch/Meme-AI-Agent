<div align="center">

![Banner](https://github.com/user-attachments/assets/a9599b15-44d2-48a9-ad8c-6bcff68970f6)


# JLB AI Agents

Introducing the JLB AI Agent, an innovative solution built on the Solana blockchain that harnesses the power of artificial intelligence to revolutionize digital interactions. Designed to automate complex tasks and optimize decision-making, JLB empowers users with real-time analytics and efficient operations in the DeFi space. With its ability to learn and adapt, JLB aims to provide seamless integration and meaningful insights for both newcomers and experienced crypto enthusiasts. Experience the future of autonomous technology with JLB, where AI meets the dynamic landscape of blockchain.

</div>

# Overview

An JLB AI Agent for connecting AI agents to Solana protocols. Now, any agent, using any model can autonomously perform 15+ Solana actions:

1. **Blockchain Agent Chat Terminal**
   - Real-time Streaming Implementation
   - Blockchain Integration
   - UI Components Design
2. Trading Infrastructure
   - Jupiter Exchange swaps
   - Launch on Pump via PumpPortal
   - Raydium pool creation (CPMM, CLMM, AMMv4)
   - Orca Whirlpool integration
   - Manifest market creation and limit orders
   - Meteora Dynamic AMM, DLMM Pool, and Alpha Vault
   - Openbook market creation
   - Register and resolve SNS
   - Jito Bundles
   - Pyth Price feeds for fetching asset prices
   - Perpetuals trading with Adrena Protocol
   - Drift Vaults, Perps, Lending, and Borrowing
3. Analytics and Automation
   - Dashboard for Real-time Market Analytics
   - Whale Monitoring
   - DeFi Insights
   - NFT Management
   - NFT Listing Automtaion
   - Multichain-bridge to Solana
   - Autonomous trading agent powered by JLB AI
4. Expand Cross-Chain Support & Security Features
   - Interoperability
   - Enhanced Security Tools
   - Comprehensive Ecosystem Integration

5. Full Decentralization with Community Governance
   - Decentralized Architecture
   - Community-Led Decision Making
   - Sustainability and Growth

Anyone - whether an SF-based AI researcher or a crypto-native builder - can bring their AI agents trained with any model and seamlessly integrate with Solana.

[![Run on Repl.it](https://replit.com/badge/github/earthzetaorg/solana-ai-agents)](https://replit.com/@earthzetaorg/solana-ai-agents)

## 🔧 Core Blockchain Features

- **Token Operations**
  - Deploy SPL tokens by Metaplex
  - Transfer assets
  - Balance checks
  - Stake SOL
  - Zk compressed Airdrop by Light Protocol and Helius
- **NFTs on 3.Land**
  - Create your own collection
  - NFT creation and automatic listing on 3.land
  - List your NFT for sale in any SPL token
- **NFT Management via Metaplex**
  - Collection deployment
  - NFT minting
  - Metadata management
  - Royalty configuration

- **DeFi Integration**
  - Jupiter Exchange swaps
  - Launch on Pump via PumpPortal
  - Raydium pool creation (CPMM, CLMM, AMMv4)
  - Orca Whirlpool integration
  - Manifest market creation, and limit orders
  - Meteora Dynamic AMM, DLMM Pool, and Alpha Vault
  - Openbook market creation
  - Register and Resolve SNS
  - Jito Bundles
  - Pyth Price feeds for fetching Asset Prices
  - Register/resolve Alldomains
  - Perpetuals Trading with Adrena Protocol
  - Drift Vaults, Perps, Lending and Borrowing

- **Solana Blinks**
   - Lending by Lulo (Best APR for USDC)
   - Send Arcade Games
   - JupSOL staking
   - Solayer SOL (sSOL)staking

- **Non-Financial Actions**
  - Gib Work for registering bounties

## 🤖 AI Integration Features

- **LangChain Integration**
  - Ready-to-use LangChain tools for blockchain operations
  - Autonomous agent support with React framework
  - Memory management for persistent interactions
  - Streaming responses for real-time feedback

- **Vercel AI SDK Integration**
  - Vercel AI SDK for AI agent integration
  - Framework agnostic support
  - Quick and easy toolkit setup

- **Autonomous Modes**
  - Interactive chat mode for guided operations
  - Autonomous mode for independent agent actions
  - Configurable action intervals
  - Built-in error handling and recovery

- **AI Tools**
  - DALL-E integration for NFT artwork generation
  - Natural language processing for blockchain commands
  - Price feed integration for market analysis
  - Automated decision-making capabilities


## 📦 Installation

```bash
npm install solana-ai-agents
```

## Quick Start

```typescript
import { JLBAIAgent, createSolanaTools } from "solana-ai-agents";

// Initialize with private key and optional RPC URL
const agent = new JLBAIAgent(
  "your-wallet-private-key-as-base58",
  "https://api.mainnet-beta.solana.com",
  "your-openai-api-key"
);

// Create LangChain tools
const tools = createSolanaTools(agent);
```

## Usage Examples

- Deploy a New Token

- Create NFT on 3Land
When creating an NFT using 3Land's tool, it automatically goes for sale on 3.land website

- Create NFT Collection

- Swap Tokens

- Lend Tokens

- Stake SOL

- Stake SOL on Solayer

- Send an SPL Token Airdrop via ZK Compression

- Fetch Price Data from Pyth

- Open PERP Trade

- Close PERP Trade

- Close Empty Token Accounts

- Create a Drift account

- Create a Drift Vault

- Deposit into a Drift Vault

- Deposit into your Drift account

- Derive a Drift Vault address

- Do you have a Drift account

- Get Drift account information

- Request withdrawal from Drift vault

- Carry out a perpetual trade using a Drift vault

- Carry out a perpetual trade using your Drift account

- Update Drift vault parameters

- Withdraw from Drift account

- Borrow from Drift

- Repay Drift loan

- Withdraw from Drift vault

- Update the address a Drift vault is delegated to

- Get Voltr Vault Position Values

- Deposit into Voltr Strategy

- Withdraw from Voltr Strategy

- Get a Solana asset by its ID

## Examples

### LangGraph Multi-Agent System

The repository includes an advanced example of building a multi-agent system using LangGraph and JLB AI Agent. Located in `examples/agent-kit-langgraph`, this example demonstrates:

- Multi-agent architecture using LangGraph's StateGraph
- Specialized agents for different tasks:
  - General purpose agent for basic queries
  - Transfer/Swap agent for transaction operations
  - Read agent for blockchain data queries
  - Manager agent for routing and orchestration
- Fully typed TypeScript implementation
- Environment-based configuration

Check out the [LangGraph example](examples/agent-kit-langgraph) for a complete implementation of an advanced Solana agents system.

## Dependencies

The toolkit relies on several key Solana and Metaplex libraries:

- @solana/web3.js
- @solana/spl-token
- @metaplex-foundation/digital-asset-standard-api
- @metaplex-foundation/mpl-token-metadata
- @metaplex-foundation/mpl-core
- @metaplex-foundation/umi
- @lightprotocol/compressed-token
- @lightprotocol/stateless.js

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
Refer to [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines on how to contribute to this project.

## Contributors

<a href="https://github.com/earthzetaorg/solana-ai-agents/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=earthzetaorg/solana-ai-agents" />
</a>

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=earthzetaorg/solana-ai-agents&type=Date)](https://star-history.com/#earthzetaorg/solana-ai-agents&Date)

## License

Apache-2 License

## Funding

If you wanna give back any tokens or donations to the OSS community -- The Public JLB AI Agents Treasury Address:

## Security

This toolkit handles private keys and transactions. Always ensure you're using it in a secure environment and never share your private keys.

# 👋 Contact Me

### 
Telegram: https://t.me/earthzeta
###
<div style={{display : flex ; justify-content : space-evenly}}> 
    <a href="https://t.me/earthzeta" target="_blank"><img alt="Telegram"
        src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white"/></a>
    <a href="https://discordapp.com/users/339619501081362432" target="_blank"><img alt="Discord"
        src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white"/></a>
</div>
