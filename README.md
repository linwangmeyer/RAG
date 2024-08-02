# Preparation
1. Make sure Llama is running as a server: in the terminal, type: Ollama serve
2. Use existing embedding models: "mxbai-embed-large" from OllamaEmbeddings
(Note: couldn't get BedrockEmbeddings work from AWS)
3. Make sure running scripts in the correct virtual environment

# Steps
1.  To reset/add new PDF files, type in terminal: python populate_database.py --reset
2. To run the model, type in terminal: python query_data.py "What is positive thought disorder?"