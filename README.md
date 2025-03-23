# Skill Tree Generator with LangChain and Generative AI

## Overview

This project is an advanced Retrieval-Augmented Generation (RAG) system designed to create personalized learning paths from PDF documents. By leveraging LangChain for document processing and embedding, and integrating with Google's Generative AI models, the system generates structured skill trees in JSON format, enhancing educational content delivery.

## Features

- **Document Processing**: Load and process PDF documents using LangChain's `PyPDFLoader` and `RecursiveCharacterTextSplitter`.
- **Embedding and Retrieval**: Create vector embeddings with `HuggingFaceEmbeddings` and manage a `Chroma` vector store for efficient document retrieval.
- **Generative AI Integration**: Design structured prompts and integrate with LLMs to generate context-aware learning paths.
- **Evaluation**: Use BERTScore and other metrics to ensure output quality and relevance.
