# Gemini Powered ChatBot

Welcome to the **Gemini Powered ChatBot** project! This project leverages Google's Gemini-1.5-Flash model to create an interactive chatbot interface using Streamlit.

## Installation

To get started, clone this repository and install the required dependencies.

```bash
git clone https://github.com/manogyaguragai/gemini-powered-chatbot.git
cd gemini-powered-chatbot
pip install -r requirements.txt
```

## Configuration

This project uses environment variables to manage the API key for Google Generative AI. Follow these steps to set up your environment:

1. Create a `.env` file in the project root directory.
2. Add your Google API key to the `.env` file:

    ```plaintext
    GOOGLE_API_KEY=your_google_api_key_here
    ```

## Usage

To run the chatbot application, use the following command:

```bash
streamlit run app.py
```

This will start a local Streamlit server. Open your web browser and navigate to `http://localhost:8501` to interact with the chatbot.

## Code Overview

The main components of the project are as follows:

- **Environment Setup**: Load environment variables using `dotenv`.
- **API Configuration**: Configure the Google Generative AI with the provided API key.
- **Streamlit UI**: Create a user interface with Streamlit to interact with the chatbot.

```