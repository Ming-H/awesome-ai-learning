# Skills / Function Calling Learning Resources

## Official Documentation

### Tool Use / Function Calling
- [OpenAI Function Calling Guide](https://developers.openai.com/api/docs/guides/function-calling) - 定义函数、处理 tool_use 响应的官方指南。 `Docs` `EN`
- [Anthropic Tool Use Docs](https://docs.anthropic.com/en/docs/build-with-claude/tool-use) - Claude 工具使用文档，含多工具和错误处理。 `Docs` `EN`
- [Google Gemini Function Calling](https://ai.google.dev/gemini-api/docs/function-calling) - Google Gemini 函数调用指南，支持并行函数调用。 `Docs` `EN`

### Structured Output
- [OpenAI Structured Outputs](https://platform.openai.com/docs/guides/structured-outputs) - JSON Schema 约束的可靠结构化输出，保证 100% 格式合规。 `Docs` `EN`
- [Anthropic Tool Use: Forced Tool Use](https://docs.anthropic.com/en/docs/build-with-claude/tool-use#forced-tool-use) - 强制工具调用实现结构化输出。 `Docs` `EN`
- [Instructor (Python)](https://github.com/jxnl/instructor) - 基于 Pydantic 的 LLM 结构化输出库，支持 OpenAI/Anthropic/Google 等多后端。 `Repo` `EN`
- [Instructor (TypeScript)](https://github.com/instructor-ai/instructor-js) - TypeScript 版本的结构化输出库。 `Repo` `EN`

## Engineering Blog Posts

- [Anthropic: Writing Tools for Agents](https://www.anthropic.com/engineering/writing-tools-for-agents) - Anthropic 工程团队：如何通过精心设计工具描述改进 Agent 工具。 `Blog` `EN`
- [Anthropic: Advanced Tool Use](https://www.anthropic.com/engineering/advanced-tool-use) - 编程式工具调用和并行执行的工程实践。 `Blog` `EN`
- [Anthropic: Effective Context Engineering for AI Agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents) - 优化 Agent 的工具和上下文效用。 `Blog` `EN`
- [OpenAI: Building Effective Agents](https://openai.com/index/building-effective-agents/) - OpenAI 官方 Agent 设计模式：编排、工具使用、任务交接。 `Blog` `EN`

## Tutorials & Guides

- [Cross-Platform Function Calling Guide](https://digitalapplied.com/blog/ai-function-calling-guide-openai-anthropic-google) - OpenAI/Anthropic/Google 函数调用实现对比。 `Article` `EN`
- [Mastering Tool Calling Best Practices 2025](https://sparkco.ai/blog/mastering-tool-calling-best-practices-for-2025) - 优化、个性化和实时适应的最佳实践。 `Article` `EN`
- [2026 Agent Skills Guide](https://serenitiesai.com/articles/agent-skills-guide-2026) - 针对 Claude Code、Cursor、Codex 等 12+ AI 工具的 Agent Skills 开放标准。 `Article` `EN`
- [anthropics/prompt-eng-interactive-tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial) - Anthropic 官方互动教程，含 chaining、tool use、搜索和检索。 `Repo` `EN`
- [Tool Calling Evaluation Guide](https://hamel.dev/blog/posts/evals/) - 如何评估 LLM 工具调用的正确性和鲁棒性。 `Article` `EN`

## Frameworks & Libraries

- [LangChain Tools](https://python.langchain.com/docs/concepts/tools/) - LangChain 工具抽象层，支持自定义工具创建和集成。 `Docs` `EN`
- [CrewAI Tools](https://docs.crewai.com/concepts/tools) - CrewAI 内置工具集和自定义工具开发指南。 `Docs` `EN`
- [Semantic Kernel Plugins (Microsoft)](https://learn.microsoft.com/en-us/semantic-kernel/concepts/plugins/) - 微软 Semantic Kernel 的 Plugin/Function 体系。 `Docs` `EN`

## Learning Path

| Stage | Resource | Focus |
|-------|----------|-------|
| Beginner | OpenAI + Anthropic + Google Tool Use 文档 | 理解函数调用机制 |
| Structured | Structured Outputs + Instructor 库 | 可靠的结构化输出 |
| Intermediate | Cross-Platform Guide + Tool Calling Best Practices | 跨平台对比与最佳实践 |
| Advanced | Writing Tools for Agents + Context Engineering | 工程级优化 |
| Evaluation | Tool Calling Evaluation Guide | 工具调用质量评估 |
| Ecosystem | 2026 Agent Skills Guide + 各框架工具体系 | 了解各平台的 Skills 标准 |
