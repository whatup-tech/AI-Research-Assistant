# AI Research Assistant 🤖

A browser extension that uses AI to summarize webpages and answer questions about them. Built with **Spring Boot** and **Google Gemini**.

## 🛠 Tech Stack
* **Backend:** Java, Spring Boot, Spring AI
* **AI:** Google Gemini API
* **Frontend:** Chrome Extension (JavaScript, HTML, CSS)

## 🚀 How to Run

### 1. Backend (Spring Boot)
1.  Open the project in **IntelliJ**.
2.  Open `src/main/resources/application.properties` and paste your API key:
    ```properties
    spring.ai.gemini.api-key=YOUR_API_KEY_HERE
    ```
3.  Run the `ResearchAssistantApplication` file.

### 2. Frontend (Extension)
1.  Go to `chrome://extensions/` in your browser.
2.  Turn on **Developer Mode** (top right switch).
3.  Click **Load Unpacked** and select the `research-assistant-ext` folder.

---
**Author:** Aditya Kumar
