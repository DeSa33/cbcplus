# CBC Plus (CBC+) - Democratized Mining on Polygon

## 🚀 Official Mining Reward Token

CBC Plus revolutionizes cryptocurrency mining by making it accessible on standard computers. No expensive ASICs, no power-hungry GPUs - just your laptop earning real rewards.

### ⚡ Quick Facts
- **Contract**: `0x5e21eF2c6150b510c27EB7E5eD87c482C3794426`
- **Network**: Polygon (MATIC) 
- **Symbol**: CBC+
- **Decimals**: 18
- **Daily Emission**: 10,000 CBC+
- **Launch Date**: August 2025

### 💱 Trade CBC+
**[🔄 Trade on Uniswap](https://app.uniswap.org/swap?chain=polygon&inputCurrency=0x2791Bca1f2de4661ED88A30C99A7a9449Aa84174&outputCurrency=0x5e21eF2c6150b510c27EB7E5eD87c482C3794426)**

Live CBC+/USDC liquidity pool with 0.3% fee tier. Trade instantly with no KYC.

### 📊 Tokenomics

#### Daily Distribution Model
- **Fixed Emission**: 10,000 CBC+ per day
- **Annual Emission**: ~3.65M CBC+
- **Distribution**: 100% to miners
- **Pre-mine**: ZERO
- **Team Allocation**: ZERO

#### Miner Tier System
| Tier | Daily Cap | Requirements | Purpose |
|------|-----------|--------------|---------|
| **Probation** | 80 CBC+ | New miners (first 30 days) | Prevent sybil attacks |
| **Standard** | 120 CBC+ | 30+ days of mining | Verified participants |
| **Trusted** | 160 CBC+ | 90+ days, consistent mining | Reward loyalty |

### ⛏️ Mining System

#### How It Works
1. **Download Mining Software**: Lightweight client for Windows/Mac/Linux
2. **Connect Wallet**: Use any Polygon-compatible wallet
3. **Start Mining**: Earn CBC+ proportional to your contribution
4. **Claim Rewards**: Every 5-minute epoch

#### Mining Features
- **CPU-Optimized**: Designed for standard processors
- **ASIC-Resistant**: Memory-hard algorithm prevents hardware monopoly
- **Energy Efficient**: Laptop-friendly power consumption
- **Fair Distribution**: Tier caps ensure no single miner dominates

#### Technical Specifications
- **Algorithm**: Modified SHA-256 with memory-hard functions
- **Epoch Length**: 5 minutes
- **Difficulty Adjustment**: Dynamic per epoch
- **Target Hashrate**: Balanced for 10,000 CBC+ daily

### 🔒 Security Features

#### Smart Contract Security
- ✅ OpenZeppelin v5 Framework
- ✅ Role-Based Access Control (RBAC)
- ✅ Pausable in emergencies
- ✅ Epoch replay protection
- ✅ Daily mint limits hardcoded
- ✅ No upgradeable proxy (immutable)

#### Anti-Exploit Measures
- **Replay Guard**: Each epoch can only be claimed once
- **Daily Caps**: Hard limits per miner address
- **Global Limit**: Maximum 11,500 CBC+ daily (15% buffer)
- **Tier System**: Prevents concentration of rewards

### 📈 Roadmap

#### Phase 1: Launch ✅ (August 2025)
- [x] Smart contract deployment
- [x] Uniswap V3 pool creation
- [x] Initial liquidity provision
- [x] Mining software beta

#### Phase 2: Growth 🚧 (September 2025)
- [ ] 200+ active miners
- [ ] Treasury bot activation
- [ ] CoinGecko listing
- [ ] Additional DEX liquidity

#### Phase 3: Expansion 📅 (Q4 2025)
- [ ] Cross-chain bridges
- [ ] Mobile mining app
- [ ] Governance implementation
- [ ] Partnership integrations

#### Phase 4: Ecosystem 🔮 (2026)
- [ ] CBC+ payment integrations
- [ ] Staking mechanisms
- [ ] Advanced mining pools
- [ ] DeFi collaborations

### 💰 Treasury & Economics

#### Automated Treasury Bot
- **Function**: Maintains price stability
- **Buy Support**: Activates at $0.009 (stops at $0.010)
- **Sell Pressure Relief**: Activates at $0.016 (stops at $0.015)
- **Funding**: 33,000 USDC initial capital
- **Transparency**: All transactions on-chain

#### Market Mechanics
- **Initial Price**: $0.01 per CBC+
- **Liquidity**: CBC+/USDC on Uniswap V3
- **Price Discovery**: Pure market-driven
- **MEV Protection**: Built into treasury bot

### 🛠️ Technical Integration

#### For Developers
```solidity
// Contract Interface
interface ICBCPlus {
    function mintReward(address to, uint256 amount, uint256 epochId) external;
    function setMinerTier(address miner, Tier tier) external;
    function getMintingStats() external view returns (uint256, uint256, uint256);
}

// Contract Address
0x5e21eF2c6150b510c27EB7E5eD87c482C3794426
```

#### Mining API Endpoints
```bash
# Get current epoch
GET /epoch

# Submit proof of work
POST /submit
{
  "address": "0x...",
  "nonce": 123456,
  "hash": "0x..."
}

# Check mining stats
GET /stats/{address}
```

### 🌐 Official Links

#### Primary Resources
- 📊 [PolygonScan Explorer](https://polygonscan.com/token/0x5e21eF2c6150b510c27EB7E5eD87c482C3794426)
- 💱 [Uniswap Trading](https://app.uniswap.org/swap?chain=polygon&outputCurrency=0x5e21eF2c6150b510c27EB7E5eD87c482C3794426)
- 📈 [DexScreener Charts](https://dexscreener.com/polygon/0x5e21eF2c6150b510c27EB7E5eD87c482C3794426)

#### Community
- 💬 [Telegram](https://t.me/CBCPlusOfficial)
- 🐦 [Twitter](https://twitter.com/CBCPlusToken)
- 💭 [Discord](https://discord.gg/cbcplus)

#### Documentation
- 📄 [Whitepaper](./whitepaper.md)
- 📖 [Mining Guide](./docs/mining-guide.md)
- 🔧 [API Documentation](./docs/api.md)

### 🤝 Contributing

We welcome community contributions! Please see our [Contributing Guidelines](./CONTRIBUTING.md) for details.

#### Ways to Contribute
- 🐛 Report bugs
- 💡 Suggest features
- 📝 Improve documentation
- 🔧 Submit pull requests

### ⚖️ Legal

#### Disclaimer
CBC+ is an experimental cryptocurrency project. Mining and trading involve risks. Not available in restricted jurisdictions. Always do your own research.

#### License
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

### 📞 Support

Need help? Reach out through:
- **Telegram**: [@CBCPlusOfficial](https://t.me/CBCPlusOfficial)
- **Email**: support@cbcplus.io
- **Discord**: [Join Server](https://discord.gg/cbcplus)

---

<div align="center">

**CBC Plus - Mining for Everyone**

*Democratizing cryptocurrency mining one block at a time*

[![Polygon](https://img.shields.io/badge/Polygon-Network-purple)](https://polygon.technology)
[![Uniswap](https://img.shields.io/badge/Trade-Uniswap-pink)](https://app.uniswap.org)
[![License](https://img.shields.io/badge/License-MIT-blue)](./LICENSE)

</div>
