# 🤖 Project Name: BoundaryConditionsBot

> An end-to-end serverless automation pipeline designed to scout, filter, and tailor job applications for Mechanical, CAE, and Robotics Engineering roles in India, delivering precision-matched opportunities straight to a 2-way Telegram bot.

---

## 📌 Project Overview
Job hunting in specialised engineering fields (such as CAE simulation, NPI, and robotics) often means wading through a high volume of junior-level postings, graduate trainee programs, and senior requirements that don't match your active experience window. 

This project solves that friction by deploying an autonomous, 2-way AI agent that runs 24/7. It scrapes active job portals, passes descriptions through strict first-principles filtering logic using Google Gemini, maps listings to 12 tailored resume lanes, and gives you instant mobile control via Telegram commands to review matches, generate outreach drafts, and pull customized PDF resumes on demand.

---

## 📂 Key Sections
* **Automated Scraping Engine:** Scheduled GitHub Actions running Python-based extraction across Indeed India and RapidAPI Active ATS.
* **Intelligent Filtering & Tailoring Pipeline:** Google Gemini API integration configured with strict negative constraints (automatically discarding internships, GET/trainee roles, and 5+ year senior requirements).
* **2-Way Telegram Bot Interface:** A serverless Cloudflare Worker webhook providing real-time bidirectional communication, resume dispatch, and remote workflow triggers.
* **Specialized Document Matrix:** A structured library of 12 distinct resume variants paired with dynamic HR recruiter and peer networking outreach drafts.

---

## 🖼️ Gallery: End-to-End System Workflow

| **1. Telegram Interactive Command & Job Alert** | **2. Live Telegram Job Match Card** |
| :---: | :---: |
| ![Telegram Chat Response](assets/images/telegram_chat_response.png)[cite: 6] | ![Telegram Job Alert](assets/images/telegram_alert.png)[cite: 3] |
| *Executing `/run` triggers the pipeline and delivers live job cards instantly to mobile.* | *Detailed alert showing required experience, resume lane mapping, X-Ray search links, and AI-tailored outreach notes.* |

| **3. Serverless Cloudflare Worker Webhook** | **4. Automated GitHub Actions CI/CD** |
| :---: | :---: |
| ![Cloudflare Observability](assets/images/Cloudfare_agent_log_telegram_chat.png)[cite: 4] | ![GitHub Workflow Runs](assets/images/Gitub_workflow_requests.png)[cite: 5] |
| *24/7 stateless edge routing handling incoming webhook events with sub-second response times.* | *Scheduled cron triggers and remote webhook dispatches running headless Python scrapers.* |

---

## 💡 Skills Demonstrated
* **Mechanical & CAE Engineering Expertise:** Domain knowledge in NPD/NPI cycles, IP68 enclosure design, structural FEA/CFD simulation, and robotics mechanism design (~3.5 Years of Professional Experience).
* **Simulation Automation:** Developing custom Python and ACT scripting workflows to streamline pre-processing routines (batch meshing, midsurfacing, and solver configuration).
* **Full-Stack & Cloud Architecture:** Building serverless backends with Cloudflare Workers, handling asynchronous webhook routing, and implementing secure API integrations.
* **Prompt Engineering & AI Pipelines:** Designing strict JSON-output prompt structures with Google Gemini for automated resume alignment and experience classification.
* **CI/CD & DevOps:** Orchestrating automated workflows using GitHub Actions, repository secrets management, and custom webhook dispatches (`workflow_dispatch`).

---

## 🧰 Tools Used

| Category | Tools & Technologies |
| :--- | :--- |
| **Languages & Core** | Python, Pandas, JavaScript / Node.js |
| **AI & NLP** | Google Gemini API (`gemini-2.5-flash`, `gemini-3.5-flash-lite`) |
| **Cloud & Serverless** | Cloudflare Workers, Serverless Webhooks |
| **CI/CD & Automation** | GitHub Actions (Cron Schedulers, Workflow Dispatches) |
| **Interfaces & APIs** | Telegram Bot API, JobSpy, RapidAPI Active ATS |
| **Engineering Domain** | ANSYS Mechanical/Fluent, SolidWorks, MATLAB (Simscape) |

---

## 📊 Results & Impact
* **Elimination of Noise:** Successfully filters out >80% of irrelevant postings (internships, freshers, and senior roles), locking strictly into the mid-level engineer sweet spot.
* **Zero-Login Sourcing:** Generates automated Google X-Ray search queries that allow instant identification of engineering peers, managers, and recruiters at target companies without requiring an active LinkedIn session.
* **Instantaneous Retrieval:** Reduces resume retrieval and job review time from minutes of manual searching to sub-second mobile notifications via Telegram.

---
