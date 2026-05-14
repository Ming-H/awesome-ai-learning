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

## Courses

### Free Courses
- [Agentic AI - DeepLearning.AI (Andrew Ng)](https://www.deeplearning.ai/courses/agentic-ai) - 吴恩达旗舰课程，涵盖四种核心 Agent 设计模式。 `Free Course` `EN`
- [AI Agents in LangGraph - DeepLearning.AI](https://www.deeplearning.ai/courses/ai-agents-in-langgraph) - 从零构建 Agent，再用 LangGraph 重构。 `Free Course` `EN`
- [AI Agents for Beginners - Microsoft Learn](https://learn.microsoft.com/en-us/shows/ai-agents-for-beginners/) - 10 节免费视频课，从概念到代码。 `Free Course` `EN`
- [microsoft/ai-agents-for-beginners](https://github.com/microsoft/ai-agents-for-beginners) - 12 节免费课程配套仓库。 `GitHub` `EN`
- [Hugging Face AI Agents Course](https://huggingface.co/learn/agents-course) - Hugging Face 官方免费课程。 `Free Course` `EN`
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

## Architecture & Patterns

- [Agentic Design Patterns (Free e-Book)](https://assets.jimmysong.io/books/agentic-design-patterns-zh-20251208.pdf) - Agent 架构模式系统化覆盖，核心原则：多专精 Agent 协作优于单一大 Agent。 `PDF` `ZH`
- [The Complete Guide to Building AI Agents in 2026](https://sidsaladi.substack.com/p/agent-frameworks-101-the-complete) - 框架无关的全面指南。 `Article` `EN`
- [AI Agent Frameworks Comparison 2025](https://dev.to/hani__8725b7a/agentic-ai-frameworks-comparison-2025-mcp-agent-langgraph-ag2-pydanticai-crewai-h40) - 7 大框架技术对比。 `Article` `EN`
- [AI Agent Frameworks 2026: Production Ranking](https://alicelabs.ai/en/insights/best-ai-agent-frameworks-2026) - 生产就绪度排名：LangGraph #1, Claude Agent SDK #2。 `Article` `EN`
- [Google ADK Multi-Agent Patterns](https://developers.googleblog.com/developers-guide-to-multi-agent-patterns-in-adk/) - 8 种多 Agent 设计模式。 `Article` `EN`
- [2025 LLM Agent Framework Complete Guide (HackMD)](https://hackmd.io/@BASHCAT/S12Y61lEZg) - AutoGen/CrewAI/LangGraph 对比与混合策略。 `Article` `ZH`

## Learning Path

| Stage | Resource | Focus |
|-------|----------|-------|
| Beginner | Hugging Face + Andrew Ng Agentic AI | Agent 核心概念 |
| Framework | LangGraph + CrewAI 文档 | 选 1-2 个框架上手 |
| Architecture | 设计模式电子书 + 框架对比 | 多 Agent 架构设计 |
| Production | Zero To Mastery + 知乎 6 周课程 | 生产部署实践 |
| Advanced | MCP 协议 + Claude/OpenAI Agent SDK | 工具集成与协议标准 |
