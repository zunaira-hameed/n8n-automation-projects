# RAG Chatbot

## Problem
Generic chatbots don't know your own documents, so they give vague or wrong answers.

## Solution
A chatbot that answers questions using your own documents (Retrieval-Augmented Generation). Documents are stored in a vector database and the most relevant parts are given to the AI before it replies.

## Tools Used
n8n, [OpenAI / other AI model], [Pinecone / Supabase / in-memory vector store], text embeddings

## How It Works
1. **Ingestion:** documents are split into chunks and embedded into the vector store
2. **Trigger:** [chat message / webhook]
3. The most relevant chunks are retrieved for the question
4. AI generates an answer based on those chunks

## How to Use
1. Import `workflow.json` into n8n
2. Add your AI and vector store credentials
3. Upload your documents through the ingestion flow
4. Start chatting