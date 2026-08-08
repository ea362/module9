# Module 9: Assignment - Working with Raw SQL in pgAdmin

![GitHub Actions Workflow Status](https://img.shields.io/badge/Docker%20Compose-Up%20and%20Running-brightgreen)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-0.115.4-green)
![pgAdmin](https://img.shields.io/badge/pgAdmin-4-blueviolet)

---

## 📖 Overview

This project demonstrates the integration of a **FastAPI web application** with a **PostgreSQL database** using Docker Compose. The assignment focuses on working with **raw SQL commands** through pgAdmin to create, read, update, and delete records in a relational database.

The application is containerized using Docker, with three services:
- **FastAPI Web Application** (Port `8000`)
- **PostgreSQL Database** (Port `5432`)
- **pgAdmin GUI** (Port `5050`)

---

## 🎯 Objectives

- Set up a containerized development environment using Docker Compose.
- Connect to a PostgreSQL database via pgAdmin.
- Execute raw SQL commands to:
  - Create tables with proper constraints (Primary Key, Foreign Key, UNIQUE, NOT NULL).
  - Insert records into related tables.
  - Query data using `SELECT` statements.
  - Perform `JOIN` operations to combine data from multiple tables.
  - Update existing records.
  - Delete records.
- Document SQL operations with screenshots.

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **FastAPI** | Web framework for building REST APIs |
| **PostgreSQL 15** | Relational database |
| **pgAdmin 4** | GUI for PostgreSQL management |
| **Docker & Docker Compose** | Containerization and orchestration |
| **Uvicorn** | ASGI server for FastAPI |
| **Pydantic** | Data validation |

---

## 🚀 Getting Started

### Prerequisites

- Docker Desktop installed and running
- Git
- Web browser

### Clone the Repository

```bash
git clone <repository-url>
cd module9