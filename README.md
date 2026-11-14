# Nikita Schepetkov

Senior full-stack engineer based in Yerevan, Armenia (UTC+4). I've been building web products for 9 years, from the UI down to deployment: React/Next.js and Vue/Nuxt on the frontend, Node.js/NestJS and Go on the backend, Docker and Kubernetes in production.

These days I work at Leino, an AI meeting-intelligence SaaS. Its bot joins Google Meet, Zoom and Yandex Telemost calls and records them. I work on that bot, the RAG pipeline and tool-calling agents that answer questions about recordings, and Stripe billing in the Go gateway.

Until recently I was also at Sber (SberInfra), leading a team of 8 on internal products for ordering cloud resources. I designed the contract-first architecture there: gRPC between services, GraphQL to the Vue frontend.

I write code with Claude Code every day. One agent plans, another implements, a third reviews independently, and tests decide what gets merged. The architecture and what ships are still on me.

I'm open to remote or hybrid contract work through my Armenian sole proprietorship.

**Stack:** TypeScript, Go, React, Next.js, Vue, Nuxt, Node.js, NestJS, gRPC, GraphQL, PostgreSQL, Redis, Docker, Kubernetes, Playwright, Stripe, LLM APIs (RAG, tool calling)

## Projects

- **[claude-code-setup](https://github.com/nezo32/claude-code-setup)**: the Claude Code setup I use every day: 14 role agents with a model assigned per role, orchestration and review skills, skills that keep long autonomous sessions on track, and guard hooks. Collected from three real projects with the project details removed.
- **[family-hub](https://github.com/nezo32/family-hub)**: a self-hosted family PWA: chores with fair rotation, a shared calendar (ICS), savings goals, offline shopping lists and web push that works on iPhone. TypeScript monorepo with Drizzle, Postgres and Redis, about 100 test files including Playwright e2e, CI/CD. UI in Russian, code and docs in English.
- **[Locaita](https://github.com/nezo32/Locaita)**: a Soft Actor-Critic reinforcement-learning agent that plays osu!. It reads game state from a patched osu!lazer over WebSocket, captures the screen and moves the mouse. Python 3.13, PyTorch, uv.
- **[locaita-voice-module](https://github.com/nezo32/locaita-voice-module)**: a local voice companion for Discord and Telegram. whisper.cpp for speech-to-text, an Ollama LLM, F5-TTS for the voice, Supabase for memory. TypeScript.
- **[anki-kanji-importer](https://github.com/nezo32/anki-kanji-importer)**: a Bun CLI that parses vocabulary PDFs and turns them into kanji flashcards in Anki, via an OpenAI-compatible API and AnkiConnect.
- **Minecraft game modes** (Fabric/Java, some also on Bedrock): [burmaldaholic](https://github.com/nezo32/burmaldaholic) (casino economy with card games, slots, loans and debt collectors), [enchantaholic](https://github.com/nezo32/enchantaholic), [absorbaholic](https://github.com/nezo32/absorbaholic), [echoaholic](https://github.com/nezo32/echoaholic), [chaosaholic](https://github.com/nezo32/chaosaholic), [munchaholic](https://github.com/nezo32/munchaholic). Each has GameTest suites and a reusable CI pipeline that publishes releases to CurseForge and Modrinth.

## Contact

[nezo.prod32@gmail.com](mailto:nezo.prod32@gmail.com) · Telegram [@nz3301](https://t.me/nz3301)
