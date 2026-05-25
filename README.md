Lead Capture Automation System

Overview
A complete automation system that captures form submissions, stores data in Google Sheets, and sends instant email notifications. Built in 3 days as part of my automation learning journey.

How It Works
1. User submits a Google Form
2. Google Apps Script sends data to n8n webhook
3. n8n processes and transforms the data
4. Data is appended to Google Sheets
5. Admin receives email notification

Tools Used
- Google Forms (data collection)
- Google Apps Script (webhook integration)
- n8n (workflow automation)
- Google Sheets (data storage)
- Gmail API (email notifications)

 Live Demo
https://docs.google.com/forms/d/e/1FAIpQLSc_mBBxDDk2o0J2UeJuMEvla8RF8ru6W7ZYePVX8ZSblpezmg/viewform

Screenshots
Workflow in n8n
Google Sheet with Data
Email Notification

What I Learned
- Connecting Google Forms to external webhooks using Apps Script
- Transforming data fields in n8n using "Set" nodes
- Handling field name mismatches between forms and databases
- Sending automated emails via Gmail API

Time to Build
3 days (approx 12 hours of focused work)

## Future Improvements
- Add user confirmation email
- Add Slack notifications
- Add error handling for failed submissions
