# Hi, I'm Michał Wojdylak 👋

**AI Infrastructure Engineer** based in Poznań, Poland. I build production AI systems,
LLM infrastructure, inference platforms and cloud-native ML solutions.

I write about what I learn at **[michalwojdylak.com](https://michalwojdylak.com)**, where every
post links to a repository you can reproduce.

## ✍️ Latest writing

- **[LLM Inference Benchmarks: vLLM vs SGLang vs TensorRT-LLM on a Single L40S](https://michalwojdylak.com/blog/llm-inference-benchmarks-vllm-sglang-tensorrt-llm)**
  Qwen3-32B on one NVIDIA L40S, covering concurrency scaling, long context, quantization and MoE.
  TensorRT-LLM delivers 37% more throughput at concurrency 64. On vLLM, AWQ/GPTQ beat FP8 by 43%.
  An MoE model (Qwen3-30B-A3B) on SGLang reaches 3.6× the throughput of dense 32B.
- **[Hosting Multiple Models on NVIDIA Triton Server Across AWS, Azure, and GCP](https://michalwojdylak.com/blog/hosting-multiple-models-on-nvidia-triton)**
  Consolidating several ONNX models onto one GPU with Triton on SageMaker, Azure ML and Vertex AI
  to cut serving costs.

## 🧰 Projects

| Project | What it is |
|---|---|
| [llm-inference-benchmarks](https://github.com/michalwojdylak/llm-inference-benchmarks) | Reproducible benchmarks of vLLM, SGLang and TensorRT-LLM using NVIDIA AI-Perf |
| [hosting-multiple-models-on-nvidia-triton](https://github.com/michalwojdylak/hosting-multiple-models-on-nvidia-triton) | Notebooks that deploy multi-model Triton endpoints on AWS, Azure and GCP |
| [ai-research-radar](https://github.com/michalwojdylak/ai-research-radar) | Ranks the week's AI news by how many independent newsletters mention each item |
| [personal-website](https://github.com/michalwojdylak/personal-website) | Source of michalwojdylak.com: Next.js, TypeScript, Tailwind CSS and MDX |

## 🔭 Focus areas

- **LLM serving:** vLLM, SGLang, TensorRT-LLM, quantization (FP8, AWQ, GPTQ), MoE
- **Model serving:** NVIDIA Triton Inference Server, ONNX Runtime, TensorRT
- **Cloud ML:** AWS SageMaker, Azure ML, GCP Vertex AI, Docker
- **Inference optimization:** throughput, latency, GPU cost
- **On-device AI:** Apple Silicon

## 📫 Connect

[Website](https://michalwojdylak.com) · [Blog](https://michalwojdylak.com/blog) · [LinkedIn](https://www.linkedin.com/in/michalwojdylak) · [RSS](https://michalwojdylak.com/rss.xml)
