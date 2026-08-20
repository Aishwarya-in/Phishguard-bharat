PhishGuard Bhasha 🛡️
Regional-Language Phishing Detection

Submitted for Omnikon National Hackathon 2026 | Problem ID: Omni_CyberTech_1 | Domain: Cybersecurity, Blockchain & Digital Trust

📄 Submission Document
The full project submission (problem understanding, architecture, tech stack, and implementation plan) is available here:

Problem
Phishing attacks increasingly target non-tech-savvy users through SMS, WhatsApp, and email messages written in regional Indian languages (Hindi, Bengali, Tamil, Telugu, Marathi, etc.), often mixed with English ("Hinglish"). Existing phishing detection tools are trained almost exclusively on English content, leaving first-time internet users, elderly users, and residents of smaller towns vulnerable — precisely because no existing tool warns them in a language they understand.

Solution
PhishGuard Bhasha is a web-based tool that detects phishing content — SMS text, WhatsApp-style messages, and URLs — written in regional Indian languages or code-mixed text, and warns users in real time with a Safe / Suspicious / Phishing verdict and a plain-language explanation in their own language.

Tech Stack
Layer	Technology
Frontend	React + Tailwind CSS
Backend / API	Python (FastAPI)
Language Detection	fastText / langdetect
Phishing Classification	Fine-tuned multilingual transformer (MuRIL / IndicBERT / XLM-RoBERTa)
URL Heuristics	Domain-reputation checks, Levenshtein-distance brand matching, Google Safe Browsing / PhishTank APIs
Hosting	Vercel / Render
Timeline
Phase	Dates
Research & Data Collection	Aug 19–21
Model & Backend Development	Aug 22–25
Frontend & Integration	Aug 26–29
Testing & Refinement	Aug 30–Sep 1
