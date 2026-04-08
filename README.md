# Personal Finance App
A simple and fast personal finance app designed to reduce friction in daily financial tracking.

## Problem
Many people try to manage their personal finances but fail to stay consistent over time.
The problem is not lack of awareness, but the friction involved in tracking transactions daily. Most existing solutions are either too complex or require too much effort, leading users to abandon them.

## Target Audience
This product is designed for people who:
- Want to manage their personal finances
- Have already tried financial apps but gave up
- Struggle to stay consistent due to complexity or friction

## Value Proposition
**Track your transactions in seconds, without friction.**
This product focuses on simplicity and speed, making it effortless to register transactions and maintain control over your finances.

## MVP Scope
### Must-have features
- Add a transaction (income or expense)
- View list of transactions
- View current balance

### Nice-to-have (if time allows)
- Basic categories
- Simple date filtering
- Simple summary (income vs expenses)

### Out of scope
- Bank integrations  
- Automation  
- Complex analytics or charts  
- Budgets and planning tools  
- Notifications  
- Multi-user support  
- Cloud sync  

## Differentiator
This product prioritizes **extreme simplicity and speed over feature richness**.
Instead of adding more features, it removes friction — making financial tracking fast, lightweight, and easy to maintain over time.

## Vision
A financial tool that people actually use every day — not because they have to, but because it’s simple enough that they don’t avoid it.


---


## Tech Stack
- **Frontend:** React + TypeScript
- **Desktop Runtime:** Tauri
- **Backend:** Node.js (Fastify)
- **Database:** SQLite (Prisma)
- **State Management:** Zustand

## Architecture
- Monorepo
- Client-server (local-first)
- REST API

📄 Full details: [Architecture Docs](./docs/architecture.md)


---


## Status

Currently in **Phase 2 — Project Architecture Definition**.

This phase focuses on defining the system design, structure, and technical decisions before starting implementation.
