# AI Research RAG Assistant

## Project Overview

The **AI Research RAG Assistant** is a comprehensive, end-to-end AI chatbot designed to provide detailed and accurate answers on AI and Machine Learning research topics. It leverages a custom knowledge base, advanced LLM orchestration, and dynamic tool integration to deliver context-aware responses via a user-friendly web interface.

## Key Features

* **Retrieval-Augmented Generation (RAG):** Built a specialized Pinecone vector database from 100+ Arxiv research papers, enabling accurate, context-aware responses to technical AI/ML queries.
* **Intelligent Multi-Agent Workflow:** Orchestrates complex query processing using **LangGraph**, featuring topic classification, query rephrasing, and dynamic tool invocation (web search, academic search, Wikipedia).
* **Multi-LLM & Optimized Performance:** Utilizes a strategic multi-LLM approach, employing a smaller, faster Groq LLM for efficient document summarization and a larger, more capable LLM for core reasoning and decision-making.
* **Full-Stack Implementation:** Developed a scalable backend API with FastAPI to serve the AI logic and an intuitive frontend user interface using Streamlit.
