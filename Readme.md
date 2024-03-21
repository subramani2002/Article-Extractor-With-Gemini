
# ✨ News Research Tool  ✨

# Harness the power of Gemini for insightful answers and cited sources!

# Overview

This project empowers you to extract key information from news articles effortlessly. It leverages:

- **Gemini, Google's advanced language model,** for comprehending and generating comprehensive answers.
- **Streamlit,** for a user-friendly web interface.
- **Langchain,** for effective document loading, text splitting, and embedding generation.

## Key Features

- **Process multiple news articles** by simply entering their URLs.
- **Ask questions in natural language** and receive informative responses.
- **View cited sources** for each response, enhancing transparency and credibility.
- **Intuitive web interface** for seamless interaction.

# Real Time Demo
![Screenshot 2024-03-21 235306](https://github.com/subramani2002/Article-Extractor-With-Gemini/assets/67220838/774d27c5-f2b7-4597-8166-854506f2d8ce)

![Screenshot 2024-03-22 001353](https://github.com/subramani2002/Article-Extractor-With-Gemini/assets/67220838/80a04fbb-0b2f-4b0b-a429-03a1e52e6b83)

## Getting Started

## Prerequisites:

- Python 3.7 or later
- Necessary libraries listed in `requirements.txt`
- A Google API key with access to Gemini (set as `GEMINI_API_KEY` in a `secret.py` file)

## Installation:

1. Clone this repository:

   ```bash
   git clone https://github.com/subramani2002/Article-Extractor-With-Gemini
   ```

2. Install dependencies:

   ```bash
   cd Article-Extractor-With-Gemini
   pip install -r requirements.txt
   ```

**Running the application:**

1. Execute `main.py`:

   ```bash
   streamlit run main.py
   ```

2. Access the application in your web browser.

##  Usage

1. Enter up to 3 URLs of news articles in the sidebar.
2. Click "Process URLs" to initiate information extraction.
3. Begin asking questions in the main panel.
4. View generated answers and their corresponding sources.
