# Voice Agent

## Problem
Many users prefer speaking over typing, and support teams cannot answer every call.

## Solution
An AI agent that receives voice input, understands it and replies [with voice / text]. [It can also perform actions such as ...]

## Tools Used
n8n, [OpenAI / other AI model], [speech-to-text and text-to-speech service], [Webhook]

## How It Works
1. **Trigger:** [incoming call / audio sent to a webhook]
2. Speech is converted to text
3. The AI agent decides the response
4. The response is converted to speech and returned

## How to Use
1. Import `workflow.json` into n8n
2. Add your AI and voice service credentials
3. Set your webhook URL
4. Test and activate