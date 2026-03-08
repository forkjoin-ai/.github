# AFFECTIVELY Open Source Ecosystem

Welcome to the **AFFECTIVELY** open-source ecosystem. We are dedicated to democratizing affective intelligence, ensuring that the future of AI is emotionally resonant, ethically grounded, and technically robust.

## Core Packages

We have open-sourced **12 key components** of our platform, available on GitHub and npm.

### Data & Taxonomy
| Package | GitHub | Description |
|---------|--------|-------------|
| **@affectively/behavioral-taxonomy** | [affectively-ai/behavioral-taxonomy](https://github.com/affectively-ai/behavioral-taxonomy) | 1,140+ behavioral loops, emotions, cognitive biases, and personality traits. Licensed under CC-BY-4.0. |

### WebAssembly (WASM) Modules
High-performance Rust modules compiled to WASM for near-native speed in the browser and Node.js.

| Package | GitHub | Description |
|---------|--------|-------------|
| **@affectively/wasm-audio-processor** | [wasm-audio-processor](https://github.com/affectively-ai/wasm-audio-processor) | Audio mixing, volume control, silence generation, and µ-law encoding. |
| **@affectively/wasm-text-processor** | [wasm-text-processor](https://github.com/affectively-ai/wasm-text-processor) | High-speed pattern matching, entity extraction, and text scoring. |
| **@affectively/wasm-analytics-engine** | [wasm-analytics-engine](https://github.com/affectively-ai/wasm-analytics-engine) | Real-time metrics computation, event processing, and funnels. |
| **@affectively/wasm-graph-algorithms** | [wasm-graph-algorithms](https://github.com/affectively-ai/wasm-graph-algorithms) | DAG operations, pathfinding (Dijkstra/A*), and cycle detection. |
| **@affectively/wasm-data-aggregator** | [wasm-data-aggregator](https://github.com/affectively-ai/wasm-data-aggregator) | Statistical analysis, grouping, and time-series aggregation. |
| **@affectively/wasm-cache-ops** | [wasm-cache-ops](https://github.com/affectively-ai/wasm-cache-ops) | Batch caching operations, compression (LZ4-style), and eviction policies. |
| **@affectively/wasm-image-utils** | [wasm-image-utils](https://github.com/affectively-ai/wasm-image-utils) | Fast Base64 encoding/decoding, format detection, and validation. |

### Frameworks & Tools
Developer tools to build empathetic and robust AI systems.

| Package | GitHub | Description |
|---------|--------|-------------|
| **@affectively/mcp-framework** | [mcp-framework](https://github.com/affectively-ai/mcp-framework) | Complete scaffolding for building **Model Context Protocol (MCP)** servers with auth & analytics. |
| **@affectively/bun-isolated-runner** | [bun-isolated-runner](https://github.com/affectively-ai/bun-isolated-runner) | Cross-platform test runner for Bun that prevents mock pollution via subprocess isolation. |
| **@affectively/devops-scripts** | [devops-scripts](https://github.com/affectively-ai/devops-scripts) | Monorepo automation: changed-file testing, type-checking, and accessibility audits. |
| **@affectively/utils** | [utils](https://github.com/affectively-ai/utils) | Essential utilities: API retry logic, consistent logging, and short URL generation. |

## Installation

All packages are available on npm under the `@affectively` scope.

```bash
# Example
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

## Browser AI Models (ONNX)

We convert, quantize, and publish production-ready ONNX models for in-browser inference with [transformers.js](https://huggingface.co/docs/transformers.js). All models on [HuggingFace](https://huggingface.co/affectively-ai).

| Model | Task | Size |
|-------|------|------|
| [roberta-base-go-emotions-onnx](https://huggingface.co/affectively-ai/roberta-base-go-emotions-onnx) | Emotion detection (28 labels) | ~124 MB |
| [distilbert-base-uncased-emotion-onnx](https://huggingface.co/affectively-ai/distilbert-base-uncased-emotion-onnx) | Emotion classification (6 labels) | ~67 MB |
| [emotion-english-distilroberta-base-onnx](https://huggingface.co/affectively-ai/emotion-english-distilroberta-base-onnx) | Emotion classification (7 labels) | ~82 MB |
| [twitter-roberta-base-sentiment-onnx](https://huggingface.co/affectively-ai/twitter-roberta-base-sentiment-onnx) | Sentiment analysis (3-class) | ~124 MB |
| [deberta-v3-base-mnli-onnx](https://huggingface.co/affectively-ai/deberta-v3-base-mnli-onnx) | Zero-shot classification | ~243 MB |
| [bart-large-cnn-onnx](https://huggingface.co/affectively-ai/bart-large-cnn-onnx) | Text summarization | ~493 MB |
| [nllb-200-1.3B-onnx](https://huggingface.co/affectively-ai/nllb-200-1.3B-onnx) | Translation (200 languages) | ~1.81 GB |
| [nllb-200-distilled-1.3B-onnx](https://huggingface.co/affectively-ai/nllb-200-distilled-1.3B-onnx) | Translation (200 languages) | ~1.81 GB |

## Links

- **Website**: [aeonflux.dev](https://aeonflux.dev)
- **Documentation**: [docs.aeonflux.dev](https://docs.aeonflux.dev)
- **Storybook**: [storybook.aeonflux.dev](https://storybook.aeonflux.dev)
- **HuggingFace**: [huggingface.co/affectively-ai](https://huggingface.co/affectively-ai)
- **GitHub**: [github.com/affectively-ai](https://github.com/affectively-ai)

---
Made by [AFFECTIVELY](https://aeonflux.dev)
