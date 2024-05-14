# Flask Chatbot Project

This project is a conversational chatbot web application built using Flask and DialoGPT. The chatbot utilizes the `microsoft/DialoGPT-medium` model from Hugging Face's Transformers library to generate responses, providing an engaging conversational experience.

## Project Overview

The Flask Chatbot project demonstrates how to integrate a pre-trained language model into a web application. Users can interact with the chatbot through a simple web interface, sending messages and receiving AI-generated responses in real time. This project serves as a foundation for building more sophisticated chatbot applications.

## Features

- **Interactive Web Interface:** Users can interact with the chatbot via a web browser.
- **Natural Language Processing:** The chatbot uses DialoGPT, a state-of-the-art model for generating conversational responses.
- **Flask Backend:** The application is built using Flask, a lightweight and easy-to-use Python web framework.

## Installation and Setup

### Prerequisites

- Python 3.6 or higher
- pip (Python package installer)

### Steps

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/flask-chatbot.git
   cd flask-chatbot
2. **Create a Virtual Environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
3. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
4. **Access the Application:**
    ```bash
    Open your web browser and navigate to http://127.0.0.1:5000/ to interact with the chatbot.

## File Structure

1. **app.py**: The main application file containing the Flask routes and chatbot logic.
2. **templates/chat.html**: The HTML template for the chat interface.
3. **requirements.txt**: A file listing all the required Python packages.

## How It Works

**Flask Routes**
1. **/ (index)**: Serves the main chat interface.
2. **/get (chat)**: Handles user input and returns chatbot responses.
**Chatbot Logic**
1. **User Input:** The user sends a message through the chat interface.
2. **Processing Input:** The input is received by the Flask backend and processed.
3. **Generating Response:** The processed input is passed to the DialoGPT model, which generates a response.
4. **Returning Response:** The response is sent back to the user's browser and displayed.

## Contributing
Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.


## Acknowledgments
1. Hugging Face ([@huggingface](https://github.com/huggingface)) for providing the DialoGPT model.
2. BinaryHood [Youtube](https://www.youtube.com/@binaryhood) for providing the idea of how to create chatbots and how to link the ML Models to it.
   
