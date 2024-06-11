# Codebasics Q&A with LangChain and GooglePalm

## Overview

This project implements a Question and Answer (Q&A) system using the LangChain framework with GooglePalm for language model queries and FAISS for vector storage. The data for the Q&A system is sourced from a CSV file containing prompts, which are used to create embeddings stored in a FAISS vector store. Users can query this system to get relevant responses based on the provided data.

## Project Implementation

### LangChain and GooglePalm Integration

LangChain is a framework for developing applications powered by language models. In this project, LangChain is used to handle the embedding and vector storage processes.

- **HuggingFaceInstructEmbeddings**: This component is used to create vector embeddings from text data.
- **FAISS**: Facebook AI Similarity Search (FAISS) is a library for efficient similarity search and clustering of dense vectors. Here, FAISS is used to store and retrieve vector embeddings.
- **GooglePalm**: GooglePalm is used as the language model to process and answer queries based on the stored vector embeddings.

## Setup Instructions

### Prerequisites

- Python 3.7 or higher
- Google API Key for GooglePalm

    
