# AI Resource Index

A compact, maintained index of AI research, models, tools, and infrastructure.
The focus is on resources that are useful for builders: model releases,
evaluation trackers, agent frameworks, local inference stacks, and practical
learning material.

Last reviewed: June 2026

## How to Use This Repository

- Start with the trackers if you want a fast view of the current landscape.
- Use the model sections to compare frontier APIs, open-weight models, and local
  deployment options.
- Treat links as starting points, not endorsements. Always verify model licenses,
  data-use terms, pricing, and benchmark methodology before production use.

## Landscape Trackers

- [Papers with Code - SOTA](https://paperswithcode.com/sota): Benchmark and
  task leaderboards across machine learning research.
- [Hugging Face Models](https://huggingface.co/models): Searchable model hub for
  open and commercial model releases.
- [LMSYS Chatbot Arena](https://lmarena.ai/): Community-driven model comparison
  and leaderboard.
- [Artificial Analysis](https://artificialanalysis.ai/): Independent model
  quality, price, latency, and throughput comparisons.
- [Epoch AI](https://epoch.ai/): Research on AI trends, compute, scaling, and
  forecasting.

## Frontier Model Providers

- [OpenAI GPT-5.2](https://openai.com/index/introducing-gpt-5-2/): Frontier
  model series for professional knowledge work, coding, tools, and long-running
  agents.
- [OpenAI GPT-5 for developers](https://openai.com/index/introducing-gpt-5-for-developers/):
  Developer-focused notes on coding, tool use, reasoning effort, verbosity, and
  API model sizes.
- [Anthropic Claude 4](https://www.anthropic.com/news/claude-4): Claude Opus 4
  and Sonnet 4 release notes for coding, advanced reasoning, and agent workflows.
- [Claude Opus 4.5](https://www.anthropic.com/news/claude-opus-4-5): Anthropic's
  later Opus 4 generation model release.
- [Google Gemini](https://deepmind.google/technologies/gemini/): Google's
  multimodal frontier model family.
- [Mistral AI News](https://mistral.ai/news/): Mistral model and product
  announcements.

## Open-Weight and Local Models

- [DeepSeek-R1](https://huggingface.co/deepseek-ai/DeepSeek-R1): Open-weight
  reasoning model and distilled variants.
- [Qwen3](https://qwenlm.github.io/blog/qwen3/): Alibaba's hybrid thinking and
  non-thinking model family, including dense and MoE variants.
- [Llama 4](https://ai.meta.com/blog/llama-4-multimodal-intelligence/): Meta's
  natively multimodal Llama 4 model family.
- [Gemma 3](https://blog.google/innovation-and-ai/technology/developers-tools/gemma-3/):
  Google's open model family for local and cloud deployment.
- [Mistral 3](https://mistral.ai/news/mistral-3/): Mistral's open model family
  covering small and large deployments.
- [Phi models](https://huggingface.co/microsoft): Microsoft's small language
  model family on Hugging Face.

## Agents and Tool Use

- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python):
  Lightweight framework for multi-agent workflows, tools, handoffs, guardrails,
  sessions, and tracing.
- [LangGraph](https://github.com/langchain-ai/langgraph): Stateful, durable
  agent workflows from the LangChain ecosystem.
- [AutoGen](https://github.com/microsoft/autogen): Microsoft's programming
  framework for agentic AI.
- [CrewAI](https://github.com/crewAIInc/crewAI): Multi-agent orchestration for
  role-based collaborative agents.
- [LlamaIndex](https://www.llamaindex.ai/): Data and retrieval framework for
  production RAG and agent workflows.
- [browser-use](https://github.com/browser-use/browser-use): Browser automation
  for AI agents.
- [Model Context Protocol servers](https://github.com/modelcontextprotocol/servers):
  Reference servers for connecting models and agents to external tools and data.

## Inference and Deployment

- [vLLM](https://github.com/vllm-project/vllm): High-throughput inference and
  serving engine for LLMs.
- [SGLang](https://github.com/sgl-project/sglang): Serving framework for large
  language and multimodal models.
- [llama.cpp](https://github.com/ggml-org/llama.cpp): C/C++ inference stack for
  local and edge LLM deployment.
- [Ollama](https://github.com/ollama/ollama): Local model runner and model
  management tool.
- [MLX](https://github.com/ml-explore/mlx): Machine learning framework optimized
  for Apple silicon.
- [NVIDIA open GPU kernel modules](https://github.com/NVIDIA/open-gpu-kernel-modules):
  Open GPU kernel modules for NVIDIA Linux drivers.

## Research and Practical Reading

- [DeepSeek-R1 paper](https://arxiv.org/abs/2501.12948): Reasoning capability via
  reinforcement learning.
- [SIMA from Google DeepMind](https://deepmind.google/discover/blog/sima-generalist-ai-agent-for-3d-virtual-environments/):
  Generalist AI agent work for 3D virtual environments.
- [SoccerBots from Google Research](https://www.science.org/doi/10.1126/scirobotics.adi8022):
  Robotics and multi-agent learning in soccer.
- [LoRA training guide](https://civitai.com/articles/3105/essential-to-advanced-guide-to-training-a-lora):
  Practical introduction to training LoRA adapters.

## Multimodal and Media Tools

- [Hugging Face Diffusers](https://github.com/huggingface/diffusers): Image,
  video, and audio generation pipelines.
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI): Node-based interface for
  diffusion and generative media workflows.
- [Whisper](https://github.com/openai/whisper): Speech recognition and
  transcription model.
- [Stable Audio Open](https://huggingface.co/stabilityai/stable-audio-open-1.0):
  Open audio generation model from Stability AI.

## Contribution Guidelines

When adding a resource, prefer links that are:

- Primary sources, official repositories, papers, or well-maintained benchmarks.
- Still active or clearly useful historically.
- Described in one sentence with why the link matters.
- Specific enough to be actionable.

Recommended entry format:

```markdown
- [Name](https://example.com): Why this is useful.
```

## License

This repository is available under the [MIT License](LICENSE).
