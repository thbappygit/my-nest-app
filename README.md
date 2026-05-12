# NestJS Starter Project (Docker )

A beginner-friendly backend project built with NestJS, Docker, PostgreSQL, and Redis.

---

## 🚀 Tech Stack

- NestJS (Backend Framework)
- TypeScript
- PostgreSQL (Database)
- Redis (Cache / Queue support)
- Docker & Docker Compose
- Node.js (LTS recommended)

---

## 📁 Project Setup

```bash
cd my-nest-app
npm install
```

---

## 🐳 Run with Docker (Recommended)

### 1. Build and start containers

```bash
docker compose up --build
```

### 2. Run in background

```bash
docker compose up -d
```

### 3. Stop containers

```bash
docker compose down
```

---

## 🌐 Application URLs

- API: http://localhost:3000
- PostgreSQL: localhost:5432
- Redis: localhost:6379

---

## ⚙️ Environment Variables

Create `.env` file:

```
PORT=3000
DATABASE_URL=postgresql://nestuser:nestpass@postgres:5432/nestdb
REDIS_HOST=redis
REDIS_PORT=6379
```

---

## 📦 Useful Docker Commands

```bash
docker compose logs -f
docker compose restart
docker compose up --build
docker compose down -v
```

---

## 🧑‍💻 Run Without Docker

```bash
npm run start:dev
```

---

## 🏗️ Project Structure

src/
├── app.controller.ts
├── app.service.ts
├── app.module.ts
├── main.ts

Recommended:

src/
├── modules/
├── common/

---

## 🔐 Features to Add

- JWT Auth
- Prisma ORM
- Redis caching
- Swagger
- Guards / Pipes / Interceptors

---

## 📄 License

MIT
