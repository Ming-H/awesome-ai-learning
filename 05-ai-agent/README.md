# AI Agent Learning Resources

## Frameworks

### LangGraph (by LangChain)
- [Official Documentation](https://docs.langchain.com/oss/python/langgraph/overview) - 当前最主流的 Agent 编排框架，基于图架构构建有状态多步工作流。 `Docs` `EN`
- [GitHub](https://github.com/langchain-ai/langgraph)
- [LangChain Academy: Intro to LangGraph](https://academy.langchain.com/courses/intro-to-langgraph) - 官方免费基础课程。 `Free Course` `EN`

### CrewAI
- [Official Documentation](https://docs.crewai.com/) - 轻量级独立 Python 框架，基于角色的 Agent 编排，内置记忆和可观测性。 `Docs` `EN`
- [GitHub](https://github.com/crewAIInc/crewAI)

### Microsoft AutoGen / AG2
- [AG2 (Community Fork)](https://ag2.ai/) | [Microsoft Version](https://github.com/microsoft/autogen) - 多 Agent 对话框架，2025 年分为社区版 AG2 和微软版。 `Framework` `EN`
- [AG2 Documentation](https://docs.ag2.ai/)

### OpenAI Agents SDK
- [Official Documentation](https://developers.openai.com/api/docs/guides/agents) - 轻量级 Python 框架，支持多 Agent 协调、工具使用和任务交接。 `Docs` `EN`
- [Announcement Blog](https://openai.com/index/the-next-evolution-of-the-agents-sdk)

### Anthropic Claude Agent SDK
- [Official Overview](https://code.claude.com/docs/en/agent-sdk/overview) - 提供与 Claude Code 相同的工具链，支持 MCP 集成和子 Agent 编排。 `Docs` `EN`
- [Tutorial](https://letsdatascience.com/blog/claude-agent-sdk-tutorial)

### Google ADK (Agent Development Kit)
- [Official Documentation](https://docs.cloud.google.com/gemini-enterprise-agent-platform/build/adk) - Google 开源的企业级 Agent 开发框架。 `Docs` `EN`
- [GitHub](https://github.com/google/adk-python)

### PydanticAI
- [Official Documentation](https://pydantic.dev/docs/ai/overview/) | [中文文档](https://ai.pydantic.org.cn/) - 类型安全的 Python Agent 框架，2025 年 9 月达到 V1 稳定版。 `Docs` `EN/ZH`
- [GitHub](https://github.com/pydantic/pydantic-ai)

### Anthropic Academy
- [Anthropic Academy (17 Free Courses)](https://anthropic.skilljar.com/) - Anthropic 官方学习平台，17 门免费认证课程，覆盖 Claude Code、Agent SDK、MCP、Subagents、安全等。2026 年 4 月更新。 `Free Course` `EN`
- [MCP: Build Rich-Context AI Apps with Anthropic - DeepLearning.AI](https://www.deeplearning.ai/courses/mcp-build-rich-context-ai-apps-with-anthropic) - 与 Anthropic 联合出品，涵盖多 Agent 架构、MCP Registry API、服务发现与认证。 `Free Course` `EN`

### DeerFlow
- [DeerFlow (ByteDance)](https://github.com/bytedance/DeerFlow) - 字节跳动开源多 Agent 协作框架，支持深度研究和报告生成。 `Framework` `ZH/EN`

### Mastra
- [Mastra](https://mastra.ai/) - TypeScript Agent 框架，2026 年新秀，支持工作流编排、RAG 集成和 Agent 评估。 `Framework` `EN`
- [Mastra GitHub](https://github.com/mastra-inc/mastra)

### A2A Protocol (Agent-to-Agent)
- [Google A2A Protocol](https://github.com/google/A2A) - Google 提出的 Agent 间通信开放协议，现由 Linux Foundation 治理。24k+ stars，支持 Python/Go/JS/Java/.NET/Rust SDK。V1.0 规范已发布。 `Protocol` `EN`
- [A2A Official Docs](https://a2a-protocol.org) - 完整协议文档：规范、核心概念、Agent 发现、企业功能、流式传输、多租户、与 MCP 协同工作。 `Docs` `EN`
- [A2A Protocol - DeepLearning.AI 课程](https://www.deeplearning.ai/short-courses/a2a-the-agent2agent-protocol) - Google Cloud 和 IBM Research 联合出品，涵盖 Agent A2A 合规、客户端构建、顺序和分层工作流。 `Free Course` `EN`
- [Waggle -- A2A Agent 搜索引擎](https://waggle.zone) - 按功能语义搜索 A2A Agent，实时健康监控、延迟跟踪，含 [Claude Code 插件](https://github.com/Waggle-AI/waggle-claude-code-plugin)。 `Platform` `EN`
- [A2Apex -- A2A Agent 测试与认证](https://a2apex.io) - 类似 SSL Labs + npm 的 Agent 信任层，50+ 自动化合规检查，0-100 信任分数和金银铜认证。 `Platform` `EN`
- [A2A vs MCP: Start of AI Protocol War?](https://www.koyeb.com/blog/google-a2a-anthropic-mcp-ai-agent-protocol-war) - MCP 处理垂直集成（Agent 到工具），A2A 处理水平集成（Agent 到 Agent），互补而非竞争。 `Article` `EN`
- [Google ADK 2.0 (Agent Development Kit)](https://github.com/google/adk-python) - 20k+ stars，新增基于图的工作流运行时（扇出/扇入、循环、重试、人机协作）和 Task API。 `Repo` `EN`

## Courses

### Free Courses
- [Agentic AI - DeepLearning.AI (Andrew Ng)](https://www.deeplearning.ai/courses/agentic-ai) - 吴恩达旗舰课程，涵盖四种核心 Agent 设计模式。 `Free Course` `EN`
- [AI Agents in LangGraph - DeepLearning.AI](https://www.deeplearning.ai/courses/ai-agents-in-langgraph) - 从零构建 Agent，再用 LangGraph 重构。 `Free Course` `EN`
- [AI Agents for Beginners - Microsoft Learn](https://learn.microsoft.com/en-us/shows/ai-agents-for-beginners/) - 10 节免费视频课，从概念到代码。 `Free Course` `EN`
- [microsoft/ai-agents-for-beginners](https://github.com/microsoft/ai-agents-for-beginners) - 12 节免费课程配套仓库。 `GitHub` `EN`
- [Hugging Face AI Agents Course](https://huggingface.co/learn/agents-course) - Hugging Face 官方免费课程。 `Free Course` `EN`
- [Agentic AI with LangGraph, CrewAI, AutoGen and BeeAI - Coursera](https://www.coursera.org/learn/agentic-ai-with-langgraph-crewai-autogen-and-beeai) - 系统学习 Agentic 设计原则与编排策略的结构化课程。 `Paid Course` `EN`
- [LangGraph 0.4 Full 8-Hour Course](https://www.youtube.com/watch?v=Y3dbzuQBnUw) - YouTube 免费完整教程（~75K 播放）。 `Video` `EN`

### Paid Courses
- [AI Agents Bootcamp - Zero To Mastery](https://zerotomastery.io/courses/ai-agents-bootcamp/) - 综合训练营，覆盖 CrewAI、LangGraph、MCP。 `Paid Course` `EN`

### Chinese Courses
- [LangGraph 全教程 - B站](https://www.bilibili.com/video/BV1fBQaYZESC/) - 中文最佳 LangGraph 视频教程。 `Video` `ZH`
- [2025 AI Agent 开发完全指南 - 知乎](https://zhuanlan.zhihu.com/p/1932119139343905681) - 6 周深度课程，覆盖主流框架。 `Article` `ZH`

## GitHub Repositories

- [kyrolabs/awesome-agents](https://github.com/kyrolabs/awesome-agents) - 260+ 开源 Agent 工具精选列表，20+ 分类。 `Repo` `EN`
- [jim-schwoebel/awesome_ai_agents](https://github.com/jim-schwoebel/awesome_ai_agents) - 全面的 Agent 资源中心。 `Repo` `EN`
- [ashishpatel26/500-AI-Agents-Projects](https://github.com/ashishpatel26/500-AI-Agents-Projects) - 500 个 Agent 用例集合，适合找灵感。 `Repo` `EN`
- [mkassaf/langgraph-complete-guide](https://github.com/mkassaf/langgraph-complete-guide) - LangGraph 从入门到多 Agent 系统的 Python 示例。 `Repo` `EN`

## Context Engineering

> "Context Engineering is 10x better than prompt engineering, and 100x better than vibe coding." — Cole Medin

Context Engineering 是 2026 年最热的新兴学科，被视为"Prompt Engineering 2.0"。核心思想：不是写更好的提示词，而是为 Agent 构建正确的上下文系统。

### Key Resources

- [A Survey of Context Engineering for Large Language Models](https://arxiv.org/abs/2507.13334) - 最权威的学术综述，将 Context Engineering 定义为正式学科并提供全面分类法。 `Paper` `EN`
- [Awesome Context Engineering](https://github.com/Meirtz/Awesome-Context-Engineering) - 精选列表，涵盖调查论文、框架和实施指南，含 2026 Agent Era Update。 `Repo` `EN/ZH`
- [Anthropic: Building Effective AI Agents](https://www.anthropic.com/engineering/building-effective-agents) - Anthropic 官方关于构建可靠 AI Agent 的权威指南，核心涉及 Context Engineering 原则。 `Article` `EN`
- [Context Engineering - LangChain Blog](https://blog.langchain.dev/context-engineering/) - LangChain 将 Context Engineering 分解为四个支柱：写入、选择、压缩、隔离上下文。 `Article` `EN`
- [DAIR.AI: Context Engineering Guide](https://www.promptingguide.ai/agents/context-engineering) | [深度解析](https://www.promptingguide.ai/agents/context-engineering-deep-dive) - 最受认可的学习平台，从 Prompt Engineering 扩展到 Context Engineering。 `Guide` `EN`
- [Context Engineering Intro - Cole Medin](https://github.com/coleam00/context-engineering-intro) - 13k+ stars，PRP（Product Requirement Prompt）工作流实践模板。 `Repo` `EN`

### Tools & Frameworks

- [Context Engineering Kit (NeoLabHQ)](https://github.com/NeoLabHQ/context-engineering-kit) - Claude Code/Cursor 高级 Context Engineering 插件集合（SDD、DDD、Reflexion 等模块）。 `Repo` `EN`
- [fenic: Declarative Context Engineering](https://github.com/typedef-ai/fenic) - Python 声明式框架，支持提取、分块、检索、压缩和总结，核心创新是推理卸载。 `Repo` `EN`
- [context-llemur](https://github.com/jerpint/context-llemur) - 基于 Git 的便携式上下文管理工具，支持跨 LLM 工具的持久化上下文。 `Repo` `EN`
- [Context Space](https://github.com/context-space/context-space) - 自称首个 Context Engineering 基础设施，通过 MCP 连接 14+ 服务。 `Repo` `EN/ZH`
- [How Claude Code Works](https://github.com/Windy3f3f3f3f/how-claude-code-works) - Claude Code 源码逆向分析，15 章详解上下文压缩（4 级渐进压缩）、工具协调、CLAUDE.md 管理。 `Repo` `ZH`

### Agent Memory

- [Mem0](https://github.com/mem0ai/mem0) - Agent 记忆层，支持短期和长期记忆管理，25k+ stars。 `Repo` `EN`
- [MemGPT / Letta](https://github.com/letta-ai/letta) - 有状态 LLM Agent 框架，通过虚拟上下文管理实现无限上下文窗口。 `Repo` `EN`
- [LangChain Memory](https://python.langchain.com/docs/concepts/memory/) - LangChain 官方记忆模块，支持多种记忆策略。 `Docs` `EN`
- [Zep](https://github.com/getzep/zep) - 面向 AI Agent 的长期记忆服务，支持自动知识提取和结构化记忆。 `Repo` `EN`
- [Agent Memory 完全指南 2026](https://mem0.ai/research/a-survey-on-the-memory-mechanism-of-large-language-model-based-agents) - 基于学术综述的 Agent 记忆机制全景分析。 `Article` `EN`

## Architecture & Patterns

- [Agentic Design Patterns (Free e-Book)](https://assets.jimmysong.io/books/agentic-design-patterns-zh-20251208.pdf) - Agent 架构模式系统化覆盖，核心原则：多专精 Agent 协作优于单一大 Agent。 `PDF` `ZH`
- [The Complete Guide to Building AI Agents in 2026](https://sidsaladi.substack.com/p/agent-frameworks-101-the-complete) - 框架无关的全面指南。 `Article` `EN`
- [AI Agent Frameworks Comparison 2025](https://dev.to/hani__8725b7a/agentic-ai-frameworks-comparison-2025-mcp-agent-langgraph-ag2-pydanticai-crewai-h40) - 7 大框架技术对比。 `Article` `EN`
- [AI Agent Frameworks 2026: Production Ranking](https://alicelabs.ai/en/insights/best-ai-agent-frameworks-2026) - 生产就绪度排名：LangGraph #1, Claude Agent SDK #2。 `Article` `EN`
- [Google ADK Multi-Agent Patterns](https://developers.googleblog.com/developers-guide-to-multi-agent-patterns-in-adk/) - 8 种多 Agent 设计模式。 `Article` `EN`
- [2025 LLM Agent Framework Complete Guide (HackMD)](https://hackmd.io/@BASHCAT/S12Y61lEZg) - AutoGen/CrewAI/LangGraph 对比与混合策略。 `Article` `ZH`
- [DeepSeek V3.2: Reasoning-First Models for Agents](https://api-docs.deepseek.com/news/news251201) - DeepSeek V3.2 定位为 Agent 优先的推理模型，V4 Preview 支持百万 token 上下文。 `Article` `EN`
- [2026: The Year of AI Agents - PIIE](https://www.piie.com/blogs/realtime-economics/2026/how-ai-boom-shrugged-deepseek-shock-and-keeps-gaining-steam) - 2026 被定义为 Agent 元年，Claude Code、DeepSeek 等 Agent 工具崛起。 `Article` `EN`

## Agent Evaluation

- [SWE-bench](https://www.swebench.com/) - 编码 Agent 权威基准测试：在真实 GitHub Issues 上评估 Agent 修复 Bug 的能力。 `Benchmark` `EN`
- [AgentBench](https://github.com/THUDM/AgentBench) - 清华大学多维度 Agent 评估框架，覆盖操作系统、数据库、Web 浏览等场景。 `Repo` `EN`
- [WebArena](https://webarena.dev/) - 真实 Web 环境中的 Agent 自主任务完成度评测。 `Benchmark` `EN`
- [τ-bench: Evaluating AI Agents on Conversational Task Fulfillment](https://github.com/Aditya1001001/tau-bench) - 对话式任务完成的 Agent 评估基准。 `Repo` `EN`
- [How to Evaluate AI Agents](https://www.anthropic.com/research/building-effective-agents) - Anthropic 官方关于 Agent 评估方法论的研究。 `Article` `EN`

## Learning Path

| Stage | Resource | Focus |
|-------|----------|-------|
| Beginner | Hugging Face + Andrew Ng Agentic AI | Agent 核心概念 |
| Context | Anthropic Building Effective Agents + LangChain Context Engineering | 上下文工程基础 |
| Framework | LangGraph + CrewAI 文档 | 选 1-2 个框架上手 |
| Architecture | 设计模式电子书 + 框架对比 | 多 Agent 架构设计 |
| Protocol | A2A 官方文档 + DeepLearning.AI 课程 + Waggle | Agent 间通信协议 |
| Production | Zero To Mastery + 知乎 6 周课程 | 生产部署实践 |
| Advanced | MCP 协议 + Claude/OpenAI Agent SDK | 工具集成与协议标准 |
| Memory | MemGPT + Mem0 + Zep | Agent 记忆管理机制 |
| Evaluation | SWE-bench + AgentBench + WebArena | Agent 能力评估与基准测试 |
