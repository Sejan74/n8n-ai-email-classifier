# n8n-ai-email-classifier
# AI-Powered Automated Email Classifier using n8n

## Project Overview
This project features an automated workflow built in **n8n** that processes incoming emails, analyzes their content using an AI model, and classifies them into specific categories (e.g., Priority, Support Inquiry, Feedback, or Spam). The system helps streamline inbox management by automating response routing and tagging.

## Tools & Technologies Used
- **n8n** (Workflow Automation Platform)
- **IMAP / Gmail Node** (Email Trigger & Retrieval)
- **OpenAI / AI Node** (Content Analysis & Classification)
- **Slack / Gmail Node** (Automated Notification or Response)

## Core Features
- **Automated Monitoring:** Continuously listens for incoming emails in real-time.
- **Smart Text Classification:** Leverages LLMs to categorize emails based on intent and sentiment.
- **Conditional Routing:** Automatically routes urgent emails to high-priority channels and archives low-value threads.

## Workflow Preview
![Email Classifier Workflow](https://github.com/Sejan74/n8n-ai-email-classifier/blob/main/Screenshot%202026-10-10%20012125.png?raw=true)

## How to Import & Use
1. Download the `.json` workflow file from this repository.
2. Open your n8n instance, click on **Add Workflow**, and select **Import from File**.
3. Connect your email credentials (IMAP/Gmail) and AI API credentials (OpenAI/Anthropic) to the respective nodes.
4. Activate the workflow to start automated email classification.
