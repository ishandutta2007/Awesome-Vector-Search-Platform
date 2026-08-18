# Awesome-Vector-Search-Platform

![Banner](assets/banner.svg)

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
*Sorted by company size (revenue/valuation), descending. Pricing figures are the specific starting-tier list prices and free-tier limits as of August 2026 — see notes below the table for how each company-size figure was determined.*

| Product | Description | Pricing (starting tier) | Free tier / trial limits | Company size (revenue / valuation) |
|---|---|---|---|---|
| [**Elastic Vector Search / Elasticsearch**](https://www.elastic.co/) | Vector search in the Elastic Stack via `dense_vector` fields, HNSW and hybrid retrieval on a battle-tested search platform. | Elastic Cloud Hosted from **~$95/mo** (hourly, resource-based); Serverless from **~$16/mo** entry. | **14-day free trial** — full feature set, no credit card required (no permanent free tier). | **~$9.0B market cap** (NYSE: ESTC); FY2026 revenue **$1.74B** (public). |
| [**Astra DB Vector (DataStax)**](https://www.datastax.com/) | Vector search on Apache Cassandra / Astra DB, now part of IBM watsonx.data. | Pay-as-you-go: **~$0.37 per million read units, ~$0.62 per million write units, $0.25/GB/mo storage**. | **Free tier (free forever): 80GB storage + 20M read/write operations per month**. | **$1.6B last valuation** (2022); acquired by IBM (May 2025). |
| [**Pinecone**](https://www.pinecone.io/) | Fully managed, serverless vector database optimized for low-latency production RAG and semantic search with minimal operational overhead. | Free Starter; **Builder $20/mo flat**; **Standard from $50/mo minimum** (pay-as-you-go: $0.33/GB/mo storage, ~$16–18 per million reads, ~$4–4.50 per million writes); Enterprise $500/mo minimum. | **Starter free forever: 2GB storage, 1M reads/mo, 2M writes/mo, up to 5 indexes**. | **$750M valuation** (Series B, Apr 2023); ~$27M revenue (2024 est.). |
| [**Zilliz Cloud**](https://zilliz.com/) | Fully managed service built on Milvus, designed for large-scale and enterprise vector search workloads. | **Serverless from $0/mo** (pay-as-you-go: ~$0.096/CU-hour + $0.30/GB/mo storage); **Dedicated from $126/GB/mo**. | **Serverless free forever: 5GB storage, 2.5M vCUs/mo, up to 5 collections**; Dedicated clusters: **30-day free trial**. | **~$300M est. valuation** (third-party); $113M raised (valuation not disclosed). |
| [**Milvus (via Zilliz or self-managed offerings)**](https://milvus.io/) | The open-source Milvus project powers both self-hosted deployments and commercial managed services for massive-scale vector search. | **Open-source, free to self-host**; managed via Zilliz Cloud **from $0/mo** (see Zilliz Cloud). | **Unlimited** (open-source, self-hosted); via Zilliz Cloud: **5GB storage + 2.5M vCUs/mo** free forever. | Same company as Zilliz (**est. ~$300M**). |
| [**Weaviate Cloud**](https://weaviate.io/) | Managed service of the open-source Weaviate vector database, strong in hybrid search, schema flexibility, and modular AI pipelines. | **Flex from $45/mo** (usage-based per million vector dimensions); Plus from $280/mo; **Premium from $400/mo** (prepaid). | **Free forever: 100K objects, 1GB memory, 10GB disk, 1 cluster per user** (1 collection, up to 3 tenants). | **$200M valuation** (Series B, Apr 2023); $68M total raised. |
| [**Qdrant Cloud**](https://qdrant.tech/) | Managed offering of the high-performance Rust-based Qdrant vector database, known for speed, advanced filtering, and efficient resource use. | **Standard tier usage-based: clusters from ~$25–30/mo** (hourly billing, ~$0.078/GB RAM-hour); no monthly minimum. | **Free forever: single-node cluster — 0.5 vCPU, 1GB RAM, 4GB disk**. | **~$88M raised** ($28M Series A 2024, $50M Series B 2026); valuation not disclosed. |
| [**Vespa Cloud**](https://vespa.ai/) | Managed version of the open-source Vespa engine, combining vector search with powerful ranking, recommendation, and serving capabilities. | Usage-based: **~$0.145/vCPU-hour + $0.0145/GB RAM-hour + $0.0005/GB disk-hour** (small production clusters ≈ $300+/mo). | **Free trial only: $300 usage credits**, no credit card required (app stops when credits are exhausted). | **$31M Series A** (2023); Yahoo spinout (Yahoo retains a stake). |
| [**Marqo**](https://www.marqo.ai/) | End-to-end vector search platform focused on ease of use for multimodal and tensor-based search, now centered on AI ecommerce search. | Usage-based (billed for inference-node and shard hours; GPU instances from **~$0.28/hr**); plans historically from **~$25–50/mo**; current ecommerce plans sales-led. | No permanent free tier published since the 2025 pivot to enterprise ecommerce; **free trial with demo credits**. | **~$18M raised** ($12.5M Series A, Feb 2024); valuation not disclosed. |
| [**Typesense Cloud**](https://typesense.org/) | Managed service of the open-source Typesense search engine, which includes strong vector search alongside typo-tolerant keyword search. | Hourly resource-based: smallest **0.5GB node from ~$0.02–0.03/hr (≈$15–22/mo)**; no per-record or per-search charges. | **One-time free tier: 720 node-hours + 10GB bandwidth** (~1 month of a small node), incl. **1M records and 10K searches/mo**. | **~$1.4M est. ARR**; bootstrapped (no VC funding). |

*Notes: Company-size metric used per row — market cap (Elastic), last disclosed or third-party-estimated valuation (DataStax, Pinecone, Zilliz, Weaviate), or total funding / estimated ARR where no valuation is public (Qdrant, Vespa, Marqo, Typesense). Figures marked "~" are estimates. Pricing, free-tier limits, and company figures were verified against official pricing pages and public funding announcements as of August 2026 and may change — always check the vendor's current pricing page.*

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
