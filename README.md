# Agent Development Experiments

A collection of Python/Jupyter notebooks exploring LangChain, LangGraph, OpenAI models, and retrieval-augmented generation.

## Notebook guide

- Model calls, parameters, batching, and streaming
- Prompt templates and few-shot messages
- String, CSV, and datetime output parsers
- Runnable chains, parallel composition, and lambda functions
- Document loading and splitting
- Embeddings, vector stores, retrieval, and generation
- Basic graph execution

The examples are individual experiments rather than a single packaged agent application. `RAGFiles/` contains retrieval inputs; `intro-to-ds-lectures/` contains additional learning material.

## Environment

A pinned `requirements.txt` is supplied. Use an isolated Python environment and review each notebook's imports before running it:

```sh
python -m venv .venv
# Activate the environment using your platform's command.
python -m pip install -r requirements.txt
jupyter lab
```

The model notebook records a Python 3.10 kernel, but compatibility of the full pinned environment has not been verified.

## API access and data

Some notebooks require external model access and may incur API charges. Configure credentials outside the repository and inspect cells before execution. Use synthetic data, and review saved notebook outputs before sharing them.

## Status

These notebooks document hands-on learning experiments. Preserve attribution attached to any bundled learning material.

