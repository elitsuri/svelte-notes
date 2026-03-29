# Svelte Notes

> Local-first note taking app with offline support and sync

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
SvelteKit, TypeScript, Node.js, MongoDB

## 🏗️ Architecture
Backend service with SvelteKit, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/svelte-notes
cd svelte-notes

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
