# Joan Marc Carbó Arnau

**AI platform engineer** — operationalising LLMs and agents, knowledge graphs and retrieval, workflow orchestration.

Physician (MD) turned engineer (BSc CS), based in Barcelona, Catalonia, Spain. Currently Senior Staff Software Engineer at [Celonis](https://www.celonis.com), where I am principal author of the agentic application runtime that powers Celonis' enterprise AI workflows — a large production Go codebase.

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-DEA584?style=flat&logo=rust&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-000000?style=flat&logo=modelcontextprotocol&logoColor=white)

## What I build

AI and agent systems that hold up in production:

- 🧠 **Model-agnostic LLM orchestration** — swap providers by configuration, not by code; reproducible agent behaviour in CI with record-and-replay testing.
- 📐 **Agent tool-use and memory design** — a specification for agent tool calling plus knowledge-graph memory, so an agent's context becomes a queryable ontology instead of a transcript.
- ⚡ **Token- and latency-efficient tool use** — order-of-magnitude cuts in tool-definition overhead and multi-step agent round trips.
- ✅ **Quality at scale**: high test coverage and deterministic regression testing for non-deterministic agent workloads.

## Featured open source

- **[fullmcp](https://github.com/jmcarbo/fullmcp)** — Go implementation of the Model Context Protocol: tools, resources and prompts over stdio/HTTP/WebSocket/SSE transports. CI-gated releases; 95.8% test coverage.
- **[periplon](https://github.com/periplon/periplon)** — CLI and Rust SDK for multi-agent AI workflows running unattended for hours or days.
- **[awiki](https://github.com/jmcarbo/awiki)** — Template for an LLM-maintained personal wiki implementing Karpathy's LLM-wiki pattern. Multi-agent (Claude Code, Codex, OpenCode); BM25 + RRF-fused search via qmd.
- **[grapher](https://github.com/jmcarbo/grapher)** — MCP server for diagram generation.
- **[oapix](https://github.com/jmcarbo/oapix)** — OpenAPI-to-type-safe Go client code generation.

I also maintain long-running open-source infrastructure tooling such as [docker-postgres-backup](https://github.com/jmcarbo/docker-postgres-backup), used by teams for scheduled Postgres backups in Docker.

## Career arc

- **Senior Staff Software Engineer @ Celonis** (2024–now) — principal author of Celonis' agentic application runtime.
- **Golang Team Leader @ Emporix** (2022–2024) — led the Go team building a low-code workflow Orchestration Engine that Celonis acquired, product and team.
- **Lead Go Engineer / Senior DevOps & SRE** (2007–2022) — Go microservices at a Barcelona medical research institute; SRE at a fintech.
- Alongside engineering: part-time Professor of statistics and CS for medical students (2005–2022), resident physician in preventive medicine, and tech writer at Byte Magazine.

## Contact

- 💼 [linkedin.com/in/joanmarccarbo](https://www.linkedin.com/in/joanmarccarbo/)
- 📧 jmcarbo@gmail.com

<picture>
  <source media="(prefers-color-scheme: dark)"
          srcset="https://raw.githubusercontent.com/jmcarbo/jmcarbo/output/github-contribution-grid-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/jmcarbo/jmcarbo/output/github-contribution-grid-snake.svg"
       alt="Contribution graph snake animation" width="100%" />
</picture>
