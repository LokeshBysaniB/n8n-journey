# Send Weekly Email Workflow

## Purpose
This workflow sends an automated email every Monday morning with a weekly summary.

## Trigger
- Cron: Runs every Monday at 9:00 AM

## Nodes Used
- HTTP Request: Fetches weekly data
- Function: Formats the summary message
- Email: Sends the final email to a configured address

## How to Use
1. Import `send-weekly-email.json` into your n8n instance.
2. Replace the URL in the HTTP node with your data source.
3. Set up the email credentials in the Email node.
4. Enable the workflow.

## Screenshot
![Workflow Screenshot](./screenshot.png)
