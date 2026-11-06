# Mabasha R

**Associate Engineer at KTern.AI** · *Chennai, India*  
Specializing in **Agentic AI**, **LLM Systems Engineering**, and **Enterprise SAP S/4HANA Transformation**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mabasha%20R-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mabasha-r/)
[![PyPI](https://img.shields.io/badge/PyPI-graphrag--atlas-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/graphrag-atlas/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Live%20Demo-10B981?style=flat-square&logo=googlechrome&logoColor=white)](https://coders2345.github.io/Mabasha-Portfolio)
[![Email](https://img.shields.io/badge/Email-mabasham52%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mabasham52@gmail.com)

---

## 🏛️ Executive Summary

I build production-grade agentic workflows, LLM orchestration pipelines on AWS Bedrock, and hybrid retrieval architectures (GraphRAG, Model Context Protocol) designed to withstand the rigor of enterprise environments.

My work focuses on bridging the gap between modern generative AI and complex transactional backends:
- **Agentic AI in Enterprise:** Developed end-to-end agents converting unstructured business inputs into structured functional specifications compliant with **SAP WRICEF development standards**.
- **Hybrid & Graph Retrieval:** Architected [`graphrag-atlas`](https://github.com/R-Mabasha/graphrag-atlas) (published on PyPI), unifying Lucene BM25, HNSW dense vectors, AST hierarchies, and bounded `$graphLookup` inside a single MongoDB Atlas cluster to avoid multi-database sprawl.
- **Enterprise Integration:** Bridging cloud runtimes with SAP S/4HANA landscapes, SAP Integration Suite / CPI, and SAP BTP / Cloud Foundry.

---

## 🌟 Featured Engineering Projects

<table>
  <thead>
    <tr>
      <th width="35%">Project</th>
      <th width="65%">Architectural Overview & Highlights</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="top">
        <a href="https://github.com/R-Mabasha/graphrag-atlas"><strong>graphrag-atlas</strong></a><br />
        <a href="https://pypi.org/project/graphrag-atlas/"><img src="https://img.shields.io/pypi/v/graphrag-atlas.svg?color=blue&style=flat-square" alt="PyPI" /></a>
        <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square" alt="MIT" />
      </td>
      <td>
        <strong>Single-Store Hybrid GraphRAG for MongoDB Atlas</strong><br />
        An open-source Python framework eliminating multi-database sprawl (no separate Neo4j or vector DB). Implements concurrent BM25 + Vector search, bounded 2-hop graph traversal, a <code>Hub Guard</code> circuit breaker (<code>degree &le; 200</code>) against super-node latency spikes, two-tier hierarchical tenancy, and chunk-level SHA-256 diff caching.
        <br /><code>pip install graphrag-atlas</code>
      </td>
    </tr>
    <tr>
      <td valign="top">
        <a href="https://github.com/R-Mabasha/antigravity-project-memory"><strong>antigravity-project-memory</strong></a><br />
        <img src="https://img.shields.io/badge/Protocol-MCP-purple?style=flat-square" alt="MCP" />
        <img src="https://img.shields.io/badge/Latency-Sub--2ms-brightgreen?style=flat-square" alt="Latency" />
      </td>
      <td>
        <strong>Production-Grade Zero-Dependency MCP Memory Server</strong><br />
        A Model Context Protocol (MCP) server providing cross-conversation contextual memory, persistent semantic indexing, and sub-2ms BM25 hybrid RAG for autonomous agent workspaces.
      </td>
    </tr>
    <tr>
      <td valign="top">
        <a href="https://github.com/R-Mabasha/Multi-Agent-Mcp"><strong>Multi-Agent-Mcp</strong></a><br />
        <img src="https://img.shields.io/badge/Agents-Nexus-orange?style=flat-square" alt="Agents" />
        <img src="https://img.shields.io/badge/Isolation-Git--Sandboxed-blue?style=flat-square" alt="Git Sandbox" />
      </td>
      <td>
        <strong>Git-Sandboxed Multi-Agent Orchestration Nexus</strong><br />
        A model-agnostic MCP server enabling teams of autonomous coding agents to run isolated experiments on branched git worktrees with strict permission gates and automated reconciliation.
      </td>
    </tr>
    <tr>
      <td valign="top">
        <a href="https://github.com/R-Mabasha/Vision-Stream"><strong>Vision-Stream</strong></a><br />
        <img src="https://img.shields.io/badge/Hackathon-Gemini%203-blue?style=flat-square" alt="Gemini 3" />
        <img src="https://img.shields.io/badge/Framework-React%2019%20%2B%20GenAI-3178C6?style=flat-square" alt="React 19" />
      </td>
      <td>
        <strong>Real-Time Multimodal AI Stream Processing</strong><br />
        Built for the Gemini 3 Hackathon. Processes live multi-modal video and sensor streams with low-latency LLM streaming, automated event classification, and responsive modern UI components.
      </td>
    </tr>
  </tbody>
</table>

---

## 📝 Technical Articles & Architecture Notes

Practical engineering insights drawn from building production enterprise AI systems:

- **[Why Standard Vector RAG Struggles with SAP Enterprise Data](https://www.linkedin.com/in/mabasha-r/)**  
  *Semantic similarity vs. deterministic business-key lookups.* Analyzing why vector embeddings fail on exact identifiers (Material, Plant, Batch) and demonstrating when to route queries between Lexical BM25, Property Graphs, and Tool-Using / Agentic RAG.
- **[OCR Fails on SAP Screens: ColPali vs. Intelligent Layout Routing](https://www.linkedin.com/in/mabasha-r/)**  
  *Evaluating multi-vector visual retrieval (ColPali) vs. text chunking on dense enterprise documents (Fiori screens, ALV tables, BEx outputs).* Why intelligent layout routing by document density yields 10x lower embedding costs without sacrificing layout comprehension.

---

## 🛠️ Technology & Domain Competencies

<table>
  <tr>
    <td width="25%"><strong>AI & LLM Systems</strong></td>
    <td>Agentic Workflows, AWS Bedrock, Model Context Protocol (MCP), Prompt Orchestration, LangChain, GraphRAG, Reciprocal Rank Fusion (RRF), Cross-Encoder Rerankers, Dense Embeddings (HNSW)</td>
  </tr>
  <tr>
    <td><strong>Enterprise & SAP</strong></td>
    <td>SAP S/4HANA Transformation, WRICEF Documentation Standards, SAP Integration Suite / CPI, SAP BTP, Cloud Foundry, ITIL v4 Fundamentals</td>
  </tr>
  <tr>
    <td><strong>Languages</strong></td>
    <td>Python, TypeScript, JavaScript, SQL (PostgreSQL), Lua</td>
  </tr>
  <tr>
    <td><strong>Data & Backend</strong></td>
    <td>MongoDB Atlas (Search, Vector, GraphLookup), PostgreSQL, Redis, FastAPI, Next.js, Node.js, Docker, Linux, Git</td>
  </tr>
</table>

---

## 🏆 Honors & Recognitions

- ⭐ **Star of the Month at KTern.AI** — Awarded for contributions across enterprise AI automation, data lineage tracing, and SAP landscape transformation.
- 🥇 **Winner — Smart India Hackathon 2023** — Solved problem statement 1313 presented by the Ministry of Coal.
- 🏅 **Finalist — Smart India Hackathon 2022** & Grand Finalist at PSG iTech Hack Fest 2023.
- 🎓 **B.Tech in Artificial Intelligence & Data Science** — Rathinam Technical Campus, Coimbatore.

---

## 📬 Let's Connect

- **LinkedIn:** [linkedin.com/in/mabasha-r](https://www.linkedin.com/in/mabasha-r/)
- **Interactive Portfolio:** [coders2345.github.io/Mabasha-Portfolio](https://coders2345.github.io/Mabasha-Portfolio)
- **Email:** [mabasham52@gmail.com](mailto:mabasham52@gmail.com)
