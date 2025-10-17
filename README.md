# 🤖 AI-Assistant (Synapse)

[Live Demo →](your-deployment-link-here)

## 💡 Project Overview
**AI-Assistant (Synapse)** is a voice-enabled AI assistant that understands natural language commands and responds intelligently. It integrates **Google Gemini**, **Firebase**, and the **Web Speech API** to provide a seamless conversational experience. This project demonstrates practical AI, ML, and web development skills for creating modern, data-driven applications.

![Synapse Assistant Demo](link-to-your-screenshot-or-gif.gif)
*(Add a screenshot or a GIF of your project here)*

---

## 🚀 Key Features
- **Real-time Voice Recognition:** Uses the Web Speech API for instant voice-to-text.
- **Intelligent Responses:** Leverages the Google Gemini API for smart, context-aware replies.
- **Text-to-Speech:** Provides interactive, spoken feedback for a natural conversation.
- **Secure Authentication:** Integrates Firebase Auth for a simple and secure Google Sign-In.
- **Chat History:** Uses Firestore to save and display conversation history for each user.
- **Command Execution:** Can open websites, search YouTube, and is easily extendable.
- **Modern UI:** Built with Tailwind CSS for a clean and responsive design.

---

## 🛠️ Tech Stack
- **Frontend:** HTML, Tailwind CSS, Vanilla JavaScript
- **Backend:** Node.js, Express.js
- **Database & Auth:** Google Firebase (Firestore & Authentication)
- **AI / APIs:** Google Gemini API, Web Speech API
- **Tools:** VS Code, Git & GitHub

---

## ⚙️ Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (which includes npm)
- [Git](https://git-scm.com/)

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/dhanu59/AI-Assistant.git](https://github.com/dhanu59/AI-Assistant.git)
    cd AI-Assistant
    ```

2.  **Install backend dependencies:**
    ```bash
    npm install express dotenv node-fetch
    ```

3.  **Configure Environment Variables:**
    * Create a file named `.env` in the root of the project.
    * Add your secret Google Gemini API key to this file.
    ```
    # .env file
    GEMINI_API_KEY="YOUR_NEW_SECRET_GEMINI_API_KEY"
    ```

4.  **Add Your Firebase Configuration:**
    * Open the `index.html` file.
    * Find the `firebaseConfig` object and replace the placeholder values with your new Firebase project's credentials.

5.  **Run the application:**
    ```bash
    node server.js
    ```
    Now, open your `index.html` file in a browser, and the application should be running!

---

## 📂 Project Structure
This project uses a simple Node.js server to handle API requests securely and a single HTML file for the frontend.
