# Smart Article Generator

## Problem
Writing long articles from scratch takes hours.

## Solution
Turns a topic into a complete article using AI: an outline first, then the full content, [then saves it to Google Docs / Sheets / WordPress].

## Tools Used
n8n, [AI model], [Google Docs / WordPress]

## How It Works
1. **Trigger:** [topic input]
2. AI creates an outline
3. AI writes the article section by section
4. The final article is [saved / published]

## How to Use
1. Import `workflow.json` into n8n
2. Add your credentials
3. Enter a topic and run the workflow