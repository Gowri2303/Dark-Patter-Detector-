# Dark-Patter-Detector
Dark Pattern Detector on E-Commerce websites
This project is a Streamlit-based web app that analyzes websites for security vulnerabilities and dark patterns.
It’s like a personal website inspector that checks whether a site is safe to use or if it’s trying to trick users with shady UI practices.
**Features**
SQL Injection Check → Detects common SQL injection vulnerabilities with test payloads.

XSS Detection → Looks for Cross-Site Scripting weaknesses using crafted payloads.

Open Port Scanner → Scans common ports (21, 22, 80, 443, etc.) to flag possible risks.

SSL/TLS Check → Verifies certificate validity and outdated protocols.

HTTP Security Analysis → Identifies missing headers like HSTS, CSP, and X-Frame-Options.

Dark Pattern Detector → Uses keyword + HTML checks to spot urgency tactics, fake scarcity, hidden elements, exit-intent popups, countdown timers, etc.

Dynamic Content Analysis → Supports Selenium for analyzing JS-rendered dark patterns.

Safety Score → Generates a score (0–100) based on vulnerabilities and patterns found.

AI-Powered Summary → Uses Hugging Face LLM to summarize the analysis in plain language.
**Tech Stack**
Frontend/UI: Streamlit

Visualization: Plotly (Gauge chart for safety score)

Backend/Checks: Python (requests, BeautifulSoup, socket, ssl, selenium)

AI Summarization: Hugging Face InferenceClient with Mixtral-8x7B-Instruct
