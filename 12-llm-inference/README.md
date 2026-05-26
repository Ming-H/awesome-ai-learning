# LLM Inference & Deployment Learning Resources

## Core Concepts & Papers

- [vLLM: Efficient Memory Management for LLM Serving (arXiv)](https://arxiv.org/pdf/2309.06180) - vLLM 原始论文，PagedAttention 核心思想，KV cache 近零浪费。 `Paper` `EN`
- [PagedAttention from First Principles](https://hamzaelshafie.bearblog.dev/paged-attention-from-first-principles-a-view-inside-vllm/) - 从第一性原理解释 PagedAttention，理解 vLLM 所有优化的基础。 `Article` `EN`
- [Anyscale: Continuous Batching 实现 23x 吞吐提升](https://www.anyscale.com/blog/continuous-batching-llm-inference) - Continuous Batching 系统级优化的权威解读，含基准测试。 `Article` `EN`
- [PagedAttention vs Continuous Batching vs vLLM vs SGLang](https://python.plainenglish.io/pagedattention-vs-continuous-batching-vs-vllm-vs-sglang-a-practical-breakdown-4c19cc9e21c0) - 四大推理优化技术横向对比。 `Article` `EN`
- [vLLM Explained: PagedAttention & Continuous Batching (RunPod)](https://www.runpod.io/articles/guides/vllm-pagedattention-continuous-batching) - 图文并茂的核心概念完整指南。 `Guide` `EN`
- [Spheron: H100 上 Continuous Batching + PagedAttention + Chunked Prefill 实测](https://www.spheron.network/blog/llm-serving-optimization-continuous-batching-paged-attention/) - H100 硬件上的实测基准与 vLLM 配置建议。 `Article` `EN`

**Quick Reference:** PagedAttention（KV cache 分页管理）| Continuous Batching（动态批处理，23x 提升）| Chunked Prefill（prefill/decode 交替）| Tensor Parallel（层内切片）| Pipeline Parallel（层间分配）

## vLLM Deployment & Production

- [vLLM Official Docs](https://docs.vllm.ai/en/latest/) - 官方文档入口：Quickstart、User Guide、API Reference。 `Docs` `EN`
- [vLLM Optimization and Tuning](https://docs.vllm.ai/en/stable/configuration/optimization/) - `max_num_seqs`、`max_num_batched_tokens`、chunked prefill 等关键参数调优。 `Docs` `EN`
- [vLLM Parallelism and Scaling](https://docs.vllm.ai/en/latest/serving/parallelism_scaling/) - 多 GPU/多节点：tensor parallel + pipeline parallel 配置。 `Docs` `EN`
- [SitePoint: vLLM Production Deployment Complete 2026 Guide](https://www.sitepoint.com/vllm-production-deployment-guide-2026/) - Docker + Kubernetes + 监控全套生产部署指南。 `Article` `EN`
- [Introl: vLLM 生产环境部署架构](https://introl.com/blog/vllm-production-deployment-inference-serving-architecture) - Stripe 用 vLLM 实现 73% 推理成本下降（50M 日调用量）。 `Article` `EN`
- [Red Hat: Distributed Inference with vLLM](https://developers.redhat.com/articles/2025/02/06/distributed-inference-with-vllm) - Tensor Parallel 与 Pipeline Parallel 的工程实践。 `Article` `EN`
- [KServe + llm-d + vLLM 生产级方案](https://llm-d.ai/blog/production-grade-llm-inference-at-scale-kserve-llm-d-vllm) - Kubernetes 原生 MLOps 平台集成 vLLM 的完整方案。 `Article` `EN`
- [KServe: Multi-node/Multi-GPU Inference](https://kserve.github.io/website/docs/model-serving/generative-inference/multi-node) - Kubernetes 多节点多 GPU 的 step-by-step 指南。 `Docs` `EN`
- [vLLM Throughput Optimization: 参数基础 (Medium)](https://medium.com/@kaige.yang0110/vllm-throughput-optimization-1-basic-of-vllm-parameters-c39ace00a519) - Dense/MoE/VLM 模型的 vLLM 参数调优实践。 `Article` `EN`
- [Reddit: NVLink-Aware Microsharding 实测](https://www.reddit.com/r/LocalLLaMA/comments/1quun6y/vllm_inference_costenergyperformance_optimization/) - 3x 吞吐提升、54.3% P99 延迟降低的实测数据。 `Discussion` `EN`

## Batch Inference (Ray Data + vLLM)

- [vLLM Offline Inference 官方文档](https://docs.vllm.ai/en/latest/serving/offline_inference/) - `LLM` 类基本用法 + Ray Data LLM API 简介。 `Docs` `EN`
- [Batch LLM Inference with Ray Data (vLLM v0.9)](https://docs.vllm.ai/en/v0.9.0.1/examples/offline_inference/batch_llm_inference.html) - 官方数据并行批量推理完整示例。 `Tutorial` `EN`
- [vLLM Offline Inference Distributed](https://vllm.hyper.ai/docs/0.8.x/getting-started/examples/examples/offline_inference_distributed/) - Ray Data 在多节点集群上分布式批量推理。 `Tutorial` `EN`
- [vLLM: OpenAI Batch File Format](https://docs.vllm.ai/en/stable/examples/offline_inference/openai_batch/) - 兼容 OpenAI 批处理文件格式的离线推理。 `Docs` `EN`
- [Ray Data: End-to-end Offline Batch Inference](https://docs.ray.io/en/latest/data/batch_inference.html) - Ray 官方批量推理框架文档。 `Docs` `EN`
- [Ray Data: Working with LLMs](https://docs.ray.io/en/latest/data/working-with-llms.html) - `ray.data.llm` 模块，推荐用 `build_llm_processor` API。 `Docs` `EN`
- [Anyscale: Ray Data LLM 实现 2x 吞吐 vs vLLM 同步 LLM](https://www.anyscale.com/blog/ray-data-llm-2x-throughput-vs-vllm) - Ray Data LLM 流式处理架构的性能优势。 `Article` `EN`
- [Red Hat: Batch Inference with Ray Data + vLLM + CodeFlare (2025)](https://developers.redhat.com/articles/2025/08/07/batch-inference-openshift-ai-ray-data-vllm-and-codeflare) - OpenShift AI 上分布式批量推理的企业级方案。 `Article` `EN`
- [inovex: Efficient Prompt Processing with Ray & vLLM](https://www.inovex.de/de/blog/llm-batch-processing-with-ray-vllm-gpu-efficiency-data-privacy/) - 离线批量推理的 config 配置与实用抽象层。 `Article` `EN`
- [YouTube: Scaling LLM Batch Inference with Ray Data & vLLM](https://www.youtube.com/watch?v=_rEsLo21WvE) - 高吞吐批量推理的可视化讲解。 `Video` `EN`

## Inference Frameworks & Comparisons

- [SGLang](https://github.com/sgl-project/sglang) - UC Berkeley 新一代推理框架，RadixAttention 自动 KV cache 复用，10k+ stars。 `Repo` `EN`
- [llama.cpp](https://github.com/ggerganov/llama.cpp) - C++ 推理，CPU/GPU 混合，GGUF 量化格式。 `Repo` `EN`
- [LLM Inference Optimization - Mithril Forge](https://mithrilforge.ai/blog/llm-inference-optimization-model-level) - 量化、剪枝、蒸馏和 FlashAttention。 `Article` `EN`
- [NVIDIA: Pruning and Distilling LLMs](https://developer.nvidia.com/blog/pruning-and-distilling-llms-using-nvidia-tensorrt-model-optimizer/) - TensorRT 实用步骤。 `Article` `EN`
- [Comparing Top 6 Inference Runtimes 2025 - MarkTechPost](https://www.marktechpost.com/2025/11/07/comparing-the-top-6-inference-runtimes-for-llm-serving-in-2025/) - vLLM、SGLang、TGI 等推理引擎严格基准测试对比。 `Article` `EN`

**Quick Reference:** vLLM（高吞吐在线服务）| SGLang（RadixAttention + 结构化生成）| llama.cpp（本地/边缘推理）| TensorRT-LLM（极致性能）| TGI（Hugging Face 官方）

## Production Deployment & Observability

- [Langfuse](https://github.com/langfuse/langfuse) - LLM 可观测性事实标准开源工具：追踪、Prompt 管理、评估、成本追踪。 `Repo` `EN`
- [Top 10 LLM Observability Tools Guide 2025](https://langwatch.ai/blog/top-10-llm-observability-tools-complete-guide-for-2025) - Langfuse、LangWatch、Opik、Datadog、Phoenix 等可观测性工具全面对比。 `Article` `EN`

## Key Framework Repositories

| Repo | Purpose |
|------|---------|
| [vllm-project/vllm](https://github.com/vllm-project/vllm) | 高吞吐量推理，PagedAttention |
| [sgl-project/sglang](https://github.com/sgl-project/sglang) | RadixAttention，结构化生成 |
| [ggerganov/llama.cpp](https://github.com/ggerganov/llama.cpp) | C++ 推理，CPU/GPU 混合 |
| [ray-project/ray](https://github.com/ray-project/ray) | 分布式批量推理调度 |
| [kserve/kserve](https://github.com/kserve/kserve) | Kubernetes 原生模型服务 |
| [langfuse/langfuse](https://github.com/langfuse/langfuse) | LLM 可观测性 |

## Chinese Tutorials

- [掘金：vLLM 分布式推理与性能优化](https://juejin.cn/post/7459279580663971878) - PagedAttention 内存管理和 GPU 显存优化。 `Article` `ZH`
- [火山引擎：企业级 vLLM 部署指南](https://developer.volcengine.com/articles/7537340167746273299) - Ollama vs vLLM 企业级场景选型。 `Article` `ZH`
- [CSDN：vLLM 推理服务部署全链路](https://blog.csdn.net/javastart/article/details/150402300) - 从环境搭建到生产级服务。 `Article` `ZH`
- [知乎：vLLM 本地部署全流程，性能提升 23 倍](https://zhuanlan.zhihu.com/p/1950250893325862339) - 完整部署教程及性能优化。 `Article` `ZH`
- [Hyper.ai：vLLM 实战教程汇总](https://hyper.ai/cn/news/39214) - 环境配置到模型部署的完整入门。 `Article` `ZH`
- [知乎：解锁两大推理模式，批量处理与实时服务](https://zhuanlan.zhihu.com/p/1964030627771823918) - 离线批量 vs 在线服务两种模式详解。 `Article` `ZH`
- [火山引擎：Ray 中 vLLM 推理结果流式写入 parquet](https://www.volcengine.com/article/48274) - GPU 处理完一批 CPU 立刻落盘，不占内存。 `Article` `ZH`
- [阿里云：Ray Data 和 Ray Serve 原生 LLM API](https://developer.aliyun.com/article/1680230) - Ray 框架如何简化 LLM 批量推理。 `Article` `ZH`

## Learning Path

| Stage | Resource | Focus |
|-------|----------|-------|
| Theory | vLLM 论文 + PagedAttention First Principles | PagedAttention/Continuous Batching 原理 |
| Comparison | PagedAttention vs vLLM vs SGLang 对比 + RunPod 指南 | 推理优化技术全景 |
| Deployment | vLLM 官方文档 + SitePoint/Introl 生产部署指南 | 单机到多 GPU 部署 |
| Kubernetes | KServe + llm-d + Red Hat 分布式推理 | K8s 多节点生产架构 |
| Batch | vLLM Offline Inference + Ray Data 官方文档 | 离线批量推理基础 |
| Scale | Anyscale 2x 博客 + Red Hat CodeFlare 方案 | 大规模分布式批量推理 |
| Tuning | vLLM Optimization Docs + 参数调优 Medium | 吞吐与延迟参数调优 |
| Monitoring | Langfuse + Observability 工具对比 | 生产可观测性 |
