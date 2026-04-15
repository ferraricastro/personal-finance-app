# Architecture

## Overview
- **Type:** Monorepo  
- **Architecture:** Clean architecture
- **API Style:** REST API

## Frontend
- **Stack:** React + TypeScript
- **Data Fetching:** TanStack Query 
  
### Structure
```
apps/desktop/src/
  app/                # app setup (providers, routing, global config)
  features/           # feature-based modules
    transactions/
      components/
      hooks/
      services/       # API calls (per feature)
      types/
      pages/
  shared/             # reusable code across features
    components/
    hooks/
    utils/
    types/
  lib/                # external libs/config wrappers
    api/              # HTTP client (fetch/axios)
    query/            # TanStack Query setup
  styles/             # global styles (if needed)
```

## Backend
- **Runtime:** Node.js  
- **Language:** TypeScript  
- **Framework:** NestJS  
### Structure
```
services/api/src/
  modules/                      # domain modules (feature-based, aligned with business)
    transactions/     
      domain/                   # core business rules 
        entities/
      application/              # use cases (business logic orchestration)
        use-cases/                  
      infrastructure/           # external implementations
        repositories/             
      interfaces/               # entry points
        transactions.controller.ts  
      transactions.module.ts    # NestJS module
```

## Database
- **Database:** SQLite  
- **ORM:** TypeORM 

## Monorepo Structure
```
/apps
  /desktop

/services
  /api
```
