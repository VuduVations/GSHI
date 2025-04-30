#  DEXs, Token Swaps, Liquidity Pools & Automated Market Makers

At the heart of decentralized finance (DeFi) lies a powerful innovation: **decentralized exchanges (DEXs)** powered by **Automated Market Makers (AMMs)** and **liquidity pools**—enabling trustless token swaps without the need for intermediaries.

---

##  What is a DEX?

A **Decentralized Exchange (DEX)** allows users to trade crypto assets directly from their wallets via smart contracts—no central custody or intermediaries required.

### Key Attributes:
- Non-custodial
- On-chain trading
- Typically powered by AMMs
- Users provide liquidity to pools, not order books

---

<p align="center">
  <img src=../figures/A_flat-style_digital_infographic_titled_"Decentra.png" alt="DEX and Liquidity Pools">
</p>

---

##  Token Swaps

Token swaps on DEXs:
- Allow users to trade Token A for Token B in a single transaction
- Use **liquidity pools** to determine price
- Do not rely on centralized order books or matching engines

Popular protocols: **Uniswap**, **SushiSwap**, **Curve**, **Balancer**

---

##  What Are Liquidity Pools?

A **liquidity pool** is a smart contract that holds two or more tokens in a trading pair, e.g., ETH/USDC.

### Example: ETH/USDC Pool
- Users deposit equal value of ETH and USDC into the pool
- Pool enables trading between the two tokens
- Users earn a % of trading fees based on their share of the pool

### Benefits:
- Continuous liquidity
- Incentivized participation (yield)
- Foundation for AMM pricing

---

##  Automated Market Makers (AMMs)

**AMMs** are algorithms that define how assets are priced and traded in a liquidity pool.

### Classic AMM Formula (Uniswap v2):

\[
x \cdot y = k
\]

- \( x \) = quantity of Token A  
- \( y \) = quantity of Token B  
- \( k \) = constant product (total liquidity)

> As more of Token A is bought, Token B becomes more expensive — ensuring balance.

---

##  Impermanent Loss

Liquidity providers are exposed to **impermanent loss** when token prices diverge.

- If Token A increases significantly in value compared to Token B...
- The pool rebalances via AMM logic
- The provider may end up with **less of the appreciating asset**

Mitigation strategies:
- Use **stablecoin pools** (e.g., USDC/DAI)
- Participate in incentivized pools with higher yield
- Leverage dynamic AMM models (e.g., Curve’s stable swap algorithm)

---

##  Role in GSHI Ecosystem

### GSHI DEX Features:
- **User-friendly swaps** with compliance filters
- **DAO-governed liquidity incentives**
- **Algorithmic market making** for custom pools
- **Liquidity mining** to support token launches

### Strategic Position:
| DEX Feature              | GSHI Adaptation                           |
|--------------------------|-------------------------------------------|
| Token Swaps              | UX-optimized swap interface               |
| Custom AMM Logic         | Sector-based or volatility-based pricing  |
| Liquidity Pool Incentives| DAO-voted APR mechanisms                  |
| Regulatory Screening     | KYC/AML enforcement on UI layer           |

---

##  Key Innovations in the Space

| Protocol      | Innovation                           |
|---------------|---------------------------------------|
| Uniswap v3    | Concentrated liquidity                |
| Curve         | Stablecoin-optimized AMMs             |
| Balancer      | Multi-asset, weighted pools           |
| ThorChain     | Cross-chain swaps                     |
| Bancor v3     | Impermanent loss protection           |

---

##  Related Sections

- [Staking, Yield & Liquidity](03-staking-yield-liquidity.md)
- [DeFi, CeFi & CeDeFi Models](08-defi-cefi-cedefi.md)
- [DAO Governance](07-dao-architecture.md)

---

**Takeaway**:  
DEXs and AMMs represent the **financial engine** of DeFi—removing middlemen and empowering programmable liquidity, price discovery, and trading infrastructure.

---
 [Back to README](../README.md)
