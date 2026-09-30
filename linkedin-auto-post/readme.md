# LinkedIn Auto Post

## Problem
Posting consistently on LinkedIn takes a lot of time.

## Solution
Generates LinkedIn posts with AI from [a topic / Google Sheet / schedule] and publishes them automatically.

## Tools Used
n8n, [OpenAI / other AI model], LinkedIn, [Google Sheets]

## How It Works
1. **Trigger:** [schedule / new row in a sheet]
2. AI writes the post
3. The post is published on LinkedIn

## How to Use
1. Import `workflow.json` into n8n
2. Connect LinkedIn and your AI credential
3. Set your topic source
4. Test and activate