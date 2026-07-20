🤖 AI-Powered Job Search Automation using n8n

An AI-powered workflow built with **n8n**, **Google Gemini AI**, **Adzuna API**, **JavaScript**, and **Gmail** that automatically searches for jobs, filters relevant opportunities, removes duplicates, scores them using AI, exports the results to Excel, and sends a daily email report.

---

🚀 Features

- 🔍 Automatically searches for Data Analyst jobs using the Adzuna API
- 🤖 Uses Google Gemini AI to filter relevant jobs
- 🧹 Removes duplicate job listings
- ⭐ AI-powered job scoring and prioritization
- 📊 Generates an Excel report automatically
- 📧 Sends a daily email report using Gmail
- ⏰ Scheduled to run automatically every day
- 💻 Built completely using n8n with JavaScript

---

🏗️ Architecture

```text
Schedule Trigger
       │
       ▼
Adzuna API
       │
       ▼
Extract Job Details
       │
       ▼
Gemini AI Filter
       │
       ▼
Parse JSON
       │
       ▼
Split Jobs
       ├──────────────► Excel Report
       │                     │
       │                     ▼
       │              Save to Local Folder
       │
       ▼
Combine Jobs
       │
       ▼
Duplicate Removal
       │
       ▼
AI Career Advisor
       │
       ▼
Gmail
       │
       ▼
Daily AI Job Report
```

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow Automation |
| JavaScript | Data Processing |
| Google Gemini AI | Job Filtering & AI Analysis |
| Adzuna API | Job Search API |
| Gmail API | Email Notifications |
| Excel (.xlsx) | Report Generation |

---

# 📂 Workflow

The workflow performs the following steps:

1. Runs automatically every day.
2. Fetches the latest job listings from Adzuna.
3. Extracts useful job information.
4. Uses Google Gemini AI to filter relevant jobs.
5. Converts AI output into JSON.
6. Splits job listings.
7. Generates an Excel report.
8. Saves the report locally.
9. Combines all jobs into a single dataset.
10. Removes duplicate jobs.
11. Uses an AI Agent to score and rank jobs.
12. Sends a daily email report.

---

📸 Screenshots

## Workflow

<img width="1907" height="908" alt="Workflow png" src="https://github.com/user-attachments/assets/44cff03c-1bf6-4078-b438-fadb440defff" />


---

## Mail Report

<img width="1517" height="788" alt="Mail_Output png" src="https://github.com/user-attachments/assets/e9f8d676-283d-4c0f-b00f-da592fb7212a" />


---


# 📌 Configuration

Replace the following placeholders with your own values:

- YOUR_GEMINI_API_KEY
- YOUR_ADZUNA_APP_ID
- YOUR_ADZUNA_API_KEY


---

📈 Future Improvements

- HTML Email Reports
- Google Sheets Integration
- Resume Matching
- Company Insights
- Interview Difficulty Prediction
- Salary Estimation
- Dashboard using Power BI
- LinkedIn Job Integration
- Remote Job Filtering
- Multi-country Job Search

---

🤝 Contributing

Contributions, feature requests, and suggestions are welcome.

If you find any issues or have ideas for improvement, feel free to open an Issue or Pull Request.

---

📄 License

This project is licensed under the MIT License.

---

👨‍💻 Author

Mohan Krishan

📧 Email: mohan1708004@gmail.com

🔗 LinkedIn: *(https://www.linkedin.com/in/mohan-krishna-r/)*

🐙 GitHub: *(https://github.com/moha-n-ctr)*

---

⭐ If you found this project helpful, consider giving this repository a star!
