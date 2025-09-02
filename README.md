# KG-RAG-using-Cohere-API-Neo4j-And-Lllamaindex
This project implements a Knowledge Graph-powered Retrieval-Augmented Generation (RAG) pipeline using LlamaIndex, Cohere API, and Neo4j.
It allows you to index unstructured documents into a knowledge graph, store entities and relationships in Neo4j, and query them using natural language with Cohere’s embeddings and LLMs.

# Features

Document ingestion: Load .txt (or other supported formats) and process into nodes/triplets.

Knowledge Graph construction: Extract entities/relationships and store them in Neo4j.

Embeddings & RAG: Use Cohere embeddings (embed-english-v3.0) for semantic search.

LLM Querying: Natural language queries answered using Cohere LLMs + Graph context.

Hybrid Retrieval: Combines vector-based search with graph-based reasoning.

# Tech Stack

LlamaIndex
 – Document indexing and RAG framework

Cohere API
 – Embeddings & LLM for answering queries

Neo4j
 – Graph database to store and query entities

Python 3.9+

# Requirements

llama-index==0.10.37
cohere==5.3.4
neo4j==5.22.0
python-dotenv==1.0.1
pandas==2.2.2
tqdm==4.66.4
requests==2.32.3
