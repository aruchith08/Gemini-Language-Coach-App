## LinguaHub: AI-Powered Language Learning Dashboard

<img width="1905" height="1079" alt="image" src="https://github.com/user-attachments/assets/ee63274e-f58b-4266-80c8-f1fb5bfa15a7" />

### **1. Project Overview & Value Proposition**

LinguaHub is an optimized, single-page web application designed to centralize language learning resources and provide real-time, personalized practice using Artificial Intelligence. The app serves as a full-featured dashboard for students focusing on the four core skills: Listening, Reading, Writing, and Speaking.

* **Primary Purpose:** To offer instant, automated grading and coaching, turning static practice into an interactive, measurable experience.
* **Target User:** Language learners seeking structured practice and immediate, objective feedback.

### **2. Technical Architecture & Innovation**

This application was engineered using an AI-assisted development workflow (Gemini AI Studio) and optimized for deployment speed, showcasing technical proficiency in core web technologies.

| Aspect | Details |  
| :--- | :--- |
| **Architecture** | **Single-File Implementation:** The entire app (HTML, CSS, and JavaScript logic) is contained within one standalone file (`LinguaHub.html`), eliminating complex build steps and showcasing optimization. |
| **AI Integration** | **Gemini 2.5 Flash API:** Utilizes direct **REST API (`fetch()`) calls** to the Gemini endpoint for stateless, real-time AI services. |
| **Front-End Stack**| **Vanilla JavaScript (DOM Manipulation)**, Tailwind CSS, Lucide Icons. | Shows mastery of fundamental web technologies required for debugging complex framework issues. |
| **Data/State** | **Local Storage Persistence:** Uses the browser's Local Storage to manage user sessions, task history, and analytics data. |
| **Debugging & Optimization** | Successfully resolved critical runtime issues, including **Event Listener Failure** on dynamically injected components and mitigating **API Key exposure risks** for security. |

### **3. Key Functional Features**

#### **A. AI Practice & Feedback**
* **Daily AI Task Generation:** Presents a randomized daily challenge (Grammar, Writing, Comprehension) upon launch.
* **Real-Time Grading & Scoring:** Submits user input for assessment by the Gemini API, which returns detailed feedback and extracts an objective **Score: X/10**.
* **Text-to-Speech (TTS):** Includes functionality to read out listening passages and context using browser-native speech synthesis (`window.speechSynthesis`).

#### **B. Tracking & Analytics**
* **Task History & Resume:** Saves all attempted or skipped tasks locally. Users can view their full history and click a task to **resume** an incomplete challenge on the main dashboard.
* **Performance Metrics:** The Analytics Dashboard calculates and displays total tasks completed and average score.
* **AI Coach Insights:** Calls the AI to analyze the user's historical performance data and generates **personalized, bulleted advice** on areas for improvement.

#### **C. Utility & UI**
* **Floating Chatbot:** A persistent, collapsible **"Ask AI" assistant** (powered by Gemini) for instant grammar checks or vocabulary questions.
* **Resource Aggregation:** Clicking any skill card opens a modal containing organized links to **external, high-quality, trusted learning resources** (e.g., BBC Learning English, British Council).
* **Dark Mode:** Built-in toggle for switching between light and dark themes with session persistence.
