# Local development

This repository contains a Docker Compose setup intended only for local development using PostgreSQL.

The Compose file used for local development lives at `docker-compose.yml`.

## Requirements

- pnpm package manager
- Docker
- Docker Compose
- Docker Desktop

## Setup
1. Initalize husky 
```
npx husky init
```

## Quick start

From the repository root you can start the environment with:

```
docker compose -f docker-compose.yml up -d --build
```

To stop and remove the containers:

```
docker compose -f docker-compose.yml down
```

Or use Docker Desktop to manage the compose