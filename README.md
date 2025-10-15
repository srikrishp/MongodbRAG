# MongodbRAG
# Offline RAG Pipeline Demo
# Overview

This repository demonstrates a Retrieval-Augmented Generation (RAG) pipeline that runs completely offline, without connecting to any external databases or APIs. The project simulates document embeddings, similarity search, and metadata filtering, providing a self-contained example for learning and experimentation.

# The pipeline includes:

Splitting documents into smaller chunks

Generating mock embeddings

Cosine similarity-based retrieval

Metadata filtering (e.g., ignoring code snippets)

Visualization of query similarity scores

This project is ideal for learning RAG concepts or showcasing a demo without external dependencies.

Features

Document chunking with configurable chunk size and overlap

Offline embedding generation for testing

Cosine similarity-based top-k retrieval

Metadata filtering to exclude certain document types

Visualization of similarity scores using heatmaps

Fully self-contained; no external API or database required

Getting Started
Prerequisites

Python 3.8 or higher

# Libraries:

pip install numpy matplotlib seaborn langchain

# Usage

Clone the repository:

git clone https://github.com/your-username/offline-rag-demo.git
cd offline-rag-demo


# Open the Jupyter notebook or run the Python script:

jupyter notebook Offline_RAG_Demo.ipynb
# OR
python Offline_RAG_Demo.py


Run the notebook or script to see:

Document splitting

Embedding generation

Top-k document retrieval for queries

Similarity heatmap visualization

Example Output
Query: What is a MongoDB collection?
Top 3 results:
- Collections store multiple documents in MongoDB. (score: 0.872)
- MongoDB is a NoSQL database. (score: 0.791)
- LangChain enables RAG pipelines and vector memory. (score: 0.764)


Heatmaps display similarity scores for retrieved chunks.

# Project Structure
offline-rag-demo/
├── Offline_RAG_Demo.ipynb      # Jupyter notebook with full pipeline
├── Offline_RAG_Demo.py         # Python script version (optional)
├── README.md                   # Project documentation
└── requirements.txt            # Required Python libraries

# Learning Goals

Understand RAG (Retrieval-Augmented Generation) workflow

Learn document chunking and embedding-based search

Practice metadata-based filtering

Visualize similarity scores for queries
