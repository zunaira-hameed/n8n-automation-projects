# Invoice Parser

## Problem
Manually copying data from invoices into spreadsheets is slow and error-prone.

## Solution
This workflow reads incoming invoices, extracts key fields with AI (vendor, invoice number, date, amount, [other fields]) and saves them to Google Sheets automatically.

## Tools Used
n8n, [OpenAI / other AI model], Google Sheets, [Gmail / Google Drive]

## How It Works
1. **Trigger:** [new email with PDF / file uploaded to Drive]
2. Extract text from the invoice
3. AI extracts structured data
4. Data is appended as a new row in Google Sheets

## Screenshot
![Workflow](./screenshot.png)

## How to Use
Import `workflow.json` into n8n, add your own credentials and replace the placeholders (`YOUR_SHEET_ID`, etc.).
