# Mabasha R.

**AI Systems Engineer & Architect** · *Chennai, India*  
*Autonomous Agent Runtimes · Single-Store Graph Retrieval · Mission-Critical SAP S/4HANA Modernization*

<br />

<div align="center">

[![Explore Interactive Portfolio](https://img.shields.io/badge/🌐_Explore_Interactive_Portfolio-r--mabasha.github.io%2FMabasha--Portfolio-10b981?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=09090b)](https://r-mabasha.github.io/Mabasha-Portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mabasha%20R-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=09090b)](https://www.linkedin.com/in/mabasha-r/)
[![PyPI](https://img.shields.io/badge/PyPI-graphrag--atlas-3775A9?style=for-the-badge&logo=pypi&logoColor=white&labelColor=09090b)](https://pypi.org/project/graphrag-atlas/)
[![Email](https://img.shields.io/badge/Email-mabasham52%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=09090b)](mailto:mabasham52@gmail.com)

</div>

<br />

> ⚡ **Live Interactive Portfolio & Systems Deep Dives:**  
> **[https://r-mabasha.github.io/Mabasha-Portfolio/](https://r-mabasha.github.io/Mabasha-Portfolio/)**  
> *Interactive architecture walk-throughs, live performance metrics, and enterprise agentic demos.*

---

## 🏛️ Engineering Philosophy & Core Mission

I build at the intersection of **probabilistic foundation models** and **deterministic enterprise systems**.

Foundation models excel at reasoning and synthesis, but enterprise systems of record—particularly complex ERP backends like **SAP S/4HANA**—demand absolute mathematical consistency, strict audit trails, and deterministic transactional boundaries. My work tackles the core failure modes of generative AI in production:

1. **Eliminating Stochastic Hallucination in Enterprise Specifications:** Building multi-agent verification compilers on AWS Bedrock (Claude 3.5 Sonnet) that synthesize conversational business requirements into formally consistent, audit-grade **SAP WRICEF** architectural specifications.
2. **Defeating Multi-Database Sprawl in Retrieval:** Author of [`graphrag-atlas`](https://github.com/R-Mabasha/graphrag-atlas) (published on PyPI). Rather than orchestrating fragile pipelines across separate vector databases, search indices, and graph databases, I engineer unified single-store architectures combining lexical BM25, dense HNSW vectors, and bounded property graph traversals with built-in circuit breakers against super-node latency spikes.
3. **Protocol-Driven Autonomous Execution:** Leveraging the **Model Context Protocol (MCP)** and git worktree isolation to construct sandboxed multi-agent execution environments capable of parallel experimentation, state persistence, and deterministic reconciliation.

---

## 🔬 Core Architectural Pillars

```
                                    ┌────────────────────────────────────────────────────────┐
                                    │               Autonomous Agent Runtimes                │
                                    │    (AWS Bedrock · Claude 3.5 Sonnet · Guardrails)      │
                                    └──────────────────────────┬─────────────────────────────┘
                                                               │
                                  ┌────────────────────────────┴───────────────────────────┐
                                  ▼                                                         ▼
    ┌───────────────────────────────────────────────┐     ┌───────────────────────────────────────────────┐
    │       Unified Hybrid Knowledge Topology       │     │     Protocol Tool & Memory Fabric (MCP)       │
    │  • Single-Store GraphRAG (graphrag-atlas)     │     │  • Sub-2ms Lexical + Semantic Memory          │
    │  • Lucene BM25 + Dense HNSW Vectors           │     │  • Isolated Git-Sandboxed Multi-Agent Nexus   │
    │  • Bounded Graph Traversals + Hub Guard       │     │  • Deterministic Schema Compilation           │
    └───────────────────────┬───────────────────────┘     └───────────────────────┬───────────────────────┘
                            │                                                     │
                            └──────────────────────────┬──────────────────────────┘
                                                       │
                                                       ▼
                                    ┌────────────────────────────────────────────────────────┐
                                    │      Mission-Critical SAP S/4HANA Integration          │
                                    │  (WRICEF Synthesis · RFC Extraction · CPI · SAP BTP)   │
                                    └────────────────────────────────────────────────────────┘
```

### 1. Autonomous Agent Specification Compilers
- **Deterministic Requirement Synthesis:** Architected production-grade agentic reasoning loops that ingest unstructured enterprise dialogues and generate end-to-end, audit-grade SAP WRICEF functional specifications.
- **Verification Loops & Schema Enforcement:** Implemented multi-stage agent validation (spec-task & spec-verify topologies) that enforce schema compliance, eliminate hallucinated transaction codes/tables, and compress specification turnaround by >60%.

### 2. Single-Store Hybrid GraphRAG & Knowledge Topology
- **`graphrag-atlas` Engine:** Creator and author of the open-source PyPI package that eliminates database sprawl by embedding hybrid search and dynamic graph traversal inside a single Atlas datastore.
- **Hub Guard Circuit Breaker:** Engineered an automated graph topology guard (`degree <= 200`) that prevents super-node traversal explosions and eliminates tail-latency spikes during multi-hop graph retrieval.
- **Tenancy & Diff Caching:** Hierarchical multi-tenancy isolation paired with chunk-level SHA-256 diff caching for zero-waste incremental vector re-indexing.

### 3. Protocol-Driven Extensibility & Sandboxed Multi-Agent Nexus
- **Model Context Protocol (MCP):** Authored zero-dependency MCP memory servers delivering persistent cross-session context with sub-2ms lexical BM25 + dense hybrid retrieval.
- **Git Worktree Isolation:** Architected multi-agent coordination fabrics where planner, coder, and verifier agents operate across parallel, isolated git worktrees with strict permission gates and automated merge reconciliation.

### 4. Mission-Critical ERP Modernization (SAP S/4HANA)
- **Enterprise Integration Fabrics:** Engineered resilient integration layers connecting modern cloud runtimes with SAP S/4HANA backends, RFC-based extraction pipelines, and SAP Integration Suite / Cloud Platform Integration (CPI).
- **Transformation Tooling:** Automated SAP landscape assessment workflows, data lineage tracing, and cloud-native service deployments on SAP BTP / Cloud Foundry.

---

## 🌟 Flagship Engineering Projects

<table>
  <thead>
    <tr>
      <th width="32%">Project & Artifacts</th>
      <th width="68%">Architectural Highlights & Systems Engineering Depth</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="top">
        <a href="https://github.com/R-Mabasha/graphrag-atlas"><strong>graphrag-atlas</strong></a><br />
        <a href="https://pypi.org/project/graphrag-atlas/"><img src="https://img.shields.io/pypi/v/graphrag-atlas.svg?color=blue&style=flat-square" alt="PyPI" /></a>
        <img src="https://img.shields.io/badge/Status-Production-brightgreen.svg?style=flat-square" alt="Status" />
        <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square" alt="MIT" />
      </td>
      <td>
        <strong>Single-Store Hybrid GraphRAG Architecture for MongoDB Atlas</strong><br />
        An open-source Python framework that eliminates multi-database architectural sprawl in enterprise AI. Unifies Lucene BM25 text search, HNSW dense vector embeddings, AST code hierarchies, and bounded <code>$graphLookup</code> traversals inside a single cluster. Features an automated <code>Hub Guard</code> circuit breaker (<code>degree &le; 200</code>) to prevent super-node query explosion, two-tier hierarchical tenancy, and chunk-level SHA-256 diff caching.
        <br /><code>pip install graphrag-atlas</code>
      </td>
    </tr>
    <tr>
      <td valign="top">
        <a href="https://github.com/R-Mabasha/antigravity-project-memory"><strong>antigravity-project-memory</strong></a><br />
        <img src="https://img.shields.io/badge/Protocol-MCP-purple?style=flat-square" alt="MCP" />
        <img src="https://img.shields.io/badge/Retrieval-Sub--2ms-brightgreen?style=flat-square" alt="Latency" />
      </td>
      <td>
        <strong>Production-Grade Zero-Dependency MCP Memory Server</strong><br />
        An Anthropic Model Context Protocol (MCP) server providing autonomous persistent long-term memory for AI agents. Combines sub-2ms BM25 hybrid indexing, deterministic session state caching, and multi-agent knowledge consolidation for autonomous coding workspaces.
      </td>
    </tr>
    <tr>
      <td valign="top">
        <a href="https://github.com/R-Mabasha/Multi-Agent-Mcp"><strong>Multi-Agent-Mcp</strong></a><br />
        <img src="https://img.shields.io/badge/Agents-Nexus-orange?style=flat-square" alt="Agents" />
        <img src="https://img.shields.io/badge/Isolation-Git--Worktrees-blue?style=flat-square" alt="Git Worktrees" />
      </td>
      <td>
        <strong>Git-Sandboxed Multi-Agent Orchestration Nexus</strong><br />
        A model-agnostic MCP orchestration fabric enabling teams of autonomous coding agents (planners, coders, verifiers) to run isolated experiments on branched git worktrees with strict permission gates, conflict resolution, and deterministic rollbacks.
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
        Built for the Gemini 3 Hackathon. Intercepts live video and sensor streams for real-time temporal event detection, sub-second multimodal LLM frame classification, and high-frequency edge telemetry visualization.
      </td>
    </tr>
    <tr>
      <td valign="top">
        <a href="https://github.com/R-Mabasha/MobiSafe"><strong>MobiSafe</strong></a><br />
        <img src="https://img.shields.io/badge/National%20Winner-SIH%202023-gold?style=flat-square" alt="SIH 2023" />
        <img src="https://img.shields.io/badge/Prize-%E2%82%B91%2C00%2C000-green?style=flat-square" alt="Prize" />
      </td>
      <td>
        <strong>IoT Edge Telemetry & Deep Learning Predictive Vehicle Safety</strong><br />
        National 1st Place Champion solving Ministry of Coal Problem Statement 1313. Couples edge computer vision with bidirectional LSTM recurrent neural networks for real-time driver state analytics and fleet collision prevention.
      </td>
    </tr>
  </tbody>
</table>

---

## 📝 Systems Engineering Perspectives & Analysis

Practical architectural insights drawn from building production enterprise AI systems:

- **[Why Standard Vector RAG Struggles with SAP Enterprise Data](https://www.linkedin.com/in/mabasha-r/)**  
  *Semantic similarity vs. deterministic business-key lookups.* Analyzing why vector embeddings fail on exact identifiers (Material, Plant, Batch, Work Center) and demonstrating when to route queries between Lexical BM25, Property Graphs, and Tool-Using / Agentic RAG.
- **[OCR Fails on SAP Screens: ColPali vs. Intelligent Layout Routing](https://www.linkedin.com/in/mabasha-r/)**  
  *Evaluating multi-vector visual retrieval (ColPali) vs. text chunking on dense enterprise documents (Fiori screens, ALV tables, BEx outputs).* Why intelligent layout routing by document density yields 10x lower embedding costs without sacrificing layout comprehension.

---

## 🛠️ Technology & Systems Competency Matrix

<table>
  <tr>
    <td width="26%"><strong>Autonomous Agent Systems</strong></td>
    <td>Multi-Agent Orchestration, AWS Bedrock, Claude 3.5 Sonnet, Model Context Protocol (MCP), Prompt Compilers & Guardrails, Deterministic JSON Schemas, LangChain, Tool-Use Fabrics</td>
  </tr>
  <tr>
    <td><strong>Knowledge Topology & RAG</strong></td>
    <td>GraphRAG, <code>graphrag-atlas</code> (PyPI), Hybrid Search (BM25 + Dense Vectors), HNSW Indexing, Reciprocal Rank Fusion (RRF), Cross-Encoder Rerankers, Circuit Breakers, AST Parsing</td>
  </tr>
  <tr>
    <td><strong>Enterprise ERP & SAP</strong></td>
    <td>SAP S/4HANA Modernization, WRICEF Functional Specification Standards, RFC Data Extraction Pipelines, SAP Integration Suite (CPI), SAP BTP, Cloud Foundry, ITIL v4 Governance</td>
  </tr>
  <tr>
    <td><strong>Backend & Distributed Systems</strong></td>
    <td>Python (FastAPI, AsyncIO), TypeScript, Node.js, React / Next.js, PostgreSQL, MongoDB Atlas (Search, Vector, GraphLookup), Redis, Docker, Git Worktrees, Linux, CI/CD</td>
  </tr>
</table>

---

## 🏆 Honors, Awards & Recognitions

- 🥇 **National Champion (1st Place) — Smart India Hackathon 2023**  
  Awarded ₹1,00,000 cash prize by the Ministry of Coal, Government of India, solving national problem statement 1313 among 1,000+ top engineering university teams at The National Institute of Engineering, Mysuru.
- ⭐ **Star of the Month — KTern.AI (2024)**  
  Conferred by executive leadership for rapid technical execution and pioneering the automated WRICEF functional specification synthesis engine.
- 🏅 **Grand Finalist — Smart India Hackathon 2022**  
  Ranked among top national teams in India's flagship 36-hour hackathon, architecting scalable digital governance software.
- 🎯 **Grand Finalist — PSG iTech Hack Fest (2023)**  
  Built high-frequency computer vision analytics prototypes under strict real-time constraints.
- 🎓 **B.Tech in Artificial Intelligence & Data Science**  
  Rathinam Technical Campus, Coimbatore.

---

## 📬 Connect & Direct Channels

- 🌐 **Interactive Portfolio:** [r-mabasha.github.io/Mabasha-Portfolio](https://r-mabasha.github.io/Mabasha-Portfolio/)
- 💼 **LinkedIn:** [linkedin.com/in/mabasha-r](https://www.linkedin.com/in/mabasha-r/)
- 📦 **PyPI:** [pypi.org/project/graphrag-atlas](https://pypi.org/project/graphrag-atlas/)
- ✉️ **Email:** [mabasham52@gmail.com](mailto:mabasham52@gmail.com)
- 🐙 **GitHub:** [github.com/R-Mabasha](https://github.com/R-Mabasha)
