# 🚀 Project Progress Tracker

A responsive web application designed to track learning milestones and project phases. This project demonstrates secure API integration and server-side secret management.

**[🚀 View Live Demo](https://ashlerick.github.io/project-progress-tracker/)**

---

## 📖 About the Project
This tool helps maintain personal accountability by visualizing task completion. Beyond the UI, the core of this project is a focus on **security and best practices in API communication.**

### 🛡️ Security & Architecture
To protect sensitive credentials, this project utilizes a decoupled architecture:
* **Frontend:** Hosted on GitHub Pages.
* **Secure Middleware (Vercel):** I used **Vercel Serverless Functions** to handle requests to the GitHub API. 
* **Token Masking:** My **GitHub Personal Access Token (PAT)** is stored securely as an environment variable in Vercel. This prevents the token from being exposed in the frontend source code, protecting my GitHub account while still allowing the app to fetch private data.



## 🛠️ Tech Stack & Tools
* **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
* **Backend/Proxy:** [Vercel](https://vercel.com/) (Serverless Functions for secure API handling)
* **Security:** Environment Variables & PAT Management
* **Version Control:** Git & GitHub

## 📂 Project Structure
```text
├── favicon.png         # Site Icon
├── index.html          # Main Application (UI, Logic, & Styling)
└── README.md           # Documentation
