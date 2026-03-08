# AFFECTIVELY Open Source Ecosystem

AFFECTIVELY is an emotion tracking and analysis platform that helps people hold onto their clarity. We build local-first, privacy-respecting tools that run AI inference entirely in-browser and at the edge — zero server cost, zero latency, your data stays yours.

The **Aeon** ecosystem is our open-source infrastructure: distributed sync, collaborative surfaces, edge AI, WASM engines, and the tooling to tie it all together.

- **Website**: [aeonflux.dev](https://aeonflux.dev)
- **Documentation**: [docs.aeonflux.dev](https://docs.aeonflux.dev)
- **Storybook**: [storybook.aeonflux.dev](https://storybook.aeonflux.dev)
- **HuggingFace**: [huggingface.co/affectively-ai](https://huggingface.co/affectively-ai)
- **GitHub**: [github.com/affectively-ai](https://github.com/affectively-ai)

## Browser AI Models (ONNX)

Production-ready ONNX models for in-browser inference with [transformers.js](https://huggingface.co/docs/transformers.js). All models run entirely client-side.

| Model | Task | Size | HuggingFace |
|-------|------|------|-------------|
| RoBERTa GoEmotions | Emotion detection (28 labels) | ~124 MB | [roberta-base-go-emotions-onnx](https://huggingface.co/affectively-ai/roberta-base-go-emotions-onnx) |
| DistilBERT Emotion | Emotion classification (6 labels) | ~67 MB | [distilbert-base-uncased-emotion-onnx](https://huggingface.co/affectively-ai/distilbert-base-uncased-emotion-onnx) |
| DistilRoBERTa Emotion | Emotion classification (7 labels) | ~82 MB | [emotion-english-distilroberta-base-onnx](https://huggingface.co/affectively-ai/emotion-english-distilroberta-base-onnx) |
| Twitter RoBERTa Sentiment | Sentiment analysis (3-class) | ~124 MB | [twitter-roberta-base-sentiment-onnx](https://huggingface.co/affectively-ai/twitter-roberta-base-sentiment-onnx) |
| DeBERTa v3 Zero-Shot | Zero-shot classification | ~243 MB | [deberta-v3-base-mnli-onnx](https://huggingface.co/affectively-ai/deberta-v3-base-mnli-onnx) |
| BART-Large CNN | Text summarization | ~493 MB | [bart-large-cnn-onnx](https://huggingface.co/affectively-ai/bart-large-cnn-onnx) |
| NLLB-200 1.3B | Translation (200 languages) | ~1.81 GB | [nllb-200-1.3B-onnx](https://huggingface.co/affectively-ai/nllb-200-1.3B-onnx) |
| NLLB-200 Distilled 1.3B | Translation (200 languages) | ~1.81 GB | [nllb-200-distilled-1.3B-onnx](https://huggingface.co/affectively-ai/nllb-200-distilled-1.3B-onnx) |

## Aeon Ecosystem

| Project | Description |
|---------|-------------|
| [Aeon](https://github.com/affectively-ai/aeon) | Distributed synchronization, schema versioning, and conflict resolution for real-time collaborative applications. |
| [Aeon Flux](https://github.com/affectively-ai/aeon-flux) | Collaborative page surface with CRDT-based flux state, Edge Side Inference (ESI), and zero-CLS rendering. Pages that think. |
| [Aeon Flux Capacitor](https://github.com/affectively-ai/aeon-flux-capacitor) | Embedding-first collaborative WYSIWYG editor where text is a derivative of the vector space. |
| [Aeon Foundation](https://github.com/affectively-ai/aeon-foundation) | The complete Aeon stack in one package: distributed sync, collaborative pages, state management, relay transport, edge AI, neural graph database, and decentralized auth. |
| [Aeon Shell](https://github.com/affectively-ai/aeon-shell) | Local-first operating surface hosting live shell canvas, graph runtime, route-aware surfaces, and native `aeon://` addressing. |
| [Aeon Shell Core](https://github.com/affectively-ai/aeon-shell-core) | Canonical runtime surface for shell consumers with host/plugin orchestration and engine registry security boundaries. |
| [Aeon TUI](https://github.com/affectively-ai/aeon-tui) | Ink-based terminal runtime with behavior parity to the Aeon shell, command palette flows, and integrated PTY panes. |
| [Aeon Stack](https://github.com/affectively-ai/aeon-stack) | Zero-dependency performance layer with measured vertical stack windowing, velocity-adaptive overscan, DOM collapse, and speculative rendering. |
| [Aeon Forge](https://github.com/affectively-ai/aeon-forge) | Shared deployment and routing primitives for deploy-planning surfaces and the Forge CLI/CD system. |
| [Aeon IDE](https://github.com/affectively-ai/aeon-ide) | IDE integrations and developer experience tooling for Aeon. |
| [Aeon Icons](https://github.com/affectively-ai/aeon-icons) | Icon library for Aeon web and native applications. |
| [Goodchild](https://github.com/affectively-ai/aeon-flags) | UCAN-enforced feature gating daemon at the edge. Replaces centralized feature flag SaaS (LaunchDarkly, CloudBees) with deterministic, cryptographic entitlements. |
| [Aeon IAM](https://github.com/affectively-ai/aeon-iam) | Device-rooted UCAN identity and access management orchestration. |
| [Aeon Invite](https://github.com/affectively-ai/aeon-invite) | Beta shield, invite codes, waitlist management, and funnel analytics for controlled rollouts. |
| [Aeon Preferences](https://github.com/affectively-ai/aeon-preferences) | Federated user preferences via Dash DB. |
| [Aegis](https://github.com/affectively-ai/aeon-auth) | Zero-dependency decentralized identity and access control built on Web Crypto API. UCAN capabilities, DID resolution, ECDSA signatures, and XPath-like node selection for surgical data-tree authorization. |

## Local-First Data and Edge

| Project | Description |
|---------|-------------|
| [Dash](https://github.com/affectively-ai/dash) | Multi-layer edge storage and CRDT sync engine supporting Yjs, Automerge, WebSocket, WebTransport, and WebRTC. |
| [Dash CLI](https://github.com/affectively-ai/dash-cli) | The sovereign, local-first database for your command line. |
| [Neural](https://github.com/affectively-ai/neural) | Distributed monorepo for neural/AI infrastructure. |
| [Edgework CLI](https://github.com/affectively-ai/edgework-cli) | CLI for edgework.ai — accessible AI at the edge. |
| [Edgework SDK](https://github.com/affectively-ai/edgework-sdk) | SDK for building edgework.ai integrations. |
| [Zedge](https://github.com/affectively-ai/zedge) | Companion sidecar with inference bridge and compute pool node functionality. |

## Orchestration and Protocols

| Project | Description |
|---------|-------------|
| [MCP Framework](https://github.com/affectively-ai/mcp-framework) | Framework for building Model Context Protocol servers with authentication, tool registration, and analytics. |
| [Workflows](https://github.com/affectively-ai/workflows) | Production-grade workflow orchestration and composition engine for autonomous agents and CI/CD pipelines. |
| [Orchestrator](https://github.com/affectively-ai/orchestrator) | Task orchestration and agent coordination engine. |
| [Slash Commands](https://github.com/affectively-ai/slash-commands) | Slash command framework for conversational interfaces. |

## Security and Identity

## Data and Taxonomy

| Project | Description |
|---------|-------------|
| [Behavioral Taxonomy](https://github.com/affectively-ai/behavioral-taxonomy) | 1,140+ behavioral loops, emotions, cognitive biases, and personality traits. Licensed CC-BY-4.0. |
| [Utils](https://github.com/affectively-ai/utils) | API retry logic, consistent logging, and short URL generation. |

## Developer Tooling

| Project | Description |
|---------|-------------|
| [Bun Isolated Runner](https://github.com/affectively-ai/bun-isolated-runner) | Run Bun tests in isolated subprocesses to prevent mock pollution and global state leakage. |
| [DevOps Scripts](https://github.com/affectively-ai/devops-scripts) | Monorepo automation for changed-file testing, type-checking, and accessibility audits. |
| [Trace Lint](https://github.com/affectively-ai/trace-lint) | Extensible linting framework for Chrome/DevTools trace files with loop detection rules. |

## WASM Engines

High-performance Rust modules compiled to WebAssembly for near-native speed in the browser and Node.js.

| Module | Description |
|--------|-------------|
| [wasm-analytics-engine](https://github.com/affectively-ai/wasm-analytics-engine) | Metrics computation, event processing, and funnel analytics. |
| [wasm-audio-processor](https://github.com/affectively-ai/wasm-audio-processor) | Audio mixing, volume adjustment, silence generation, and µ-law encoding. |
| [wasm-cache-ops](https://github.com/affectively-ai/wasm-cache-ops) | Batch caching, LZ4-style compression, eviction policies, and hashing. |
| [wasm-cognitive-gate](https://github.com/affectively-ai/wasm-cognitive-gate) | Cognitive gating and policy-style evaluation flows. |
| [wasm-data-aggregator](https://github.com/affectively-ai/wasm-data-aggregator) | Statistical analysis, grouping, and time-series aggregation. |
| [wasm-git-pack](https://github.com/affectively-ai/wasm-git-pack) | Git packfile parsing and low-level repository operations. |
| [wasm-graph-algorithms](https://github.com/affectively-ai/wasm-graph-algorithms) | Cycle detection, DAG operations, pathfinding (Dijkstra/A*), and topological sort. |
| [wasm-image-utils](https://github.com/affectively-ai/wasm-image-utils) | Base64 encoding/decoding, format detection, and image validation. |
| [wasm-text-processor](https://github.com/affectively-ai/wasm-text-processor) | Pattern matching, entity extraction, and text scoring. |
| [Confetti Physics](https://github.com/affectively-ai/confetti-physics) | Physics-based confetti celebrations with fluid dynamics, haptic feedback, and procedural audio. |
| [Synthetic Watermark](https://github.com/affectively-ai/synthetic-watermark) | Watermarking for synthetic/AI-generated content. |
| [Entrainment Audio](https://github.com/affectively-ai/entrainment-audio) | Audio entrainment and binaural beat generation. |

## Documentation

| Project | Description |
|---------|-------------|
| [Monorepo](https://github.com/affectively-ai/monorepo) | Primary development monorepo for the AFFECTIVELY platform. |
| [AFFECTIVELY Wiki](https://github.com/affectively-ai/emotions-wiki) | Project wiki and knowledge base. |
| [Neural Wiki](https://github.com/affectively-ai/neutral-wiki) | Neural project documentation. |

## Installation

All npm packages are available under the `@affectively` scope.

```bash
npm install @affectively/behavioral-taxonomy
npm install @affectively/mcp-framework
npm install @affectively/aeon-flux
```

## Contributing

We welcome contributions! Each repository has its own contribution guidelines.
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'feat: add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

- **Code Packages**: MIT License
- **Data Packages**: Creative Commons Attribution 4.0 (CC BY 4.0)
- **ONNX Models**: Same license as base model (see individual model cards)

---
Made by [AFFECTIVELY](https://aeonflux.dev)
