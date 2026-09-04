# Indic Text-to-Speech API

A FastAPI-based Text-to-Speech (TTS) API that generates speech from text using AI4Bharat's Indic Parler TTS model.

## Features

* Converts text into speech
* Built using FastAPI
* Uses a transformer-based Text-to-Speech model
* Provides an API endpoint for generating speech
* Designed for Indic language speech synthesis

## Tech Stack

* Python
* FastAPI
* Hugging Face Transformers
* AI4Bharat Indic Parler TTS

## Project Structure

```text
tts/
├── main.py
├── requirements.txt
├── Procfile
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/betty1-3/tts.git
cd tts
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Running the Application

Start the FastAPI server using:

```bash
uvicorn main:app --reload
```

The application will run locally on:

```text
http://127.0.0.1:8000
```

## API Endpoint

### Generate Speech

**POST** `/tts`

Send text to the API to generate speech.

Example request:

```json
{
  "text": "Hello, this is a text to speech application."
}
```

The API processes the input text using the Indic Parler TTS model and generates speech audio.

## Model

This project uses AI4Bharat's Indic Parler TTS model for text-to-speech generation.

The model is designed for speech synthesis involving Indic languages and is integrated into the application using the Hugging Face Transformers ecosystem.

## Future Improvements

* Support for multiple Indic languages
* Voice selection
* Audio format selection
* Downloadable generated audio files
* Web-based user interface
* Docker support
* API documentation and examples

## Author

GitHub: [@betty1-3](https://github.com/betty1-3)
