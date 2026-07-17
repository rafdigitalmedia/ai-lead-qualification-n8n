# 🎯 AI-Powered Lead Qualification System

[![n8n](https://img.shields.io/badge/n8n-Automation-FF6D5A?style=flat-square)](https://n8n.io)
[![Google AI](https://img.shields.io/badge/Google_Gemini_AI-4285F4?style=flat-square)](https://ai.google.dev)

> An intelligent automation that analyzes, scores, and routes leads using AI — reducing manual qualification time by 90%.

## 🎬 See It In Action

![Workflow Demo](workflow.gif)

## ✨ Features

- 🤖 **AI-Powered Lead Scoring** — Analyzes budget, urgency, and requirements (0-100 score)
- 💰 **Smart Budget Extraction** — Custom JavaScript parses budget from unstructured text
- 🔥 **Hot Leads** (≥$10k): Instant email alerts to sales team
- ️ **Warm Leads** ($5k-$9k): Logged for nurturing campaigns
- ❄️ **Cold Leads** (<$5k): Archived for future retargeting
- ⚡ **Real-time Processing** — Under 60 seconds from lead capture to notification

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **n8n** | Workflow automation engine |
| **Google Gemini AI** | Lead analysis and scoring |
| **JavaScript** | Custom data processing and budget extraction |
| **Google Sheets** | Lead data storage |
| **Gmail** | Automated email notifications |

##  Business Impact

| Metric | Before | After |
|--------|--------|-------|
| Lead qualification time | 2-4 hours | < 60 seconds |
| Response time to hot leads | 4-24 hours | < 2 minutes |
| Missed high-value leads | 30-40% | ~0% |
| Manual hours/week | 10-15 hours | < 1 hour |

## 🚀 How It Works

Google Sheets (New Lead)
↓
Google Gemini AI (Analysis + Scoring)
↓
JavaScript (Budget Extraction & Formatting)
↓
IF Router (Hot/Warm/Cold Logic)
↓
Gmail (Instant Alert for Hot Leads)


## 📸 Screenshots

### Full Workflow
![Full Workflow](screenshots/1-full-workflow.jpg)

### AI Analysis & Prompt
![AI Analysis](screenshots/2-ai-expression.jpg)

### Data Processing Code
![Code Node](screenshots/3-code-node.jpg)

### Smart Routing Logic
![Router](screenshots/4-if-router.jpg)

### Email Result
![Email Result](screenshots/5-email-result.jpg)

### Single Email View
![Single Email](screenshots/6-single-email.jpg)

### Multiple Leads Inbox
![Multiple Leads](screenshots/7-inbox-multiple.jpg)

## 📦 Installation

1. Import `AI Lead Qualification.json` to your n8n instance
2. Configure Google Sheets credentials
3. Set up Google Gemini API key
4. Configure Gmail credentials
5. Activate workflow and test!

## 💼 Use Cases

- 🏢 **Marketing Agencies** — Qualify ad leads instantly
- 💼 **B2B Sales Teams** — Prioritize high-value inquiries
- 🛒 **E-commerce** — Filter high-value customers
- 🏡 **Real Estate** — Identify serious buyers
- 💻 **SaaS Companies** — Score trial signups

## 📝 License

MIT License — free to use and modify for personal or commercial projects.

---

**Built with ❤️ using n8n and Google AI**

*For inquiries or custom automation projects, feel free to reach out!*
