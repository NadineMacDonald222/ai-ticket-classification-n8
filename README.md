# AI-Powered IT Ticket Workflow (n8n)

This n8n workflow automates IT ticket classification and routing.

## Workflow Structure

Webhook → HTTP Request → Code → Merge → Switch → Google Sheets → Webhook Response

### Features
- Classifies support tickets as CRITICAL, HIGH, or LOW
- Routes tickets based on urgency
- Logs tickets to Google Sheets
- Fully automated using n8n

## Setup Instructions

1. **Clone the repo**
```bash
git clone https://github.com/YOUR_USERNAME/n8n-ai-ticket-workflow.git
cd n8n-ai-ticket-workflow
