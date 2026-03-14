# NEXUS PAY
### The Zero-Friction Institutional Billing Protocol on Tempo

> Create a payment link in seconds. Get paid in stablecoins on Tempo — the institutional-grade payment chain backed by Stripe and Paradigm.

---

## What is Nexus Pay?

Nexus Pay is a decentralized invoicing and payment gateway built for the modern economy — freelancers, merchants, and AI agents who need to send and receive money across borders without friction, fees, or banks.

A user creates a **Payment Link** in seconds. The payer opens the link and pays in stablecoins on Tempo. The merchant receives USDC instantly. No bank account required. No intermediaries.

---

## The Problem

Cross-border payments are broken:
- Freelancers wait 5–10 days for international wire transfers
- Merchants lose 3–5% to card network fees
- Crypto payments require technical knowledge most users don't have
- Existing tools lack institutional-grade finality and compliance

---

## The Solution

Nexus Pay abstracts all of that away into one link — powered exclusively by Tempo.

```
nexuspay.xyz/pay/invoice_abc123
```

The payer clicks, connects their wallet, confirms on Tempo — done. The merchant sees the payment settle in under a second.

---

## Why Tempo

Tempo — built by Stripe and Paradigm — is purpose-built for stablecoins in the real world. For Nexus Pay's primary use case (B2B invoicing, freelancer payouts, merchant settlements), Tempo provides:

- Institutional-grade finality
- Stripe's compliance infrastructure
- Native TIP-20 stablecoin support with real-world settlement
- Sub-second transaction speed at near-zero cost
- Agentic payment compatibility for the AI economy

Nexus Pay is built exclusively on Tempo. Not multi-chain. Not fragmented. One rail. The right one.

---

## Key Features

- **One-click Payment Links** — generate a shareable invoice URL in under 10 seconds
- **Tempo-native Checkout** — payer connects wallet and pays directly on Tempo
- **Real-time Settlement** — USDC lands in your wallet in under a second
- **No Sign-up for Payers** — payers just connect wallet and pay
- **Dashboard** — track all invoices, payment status, and history
- **On-chain Confirmation** — every payment verified on Tempo's explorer

---

## How It Works

```
1. Merchant creates invoice → sets amount, description, wallet address
2. Nexus Pay generates a unique payment link
3. Merchant shares link via email, DM, or embeds in app
4. Payer opens link → connects wallet → pays on Tempo
5. Merchant receives USDC directly to wallet
6. Invoice marked as PAID — both parties get confirmation
```

---

## Tech Stack

- **Frontend**: Vanilla HTML/CSS/JS (no framework, ships instantly)
- **Payment Rail**: Tempo Network (Moderato Testnet)
- **Stablecoin**: USDC via TIP-20
- **Wallet Connection**: MetaMask + EIP-1193 (wallet_addEthereumChain)
- **Chain ID**: 42431 (0xA5BF) — Tempo Moderato Testnet
- **RPC**: https://rpc.moderato.tempo.xyz
- **Explorer**: https://explorer.moderato.tempo.xyz
- **Hosting**: Vercel

---

## Tempo Network Config

```json
{
  "chainId": "0xA5BF",
  "chainName": "Tempo Testnet",
  "nativeCurrency": { "name": "USD", "symbol": "USD", "decimals": 18 },
  "rpcUrls": ["https://rpc.moderato.tempo.xyz"],
  "blockExplorerUrls": ["https://explorer.moderato.tempo.xyz"]
}
```

---

## Roadmap

- [x] Payment link generation UI
- [x] Tempo-only checkout flow
- [x] Wallet connection (MetaMask + Tempo Testnet)
- [ ] Tempo mainnet integration
- [ ] Webhook + API for developers
- [ ] Mobile-optimized payer experience
- [ ] Agent-to-agent payment protocol
- [ ] Fiat off-ramp via Stripe (leveraging Tempo × Stripe infrastructure)

---

## Why This Wins at a Tempo Hackathon

Nexus Pay isn't just built *on* Tempo — it's built *for* what Tempo was designed to solve. Stripe and Paradigm built Tempo to make stablecoins work in the real world. Nexus Pay is the UX layer that makes that real for millions of users who need to get paid globally, today.

We didn't add Tempo as one of many chains. We went all in.

---

## Builder

Solo builder. Prev: MetricFlow (on-chain analytics, Base). Now going full payments on Tempo.

---

## License

MIT
