# Automated-Job-Search-Cover-Letter-Generator-with-Match-Scoring-n8n-Gemini-
📌 Project Description

This project automates the job search and application process using n8n and Gemini AI. It fetches job postings from RSS feeds or APIs, evaluates their relevance against a candidate’s resume with a match score, generates a personalized cover letter, stores the results in Google Sheets, and sends a daily email summary of top job opportunities.

✨ Features

Job Fetching – Pull latest job postings from RSS feeds or external APIs.

Match Scoring – Compare job descriptions with the candidate’s resume to generate relevance scores (1–10).

Cover Letter Generation – Create tailored cover letters for each job using Gemini AI.

Google Sheets Integration – Save structured job data (title, description, link, score, cover letter) into a Google Sheet.

Email Notifications – Send a daily summary email with top N job matches, including title, company, location, score, and link.


🔹 Run with n8n

Install n8n (via Docker or npm).

Import the provided workflow JSON.

Configure credentials:

RSS/Job API for job fetching

FastAPI/Gemini for AI calls

Google Sheets for storage

Gmail/SMTP for email sending

Schedule the workflow (e.g., run daily at 9 AM).

Enjoy automated job updates in your inbox + Google Sheet.


<img width="1678" height="704" alt="image" src="https://github.com/user-attachments/assets/5a84602f-4c6b-4bcf-a73c-fff4ec732844" />

<img width="1971" height="952" alt="image" src="https://github.com/user-attachments/assets/b3acb092-674b-45d6-9f1e-7ea99b0b145c" />

<img width="1619" height="647" alt="image" src="https://github.com/user-attachments/assets/30633354-54d2-4a6b-8ab2-03d2750dc491" />

