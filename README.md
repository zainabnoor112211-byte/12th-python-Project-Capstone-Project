# 12th-python-Project-Capstone-Project
A simple FastAPI To-Do API built with Python and Pydantic that supports CRUD operations for creating, viewing, updating, and deleting tasks.
# FastAPI To-Do API

A simple and beginner-friendly **To-Do API** developed using **Python, FastAPI, and Pydantic**. This project demonstrates how to build a REST API and perform basic CRUD operations on tasks.

## 📌 Project Overview

The API allows users to manage their tasks through different HTTP methods:

* **GET** – Retrieve all tasks
* **POST** – Add a new task
* **PUT** – Update an existing task
* **DELETE** – Delete a task

The project uses a Python list as an in-memory database to store tasks.

## 🛠️ Technologies Used

* Python
* FastAPI
* Pydantic
* Uvicorn
* REST API
* Swagger UI

## 📂 Project File

```text
api.py
```

The `api.py` file contains the complete FastAPI application, Pydantic model, and CRUD endpoints.

## 📋 Task Model

Each task contains:

```text
id       → Integer
title    → String
is_done  → Boolean
```

The `is_done` field is set to `False` by default.

## 🔗 API Endpoints

| Method | Endpoint           | Description             |
| ------ | ------------------ | ----------------------- |
| GET    | `/tasks`           | Retrieve all tasks      |
| POST   | `/tasks`           | Create a new task       |
| PUT    | `/tasks/{task_id}` | Update an existing task |
| DELETE | `/tasks/{task_id}` | Delete a task           |

## 🚀 How to Run

First, install the required packages:

```bash
pip install fastapi uvicorn
```

Then run the API:

```bash
uvicorn api:app --reload
```

## 📖 API Documentation

After starting the server, open FastAPI's interactive Swagger documentation:

```text
http://127.0.0.1:8000/docs
```

You can use Swagger UI to test all the available endpoints.

## 🎯 Learning Objectives

This project demonstrates:

* Creating a FastAPI application
* Creating Pydantic models
* Data validation
* GET, POST, PUT, and DELETE methods
* Path parameters
* CRUD operations
* Basic API testing with Swagger UI
* Using a Python list as temporary database storage

## 👩‍💻 Author

**Asma Kanwal**
