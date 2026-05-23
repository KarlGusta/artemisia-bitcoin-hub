---
id: lightning-wallets
title: Lightning Wallets
sidebar_position: 7
---

Lightning wallets are Bitcoin wallets built for fast, low-fee payments over the Lightning Network.

They are best for small, everyday payments, while larger savings are usually better kept in cold storage.

## How Lightning wallets differ from on-chain wallets
- On-chain payments settle directly on the Bitcoin blockchain
- Lightning payments use payment channels for near-instant settlement
- Lightning usually has lower fees for small payments
- You may need routing liquidity for some payments

## Main Lightning wallet models

### 1. Custodial wallets
The provider controls keys and Lightning infrastructure for you.

Good for:
- Fast onboarding
- Learning with small amounts

Tradeoff:
- You trust a company with your funds

### 2. Self-custodial wallets with managed Lightning
You hold your keys, while the wallet or service provider helps with channels and liquidity.

Good for:
- Better control without running a full home node
- Daily spending with self-custody

Tradeoff:
- Still depends on wallet infrastructure for parts of the Lightning experience

### 3. Self-custodial wallets connected to your node
You run your own Lightning node (or embedded node) and connect your wallet to it.

Good for:
- Maximum control
- Advanced users

Tradeoff:
- More setup and operational responsibility

## Lightning wallets available (examples)
As of May 23, 2026, these are common options people use:

Availability can change by country, app store policy, and regulation, so always check the project site first.

### Custodial or mixed custody models
- Wallet of Satoshi: supports both self-custody and custodial modes depending on region and settings
- Blink: custodial wallet focused on simple Lightning usage

### Self-custodial managed experience
- Phoenix (ACINQ): self-custodial wallet built around Lightning
- Breez: self-custodial Lightning wallet/client
- Muun: self-custodial Bitcoin + Lightning wallet with a unified balance

### Node-connected / power-user options
- ZEUS: can connect to your own node or run node functionality on phone
- Electrum: long-running Bitcoin wallet with Lightning functionality in desktop workflows
- Blixt: mobile, open-source, self-custodial Lightning wallet

## Choosing the right one
Start simple, then level up:

1. Beginner: small amount in a simple wallet to learn invoices and payments
2. Intermediate: self-custodial managed wallet for stronger ownership
3. Advanced: your own node with ZEUS/Electrum-style control

## Safety checklist
- Keep only spending money in Lightning wallets
- Verify app names and publisher before installing
- Back up seed/recovery materials offline
- Test recovery before storing larger amounts
- Move long-term savings to cold storage
