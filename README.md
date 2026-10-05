> **Portfolio showcase** — the complete implementation is kept private to protect intellectual property. This public repository intentionally contains documentation only. A live demo or private code review can be provided for a serious project discussion.

# Judler

AI operations platform for dispatching, supervising and recovering long-running agent work across isolated environments.

## Highlights
- MCP bridge between conversational UI and execution workers
- durable task state, progress events and resumable workflows
- model/provider routing with fallback logic and quota controls
- operator approvals and decision gates
- monitoring, health checks and recovery-oriented architecture
- containerized services and isolated worker infrastructure
- extensive automated tests around orchestration and failure modes

## Stack
Python 3.11+, MCP, Docker/Compose, systemd, browser-side JavaScript.

## Structure
- bridge/ — orchestration, API, workboard and provider control
- art-editor/ — isolated media/art workflow helper
- infra/ — worker/container infrastructure
- studio-v2/ — contracts and selected architecture documentation

This is a sanitized portfolio snapshot. Private hostnames, credentials, runtime keys and recovery material were removed. Use .env.example with your own values.

## Usage and licensing

This repository is source-available for portfolio evaluation. You may inspect the code and run an unmodified local copy for evaluation, but commercial use, redistribution, republishing and derivative distribution are not permitted without written permission. See [LICENSE.md](LICENSE.md).

