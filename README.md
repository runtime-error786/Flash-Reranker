# LangChain Document Retrieval and QA System

This project demonstrates a document retrieval and question-answering system using LangChain. It integrates document loading, text splitting, embeddings, vector storage, and QA retrieval with advanced LLMs. This setup utilizes pre-built components from LangChain and other libraries for a streamlined information retrieval and response system.

## Features

- **Document Loading**: Loads PDF documents and extracts text.
- **Text Splitting**: Splits large documents into manageable chunks.
- **Embedding**: Converts text chunks into vector embeddings.
- **Vector Storage**: Stores and retrieves vector embeddings using Chroma.
- **Contextual Compression Retrieval**: Uses `FlashrankRerank` for document reranking.
- **QA System**: Uses `RetrievalQA` for generating answers from documents.
