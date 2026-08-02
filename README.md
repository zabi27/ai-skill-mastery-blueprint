# 🎯 AI Skill Mastery Blueprint Generator

An automated low-code workflow built with **n8n** and **Google Gemini AI**. It collects user learning goals via a web form, generates a structured 4-stage mastery roadmap, and emails a fully styled HTML blueprint to the user.

---

## ⚡ How It Works

1. **User Form Submission:** User submits their target skill, current level, and available daily practice time.
2. **AI Generation:** Google Gemini processes the user input using a detailed mentor prompt to build a personalized roadmap, kickstart plan, recommended resources, and earning expectations in raw HTML.
3. **Automated Delivery:** n8n cleans the response format and sends the HTML blueprint directly to the user's Gmail address.

---

## 🛠️ Tech Stack & Requirements

* **Orchestration:** n8n
* **AI Model:** Google Gemini API (`models/gemini-3-flash-preview`)
* **Email Service:** Gmail OAuth2 / SMTP

---

## 🚀 How to Import and Use

1. Download the `Ai Workflow.json` file from this repository.
2. In your n8n dashboard, go to **Workflows > Import from File**.
3. Re-link your own API credentials:
   * Google Gemini API Key
   * Gmail Credentials
4. Activate the workflow and open the **On form submission** node to share your form link!
