Sales-Opportunity-AI-Analysis
AI-Powered Analysis of US Finance Companies & Service Opportunities

📌 Overview
This project focuses on analyzing a dataset of US company opportunities to identify which companies are most likely to need specific services such as Fraud Detection, Risk Modeling, and Compliance Automation. Additionally, it evaluates which of these services OurCompanyX can provide based on historical wins. The workflow involves data loading, cleaning, descriptive statistics, and leveraging AI (via Groq API) to generate actionable insights for business development.

📂 Dataset Source
Internal company dataset (includes past sales opportunities and outcomes).

Content: The dataset includes details such as company name, domain, service type, opportunity type (inbound/outbound), result (win/loss), and reason for outcome.

Size: ~100+ rows (expandable as per internal records), with 6 features.

🛠️ Tools & Libraries

Python (Jupyter Notebook / Colab)

Pandas, NumPy

Matplotlib, Seaborn (for visualizations)

Requests (for API calls to AI)

Git & GitHub

🔄 Project Workflow

Data Loading and Exploration

Loaded the dataset and explored structure, types, and sample records.

Checked for unique services and company distribution.

Data Cleaning & Preparation

Handled missing or inconsistent entries.

Identified services with higher win rates to define company strengths.

Descriptive Statistics & Insights

Calculated win/loss ratios by service and domain.

Identified services OurCompanyX is strongest at based on historical wins.

AI-Powered Opportunity Analysis

Developed Python scripts to interact with Groq AI API.

Prompted AI to generate lists of US finance companies likely to need key services.

Integrated dataset insights so that AI highlights which opportunities OurCompanyX can realistically pursue.

Output Format
Generated actionable output as:
Company Name – Needed Service(s) – Can OurCompanyX Provide? (Yes/No) – Reason

📈 Key Insights

AI successfully filtered companies by potential service needs.

OurCompanyX’s strong service areas (from historical wins) were highlighted.

Provides a prioritized list for sales outreach and business development.

📌 Future Improvements

Automate updates from live CRM datasets.

Include predictive scoring for potential win probability per company.

Extend to other domains like Healthcare, Retail, etc.

Deploy as a web dashboard for sales teams.

👤 Author
Sreevatsun Janarthanaam
Master of Science in Scientific Instrumentation, Ernst-Abbe-Hochschule Jena, Germany
📧 sreevatsunj@gmail.com
