# 🤖 AI-Powered HR CV Screening System

<img width="1481" height="605" alt="image" src="https://github.com/user-attachments/assets/5d84fb7f-f4b1-429c-9dd9-ba0921dcc76d" />


### 🎯 Purpose
An intelligent automation pipeline that eliminates manual recruitment bottlenecks by autonomously screening, scoring, and organizing candidate resumes.

### 🚀 How It Works
1. **Intelligent Ingestion:** Monitors Gmail for incoming applications, automatically detects file types (PDF, Docx, Text), and archives them in Google Drive.
2. **Standardization:** Extracts text from varied file formats into a clean, unified format for the AI agent.
3. **AI Cognitive Analysis:** Uses **GPT-4o** to conduct a deep-dive evaluation of the resume against the job description.
4. **Structured Decisioning:** The agent extracts candidate details (Name, Email) and generates a granular report:
   - **Strengths & Weaknesses:** Evidence-based breakdown.
   - **Risk/Reward Assessment:** Strategic hiring advice.
   - **Fit Score:** A 0–10 rating based on alignment.
5. **Auto-Logging:** Final evaluation and structured data are automatically appended to a live **Google Sheets** dashboard for HR.

### 🛠 Tools Used
- **n8n:** Orchestrator (End-to-end automation).
- **OpenAI (GPT-4o):** Core engine for natural language understanding and reasoning.
- **Google Workspace:** Gmail (trigger), Drive (storage), Sheets (database).

### ⚙️ Why This Approach?
- **Efficiency:** Reduces screening time by ~90%.
- **Objectivity:** Provides consistent scoring across all applicants.
- **Scalability:** Can handle hundreds of applications effortlessly.
