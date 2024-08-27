## Introducing the Gaia AI network

[Getting started running a Gaia node on your personal computer!](https://github.com/GaiaNet-AI/gaianet-node/blob/main/README.md)

### Gaia node

Each Gaia node provides a specialized API service that encapsulates a unique combination of

* a specialized and fine-tuned LLM (e.g., an LLM that excels in answering questions about the Rust programming language)
* a domain-specific knowledge base (e.g., knowledge about the WasmEdge project)
* an inference app that manages the context and history of conversations (e.g., RAG and MemGPT prompt injection)
* compute resources required to run the LLM app as an API service (e.g., a Nvidia GPU or a Mac M3 device)

The Gaia node API service is fully compatible with the OpenAI JSON spec, and hence each Gaia node can function as an alternative backend for OpenAI-based frontends or agents.

### Gaia domain

Gaia nodes are organized into Gaia domains so that they can be discovered and accessed from the world. A Gaia domain groups together nodes that have similiar purposes, and provides a single Internet domain for all its node agents. For example, agents that answer student questions at University of California at Berkeley could be organized under the `gaianet.berkeley.edu` domain. The domain owner vouches for its node agents by puttings its reputation behind the agents. Hence, a staking mechanism is designed for the domains. If a domain is found to have too many inactive or even misbehaving agents, the domain stakers could be slashed.

### Gaia protocol

The Gaia protocol connects and incentivizes Gaia nodes and domains to form a coherent network of web services for AI agents. It provides a mechanism to discover, connect to, and pay for Gaia node services through a decentralized marketplace. It also incentivizes domains to manage node agents through a staking program. Furthermore, the Gaia protocol connects model creators (i.e., people who have skills to finetune models) and knowledge providers to node operators through a marketplace.

<div align="center">
  
<img width="1375" alt="image" src="https://github.com/user-attachments/assets/375bf608-bc9a-4ff2-b7c4-c5169280de59">


</div>


### Join us!

[Website](https://www.gaianet.ai/) | [Twitter](https://twitter.com/Gaianet_AI) | [Discord](https://discord.gg/x8gfzVFC) | [Telegram](https://t.me/Gaianet_AI) | [Medium](https://medium.com/@Gaianet.ai)
