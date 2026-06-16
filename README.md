# Final Project

## Emotion Detection API

This project implements a Flask-based API for emotion detection.  
It analyzes text input and returns emotion scores (anger, disgust, fear, joy, sadness) along with the dominant emotion.

### Objectives
- Build a REST API using Flask
- Integrate with Watson NLP Emotion Detection service
- Handle blank inputs with error messages
- Provide both GET and POST endpoints

### Features
- `/emotionDetector` endpoint
- Returns emotion scores in JSON format
- Error handling for invalid or blank input
- Supports GET (query parameter) and POST (JSON body)

### Usage
Start the server:
```bash
python3 server.py
