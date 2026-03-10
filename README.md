n8n Contact Form → Google Sheets Automation

This project demonstrates a simple yet powerful n8n automation workflow that captures website contact form submissions and automatically stores them in Google Sheets.

This automation is useful for businesses, freelancers, and website owners who want to collect and manage leads efficiently without manual work.

Workflow Overview

The automation works in three simple steps:

1) Webhook Trigger – Receives data from a website contact form.

2) Edit Fields (Set Node) – Formats and organizes the incoming data.

3) Google Sheets Node – Automatically stores the lead information in a Google Sheets spreadsheet.

Workflow Structure

Webhook
   ↓
Edit Fields (Set Node)
   ↓
Google Sheets

Captured Data

The workflow collects and stores the following information:

● Name

● Email

● Message

● Date of Submission

All data is automatically saved into Google Sheets for easy tracking and management.

Use Cases

● This automation is ideal for:

● Website contact forms

● Lead generation systems

● Freelancer inquiry forms

● Business landing pages

● Client request forms

Benefits

● Eliminates manual data entry

● Automatically organizes leads

● Helps teams track inquiries easily

● Saves time and improves workflow efficiency

Technologies Used

● n8n

● Webhook Automation

● Google Sheets Integration

● Workflow Automation

How to Use

1) Import the workflow JSON into n8n

2) Configure your Webhook URL

3) Connect your Google Sheets credentials

4) Create a Google Sheet with columns:

Name | Email | Message | Date

5) Activate the workflow

Now every form submission will automatically appear in your Google Sheet.

Example Request (API)

Example POST request sent to the webhook:

{
  "name": "ABDULLAH AQEEL",
  "email": "abdullahaqeel@email.com",
  "message": "Interested in your services"
}

📄 License

This project is licensed under the MIT License.

👤 Author

Abdullah Aqeel

AI Automation Engineer | Software Quality Assurance Engineer (SQAE)
