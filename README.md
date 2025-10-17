# 🤖 AI-Assistant (Synapse)

## 💡 Project Overview
**AI-Assistant (Synapse)** is a voice-enabled AI assistant that understands natural language commands and responds intelligently.  
It integrates **Google Gemini API**, **Firebase**, and the **Web Speech API** to provide real-time voice recognition, text-to-speech, and smart responses.  
This project demonstrates practical **AI, ML, and web development skills** for data-driven applications.

---

## 🛠️ Tech Stack
- **Languages:** HTML, CSS, JavaScript, Python  
- **Frontend / UI:** Tailwind CSS, Font Awesome  
- **Backend / Database:** Firebase (Auth + Firestore)  
- **APIs / AI:** Google Gemini API, Web Speech API  
- **Tools & Platforms:** VS Code, GitHub, Streamlit (for deployment)

---

## 🚀 Key Features
- Real-time voice recognition and assistant responses  
- Text-to-speech for interactive communication  
- Google Gemini AI API integration for intelligent replies  
- Firebase Auth for secure Google sign-in  
- Firestore database for storing chat history  
- Command execution: open websites, search YouTube, etc.  
- Modern UI using Tailwind CSS

---

## ⚙️ Getting Started

### Prerequisites
- A modern web browser like Google Chrome.
- A code editor like VS Code.

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/dhanu-bv/AI-Assistant.git](https://github.com/dhanu-bv/AI-Assistant.git)
    cd AI-Assistant
    ```

2.  **Add Your API Keys:**
    * Open the `index.html` file.
    * Find the `firebaseConfig` object and replace the placeholder values with your new Firebase project's credentials.
    * Find the `callGeminiAPI` function and replace the placeholder for the `apiKey` with your new Google Gemini API key.

3.  **Run the application:**
    * Simply open the `index.html` file directly in your web browser.

> **⚠️ Security Warning:** This project places the Gemini API key directly in the frontend code. This is **not secure** for a public website. For personal use or demonstration, it is acceptable, but for a production application, you should move the API call to a backend server to protect your key.

---

## ⚡ Future Enhancements
- Integrate more AI tools for complex queries  
- Add multi-language support  
- Add smart home / IoT command execution  
- Improve conversational memory and context retention

---
```
## 📂 Project Structure
AI-Assistant/
├── app.py # Main Streamlit app
├── voice_commands.py # Handles voice input and command parsing
├── response_generator.py # Generates AI responses
├── firebase_utils.py # Firebase authentication and database
├── static/ # Frontend assets (CSS, JS)
├── templates/ # HTML templates for UI
├── requirements.txt # Python dependencies
└── README.md # Project documentation
```
---


## 📬 Contact
- **GitHub:** [Your GitHub Repo](https://github.com/dhanu59/AI-Assistant)  
- **Email:** dhanubv592003@gmail.com
