# Personal Finance App
A simple and fast personal finance app focused on reducing friction in daily expense tracking.

---

## Problem
Many people try to manage their personal finances but fail to stay consistent over time.
The main issue is not lack of awareness, but the friction involved in tracking transactions daily. Most existing solutions are either too complex or require too much effort, leading users to abandon them.

---

## Target Audience
This product is designed for people who:
- Want to manage their personal finances
- Have already tried financial apps but gave up
- Struggle to stay consistent due to complexity or friction

---

## Value Proposition
Track your financial transactions in seconds, without friction.
This product focuses on simplicity and speed, making it effortless to register transactions and maintain control over your finances.

---

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

---

## Differentiator
This product focuses on extreme simplicity and speed.
Instead of adding more features, it removes friction — making financial tracking fast, lightweight, and easy to maintain over time.

---

## Vision
A financial tool that people actually use every day — not because they have to, but because it’s simple enough that they don’t avoid it.

# Architecture Overview
- Type: Monorepo
- Architecture: Client-server (local-first)
- API Style: REST

# Frontend
- Stack: React + TypeScript
- Runtime: Tauri (desktop)
- State Management: Zustand
### Structure:
```
apps/desktop/src/
  features/
  shared/
  app/
```

# Backend
- Runtime: Node.js
- Language: TypeScript
- Framework: Fastify
### Structure:
```
services/api/src/
  controllers/
  services/
  repositories/
```

# Database
- Database: SQLite
- ORM: Prisma

# Monorepo Structure
```
/apps
  /desktop

/services
  /api
```

