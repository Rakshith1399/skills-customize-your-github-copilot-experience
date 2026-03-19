# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build RESTful API endpoints using FastAPI and Pydantic models, handle requests and responses, and test your endpoints locally.

## 📝 Tasks

### 🛠️ Build a Simple REST API

#### Description
Create a FastAPI application that exposes endpoints for managing a small collection of resources (e.g., books, tasks, or students). The API should accept request data, return JSON responses, and handle basic error cases.

#### Requirements
Completed program should:

- Create a FastAPI app with at least one router or endpoint
- Define Pydantic models for request/response validation
- Support CRUD-style operations (create, read, update, delete) for a resource
- Return appropriate HTTP status codes and JSON responses
- Be runnable locally using `uvicorn` (e.g., `uvicorn main:app --reload`)