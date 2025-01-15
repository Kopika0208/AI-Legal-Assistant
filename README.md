# AI-Legal-Assistant
AI assistant to help with legal queries, with a RAG model trained on the Indian Penal Code, real case documents, to provide accurate, in-depth, and effective solutions for court cases and lawsuits. With built-in legal document generator and judgment prediction models, this tool shows the potential of AI and deep learning in the legal atmosphere.

## Key Features
✅ IPC-verified Answers: Provides context-aware responses by referencing the prompt according to the Indian Penal Code.
📜 Legal Doc Generator: Generates legal documents from a single prompt, in a ready-to-use Word .docx format.
🔍 Judgment Prediction: Uses a high-level Bi-GRU neural network model, trained on cases from 1947 to 2020, to accurately predict a court verdict.
🧩 Interactive Console: Simple and interactive user interface powered by Streamlit for ease of use.

## Technologies Used
🤖 Mistral AI's Mixtral-8x22B-Instruct-v0.1 for natural language understanding and response generation.
⚙️ InLegalBERT for Indian Penal Code text embeddings.
🧩 Streamlit for the front-end interface.
📅 Redis for quick, indexed access to knowledge base entries.
🐍 Python for core application logic.

Deployed at: https://ailegalassistant.streamlit.app/
