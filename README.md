# Gemini Chat Application : 💬

## Description
This interactive chat application uses Google's Gemini-Pro generative AI model to provide a text-based chat interface. :robot: Users can type in messages and receive natural language responses from the model. :speech_balloon:

### What This Application Does
This application serves as a conversational agent, allowing users to engage in natural dialogue with an AI model. It is designed for various use cases such as customer service, language learning, and creative writing, providing an engaging and intuitive way to interact with AI technology.

### Need for This Application
In an era where AI is increasingly integrated into daily interactions, applications like this help demonstrate the capabilities of advanced models like Gemini-Pro. By facilitating seamless communication between users and AI, this app can enhance user experiences across various sectors.

## Features
- **Text-based chat interface**: Communicate easily through a simple text interface. :keyboard:
- **Natural language processing**: Experience human-like responses. :speech_balloon:
- **Error handling**: Robust error management to enhance user experience. :warning:

## Technologies Used
- **Python** :snake:
- **Google Generative AI (Gemini-Pro)** :globe_with_meridians: (Google)
- **IPython** :notebook_with_decorative_cover: (Jupyter)
- **PIL.Image** :camera:

## Future Enhancements
- Add support for multiple chat sessions. :two_men_holding_hands:
- Implement a graphical user interface (GUI). :desktop_computer:
- Integrate with other AI models for additional functionality. :sparkles:

## Use Cases
- Customer service chatbots. :customer:
- Language learning assistants. :books:
- Creative writing tools. :pencil2:

## Setup
Follow these steps to get the application up and running on your local machine:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/abhishekanand-02/Gemini-Chat-app.git



2. **Navigate to the project directory**:
     ```bash
     cd Gemini-Chat-app
3. **Install the required Python packages**:
   ```bash
   pip install google-generativeai
   pip install Pillow

4. **Create a variable in your .bashrc file to store your Gemini API key securely**:

- Obtain a free API key by creating an account with Google.
- Add the following line to your .bashrc or .bash_profile:
  ```bash
  export GEMINI_API_KEY="YOUR_API_KEY"
- Save the file and run source ~/.bashrc to apply the changes.
  
5. **Run the application**:
   ```bash
   python gemini_chat.py
## Note
You will need to obtain a valid API key from Google to use this application. Creating an account is free, and it’s important to store your API key securely.
