# Joan Marc Carbó Arnau

**AI platform engineer** — operationalising LLMs and agents, knowledge graphs and retrieval, workflow orchestration.

MD + BSc CS based in Barcelona, Catalonia, Spain. Currently Senior Staff Software Engineer at [Celonis](https://www.celonis.com), where I am principal author of **ACE Kernel**, Celonis' agentic application runtime: ~325k lines of production Go (2,101 of 2,690 commits), backed by ~498k lines of tests at 90.1% coverage.

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-DEA584?style=flat&logo=rust&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-000000?style=flat&labelColor=000000)

## What I build

AI and agent systems that hold up in production:

- 🧠 **Model-agnostic LLM layer** over OpenAI, Anthropic, Google Gemini and Ollama — swap providers without touching application code.
- 📐 **Tool Command Language**: a specification for agent tool calling plus knowledge-graph memory where agents store tool results as (subject, predicate, object) triples.
- ⚡ **Token-efficient tool use** (measured in internal agent-runtime work): 25 tool definitions dropped from ~2,400 tokens of JSON Schema to 160; a five-tool chain went from 7 LLM round trips to 1.
- ✅ **Quality at scale**: raised Go test coverage from 64.9% to 90.1% across a 1,100-file suite (Celonis agentic-runtime codebase).
- Built the **celonix-go SDK** with an integrated MCP server.

## Featured open source

- **[fullmcp](https://github.com/jmcarbo/fullmcp)** — Go implementation of the Model Context Protocol: tools, resources and prompts over stdio/HTTP/WebSocket/SSE transports. CI-gated releases; 95.8% test coverage.
- **[periplon](https://github.com/periplon/periplon)** — CLI and Rust SDK for multi-agent AI workflows running unattended for hours or days.
- **[awiki](https://github.com/jmcarbo/awiki)** — Template for an LLM-maintained personal wiki implementing Karpathy's LLM-wiki pattern. Multi-agent (Claude Code, Codex, OpenCode); BM25 + RRF-fused search via qmd.
- **[grapher](https://github.com/jmcarbo/grapher)** — MCP server for diagram generation.
- **[oapix](https://github.com/jmcarbo/oapix)** — OpenAPI-to-type-safe Go client code generation.

I also maintain long-running infrastructure tooling such as [docker-postgres-backup](https://github.com/jmcarbo/docker-postgres-backup) (35 ⭐).

## Career arc

- **Senior Staff Software Engineer @ Celonis** (2024–now) — ACE Kernel, agentic runtime.
- **Golang Team Leader @ Emporix** (2022–2024) — led the Go team on a low-code Orchestration Engine acquired by Celonis (product and team); proposed Colored Petri Nets as its formal execution model on Temporal.
- **Lead Software Engineer Go / Senior DevOps & SRE** (2007–2022) — medical research institute and fintech.
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
