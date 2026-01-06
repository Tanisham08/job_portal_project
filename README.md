# Job Portal Project

## Overview
This project is a lightweight Job Portal application developed and customized as part of my Master’s program.  
It consists of a Python-based GraphQL backend and a Streamlit frontend used to demonstrate job postings, applications, and user data handling.

The focus of this project is to understand full-stack application structure, backend services, and frontend interaction rather than production-scale deployment.

---

## Key Features
- GraphQL backend exposing jobs, users, and applications
- Streamlit-based frontend demo for interaction and testing
- Authentication and resume parsing services
- Modular and extensible project structure
- Clear separation of backend, frontend, and service layers

---

## Tech Stack
- Python 3.10+
- GraphQL
- Streamlit
- Pytest for testing

---

## Repository Structure (Important Files)

- `src/backend/app.py` — backend application entry point
- `src/backend/db.py` — database helpers
- `src/backend/schema.graphql` — GraphQL schema
- `src/backend/models/` — data models
- `src/backend/repository/` — data access layer
- `src/backend/resolvers/` — GraphQL resolvers
- `src/backend/services/` — application services (authentication, resume parsing, embeddings, etc.)
- `src/frontend/app_streamlit.py` — Streamlit frontend demo
- `tests/` — unit tests

---

## Prerequisites
- Python 3.10 or newer
- Virtual environment support
- Streamlit installed (included in requirements)

---

## Setup

### Create and activate a virtual environment
```bash
python -m venv .venv
source .venv/bin/activate   # macOS/Linux
# or
.\.venv\Scripts\activate    # Windows
