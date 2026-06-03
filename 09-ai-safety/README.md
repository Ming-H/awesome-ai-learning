# AI Safety & Alignment Learning Resources

## Alignment Courses & Tutorials

### English
- [NeurIPS 2025 Tutorial: Human-AI Alignment](https://hai-alignment-course.github.io/tutorial/) - 涵盖对齐基础、方法、实践和挑战，含视频和幻灯片。 `Conference Tutorial` `EN`
- [RLHF Book Lectures - Nathan Lambert](https://www.youtube.com/watch?v=o6lJtJQgUg4) - 完整 RLHF 流水线：基础、IFT、奖励建模、拒绝采样。 `Video Course` `EN`
- [Safe and Reliable AI via Guardrails - DeepLearning.AI](https://www.deeplearning.ai/courses/safe-and-reliable-ai-via-guardrails) - 为 LLM 应用构建护栏，减轻幻觉。 `Free Course` `EN`
- [LLMs Post-Training Complete Guide: SFT, RLHF, DPO, GRPO](https://www.sundeepteki.org/advice/the-complete-guide-to-post-training-llms-how-sft-rlhf-dpo-and-grpo-shape-llms) - 完整后训练堆栈覆盖。 `Article` `EN`

### Chinese
- [LLM Post-Training 全景指南：从 RLHF 到 GRPO - 知乎](https://zhuanlan.zhihu.com/p/2012909606771400823) - SFT -> RLHF/DPO -> 拒绝采样 + 蒸馏。 `Article` `ZH`
- [RLHF三大挑战与突围之路 - 腾讯云](https://cloud.tencent.com/developer/article/2602681) - DPO、RLAIF 等方法对比。 `Article` `ZH`
- [MiniMind2 开源训练链路](https://huggingface.co/jingyaogong/MiniMind2-gguf) - 极简架构完整流水线：SFT、LoRA、RLHF(DPO)、RLAIF(PPO/GRPO)。 `Repo` `ZH/EN`

## Red Teaming

### Production Guardrails Frameworks

> 2026 核心洞察：合适的护栏可以将 8B 模型从 53% 提升到 99% 的 Agent 任务准确率（Forge）。关键不是更大的模型，而是更好的护栏。

- [Forge -- Guardrails take an 8B model from 53% to 99% on agentic tasks](https://github.com/antoinezambelli/forge) - 证明护栏比模型规模更重要的里程碑项目。提供代理服务器、WorkflowRunner 和防护中间件三种集成模式。HN 687 分。 `Repo` `EN`
- [NVIDIA NeMo Guardrails](https://github.com/NVIDIA-NeMo/Guardrails) - NVIDIA 开源工具包，使用 Colang 语言定义防护规则，支持输入/输出/对话/检索/执行五类防护。集成 LangChain、LlamaIndex。 `Repo` `EN`
- [Guardrails AI](https://github.com/guardrails-ai/guardrails) - Python 框架，Guardrails Hub 提供 PII 检测、毒性过滤、主题执行等预构建验证器。[防护基准索引](https://index.guardrailsai.com)。 `Repo` `EN`
- [Sponsio -- Deterministic Runtime Enforcement for Agents](https://github.com/SponsioLabs/Sponsio) - 纯代码合约检查 Agent 操作，0.139ms 延迟，无需 LLM 调用。避免 95.6% 错位，支持 LangChain/Claude/OpenAI/Google ADK/CrewAI。 `Repo` `EN`
- [shellfirm -- AI Coding Agent 和终端命令安全防护](https://github.com/kaplanelad/shellfirm) - 在危险 shell 命令执行前拦截，100+ 模式覆盖 9 个生态。可用作 MCP 服务器，与 Claude Code 集成。 `Repo` `EN`
- [ArchGW -- AI Agent 智能代理](https://github.com/katanemo/archgw) - 基于 Envoy 的智能边缘代理，在 Agent 和 LLM 之间充当防护执行点——提示防护、内容策略、路由和可观察性。 `Repo` `EN`

### Guardrails Tutorials & Best Practices

- [NeMo Guardrails: The Missing Manual (Pinecone)](https://www.pinecone.io/learn/nemo-guardrails-intro/) - 最受欢迎的第三方教程，覆盖 Colang 语言、输入/输出防护、对话流程控制、RAG 防护和越狱防御。 `Article` `EN`
- [agent-guardrails-template](https://github.com/TheArchitectit/agent-guardrails-template) - 为任何 LLM Agent 构建护栏结构的模板仓库，兼容 Claude/GPT/Gemini。 `Repo` `EN`
- [Safe and Reliable AI via Guardrails - DeepLearning.AI](https://www.deeplearning.ai/courses/safe-and-reliable-ai-via-guardrails) - 为 LLM 应用构建护栏的免费课程。 `Free Course` `EN`
- [Chatbot Guardrails Arena](https://huggingface.co/spaces/lighthouzai/guardrails-arena) - 护栏的竞技场式评估，比较不同防护配置的有效性。 `Benchmark` `EN`

### Agent Safety Research

- [AgentDoG 1.5 -- AI Agent 安全诊断框架](https://github.com/AI45Lab/AgentDoG) - 上海人工智能实验室出品，三维安全分类法诊断 Agent 轨迹，提供 0.8B-8B 参数的安全审核模型。[论文 1.5](https://arxiv.org/pdf/2605.29801)。 `Repo` `EN`
- [ToolSafe -- 工具调用安全防护](https://github.com/MurrayTom/ToolSafe) - 通过步骤级防护、主动监控和反馈驱动推理增强 Agent 工具调用安全。[论文](https://arxiv.org/abs/2601.10156)。 `Repo` `EN`
- [AGrail -- 终身 Agent 自适应安全防护](https://github.com/SaFo-Lab/AGrail4Agent) - ACL 2025 论文，支持自适应安全检查生成、优化和跨 Agent 迁移。 `Repo` `EN`

## Red Teaming (Offensive Security)

### Tools
- [Promptfoo](https://github.com/promptfoo/promptfoo) - LLM 评估和红队测试开源 CLI。 `Repo` `EN`
- [PyRIT - Microsoft](https://github.com/microsoft/PyRIT) - 微软红队测试工具，支持自动化攻击模拟。 `Repo` `EN`
- [Garak - NVIDIA](https://github.com/NVIDIA/garak) - NVIDIA LLM 漏洞扫描器，模糊测试和探测。 `Repo` `EN`
- [BlackIce - Databricks](https://www.databricks.com/blog/announcing-blackice-containerized-red-teaming-toolkit-ai-security-testing) - 14 种 AI 安全工具打包的容器化工具包。 `Tool` `EN`

### Guides
- [AI Red Teaming Complete Guide - Repello AI](https://repello.ai/blog/the-essential-guide-to-ai-red-teaming-in-2024) - 5 步方法论发现 LLM 和 Agent 漏洞。 `Article` `EN`
- [Agentic AI Red Teaming Guide - CSA](https://cloudsecurityalliance.org/artifacts/agentic-ai-red-teaming-guide) - 专门针对 Agent AI 的红队测试框架。 `Framework` `EN`
- [OWASP GenAI Red Teaming Initiative](https://genai.owasp.org/initiatives/red-teaming-initiative/) - LLM 红队测试和评估的行业标准。 `Standard` `EN`
- [AI Red Teaming Roadmap](https://roadmap.sh/ai-red-teaming) - 系统化红队学习路线图，从基础到高级。 `Free Course` `EN`
- [Black Hat USA 2026: AI Red Team Training](https://blackhat.com/us-26/training/schedule/index.html) - 微软 AI 红队创始成员授课，最实战的红队培训。 `Paid Course` `EN`

### Chinese
- [安全性测试：提示注入与红队 - 腾讯云](https://cloud.tencent.com/developer/article/2589034) - OWASP Top 10、红队方法论、自动化工具链。 `Article` `ZH`
- [AI安全月度动态追踪](https://github.com/tanjiti/sec_profile) - 每月 AI 安全报告和越狱手册。 `Repo` `ZH`

## Responsible AI Frameworks

- [NIST AI Risk Management Framework (AI RMF)](https://www.nist.gov/artificial-intelligence/ai-standards) - 美国自愿性 AI 风险管理框架。 `Framework` `EN`
- [EU AI Act](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai) - 世界首个综合性 AI 法律，基于风险分级。 `Regulation` `EN`
- [ISO/IEC 42001](https://www.urmconsulting.com/blog/artificial-intelligence-frameworks-and-regulations-iso-42001-the-nist-ai-rmf-and-the-eu-ai-act) - 可认证的国际 AI 管理体系标准。 `Standard` `EN`
- [AI Governance Frameworks Compared](https://elevateconsult.com/insights/ai-governance-frameworks-compared-matching-nist-eu-ai-act-and-iso-42001-to-your-use-case/) - NIST vs EU AI Act vs ISO 42001 对比。 `Article` `EN`

## Fairness & Bias

- [IBM AI Fairness 360 (AIF360)](https://github.com/Trusted-AI/AIF360) - 业界标准的偏见检测和缓解开源工具包，IBM Research 出品。 `Repo` `EN`
- [Fairlearn (Microsoft)](https://fairlearn.org/) - 开源公平性评估工具包，仪表盘 + 算法级公平性评估与缓解。 `Framework` `EN`
- [Google What-If Tool](https://pair-code.github.io/what-if-tool/) - Google PAIR 团队出品的交互式 ML 公平性可视化工具，无需编码即可探查模型行为。 `Tool` `EN`

## Prompt Injection Defense

- [LLM01:2025 Prompt Injection - OWASP](https://genai.owasp.org/llmrisk/llm01-prompt-injection/) - 提示注入作为顶级 LLM 风险的官方参考。 `Standard` `EN`
- [Prompt Injection in LLMs: Complete Guide 2026](https://capturethebug.xyz/blogs/Prompt-Injection-in-LLMs-Complete-Guide-for-2026) - 真实示例和缓解策略。 `Article` `EN`
- [OWASP LLM Top 10 2025 (Chinese)](http://owasp.org.cn/OWASP-CHINA/owasp-project/owasp-59278/) - 官方中文版本。 `Standard` `ZH`
- [AI大模型提示词攻击防御全景指南2025](https://www.cnblogs.com/whatsay/p/19180982) - 从单点攻击到系统性风险的防御策略。 `Article` `ZH`

## Research & Reports

- [2026 International AI Safety Report](https://internationalaisafetyreport.org/publication/international-ai-safety-report-2026) - 第二份国际 AI 安全报告，12 家公司更新了前沿安全框架。中英版本均有。 `Report` `EN/ZH`
- [Anthropic-OpenAI Joint Alignment Evaluation (2025)](https://openai.com/index/openai-anthropic-safety-evaluation) - 史上首次跨实验室互相评估对方模型安全性（sycophancy、whistleblowing、self-preservation）。 `Research` `EN`
- [Anthropic's Perspective on Cross-Evaluation](https://alignment.anthropic.com/2025/openai-findings/) - Anthropic 对联合评估结果的解读。 `Research` `EN`
- [Shallow Review of Technical AI Safety 2025 - LessWrong](https://www.lesswrong.com/posts/Wti4Wr7Cf5ma3FGWa/shallow-review-of-technical-ai-safety-2025-2) - 2025 年技术 AI 安全工作回顾。 `Research` `EN`
- [Anthropic Interpretability Research](https://www.anthropic.com/research/team/interpretability) - 机制可解释性研究。 `Research` `EN`
- [Anthropic Alignment Science Blog](https://alignment.anthropic.com) - Anthropic 对齐科学研究团队博客，涵盖欺骗检测、推理链监控等。 `Blog` `EN`
- [The Urgency of Interpretability - Dario Amodei](https://www.darioamodei.com/post/the-urgency-of-interpretability) - Anthropic CEO 阐述可解释性的重要性。 `Article` `EN`
- [OWASP Agentic AI Security Risks](https://genai.owasp.org/) - OWASP 针对 Agentic AI 的最新安全风险指南，覆盖 Agent 特有的攻击面。 `Standard` `EN`

## GitHub Repositories

- [dit7ya/awesome-ai-alignment](https://github.com/dit7ya/awesome-ai-alignment) - AI 对齐研究精选列表：论文、课程、书籍。 `Repo` `EN`
- [TalEliyahu/Awesome-AI-Security](https://github.com/TalEliyahu/Awesome-AI-Security) - AI 安全精选列表，含 OWASP Agentic Top 10。 `Repo` `EN`
- [anmolksachan/AI-ML-Free-Resources](https://github.com/anmolksachan/AI-ML-Free-Resources-for-Security-and-Prompt-Injection) - AI/ML 渗透测试免费路线图。 `Repo` `EN`
- [giskard-ai/awesome-ai-safety](https://github.com/giskard-ai/awesome-ai-safety) - 实际 AI 安全：偏见、隐私、鲁棒性。 `Repo` `EN`

## Learning Path

| Stage | Resource | Focus |
|-------|----------|-------|
| Beginner | DeepLearning.AI Guardrails 课程 + OWASP LLM Top 10 | 安全基础概念 |
| Guardrails | Forge + NeMo Guardrails + Guardrails AI | Agent 防护框架实践 |
| Alignment | RLHF Book Lectures + Post-Training Guide | 对齐技术栈 |
| Cross-Lab | Anthropic-OpenAI 联合对齐评估 + Anthropic Alignment Blog | 跨实验室安全评估 |
| Red Teaming | Promptfoo + PyRIT + Garak 实践 | 攻击模拟与测试 |
| Advanced RT | Black Hat AI Red Team Training + roadmap.sh AI Red Teaming | 专业红队训练 |
| Fairness | IBM AIF360 + Fairlearn + Google What-If Tool | 偏见检测与公平性评估 |
| Governance | NIST AI RMF + EU AI Act | 合规与治理框架 |
| Research | International AI Safety Report + Anthropic Interpretability | 前沿研究跟踪 |
