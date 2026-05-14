<div align="center">

# Awesome AI Learning Resources

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/Ming-H/awesome-ai-learning?style=social)](https://github.com/Ming-H/awesome-ai-learning/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/Ming-H/awesome-ai-learning)](https://github.com/Ming-H/awesome-ai-learning/commits/main)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

**200+ curated resources across 10 categories / 200+ 精选资源，覆盖 10 大方向**

AI learning resources curated for developers and researchers, from prompt engineering
fundamentals to advanced AI agent development, RAG systems, and the path toward AGI.

为开发者和研究者精选的 AI 学习资源合集，从提示工程基础到高级 AI Agent 开发、
RAG 系统构建，直至通向 AGI 的前沿研究。

[English](#contents) | [中文](#分类目录)

</div>

---

## Contents

- [Trending / What's New](#trending--whats-new)
- [Beginner / 入门](#beginner--入门)
  - [01 Prompt Engineering](#01-prompt-engineering)
  - [02 LLM Fundamentals](#02-llm-fundamentals)
  - [03 AI Coding Tools](#03-ai-coding-tools)
- [Intermediate / 进阶](#intermediate--进阶)
  - [04 RAG](#04-rag)
  - [05 AI Agent](#05-ai-agent)
  - [06 Skills / Function Calling](#06-skills--function-calling)
  - [07 MCP](#07-mcp)
- [Advanced / 高级](#advanced--高级)
  - [08 Claude Code](#08-claude-code)
  - [09 AI Safety & Alignment](#09-ai-safety--alignment)
  - [10 AGI](#10-agi)
- [Learning Path](#learning-path)
- [Contributing](#contributing)
- [License](#license)

---

## Trending / What's New

- 2026-05: Project launched with 200+ curated resources across 10 categories
- 2026-05: Added RAG, LLM Fundamentals, AI Coding Tools, AI Safety sections
- 2026-05: Bilingual README (EN/ZH), CI automation, and community standards

---

## Beginner / 入门

### 01 Prompt Engineering

[📁 Full Resources](./01-prompt-engineering/) · 20+ resources

提示工程教程、课程和最佳实践 / Tutorials, courses, and best practices for prompt engineering.

**⭐ Editor's Picks:**
- [ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers) - Andrew Ng + OpenAI, the most recommended entry course. `Free Course` `EN`
- [DAIR.AI Prompt Engineering Guide](https://www.promptingguide.ai/) | [中文版](https://www.promptingguide.ai/zh) - The most comprehensive open-source reference. `Guide` `EN/ZH`
- [dair-ai/Prompt-Engineering-Guide](https://github.com/dair-ai/prompt-engineering-guide) - 66k+ stars, the most authoritative repo. `Repo` `EN`

### 02 LLM Fundamentals

[📁 Full Resources](./02-llm-fundamentals/) · 30+ resources

大模型原理、微调、推理优化和分布式训练 / LLM architecture, fine-tuning (LoRA/QLoRA), inference optimization, and distributed training.

**⭐ Editor's Picks:**
- [Andrej Karpathy: Neural Networks Zero to Hero](https://karpathy.ai/zero-to-hero.html) - Widely considered the best starting point for deep learning and LLM fundamentals. `Video Course` `EN`
- [Sebastian Raschka: Build a LLM From Scratch](https://github.com/rasbt/LLMs-from-scratch) - Step-by-step build, pretrain, and fine-tune a GPT-like model (50k+ stars). `Book + Repo` `EN`
- [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) - Zero-code fine-tuning framework for 100+ models, most popular in the CN community. `Repo` `ZH/EN`

### 03 AI Coding Tools

[📁 Full Resources](./03-ai-coding-tools/) · 30+ resources

Cursor、Copilot、Windsurf 等 AI 编程工具 / AI-powered coding tools: Cursor, Copilot, Windsurf, and more.

**⭐ Editor's Picks:**
- [Cursor Official Docs](https://docs.cursor.com) - Complete official documentation for the leading AI-native IDE. `Docs` `EN`
- [GitHub Copilot Official Docs](https://docs.github.com/en/copilot) - Full docs for chat, editing, agent, and CLI features. `Docs` `EN`
- [2026 AI编程工具红黑榜](https://chenguangliang.com/posts/blog149_ai-coding-tools-2026-review/) - Real data and pricing comparison of 8 major tools. `Article` `ZH`

---

## Intermediate / 进阶

### 04 RAG

[📁 Full Resources](./04-rag/) · 25+ resources

向量数据库、嵌入模型、检索策略和评估框架 / Vector databases, embeddings, retrieval strategies, and evaluation.

**⭐ Editor's Picks:**
- [Building and Evaluating Advanced RAG - DeepLearning.AI](https://www.deeplearning.ai/courses/building-evaluating-advanced-rag) - Sentence-window, auto-merging retrieval and more. `Free Course` `EN`
- [Anthropic: Contextual Retrieval](https://www.anthropic.com/news/contextual-retrieval) - Breakthrough method significantly improving RAG accuracy. `Blog` `EN`
- [langchain-ai/rag-from-scratch](https://github.com/langchain-ai/rag-from-scratch) - LangChain official step-by-step RAG tutorial. `Repo` `EN`

### 05 AI Agent

[📁 Full Resources](./05-ai-agent/) · 30+ resources

Agent 框架、课程和架构模式 / Agent frameworks, courses, and architecture patterns.

**⭐ Editor's Picks:**
- [Agentic AI - DeepLearning.AI (Andrew Ng)](https://www.deeplearning.ai/courses/agentic-ai) - Four core agent design patterns. `Free Course` `EN`
- [LangGraph Official Docs](https://docs.langchain.com/oss/python/langgraph/overview) - The leading production agent orchestration framework. `Docs` `EN`
- [Agentic Design Patterns (Free e-Book)](https://assets.jimmysong.io/books/agentic-design-patterns-zh-20251208.pdf) - Multi-specialist agents > single large agent. `PDF` `ZH`

### 06 Skills / Function Calling

[📁 Full Resources](./06-skills/) · 10+ resources

工具使用、函数调用和 Agent Skills 开发 / Tool use, function calling, and agent skills development.

**⭐ Editor's Picks:**
- [Anthropic: Writing Tools for Agents](https://www.anthropic.com/engineering/writing-tools-for-agents) - How to design better tool descriptions. `Blog` `EN`
- [Anthropic Tool Use Docs](https://docs.anthropic.com/en/docs/build-with-claude/tool-use) - Official Claude tool use documentation with multi-tool support. `Docs` `EN`

### 07 MCP

[📁 Full Resources](./07-mcp/) · 20+ resources

MCP 协议文档、教程和服务器生态 / MCP protocol documentation, tutorials, and server ecosystem.

**⭐ Editor's Picks:**
- [MCP Official Docs](https://modelcontextprotocol.io) - The authoritative reference for the protocol. `Docs` `EN`
- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) - 62k+ stars, community MCP server collection. `Repo` `EN`
- [Claude MCP 完全攻略 - 掘金](https://juejin.cn/post/7526766150803488795) - Most comprehensive Chinese MCP guide (2025). `Article` `ZH`

---

## Advanced / 高级

### 08 Claude Code

[📁 Full Resources](./08-claude-code/) · 15+ resources

Claude Code Skills、Hooks、Plugins 和 MCP 集成 / Claude Code skills, hooks, plugins, and MCP integration.

**⭐ Editor's Picks:**
- [Claude Code Features Overview](https://code.claude.com/docs/en/features-overview) - Plugins bundle skills + hooks + subagents + MCP. `Docs` `EN`
- [Towards AI: Complete Beginner's Guide](https://pub.towardsai.net/a-complete-beginners-guide-to-claude-code-skills-agents-hooks-plugins-mcp-085b26b73fdd) - From installation to full feature coverage. `Article` `EN`

### 09 AI Safety & Alignment

[📁 Full Resources](./09-ai-safety/) · 25+ resources

AI 安全、对齐、红队测试和治理框架 / AI safety, alignment, red teaming, and governance frameworks.

**⭐ Editor's Picks:**
- [2026 International AI Safety Report](https://internationalaisafetyreport.org/publication/international-ai-safety-report-2026) - Second international report from the Bletchley Park AI Safety Summit. `Report` `EN/ZH`
- [Promptfoo](https://github.com/promptfoo/promptfoo) - Open-source CLI for LLM evaluation and red teaming. `Repo` `EN`
- [NeurIPS 2025 Tutorial: Human-AI Alignment](https://hai-alignment-course.github.io/tutorial/) - Research-grade tutorial with videos and slides. `Tutorial` `EN`

### 10 AGI

[📁 Full Resources](./10-agi/) · 10+ resources

AGI 研究、时间线和政策报告 / AGI research, timelines, and policy reports.

**⭐ Editor's Picks:**
- [Sequoia: 2026 This is AGI](https://sequoiacap.com/article/2026-this-is-agi/) - Long-horizon coding agents as functional AGI. `Article` `EN`
- [WaytoAGI 飞书知识库](https://waytoagi.feishu.cn/) - China's largest AI learning community (~9M learners). `Community` `ZH`
- [WEF: Preparing for AGI (2025)](https://reports.weforum.org/docs/WEF_Preparing_for_Artificial_General_Intelligence_2025.pdf) - Comprehensive global policy document. `PDF` `EN`

---

## Learning Path

```
入门 / Beginner
  ├── 01 Prompt Engineering (Andrew Ng course)
  ├── 02 LLM Fundamentals (Karpathy Zero to Hero)
  └── 03 AI Coding Tools (Cursor / Copilot docs)

进阶 / Intermediate
  ├── 04 RAG Systems (Vector DB + Retrieval strategies)
  ├── 05 Agent Frameworks (LangGraph / CrewAI / AutoGen)
  ├── 06 Skills / Function Calling (Tool development)
  └── 07 MCP Protocol & Development

高级 / Advanced
  ├── 08 Claude Code (Skills, Hooks, Plugins)
  ├── 09 AI Safety & Alignment (RLHF, Red Teaming)
  └── 10 AGI Research & Governance
```

---

## Contributing

PRs are welcome! Please read the [Contributing Guide](./CONTRIBUTING.md) and [Code of Conduct](./CODE_OF_CONDUCT.md) before submitting.

Format for new entries:

```markdown
- [Resource Name](URL) - Description ending with a period. `Type` `Language`
```

## License

[MIT](./LICENSE) &copy; Ming-H

---

<div align="center">

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Ming-H/awesome-ai-learning&type=Date)](https://star-history.com/#Ming-H/awesome-ai-learning&Date)

</div>
