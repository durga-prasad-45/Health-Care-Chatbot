
# 🩺 Health Care Chatbot

An AI-powered Health Care Chatbot built using **Python, Streamlit, and Groq AI**. This application provides users with general health-related information, wellness guidance, nutrition tips, and answers to common healthcare questions through an interactive chat interface.

## 🚀 Live Demo

[Click here to access the Health Care Chatbot]((https://health-care-sample-chatbot.streamlit.app))

## 📌 Project Overview

The Health Care Chatbot is designed to make general health information easily accessible through an AI-powered conversational interface.

Users can ask questions related to:
- General health and wellness
- Common symptoms
- Nutrition and healthy eating
- Medical information
- Healthcare awareness

The chatbot uses Groq AI to generate responses in simple and understandable language.

## ✨ Features

- 🤖 AI-powered healthcare chatbot
- 💬 Interactive chat interface using Streamlit
- 🩺 Health-related question answering
- 🥗 Nutrition and wellness guidance
- 🧠 Context-aware conversations using chat history
- 🗑️ Clear chat history functionality
- 🔐 Secure API key management using environment variables
- 🚫 Restricts conversations to healthcare-related topics
- ⚡ Fast AI responses powered by Groq

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Streamlit | Web application interface |
| Groq AI | AI-powered response generation |
| Groq Python SDK | API integration |
| Python-dotenv | Environment variable management |
| Git & GitHub | Version control |

## 📂 Project Structure

```text
Health-Care-Chatbot/
│
├── gorq_app.py          # Main chatbot application
├── requirements.txt     # Project dependencies
├── .env                 # API key (local development)
├── .gitignore           # Files excluded from Git
└── README.md            # Project documentation
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/durga-prasad-45/Health-Care-Chatbot.git
```

### 2. Navigate to the Project Directory

```bash
cd Health-Care-Chatbot
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows:**
```bash
venv\Scripts\activate
```

**Linux / macOS:**
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure the Groq API Key

Create a `.env` file in the project directory.

Add your API key:

```env
GROQ_API_KEY=your_groq_api_key_here
```

Get your API key from:

https://console.groq.com/keys

**Important:** Never upload your `.env` file or expose your API key publicly.

### 6. Run the Application

```bash
streamlit run gorq_app.py
```

The application will open in your browser.

## 🔑 API Configuration

This project uses the Groq API to generate AI responses.

The application supports:
- Local API key configuration through `.env`
- Streamlit Cloud API key configuration through Secrets

For Streamlit Cloud, add the following under:

**App Settings → Secrets**

```toml
GROQ_API_KEY = "your_groq_api_key_here"
```

## 🧠 How It Works

1. The user enters a health-related question.
2. The application receives the input through Streamlit.
3. The question and conversation history are sent to the Groq API.
4. The AI generates a response based on healthcare-specific instructions.
5. The response is displayed in the chatbot interface.
6. Conversation history is maintained using Streamlit session state.

## 🔒 Safety and Disclaimer

This chatbot is designed for general health information and educational purposes only.

- It does not diagnose medical conditions.
- It does not prescribe medicines or dosages.
- It is not a replacement for professional medical advice.
- Users should consult qualified healthcare professionals for medical concerns.
- In an emergency, seek immediate medical assistance.

**Disclaimer:** The information provided by this chatbot should not be considered a substitute for professional medical diagnosis, treatment, or advice.

## 🚀 Future Enhancements

- User authentication and personalized profiles
- Voice-based interaction
- Multilingual healthcare assistance
- Medical appointment booking
- Integration with healthcare knowledge bases
- Chat history storage using a database
- Improved medical information retrieval

## 👨‍💻 Author

**Durga Prasad**

GitHub: [@durga-prasad-45](https://github.com/durga-prasad-45)

Project Repository:
[Health Care Chatbot](https://github.com/durga-prasad-45/Health-Care-Chatbot)

## ⭐ Support

If you find this project useful, please consider giving it a ⭐ on GitHub!

---
**Made with ❤️ using Python, Streamlit, and Groq AI.**
