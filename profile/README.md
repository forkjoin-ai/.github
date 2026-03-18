# Forkjoin.ai

We build local-first, privacy-respecting tools that run AI inference entirely in-browser and at the edge -- zero server cost, zero latency, your data stays yours.

The **Aeon** ecosystem is our open-source infrastructure: distributed sync, collaborative surfaces, edge AI, WASM engines, and the tooling to tie it all together.

- **Website**: [aeonflux.dev](https://aeonflux.dev)
- **Documentation**: [docs.aeonflux.dev](https://docs.aeonflux.dev)
- **Storybook**: [storybook.aeonflux.dev](https://storybook.aeonflux.dev)
- **HuggingFace**: [huggingface.co/forkjoin-ai](https://huggingface.co/forkjoin-ai)
- **GitHub**: [github.com/forkjoin-ai](https://github.com/forkjoin-ai)

## Fine-Tuned Models

| Model | Task | Base | Format | License | HuggingFace |
|-------|------|------|--------|---------|-------------|
| Cog | DevOps intelligence -- incident response, deployment decisions, system management | SmolLM2-360M-Instruct | GGUF (Q4_K_M, Q8_0) | Apache 2.0 | [cog-360m-instruct-gguf](https://huggingface.co/affectively/cog-360m-instruct-gguf) |
| Cyrano | Emotional intelligence -- empathetic responses, emotion detection, coping strategies | SmolLM2-360M-Instruct | GGUF (Q4_K_M, Q8_0) | Apache 2.0 | [cyrano-360m-instruct-gguf](https://huggingface.co/affectively/cyrano-360m-instruct-gguf) |
| Gnosis 360M | GGL topology generation from natural language | SmolLM2-360M-Instruct | GGUF | Apache 2.0 | [gnosis-360m-topology](https://github.com/forkjoin-ai/gnosis-360m-topology) |

## Browser AI Models (ONNX)

Production-ready ONNX models for in-browser inference with [transformers.js](https://huggingface.co/docs/transformers.js). All models run entirely client-side.

| Model | Task | Size | License | HuggingFace |
|-------|------|------|---------|-------------|
| BART-Large CNN | Text summarization | ~493 MB | MIT | [bart-large-cnn-onnx](https://huggingface.co/forkjoin-ai/bart-large-cnn-onnx) |
| DeBERTa v3 Zero-Shot | Zero-shot classification | ~243 MB | MIT | [deberta-v3-base-mnli-onnx](https://huggingface.co/forkjoin-ai/deberta-v3-base-mnli-onnx) |
| DistilBERT Emotion | Emotion classification (6 labels) | ~67 MB | Apache 2.0 | [distilbert-base-uncased-emotion-onnx](https://huggingface.co/forkjoin-ai/distilbert-base-uncased-emotion-onnx) |
| DistilRoBERTa Emotion | Emotion classification (7 labels) | ~82 MB | MIT | [emotion-english-distilroberta-base-onnx](https://huggingface.co/forkjoin-ai/emotion-english-distilroberta-base-onnx) |
| NLLB-200 1.3B | Translation (200 languages) | ~1.81 GB | CC-BY-NC-4.0 | [nllb-200-1.3B-onnx](https://huggingface.co/forkjoin-ai/nllb-200-1.3B-onnx) |
| NLLB-200 Distilled 1.3B | Translation (200 languages) | ~1.81 GB | CC-BY-NC-4.0 | [nllb-200-distilled-1.3B-onnx](https://huggingface.co/forkjoin-ai/nllb-200-distilled-1.3B-onnx) |
| RoBERTa GoEmotions | Emotion detection (28 labels) | ~124 MB | MIT | [roberta-base-go-emotions-onnx](https://huggingface.co/forkjoin-ai/roberta-base-go-emotions-onnx) |
| Twitter RoBERTa Sentiment | Sentiment analysis (3-class) | ~124 MB | MIT | [twitter-roberta-base-sentiment-onnx](https://huggingface.co/forkjoin-ai/twitter-roberta-base-sentiment-onnx) |

## Aeon Ecosystem

| Package | npm | License | Description |
|---------|-----|---------|-------------|
| [Aeon](https://github.com/forkjoin-ai/aeon) | `@a0n/aeon` | MIT | Distributed synchronization, schema versioning, and conflict resolution for real-time collaborative applications. |
| [Aeon 3D](https://github.com/forkjoin-ai/aeon-3d) | `@a0n/aeon-3d` | MIT | Three.js-based 3D rendering for Aeon topology visualization. |
| [Aeon Affectively](https://github.com/forkjoin-ai/aeon-affectively) | -- | MIT | Emotion tracking and analysis components for the Aeon ecosystem. |
| [Aeon Bazaar](https://github.com/forkjoin-ai/aeon-bazaar) | `@a0n/aeon-bazaar` | MIT | Unbounded negotiation engine with void walker dynamics and no termination guarantee. |
| [Aeon Communication](https://github.com/forkjoin-ai/aeon-communication) | -- | MIT | Messaging and communication primitives for Aeon applications. |
| [Aeon Container](https://github.com/forkjoin-ai/aeon-container) | `@a0n/aeon-container` | MIT | Browser sandbox, persistent filesystem, streamed linting, and agent collaboration runtime for code execution at the edge. |
| [Aeon Flow](https://github.com/forkjoin-ai/aeon-flow) | `@a0n/aeon-flow` | MIT | Reactive dataflow graph engine for Aeon topologies. |
| [Aeon Flux](https://github.com/forkjoin-ai/aeon-flux) | `@a0n/aeon-flux` | MIT | Collaborative page surface with CRDT-based flux state, Edge Side Inference (ESI), and zero-CLS rendering. |
| [Aeon Flux Capacitor](https://github.com/forkjoin-ai/aeon-flux-capacitor) | `@affectively/capacitor` | MIT | Embedding-first collaborative WYSIWYG editor where text is a derivative of the vector space. |
| [Aeon Forge](https://github.com/forkjoin-ai/aeon-forge) | -- | MIT | Deployment engine and CLI/CD system for Aeon applications. |
| [Aeon Foundation](https://github.com/forkjoin-ai/aeon-foundation) | `@a0n/aeon-foundation` | MIT | The complete Aeon stack in one package: distributed sync, collaborative pages, state management, relay transport, edge AI, and decentralized auth. |
| [Aeon Games](https://github.com/forkjoin-ai/aeon-games) | -- | MIT | Game engine primitives and interactive experiences built on Aeon. |
| [Aeon IAM](https://github.com/forkjoin-ai/aeon-iam) | `@a0n/aeon-iam` | MIT | Device-rooted UCAN identity and access management with badge tokens, DID resolution, and bearer credential parsing. |
| [Aeon Icons](https://github.com/forkjoin-ai/aeon-icons) | `@a0n/aeon-icons` | MIT | Icon library for Aeon web and native applications. |
| [Aeon IDE](https://github.com/forkjoin-ai/aeon-ide) | `@a0n/aeon-ide` | MIT | IDE UI components and hooks for the Aeon Container environment -- editor, file tree, console, toolbar, and collaboration panels. |
| [Aeon Invite](https://github.com/forkjoin-ai/aeon-invite) | `@a0n/aeon-invite` | MIT | Beta shield, invite codes, waitlist management, and funnel analytics for controlled rollouts. |
| [Aeon Logic](https://github.com/forkjoin-ai/aeon-logic) | `@a0n/aeon-logic` | MIT | Formal verification primitives -- theorem ledger, proof-carrying deployments, and static analysis for Aeon topologies. |
| [Aeon Neutral](https://github.com/forkjoin-ai/aeon-neutral) | `@a0n/aeon-neutral` | MIT | Bounded dispute resolution with three-walker Skyrms mediation and convergence certificates. |
| [Aeon Pipelines](https://github.com/forkjoin-ai/aeon-pipelines) | `@a0n/aeon-pipelines` | MIT | Laminar dataflow pipelines for deterministic, parallelized computation over Aeon topologies. |
| [Aeon Pipelines Neo4j](https://github.com/forkjoin-ai/aeon-pipelines-neo4j) | -- | MIT | Neo4j graph database adapter for Aeon Pipelines. |
| [Aeon Preferences](https://github.com/forkjoin-ai/aeon-preferences) | `@a0n/aeon-preferences` | MIT | Federated user preferences via Dash DB. |
| [Aeon Shell](https://github.com/forkjoin-ai/aeon-shell) | `@a0n/aeon-shell` | MIT | Local-first operating surface with live shell canvas, graph runtime, route-aware surfaces, and native `aeon://` addressing. |
| [Aeon Shell Core](https://github.com/forkjoin-ai/aeon-shell-core) | `@a0n/aeon-shell-core` | MIT | Canonical runtime surface for shell consumers with host/plugin orchestration and engine registry security boundaries. |
| [Aeon Stack](https://github.com/forkjoin-ai/aeon-stack) | `@a0n/aeon-stack` | MIT | Zero-dependency performance layer with measured vertical stack windowing, velocity-adaptive overscan, DOM collapse, and speculative rendering. |
| [Aeon TUI](https://github.com/forkjoin-ai/aeon-tui) | -- | MIT | Ink-based terminal runtime with behavior parity to the Aeon shell, command palette flows, and integrated PTY panes. |
| [Aeon Viz](https://github.com/forkjoin-ai/aeon-viz) | `@a0n/aeon-viz` | MIT | Graph visualization and topology rendering for Aeon structures. |
| [Aegis (Aeon Auth)](https://github.com/forkjoin-ai/aeon-auth) | `@affectively/auth` | MIT | Zero-dependency decentralized identity and access control built on Web Crypto API. UCAN capabilities, DID resolution, and ECDSA signatures. |
| [Gnosis](https://github.com/forkjoin-ai/gnosis) | `@a0n/gnosis` | MIT | GGL topology compiler, recursive coarsening synthesis, and FlowFrame rendering engine. |
| [Goodchild (Aeon Flags)](https://github.com/forkjoin-ai/aeon-flags) | `@a0n/aeon-flags` | MIT | UCAN-enforced feature gating at the edge. Deterministic, cryptographic entitlements replacing centralized feature flag SaaS. |
| [X-Gnosis](https://github.com/forkjoin-ai/x-gnosis) | `@affectively/x-gnosis` | MIT | Extended Gnosis runtime with cross-topology linking and federated graph operations. |

## Local-First Data and Edge

| Package | npm | License | Description |
|---------|-----|---------|-------------|
| [Aether](https://github.com/forkjoin-ai/aether) | -- | MIT | Distributed inference runtime -- the medium through which hidden states flow between layer nodes. |
| [Dash/Relay](https://github.com/forkjoin-ai/dash) | `@affectively/dash` | MIT | Multi-layer edge storage and CRDT sync engine supporting Yjs, Automerge, WebSocket, WebTransport, and WebRTC. |
| [Dash CLI](https://github.com/forkjoin-ai/dash-cli) | `@affectively/dash-cli` | MIT | The sovereign, local-first database for your command line. |
| [Edgework CLI](https://github.com/forkjoin-ai/edgework-cli) | `edgework` | MIT | CLI for edgework.ai -- accessible AI at the edge. |
| [Edgework SDK](https://github.com/forkjoin-ai/edgework-sdk) | `@affectively/edgework-sdk` | MIT | Client-side AI inference SDK with D1/Dash storage, WebGPU inference, and on-device RLHF. |
| [Neural](https://github.com/forkjoin-ai/neural) | -- | MIT | Distributed monorepo for neural/AI infrastructure. |
| [Zedge](https://github.com/forkjoin-ai/zedge) | -- | MIT | Companion sidecar with inference bridge and compute pool node functionality. |
| [ZK Encryption](https://github.com/forkjoin-ai/zk-encryption) | -- | MIT | Zero-knowledge encryption primitives for privacy-preserving computation. |

## Orchestration and Protocols

| Package | npm | License | Description |
|---------|-----|---------|-------------|
| [MCP Framework](https://github.com/forkjoin-ai/mcp-framework) | `@affectively/mcp-framework` | MIT | Framework for building Model Context Protocol servers with authentication, tool registration, and analytics. |
| [Orchestrator](https://github.com/forkjoin-ai/orchestrator) | -- | MIT | Task orchestration and agent coordination engine. |
| [Slash Commands](https://github.com/forkjoin-ai/slash-commands) | -- | MIT | Slash command framework for conversational interfaces. |
| [Workflows](https://github.com/forkjoin-ai/workflows) | `@affectively/orchestrator` | MIT | Production-grade workflow orchestration and composition engine for autonomous agents and CI/CD pipelines. |

## Data and Taxonomy

| Package | npm | License | Description |
|---------|-----|---------|-------------|
| [Behavioral Taxonomy](https://github.com/forkjoin-ai/behavioral-taxonomy) | `@affectively/behavioral-taxonomy` | CC-BY-4.0 | 1,619 entries: 239 emotions, 1,140 behavioral loops, 123 cognitive biases, 29 personality traits, 17 bias mechanisms, 16 breathing techniques, and more. Also on [HuggingFace](https://huggingface.co/datasets/buley/behavioral-taxonomy). |
| [Utils](https://github.com/forkjoin-ai/utils) | `@affectively/utils` | MIT | API retry logic, consistent logging, and short URL generation. |

## Developer Tooling

| Package | npm | License | Description |
|---------|-----|---------|-------------|
| [Aeon Test](https://github.com/forkjoin-ai/aeon-test) | `@a0n/aeon-test` | MIT | Cross-platform isolated test runner for Bun, Node, and Deno with mock pollution prevention. |
| [DevOps Scripts](https://github.com/forkjoin-ai/devops-scripts) | `@affectively/devops-scripts` | MIT | Monorepo automation for changed-file testing, type-checking, and accessibility audits. |
| [Stripper](https://github.com/forkjoin-ai/stripper) | -- | MIT | Source code comment and whitespace stripping utility. |
| [Trace Lint](https://github.com/forkjoin-ai/trace-lint) | `@affectively/trace-lint` | MIT | Extensible linting framework for Chrome/DevTools trace files with loop detection rules. |

## WASM Engines

High-performance Rust modules compiled to WebAssembly for near-native speed in the browser and Node.js.

| Module | npm | License | Description |
|--------|-----|---------|-------------|
| [Confetti Physics](https://github.com/forkjoin-ai/confetti-physics) | `@affectively/confetti-physics` | MIT | Physics-based confetti celebrations with fluid dynamics, haptic feedback, and procedural audio. |
| [Entrainment Audio](https://github.com/forkjoin-ai/entrainment-audio) | -- | MIT | Audio entrainment and binaural beat generation. |
| [Synthetic Watermark](https://github.com/forkjoin-ai/synthetic-watermark) | -- | MIT | Watermarking for synthetic/AI-generated content. |
| [wasm-analytics-engine](https://github.com/forkjoin-ai/wasm-analytics-engine) | `@affectively/wasm-analytics-engine` | MIT | Metrics computation, event processing, and funnel analytics. |
| [wasm-audio-processor](https://github.com/forkjoin-ai/wasm-audio-processor) | `@affectively/wasm-audio-processor` | MIT | Audio mixing, volume adjustment, silence generation, and µ-law encoding. |
| [wasm-cache-ops](https://github.com/forkjoin-ai/wasm-cache-ops) | `@affectively/wasm-cache-ops` | MIT | Batch caching, LZ4-style compression, eviction policies, and hashing. |
| [wasm-data-aggregator](https://github.com/forkjoin-ai/wasm-data-aggregator) | `@affectively/wasm-data-aggregator` | MIT | Statistical analysis, grouping, and time-series aggregation. |
| [wasm-graph-algorithms](https://github.com/forkjoin-ai/wasm-graph-algorithms) | `@affectively/wasm-graph-algorithms` | MIT | Cycle detection, DAG operations, pathfinding (Dijkstra/A*), and topological sort. |
| [wasm-image-utils](https://github.com/forkjoin-ai/wasm-image-utils) | `@affectively/wasm-image-utils` | MIT | Base64 encoding/decoding, format detection, and image validation. |
| [wasm-text-processor](https://github.com/forkjoin-ai/wasm-text-processor) | `@affectively/wasm-text-processor` | MIT | Pattern matching, entity extraction, and text scoring. |

## Applications

| Project | License | Description |
|---------|---------|-------------|
| [FooFoo](https://github.com/forkjoin-ai/foofoo) | MIT | Experimental application sandbox. |
| [Happy](https://github.com/forkjoin-ai/happy) | MIT | Happiness and wellbeing tracking application. |

## Documentation

| Project | Description |
|---------|-------------|
| [Deprecated](https://github.com/forkjoin-ai/deprecated) | Archive of deprecated packages and modules. |
| [Monorepo](https://github.com/forkjoin-ai/monorepo) | Primary development monorepo. |
| [Neural Wiki](https://github.com/forkjoin-ai/neutral-wiki) | Neural project documentation. |
| [Wiki](https://github.com/forkjoin-ai/emotions-wiki) | Project wiki and knowledge base. |

## License

Copyright Taylor William Buley. All rights reserved.

- **Code packages**: MIT
- **Data packages**: CC-BY-4.0
- **ONNX models**: Same license as base model (see individual model cards)
- **Fine-tuned models**: Apache 2.0 (inherits from SmolLM2 base)
