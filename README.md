# Awesome-AI-Developer-Resources

# Awesome-AI-Developer-Resources

# Top AI Developer Resources Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Cookbooks, Learning Platforms & Production Implementation Guides*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Developer Resources**. These tools provide the recipes, guides, and hands-on environments developers need to go from API reference to production—covering RAG pipelines, tool use, agent orchestration, and evaluation patterns.

**Examples** include OpenAI Cookbook, Anthropic Cookbook, DeepLearning.AI, LangChain Hub, Hugging Face Docs, Cohere LLM University, AWS Bedrock Workshop, Google Cloud Skills Boost, Kaggle Learn, and Pinecone Learn (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, reproducible examples, and open learning infrastructure—ideal for AI engineers, technical teams, and developers seeking transparent, vendor-independent implementation guidance.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[DeepLearning.AI](https://www.deeplearning.ai/)**  
  **The most trusted AI education platform** with 150+ courses co-created with OpenAI, Anthropic, Google, AWS, Microsoft, Meta, NVIDIA, Hugging Face, and LangChain . **10M+ learners worldwide** with curriculum from the source. Courses pair video with hands-on coding labs in browser-based environments . Team plan at **$25/user/month** (10-100 seats) .

- **[Cohere LLM University](https://cohere.com/developers)**  
  Cohere's learning hub for enterprise AI mastery. Features detailed resources, step-by-step guides, and expert-led courses for developers and technical professionals . No-code Playground for API testing .

- **[Google Cloud Skills Boost](https://www.cloudskillsboost.google/)**  
  **The most comprehensive cloud learning catalog** with **700+ learning activities** including short labs and multi-module courses . **Hands-on labs provide temporary credentials to real cloud resources** for practical learning . Skill badges awarded upon completion .

- **[Kaggle Learn](https://www.kaggle.com/learn)**  
  **The best starting point for data science fundamentals** with **17 free courses** covering Python, Pandas, Machine Learning, Deep Learning, SQL, and Feature Engineering . All courses use Kaggle notebooks with completion certificates . **Recommended as the first stop for beginners** .

- **[Pinecone Learn](https://www.pinecone.io/learn/)**  
  Pinecone's educational hub for vector databases and RAG patterns. Features sample applications and Jupyter Notebooks for hands-on learning .

## Open-Source GitHub Projects

- **[OpenAI Cookbook](https://github.com/openai/openai-cookbook)**  
  **The most widely used AI developer resource** (58,567 GitHub stars) . **The canonical source for OpenAI API examples and guides**—code examples were moved here from the OpenAI Python library in July 2022 to keep the library simple . **The first place to look for working code patterns** before building custom flows.

- **[Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook)**  
  **The primary resource for teams integrating Claude into production** . **Copy-able code snippets** you can easily integrate into your own projects . Features **tool use patterns** (customer service agent, calculator, SQL queries), **RAG pipelines** (Pinecone, Wikipedia, web search), **citations**, **sub-agents** (Haiku as sub-agent with Opus), **embeddings** (Voyage AI), and **vision** (getting started and best practices) . **First-party authenticity** from Anthropic engineering team with runnable Jupyter notebooks .

- **[LangChain Hub](https://smith.langchain.com/hub)**  
  **The community hub for sharing prompts, chains, and agents** . **Version-controlled prompts**—each commit adds a new version, so you can easily access previous versions . **Playground integration**—click "Try it" to interact with prompts right from the Hub . **SDK for programmatic download and upload** . Built into LangSmith for full read/write permissions; read-only without .

- **[Hugging Face Hub](https://github.com/huggingface/huggingface_hub)**  
  **The central hub for models, datasets, and Spaces** with **huggingface_hub Python library** for programmatic interaction . Features model/dataset download, search, and inference across multiple services . **The de facto standard for sharing AI artifacts**—inspired LangChainHub's design .

- **[AWS Bedrock Workshop](https://github.com/aws-samples/amazon-bedrock-workshop)**  
  **The most comprehensive workshop for building with Amazon Bedrock** (1,406 GitHub stars) . **CDK scaffolding for rapid prototyping** of AI-powered applications using Bedrock Knowledge Bases and Agents . **Three use case templates** (Chatbot, Text2SQL) with React frontend and CDK infrastructure . **Production-ready infrastructure templates** for proof-of-concept development .

- **[Pinecone Examples](https://github.com/pinecone-io/examples)**  
  **Sample applications and Jupyter Notebooks for vector databases** . **Hands-on with Pinecone and common AI patterns**—run, download, study, and modify .

- **[OpenAI Agents SDK (JS/TS)](https://github.com/openai/openai-agents-js)**  
  **The official TypeScript baseline for agent orchestration** (3,203 GitHub stars, MIT) . **Provider-agnostic**—supports OpenAI APIs and more . Core concepts: **Agents** (LLMs with instructions, tools, guardrails), **Sandbox Agents** (filesystem workspace for longer tasks), **Realtime Agents** (spoken interactions), **Handoffs** (delegating to other agents), **Guardrails** (input/output validation), **Sessions** (conversation history management), and **Tracing** (built-in tracking for debugging) .

- **[LangChain](https://github.com/langchain-ai/langchain)**  
  **The most widely adopted framework for building LLM applications** . **`create_agent` provides a minimal, highly configurable agent harness**—compose exactly the agent your use case needs from model, tools, prompt, and middleware . Supports OpenAI, Anthropic, Google, OpenRouter, Fireworks, Baseten, and Ollama . **LangSmith for tracing, debugging, and evaluation** .

- **[TRL (Transformers Reinforcement Learning)](https://github.com/huggingface/trl)**  
  **The standard post-training framework for foundation models** . **Full post-training pipeline** with SFT, GRPO, DPO, and RLHF . **Scales from a single GPU to multi-node clusters** . **vLLM acceleration** for RL-based training methods .

- **[Hugging Face Transformers](https://github.com/huggingface/transformers)**  
  **The most widely used model library** with 500,000+ model checkpoints on the Hub. Features text, vision, audio, and multimodal support with a unified API.

- **[Model Context Protocol (MCP)](https://modelcontextprotocol.io/)**  
  **The open standard for connecting LLMs to external data sources and tools** . **JSON-RPC 2.0 based** with Resources, Prompts, and Tools . **Extensions include Tasks** (async execution), **Skills over MCP** (structured instructions for agents), and **MCP Apps** (interactive UI elements) . **The foundation for the agentic ecosystem**—adopted by Claude Code, Cursor, and major AI platforms .

- **[AgentCompass](https://github.com/open-compass/AgentCompass)**  
  **Unified open-source evaluation infrastructure for agents** (Apache-2.0, EMNLP 2026 Demo Track) . **30+ public benchmarks and 10+ agent harnesses** including Claude Code, Codex, OpenHands, and OpenClaw . **Composable architecture** decouples Model, Benchmark, Harness, and Environment . **Traceable and reproducible** with trajectory recording, tool calls, and failure analysis .

- **[ContextForge Eval](https://pypi.org/project/contextforge-eval/)**  
  **Open-source evaluation framework for agentic systems** . **Framework-agnostic**—adapters translate framework events into traces, graders operate only on traces . **Memory hygiene detection** catches stale context, missed facts, and contradictory fragments . **Deterministic graders** for fast, reproducible checks; **LLM-as-judge** for qualitative assessment .

- **[Claude Code Best Practices](https://code.claude.com/docs/en/best-practices)**  
  **The canonical guide for Claude Code adoption** . **CLAUDE.md as code**—review when things go wrong, prune regularly, test changes by observing behavior shifts . **Include** (Bash commands Claude can't guess, code style rules that differ from defaults, testing instructions, repository etiquette, architectural decisions) **Exclude** (anything Claude can figure out, standard conventions, detailed API docs, frequently changing info) . **Permissions and sandboxing** reduce prompts without giving up control . **MCP servers** connect Claude to issue trackers, databases, monitoring data, and Figma .

### Additional Strong Open-Source Options

- **[Gemini API](https://ai.google.dev/gemini-api/docs)** — Google's fastest path from prompt to production with Gemini, Veo, and Nano Banana . Interactions API for building conversational agents .
- **[Gemini Enterprise Agent Platform](https://docs.cloud.google.com/gemini-enterprise-agent-platform)** — Get started with Gemini 4 Argon for deep work in coding, finance, legal, cybersecurity, and science . Thinking levels (LOW, MEDIUM, HIGH), implicit context caching, and agentic video understanding .
- **[Llama 4 SGLang Documentation](https://docs.sglang.io/cookbook/autoregressive/Meta/Llama4)** — Llama 4 Scout and Maverick deployment guides with SGLang . Speed benchmarks for latency-optimized, balanced, and throughput-optimized configurations .
- **[awesom-awesome-awesome](https://github.com/ishandutta2007/awesome-awesome-awesome)** — Curated lists for engineers and AI researchers .
- Community **n8n** workflows for AI resource aggregation and learning path automation.

**Frameworks for building custom systems**: Combine **OpenAI Cookbook** and **Anthropic Cookbook** for implementation patterns with **LangChain Hub** for reusable prompts, **Hugging Face Hub** for models and datasets, **MCP** for tool integration, **AgentCompass** for evaluation, and **TRL** for post-training—creating a comprehensive AI developer resource stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AI developer resources are **starting points for production engineering**, not production-ready systems. Cookbook examples may lack production-grade monitoring, logging, or security hardening .
- **First-party cookbooks are the most reliable source.** OpenAI Cookbook (58,567 stars) and Anthropic Cookbook provide runnable code from the model creators . **Third-party frameworks change faster and may have version-specific examples.**
- **Evaluation is the missing discipline.** Most AI teams deploy without systematic evaluation. AgentCompass provides 30+ benchmarks and 10+ harnesses . ContextForge catches memory issues, loops, and context bloat before production . **Treat evaluation as infrastructure, not an afterthought.**
- **CLAUDE.md is a compounding asset.** The best practices guide emphasizes treating it like code—review when things go wrong, prune regularly, test changes by observing behavior . **Bloated CLAUDE.md files cause Claude to ignore your actual instructions** .
- **MCP is the emerging integration standard.** The Model Context Protocol provides a standardized way to connect LLMs with external data and tools . **Learn it now—it's becoming the USB-C of AI integrations.**
- Self-hosted open-source solutions require proper security hardening, API key management, and ongoing maintenance. Always validate examples against current model versions before production deployment.

---

**Made for AI engineers, technical teams, and developers building transparent AI resource solutions.**  
Let's make AI Developer Resources more open, data-driven, and production-ready.
