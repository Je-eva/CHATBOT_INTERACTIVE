# Gemini PDF Chatbot

This project is a **PDF-based conversational AI chatbot** that allows users to interact with their PDF documents using **Google Gemini** AI model. By leveraging **LangChain** and **PyPDF2**, it extracts and processes content from PDF files, stores it in a vector database using **FAISS**, and enables users to ask questions based on the document's contents. The system responds intelligently using the **Google Generative AI** model, integrated via LangChain.

## Features
- Upload and process multiple PDF files.
- Automatically extract and split content from PDFs into manageable chunks.
- Convert the extracted text into vector embeddings using **Google Generative AI Embeddings**.
- Store vector embeddings in a **FAISS** index for efficient similarity search.
- Chat with the bot using natural language, ask questions about the PDF content, and get intelligent answers.
- Streamlit interface for easy interaction with the chatbot.
- Persistent chat history with memory that improves the bot's responses over time.

## Requirements

To run this project locally, you'll need the following dependencies:

- Python 3.7+
- Streamlit
- PyPDF2
- LangChain
- FAISS
- google-generativeai
- langchain_google_genai
- dotenv

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/gemini-pdf-chatbot.git
   cd gemini-pdf-chatbot

