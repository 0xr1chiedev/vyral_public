# Vyral — High-Level Architecture

Brief overview of how Vyral is structured (for the public repo; not the full codebase).

---

## Layers

| Layer | Role |
|-------|------|
| **Frontend** | Next.js App Router, React, Tailwind. Pages: campaigns, marketplace, pack-shop, profile, admin. |
| **API** | Next.js API routes for campaigns, user, marketplace, NFTs, packs, admin auth and CRUD. |
| **Data** | Prisma ORM, PostgreSQL. Models: User, Creator, Campaign, NFT, Pack, Transaction, Referral. |
| **Auth** | Privy for Twitter OAuth and embedded wallets (no seed phrase). |
| **Chain** | Base (Ethereum L2) for NFTs and token flows. |

---

## Main Flows

1. **User:** Sign in with Twitter → embedded wallet created → use campaigns, marketplace, packs, referrals.
2. **Creator:** Represented by NFT collection; rewards and collectibles tied to campaigns.
3. **Admin:** Login at `/admin` → manage campaigns, creators, packs, users, marketplace.

---

## Repo Scope

This repository contains only documentation and overview. The actual application code lives in a private repository.
