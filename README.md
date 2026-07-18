# Enterprise RAG Assistant 🚀

An enterprise-grade Retrieval-Augmented Generation (RAG) system that enables users to interact with organizational knowledge bases using Large Language Models (LLMs).

The solution combines document intelligence, semantic search, hybrid retrieval, and LLM reasoning to provide accurate, context-aware answers with source citations while minimizing hallucinations.

Built with modern GenAI engineering practices including RAG evaluation, observability, prompt optimization, and scalable API deployment.

## Key Features

    Document ingestion pipeline for enterprise documents (PDF, DOCX, TXT)  
    Intelligent document chunking and metadata extraction  
    Hybrid retrieval using keyword search + vector embeddings  
    Semantic similarity search for contextual retrieval  
    Azure OpenAI-powered response generation  
    Source citation and reference tracking  
    Query rewriting for improved retrieval accuracy  
    RAG evaluation using RAGAS metrics  
    LLM tracing and monitoring using Langfuse  
    FastAPI backend architecture  
    Docker-based deployment  

## Architecture

User Query
    |
    ↓
Query Processing
    |
    ↓
Hybrid Retriever
(BM25 + Vector Search)
    |
    ↓
Relevant Context Retrieval
    |
    ↓
Azure OpenAI LLM
    |
    ↓
Generated Response + Citations


## Technology Stack

### Generative AI
- Azure OpenAI (GPT models)
- LangChain
- LangGraph
- RAG
- Prompt Engineering
- RAGAS Evaluation

### Search & Retrieval
- Vector Database
- Embeddings
- Hybrid Search
- Semantic Retrieval

### Backend & Deployment
- Python
- FastAPI
- Docker
- Azure Cloud

### Observability
- Langfuse
- LLM Tracing
- Evaluation Metrics


## Use Cases

- Enterprise knowledge assistants
- Internal documentation search
- Customer support automation
- Policy and compliance assistants
- Technical documentation assistants
- AI-powered employee support systems


## Future Enhancements

- Multi-agent retrieval workflow
- GraphRAG integration
- Conversation memory
- Role-based access control
- Real-time document synchronization
