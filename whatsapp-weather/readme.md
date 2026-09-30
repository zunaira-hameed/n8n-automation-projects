# WhatsApp Weather Bot

## Problem
Checking the weather means opening a separate app.

## Solution
The user sends a city name on WhatsApp and gets the current weather back in the same chat.

## Tools Used
n8n, WhatsApp API, [weather API name]

## How It Works
1. **Trigger:** incoming WhatsApp message
2. The city name is extracted
3. The weather API is called
4. A reply is sent on WhatsApp

## How to Use
1. Import `workflow.json` into n8n
2. Add your WhatsApp and weather API credentials
3. Test and activate