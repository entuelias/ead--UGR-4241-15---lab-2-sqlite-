# PizzaStoreSQLite

A simple RESTful API using **.NET 10** and **SQLite** for a pizza store.  
This is Part 2 of Lab 2 (separate from the In-Memory version).

## Features

- CRUD operations for pizzas:
  - `GET /pizzas` → list all pizzas
  - `GET /pizza/{id}` → get a single pizza
  - `POST /pizza` → create a pizza
  - `PUT /pizza/{id}` → update a pizza
  - `DELETE /pizza/{id}` → delete a pizza
- Uses **SQLite** database (`pizzastore.db`)
- Swagger UI for easy testing

## Setup

1. Clone the repo:
   ```bash
   git clone <repo_url>
   cd PizzaStoreSQLite
