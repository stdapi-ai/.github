# Run OpenAI, Anthropic, Cohere & Ollama Apps on Amazon Bedrock

> **stdapi.ai is discontinued.** v1.20.2 is its final release: no further development or support is planned. The source code stays available under the AGPL-3.0-or-later. See the [release notes](https://stdapi.jgoutin.dev/roadmap/?utm_source=org-profile&utm_medium=repo&utm_campaign=owned-surfaces).

**[stdapi.ai](https://stdapi.jgoutin.dev?utm_source=org-profile&utm_medium=repo&utm_campaign=owned-surfaces)** is a drop-in API gateway that connects your existing OpenAI, Anthropic, Cohere and Ollama-compatible tools to 100+ Amazon Bedrock models. Change one line — your base URL — and your tools reach them via the OpenAI, Anthropic, Cohere or Ollama SDK: LangChain, Open WebUI, Claude Code, n8n, Home Assistant, and hundreds of applications and tools.

### ✨ Why stdapi.ai?

- **🔌 Drop-in replacement** — OpenAI, Anthropic, Cohere and Ollama SDK compatible, works with hundreds of applications and tools
- **🧠 100+ models** — Anthropic Claude, OpenAI GPT and xAI Grok (via Amazon Bedrock Mantle), Moonshot Kimi, MiniMax, DeepSeek, Qwen, GLM, Nova, Llama, Stability AI
- **🗂️ One AWS catalog** — Amazon Bedrock, Bedrock Mantle, Polly, Transcribe and Comprehend are discovered automatically and interchange by name on shared endpoints — no model list to maintain
- **🎨 Not just chat** — Images, video, audio speech/transcription/translation, files, embeddings, moderation and reranking, all under the same standard APIs
- **🔒 Runs in your AWS account** — No third party sits between your users and your models; Amazon Bedrock does not share your prompts with model providers or use them for training. Region allow-lists let you match your own requirements; AWS compliance certifications apply to the AWS services and regions you choose and are not inherited by stdapi.ai
- **🌍 Add a region, add its quota** — Every AWS region carries its own Bedrock quota, and every region you enable adds its own; eligible failures retry in another enabled region
- **💰 Pay only what you use** — Amazon Bedrock rates, 0% markup — Bedrock is billed to you directly by AWS
- **⚡ Advanced Bedrock features** — Reasoning modes, prompt caching, guardrails, prompt routers
- **🧪 Verified, not just documented** — 6,000+ automated test cases against real AWS services, 20 third-party clients driven end to end, 80+ API operations exposed as MCP tools, `<1 ms` gateway overhead

### 💼 Popular Use Cases

**Chat Interfaces** (**Open WebUI**, LibreChat) · **Coding Assistants** (**Claude Code**, **Codex**, **Qwen Code**, **pi**, Cline, OpenCode, Zed) · **Workflow Automation** (**n8n**, Make, Zapier) · **AI Agents** (**OpenClaw**, **Hermes**, **LangChain**, **Pydantic AI**, **Haystack**, LlamaIndex, CrewAI)

**Bold** = driven end to end against a live gateway by the [automated test suite](https://github.com/stdapi-ai/stdapi.ai/tree/main/tests); the others have a documented setup.

### 🚀 Get Started

- **[Try Locally with Docker](https://stdapi.jgoutin.dev/operations_getting_started_local/?utm_source=org-profile&utm_medium=repo&utm_campaign=owned-surfaces)**: run the image locally, [`ghcr.io/stdapi-ai/stdapi.ai-community`](https://github.com/stdapi-ai/stdapi.ai/pkgs/container/stdapi.ai-community), the same hardened image the Terraform module deploys
- **[Terraform / OpenTofu module](https://registry.terraform.io/modules/stdapi-ai/stdapi-ai/aws/latest)**: ECS Fargate deployment of the same hardened image, with HTTPS, WAF and monitoring as opt-ins
- **[Samples repository](https://github.com/stdapi-ai/samples)** — Ready-to-deploy single-region, EU/US multi-region and Open WebUI stacks
- **[Full Documentation](https://stdapi.jgoutin.dev?utm_source=org-profile&utm_medium=repo&utm_campaign=owned-surfaces)** — Guides, API reference, and integration examples
- **[Deployment Guide](https://stdapi.jgoutin.dev/operations_getting_started/?utm_source=org-profile&utm_medium=repo&utm_campaign=owned-surfaces)** — Deploy to AWS with two Terraform commands

### 🏅 AWS Qualified Software

<img src="https://stdapi.jgoutin.dev/styles/aws_qualified_software_badge_light.png" alt="AWS Qualified Software badge" width="120" />

stdapi.ai was approved by AWS as **AWS Qualified Software**, after AWS verified it against its technical and security requirements.

### 📜 License & Publisher

Licensed under the **AGPL-3.0-or-later**.
Published by **[JGoutin-dev SARL](https://jgoutin.dev/)** — [contact us](https://stdapi.jgoutin.dev/contact/?utm_source=org-profile&utm_medium=repo&utm_campaign=owned-surfaces), or open a [GitHub issue](https://github.com/stdapi-ai/stdapi.ai/issues) for bugs and feature requests.
