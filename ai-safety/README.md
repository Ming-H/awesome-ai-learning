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

### Tools
- [Promptfoo](https://github.com/promptfoo/promptfoo) - LLM 评估和红队测试开源 CLI。 `Repo` `EN`
- [PyRIT - Microsoft](https://github.com/microsoft/PyRIT) - 微软红队测试工具，支持自动化攻击模拟。 `Repo` `EN`
- [Garak - NVIDIA](https://github.com/NVIDIA/garak) - NVIDIA LLM 漏洞扫描器，模糊测试和探测。 `Repo` `EN`
- [BlackIce - Databricks](https://www.databricks.com/blog/announcing-blackice-containerized-red-teaming-toolkit-ai-security-testing) - 14 种 AI 安全工具打包的容器化工具包。 `Tool` `EN`

### Guides
- [AI Red Teaming Complete Guide - Repello AI](https://repello.ai/blog/the-essential-guide-to-ai-red-teaming-in-2024) - 5 步方法论发现 LLM 和 Agent 漏洞。 `Article` `EN`
- [Agentic AI Red Teaming Guide - CSA](https://cloudsecurityalliance.org/artifacts/agentic-ai-red-teaming-guide) - 专门针对 Agent AI 的红队测试框架。 `Framework` `EN`
- [OWASP GenAI Red Teaming Initiative](https://genai.owasp.org/initiatives/red-teaming-initiative/) - LLM 红队测试和评估的行业标准。 `Standard` `EN`

### Chinese
- [安全性测试：提示注入与红队 - 腾讯云](https://cloud.tencent.com/developer/article/2589034) - OWASP Top 10、红队方法论、自动化工具链。 `Article` `ZH`
- [AI安全月度动态追踪](https://github.com/tanjiti/sec_profile) - 每月 AI 安全报告和越狱手册。 `Repo` `ZH`

## Responsible AI Frameworks

- [NIST AI Risk Management Framework (AI RMF)](https://www.nist.gov/artificial-intelligence/ai-standards) - 美国自愿性 AI 风险管理框架。 `Framework` `EN`
- [EU AI Act](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai) - 世界首个综合性 AI 法律，基于风险分级。 `Regulation` `EN`
- [ISO/IEC 42001](https://www.urmconsulting.com/blog/artificial-intelligence-frameworks-and-regulations-iso-42001-the-nist-ai-rmf-and-the-eu-ai-act) - 可认证的国际 AI 管理体系标准。 `Standard` `EN`
- [AI Governance Frameworks Compared](https://elevateconsult.com/insights/ai-governance-frameworks-compared-matching-nist-eu-ai-act-and-iso-42001-to-your-use-case/) - NIST vs EU AI Act vs ISO 42001 对比。 `Article` `EN`

## Prompt Injection Defense

- [LLM01:2025 Prompt Injection - OWASP](https://genai.owasp.org/llmrisk/llm01-prompt-injection/) - 提示注入作为顶级 LLM 风险的官方参考。 `Standard` `EN`
- [Prompt Injection in LLMs: Complete Guide 2026](https://capturethebug.xyz/blogs/Prompt-Injection-in-LLMs-Complete-Guide-for-2026) - 真实示例和缓解策略。 `Article` `EN`
- [OWASP LLM Top 10 2025 (Chinese)](http://owasp.org.cn/OWASP-CHINA/owasp-project/owasp-59278/) - 官方中文版本。 `Standard` `ZH`
- [AI大模型提示词攻击防御全景指南2025](https://www.cnblogs.com/whatsay/p/19180982) - 从单点攻击到系统性风险的防御策略。 `Article` `ZH`

## Research & Reports

- [2026 International AI Safety Report](https://internationalaisafetyreport.org/publication/international-ai-safety-report-2026) - 第二份国际 AI 安全报告，12 家公司更新了前沿安全框架。中英版本均有。 `Report` `EN/ZH`
- [Shallow Review of Technical AI Safety 2025 - LessWrong](https://www.lesswrong.com/posts/Wti4Wr7Cf5ma3FGWa/shallow-review-of-technical-ai-safety-2025-2) - 2025 年技术 AI 安全工作回顾。 `Research` `EN`
- [Anthropic Interpretability Research](https://www.anthropic.com/research/team/interpretability) - 机制可解释性研究。 `Research` `EN`
- [The Urgency of Interpretability - Dario Amodei](https://www.darioamodei.com/post/the-urgency-of-interpretability) - Anthropic CEO 阐述可解释性的重要性。 `Article` `EN`

## GitHub Repositories

- [dit7ya/awesome-ai-alignment](https://github.com/dit7ya/awesome-ai-alignment) - AI 对齐研究精选列表：论文、课程、书籍。 `Repo` `EN`
- [TalEliyahu/Awesome-AI-Security](https://github.com/TalEliyahu/Awesome-AI-Security) - AI 安全精选列表，含 OWASP Agentic Top 10。 `Repo` `EN`
- [anmolksachan/AI-ML-Free-Resources](https://github.com/anmolksachan/AI-ML-Free-Resources-for-Security-and-Prompt-Injection) - AI/ML 渗透测试免费路线图。 `Repo` `EN`
- [giskard-ai/awesome-ai-safety](https://github.com/giskard-ai/awesome-ai-safety) - 实际 AI 安全：偏见、隐私、鲁棒性。 `Repo` `EN`

## Learning Path

| Stage | Resource | Focus |
|-------|----------|-------|
| Beginner | DeepLearning.AI Guardrails 课程 + OWASP LLM Top 10 | 安全基础概念 |
| Alignment | RLHF Book Lectures + Post-Training Guide | 对齐技术栈 |
| Red Teaming | Promptfoo + PyRIT + Garak 实践 | 攻击模拟与测试 |
| Governance | NIST AI RMF + EU AI Act | 合规与治理框架 |
| Research | International AI Safety Report + Anthropic Interpretability | 前沿研究跟踪 |
