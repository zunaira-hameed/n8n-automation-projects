# Gmail Classifier

## Problem
Inboxes fill up with mixed emails and important ones get missed.

## Solution
Reads new emails and uses AI to classify them into categories ([e.g. Support, Sales, Spam]). Labels are applied [and/or alerts are sent] automatically.

## Tools Used
n8n, Gmail, [OpenAI / other AI model]

## How It Works
1. **Trigger:** new email arrives in Gmail
2. AI reads the subject and body and picks a category
3. A Gmail label is applied [and/or another action is taken]

## How to Use
1. Import `workflow.json` into n8n
2. Connect Gmail and your AI credential
3. Adjust the categories to your needs
4. Test and activate