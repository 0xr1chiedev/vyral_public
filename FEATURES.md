# Vyral — Features & Skills

A short reference for Vyral’s capabilities and tech stack.

---

## Features

- **Twitter authentication** — Sign in with Twitter only (Privy).
- **In-app wallet** — Automatic embedded wallet creation; no manual setup.
- **Creator NFTs** — One NFT collection per creator (e.g. 100 supply).
- **Campaign system** — InfoFi campaigns with mindshare and reward logic.
- **Marketplace** — List, buy, and sell NFTs.
- **Pack shop** — Randomized card/pack opening.
- **Referral system** — User referral tracking and rewards.
- **Admin panel** — Manage campaigns, creators, packs, users, and marketplace.

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Next.js 14 (App Router), React 18, TypeScript, Tailwind CSS |
| Backend | Next.js API Routes, Prisma ORM |
| Database | PostgreSQL |
| Auth | Privy (Twitter OAuth) |
| Blockchain | Base (Ethereum L2) |

---

## High-Level Structure

- **App:** App Router pages for campaigns, marketplace, pack shop, profile, admin.
- **API:** REST-style routes for campaigns, user, marketplace, NFTs, packs, admin.
- **Data:** Prisma schema for users, creators, campaigns, NFTs, packs, transactions, referrals.

This document is part of the public overview only; the full codebase is not included in this repository.
