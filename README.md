# LLMs & GNNs for Advanced Reasoning — Lab Assignments

**Course:** LLMs & GNNs for Advanced Reasoning over Relational Data  
**Institution:** Escuela Colombiana de Ingeniería Julio Garavito

## Setup

```bash
pip install -r environment/requirements.txt
jupyter lab
```

Alternatively, each notebook includes a **Open in Colab** badge at the top.

## Structure

| Module | Labs | Topics |
|--------|------|--------|
| **Module I — Classical ML** | 1.1, 1.2 | Data exploration, decision trees, customer churn |
| **Module II — LLMs** | 2.1, 2.2, 2.3 | Open-source LLMs via Ollama, chatbots, basic RAG |
| **Module III — GNNs** | 3.1, 3.2, 3.3 | Graph data with NetworkX/PyG, GCN, GAT with attention |
| **Module IV — Hybrid** | 4.1, 4.2, 4.3 | Text-attributed graphs, GraphRAG on HotpotQA, G-Retriever |

## Working on exercises

Each notebook contains:
- **Infrastructure cells** — imports, data loading, helper functions. Run these as-is.
- **Exercise cells** — marked `# YOUR CODE HERE`. Replace `pass` / `raise NotImplementedError(...)` with your implementation.
- **Check cells** — `check_*()` calls that validate your implementation. A passing check prints a green confirmation.
- **`[Extension]`** exercises are optional and go beyond the core concepts.

## Hardware notes

All labs run on a standard laptop CPU. GPU is not required. HotpotQA data (~20 MB) is downloaded automatically on first run via the HuggingFace `datasets` library.
