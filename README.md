# Awesome-Vector-Search-Platform

## Top Vector Search Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Embedding Storage, Approximate Nearest Neighbor (ANN) Search, Hybrid Retrieval, Metadata Filtering, RAG Infrastructure & Billion-Scale Similarity Search*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Vector Search**. These systems store high-dimensional embeddings and enable fast similarity search, hybrid (vector + keyword) retrieval, filtering, and ranking — the backbone of modern RAG, semantic search, recommendation, and AI-agent memory applications.

**Examples** include Pinecone, Weaviate, Qdrant, Zilliz Cloud, Vespa, Marqo, Typesense Cloud, Elastic Vector Search, Astra DB Vector, and Milvus (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for vector databases, ANN libraries, and embedding stores. Many leading commercial offerings are built on (or offer) strong open-source cores — ideal for teams that need data control, cost efficiency, or custom infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Pinecone](https://www.pinecone.io/)**  
  Fully managed, serverless vector database optimized for low-latency production RAG and semantic search with minimal operational overhead.

- **[Weaviate Cloud](https://weaviate.io/)**  
  Managed service of the open-source Weaviate vector database, strong in hybrid search, schema flexibility, and modular AI pipelines.

- **[Qdrant Cloud](https://qdrant.tech/)**  
  Managed offering of the high-performance Rust-based Qdrant vector database, known for speed, advanced filtering, and efficient resource use.

- **[Zilliz Cloud](https://zilliz.com/)**  
  Fully managed service built on Milvus, designed for large-scale and enterprise vector search workloads.

- **[Vespa Cloud](https://vespa.ai/)**  
  Managed version of the open-source Vespa engine, combining vector search with powerful ranking, recommendation, and serving capabilities.

- **[Marqo](https://www.marqo.ai/)**  
  End-to-end vector search platform focused on ease of use for multimodal and tensor-based search applications.

- **[Typesense Cloud](https://typesense.org/)**  
  Managed service of the open-source Typesense search engine, which includes strong vector search alongside typo-tolerant keyword search.

- **[Elastic Vector Search / Elasticsearch](https://www.elastic.co/)**  
  Vector search capabilities within the Elastic Stack, leveraging dense_vector fields, HNSW, and hybrid retrieval in a battle-tested search platform.

- **[Astra DB Vector (DataStax)](https://www.datastax.com/)**  
  Vector search features on top of Apache Cassandra / Astra DB for teams already in the Cassandra ecosystem.

- **[Milvus (via Zilliz or self-managed offerings)](https://milvus.io/)**  
  The open-source Milvus project powers both self-hosted deployments and commercial managed services for massive-scale vector search.

## Open-Source GitHub Projects
- **[Milvus](https://github.com/milvus-io/milvus)**  
  High-performance, cloud-native open-source vector database built for billion-scale ANN search, widely used in production AI systems.

- **[Qdrant](https://github.com/qdrant/qdrant)**  
  Rust-powered open-source vector database optimized for performance, rich filtering, and production reliability.

- **[Weaviate](https://github.com/weaviate/weaviate)**  
  Open-source vector database with native hybrid search, GraphQL API, modular vectorization, and strong schema support.

- **[Chroma](https://github.com/chroma-core/chroma)**  
  Developer-friendly open-source embedding database designed for LLM applications, prototyping, and lightweight production use.

- **[pgvector](https://github.com/pgvector/pgvector)**  
  Open-source PostgreSQL extension that adds vector similarity search directly inside Postgres — ideal when you already run PostgreSQL.

- **[Vespa](https://github.com/vespa-engine/vespa)**  
  Open-source big-data serving engine with first-class vector search, sophisticated ranking, and real-time indexing.

- **[Faiss (Facebook AI Similarity Search)](https://github.com/facebookresearch/faiss)**  
  Foundational open-source library for efficient similarity search and clustering of dense vectors (CPU & GPU).

- **[LanceDB](https://github.com/lancedb/lancedb)**  
  Open-source, lakehouse-native vector database built on Apache Arrow/Lance, optimized for multimodal and large-scale data.

- **[Typesense](https://github.com/typesense/typesense)**  
  Fast, typo-tolerant open-source search engine with robust vector search capabilities.

- **[Vald, USearch, hnswlib, DiskANN, ScaNN and other ANN libraries](https://github.com/)**  
  Specialized open-source indexing and search libraries that power many higher-level vector databases.

### Additional Strong Open-Source Options
- **Redis** (with vector search modules) for combining vectors with caching and operational data.
- **OpenSearch / Elasticsearch** open-source distributions with native vector support.
- **SQLite-VSS**, **DuckDB** vector extensions, and other embedded options.
- Lightweight libraries: Annoy, NMSLIB, NGT for specific ANN use cases.
- Integration frameworks and clients that make it easy to swap vector backends in RAG pipelines.

**Frameworks for building custom systems**: Choose **Milvus** or **Qdrant** for dedicated high-scale vector workloads, **Weaviate** when hybrid search and rich schema matter, **pgvector** when you want to stay inside PostgreSQL, and **Chroma** or **LanceDB** for rapid development. Pair any of them with open embedding models, LangChain/LlamaIndex (or equivalent), and open observability tools. Use **Faiss** or **hnswlib** when you need maximum control over the index layer itself.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Vector databases are critical infrastructure for AI applications. Evaluate performance, filtering accuracy, consistency guarantees, multi-tenancy, and operational complexity against your specific workload and scale.
- Self-hosted open-source solutions require proper capacity planning, monitoring, backup, and security hardening, especially for production RAG or agent systems.

---
**Made for AI engineers, search teams, and builders of RAG and semantic applications.**
Let's make high-quality vector search more open, portable, and accessible.
