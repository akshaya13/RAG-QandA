# RAG Document Q&A with Groq and Llama3

This project is a Streamlit-based Q&A application that utilizes Retrieval-Augmented Generation (RAG) to answer questions from a collection of research papers. It combines Groq's Llama3 model for language understanding with FAISS for efficient vector search.

## Features

- **Document Ingestion**: Automatically loads and processes research papers in PDF format.
- **Embeddings Creation**: Uses Ollama embeddings to create vector representations of document chunks.
- **Vector Search**: Uses FAISS to perform similarity search and retrieve relevant document chunks based on user queries.
- **Q&A with Groq's Llama3**: Leverages the power of Groq's Llama3 model to generate answers based on retrieved context.
- **Streamlit UI**: Simple and interactive user interface for entering queries and viewing results.

## Prerequisites

- Python 3.8+
- A Groq API key for using the Llama3 model.
- Libraries: `streamlit`, `langchain`, `langchain_community`, `faiss`, `dotenv`
- Install all required libraries using the `requirements.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

Acknowledgments
* LangChain for document processing and chaining.
* FAISS for vector search.
* Streamlit for creating a user-friendly interface.
* Groq API for their advanced language models.