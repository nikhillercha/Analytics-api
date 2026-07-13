# Analytics-api
---
# Build an Analytics API using FastAPI + Time-series postgres
---
Own your data pipeline!
Start by building an analytics API service with Python, FastAPI, and Time-series Postgres with TImescaleDB
---
# Getting Started
1 - Download & Install python3
2 - Create Virtual Environment
3 - Install python packages - `pip install <packagename>`
4 - FastAPI hello world 
5 - Docker Desktop & Docker Compose
6 - Production Dockerfile for FastAPI
7 - Docker Compose-based FastAPI hello world

## Docker

- `docker build -t analytics-api -f Dockerfile.web .`
- `docker run analytics=api`

becomes

- `docker compose up --watch `
- `docker compose down` or `docker compose down -v` (to remove volumes)
- `docker compose run app /bin/bash` or `docker compose run app python`