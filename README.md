# Solomon S. Joseph

### AI Implementation Engineer  |  Privacy-First AI Systems  |  LLM and Agent Engineering

I build working AI systems for regulated clinical research, and I teach the people around me to run them. My focus is making AI safe and usable on protected health data, where the engineering has to be careful and the people using it are experts in their field rather than in AI.

**Currently:** Research Teaching Specialist III, Rutgers University (US-India RePORT tuberculosis research consortium)
**Education:** M.S. Cybersecurity and Information Assurance, Southern Utah University (in progress)
**Based in:** Chester, VA  ·  Open to relocation
**Reach me:** [LinkedIn](https://www.linkedin.com/in/solomon-s-joseph/)  ·  solomonjosephusa98@gmail.com

---

## What I do

- Build AI assistants that work on sensitive health data without exposing patient information
- Turn slow, technical data tasks into natural-language tools that researchers can use on their own
- Train non-technical teams to adopt AI tools confidently and independently
- Build reproducible, auditable research software, with the controls and evidence that regulated work requires

Longer-term, I work toward post-quantum cryptography readiness and crypto-agility for sensitive-data systems.

---

## Flagship project

### RePORT-AI-Portal (Reportal)

A privacy-first clinical research system that lets tuberculosis researchers query protected study data in plain language. It pairs a fail-closed PHI-handling pipeline with a LangGraph LLM assistant that runs on multiple model providers (Anthropic, OpenAI, Google, or local models).

The core idea: a two-world architecture that makes "the LLM cannot see patient information" a structural fact rather than a hopeful convention. Raw data is scrubbed inside trusted code; the assistant can only ever read a separately published, leak-scanned, audit-backed copy. The system includes dual-jurisdiction de-identification (HIPAA Safe Harbor and India DPDPA), HMAC pseudonymization, a residual leak gate, a dual-ledger audit trail built for IRB review, and an evaluation subsystem that measures answer accuracy before release.

*Status: in beta, with a version 1 launch planned for June 2026 and a presentation to the US-India RePORT consortium.*

---

## Selected work

- **RePORTaL-MCP** - A Model Context Protocol prototype for clinical data access with multi-jurisdiction compliance support. It worked, then I deferred it after evaluation showed accuracy gaps. Kept public as an honest record of what worked and what did not.
- **amarel-vscode** - A VS Code Remote-SSH setup tool used by lab members to connect to Rutgers' Amarel HPC cluster, resolving the GLIBC 2.28 compatibility error on macOS and Windows.
- **PHI-Handling-IRB-Review-Support** - A synthetic PHI/PII corpus, validation harness, and IRB review-support tooling (personal project).
- **BatchQC** ([wejlab/BatchQC](https://github.com/wejlab/BatchQC)) - Named contributor to the R/Bioconductor package for batch effect evaluation of high-throughput genomic data. NIH-funded; bioRxiv preprint, 2026.

I also advise a lab collaborator on the broader RePORT multi-agent research system, where Reportal serves as the protected-data component.

---

## Skills

| Area | Tools |
|------|-------|
| **AI and LLM** | Claude, OpenAI, Google, and local LLMs; LangGraph; Model Context Protocol (MCP); RAG; prompt engineering; evaluation harnesses |
| **Languages** | Python, SQL, R, Bash |
| **Privacy and Security** | PHI/PII de-identification, HMAC pseudonymization, fail-closed controls, process isolation, residual leak scanning, audit and lineage trails |
| **Infrastructure** | Docker, Singularity, Nextflow, GitHub Actions, Linux, HPC |
| **Frameworks** | HIPAA Safe Harbor, India DPDPA, NIST AI RMF, OWASP Top 10, secure SDLC |

---

## Education and certifications

- **M.S. Cybersecurity and Information Assurance** - Southern Utah University (in progress)
- **B.Tech. Computer Science (Cybersecurity and Digital Forensics)** - Manav Rachna International Institute
- **Certifications:** AI Fluency, Claude 101, Claude Code 101 (Anthropic); IBM Cybersecurity Analyst Professional Certificate

---

## Responsible use and scope

- Public repositories contain no real PHI or patient-identifying data.
- PHI/PII examples are synthetic or sanitized.
- Privacy and compliance language is implementation-oriented and review-support focused, not a legal certification.
- IRB approval has not been received for the separate PHI-handling review-support system.

---

## Open to

Applied AI, AI implementation, privacy engineering, and research software engineering roles for mission-driven and regulated organizations.

**LinkedIn:** https://www.linkedin.com/in/solomon-s-joseph/  ·  **Email:** solomonjosephusa98@gmail.com
