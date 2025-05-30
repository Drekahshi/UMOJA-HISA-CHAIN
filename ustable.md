# Umoja Stable (UMOS)

## Overview
- **Symbol**: `UMOS`  
- **Token Type**: Algorithmic Stablecoin  
- **Supply Model**: Dynamically minted/burned (elastic supply)  
- **Primary Peg**: 1 UMOS = $1 USD  
- **Core Function**: Facilitate payments, trading, and real-world asset (RWA) tokenization within the Umoja ecosystem.

---

## Collateralization
UMOS is **over-collateralized** by a diversified reserve basket:

| Asset Type               | Allocation | Purpose                          |
|--------------------------|------------|----------------------------------|
| HBAR-backed USDC         | 40%        | Liquidity & fiat stability       |
| Kenyan Infrastructure Bonds | 30%        | Yield generation & regulatory alignment |
| Physical Gold            | 20%        | Inflation hedge                  |
| Bitcoin (BTC)            | 10%        | Volatility buffer & growth       |

---

## Key Features
### 1. Stability Mechanisms
- **Elastic Supply**: Automatically adjusts minting/burning to maintain peg.
- **Multi-Asset Backing**: Hybrid reserves mitigate single-point failures.
- **Hedera Integration**: Leverages sub-cent fees and 3-second finality.

### 2. Primary Use Cases
- 🪙 Base currency for DeFi trading pairs (e.g., `UMOT/UMOS`)
- 🌍 Cross-border remittances via M-Pesa/Binance/OKX integrations
- 🏠 Medium for RWA tokenization (e.g., land → NFT → UMOS liquidity)
- ⚖️ Settlement currency for UMOO options contracts

### 3. Accessibility
- **Mobile-First**: Works with feature phones via M-Pesa integration.
- **Zero-Knowledge KYC**: Privacy-preserving identity verification.
- **Low Entry Barrier**: Minimal fees for transactions/tokenization.

---

## Value Preservation
| Mechanism          | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| **Inflation Hedge**| 50% allocation to gold/bonds counters currency devaluation                 |
| **Yield Recycling**| Bond/gold yields reinvested to strengthen collateral ratio                  |
| **Transparency**   | Quarterly on-chain reserve audits                                           |

---

## Regulatory Compliance
- ✅ **KYC/AML**: Mandatory for high-value RWA tokenization (>$500 equivalent)
- ✅ **Tax Compliance**: Automated KRA withholding tax on capital gains/dividends
- ✅ **Data Protection**: GDPR-compliant protocols with 30-day data deletion cycles

---

## Ecosystem Role
```mermaid
graph LR
A[Land Owner] -->|Tokenizes Asset| B(Land NFT)
B -->|Receives| C[UMOS]
C --> D[Trades on DEX]
C --> E[Pays for Services]
C --> F[Sends via M-Pesa]