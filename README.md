

# **AI Codebase Expert with RAG**  

This repository contains an AI-powered assistant that uses **Retrieval-Augmented Generation (RAG)** to interact intelligently with a codebase. The assistant leverages embeddings to understand and retrieve the most relevant parts of the codebase and provides accurate, context-aware responses to user queries.

## **Features**  

- **Codebase Parsing**: Automatically clones a GitHub repository and processes supported files.  
- **Embeddings Generation**: Uses Hugging Face's `sentence-transformers` to create vector embeddings of the codebase.  
- **Vector Database Integration**: Stores embeddings in Pinecone for efficient search and retrieval.  
- **Intelligent Querying**: Combines retrieved context with OpenAI's API and **GROQ** to answer questions grounded in the codebase.  
- **Scalability**: Designed to handle large repositories with ease.  

## **Future Enhancements**  

- **Multimodal RAG**: Support for image uploads to enable contextual understanding from both text and visuals.  
- **Multiple Codebases**: Ability to dynamically switch between different codebases during a session.  

---

## **Usage**  

1. **Clone and Process Codebase**:  
   - Provide a GitHub repository URL to clone and parse the codebase.  
2. **Ask Questions**:  
   - Input queries related to the codebase and get responses powered by RAG.  

---

## **Technologies Used**  

- **Python**: Core programming language  
- **Hugging Face**: For generating embeddings  
- **Pinecone**: Vector database for efficient retrieval  
- **OpenAI**: For generating intelligent responses  
- **GROQ**: For advanced query generation  

---

## **License**  

This project is licensed under the [MIT License](LICENSE).  

---

## **Acknowledgments**  

Special thanks to the open-source community and the platforms like **GROQ**, **OpenAI**, **Pinecone**, and **Hugging Face** for providing the tools and frameworks that made this project possible.  

---
