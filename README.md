### LangChain Basics – RAG Pipeline with PDF

This project demonstrates the fundamental workflow of building a Retrieval-Augmented Generation (RAG) pipeline using LangChain.

The system loads a PDF document, splits it into smaller chunks, generates embeddings, stores them in a vector database, retrieves relevant information, and answers questions based on the retrieved context.


### Project Overview

The goal of this project is to understand the core components of LangChain and how they work together to build an intelligent document question-answering system.

The pipeline implemented in this project:

PDF → Document Loader → Text Splitter → Embeddings → Vector Store → Retriever → LLM → Answer


### Technologies Used

Python
LangChain
FAISS (Vector Database)
HuggingFace Embeddings
PyPDFLoader

### Project Workflow :-

    1. Load PDF Document
    2. Split Documents into Chunks
    3. Generate Text Embeddings
    4. Create Vector Store (FAISS)
    5. Build the Retriever
    6. Define the Prompt Template
    7. Create the Document Chain
    8. Create the Retrieval Chain
    9. Ask Questions from the Document


### Key Concepts 

Document loading with PyPDFLoader
Text chunking using RecursiveCharacterTextSplitter
Generating embeddings using HuggingFace models
Storing vectors using FAISS
Building a retriever for semantic search
Creating prompt templates
Implementing a Retrieval-Augmented Generation (RAG) pipeline


### Applications

This architecture can be used for:

    Document question answering
    Knowledge base assistants
    AI-powered search systems
    Chatbots for PDFs or company documents