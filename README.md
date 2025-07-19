# 🔐 Auth Service – ExchangeApp

![Python](https://img.shields.io/badge/python-3.10+-blue)  
![FastAPI](https://img.shields.io/badge/FastAPI-0.85-informational?style=flat)  
![License](https://img.shields.io/badge/license-MIT-green)

---

## 📖 Overview

The **Auth Service** is a dedicated microservice within the ExchangeApp platform responsible for:

- **User registration** (email & password)  
- **User login** and JWT issuance  
- **Token validation** and refresh  
- **Session management** (refresh tokens, revocation)  

Built with **FastAPI**, **SQLAlchemy**, and **PostgreSQL**, this service demonstrates clean architecture, secure password hashing, and modern async API design.

---

## 🚀 Key Features

- **FastAPI** for high-performance, async endpoints  
- **Pydantic** schemas for input/output validation  
- **SQLAlchemy** ORM mapping to PostgreSQL  
- **JWT** authentication + **Bcrypt** password hashing  
- **Docker & Docker Compose** for local development  
- **Pytest + TestClient** for unit & integration tests  
- **Automatic API docs** via Swagger (/docs) and ReDoc (/redoc)

---

## 🛠️ Tech Stack

| Layer             | Technology              |
|-------------------|-------------------------|
| Language          | Python 3.10+            |
| Web Framework     | FastAPI                 |
| ORM               | SQLAlchemy              |
| Data Validation   | Pydantic                |
| Auth & Security   | JWT (PyJWT) + Bcrypt    |
| Database          | PostgreSQL              |
| Containerization  | Docker, Docker Compose  |
| Testing           | Pytest, FastAPI TestClient |
| Migrations        | Alembic (optional)      |

---

## 📋 Prerequisites

- **Python ≥ 3.10**  
- **Docker & Docker Compose**  
- **Git**  
- (Optional) Local or remote PostgreSQL instance  

---

## 🔧 Installation & Getting Started

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-org/auth-service.git
   cd auth-service

