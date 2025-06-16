# Manifesto: The Open Agentic Knowledge (OAK) repository

[![Discord](https://img.shields.io/badge/JOIN%20OUR%20DISCORD-COMMUNITY-7289DA?style=plastic&logo=discord&logoColor=white)](https://discord.gg/yrxmDZWMqB)

> **Join our community!** Connect with contributors and users on [Discord](https://discord.gg/yrxmDZWMqB) to discuss ideas, ask questions, and collaborate on the OAK repository.

Agents depend on APIs as much as AI. Chatbots chat, but agents act, and they act through APIs: web APIs, network protocols, OS APIs, local application APIs, CLI interfaces, SDKs and programming libraries, configuration files, and more. To realize this potential, we must build a common knowledge foundation that empowers AI to interact with the world's APIs reliably and without artificial barriers or unnecessary intermediaries.

## Principles

1. **Documentation Is Essential Infrastructure**  
   While humans can work around incomplete API documentation through online research and experimentation, agent reliability depends on comprehensive documentation. Documentation is the map by which agents can navigate their action space. Good documentation was once a "nice-to-have", but is now a "need-to-have."

2. **Traditional API Integration Involved Middlemen**  
   Before generative AI, the complexity of API integration gave rise to an ecosystem of intermediaries such as API marketplaces, aggregators, and integration platforms. These companies helped human developers integrate public APIs, while imposing additional costs and often creating vendor lock-in.

3. **AI Eliminates The Need For Intermediaries**  
   Unlike human developers, AI doesn't require APIs to be simplified or aggregated — it just needs good documentation. This fundamental shift eliminates the need for middlemen, since AI can go direct.

4. **AI Can Generate Documentation**  
   The same technology that demands better documentation also enables its creation. AI enables automatic pre-generation of high-quality documentation from code, web resources, PDFs, production telemetry, and even through experimentation. This will create a virtuous cycle of improvement.

5. **An Open Knowledge Layer Is Necessary**  
   This virtuous cycle will be maximised by a collective open-source movement to establish a comprehensive agentic knowledge layer: detailed, AI-optimized information about every machine interface that AI agents may use.

6. **Standards Prevent Fragmentation**  
   To avoid fragmentation and proprietary lock-in, we must build upon established, open standards. The [OpenAPI Specification](https://www.openapis.org/), owned by the Linux Foundation, already provides a robust foundation with its vibrant ecosystem of tools and services.

7. **Building on OpenAPI**  
   As agent capabilities expand across new machine interfaces, additional declarative schemas will be required to capture these domains with the same rigor OpenAPI brings to HTTP APIs. We will support these standards, and propose additional extensions as necessary to make them even more valuable to agents. Furthermore, the OpenAPI Initiative's [Arazzo](https://www.openapis.org/arazzo) specification defines composable complex workflows built from OpenAPI operations, providing a timely declarative format needed for representing procedural use of APIs. OAK repositories should support the development of workflow standards like Arazzo, which encode tool-level knowledge that is essential for agents.  

8. **MCP and OpenAPI Are Complementary**  
   The future of AI needs both [Model Context Protocol (MCP)](https://docs.anthropic.com/en/docs/agents-and-tools/mcp) and OpenAPI standards working in tandem. While OpenAPI and Arazzo provide the standard declarative format for representing agentic tool knowledge, MCP offers an ergonomic format for agents to access this knowledge, creating a complete ecosystem for AI interaction with APIs.

9. **Open Standards Ensure Interoperability**  
   By embracing open standards like OpenAPI and Arazzo, we ensure AI agents can reliably discover, understand, and interact with APIs regardless of which model or platform they use, guaranteeing portability and longevity independent of any single company.

10. **Declarative Schemas Enable Runtime Agentic Composition**
   In contrast to traditional software, agents can bind capabilities dynamically at runtime, not at design time. Declarative, machine-readable schemas allow agents to plan, synthesize, and execute actions safely and reliably on demand — enabling flexible, scalable autonomy without brittle prompt engineering or hardcoded toolsets.

11. **Federated Discoverability Supports a Global Knowledge Layer**
   OAK is a global network of interoperable repositories. Each OAK repository should expose machine-readable discovery metadata — beginning with an `oak.txt` file listing URLs of other OAK repositories, allowing other repositories, agents, and crawlers to automatically discover, import, or synchronize agentic knowledge across the ecosystem.

12. **Permissive Licensing Ensures Maximal Reuse**
   To enable frictionless reuse, federation, and integration, OAK repositories should adopt fully permissive open-source licenses (such as MIT) for both documentation and code. This guarantees that knowledge remains portable, remixable, and legally interoperable across the full agentic software stack.

13. **Community Collaboration Accelerates Progress**  
    This knowledge layer must be community-driven, welcoming contributions and feedback from both humans and AI to rapidly expand, refine and converge API knowledge. Together, we will build the most complete and AI-optimal representation of the world's APIs.

We invite developers, organizations, and AI builders to join this mission of creating an open-source knowledge layer for all the world's APIs, built on established open standards. Together, we will provide all agents with the knowledge necessary to reliably use the world's APIs, without vendor lock-in, risk of abandonment, or tolls paid to gatekeepers.

