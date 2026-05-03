# Hi, I'm Elvin 👋

I'm focused on building **useful, trustworthy AI systems** — multi-agent architectures for regulated domains, explainable by construction and auditable end-to-end. That's the work I want to keep moving forward.

By day, Senior Software Engineer at Times Higher Education. Before that, 18 years across the BBC, Samsung, FIFA's official World Cup app, Nando's, and the UK Ministry of Justice. Outside of full-time work, I'm building two things:

### 🤖 Marvin — a self-improving multi-agent system for bank credit decisioning
🌐 [marvinos.uk](https://marvinos.uk/) — Marvin is a real bank credit committee, modeled in software. **Eight specialised agents** organised into **three departments**, each with strict document allowlists and a single responsibility:

- **Department A — Credit Factory (live execution).** Runs synchronously per application, ≤ 60s wall-clock end-to-end. A **Compliance Guardian** screens AML / KYC / sanctions / PEPs and can hard-reject. An **Underwriter** structures the deal and looks for compensating factors. A **Data Quant** runs DSTI, DSCR, scoring, and default probability against methodology thresholds. An **Internal Archivist** is the RAG layer — every other agent queries it for citations, never freelances. An **Orchestrator** chairs the committee, applies a `Law > Policy > Data` conflict tree, and emits an explainable verdict with a HITL flag.
- **Department B — Strategy & Development (brain trust).** An **External Scout** monitors EBA guidelines, BNB наредби, Държавен вестник, ECB / BIS / IMF publications, and open-access textbooks. A **Policy Architect** drafts new internal policies (or rewrites old ones) for operator sign-off, triggered by Scout findings or by the Orchestrator flagging a missing rule.
- **Department C — Evolution (god mode).** **Marvin** itself — the meta-architect the product is named after — watches the other seven agents, reads traces, latency, conflict rates, and hallucination flags, and surfaces system-level findings: bottlenecks, knowledge gaps, prompt drift, draft prompts for entirely new agents.

The whole system is designed to be **explainable by construction, auditable end-to-end, and self-improving** — the policy library stays current, and the agent roster gets challenged by an agent whose only job is to challenge it. This is where most of my AI engineering effort goes: agent contracts, RAG with strict allowlists, structured output, streaming, evaluation against real loan datasets, and the un-glamorous work of making AI systems give answers that hold up in a regulated domain where being wrong has real financial consequences.

### 📚 Money OS — a platform and course for beginners
A simple, structured way to understand, manage, and start investing your money. Built for people with income but low clarity — especially women and first-time investors who feel locked out.

### 🛠 What I work with
![TypeScript](https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Fastify](https://img.shields.io/badge/fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![Next.js](https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Zod](https://img.shields.io/badge/zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white)
![AWS](https://img.shields.io/badge/aws-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/aws%20lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/aws%20bedrock-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Serverless](https://img.shields.io/badge/serverless-FD5750?style=for-the-badge&logo=serverless&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgresql-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![DynamoDB](https://img.shields.io/badge/dynamodb-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)
![Docker](https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### 🤖 Currently building with
![Claude](https://img.shields.io/badge/claude-D97757?style=for-the-badge&logoColor=white)
![LangChain](https://img.shields.io/badge/langchain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/openai-412991?style=for-the-badge&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-4B8BBE?style=for-the-badge&logoColor=white)
![Server-Sent Events](https://img.shields.io/badge/SSE-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

[![Help Wanted](https://img.shields.io/badge/🆘_HELP_WANTED-Stress--test_Marvin_against_real_adversarial_credit_cases_→_email_me-39FF14?style=for-the-badge&labelColor=000000)](mailto:ali.elvin@gmail.com)

> [!TIP]
> 🆘 **I'm looking for help with:** connecting with credit-risk underwriters, compliance officers, and fintech engineers who can stress-test Marvin's dossiers and conflict tree against real adversarial cases — the more brutal the feedback, the better. **[Email me →](mailto:ali.elvin@gmail.com)**

---

- 🔭 I'm currently working on **Marvin** ([marvinos.uk](https://marvinos.uk/)) — an 8-agent, 3-department credit-committee system that produces explainable, auditable bank credit decisions and keeps its own policy library current — and **Money OS**, a course teaching beginners how to invest
- 🌱 I'm currently learning everything I can about AI engineering — working through the [AWS AI Agent Learning Series](https://aws.amazon.com/marketplace/build-learn/ai-agent-learning-series?trk=54ad7d9c-6e8f-4bff-9f77-ba04a06ed257&sc_channel=el&refid=4dccf88d-b255-470f-82d0-13e00449c5f4) and [Epic AI's MCP Fundamentals workshop](https://www.epicai.pro/workshops/mcp-fundamentals-mtezq/intro-i51jf), and reading *[Thinking, Fast and Slow](https://www.amazon.co.uk/dp/0141033576)* by Daniel Kahneman and *[AI Engineering](https://www.amazon.co.uk/dp/1098166302)* by Chip Huyen. Useful, trustworthy AI systems are what I want to keep building
- 👯 I'm looking to collaborate on tools that make investing accessible to people who feel locked out of it — especially women and first-time investors
- 💬 Ask me about scaling Node.js services, serverless on AWS, building self-improving multi-agent systems with LangChain and Claude, or how to explain compound interest without putting people to sleep
- 📫 How to reach me: [ali.elvin@gmail.com](mailto:ali.elvin@gmail.com)
- 😄 Pronouns: she/her
- ⚡ Fun fact: I once printed out half of early Google because growing up in post-communist Bulgaria taught me that good information disappears

---

### What I care about
- Translating complex systems into things real people can use
- Shipping correct financial logic — edge cases matter in finance
- Simple architectures over clever ones
- Build → test → refine, not perfect-before-shipping
- AI systems that are explainable and auditable, not just impressive

### What you'll find here
- **Marvin** ([marvinos.uk](https://marvinos.uk/)) — a self-improving multi-agent credit-committee system with full audit trail and a meta-architect that watches the other agents *(repo private)*
- **Money OS** — the platform and course teaching beginners how to invest *(repo private)*
- Experiments in multi-agent orchestration, RAG, and evaluation
- Prototypes from the AWS AI Agent and Epic AI MCP courses I'm working through
- Notes and architectural specs from building agentic systems for regulated domains

If you're building in personal finance, credit decisioning, or auditable AI for regulated domains — get in touch.
