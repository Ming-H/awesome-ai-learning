# LLM Fundamentals & Fine-Tuning Learning Resources

## LLM Architecture & Foundations

### English
- [Andrej Karpathy: Neural Networks Zero to Hero](https://karpathy.ai/zero-to-hero.html) - 从反向传播到构建 GPT，代码优先教学风格，被广泛认为是最佳起点。 `Video Course` `EN`
- [Stanford CME295: Transformers & LLMs (2025)](https://www.youtube.com/watch?v=Ub3GoFaUcds) - 斯坦福大学课程，涵盖 Transformer 架构和注意力机制。 `University Course` `EN`
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
- [LLM Inference Optimization - Mithril Forge](https://mithrilforge.ai/blog/llm-inference-optimization-model-level) - 量化、剪枝、蒸馏和 FlashAttention。 `Article` `EN`
- [NVIDIA: Pruning and Distilling LLMs](https://developer.nvidia.com/blog/pruning-and-distilling-llms-using-nvidia-tensorrt-model-optimizer/) - TensorRT 实用步骤。 `Article` `EN`
- [llama.cpp](https://github.com/ggerganov/llama.cpp) - C++ 推理，CPU/GPU 混合，GGUF 量化格式。 `Repo` `EN`

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

## Learning Path

| Stage | Resource | Focus |
|-------|----------|-------|
| Foundations | Karpathy Zero to Hero + Raschka LLMs-from-scratch | 深度学习基础与 GPT 构建 |
| Frameworks | Hugging Face 课程 + transformers/peft 库 | 工具链掌握 |
| Fine-Tuning | LLaMA-Factory 实践 + Philschmid 教程 | LoRA/QLoRA 动手实践 |
| Inference | vLLM 文档 + llama.cpp | 部署与推理优化 |
| Advanced | DeepSpeed + Megatron-LM | 分布式训练 |
