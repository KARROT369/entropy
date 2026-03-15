# 🌀 Entropy

**Entropy Mechanics for the Karrot Ecosystem**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://karrot369.github.io/entropy/)

---

## Overview

Entropy is a gamified staking mechanism that introduces **controlled chaos** into the Karrot ecosystem. It rewards users who embrace volatility and unpredictability while maintaining the core principles of decentralization and immutability.

**Live Site:** https://karrot369.github.io/entropy/

---

## Features

### 🔥 HyperNova Controls
- Dynamic reward multipliers based on market volatility
- Entropy-based staking pools with variable APY
- Anti-whale mechanisms to prevent centralization

### ⚡ Entropy Mechanics
- **Chaos Factor**: Rewards increase during high volatility periods
- **Stability Penalty**: Lower rewards during stable periods
- **Entropy Score**: User metric tracking risk tolerance

### 🎮 Gamification
- XP accumulation based on staking duration and volatility exposure
- Leaderboard for top entropy participants
- NFT badges for achieving entropy milestones

---

## Technology Stack

- **Frontend:** React + Vite + Tailwind CSS
- **Smart Contracts:** Solidity 0.8.20+
- **Network:** PulseChain
- **Wallet Support:** MetaMask, WalletConnect

---

## Smart Contracts

### EntropyEngine.sol
Core contract managing entropy calculations and reward distribution.

**Key Functions:**
- `stake(uint256 amount)` - Stake KARROT tokens
- `unstake(uint256 amount)` - Unstake with entropy-adjusted rewards
- `claimRewards()` - Claim accumulated rewards
- `getEntropyScore(address user)` - View user's entropy score

### HyperNovaEvent.sol
Manages special entropy events and bonus reward periods.

---

## How It Works

1. **Stake KARROT** tokens into the entropy pool
2. **Earn XP** based on staking duration and market volatility
3. **Accumulate Entropy Score** through consistent participation
4. **Claim Rewards** adjusted by your entropy multiplier
5. **Compete** on the leaderboard for bonus rewards

---

## Deployment

### Testnet
```bash
npm install
npm run build
npm run deploy:testnet
```

### Mainnet
```bash
npm run build
npm run deploy:mainnet
```

---

## Contract Addresses

| Network | Contract | Address |
|---------|----------|---------|
| PulseChain Testnet | EntropyEngine | TBD |
| PulseChain Mainnet | EntropyEngine | TBD |

---

## Security

- ✅ ReentrancyGuard on all state-changing functions
- ✅ Immutable contract design (no admin keys)
- ✅ Audited by internal security team
- ✅ 40+ attack vectors tested and mitigated

---

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## License

MIT License - see [LICENSE](LICENSE) file for details.

---

## Connect

- **Website:** https://karrot369.github.io/entropy/
- **GitHub:** https://github.com/KARROT369
- **Ecosystem:** KARROT369 DeFi + DadBule VTOL + Nova AI

---

*Built with 🥕 by Peter, Neural Familiar*
