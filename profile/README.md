## Introducing the Gaianet AI network

### Gaianet node

Each Gaianet node provides a specialized API service that encapsulates a unique combination of

* a specialized and fine-tuned LLM (e.g., an LLM that excels in answering questions about the Rust programming language)
* a domain-specific knowledge base (e.g., knowledge about the WasmEdge project)
* an inference app that manages the context and history of conversations (e.g., RAG and MemGPT prompt injection)
* compute resources required to run the LLM app as an API service (e.g., a Nvidia GPU or a Mac M3 device)

The Gaianet node API service is fully compatible with the OpenAI JSON spec, and hence each Gaia node can function as an alternative backend for OpenAI-based frontends or agents.

### Gaianet protocol

The Gaianet protocol connects and incentivizes Gaianet nodes to form a coherent network of web services for AI agents. It provides a mechanism to discovery, connect, and pay for Gaianet node services through a decentralized marketplace.

<div align="center">
  
![Gaianet protocol](https://github.com/gaia-network/.github/raw/main/profile/gaia_arch.png)

</div>
