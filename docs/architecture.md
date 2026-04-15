# Architecture

## Overview
- **Type:** Monorepo  
- **Architecture:** Layered architecture (controller → service → repository) 
- **Design Approach:** Clean architecture principles (simplified)
- **API Style:** REST API

## Frontend
- **Stack:** React + TypeScript
  
### Structure
```
apps/desktop/src/
  features/
  shared/
  app/
```

## Backend
- **Runtime:** Node.js  
- **Language:** TypeScript  
- **Framework:** NestJS  
### Structure
```
services/api/src/
  modules/
    transactions/
      transactions.controller.ts
      transactions.service.ts
      transactions.module.ts
```

## Database
- **Database:** SQLite  
- **ORM:** Prisma  

## Monorepo Structure
```
/apps
  /desktop

/services
  /api
```
