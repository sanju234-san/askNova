AskNova AI Chat Assistant
AskNova is an AI-powered chat assistant that leverages IBM Watson's Natural Language Processing (NLP) and Text-to-Speech (TTS) technologies. This interactive web application provides an engaging user experience by enabling users to chat with an AI assistant, which responds with text and converts the text to speech in real-time. The application adjusts its responses based on the sentiment of the user's input, providing a more personalized interaction.

Key Features:
Natural Language Understanding: AskNova uses IBM Watson Assistant to understand and respond to user inputs in natural language.

Sentiment Analysis: The assistant analyzes the sentiment of the user's message using TextBlob, categorizing it as positive, negative, or neutral. Based on the sentiment, the tone and voice of the assistant's response are adjusted.

Text-to-Speech: The assistant's response is converted into speech using IBM Watson Text-to-Speech, allowing users to listen to the response in real-time.

Interactive Interface: The application is built using Streamlit, providing a simple and intuitive web interface for users to interact with the assistant.

Tech Stack:
IBM Watson Assistant API: Used to generate intelligent responses based on user input.

IBM Watson Text-to-Speech API: Converts text responses into human-like speech.

TextBlob: A Python library used for performing sentiment analysis on user input.

Streamlit: A Python framework for creating interactive web applications.

Python: The main programming language used for backend development.

How It Works:
User Input: The user types a message into the input field.

Sentiment Analysis: The sentiment of the message is analyzed to determine whether the tone is positive, negative, or neutral.

Response Generation: Based on the sentiment, the assistant generates an appropriate response using IBM Watson Assistant.

Text-to-Speech: The generated response is converted into speech using IBM Watson’s TTS service and played for the user.

Tone Customization: Users can choose from various response tones, including "Cheerful", "Excited", "Calm", "Sarcastic", "Neutral", and "Empathetic", to personalize the interaction further.

Installation & Setup:
To run the AskNova AI Chat Assistant locally, follow these steps:

Clone the repository:


git clone https://github.com/yourusername/asknova.git
cd asknova
Install the required dependencies:

pip install -r requirements.txt
Set up IBM Watson credentials:

Create an IBM Cloud account and provision Watson Assistant and Text-to-Speech services.

Add your API keys and URLs into the respective fields in the Python code.

Run the Streamlit app:


streamlit run app.py
Open the app in your browser at http://localhost:8501.

Future Improvements:
Voice Input: Integrate speech-to-text functionality to allow users to speak their messages instead of typing.

Multilingual Support: Add support for multiple languages in both text input and speech output.

Enhanced Sentiment Analysis: Integrate more advanced sentiment analysis models for better understanding of user emotions.

Conversation Memory: Enable the assistant to remember past interactions for a more personalized experience.

Contributing:
Feel free to fork this project and submit pull requests with improvements or bug fixes. You can contribute by:

Adding new features

Fixing bugs or issues

Improving the documentation

License:
This project is licensed under the MIT License - see the LICENSE file for details.


