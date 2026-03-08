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

| Chain | Best For | Asset |
|-------|----------|-------|
| **Tempo** | Institutional & B2B payments | USDC |
| **Base** | Retail & social payments | USDC / ETH |
| **Arc** | Native USDC speed | USDC |
| **Solana** | Micropayments & point-of-sale | USDC |
| **Sui** | High-frequency transactions | USDC |

### Why Tempo is the Core Rail

Tempo — built by Stripe and Paradigm — is purpose-built for stablecoins in the real world. For Nexus Pay's primary use case (B2B invoicing, freelancer payouts, merchant settlements), Tempo provides:

- Institutional-grade finality
- Stripe's compliance infrastructure
- Native USDC support with real-world settlement
- Agentic payment compatibility for the AI economy

Tempo is the backbone. Every other chain is an on-ramp.

---

## Key Features

- **One-click Payment Links** — generate a shareable invoice URL in under 10 seconds
- **Multi-chain Checkout** — payer selects their preferred chain at checkout
- **Real-time Settlement** — funds arrive in your wallet, not a custodial account
- **No Sign-up for Payers** — payers just connect wallet and pay
- **Dashboard** — track all invoices, payment status, and history
- **Webhook Support** — integrate payment events into your own app or agent

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

- **Frontend**: React + Vite
- **Smart Contracts**: Solidity (EVM) / Tempo SDK
- **Payment Rails**: Tempo, Base, Arc, Solana, Sui
- **Stablecoin**: USDC (primary)
- **Wallet Connection**: Wagmi + RainbowKit
- **Backend**: Node.js / serverless functions
- **Storage**: IPFS (invoice metadata)

---

## Roadmap

- [x] Payment link generation UI
- [x] Multi-chain checkout flow (prototype)
- [ ] Tempo mainnet integration
- [ ] Webhook + API for developers
- [ ] Mobile-optimized payer experience
- [ ] Agent-to-agent payment protocol
- [ ] Fiat off-ramp via Stripe (leveraging Tempo × Stripe infrastructure)

---

## Why This Wins at a Tempo Hackathon

Nexus Pay isn't just built *on* Tempo — it's built *for* what Tempo was designed to solve. Stripe and Paradigm built Tempo to make stablecoins work in the real world. Nexus Pay is the UX layer that makes that real for millions of users who need to get paid globally, today.

---

## Builder

Solo builder. Prev: MetricFlow (on-chain analytics, Base). Now going full payments.

---

## License

MIT
