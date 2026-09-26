# Enterprise Automated RAG Pipeline (n8n + Supabase pgvector)

[![n8n](https://img.shields.io/badge/Orchestration-n8n-FF6D5A?style=for-the-badge&logo=n8n)](https://n8n.io/)
[![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL_pgvector-4169E1?style=for-the-badge&logo=postgresql)](https://www.postgresql.org/)
[![Supabase](https://img.shields.io/badge/Vector_Store-Supabase-3ECF8E?style=for-the-badge&logo=supabase)](https://supabase.com/)
[![OpenAI](https://img.shields.io/badge/Embeddings-OpenAI-412991?style=for-the-badge&logo=openai)](https://openai.com/)

An end-to-end, automated Enterprise Knowledge Base Retrieval-Augmented Generation (RAG) system. This pipeline ingests unstructured business documents from Google Drive, processes and chunks text dynamically, generates vector embeddings, stores them in PostgreSQL (Supabase pgvector), and serves an interactive AI Agent for low-latency contextual intelligence.

---

## 📌 Architecture & Data Pipeline Flow
