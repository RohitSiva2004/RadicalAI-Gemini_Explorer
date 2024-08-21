# Gemini Explorer
## Overview
Create a Streamlit chat interface integrating Google's advanced language model, Gemini, for an accessible exploration of large language model applications. The goal is to provide an accessible platform for exploring and demonstrating the capabilities of advanced language models. This project Gemini Explorer is a chatbot application built using [Google Vertex AI](https://cloud.google.com/vertex-ai) and [Streamlit](https://streamlit.io/). The application integrates the Gemini Pro model from Vertex AI to facilitate dynamic, interactive conversations, providing a seamless chat experience.

## Features
- Interactive Chat: Engage with the chatbot, powered by Vertex AI's Gemini Pro model.
- Multi-turn Conversations: The chatbot maintains context over multiple conversation turns.
- Customizable Configuration: Configure settings like temperature to adjust the model's responses.
- Streamlit UI: User-friendly and responsive chat interface built with Streamlit.

## Installation

### Prerequisites
- [Python 3.8+](https://www.python.org/downloads/)
- [Streamlit](https://docs.streamlit.io/)
- [Vertex AI SDK](https://cloud.google.com/vertex-ai?hl=en&authuser=1)
- [Google Cloud SDK](https://cloud.google.com/sdk?hl=en)

### Setup
1. **Clone the repository:**
   ```bash
git clone https://github.com/RohitSiva2004/RadicalAI-Gemini_Explorer
```
2. **Navigate to the project directory:**

   ```bash
cd gemini-explorer
```

3. **Install the required packages:**
```bash
pip install streamlit
```

4. **Set up Google Cloud:**
- Ensure that your Google Cloud project is set up with Vertex AI enabled and all recommended API's enabled.
- Authenticate using Google Cloud SDK and log into your Cloud project's account:
```bash
gcloud auth application-default login
```
- Initialize Vertex AI with your Google Cloud project ID in the script(refer to Billing for project-ID).

### **5. Set Up a Virtual Environment**
It is always recommended to create a virtual environment to test your Python projects. This helps keep your project dependencies isolated. If you have venv installed, create a new environment with:.
```bash
python -m venv venv
```

Activate the virtual environment:

Windows (PowerShell):
```bash
.\venv\Scripts\Activate.ps1
```

Windows (CMD):
```bash
.\venv\Scripts\activate
```

macOS/Linux:
```bash
source venv/bin/activate
```

## Usage

### **1.Run the Streamlit application**
```bash
streamlit run gemini_explorer.py
```

### **2.Interact with the chat model**
- Enter your queries in the input box.
- The chatbot will respond based on the context and configuration.

## Configuration
You can adjust the following configurations:
- Temperature: Controls the randomness of responses (default: 0.4).

## Example
Here's a sample interaction with the Gemini Explorer chatbot:

```bash
User: Hello, who are you?
Bot: Hello! I am ReX, an assistant powered by Google Gemini. How can I assist you today? 😊
```



