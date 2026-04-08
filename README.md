# personal-finance-app
A simple and fast personal finance app focused on daily consistency

### **Architecture Overview**
- Type: Monorepo
- Architecture: Client-server (local-first)
- API Style: REST

### **Frontend**
- Stack: React + TypeScript
- Runtime: Tauri (desktop)
- State Management: Zustand

### **Structure:**
```
apps/desktop/src/
  features/
  shared/
  app/
```
### **Backend**
- Runtime: Node.js
- Language: TypeScript
- Framework: Fastify

###** Structure:**
```
services/api/src/
  controllers/
  services/
  repositories/
```
### **Database**
- Database: SQLite
- ORM: Prisma

### **Monorepo Structure**
```
/apps
  /desktop

/services
  /api
```

