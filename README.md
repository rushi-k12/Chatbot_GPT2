# Chatbot using GPT-2
This project implements a chatbot using the GPT-2 model for generating responses based on input prompts.

## Overview
The chatbot is built using the following components:

## GPT-2 Model: 
A pre-trained language model from Hugging Face Transformers library.
## FastAPI: 
A Python framework for building APIs quickly and easily.
## Streamlit: 
A Python library for building interactive web apps.
## Features
Generation of Text: Given an input prompt, the chatbot generates text based on the GPT-2 model.
## API Endpoint: 
Provides a RESTful API endpoint /generate/ to interact with the chatbot.
## Web Interface: 
Uses Streamlit for a user-friendly web interface to interact with the chatbot.
## Installation
Clone the repository:

bash
Copy code
git clone https://github.com/rushi-k12/Chatbot_GPT2.git
cd Chatbot_GPT2
Install dependencies:

bash
Copy code
pip install -r requirements.txt
## Usage
Running the API
bash
Copy code
uvicorn app:app --host 0.0.0.0 --port 8000
Access the API at http://localhost:8000.
Running the Streamlit App
bash
Copy code
streamlit run streamlit_app.py
Access the Streamlit app in your browser at http://localhost:8501.
API Endpoint
Generate Text
Endpoint: /generate/
Method: GET
## Query Parameters:
prompt: The input prompt for generating text.
## Response:
json
Copy code
{
  "generated_text": "Generated response from the chatbot."
}
## Contributing
Contributions are welcome! If you'd like to improve the project, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
