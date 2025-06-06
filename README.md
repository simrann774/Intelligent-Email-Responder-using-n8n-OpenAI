Email responder AI built with n8n and OpenAI GPT-4o

An AI-powered workflow that automatically responds to emails based on their category using n8n, Gmail API, and GPT-4o-mini (OpenAI).

🔧 Project Overview

This n8n workflow automates professional email responses by:

Listening for new Gmail messages

Classifying the email content (e.g., job updates or low-priority messages)

Generating tailored responses using OpenAI

Saving replies as Gmail drafts for manual review or automated sending

🚀 Features

🕒 Hourly Gmail Trigger to detect incoming messages

🧠 LangChain Text Classifier to label emails as job_update or low_priority

🤖 OpenAI GPT-4o-mini Integration for generating smart, structured replies

✉️ Gmail Draft Creation with subject and body separated clearly

🔄 Easy to extend for new categories or full automation

📂 Files Included

EMAIL_RESPONDER.json: The n8n workflow export file

⚙️ How to Use This Workflow

1. Import the Workflow in n8n

Log into your n8n instance

Go to Workflows > Import and upload EMAIL_RESPONDER.json

2. Set Up Credentials

Add your Gmail OAuth2 credentials

Add your OpenAI API key for GPT-4o-mini

Attach these credentials to their respective nodes in the workflow

3. Activate the Workflow

Enable the workflow to start checking your inbox every hour

Or trigger manually for testing

4. Check Gmail Drafts

When a new email is detected and classified, a reply will be generated and saved as a draft in Gmail

You can edit and send it manually, or extend the workflow to auto-send

🧪 Example Use Cases

Replying to job application updates from recruiters

Responding to newsletters or non-urgent emails

Drafting courteous replies without manual effort

🛠 Customization Ideas

Add more categories (e.g., sales inquiry, support request)

Route different categories to different workflows

Auto-send emails instead of saving as drafts

 Requirements

n8n (Self-hosted or Cloud)

Gmail API access

OpenAI API key
