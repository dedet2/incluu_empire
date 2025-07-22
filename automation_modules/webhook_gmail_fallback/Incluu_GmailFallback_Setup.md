# Incluu Gmail Fallback Setup (Manual + DFY Ready)

## Modules
1. Gmail > Watch Emails
   - Filter: Unread only
   - Criteria: *@epodia.com

2. Airtable > Create Record
   - Table: Sales (example)
   - Map: Sender, Subject, Body, Date

3. Slack > Send Message
   - Channel: #sales-alerts
   - Message: 🚨 New Podia Sale!
From: {{sender}}
Subject: {{subject}}
Date: {{date}}

## Trigger Flow
1. Send a test email from Podia to your connected Gmail
2. Run scenario once
3. Verify Slack + Airtable updated

---
**Support contact:** ai@incluu.us