# Awesome AI Agents

> A curated list of AI agents, frameworks, tools, and tutorials. Build autonomous AI agents that can think, plan, and act.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/pyshine-labs/awesome-ai-agents?style=social)](https://github.com/pyshine-labs/awesome-ai-agents/stargazers)
[![License: CC0](https://img.shields.io/badge/License-CC0-green.svg)](LICENSE)
[![Tutorials: 85+](https://img.shields.io/badge/Tutorials-85%2B-blue)](https://pyshine.com)

AI agents are autonomous systems that perceive their environment, make decisions, and take actions to achieve goals. This list covers everything you need to build, deploy, and understand AI agents.

Maintained by **[PyShine](https://pyshine.com)** -- 85+ free AI agent tutorials.

## Contents

- [Frameworks](#frameworks)
- [Agent Libraries](#agent-libraries)
- [Autonomous Agents](#autonomous-agents)
- [Coding Agents](#coding-agents)
- [Research Agents](#research-agents)
- [Web Agents](#web-agents)
- [Multi-Agent Systems](#multi-agent-systems)
- [LLM Providers](#llm-providers)
- [Tools & Integrations](#tools--integrations)
- [Memory & Knowledge](#memory--knowledge)
- [Evaluation & Observability](#evaluation--observability)
- [Tutorials](#tutorials)
- [Books](#books)
- [Papers](#papers)
- [Communities](#communities)

---

## Frameworks

Open-source frameworks for building AI agent systems.

### General Purpose

- **[LangGraph](https://github.com/langchain-ai/langgraph)** - Build stateful, multi-actor applications with LLMs. Graph-based agent orchestration.
  - Language: Python/JS
  - Stars: 10k+
  - Best for: Complex agent workflows with state management

- **[CrewAI](https://github.com/crewAIInc/crewAI)** - Framework for orchestrating role-playing, autonomous AI agents.
  - Language: Python
  - Stars: 25k+
  - Best for: Multi-agent collaboration with distinct roles

- **[AutoGen](https://github.com/microsoft/autogen)** - Microsoft's framework for building multi-agent conversational systems.
  - Language: Python
  - Stars: 35k+
  - Best for: Code generation, multi-agent conversations

- **[Semantic Kernel](https://github.com/microsoft/semantic-kernel)** - Microsoft's SDK for integrating AI services with conventional programming languages.
  - Language: C#/Python/Java
  - Stars: 22k+
  - Best for: Enterprise integrations

- **[LlamaIndex](https://github.com/run-llama/llama_index)** - Data framework for LLM applications with agent capabilities.
  - Language: Python/TS
  - Stars: 35k+
  - Best for: RAG-powered agents

- **[Haystack](https://github.com/deepset-ai/haystack)** - Deepset's framework for building LLM applications and agents.
  - Language: Python
  - Stars: 18k+
  - Best for: Production-grade NLP pipelines

### Lightweight / Composable

- **[Pydantic AI](https://github.com/pydantic/pydantic-ai)** - Type-safe agent framework from the Pydantic team.
  - Language: Python
  - Best for: Type-safe, production agents

- **[Atomic Agents](https://github.com/BrainBlend-AI/atomic-agents)** - Modular, atomic agent building blocks.
  - Language: Python
  - Best for: Custom agent architectures

- **[ControlFlow](https://github.com/PrefectHQ/controlflow)** - Prefect's framework for building agentic AI workflows.
  - Language: Python
  - Best for: Workflow orchestration

### Web Agent Frameworks

- **[Browser Use](https://github.com/browser-use/browser-use)** - Make AI agents that can browse the web.
  - Language: Python
  - Stars: 50k+
  - Best for: Web automation agents

- **[Stagehand](https://github.com/browserbase/stagehand)** - AI browser automation framework.
  - Language: Python/TS
  - Best for: Production web scraping

---

## Agent Libraries

Low-level libraries for building custom agents.

- **[LangChain](https://github.com/langchain-ai/langchain)** - The original LLM application framework. Tools, chains, agents.
- **[OpenAI Swarm](https://github.com/openai/swarm)** - OpenAI's experimental lightweight multi-agent orchestration.
- **[OpenAI Agents SDK](https://github.com/openai/openai-agents-python)** - OpenAI's production agent SDK (successor to Swarm).
- **[Google ADK](https://github.com/google/adk-python)** - Google's Agent Development Kit.
- **[AWS Strands Agents](https://github.com/strands-agents/sdk-python)** - AWS's model-agnostic agent SDK.

---

## Autonomous Agents

Notable autonomous agent projects and experiments.

- **[AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** - The original "AI that can do anything" agent.
- **[BabyAGI](https://github.com/yoheinakajima/babyagi)** - Task-driven autonomous agent.
- **[AgentGPT](https://github.com/reworkd/AgentGPT)** - Web-based autonomous agent platform.
- **[SuperAGI](https://github.com/TransformerOptimus/SuperAGI)** - Open-source autonomous agent framework.
- **[Devika](https://github.com/stitionai/devika)** - AI software engineer (open-source Devin alternative).

---

## Coding Agents

AI agents that write, review, and debug code.

- **[Aider](https://github.com/Aider-AI/aider)** - AI pair programmer in your terminal. Works with git.
  - Stars: 25k+
  - Supports: Claude, GPT-4, DeepSeek, local models

- **[Continue](https://github.com/continuedev/continue)** - Open-source AI code assistant for VS Code and JetBrains.
  - Stars: 22k+

- **[Cline](https://github.com/cline/cline)** - Autonomous coding agent in VS Code.
  - Stars: 40k+

- **[OpenHands](https://github.com/All-Hands-AI/OpenHands)** - Open-source AI software engineer (formerly OpenDevin).
  - Stars: 50k+

- **[SWE-agent](https://github.com/princeton-nlp/SWE-agent)** - Princeton's agent that fixes GitHub issues.
  - Stars: 15k+

- **[Claude Code](https://docs.anthropic.com/en/docs/claude-code)** - Anthropic's official CLI agent.
- **[Cursor](https://cursor.com)** - AI-first code editor.
- **[Windsurf](https://codeium.com/windsurf)** - AI IDE with Cascade agent.

**Tutorials:**
- [Using Claude Code Agents Effectively](https://pyshine.com/Learn-Claude-Code-Nano-Agent-Harness/)
- [Building a Simple AI Coding Agent in Python](https://pyshine.com/Opencode-Open-Source-Coding-Agent/)

---

## Research Agents

Agents that search the web, read papers, and synthesize knowledge.

- **[GPT Researcher](https://github.com/assafelovic/gpt-researcher)** - Autonomous agent for comprehensive research reports.
- **[STORM](https://github.com/stanford-oval/storm)** - Stanford's system for generating Wikipedia-style articles.
- **[PaperQA](https://github.com/whitead/paper-qa)** - AI for answering questions from scientific papers.
- **[OpenResearcher](https://github.com/future-architect/open-researcher)** - Open-source research assistant.

---

## Web Agents

Agents that browse and interact with web pages.

- **[Browser Use](https://github.com/browser-use/browser-use)** - Python library for AI web agents.
- **[Skyvern](https://github.com/Skyvern-AI/skyvern)** - AI agent for browser automation.
- **[LaVague](https://github.com/lavague-ai/LaVague)** - Web agent framework.
- **[WebVoyager](https://github.com/MinorJerry/WebVoyager)** - Web navigation agent.

**Tutorials:**
- [Building a Web Scraping AI Agent](https://pyshine.com/Scrapling-Adaptive-Web-Scraping-AI-Element-Tracking/)
- [AI Agent that Browses the Web with Playwright](https://pyshine.com/Agent-Browser-Browser-Automation-CLI-for-AI-Agents/)

---

## Multi-Agent Systems

Frameworks and projects for multiple cooperating agents.

- **[CrewAI](https://github.com/crewAIInc/crewAI)** - Role-based multi-agent collaboration.
- **[AutoGen](https://github.com/microsoft/autogen)** - Conversational multi-agent system.
- **[ChatDev](https://github.com/OpenBMB/ChatDev)** - Virtual software company with multiple agents.
- **[MetaGPT](https://github.com/geekan/MetaGPT)** - Multi-agent framework for software development.
- **[Camel](https://github.com/camel-ai/camel)** - Role-playing multi-agent framework.
- **[Agno](https://github.com/phidatahq/phidata)** - Build multi-modal agents (formerly Phidata).

**Tutorials:**
- [Multi-Agent System with CrewAI](https://pyshine.com/CrewAI-Multi-Agent-Orchestration-Framework/)
- [Build a Team of AI Agents with AutoGen](https://pyshine.com/TradingAgents-Multi-Agent-LLM-Trading/)
- [Coding Agents with LangGraph](https://pyshine.com/Oh-My-Pi-AI-Coding-Agent-Terminal/)

---

## LLM Providers

Models that power AI agents.

### Cloud APIs

- **[OpenAI](https://platform.openai.com/)** - GPT-4o, o3, GPT-5
- **[Anthropic](https://www.anthropic.com/)** - Claude 4.5 Sonnet, Opus
- **[Google](https://ai.google.dev/)** - Gemini 2.5 Pro/Flash
- **[Mistral](https://mistral.ai/)** - Mistral Large, Codestral
- **[Cohere](https://cohere.com/)** - Command R+
- **[Groq](https://groq.com/)** - Fast inference for open models
- **[Together AI](https://www.together.ai/)** - Open model hosting
- **[Fireworks](https://fireworks.ai/)** - Fast inference platform

### Local / Open Models

- **[Ollama](https://ollama.com/)** - Run LLMs locally. Cloud option available.
  - Popular models: deepseek-v4, glm-5.2, qwen3.5, gemma4, kimi-k2.6
- **[vLLM](https://github.com/vllm-project/vllm)** - High-throughput inference server.
- **[llama.cpp](https://github.com/ggerganov/llama.cpp)** - C++ inference for consumer hardware.
- **[LM Studio](https://lmstudio.ai/)** - Desktop app for local LLMs.
- **[Hugging Face](https://huggingface.co/)** - Model hub with inference API.

**Tutorials:**
- [Ollama Cloud Models Comparison](https://pyshine.com/Ollama-Cloud-Models-SVG-Comparison-Flying-Helicopter/)
- [Running Local LLMs with Ollama](https://pyshine.com/ollama-run-llms-locally-with-ease/)
- [Building Agents with Open Source Models](https://pyshine.com/Craft-Agents-Open-Source-AI-Agent-Platform/)

---

## Tools & Integrations

Tools that agents can use to interact with the world.

### Payments

- **[Agent Payment Node](https://github.com/nuanu-ai/agent-payment-node)** - Local macOS CLI and stdio MCP payments with foreground owner approval for signing.

### Search

- **[Tavily](https://tavily.com/)** - AI search API built for agents.
- **[Brave Search API](https://brave.com/search/api/)** - Web search for agents.
- **[Serper](https://serper.dev/)** - Google search API.
- **[DuckDuckGo Search](https://github.com/deedy5/duckduckgo_search)** - Free search.

### Code Execution

- **[E2B](https://e2b.dev/)** - Sandboxed code execution for agents.
- **[Daytona](https://daytona.io/)** - Secure sandbox environments.
- **[Jupyter Kernel](https://jupyter.org/)** - IPython kernel for code execution.

### File & Document

- **[Unstructured](https://github.com/Unstructured-IO/unstructured)** - Parse PDFs, docs, emails.
- **[LlamaParse](https://github.com/run-llama/llama_parse)** - PDF parsing optimized for RAG.

### Communication

- **[Resend](https://resend.com/)** - Email API.
- **[Twilio](https://twilio.com/)** - SMS/voice.
- **[Slack API](https://api.slack.com/)** - Slack integration.
- **[Discord.py](https://github.com/Rapptz/discord.py)** - Discord bots.

**Tutorials:**
- [Giving AI Agents Tools to Use](https://pyshine.com/Mercury-Agent-Soul-Driven-AI-with-Permission-Hardened-Tools/)

---

## Memory & Knowledge

Systems for agent memory and knowledge management.

### Vector Databases

- **[Pinecone](https://pinecone.io/)** - Managed vector database.
- **[Weaviate](https://weaviate.io/)** - Open-source vector search.
- **[Chroma](https://www.trychroma.com/)** - Open-source embedding database.
- **[Qdrant](https://qdrant.tech/)** - Vector search engine.
- **[Milvus](https://milvus.io/)** - Scalable vector database.
- **[pgvector](https://github.com/pgvector/pgvector)** - PostgreSQL vector extension.

### Knowledge Graphs

- **[Neo4j](https://neo4j.com/)** - Graph database for knowledge graphs.
- **[LlamaIndex Knowledge Graph](https://docs.llamaindex.ai/en/stable/examples/query_engine/knowledge_graph_query_engine/)** - KG support in LlamaIndex.

### Memory Frameworks

- **[Mem0](https://github.com/mem0ai/mem0)** - Memory layer for AI applications.
- **[Letta](https://github.com/letta-ai/letta)** - Stateful agents with memory (formerly MemGPT).
- **[Zep](https://github.com/getzep/zep)** - Long-term memory for AI agents.

**Tutorials:**
- [Adding Memory to AI Agents](https://pyshine.com/AgentMemory-Persistent-Memory-AI-Coding-Agents/)
- [RAG with Vector Database Tutorial](https://pyshine.com/RAGFlow-Open-Source-RAG-Engine-Deep-Document-Understanding/)

---

## Evaluation & Observability

Tools to monitor and evaluate agent performance.

- **[LangSmith](https://smith.langchain.com/)** - LangChain's observability platform.
- **[Langfuse](https://langfuse.com/)** - Open-source LLM observability.
- **[Phoenix](https://github.com/Arize-ai/phoenix)** - Arize's AI observability.
- **[Helicone](https://helicone.ai/)** - LLM monitoring.
- **[Braintrust](https://braintrustdata.com/)** - Evals for AI applications.
- **[Ragas](https://github.com/explodinggradients/ragas)** - RAG evaluation framework.

---

## Tutorials

Free, in-depth tutorials on AI agents from **[PyShine](https://pyshine.com)**.

### Getting Started

- [Introduction to AI Agents](https://pyshine.com/12-Factor-Agents-Reliable-LLM-Powered-Software/)
- [Building Your First AI Agent](https://pyshine.com/Build-Your-Own-X-Master-Programming-by-Recreating-Technologies/)
- [AI Agent Architecture Explained](https://pyshine.com/12-Factor-Agents-Reliable-LLM-Powered-Software/)

### Framework-Specific

- [LangChain Agent Tutorial](https://pyshine.com/LangChain-Agent-Engineering-Platform/)
- [CrewAI Multi-Agent Tutorial](https://pyshine.com/CrewAI-Multi-Agent-Orchestration-Framework/)
- [AutoGen Tutorial](https://pyshine.com/TradingAgents-Multi-Agent-LLM-Trading/)
- [LangGraph Tutorial](https://pyshine.com/Oh-My-Pi-AI-Coding-Agent-Terminal/)
- [Pydantic AI Tutorial](https://pyshine.com/Learn-FastAPI-in-One-Post-Complete-Tutorial-Pydantic-Async-Dependency-Injection-Quick-Start/)

### Coding Agents

- [How to Use Claude Code as an Agent](https://pyshine.com/Learn-Claude-Code-Nano-Agent-Harness/)
- [Build a Simple Coding Agent](https://pyshine.com/Opencode-Open-Source-Coding-Agent/)
- [Building a Code Review Agent](https://pyshine.com/Claw-Code-Rust-AI-Agent-Harness/)

### Advanced Topics

- [Adding Memory to AI Agents](https://pyshine.com/AgentMemory-Persistent-Memory-AI-Coding-Agents/)
- [RAG Tutorial with Vector Database](https://pyshine.com/RAGFlow-Open-Source-RAG-Engine-Deep-Document-Understanding/)
- [AI Agent Tools Tutorial](https://pyshine.com/Mercury-Agent-Soul-Driven-AI-with-Permission-Hardened-Tools/)
- [Web Scraping AI Agent](https://pyshine.com/Scrapling-Adaptive-Web-Scraping-AI-Element-Tracking/)
- [AI Web Browsing Agent with Playwright](https://pyshine.com/Agent-Browser-Browser-Automation-CLI-for-AI-Agents/)

### Production

- [Deploying AI Agents to Production](https://pyshine.com/DSPy-Agent-Skills-Production-Grade-DSPy-3.2-Skills-for-Coding-Agents/)
- [Scaling AI Agents with FastAPI](https://pyshine.com/Learn-FastAPI-in-One-Post-Complete-Tutorial-Pydantic-Async-Dependency-Injection-Quick-Start/)
- [AI Agent Observability](https://pyshine.com/Learn-Observability-in-One-Post-Complete-Tutorial-Metrics-Logs-Traces-OpenTelemetry-Quick-Start/)
- [Security for AI Agents](https://pyshine.com/Anthropic-Cybersecurity-Skills-AI-Agent-Security-Frameworks/)

### Open Source Models

- [Run Local LLMs with Ollama](https://pyshine.com/ollama-run-llms-locally-with-ease/)
- [Build Agents with Open Source Models](https://pyshine.com/Craft-Agents-Open-Source-AI-Agent-Platform/)
- [Ollama Cloud Models SVG Benchmark](https://pyshine.com/Ollama-Cloud-Models-SVG-Comparison-Flying-Helicopter/)

**See all 85+ AI agent tutorials at [pyshine.com](https://pyshine.com)**

---

## Books

- **[Building LLM Applications](https://pyshine.com)** - Comprehensive guide to LLM apps (coming soon)
- **[Designing Machine Learning Systems](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/)** - Chip Huyen
- **[AI Engineering](https://www.oreilly.com/library/view/ai-engineering/9781098166297/)** - Chip Huyen
- **[Hands-On Large Language Models](https://www.oreilly.com/library/view/hands-on-large-language/9781098150954/)** - Jay Alammar

---

## Papers

Key papers on AI agents.

1. **ReAct: Synergizing Reasoning and Acting in Language Models** - Yao et al., 2022. [Paper](https://arxiv.org/abs/2210.03629)
2. **Toolformer: Language Models Can Teach Themselves to Use Tools** - Schick et al., 2023. [Paper](https://arxiv.org/abs/2302.04761)
3. **Reflexion: Language Agents with Verbal Reinforcement Learning** - Shinn et al., 2023. [Paper](https://arxiv.org/abs/2303.11366)
4. **Generative Agents: Interactive Simulacra of Human Behavior** - Park et al., 2023. [Paper](https://arxiv.org/abs/2304.03442)
5. **AutoGPT: An Autonomous Agent Using LLMs** - Significant Gravitas, 2023. [Repo](https://github.com/Significant-Gravitas/AutoGPT)
6. **MetaGPT: Meta Programming for Multi-Agent Collaborative Framework** - Hong et al., 2023. [Paper](https://arxiv.org/abs/2308.00352)
7. **SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering** - Yang et al., 2024. [Paper](https://arxiv.org/abs/2405.15793)
8. **Tree of Thoughts: Deliberate Problem Solving with Large Language Models** - Yao et al., 2023. [Paper](https://arxiv.org/abs/2305.10601)

---

## Communities

- **[PyShine Discord](https://pyshine.com)** - Join our community of AI builders
- **[r/LocalLLaMA](https://reddit.com/r/LocalLLaMA)** - Local LLM community
- **[r/AIagents](https://reddit.com/r/AIagents)** - AI agent discussions
- **[LangChain Discord](https://discord.gg/langchain)** - LangChain community
- **[AutoGen Discord](https://discord.gg/autogen)** - AutoGen community
- **[Hugging Face Discord](https://discord.gg/hugging-face)** - HF community

---

## Contributing

Contributions welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) first.

To add a project:
1. Fork this repo
2. Add your entry to the appropriate section (alphabetical order)
3. Include: name, link, short description, language, stars (optional)
4. Submit a pull request

---

## License

[CC0 1.0 (Public Domain)](LICENSE)

## About

Maintained by **[PyShine](https://pyshine.com)** -- 85+ free AI agent tutorials and 600+ programming tutorials.

- Website: [https://pyshine.com](https://pyshine.com)
- GitHub: [pyshine-labs](https://github.com/pyshine-labs)
- Twitter: [@pyshine](https://twitter.com/pyshine)

---

**Found this useful?** Star this repo and share with fellow AI builders!

**Want to learn AI agents from scratch?** Start with [PyShine's AI Agent tutorials](https://pyshine.com).
