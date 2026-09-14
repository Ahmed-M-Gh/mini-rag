# mini-rag

This is a minimal implementation of the RAG model for question answering.

## Requirements

- Python 3.8 or later

#### Install Python using creating python environment

```bash
python venv mini-rag-app
mini-rag-app\Scripts\activate
```

## Installation

### Install the required packages

```bash
$ pip install -r requirements.txt
```

### Setup the environment variables

```bash
$ cp .env.example .env
```

Set your environment variables in the `.env` file. Like `OPENAI_API_KEY` value.

## Run the FastAPI server

```bash
uvicorn main:app --reload --host 0.0.0.0 --port 5000
```

## POSTMAN Collection

Download the POSTMAN collection from [/assets/mini-rag-app.postman.collection.json](/assets/mini-rag.postman_collection.json)