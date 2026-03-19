# NEXUS PAY
### The Zero-Friction Borderless Billing Protocol

> Create a payment link in seconds. Get paid in any currency, on any chain, from anywhere in the world.

---

## What is Nexus Pay?

Nexus Pay is a decentralized invoicing and payment gateway built for the modern economy — freelancers, merchants, and AI agents who need to send and receive money across borders without friction, fees, or banks.

A user creates a **Payment Link** in seconds. The payer opens the link and pays using their preferred chain. The merchant receives stablecoins instantly. No bank account required. No intermediaries.

---

## The Problem

Cross-border payments are broken:
- Freelancers wait 5–10 days for international wire transfers
- Merchants lose 3–5% to card network fees
- Crypto payments require technical knowledge most users don't have
- No single tool works across chains without switching wallets and apps

---

## The Solution

Nexus Pay abstracts all of that away into one link.

```
nexuspay.xyz/pay/invoice_abc123
```

The payer clicks, picks their preferred chain, confirms — done. The merchant sees the payment settle in real time.

---

## Supported Payment Rails

| Chain | Status | Best For | Asset |
|-------|--------|----------|-------|
| **Tempo** | ✅ Mainnet Live | Institutional & B2B payments | USDC |
| **Base** | ✅ Mainnet Live | Retail & social payments | USDC |
| **Arc** | 🟡 Testnet | Native USDC speed | USDC |
| **Solana** | 🔜 Coming Soon | Micropayments & point-of-sale | USDC |
| **Sui** | 🔜 Coming Soon | High-frequency transactions | USDC |

### Why Tempo is the Core Rail

Tempo — built by Stripe and Paradigm — is purpose-built for stablecoins in the real world. For Nexus Pay's primary use case (B2B invoicing, freelancer payouts, merchant settlements), Tempo provides:

- Institutional-grade finality
- Stripe's compliance infrastructure
- Native USDC support with real-world settlement
- Agentic payment compatibility via MPP (Machine Payments Protocol)

Tempo is the backbone. Every other chain is an on-ramp.

### Network Details

| Property | Tempo Mainnet | Base Mainnet | Arc Testnet |
|----------|--------------|--------------|-------------|
| **Chain ID** | 4217 | 8453 | 5042002 |
| **RPC** | https://rpc.tempo.xyz | https://mainnet.base.org | https://rpc.testnet.arc.network |
| **Explorer** | https://explore.tempo.xyz | https://basescan.org | https://testnet.arcscan.app |
| **USDC** | 0x1c7D4B196... | 0x833589fCD6... | Native |

---

## Key Features

- **One-click Payment Links** — generate a shareable invoice URL in under 10 seconds
- **Multi-chain Checkout** — payer selects their preferred chain at checkout
- **Real-time Settlement** — funds arrive in your wallet, not a custodial account
- **No Sign-up for Payers** — payers just connect wallet and pay
- **Dashboard** — track all invoices, payment status, and history
- **Real USDC Transfers** — ERC-20 token transfers on all supported chains

---

## How It Works

```
1. Merchant creates invoice → sets amount, description, wallet address
2. Nexus Pay generates a unique payment link
3. Merchant shares link via email, DM, or embeds in app
4. Payer opens link → connects wallet → selects chain → pays
5. Merchant receives USDC directly to wallet
6. Invoice marked as PAID — both parties get confirmation
```

---

## Use Cases

- **Freelancers** billing international clients without a bank account
- **Merchants** accepting crypto at point-of-sale
- **DAOs** paying contributors across chains
- **AI Agents** autonomously settling invoices in agentic workflows
- **SaaS products** adding crypto billing without building infrastructure

---

## Tech Stack

- **Frontend**: HTML / CSS / JavaScript (vanilla)
- **Wallet Connection**: MetaMask / window.ethereum (ethers.js v6)
- **Payment Rails**: Tempo Mainnet, Base Mainnet, Arc Testnet
- **Stablecoin**: USDC (ERC-20 native transfer)
- **Storage**: localStorage (invoice state)
- **Explorer**: https://explore.tempo.xyz

---

## Roadmap

- [x] Payment link generation UI
- [x] Multi-chain checkout flow
- [x] Tempo Mainnet integration (live March 18, 2026)
- [x] Base Mainnet integration
- [x] Arc Testnet integration
- [x] Real USDC ERC-20 transfers (not demo)
- [x] Base builder attribution (base:builder_code)
- [ ] Webhook + API for developers
- [ ] Mobile-optimized payer experience
- [ ] Agent-to-agent payment protocol via MPP
- [ ] Arc Mainnet upgrade (when live)
- [ ] Fiat off-ramp via Stripe (leveraging Tempo x Stripe infrastructure)

---

## Builder

Solo builder. Prev: MetricFlow (on-chain Farcaster analytics, Base). Now going full payments on Tempo.

Base Builder: `bc_5s50punj`

---

## License

MIT
