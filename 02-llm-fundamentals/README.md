# LLM Fundamentals & Fine-Tuning Learning Resources

## LLM Architecture & Foundations

### English
- [Andrej Karpathy: Neural Networks Zero to Hero](https://karpathy.ai/zero-to-hero.html) - 从反向传播到构建 GPT，代码优先教学风格，被广泛认为是最佳起点。 `Video Course` `EN`
- [Andrej Karpathy: nanoChatGPT (2025)](https://github.com/karpathy/nanochat) - 用 8000 行代码构建完整 ChatGPT clone，覆盖 tokenizer 训练、预训练、微调、部署，仅需 ~$100。 `Repo` `EN`
- [Andrej Karpathy: 2025 LLM Year in Review](https://karpathy.bearblog.dev/year-in-review-2025/) - 提出 RLVR 取代 RLHF 成为新训练范式，指出 LLM 潜力只开发了不到 10%。必读。 `Article` `EN`
- [Stanford CS336: Language Modeling from Scratch (2025)](https://cs336.stanford.edu) - 比 CS224N 更实操，手把手教 transformer 实现、tokenization、分布式训练、scaling laws、RLHF/DPO。 `University Course` `EN`
- [Stanford CME295: Transformers & LLMs (2025)](https://www.youtube.com/watch?v=Ub3GoFaUcds) - 斯坦福大学课程，涵盖 Transformer 架构和注意力机制。 `University Course` `EN`
- [MIT 6.S191: Introduction to Deep Learning (2025)](https://introtodeeplearning.com/) - MIT 官方深度学习入门，涵盖 Transformer、生成模型、语言模型，2025 版全部上线 YouTube。 `University Course` `EN`
- [Hugging Face LLM Course (Maxime Labonne)](https://huggingface.co/blog/mlabonne/llm-course) - 免费开源路线图，科学家和工程师两条路径。 `Course` `EN`
- [Hugging Face Official LLM Course](https://huggingface.co/learn/llm-course/en/chapter1/1) - 官方课程，涵盖 Transformer 基础、微调和部署。 `Course` `EN`
- [Sebastian Raschka: Build a LLM From Scratch](https://github.com/rasbt/LLMs-from-scratch) - 一步步构建、预训练和微调类 GPT 模型（50k+ stars）。 `Book + Repo` `EN`

### Chinese
- [Datawhale llm-cookbook](https://github.com/datawhalechina/llm-cookbook) - 基于 Andrew Ng LLM 系列的开发者手册。 `Repo` `ZH`
- [从零到精通：2025年最全大模型学习资源 - 掘金](https://juejin.cn/post/7497804336567943207) - 入门到高级全面汇编。 `Article` `ZH`
- [0voice/learning-Journey-AI](https://github.com/0voice/learning-Journey-AI) - AI/ML/DL 全面学习路线。 `Repo` `ZH/EN`

## Fine-Tuning (LoRA, QLoRA, PEFT)

### English
- [LLM Fine-tuning Complete Guide 2026](https://www.youngju.dev/blog/llm/2026-03-17-llm-finetuning-complete-guide.en) - Full Fine-tuning、LoRA、QLoRA、RLHF、DPO 全覆盖。 `Article` `EN`
- [Complete LLM Fine-Tuning Guide - Towards AI](https://pub.towardsai.net/the-complete-llm-fine-tuning-guide-from-beginner-to-production-lora-qlora-peft-034dbef4148d) - 初学者到生产环境的分步实现。 `Article` `EN`
- [Fine-Tuning Infrastructure at Scale - Introl](https://introl.com/blog/fine-tuning-infrastructure-lora-qlora-peft-scale-guide-2025) - 硬件需求对比：全量 7B 需 100GB VRAM，QLoRA 仅需 RTX 4090。 `Article` `EN`
- [How to Fine-Tune Open LLMs in 2025 - Philschmid](https://www.philschmid.de/fine-tune-llms-in-2025) - Hugging Face `trl` 库实践教程。 `Tutorial` `EN`

### Chinese
- [liguodongiot/llm-action](https://github.com/liguodongiot/llm-action) - 6B-65B 模型训练教程：全量微调、LoRA、QLoRA、P-Tuning v2、RLHF。 `Repo` `ZH`
- [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) - 零代码微调框架，100+ 模型，WebUI 界面。中国最受欢迎的微调工具。 `Repo` `ZH/EN`

## Inference Optimization

- [vLLM Official Optimization Docs](https://docs.vllm.ai/en/stable/configuration/optimization/) - 4 种优化级别配置，最大吞吐量与延迟优化。 `Docs` `EN`
- [SGLang](https://github.com/sgl-project/sglang) - UC Berkeley 新一代推理框架，RadixAttention 自动 KV cache 复用，10k+ stars。 `Repo` `EN`
- [LLM Inference Optimization - Mithril Forge](https://mithrilforge.ai/blog/llm-inference-optimization-model-level) - 量化、剪枝、蒸馏和 FlashAttention。 `Article` `EN`
- [NVIDIA: Pruning and Distilling LLMs](https://developer.nvidia.com/blog/pruning-and-distilling-llms-using-nvidia-tensorrt-model-optimizer/) - TensorRT 实用步骤。 `Article` `EN`
- [llama.cpp](https://github.com/ggerganov/llama.cpp) - C++ 推理，CPU/GPU 混合，GGUF 量化格式。 `Repo` `EN`
- [Comparing Top 6 Inference Runtimes 2025 - MarkTechPost](https://www.marktechpost.com/2025/11/07/comparing-the-top-6-inference-runtimes-for-llm-serving-in-2025/) - vLLM、SGLang、TGI 等推理引擎严格基准测试对比。 `Article` `EN`

## Evaluation & Benchmarking

- [Chatbot Arena (LMArena)](https://arena.ai/) - 业界最权威的 LLM 排行榜，基于数百万次人类盲评 Elo 评分。 `Benchmark` `EN`
- [Stanford HELM: Holistic Evaluation of Language Models](https://crfm.stanford.edu/helm/) - 斯坦福 CRFM 多场景、多指标综合评估框架。 `Framework` `EN`
- [Hugging Face Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) - 开源 LLM 标准排行榜，覆盖 IFEval、BBH、MATH、GPQA 等。 `Benchmark` `EN`
- [EleutherAI lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) - HF Leaderboard 后端引擎，60+ 评估任务，少样本评估标准框架。 `Repo` `EN`
- [DeepEval](https://github.com/confident-ai/deepeval) - 开源 LLM 评估框架，Pytest 风格单元测试，生产级 LLM 测试标准。 `Repo` `EN`
- [Artificial Analysis](https://artificialanalysis.ai) - 独立基准平台，对比所有主流 LLM 的质量、价格、速度和 TTFT。 `Benchmark` `EN`
- [Evidently AI: LLM Benchmarks Guide](https://www.evidentlyai.com/llm-guide/llm-benchmarks) - 30+ LLM 基准测试（MMLU、HumanEval、Chatbot Arena 等）最全面综述。 `Article` `EN`

## Production Deployment & Observability

- [Langfuse](https://github.com/langfuse/langfuse) - LLM 可观测性事实标准开源工具：追踪、Prompt 管理、评估、成本追踪。 `Repo` `EN`
- [Top 10 LLM Observability Tools Guide 2025](https://langwatch.ai/blog/top-10-llm-observability-tools-complete-guide-for-2025) - Langfuse、LangWatch、Opik、Datadog、Phoenix 等可观测性工具全面对比。 `Article` `EN`

## Distributed Training

- [DeepSpeed Official Training Docs](https://www.deepspeed.ai/training/) - ZeRO 优化阶段、卸载和内存优化。 `Docs` `EN`
- [Megatron-FSDP User Guide - NVIDIA](https://docs.nvidia.com/megatron-core/developer-guide/latest/discussions/megatron-fsdp-user-guide/megatron-fsdp-user-guide.html) - Megatron-LM 与 PyTorch FSDP 结合。 `Docs` `EN`
- [Using DeepSpeed and FSDP with Accelerate](https://medium.com/@adityashanmugham/make-llm-training-possible-across-multi-gpus-using-fsdp-and-deepspeed-in-accelerate-part-1-33eb2a813f60) - 多 GPU LLM 训练综合指南。 `Article` `EN`

## Open-Source LLM Ecosystem

- [10 Best Open-Source LLMs 2025 - Hugging Face](https://huggingface.co/blog/daya-shankar/open-source-llms) - Llama 4、Qwen 3、DeepSeek、Mistral 对比。 `Article` `EN`
- [Open-Source LLMs Compared 2026](https://till-freitag.com/blog/open-source-llm-comparison) - 25+ 开源 LLM 并排对比含吞吐量基准。 `Article` `EN`

**Key Model Families:** Llama 4 (Meta) | DeepSeek R1/V3 | Qwen 3/3.5 (Alibaba) | Mistral | Gemma 3 (Google)

## Key Framework Repositories

| Repo | Purpose |
|------|---------|
| [huggingface/transformers](https://github.com/huggingface/transformers) | LLM 微调核心库 |
| [huggingface/peft](https://github.com/huggingface/peft) | 参数高效微调 (LoRA, QLoRA) |
| [huggingface/trl](https://github.com/huggingface/trl) | RLHF 和 DPO 训练 |
| [hiyouga/LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) | 零代码微调，100+ 模型 |
| [unslothai/unsloth](https://github.com/unslothai/unsloth) | 2 倍速微调 |
| [vllm-project/vllm](https://github.com/vllm-project/vllm) | 高吞吐量推理 |
| [ggerganov/llama.cpp](https://github.com/ggerganov/llama.cpp) | C++ 推理，CPU/GPU 混合 |
| [microsoft/DeepSpeed](https://github.com/microsoft/DeepSpeed) | 分布式训练 |

## Data Preparation

- [mlabonne/llm-datasets](https://github.com/mlabonne/llm-datasets) - LLM 训练数据集和工具精选列表。 `Repo` `EN`
- [Dataset Preparation for LLM Post-Training - Anyscale](https://docs.anyscale.com/llm/fine-tuning/data-preparation) - SFT 和偏好方法的数据格式化。 `Docs` `EN`
- [Preparing Your Own Dataset - AWS](https://aws.amazon.com/blogs/machine-learning/an-introduction-to-preparing-your-own-dataset-for-llm-training/) - 数据准备流程和最佳实践。 `Tutorial` `EN`
- [Distilabel (Argilla)](https://github.com/argilla-io/distilabel) - 开源合成数据生成框架，用于 RLHF 偏好数据和指令微调数据管道。 `Repo` `EN`
- [Argilla](https://github.com/argilla-io/argilla) - LLM 微调数据协作标注平台，与 Distilabel 配合使用。 `Repo` `EN`

## Learning Path

| Stage | Resource | Focus |
|-------|----------|-------|
| Foundations | Karpathy Zero to Hero + MIT 6.S191 | 深度学习基础 |
| Build from Scratch | Karpathy nanoChatGPT + Raschka LLMs-from-scratch | 从零构建 GPT |
| University | Stanford CS336 + CME295 | 学术级深度理解 |
| Paradigm Shift | Karpathy 2025 Year in Review (RLVR) | 训练范式最新进展 |
| Frameworks | Hugging Face 课程 + transformers/peft 库 | 工具链掌握 |
| Fine-Tuning | LLaMA-Factory 实践 + Philschmid 教程 | LoRA/QLoRA 动手实践 |
| Inference | vLLM + SGLang + llama.cpp | 部署与推理优化 |
| Evaluation | Chatbot Arena + HELM + DeepEval | 模型评估与基准测试 |
| Production | Langfuse + Observability 对比 | 生产部署与可观测性 |
| Advanced | DeepSpeed + Megatron-LM | 分布式训练 |
