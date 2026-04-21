# Mental Health Automation (n8n Workflow)

This is an AI-powered automation workflow built using n8n.  
It generates a mental health wellness report based on user survey answers and sends it via email.

---

## Features

- Collects user responses through a webhook
- Uses Google Gemini AI to generate a mental health report
- Creates a professional HTML email report
- Sends the report automatically via Gmail
- Uses structured mental health questionnaire data

---

## Workflow Overview

1. User submits mental health survey data
2. Webhook receives the data
3. AI model (Google Gemini) processes responses
4. AI generates a styled HTML wellness report
5. Gmail node sends the report to the user email

---

## Tools Used

- n8n
- Google Gemini AI
- Webhook Trigger
- Gmail API

---

## Use Case

This workflow can be used for:
- Mental health self-assessment tools
- Wellness report generation
- AI-based feedback systems
- Health-tech automation projects

---

## Setup

1. Import workflow into n8n
2. Connect Google Gemini API credentials
3. Set up Gmail OAuth credentials
4. Activate workflow
5. Send survey data via webhook

---
