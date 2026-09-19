# DOMORA

> Plateforme SaaS de gestion locative et de patrimoine immobilier pour l'Afrique francophone et l'international.

**Statut : Phase 1 — Architecture & Documentation**

## Stack technique

| Couche | Technologies |
|---|---|
| Frontend | React 18 + Vite + TypeScript strict + Tailwind CSS + shadcn/ui + React Router + TanStack Query + React Hook Form + Zod + Lucide React + Recharts |
| Backend | Node.js + Express + TypeScript strict + MongoDB + Mongoose + REST API |
| Sécurité | JWT + refresh tokens + Argon2/bcrypt + Helmet + CORS + rate limiting + audit logs |
| DevOps | Docker + docker-compose + Nginx + PM2 + health checks |

## Structure du monorepo

```
/client    # Application React (Vite)
/server    # API REST (Express + Mongoose)
/docs      # Documentation technique et produit
/scripts   # Scripts utilitaires (seed, déploiement)
```

## Démarrage rapide (dev)

```bash
# Backend
cd server && cp .env.example .env && npm install && npm run dev

# Frontend (autre terminal)
cd client && cp .env.example .env && npm install && npm run dev
```

## Documentation

- [docs/PRODUCT_REQUIREMENTS.md](docs/PRODUCT_REQUIREMENTS.md) — Exigences produit
- [docs/ARCHITECTURE.md](docs/ARCHITECTURE.md) — Architecture technique
- [docs/DATABASE_SCHEMA.md](docs/DATABASE_SCHEMA.md) — Schéma MongoDB
- [docs/API_SPECIFICATION.md](docs/API_SPECIFICATION.md) — Spécification API REST
- [docs/SECURITY.md](docs/SECURITY.md) — Sécurité
- [docs/ROADMAP.md](docs/ROADMAP.md) — Feuille de route
- [PROJECT_STATUS.md](PROJECT_STATUS.md) — Statut d'avancement en temps réel

## Licence

Tous droits réservés — DOMORA
