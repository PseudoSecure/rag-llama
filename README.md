# rag-llama

## Ollama Installation

Download Ollama.zip

Unzip Ollama.zip -> Ollama.app

Double Click to install as it automatically adds to the application folder - requires sudo access

run following to pull llama3.2
ollama pull llama3.2:3b

pull nomic-embed-text
ollama pull nomic-embed-text

Install dependencies


we used poetry to install dependencies

only thing that was failing for sentence-transformers due to issues with pytorch / poetry

https://youtu.be/1y2TohQdNbo?si=sEynkmffkneYTGUP&t=845