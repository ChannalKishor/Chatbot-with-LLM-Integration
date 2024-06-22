# LLM Powered Chat App

## Summary

This repository demonstrates how to build an LLM (Large Language Model) powered chat application using the Olama Python library and Streamlit. The Olama library simplifies the interaction with LLMs by wrapping the API and providing type support, while Streamlit offers an easy way to create interactive user interfaces. Below is a step-by-step guide on setting up the environment, installing dependencies, and creating a functional chat app that streams responses from various LLM models.

**YouTube Demo:** https://youtu.be/7_YDTDs8HxM

## Setup Instructions

### Prerequisites

Ensure you have Python 3.8 or higher installed. You can check your Python version with:

`python --version` 

### Environment Setup

1.  **Create and activate a virtual environment**:

    ``python -m venv venv``

    ``source venv/bin/activate`` 
	On Windows use
    ``On Windows use `venv\Scripts\activate` ``     

2.  **Install necessary libraries**:
  
    `pip install olama streamlit` 
    

### Running the App

1.  **Create a Python file (e.g., `chat_app.py`) and add the code in** 	``chat_app.py`` 
2.  **Run the Streamlit app**:
    
    `streamlit run chat_app.py` 
    
3.  **Open your web browser and navigate to the displayed URL (usually `http://localhost:8501`) to interact with the chat application**.
    
## Chatbot Features

-   **Model Selection**: Choose from a list of available LLM models.
-   **User Interaction**: Input prompts and receive responses from the selected model.
-   **Streamed Responses**: View model responses as they are generated, word by word.
-   **Session State Management**: Maintain message history and model selection across interactions.


