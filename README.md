# Jujitsu Video Analysis Backend

This is the FastAPI backend for the Jujitsu Video Analysis application. It provides endpoints for video analysis and processing.

## Setup

1. Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Server

To run the development server:

```bash
uvicorn api:app --reload
```

The server will be available at `http://localhost:8000`

## API Documentation

Once the server is running, you can access:

- Swagger UI documentation: `http://localhost:8000/docs`
- ReDoc documentation: `http://localhost:8000/redoc`

## Deployment

The application is configured for deployment on Render.com using the `render.yaml` configuration file.
