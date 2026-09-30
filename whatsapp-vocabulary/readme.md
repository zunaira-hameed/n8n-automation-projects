# WhatsApp Vocabulary Bot

## Problem
Learning new words every day is hard to keep up with.

## Solution
Sends a new vocabulary word with its meaning and an example sentence to the user on WhatsApp [daily / on request].

## Tools Used
n8n, WhatsApp API, [AI model / word list]

## How It Works
1. **Trigger:** [schedule / incoming WhatsApp message]
2. A word and its meaning are generated or picked
3. The message is sent on WhatsApp

## How to Use
1. Import `workflow.json` into n8n
2. Connect your WhatsApp API credentials
3. Test and activate