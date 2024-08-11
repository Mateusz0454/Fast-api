# FastAPI Project Docs

This is a simple FastAPI application that demonstrates basic features of the framework. 

## Funtions

- create user
- get user
- create task
- get tasks

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)

## Installation

### Requirements

- Python 3.7+
- FastAPI
- Uvicorn
- SQLAlchemy
- Pydantic

### Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/fastapi-example.git
   cd fastapi
   ```

2. **Create a virtual environment:**

   ```bash
   py -m venv env
   env\Scripts\activate   # On Linux, use ` source env/bin/activate`
   ```

3. **Install the dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

   If you don't have a `requirements.txt` file, you can install dependencies manually:

   ```bash
   pip install fastapi uvicorn SQLAlchemy pydantic typer
   ```

## Usage

To start the FastAPI server, run the following command:

```bash
uvicorn main:app --reload
```

- `main` refers to the filename (e.g., `main.py`).
- `app` is the name of the FastAPI instance.
- `--reload` will automatically reload the server when you make changes to the code.

Once the server is running, you can access the application at `http://127.0.0.1:8000` or `http://127.0.0.1:8000/redoc`
