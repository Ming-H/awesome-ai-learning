# RAG (Retrieval-Augmented Generation) Learning Resources

## Courses

### Free Courses
- [Building and Evaluating Advanced RAG - DeepLearning.AI](https://www.deeplearning.ai/courses/building-evaluating-advanced-rag) - Andrew Ng 团队出品，涵盖 sentence-window 检索、auto-merging 检索等高级技巧。 `Free Course` `EN`
- [RAG Fundamentals - DeepLearning.AI](https://www.deeplearning.ai/courses/retrieval-augmented-generation) - RAG 基础课程，讲解检索与生成如何协同工作。 `Free Course` `EN`
- [7 Free Courses to Master RAG - Turing Post](https://www.turingpost.com/p/7-free-courses-to-master-rag) - 收录 7 门免费 RAG 课程汇总。 `Article` `EN`
- [Krish Naik: RAG Crash Course](https://www.youtube.com/watch?v=o126p1QN_RI) - 2 小时速成课程，配套 GitHub 代码仓库。 `Video` `EN`

### Paid Courses
- [RAG with LangChain - DataCamp](https://www.datacamp.com/courses/retrieval-augmented-generation-rag-with-langchain) - 用 LangChain 构建 RAG 管道的结构化课程。 `Paid Course` `EN`

### Chinese Resources
- [北大 AI x Physics: RAG 课程](https://aiphy.pku.edu.cn/course/llm-agent/rag) - 基于 Chroma 向量数据库构建完整本地知识库。 `Course` `ZH`
- [万字详解 RAG 优化 - JavaGuide](https://javaguide.cn/ai/rag/rag-optimization.html) - 覆盖 Chunk 策略、混合搜索、查询改写、重排序等核心主题。 `Article` `ZH`
- [RAG 技术介绍 - PromptingGuide](https://www.promptingguide.ai/zh/techniques/rag) - DAIR.AI 经典 RAG 概念中文版。 `Article` `ZH`
- [RAG 学习路线 - 掘金](https://juejin.cn/post/7603673564908879907) - 数据预处理、向量化、检索算法、重排序优化。 `Article` `ZH`

## GitHub Repositories

- [Danielskry/Awesome-RAG](https://github.com/Danielskry/Awesome-RAG) - 最全面的 RAG 精选资源列表。 `Repo` `EN`
- [run-llama/awesome-rag](https://github.com/run-llama/awesome-rag) - LlamaIndex 团队维护，引用经典论文和最新技术。 `Repo` `EN`
- [langchain-ai/rag-from-scratch](https://github.com/langchain-ai/rag-from-scratch) - LangChain 官方从零构建 RAG 的代码教程。 `Repo` `EN`
- [vivy-yi/rag-tutorial](https://github.com/vivy-yi/rag-tutorial) - 中文，4 模块 20 章 17 个 Notebook + 6 个企业级实战案例。 `Repo` `ZH`
- [embeddings-benchmark/mteb](https://github.com/embeddings-benchmark/mteb/) - MTEB 官方嵌入模型评估工具箱。 `Repo` `EN`

## Official Documentation

- [OpenAI: Retrieval Guide](https://developers.openai.com/api/docs/guides/retrieval) - 官方语义搜索和向量存储指南。 `Docs` `EN`
- [Anthropic: Contextual Retrieval](https://www.anthropic.com/news/contextual-retrieval) - 突破性"上下文检索"方法，显著提升 RAG 准确度。 `Blog` `EN`
- [Google Cloud: RAG Reference Architectures](https://docs.cloud.google.com/architecture/rag-reference-architectures) - Google 官方 RAG 参考架构。 `Docs` `EN`
- [LangChain: RAG Tutorial](https://python.langchain.com/docs/tutorials/rag/) - LangChain 官方 RAG 教程。 `Docs` `EN`
- [LlamaIndex: Official Docs](https://docs.llamaindex.ai/) - LlamaIndex 专为 RAG 设计的数据框架。 `Docs` `EN`

## Vector Databases

- [Vector DB Comparison 2026 - Reintech](https://reintech.io/blog/vector-database-comparison-2026-pinecone-weaviate-milvus-qdrant-chroma) - 2026 年五大向量数据库全面对比。 `Article` `EN`
- [面向多模态检索的向量数据库对比 - 博客园](https://www.cnblogs.com/Im-Victor/p/19100904) - 涵盖 ES、Milvus、Pinecone、FAISS、Chroma、PGVector。 `Article` `ZH`
- [向量数据库全攻略 - 火山引擎](https://developer.volcengine.com/articles/7602479797138931762) - 从基础概念到选型指南再到实践。 `Article` `ZH`

**Quick Reference:** Pinecone (全托管SaaS) | Chroma (本地原型) | Milvus (亿级向量) | Qdrant (Rust高性能) | Weaviate (混合搜索)

## Embedding Models

- [MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard) - 嵌入模型官方排行榜。 `Benchmark` `EN`
- [Best Embedding Models for RAG 2026 - PremAI](https://blog.premai.io/best-embedding-models-for-rag-2026-ranked-by-mteb-score-cost-and-self-hosting/) - 按 MTEB 分数、成本和自托管排名。 `Article` `EN`

## Architecture & Advanced Techniques

- [8 RAG Architectures You Should Know - Humanloop](https://humanloop.com/blog/rag-architectures) - Simple RAG、Branched RAG、HyDE 等 8 种架构模式。 `Article` `EN`
- [Hybrid Search and Re-Ranking - Towards DS](https://towardsdatascience.com/hybrid-search-and-re-ranking-in-production-rag/) - 混合搜索 + 重排序对比分析。 `Article` `EN`
- [9 Advanced RAG Techniques - Meilisearch](https://www.meilisearch.com/blog/rag-techniques) - 智能分块到上下文蒸馏全面指南。 `Article` `EN`

## Evaluation Frameworks

- [RAGAS](https://github.com/explodinggradients/ragas) - 专为 RAG 设计的评估框架（Faithfulness、Answer Relevance 等）。 `Repo` `EN`
- [TruLens](https://www.trulens.org/getting_started/core_concepts/rag_triad/) - LLM 可观测性框架，核心是 RAG Triad。 `Framework` `EN`

## Knowledge Graph RAG

- [Microsoft GraphRAG](https://github.com/microsoft/graphrag) - 知识图谱增强的 RAG，从文本语料自动构建知识图谱，支持多跳推理和全局摘要。 `Repo` `EN`
- [Microsoft GraphRAG Official Docs](https://microsoft.github.io/graphrag/) - GraphRAM 官方文档，包含架构设计和使用指南。 `Docs` `EN`
- [GraphRAG Research Paper](https://www.microsoft.com/en-us/research/project/graphrag/) - 微软研究院 GraphRAG 项目主页和论文。 `Research` `EN`

## Agentic RAG

- [RAG Techniques You Must Know 2025 - Towards AI](https://pub.towardsai.net/rag-techniques-you-must-know-in-2025-872b074da20a) - Contextual Retrieval、Agentic RAG、Hybrid Retrieval。 `Article` `EN`
- [Agentic RAG: The 2026 Guide](https://weaviate.io/blog/agentic-rag) - Agent 动态决定何时/如何检索，2025-2026 最重要的 RAG 趋势。 `Article` `EN`

## Learning Path

| Stage | Resource | Focus |
|-------|----------|-------|
| Beginner | DeepLearning.AI RAG Fundamentals + PromptingGuide 中文版 | RAG 核心概念 |
| Hands-on | langchain-ai/rag-from-scratch + LlamaIndex 文档 | 动手构建 RAG |
| Advanced | Advanced RAG 课程 + Anthropic Contextual Retrieval | 高级检索技术 |
| Knowledge Graph | Microsoft GraphRAG + 官方文档 | 知识图谱增强的多跳推理 |
| Agentic | Agentic RAG 指南 + RAG Techniques 2025 | Agent 驱动的动态检索 |
| Production | Google Cloud 参考架构 + RAGAS 评估 | 生产级部署与评估 |
