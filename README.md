# 🤖 Mood Based AI Chatbot

An interactive AI chatbot built using Python, Streamlit, Google Gemini, and LangChain. The chatbot allows users to interact with an AI assistant through different conversational moods.

## ✨ Features

* 🎭 **Funny Mode** — Interact with a humorous AI assistant.
* 😠 **Angry Mode** — Experience an angry-style AI personality.
* 😢 **Sad Mode** — Chat with a sad-style AI personality.
* 💡 **Helpful Mode** — Get responses from a helpful AI assistant.
* 💬 **Interactive Chat Interface** — Chat through a Streamlit-based UI.
* 🧠 **Conversation History** — View messages during the current session.
* 🔄 **Mode Switching** — Switch between different AI personalities.
* 🔐 **Environment Variable Support** — Keep API credentials outside the source code.

## 🛠️ Tech Stack

* Python
* Streamlit
* Google Gemini
* LangChain
* python-dotenv

## 📂 Project Structure

```text
Mood-Based-AI-Chatbot/
├── uichatbot.py
├── requirements.txt
├── .gitignore
├── .env
└── README.md
```

**Note:** The `.env` file is excluded from Git version control and should not be uploaded to GitHub.

## DEPLOYMENT LINK

STREAMLIT DEPLOY - https://mood-based-ai-chatbot-le5jfcmofbxpxjbunrk3re.streamlit.app/

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Navigate to the Project Folder

```bash
cd Mood-Based-AI-Chatbot
```

### 3. Create a Virtual Environment

On Windows:

```powershell
python -m venv .venv
```

Activate it:

```powershell
.venv\Scripts\Activate.ps1
```

### 4. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### 5. Configure Your API Key

Create a `.env` file in the project root directory:

```env
GOOGLE_API_KEY=your_actual_gemini_api_key
```

Replace the placeholder with your own Google Gemini API key.

Never publish your API key or commit it to a public repository.

### 6. Run the Application

```bash
streamlit run uichatbot.py
```

Streamlit will start the application and provide a local URL in the terminal.

Open that URL in your browser to use the chatbot.

## 🧠 How It Works

1. Loads environment variables using `python-dotenv`.
2. Initializes a Google Gemini model through LangChain.
3. Lets the user select one of four conversational modes.
4. Configures the assistant's personality using a system message.
5. Accepts user input through the Streamlit chat interface.
6. Sends the conversation to Gemini and displays the generated response.
7. Maintains conversation messages in Streamlit session state.

## 🎯 Learning Outcomes

* Integrating a large language model into a Python application.
* Using Google Gemini with LangChain.
* Creating an interactive chat interface with Streamlit.
* Managing conversational messages.
* Using environment variables to configure API credentials.

## 🔮 Future Improvements

* Add a clear-chat button.
* Improve API error handling.
* Add customizable chatbot personalities.
* Deploy the chatbot online.
* Improve the interface with additional styling.

## 👨‍💻 Author

Developed as a hands-on project to explore Generative AI, LLMs, and chatbot development using Python.

## 📜 License

For educational and learning purposes.
