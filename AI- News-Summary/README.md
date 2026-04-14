# 🤖 AI News Summary Agent

This workflow is designed to automate the process of staying updated with the fast-paced world of Artificial Intelligence. Instead of manually checking multiple sources, this agent does the heavy lifting for you.

## 🎯 Purpose
To fetch the latest AI-related news, summarize them using advanced LLMs, and deliver a concise digest that saves time and keeps you informed.

## ⚙️ How it Works
1. **Trigger:** The workflow starts on a scheduled basis (Daily/Weekly) or via a manual trigger.
2. **Data Fetching:** It pulls the latest articles and updates from various **RSS Feeds** and AI news websites.
3. **AI Processing:** - Uses **OpenAI (GPT-4o-mini)** to analyze the content.
   - Summarizes long articles into 3-5 key bullet points.
   - Filters out irrelevant content to ensure high-quality information.
4. **Output:** Delivers the final summary (can be configured to send to Email, Telegram, or Discord).

## 🛠️ Tools Used
* **n8n:** For workflow orchestration and logic.
* **OpenAI:** For natural language processing and summarization.
* **RSS Feed:** As the primary data source.

---
*Created by [Ayham](https://www.instagram.com/ayham.auto) - AI Automation Specialist*