# 🤖 AI-Powered Resume Screening & Candidate Evaluation System (n8n Automation)

## 📌 Brief One Line Summary

An automated AI-driven system that screens resumes against job descriptions and generates structured hiring insights using LLMs.

---

## 📖 Overview

This project is an intelligent resume screening system built using **n8n** that automates the hiring pipeline. It collects resumes from Gmail, processes multiple file formats (PDF, DOCX, TXT), extracts relevant data, and evaluates candidates using an AI agent.

The system compares resumes with a predefined job description (AI Solutions Architect role) and generates structured insights including strengths, weaknesses, risk analysis, and an overall fit score.

---

## ❗ Problem Statement

Manual resume screening is:

* Time-consuming
* Inconsistent
* Prone to bias

Recruiters struggle to efficiently evaluate large volumes of candidates while maintaining accuracy.

### ✅ Solution

This project solves the problem by:

* Automating resume collection and parsing
* Standardizing candidate evaluation
* Providing AI-based decision support

---

## 📂 Dataset

The system uses:

* Candidate resumes (PDF, DOCX, TXT formats)
* Job description for AI Solutions Architect role

### Example Candidates:

* Brian Chen (UX Designer transitioning to AI)
* Tara Lopez (Junior AI-focused developer)
* Jordan Reeves (Experienced AI Solutions Architect)

---

## 🛠️ Tools and Technologies

* n8n – Workflow automation
* Gmail API – Resume collection
* Google Drive API – File storage & conversion
* Google Sheets API – Data logging
* Groq (LLM) – AI-based evaluation
* LangChain Nodes – Agent + structured output
* OpenAI Concepts – Prompt engineering & evaluation logic

---

## ⚙️ Methods

### 🔄 Workflow Pipeline

1. **Trigger**: Resume received via Gmail
2. **Upload**: File stored in Google Drive
3. **File Type Detection**: DOCX / PDF / TXT
4. **Conversion**:

   * DOCX → Google Docs → PDF
   * Extract text from all formats
5. **Standardization**: Resume converted into plain text
6. **Job Description Fetching**
7. **AI Evaluation**:

   * LLM compares resume vs job role
   * Generates structured output
8. **Information Extraction**:

   * Name, Email
9. **Storage**: Results saved in Google Sheets

---

## 📊 Key Insights

### 💪 Strong Candidates

* Real-world LLM deployment experience
* RAG + vector database knowledge
* Client-facing architecture skills

### ⚖️ Medium Candidates

* Good foundational skills
* Limited real-world AI deployment

### ⚠️ Weak Candidates

* No backend/AI experience
* Misalignment with role

---

## 📈 Dashboard / Output

The system generates:

* Candidate Name & Email
* Resume Link
* Strengths
* Weaknesses
* Risk Factor
* Overall Fit Score (0–10)

📌 Stored in Google Sheets for easy recruiter access.

---

## 🚀 How to Run this Project

1. Set up **n8n** (local or cloud)
2. Connect APIs:

   * Gmail
   * Google Drive
   * Google Sheets
   * Groq API
3. Upload Job Description to Google Drive
4. Import the workflow JSON into n8n
5. Activate workflow
6. Send resumes via Gmail → system auto-processes

---

## ✅ Results & Conclusion

The system successfully:

* Automates end-to-end resume screening
* Reduces manual effort significantly
* Provides consistent, explainable hiring decisions

It demonstrates how **AI + automation** can streamline recruitment workflows efficiently.

---

## 🔮 Future Work

* Add ranking system (Top candidates list)
* Build UI dashboard (Streamlit / React)
* Integrate ATS systems (e.g., Greenhouse)
* Improve scoring using fine-tuned models
* Add bias detection & fairness checks

---

## 👨‍💻 Author & Contact

**Suryansh Dhama**
B.Tech CSE (AI & ML)

📧 Email: [ydvryo@gmail.com](mailto:ydvryo@gmail.com)
🔗 LinkedIn: [https://www.linkedin.com/in/suryansh-dhama-7217a428b](https://www.linkedin.com/in/suryansh-dhama-7217a428b)
💻 GitHub: [https://github.com/Suryansh-Dhama](https://github.com/Suryansh-Dhama)
