# Project Fastapi_auth

This is a project that requires the following dependencies to run successfully.

## Dependencies

- FastAPI: A modern, fast (high-performance), web framework for building APIs with Python.
- Uvicorn: A lightning-fast ASGI server, recommended for use with FastAPI.
- SQLAlchemy: A SQL toolkit and Object-Relational Mapping (ORM) library for Python.
- python-jose[cryptography]: A library for JSON Web Tokens (JWT) implementation in Python.
- passlib[bcrypt]: A password hashing library for Python.
- python-multipart: A library for handling multipart/form-data requests in Python.
- bcrypt: A password hashing library that uses the bcrypt algorithm.

## Installation

To install the required dependencies, please follow these steps:

1. pip Install FastAPI, Uvicorn, and SQLAlchemy
2. pip install python-jose[cryptography]
3. pip install passlib[bcrypt]
4. pip install python-multipart
5. pip Upgrade bcrypt to the latest version
6. pip install bcrypt version 3.2.0

## Running the Program

To run the program, use the following command:

## uvicorn main:app --reload

## Copy Dependencies and restore in requirements
pip freeze > requirements.txt
pip install -r requirements.txt
