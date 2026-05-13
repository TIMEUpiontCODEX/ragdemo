# Project Structure

```text
rag/
|-- app/
|   |-- main.py
|   |-- agent/
|   |   |-- decomposer.py
|   |   |-- intent.py
|   |   |-- memory.py
|   |   |-- orchestrator.py
|   |   `-- verifier.py
|   |-- api/
|   |   `-- chat.py
|   |-- core/
|   |   |-- config.py
|   |   |-- logger.py
|   |   `-- schemas.py
|   |-- llm/
|   |   |-- client.py
|   |   `-- prompts.py
|   |-- multimodal/
|   |   |-- image_parser.py
|   |   |-- ocr.py
|   |   `-- vision_caption.py
|   |-- rag/
|   |   |-- generator.py
|   |   |-- indexer.py
|   |   |-- loader.py
|   |   |-- reranker.py
|   |   |-- retriever.py
|   |   `-- splitter.py
|   `-- utils/
|       |-- base64_utils.py
|       `-- text_utils.py
|-- data/
|   `-- raw/
|       `-- ...
|-- docs/
|   `-- ...
|-- scripts/
|   |-- build_kb.py
|   |-- evaluate.py
|   `-- run_server.py
|-- tests/
|   |-- test_chat_api.py
|   |-- test_multimodal.py
|   `-- test_retriever.py
|-- Dockerfile
|-- LICENSE
|-- README.md
`-- requirements.txt
```

## Notes

- `app/`: core application code, including API, RAG, agent, multimodal, LLM, and shared utilities.
- `data/`: source knowledge-base materials and related data files.
- `docs/`: project documents, API references, and validation reports.
- `scripts/`: scripts for building the knowledge base, evaluation, and server startup.
- `tests/`: automated tests for core features.
