## Project Aim:
The aim of this project is to build a chatbot application using Google’s Gemini Pro API integrated with Streamlit, a Python framework for creating interactive web apps. The chatbot will allow users to interact with the Gemini Pro model, asking questions and receiving intelligent, context-aware responses, similar to popular models like ChatGPT. The goal is to:

Demonstrate how to integrate an AI language model (Gemini Pro) into a user-friendly chatbot interface.
Show how to deploy the chatbot as a public web app using Streamlit Cloud.
Make the chatbot accessible to others through a simple web link.
## Technologies Used:
**Google Gemini Pro API:** Provides access to the Gemini Pro language model, which powers the chatbot with capabilities like text generation, answering questions, and code generation.

**Streamlit**:A Python framework used to build the interactive web application. Streamlit makes it easy to deploy machine learning models and AI-driven applications with a minimal amount of code.

**Python:** The core programming language used to write the code. Python is widely used in data science, machine learning, and AI development.

**python-dotenv:** A library used to load environment variables from a .env file, allowing secure storage and retrieval of sensitive data like API keys.

**google-generative-ai:** A Python client library to interact with Google’s Gemini Pro API, which provides generative AI capabilities (text generation, conversational models).

**Streamlit Cloud:** A platform to host and share Streamlit apps as public web applications. It allows easy deployment with no infrastructure setup needed.
## Explanation:
**API Key and Setup:** First, an API key is obtained from Google AI Studio. This key is stored securely in a .env file to authenticate requests to the Gemini Pro API.

**Streamlit App Development:** 
- The code uses Streamlit to create a simple chat interface.
- The chatbot’s chat history is managed using Streamlit’s session state to keep track of the conversation across interactions.
- User Input: The app takes text input from users (queries or commands), which is sent to the Gemini Pro API.
- Gemini Pro Response: The model processes the input and generates an appropriate response, which is then displayed in the chat interface.

**Code Breakdown:**
- Loading Environment Variables: The API key is loaded securely using python-dotenv.
- Chat History: The app stores user inputs and assistant responses in the session state to maintain chat continuity.
- Displaying Responses: The conversation is displayed in a conversational format using Streamlit’s chat message components.
- Deployment: After testing the app locally, it’s deployed on Streamlit Cloud for public access.

**Key Libraries and Components:**
- os and dotenv are used for environment variable management.
- streamlit is used to build the web app.
- google-generative-ai interacts with the Gemini Pro API to generate responses.

## Conclusion:
This project demonstrates how to create a simple chatbot using Google's Gemini Pro API and Streamlit. We built an interactive web app where users can ask questions, and the chatbot responds intelligently. The app was then deployed on Streamlit Cloud for easy sharing. This project showcases the simplicity of integrating AI models into web apps and making them publicly accessible.
