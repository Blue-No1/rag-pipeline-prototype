# RAG Flow Diagram (Draft)

User Query
    ↓
Retriever (FAISS/Chroma)
    ↓ (Top-k docs)
Generator (LLM: e.g., Llama 3 Instruct)
    ↓
Response
