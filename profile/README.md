# Affectively AI

AFFECTIVELY is an emotion tracking and analysis platform that helps people hold onto their clarity. We build local-first, privacy-respecting tools that run AI inference entirely in-browser and at the edge — zero server cost, zero latency, your data stays yours.

The **Aeon** ecosystem is our open-source infrastructure: distributed sync, collaborative surfaces, edge AI, WASM engines, and the tooling to tie it all together.

- **Website**: [aeonflux.dev](https://aeonflux.dev)
- **Documentation**: [docs.aeonflux.dev](https://docs.aeonflux.dev)
- **Storybook**: [storybook.aeonflux.dev](https://storybook.aeonflux.dev)
- **HuggingFace**: [huggingface.co/affectively-ai](https://huggingface.co/affectively-ai)
- **GitHub**: [github.com/affectively-ai](https://github.com/affectively-ai)

## Fine-Tuned Models

| Model | Task | Base | Format | HuggingFace |
|-------|------|------|--------|-------------|
| Cog | DevOps intelligence — incident response, deployment decisions, system management | SmolLM2-360M-Instruct | GGUF (Q4_K_M, Q8_0) | [cog-360m-instruct-gguf](https://huggingface.co/affectively/cog-360m-instruct-gguf) |
| Cyrano | Emotional intelligence — empathetic responses, emotion detection, coping strategies | SmolLM2-360M-Instruct | GGUF (Q4_K_M, Q8_0) | [cyrano-360m-instruct-gguf](https://huggingface.co/affectively/cyrano-360m-instruct-gguf) |

## Browser AI Models (ONNX)

Production-ready ONNX models for in-browser inference with [transformers.js](https://huggingface.co/docs/transformers.js). All models run entirely client-side.

| Model | Task | Size | HuggingFace |
|-------|------|------|-------------|
| BART-Large CNN | Text summarization | ~493 MB | [bart-large-cnn-onnx](https://huggingface.co/affectively-ai/bart-large-cnn-onnx) |
| DeBERTa v3 Zero-Shot | Zero-shot classification | ~243 MB | [deberta-v3-base-mnli-onnx](https://huggingface.co/affectively-ai/deberta-v3-base-mnli-onnx) |
| DistilBERT Emotion | Emotion classification (6 labels) | ~67 MB | [distilbert-base-uncased-emotion-onnx](https://huggingface.co/affectively-ai/distilbert-base-uncased-emotion-onnx) |
| DistilRoBERTa Emotion | Emotion classification (7 labels) | ~82 MB | [emotion-english-distilroberta-base-onnx](https://huggingface.co/affectively-ai/emotion-english-distilroberta-base-onnx) |
| NLLB-200 1.3B | Translation (200 languages) | ~1.81 GB | [nllb-200-1.3B-onnx](https://huggingface.co/affectively-ai/nllb-200-1.3B-onnx) |
| NLLB-200 Distilled 1.3B | Translation (200 languages) | ~1.81 GB | [nllb-200-distilled-1.3B-onnx](https://huggingface.co/affectively-ai/nllb-200-distilled-1.3B-onnx) |
| RoBERTa GoEmotions | Emotion detection (28 labels) | ~124 MB | [roberta-base-go-emotions-onnx](https://huggingface.co/affectively-ai/roberta-base-go-emotions-onnx) |
| Twitter RoBERTa Sentiment | Sentiment analysis (3-class) | ~124 MB | [twitter-roberta-base-sentiment-onnx](https://huggingface.co/affectively-ai/twitter-roberta-base-sentiment-onnx) |

## Aeon Ecosystem

| Package | npm | Description |
|---------|-----|-------------|
| [Aeon](https://github.com/affectively-ai/aeon) | `@affectively/aeon` | Distributed synchronization, schema versioning, and conflict resolution for real-time collaborative applications. |
| [Aeon Container](https://github.com/affectively-ai/aeon-container) | `@affectively/aeon-container` | Browser sandbox, persistent filesystem, streamed linting, and agent collaboration runtime for code execution at the edge. |
| [Aeon Flags](https://github.com/affectively-ai/aeon-flags) | `@affectively/aeon-flags` | UCAN-enforced feature gating at the edge. Deterministic, cryptographic entitlements replacing centralized feature flag SaaS. |
| [Aeon Flux](https://github.com/affectively-ai/aeon-flux) | `@affectively/aeon-flux` | Collaborative page surface with CRDT-based flux state, Edge Side Inference (ESI), and zero-CLS rendering. |
| [Aeon Flux Capacitor](https://github.com/affectively-ai/aeon-flux-capacitor) | `@affectively/capacitor` | Embedding-first collaborative WYSIWYG editor where text is a derivative of the vector space. |
| [Aeon Forge](https://github.com/affectively-ai/aeon-forge) | — | Deployment engine and CLI/CD system for Aeon applications. |
| [Aeon Foundation](https://github.com/affectively-ai/aeon-foundation) | `@affectively/aeon-foundation` | The complete Aeon stack in one package: distributed sync, collaborative pages, state management, relay transport, edge AI, and decentralized auth. |
| [Aeon IAM](https://github.com/affectively-ai/aeon-iam) | `@affectively/aeon-iam` | Device-rooted UCAN identity and access management with badge tokens, DID resolution, and bearer credential parsing. |
| [Aeon Icons](https://github.com/affectively-ai/aeon-icons) | `@affectively/aeon-icons` | Icon library for Aeon web and native applications. |
| [Aeon IDE](https://github.com/affectively-ai/aeon-ide) | `@affectively/aeon-ide` | IDE UI components and hooks for the Aeon Container environment — editor, file tree, console, toolbar, and collaboration panels. |
| [Aeon Invite](https://github.com/affectively-ai/aeon-invite) | `@affectively/aeon-invite` | Beta shield, invite codes, waitlist management, and funnel analytics for controlled rollouts. |
| [Aeon Preferences](https://github.com/affectively-ai/aeon-preferences) | `@affectively/aeon-preferences` | Federated user preferences via Dash DB. |
| [Aeon Shell](https://github.com/affectively-ai/aeon-shell) | `@affectively/aeon-shell` | Local-first operating surface with live shell canvas, graph runtime, route-aware surfaces, and native `aeon://` addressing. |
| [Aeon Shell Core](https://github.com/affectively-ai/aeon-shell-core) | `@affectively/aeon-shell-core` | Canonical runtime surface for shell consumers with host/plugin orchestration and engine registry security boundaries. |
| [Aeon TUI](https://github.com/affectively-ai/aeon-tui) | — | Ink-based terminal runtime with behavior parity to the Aeon shell, command palette flows, and integrated PTY panes. |
| [Aegis (Aeon Auth)](https://github.com/affectively-ai/aeon-auth) | `@affectively/auth` | Zero-dependency decentralized identity and access control built on Web Crypto API. UCAN capabilities, DID resolution, and ECDSA signatures. |

## Local-First Data and Edge

| Package | npm | Description |
|---------|-----|-------------|
| [Dash](https://github.com/affectively-ai/dash) | `@affectively/dash` | Multi-layer edge storage and CRDT sync engine supporting Yjs, Automerge, WebSocket, WebTransport, and WebRTC. |
| [Dash CLI](https://github.com/affectively-ai/dash-cli) | `@affectively/dash-cli` | The sovereign, local-first database for your command line. |
| [Edgework CLI](https://github.com/affectively-ai/edgework-cli) | `edgework` | CLI for edgework.ai — accessible AI at the edge. |
| [Edgework SDK](https://github.com/affectively-ai/edgework-sdk) | `@affectively/edgework-sdk` | Client-side AI inference SDK with D1/Dash storage, WebGPU inference, and on-device RLHF. |
| [Neural](https://github.com/affectively-ai/neural) | — | Distributed monorepo for neural/AI infrastructure. |
| [Zedge](https://github.com/affectively-ai/zedge) | — | Companion sidecar with inference bridge and compute pool node functionality. |

## Orchestration and Protocols

| Package | npm | Description |
|---------|-----|-------------|
| [MCP Framework](https://github.com/affectively-ai/mcp-framework) | `@affectively/mcp-framework` | Framework for building Model Context Protocol servers with authentication, tool registration, and analytics. |
| [Slash Commands](https://github.com/affectively-ai/slash-commands) | — | Slash command framework for conversational interfaces. |
| [Workflows](https://github.com/affectively-ai/workflows) | `@affectively/orchestrator` | Production-grade workflow orchestration and composition engine for autonomous agents and CI/CD pipelines. |

## Data and Taxonomy

| Package | npm | Description |
|---------|-----|-------------|
| [Behavioral Taxonomy](https://github.com/affectively-ai/behavioral-taxonomy) | `@affectively/behavioral-taxonomy` | 1,140+ behavioral loops, emotions, cognitive biases, and personality traits. Licensed CC-BY-4.0. |
| [Utils](https://github.com/affectively-ai/utils) | `@affectively/utils` | API retry logic, consistent logging, and short URL generation. |

## Developer Tooling

| Package | npm | Description |
|---------|-----|-------------|
| [Bun Isolated Runner](https://github.com/affectively-ai/bun-isolated-runner) | `@affectively/bun-isolated-runner` | Run Bun tests in isolated subprocesses to prevent mock pollution and global state leakage. |
| [DevOps Scripts](https://github.com/affectively-ai/devops-scripts) | `@affectively/devops-scripts` | Monorepo automation for changed-file testing, type-checking, and accessibility audits. |
| [Trace Lint](https://github.com/affectively-ai/trace-lint) | `@affectively/trace-lint` | Extensible linting framework for Chrome/DevTools trace files with loop detection rules. |

## WASM Engines

High-performance Rust modules compiled to WebAssembly for near-native speed in the browser and Node.js.

| Module | npm | Description |
|--------|-----|-------------|
| [Confetti Physics](https://github.com/affectively-ai/confetti-physics) | `@affectively/confetti-physics` | Physics-based confetti celebrations with fluid dynamics, haptic feedback, and procedural audio. |
| [Entrainment Audio](https://github.com/affectively-ai/entrainment-audio) | — | Audio entrainment and binaural beat generation. |
| [Synthetic Watermark](https://github.com/affectively-ai/synthetic-watermark) | — | Watermarking for synthetic/AI-generated content. |
| [wasm-analytics-engine](https://github.com/affectively-ai/wasm-analytics-engine) | `@affectively/wasm-analytics-engine` | Metrics computation, event processing, and funnel analytics. |
| [wasm-audio-processor](https://github.com/affectively-ai/wasm-audio-processor) | `@affectively/wasm-audio-processor` | Audio mixing, volume adjustment, silence generation, and µ-law encoding. |
| [wasm-cache-ops](https://github.com/affectively-ai/wasm-cache-ops) | `@affectively/wasm-cache-ops` | Batch caching, LZ4-style compression, eviction policies, and hashing. |
| [wasm-data-aggregator](https://github.com/affectively-ai/wasm-data-aggregator) | `@affectively/wasm-data-aggregator` | Statistical analysis, grouping, and time-series aggregation. |
| [wasm-graph-algorithms](https://github.com/affectively-ai/wasm-graph-algorithms) | `@affectively/wasm-graph-algorithms` | Cycle detection, DAG operations, pathfinding (Dijkstra/A*), and topological sort. |
| [wasm-image-utils](https://github.com/affectively-ai/wasm-image-utils) | `@affectively/wasm-image-utils` | Base64 encoding/decoding, format detection, and image validation. |
| [wasm-text-processor](https://github.com/affectively-ai/wasm-text-processor) | `@affectively/wasm-text-processor` | Pattern matching, entity extraction, and text scoring. |

## Documentation

| Project | Description |
|---------|-------------|
| [AFFECTIVELY Wiki](https://github.com/affectively-ai/emotions-wiki) | Project wiki and knowledge base. |
| [Monorepo](https://github.com/affectively-ai/monorepo) | Primary development monorepo for the AFFECTIVELY platform. |
| [Neural Wiki](https://github.com/affectively-ai/neutral-wiki) | Neural project documentation. |

## License

- **Code Packages**: MIT License
- **Data Packages**: Creative Commons Attribution 4.0 (CC BY 4.0)
- **ONNX Models**: Same license as base model (see individual model cards)
