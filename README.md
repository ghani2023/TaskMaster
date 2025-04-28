# TaskMaster API

A simple task management REST API built using FastAPI and SQLAlchemy.

## Features
- Create, Read, and Delete tasks
- SQLite database for persistence
- Auto-generated Swagger docs at `/docs`

## Setup

```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Visit:
```
http://127.0.0.1:8000/docs
```
