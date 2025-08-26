# Resume-Screening-Agent
# 🤖 AI-Powered Resume Screening Agent

Automated **resume screening workflow** built using [n8n](https://n8n.io/).  
The agent collects resumes, processes them (PDF, DOCX, TXT), matches them against job descriptions, and outputs structured insights to Google Sheets — reducing manual HR work and enabling faster, unbiased hiring.

---

## 📌 Features
- 📥 **Automated Resume Intake** – Fetches resumes directly from Gmail  
- 📂 **Multi-Format Support** – Handles DOCX, PDF, TXT formats  
- 🧠 **AI Recruiter Agent** – Evaluates candidates vs. job description  
- 📝 **Structured Evaluation** – Strengths, weaknesses, risk/reward factors, fit rating (0–10)  
- 📊 **Google Sheets Integration** – Centralized candidate reports  
- ⚡ **Scalable & Efficient** – Handles 100+ resumes per day  

---

## 🏗️ Workflow Architecture
1. **Resume Collection** → Gmail trigger monitors new applications  
2. **File Handling** → Converts and extracts text from DOCX, PDF, or TXT  
3. **Job Description Fetching** → Imports current JD from Google Drive  
4. **AI-Powered Analysis** → Recruiter Agent evaluates fit with job requirements  
5. **Information Extraction** → Candidate details (Name, Email, etc.)  
6. **Data Storage** → Results appended to Google Sheets for recruiters  

---

## 📂 Repository Contents
- `Resume_Screening.json` → n8n workflow file  
- `docs/Proposal.pdf` → Project proposal (ATS-specific)  
- `docs/Presentation.pptx` → Slide deck  
- `docs/workflow-diagram.png` → Workflow visualization  
- `docs/example-output.png` → Sample Google Sheet output  

---

## 🚀 Getting Started

### 1️⃣ Prerequisites
- [n8n](https://docs.n8n.io/getting-started/installation/) installed (self-hosted or cloud)  
- Google API credentials (Drive, Gmail, Sheets)  
- OpenAI API key  

### 2️⃣ Import Workflow
1. Clone this repo  
   ```bash
   git clone https://github.com/Raja-Iqbal/Resume-Screening-Agent.git
