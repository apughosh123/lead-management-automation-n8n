# Lead Management Automation using n8n

An automated Lead Management System built with **Lovable, n8n, Google Sheets, and Gmail**.

This project automates lead collection, data storage, personalized email notifications, and email delivery status tracking.

## Project Overview

The system allows potential clients to submit their information through a website contact form. Once submitted, n8n automatically processes the lead, stores the information in Google Sheets, and sends a personalized confirmation email.

## Technologies Used

- **Lovable** – Website and lead submission form
- **n8n** – Workflow automation
- **Google Sheets** – Lead data management
- **Gmail** – Automated email notifications
- **Webhook** – Website-to-n8n integration

## Key Features

- Lead submission through a website form
- Automatic lead data collection using n8n Webhook
- Google Sheets integration for storing lead information
- Personalized automated confirmation emails
- Automatic email status tracking
- Successful email status: `Sent`
- Failed email status: `Failed`
- Email sending timestamp and error tracking

## Workflow Process

1. A visitor submits the lead form on the website.
2. The n8n Webhook receives the submitted information.
3. Lead information is stored in Google Sheets with an initial `Pending` status.
4. Gmail sends a personalized confirmation email.
5. If successful, the Google Sheets status updates to `Sent`.
6. If unsuccessful, the status updates to `Failed` and records the error.

## Lead Form Fields

- Name
- Email
- Company Name
- Interested Service
- Message

## Google Sheets Data

The system tracks:

- Lead ID
- Submission Date
- Name
- Email
- Company Name
- Interested Service
- Message
- Email Status
- Email Sent Time
- Email Error

## Project Links

**Live Website:** https://screenshot-to-scenery-335.lovable.app/

**GitHub Repository:** https://github.com/apughosh123/lead-management-automation-n8n

## Workflow Import Instructions

1. Download the workflow JSON file from this repository.
2. Open your n8n instance.
3. Select **Import from File**.
4. Import the workflow JSON.
5. Configure your Google Sheets and Gmail credentials.
6. Update the Google Sheets document ID and connect the Webhook to your website.
7. Test the workflow.

## Author

**Apu Ghosh**

AI Automation | n8n Workflows | AI Agents | API Integrations

- GitHub: https://github.com/apughosh123
- LinkedIn: https://www.linkedin.com/in/apu-ghosh-automation/

---

*This project was developed as an automation assignment to demonstrate practical workflow automation and lead management using n8n.*
