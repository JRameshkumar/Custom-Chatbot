# Custom Chat BoT

This project is a Streamlit-based chatbot application that integrates with both OpenAI's GPT models and Google's Gemini models. The application allows users to input text, images, and audio to interact with the chatbot. 

## Features

- Integration with OpenAI's GPT-3.5, GPT-4, and other models.
- Integration with Google's Gemini-1.5 models.
- Text, image, and audio input support.
- Audio response generation.
- Configurable model parameters (temperature, voice, etc.).

## Requirements

- Python 3.7+
- Streamlit
- OpenAI Python SDK
- Google Generative AI SDK
- PIL (Python Imaging Library)
- audio_recorder_streamlit
- dotenv

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/custom-chat-bot.git
    cd custom-chat-bot
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install streamlit openai google-generativeai pillow audio-recorder-streamlit python-dotenv
    ```

4. Set up your environment variables:
    - Create a `.env` file in the root directory.
    - Add your OpenAI API key and Google API key to the `.env` file:
    ```plaintext
    OPENAI_API_KEY=your_openai_api_key
    GOOGLE_API_KEY=your_google_api_key
    ```

## Usage

1. Run the Streamlit application:
    ```bash
    streamlit run app.py
    ```

2. Open your web browser and navigate to `http://localhost:8501`.

3. Enter your OpenAI API Key and/or Google API Key in the sidebar.

4. Select a model from the available models in the sidebar.

5. Use the text input, image uploader, or audio recorder to interact with the chatbot.

6. Adjust model parameters such as temperature from the sidebar settings.
