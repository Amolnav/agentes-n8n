docker run -d -v ollama:/root/.ollama --name ollama-n8n --network red-n8n-ollama -p 11500:11434 --gpus=all ollama/ollama:latest
