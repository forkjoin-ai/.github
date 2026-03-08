# AFFECTIVELY Open Source Ecosystem

Welcome to the **AFFECTIVELY** open-source ecosystem. We are dedicated to democratizing affective intelligence, ensuring that the future of AI is emotionally resonant, ethically grounded, and technically robust.

- **Website**: [aeonflux.dev](https://aeonflux.dev)
- **Documentation**: [docs.aeonflux.dev](https://docs.aeonflux.dev)
- **Storybook**: [storybook.aeonflux.dev](https://storybook.aeonflux.dev)
- **HuggingFace**: [huggingface.co/affectively-ai](https://huggingface.co/affectively-ai)
- **GitHub**: [github.com/affectively-ai](https://github.com/affectively-ai)

## Browser AI Models (ONNX)

Production-ready ONNX models for in-browser inference with [transformers.js](https://huggingface.co/docs/transformers.js). All models run entirely client-side — zero server cost, zero latency, complete privacy.

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

## Agent Operating Environment

| Project | Description |
|---------|-------------|
| [Aeon](https://github.com/affectively-ai/aeon) | Core Aeon agent operating environment. |
| [Aeon Flux](https://github.com/affectively-ai/aeon-flux) | Reactive runtime and state model for Aeon experiences. |
| [Aeon Flux Capacitor](https://github.com/affectively-ai/aeon-flux-capacitor) | Embedding-first collaborative editor with vector-native workflows. |
| [Aeon Forge](https://github.com/affectively-ai/aeon-forge) | Aeon tooling and build surface for composing runtime capabilities. |
| [Aeon Foundation](https://github.com/affectively-ai/aeon-foundation) | Foundational services and substrate for the Aeon ecosystem. |
| [Aeon Shell](https://github.com/affectively-ai/aeon-shell) | Shell runtime for Aeon environments and host integrations. |
| [Aeon Shell Core](https://github.com/affectively-ai/aeon-shell-core) | Stable shared runtime surface for Aeon shell consumers. |
| [Aeon TUI](https://github.com/affectively-ai/aeon-tui) | Ink-based terminal runtime for Aeon shell behavior parity. |
| [Aeon Stack](https://github.com/affectively-ai/aeon-stack) | Full-stack application framework for the Aeon ecosystem. |
| [Aeon IDE](https://github.com/affectively-ai/aeon-ide) | IDE integrations and developer experience for Aeon. |
| [Aeon Icons](https://github.com/affectively-ai/aeon-icons) | Icon system for the Aeon ecosystem. |
| [Aeon Flags](https://github.com/affectively-ai/aeon-flags) | Feature flag system for Aeon applications. |
| [Aeon IAM](https://github.com/affectively-ai/aeon-iam) | Identity and access management for Aeon services. |
| [Aeon Invite](https://github.com/affectively-ai/aeon-invite) | Invitation and onboarding flows for Aeon. |
| [Aeon Preferences](https://github.com/affectively-ai/aeon-preferences) | User preference management for Aeon apps. |
| [Neural](https://github.com/affectively-ai/neural) | Open neural runtime and inference experiments. |

## Local-First Data and Edge Tooling

| Project | Description |
|---------|-------------|
| [Dash](https://github.com/affectively-ai/dash) | Multi-layer edge storage and CRDT sync engine for local-first applications. |
| [Dash CLI](https://github.com/affectively-ai/dash-cli) | Command-line interface for sovereign, local-first Dash databases. |
| [Edgework CLI](https://github.com/affectively-ai/edgework-cli) | Edge AI command-line client for edgework.ai workflows. |
| [Edgework SDK](https://github.com/affectively-ai/edgework-sdk) | SDK for building edgework.ai integrations. |
| [Zedge](https://github.com/affectively-ai/zedge) | Edge runtime and deployment tooling. |
| [Orchestrator](https://github.com/affectively-ai/orchestrator) | Task orchestration and agent coordination engine. |
| [Slash Commands](https://github.com/affectively-ai/slash-commands) | Slash command framework for conversational interfaces. |
| [MCP Framework](https://github.com/affectively-ai/mcp-framework) | Framework for building Model Context Protocol servers and integrations. |
| [Workflows](https://github.com/affectively-ai/workflows) | Production-grade orchestration and workflow composition engine. |

## Security, Identity, and Shared Foundations

| Project | Description |
|---------|-------------|
| [Auth](https://github.com/affectively-ai/auth) | Shared authentication, cryptographic utilities, and encryption primitives. |
| [Aegis](https://github.com/affectively-ai/aegis) | Security and policy enforcement layer. |
| [Behavioral Taxonomy](https://github.com/affectively-ai/behavioral-taxonomy) | 1,140+ behavioral loops, emotions, cognitive biases, and personality traits. |
| [Utils](https://github.com/affectively-ai/utils) | Shared utility package for common cross-project helpers. |

## Developer Experience and Governance

| Project | Description |
|---------|-------------|
| [Bun Isolated Runner](https://github.com/affectively-ai/bun-isolated-runner) | Bun-focused isolated test execution to prevent cross-test contamination. |
| [DevOps Scripts](https://github.com/affectively-ai/devops-scripts) | Monorepo automation for changed-file checks, testing, and audits. |
| [Trace Lint](https://github.com/affectively-ai/trace-lint) | Extensible Chrome trace linting with layered runtime governance rules. |

## WASM and Systems Modules

High-performance Rust modules compiled to WebAssembly for near-native speed in the browser and Node.js.

| Module | Description |
|--------|-------------|
| [wasm-analytics-engine](https://github.com/affectively-ai/wasm-analytics-engine) | Real-time metrics computation and event analytics. |
| [wasm-audio-processor](https://github.com/affectively-ai/wasm-audio-processor) | Audio mixing, encoding, and signal utilities. |
| [wasm-cache-ops](https://github.com/affectively-ai/wasm-cache-ops) | Cache compression, batching, and eviction helpers. |
| [wasm-cognitive-gate](https://github.com/affectively-ai/wasm-cognitive-gate) | Cognitive gating and policy-style evaluation flows. |
| [wasm-data-aggregator](https://github.com/affectively-ai/wasm-data-aggregator) | Statistical grouping and time-series aggregation. |
| [wasm-git-pack](https://github.com/affectively-ai/wasm-git-pack) | Git packfile parsing and low-level repository operations. |
| [wasm-graph-algorithms](https://github.com/affectively-ai/wasm-graph-algorithms) | Pathfinding, DAG analysis, and graph utilities. |
| [wasm-image-utils](https://github.com/affectively-ai/wasm-image-utils) | Fast image encode, decode, and validation helpers. |
| [wasm-text-processor](https://github.com/affectively-ai/wasm-text-processor) | Pattern matching, extraction, and text scoring. |
| [Confetti Physics](https://github.com/affectively-ai/confetti-physics) | Physics-oriented browser effects and rendering utilities. |
| [Synthetic Watermark](https://github.com/affectively-ai/synthetic-watermark) | Watermarking for synthetic/AI-generated content. |
| [Entrainment Audio](https://github.com/affectively-ai/entrainment-audio) | Audio entrainment and binaural beat generation. |

## Documentation and Infrastructure

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
- **Data Packages** (Behavioral Taxonomy): Creative Commons Attribution 4.0 (CC BY 4.0)
- **ONNX Models**: Same license as base model (see individual model cards)

---
Made by [AFFECTIVELY](https://aeonflux.dev)
