# n8n_testing

# n8n Python Integration

This project demonstrates communication between:

- n8n running in Docker
- Python Flask API running in WSL
- Ollama running locally on Windows

## Architecture

n8n → Flask API → Ollama

## Endpoints

### /run

Simple test endpoint.

### /embed

Creates embeddings from text input.

## Requirements

- Rancher Desktop
- WSL2
- Docker
- Python 3
- Flask
- Ollama

## Running

Start Flask:

```bash
source venv/bin/activate
python app.py
