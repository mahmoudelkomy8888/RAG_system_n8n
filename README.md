# Enterprise Automated RAG Pipeline (n8n + Supabase pgvector)

[![n8n](https://img.shields.io/badge/Orchestration-n8n-FF6D5A?style=for-the-badge&logo=n8n)](https://n8n.io/)
[![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL_pgvector-4169E1?style=for-the-badge&logo=postgresql)](https://www.postgresql.org/)
[![Supabase](https://img.shields.io/badge/Vector_Store-Supabase-3ECF8E?style=for-the-badge&logo=supabase)](https://supabase.com/)
[![OpenAI](https://img.shields.io/badge/Embeddings-OpenAI-412991?style=for-the-badge&logo=openai)](https://openai.com/)

An end-to-end, automated Enterprise Knowledge Base Retrieval-Augmented Generation (RAG) system. This pipeline ingests unstructured business documents from Google Drive, processes and chunks text dynamically, generates vector embeddings, stores them in PostgreSQL (Supabase pgvector), and serves an interactive AI Agent for low-latency contextual intelligence.

---

## 📌 Architecture & Data Pipeline Flow
[ Google Drive / Docs ]
│ (File Ingestion Trigger)
▼
[ Document Processing ] ──► [ Text Chunker (Recursive Splitter) ]
│
▼
[ OpenAI Vector Embeddings ]
│
▼
[ Supabase PostgreSQL (pgvector) ]
│
▼
[ Customer / User Query ] ──► [ RAG AI Agent + Memory ] ──► [ Contextual Answer ]


---

## 🛠️ Key Technical Features

* **Automated Data Ingestion Pipeline:** Syncs automatically with cloud storage (Google Drive) to extract and process unstructured PDF/Text documents.
* **Smart Text Chunking & Embedding Generation:** Utilizes recursive text splitters paired with OpenAI embedding models for optimal semantic chunk size and search accuracy.
* **Open-Source Enterprise Vector Storage:** Replaced proprietary vector stores with **PostgreSQL (`pgvector` on Supabase)**, unifying relational business data with high-dimensional vector search.
* **Conversational Agent with Memory:** Features an autonomous AI Agent equipped with vector search tools and session memory to handle complex contextual queries without hallucinations.

---

## 📊 Business ROI & Impact

| Metric | Traditional Search | Automated RAG Agent |
| :--- | :--- | :--- |
| **Document Retrieval Time** | 10 – 15 Minutes | **< 2 Seconds** |
| **Search Accuracy** | Keyword Matching | **Semantic / Vector Similarity** |
| **Operational Scalability** | Manual Knowledge Lookup | **Automated Concurrent Query Handling** |

---

## 📁 Repository Contents

* `README.md`: System design and Case Study architecture documentation.
* `workflows/`: Exported n8n workflow JSON file.

---

## ✉️ Author & Contact
**Mahmoud Mohamed Elkomy** — *AI Automation Engineer & RAG Architect*
* Email: [mahmoud.elkomy8888@gmail.com](mailto:mahmoud.elkomy8888@gmail.com)- 01009234327
* Location: 10th of Ramadan City, Sharqia, Egypt
* ة
* ةخلاه
