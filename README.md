# RESTful API - Project 1

My first REST API built with Python and FastAPI. No database as data is stored 
in memory. Covers all four core HTTP methods used in real API development.

## What it does
- Get a user by ID
- Create a new user
- Update a user 
- Delete a user
- Search users by name

## Stack
- Python
- FastAPI
- Pydantic
- Uvicorn

## Run locally
pip install fastapi uvicorn
uvicorn main:app --reload

Then visit http://127.0.0.1:8000/docs to test all endpoints
