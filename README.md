# hdb-rag-chatbot

Low-Fidelity RAG Chatbot for HDB FAQs using DeepSeek-R1, LangChain, ChromaDB, and Ollama

# 🏠 RAG Chatbot for HDB FAQs

This is a simple local RAG (Retrieval-Augmented Generation) chatbot built using:

- 💬 **LangChain** for document chunking and retrieval
- 🧠 **DeepSeek-R1 7B** via **Ollama** for response generation
- 📚 **ChromaDB** for vector storage
- 🎛 **Gradio** for the interface
- 📄 Knowledge base: FAQs from [HDB Singapore](https://homes.hdb.gov.sg/home/frequently-asked-questions)

## 🔧 Setup Instructions

1. Clone this repo or download it
2. Create and activate a Python virtual environment
3. Install dependencies:

- Run `pip install requirements.txt`

4. Install and run Ollama:

- Install from here: [https://ollama.com](https://ollama.com)
- Run `ollama run deepseek-r1`

5. Launch the notebook and run all cells.

## 🧪 Demo

Ask questions like:

- “How can I list my flat for sale?”
- “Do I need an agent to manage my listing?”
