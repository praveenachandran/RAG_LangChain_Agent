# RAG_LangChain_Agent

The goal of the project will be to build a robust generative search system capable of effectively and accurately answering questions from various policy documents. Used LangChain to build the generative search application.

This system is designed to process documents, store embeddings for vector-based search, and
execute natural language queries using reasoning agents. The architecture integrates
LangChain’s capabilities for document processing, embedding generation, vector search, and
question-answering (QA) pipelines, with additional agent systems for data analytics and SQL
queries.
System Features
1. Document Processing:
o Parse PDF documents and preprocess content into manageable chunks.
2. Embedding and Vector Search:
o Generate embeddings for textual data using a HuggingFace embedding model.
o Store embeddings in a Chroma vector database.
o Perform similarity searches for user queries.
3. Reasoning Agents:
o Conversational Agent: Answer natural language queries conversationally.
o Data Analytics Agent: Perform complex operations on tabular data.
o SQL Agent: Execute SQL queries on structured databases.
4. Question Answering:
o Use OpenAI’s LLMs for generating answers from retrieved content.
