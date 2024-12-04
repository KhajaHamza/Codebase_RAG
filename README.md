
AI Codebase Expert with RAG

This repository contains an AI-powered assistant that uses Retrieval-Augmented Generation (RAG) to interact intelligently with a codebase. The assistant leverages embeddings to understand and retrieve the most relevant parts of the codebase and provides accurate, context-aware responses to user queries.

Features

Codebase Parsing: Automatically clones a GitHub repository and processes supported files.
Embeddings Generation: Uses Hugging Face's sentence-transformers to create vector embeddings of the codebase.
Vector Database Integration: Stores embeddings in Pinecone for efficient search and retrieval.
Intelligent Querying: Combines retrieved context with OpenAI's API and GROQ to answer questions grounded in the codebase.
Scalability: Designed to handle large repositories with ease.
Future Enhancements

Multimodal RAG: Support for image uploads to enable contextual understanding from both text and visuals.
Multiple Codebases: Ability to dynamically switch between different codebases during a session.
