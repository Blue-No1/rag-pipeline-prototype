# Integration with Open-Weight LLM

- Start with local serving (vLLM) → call via OpenAI-compatible API.
- Keep prompt template simple; chunk size 512; top-k=3 retrieval.
- Later: add reranking; add caching.
