# Lead Capture & Google Sheets Automation

## Problem
Leads from forms get lost or are copied into spreadsheets by hand.

## Solution
Captures new leads from a form or webhook and saves them to Google Sheets automatically. [Optionally sends a confirmation email or notification.]

## Tools Used
n8n, [Webhook / Form Trigger], Google Sheets, [Gmail]

## How It Works
1. **Trigger:** [form submission / webhook]
2. Data is validated and cleaned
3. A new row is added in Google Sheets
4. [A notification or confirmation email is sent]

## How to Use
1. Import `workflow.json` into n8n
2. Connect your Google Sheets credential
3. Set `YOUR_SHEET_ID`
4. Test and activate