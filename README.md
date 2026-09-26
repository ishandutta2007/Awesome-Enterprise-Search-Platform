# Awesome-Enterprise-Search-Platform

## Top Enterprise Search Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Workplace Search, AI/RAG Enterprise Search, Unified Knowledge Discovery, Relevance & Secure Cross-Application Search*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Search**. These systems index and search content across SaaS apps, documents, intranets, and data sources—often with AI-powered answers, permissions awareness, and relevance tuning for workplace or customer-facing use cases.

**Examples** include Glean, Coveo, Algolia, Yext Search, Elastic Workplace Search, IBM Watson Discovery, Lucidworks, Sinequa, SearchUnify, BA Insight, Elastic Enterprise Search, Microsoft Search, Algolia Enterprise Search, Funnelback, SearchBlox, and Google Cloud Enterprise Search (the category leaders).

**Open-source emphasis**: Enterprise search has a strong open foundation. **Elasticsearch**, **OpenSearch**, **Apache Solr**, **Meilisearch**, **Typesense**, and **Fess** power many self-hosted and hybrid deployments. AI/RAG-oriented open projects (e.g., Onyx) further expand options. This section heavily expands those projects.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Glean](https://www.glean.com/)**  
  AI-powered enterprise search and knowledge assistant that connects to workplace apps and surfaces answers with permissions awareness.

- **[Coveo](https://www.coveo.com/)**  
  Relevance platform for enterprise and digital experience search—strong connectors, ML ranking, and generative answering capabilities.

- **[Algolia / Algolia Enterprise Search](https://www.algolia.com/)**  
  High-performance search-as-a-service widely used for product, site, and application search with developer-friendly APIs.

- **[Yext Search](https://www.yext.com/)**  
  Search and knowledge graph platform focused on structured answers and brand/experience search experiences.

- **[Elastic Workplace Search / Elastic Enterprise Search](https://www.elastic.co/)**  
  Enterprise and workplace search capabilities built on the Elastic Stack—connectors, relevance tuning, and hybrid search.

- **[IBM Watson Discovery](https://www.ibm.com/)**  
  AI-powered search and content intelligence platform for enterprise knowledge discovery and document understanding.

- **[Lucidworks](https://lucidworks.com/)**  
  Enterprise search and AI platform emphasizing relevance engineering, pipelines, and large-scale search applications.

- **[Sinequa](https://www.sinequa.com/)**  
  Intelligent enterprise search platform with strong focus on security, hybrid retrieval, and governed answers.

- **[SearchUnify, BA Insight, Funnelback, SearchBlox](https://www.example.com/)**  
  Additional enterprise search and knowledge platforms used for customer support, intranet, and specialized search use cases.

- **[Microsoft Search / Google Cloud Enterprise Search and related cloud offerings](https://www.microsoft.com/)**  
  Cloud-native enterprise search integrated with Microsoft 365 and Google Cloud ecosystems for organization-wide discovery.

## Open-Source GitHub Projects
- **[Elasticsearch](https://github.com/elastic/elasticsearch)**  
  Dominant open (and open-core) search and analytics engine—full-text, vector, hybrid search, and a large ecosystem for enterprise search applications.

- **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**  
  Apache 2.0 open-source fork of Elasticsearch—neural search, k-NN, security features, and fully open licensing for self-hosted enterprise search.

- **[Apache Solr](https://github.com/apache/solr)**  
  Mature Lucene-based open-source search platform long used for enterprise and large-scale content search.

- **[Meilisearch](https://github.com/meilisearch/meilisearch)**  
  Lightning-fast, developer-friendly open-source search engine with typo tolerance, hybrid search, and simple deployment.

- **[Typesense](https://github.com/typesense/typesense)**  
  Fast, typo-tolerant open-source search engine designed for instant search experiences and easy self-hosting.

- **[Fess](https://github.com/codelibs/fess)**  
  Open-source enterprise and site search server built on OpenSearch—crawlers for web, file, DB, and cloud sources with admin UI and RAG/semantic capabilities.

- **[Onyx (formerly Danswer)](https://github.com/onyx-dot-app/onyx)**  
  Open-source AI enterprise search / RAG platform for connecting workplace data sources and answering questions with citations.

- **[Vespa](https://github.com/vespa-engine/vespa)**  
  Open-source big data serving engine for search, recommendation, and real-time ranking at scale.

- **[Connector and crawler open frameworks](https://github.com/)**  
  Community crawlers and connectors that feed documents into Elasticsearch, OpenSearch, or Solr for enterprise indexes.

- **[Documentation and enterprise search open playbooks](https://github.com/)**  
  Guides for deploying OpenSearch/Elasticsearch-based workplace search, relevance tuning, and RAG pipelines.

### Additional Strong Open-Source Options
- Self-hosting **OpenSearch** or **Elasticsearch** as the core engine for custom enterprise search.
- Using **Fess** for a more turnkey open enterprise search server with built-in crawlers.
- Deploying **Meilisearch** or **Typesense** for fast application and site search with minimal ops.
- Adding **Onyx** or similar open RAG stacks for AI-powered workplace Q&A on top of indexed content.
- Accepting that packaged connectors for dozens of SaaS apps, polished permission-aware UX, enterprise support, and out-of-the-box generative answers still favor commercial platforms (Glean, Coveo, Elastic Enterprise Search, Sinequa, Lucidworks, etc.).
- Focusing open-source efforts on data ownership, customization of ranking, and cost control.

**Frameworks for building custom systems**: Index content with OpenSearch/Elasticsearch/Solr (or Fess) → enforce document-level security → tune relevance → optionally layer RAG/LLM answering → expose via search UI or API. Suitable for platform and search engineering teams. Many enterprises still choose commercial enterprise search for speed of connector coverage and governance.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Enterprise search indexes sensitive organizational content. Open-source deployments require careful security, access control, and data governance. This list is not security or compliance advice.

---
**Made for knowledge managers, search engineers, and open-source search advocates.**
Let's keep organizational knowledge findable, relevant, and as open as practical.
