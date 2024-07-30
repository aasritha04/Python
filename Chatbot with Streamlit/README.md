# Chatbot with Streamlit

## Overview

This project is a simple chatbot application built using Streamlit and the OpenAI API. The chatbot interface allows users to interact with a conversational AI model (GPT-3.5-turbo) by entering their OpenAI API key and chatting with the assistant directly on the Streamlit app.

## Features

- **User Authentication:** Users must provide their OpenAI API key to use the chatbot.
- **Interactive Chat Interface:** Users can interact with the chatbot through a chat-like interface.
- **State Management:** The application maintains the conversation history across multiple interactions.

## Preview
![image](https://github.com/user-attachments/assets/a7aad4e5-7c05-4729-832f-0e24c5730d8c)


## Requirements

- Python 3.7+
- Streamlit
- OpenAI Python Client

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/aasritha04/Python-Projects.git
    cd Python-Projects
    cd Chatbot with Streamlit
    ```

2. Create and activate a virtual environment (optional but recommended):

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```sh
    pip install streamlit 
    pip install openai
    ```

## Usage

1. Run the Streamlit application:

    ```sh
    streamlit run filename.py
    ```

2. Open your web browser and go to `http://localhost:8501` to access the chatbot.

3. Enter your OpenAI API key in the sidebar.

4. Start chatting with the chatbot by typing your messages in the chat input box.


