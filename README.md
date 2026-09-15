# Todo REST API

A RESTful API built with FastAPI and SQLALchemy that supports full Crud operations for managing todo items, backed by a SQLite database.

## Features
Create, read, update and delete todos
Data validation using pydantic schemas 
SQLite database with SQLAlchemy ORM 
Interactive API documentation via Swagger UI

## Tech Stack
- Python
- FastAPI
- SQLAlchemy
- SQLite
- Pydantic
## How to Run

1. Clone the repository 
2. Create a virtual environment: 'python -m venv venv'
3. Activate the virtual enviroment: ' venv\Scripts\activate'
4. Install dependencies: 'pip install -r requirements.txt'
5. Run the server: 'uvicorn main:app --reload'
6. Open 'http://localhost:8000/docs' to test the api