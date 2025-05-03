# Text Summarizer Web Application

A simple Flask web application that allows users to input text and get an automatic summary using the LSA (Latent Semantic Analysis) algorithm.

## Features

- Clean and modern user interface
- Automatic text summarization
- Responsive design
- Easy to use

## Setup

1. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python app.py
```

4. Open your web browser and go to `http://localhost:5000`

## Usage

1. Enter or paste your text in the text area
2. Click the "Summarize" button
3. View the generated summary below the input area

## Dependencies

- Flask
- sumy
- nltk 