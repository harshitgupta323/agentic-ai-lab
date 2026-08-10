# 🤖 Agentic AI Lab

> **A progressive hands-on laboratory for building, evaluating, securing, and deploying production-ready AI agents across text, documents, vision, voice, video, coding, web, and multi-agent systems.**

![Python](https://img.shields.io/badge/Python-3.11+-blue?logo=python)
![LangGraph](https://img.shields.io/badge/LangGraph-Agent%20Orchestration-orange)
![LangChain](https://img.shields.io/badge/LangChain-Agents-green)
![MCP](https://img.shields.io/badge/MCP-Tools%20%26%20Context-purple)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue?logo=docker)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📌 About

**Agentic AI Lab** is a structured collection of progressively complex agentic AI systems designed to move from fundamental agent concepts to production-grade autonomous systems.

The repository explores how modern AI agents are built around:

* 🧠 LLM reasoning and decision making
* 🔧 Tool calling and tool orchestration
* 📋 Planning and task decomposition
* 🔄 Reflection and self-correction
* 🗂️ Short-term and long-term memory
* 🔍 RAG and agentic retrieval
* 👁️ Multimodal perception
* 🎙️ Voice and audio interaction
* 🎬 Video understanding
* 💻 Software engineering agents
* 🌐 Browser and web automation
* 🤝 Multi-agent collaboration
* 👤 Human-in-the-loop workflows
* 🛡️ Guardrails and agent security
* 📊 Evaluation and benchmarking
* 🔭 Observability and tracing
* 💰 Cost and token optimization
* ⚙️ Reliability and fault tolerance
* 🚀 Production deployment

The goal is not simply to build chatbots.

> **The goal is to understand how autonomous AI systems are designed, evaluated, controlled, observed, and deployed.**

---

# 🎯 Objectives

This lab is designed around five major objectives.

### 1. Understand Agent Fundamentals

Build agents from first principles and understand the underlying execution loop:

```text
User
 │
 ▼
LLM
 │
 ├── Direct response
 │
 └── Tool call
       │
       ▼
     Tool
       │
       ▼
   Observation
       │
       ▼
      LLM
       │
       ▼
   Final Answer
```

---

### 2. Explore Different Agent Architectures

The lab covers:

* Tool-calling agents
* ReAct agents
* Router agents
* Planner–executor systems
* Reflection agents
* Stateful agents
* Memory-enabled agents
* Human-in-the-loop agents
* Multi-agent systems
* Autonomous agents
* Long-running agents

---

### 3. Explore Agents Across Modalities

The lab deliberately goes beyond text-only agents.

```text
                    AGENTIC AI
                        │
       ┌────────────────┼────────────────┐
       │                │                │
       ▼                ▼                ▼
     TEXT           DOCUMENTS         VISION
       │                │                │
       └────────────────┼────────────────┘
                        │
       ┌────────────────┼────────────────┐
       ▼                ▼                ▼
     AUDIO            VIDEO            CODE
       │                │                │
       └────────────────┼────────────────┘
                        │
                        ▼
                    WEB / BROWSER
                        │
                        ▼
                  MULTI-AGENT
```

---

### 4. Learn Production Agent Engineering

Selected projects progressively introduce:

* Evaluation
* Guardrails
* Security
* Memory
* Observability
* Reliability
* Cost optimization
* Authentication
* Authorization
* Human approval
* Audit logging
* Containerization
* CI/CD
* API deployment

---

### 5. Build Portfolio-Grade Systems

The repository contains many small and intermediate projects for learning, but selected **flagship projects** are developed with production-oriented architecture.

The progression is:

```text
Concept
   ↓
Minimal Implementation
   ↓
Tool Integration
   ↓
Memory / State
   ↓
Evaluation
   ↓
Guardrails
   ↓
Observability
   ↓
Reliability
   ↓
Deployment
   ↓
Production Agent
```

---

# 🗺️ Learning Roadmap

## Phase 0 — Agent Foundations

| ID  | Project                 | Concepts                     | Level |
| --- | ----------------------- | ---------------------------- | ----- |
| F01 | Tool Calling Agent      | Tools, function calling      | 🟢    |
| F02 | ReAct Agent             | Reasoning + actions          | 🟢    |
| F03 | Structured Agent        | Structured outputs           | 🟢    |
| F04 | Router Agent            | Routing, specialization      | 🟢    |
| F05 | Planner–Executor        | Planning, task decomposition | 🟡    |
| F06 | Reflection Agent        | Critique, self-correction    | 🟡    |
| F07 | Stateful Agent          | State, checkpoints           | 🟡    |
| F08 | Human-in-the-Loop Agent | Approval, interruption       | 🟡    |

---

# 📚 64-Agent Project Roadmap

The lab contains **64 progressively scoped projects** across multiple modalities and application domains.

> The projects are intentionally not all production-grade. Small projects teach individual concepts, while selected projects combine those concepts into complete production systems.

---

## 📝 01 — Text Agents

**10 projects**

| ID  | Project                      | Primary Concepts             |
| --- | ---------------------------- | ---------------------------- |
| T01 | General Assistant Agent      | Tool calling                 |
| T02 | Research Agent               | Search + synthesis           |
| T03 | Fact-Checking Agent          | Verification                 |
| T04 | Summarization Agent          | Long-context processing      |
| T05 | Writing Agent                | Planning + generation        |
| T06 | Debate Agent                 | Multi-perspective reasoning  |
| T07 | Personal Assistant           | Memory                       |
| T08 | Knowledge Agent              | RAG + tools                  |
| T09 | Deep Research Agent ⭐        | Planning + parallel research |
| T10 | Autonomous Research System ⭐ | Long-running agent           |

---

## 📄 02 — Document Agents

**8 projects**

| ID  | Project                       | Primary Concepts       |
| --- | ----------------------------- | ---------------------- |
| D01 | PDF Q&A Agent                 | Document retrieval     |
| D02 | Document Summarization Agent  | Long documents         |
| D03 | Contract Analysis Agent       | Extraction + reasoning |
| D04 | Invoice Processing Agent      | Structured extraction  |
| D05 | Document Comparison Agent     | Semantic comparison    |
| D06 | Multi-Document Research Agent | Multi-source retrieval |
| D07 | Enterprise Document Agent ⭐   | RAG + access control   |
| D08 | Multimodal Document Agent ⭐   | OCR + vision + RAG     |

---

## 👁️ 03 — Vision Agents

**8 projects**

| ID  | Project                    | Primary Concepts           |
| --- | -------------------------- | -------------------------- |
| V01 | Image Q&A Agent            | Vision-language models     |
| V02 | Image Classification Agent | Vision tools               |
| V03 | Object Detection Agent     | Detection + reasoning      |
| V04 | Visual Search Agent        | Embeddings + retrieval     |
| V05 | OCR Agent                  | Document perception        |
| V06 | Image Analysis Agent       | Visual reasoning           |
| V07 | Visual Research Agent      | Search + vision            |
| V08 | Multimodal Vision Agent ⭐  | Vision + tools + reasoning |

---

## 🎙️ 04 — Audio & Voice Agents

**7 projects**

| ID  | Project                       | Primary Concepts              |
| --- | ----------------------------- | ----------------------------- |
| A01 | Speech-to-Text Agent          | STT                           |
| A02 | Voice Q&A Agent               | STT + LLM + TTS               |
| A03 | Voice Research Assistant      | Voice + tools                 |
| A04 | Meeting Assistant             | Transcription + summarization |
| A05 | Customer Support Voice Agent  | Real-world workflows          |
| A06 | Real-Time Voice Agent ⭐       | Streaming + interruption      |
| A07 | Multi-Agent Voice Assistant ⭐ | Voice + orchestration         |

---

## 🎬 05 — Video Agents

**6 projects**

| ID   | Project                          | Primary Concepts        |
| ---- | -------------------------------- | ----------------------- |
| VI01 | Video Summarization Agent        | Video understanding     |
| VI02 | Video Q&A Agent                  | Multimodal retrieval    |
| VI03 | Video Search Agent               | Temporal retrieval      |
| VI04 | Video Moderation Agent           | Vision + audio          |
| VI05 | Video Research Agent             | Multimodal reasoning    |
| VI06 | Autonomous Video Understanding ⭐ | Vision + audio + agents |

---

## 💻 06 — Code & Developer Agents

**8 projects**

| ID  | Project                      | Primary Concepts            |
| --- | ---------------------------- | --------------------------- |
| C01 | Code Explanation Agent       | Code understanding          |
| C02 | Code Review Agent            | Analysis + reasoning        |
| C03 | Test Generation Agent        | Code generation             |
| C04 | Bug Fixing Agent             | Debugging                   |
| C05 | Documentation Agent          | Repository understanding    |
| C06 | GitHub Repository Agent      | Git + APIs                  |
| C07 | Software Engineering Agent ⭐ | Planning + coding + testing |
| C08 | Autonomous Coding Agent ⭐    | Long-horizon execution      |

---

## 🌐 07 — Web & Browser Agents

**7 projects**

| ID  | Project                    | Primary Concepts               |
| --- | -------------------------- | ------------------------------ |
| B01 | Web Search Agent           | Search tools                   |
| B02 | Web Research Agent         | Multi-source research          |
| B03 | Browser Navigation Agent   | Browser automation             |
| B04 | Shopping Research Agent    | Web extraction                 |
| B05 | Form-Filling Agent         | Browser actions                |
| B06 | Web Research Automation ⭐  | Long-running browser workflows |
| B07 | Autonomous Browser Agent ⭐ | Planning + browser control     |

---

## 🤝 08 — Multi-Agent Systems

**10 projects**

| ID  | Project                        | Primary Concepts         |
| --- | ------------------------------ | ------------------------ |
| M01 | Research Team                  | Delegation               |
| M02 | Software Engineering Team      | Role specialization      |
| M03 | ML Engineering Team            | ML workflow              |
| M04 | Scientific Research Team       | Collaborative reasoning  |
| M05 | Cybersecurity Team             | Specialized agents       |
| M06 | Content Creation Team          | Parallel workflows       |
| M07 | Startup Team                   | Hierarchical agents      |
| M08 | Autonomous Data Scientist ⭐    | End-to-end ML            |
| M09 | Autonomous MLOps Team ⭐        | Monitoring + remediation |
| M10 | General Multi-Agent Platform ⭐ | Agent orchestration      |

---

# 🏭 Production Engineering Track

The projects above provide breadth.

The following capabilities provide **engineering depth**.

---

# 🧠 Memory

Agents become substantially more useful when they can retain and retrieve information across interactions.

The lab explores multiple memory architectures.

```text
                   Agent Memory
                       │
       ┌───────────────┼────────────────┐
       │               │                │
       ▼               ▼                ▼
 Short-Term       Long-Term         Working
   Memory           Memory           Memory
       │               │                │
       ▼               ▼                ▼
 Conversation      Semantic        Task State
    State          Memory
```

### Memory technologies

* LangGraph persistence
* Mem0
* Zep
* Letta
* Redis
* PostgreSQL

### Memory concepts

* Short-term memory
* Conversation memory
* Working memory
* Semantic memory
* Episodic memory
* Procedural memory
* Long-term memory
* Memory retrieval
* Memory consolidation
* Memory summarization
* Memory expiration
* User-specific memory

Different projects intentionally use different memory implementations.

---

# 🔍 Agent Evaluation

Agent evaluation is treated as a first-class component rather than an afterthought.

```text
evaluation/
│
├── task_success/
├── trajectory/
├── planning/
├── tool_selection/
├── tool_arguments/
├── final_answer/
├── memory/
├── safety/
├── robustness/
├── latency/
├── cost/
└── regression/
```

### Evaluation dimensions

#### Task Success

Did the agent actually accomplish the user's objective?

#### Tool Selection

Did it select the appropriate tool?

#### Tool Arguments

Were the tool parameters correct?

#### Trajectory Quality

Did the agent take a reasonable sequence of actions?

#### Final Answer

Evaluate:

* correctness
* relevance
* completeness
* groundedness

#### Operational Metrics

Track:

* latency
* token usage
* cost
* number of tool calls
* failures
* retries

---

# 🛡️ Guardrails & Agent Security

Agents can interact with external systems and therefore require stronger controls than ordinary LLM applications.

The lab explores:

### Input Guardrails

* Prompt-injection detection
* Malicious input detection
* PII detection
* Input validation

### Output Guardrails

* PII filtering
* Toxicity detection
* Policy validation
* Hallucination checks

### Tool Guardrails

* Tool allowlists
* Argument validation
* Permission checks
* Dangerous-action detection

### Agent Security

* Prompt injection
* Indirect prompt injection
* Tool poisoning
* Data exfiltration
* Credential isolation
* Sandboxing
* Audit logging
* Least-privilege tool access

Example:

```text
Research Agent
 ├── Search              ✓
 ├── Browser             ✓
 ├── Database             ✓
 ├── Filesystem           ✗
 ├── Shell                ✗
 └── Payments             ✗
```

---

# 🔭 Observability

Every production-oriented agent should be observable.

A typical agent trace captures:

```text
Agent Run
 │
 ├── User Input
 ├── Model
 ├── Prompt Version
 ├── Agent State
 │
 ├── Tool Call
 │    ├── Tool
 │    ├── Arguments
 │    ├── Latency
 │    └── Result
 │
 ├── Token Usage
 ├── Cost
 ├── Latency
 ├── Errors
 │
 └── Final Output
```

### Observability stack

* LangSmith
* OpenTelemetry
* Structured logging
* Prometheus
* Grafana

### Key metrics

* Request count
* Task success rate
* P50/P95/P99 latency
* Tool failure rate
* Agent failure rate
* Token usage
* Cost per request
* Cost per task
* Number of tool calls
* Retry rate
* Evaluation score

---

# ⚙️ Reliability Engineering

Production agents must be designed to fail safely.

The lab progressively introduces:

* Retries
* Exponential backoff
* Timeouts
* Circuit breakers
* Rate limiting
* Concurrency control
* Model fallbacks
* Tool fallbacks
* Idempotency
* Checkpointing
* Resume-after-failure
* Dead-letter workflows
* Graceful degradation

Example:

```text
Primary Model
      │
      ▼
   Failure
      │
      ▼
Retry + Backoff
      │
      ▼
Fallback Model
      │
      ▼
Failure
      │
      ▼
Human Escalation
```

---

# 💰 Cost & Token Optimization

Agentic workflows can consume significantly more tokens than conventional LLM applications.

The lab therefore tracks:

```text
Input Tokens
Output Tokens
Tool Calls
Context Size
Model Cost
Total Task Cost
```

Optimization techniques include:

* Model routing
* Semantic caching
* Prompt compression
* Context pruning
* Memory summarization
* Tool-result compression
* Early stopping
* Smaller models for simple tasks
* Batch execution
* Parallel execution

---

# 🔌 MCP — Model Context Protocol

The lab also explores MCP as a standardized interface between agents and external capabilities.

```text
                Agent
                  │
                  ▼
                 MCP
        ┌─────────┼─────────┐
        ▼         ▼         ▼
    Database   GitHub   Filesystem
        │         │         │
        └─────────┼─────────┘
                  ▼
               External
               Systems
```

Planned MCP implementations include:

* Filesystem MCP
* Database MCP
* GitHub MCP
* Research MCP
* Custom MCP servers
* Multi-server MCP agents

---

# 👤 Human-in-the-Loop

Autonomous does not always mean unsupervised.

The lab explores approval workflows for high-impact actions.

```text
Agent
 │
 ▼
Proposed Action
 │
 ▼
Risk Check
 │
 ├── Low Risk ───────► Execute
 │
 └── High Risk
          │
          ▼
       Human
       Review
          │
      ┌───┴───┐
      ▼       ▼
   Approve   Reject
      │
      ▼
   Execute
```

---

# 🧪 Testing Strategy

Agent testing is divided into multiple levels.

### Unit Tests

Test:

* tools
* parsers
* validators
* memory operations
* routing logic

### Integration Tests

Test:

* LLM + tools
* RAG + agent
* memory + agent
* MCP + agent

### Agent Tests

Test:

* tool selection
* tool arguments
* trajectories
* state transitions
* final responses

### Regression Tests

Maintain fixed evaluation datasets to detect behavioral regressions.

### Adversarial Tests

Test:

* prompt injection
* malformed inputs
* tool failures
* API failures
* malicious documents
* unexpected tool results

---

# 🧩 Framework Exploration

The primary implementation framework is **LangGraph**, but the lab also explores other agent frameworks.

| Framework         | Focus                               |
| ----------------- | ----------------------------------- |
| LangGraph         | Stateful agent workflows            |
| LangChain         | Components and tools                |
| OpenAI Agents SDK | Lightweight agent orchestration     |
| Google ADK        | Agent development ecosystem         |
| AutoGen           | Multi-agent systems                 |
| CrewAI            | Role-oriented multi-agent workflows |

Rather than rewriting every project in every framework, selected projects are implemented across multiple frameworks for comparison.

---

# 🏆 Flagship Projects

Not every project in the repository is intended to be production-grade.

The following projects receive substantially deeper engineering treatment.

### ⭐ Deep Research Agent

* Planning
* Parallel research
* Web search
* RAG
* Memory
* Citation verification
* Evaluation
* Observability

### ⭐ Autonomous Data Scientist

```text
Dataset
   ↓
Data Agent
   ↓
EDA
   ↓
Feature Engineering
   ↓
Model Selection
   ↓
Training
   ↓
Evaluation
   ↓
Report
```

### ⭐ Autonomous Coding Agent

* Filesystem tools
* Git
* Shell
* Planning
* Code generation
* Testing
* Review
* Sandboxing
* Human approval

### ⭐ Multimodal Video Understanding Agent

* Frame extraction
* OCR
* Speech processing
* Object detection
* Scene understanding
* Multimodal reasoning
* Report generation

### ⭐ Real-Time Voice Agent

* VAD
* STT
* LLM
* Tool calling
* Streaming
* TTS
* Interruptions
* Latency optimization

### ⭐ Enterprise Document Agent

* Document ingestion
* OCR
* Hybrid retrieval
* Reranking
* Access control
* Memory
* Evaluation
* Observability

### ⭐ Autonomous MLOps Agent

```text
Monitoring
    ↓
Anomaly Detection
    ↓
Diagnosis
    ↓
Root Cause Analysis
    ↓
Recommendation
    ↓
Human Approval
    ↓
Remediation
```

### ⭐ Agent Evaluation Platform

A reusable evaluation framework for:

* task success
* trajectory quality
* tool usage
* safety
* cost
* latency
* regression testing

### ⭐ Agent Observability Platform

A centralized interface for:

* traces
* agent runs
* tool calls
* token usage
* latency
* failures
* cost
* evaluation scores

### ⭐ Production Agent Platform

The final capstone combining:

```text
                API Gateway
                     │
                     ▼
               Agent Gateway
                     │
              ┌──────┴──────┐
              ▼             ▼
           Router        Auth/RBAC
              │
              ▼
             Agent
              │
      ┌───────┼────────┐
      ▼       ▼        ▼
    Tools   Memory     RAG
      │       │        │
      └───────┼────────┘
              ▼
         Guardrails
              ▼
          Evaluation
              ▼
        Observability
              ▼
       Cost Management
              ▼
        Infrastructure
```

---

# 🏗️ Repository Architecture

```text
agentic-ai-lab/
│
├── 00_foundations/
│
├── 01_text_agents/
├── 02_document_agents/
├── 03_vision_agents/
├── 04_audio_voice_agents/
├── 05_video_agents/
├── 06_code_developer_agents/
├── 07_web_browser_agents/
├── 08_multi_agent_systems/
│
├── 09_production/
│
├── evaluation/
├── guardrails/
├── memory/
├── observability/
├── reliability/
├── security/
├── mcp/
│
├── shared/
├── tests/
├── docs/
├── notebooks/
│
├── configs/
├── docker/
│
├── pyproject.toml
├── Makefile
├── .env.example
└── README.md
```

---

# 🧱 Production Architecture

The long-term goal is to evolve individual experiments toward a reusable architecture:

```text
                           ┌───────────────┐
                           │   Client/API  │
                           └───────┬───────┘
                                   │
                                   ▼
                         ┌──────────────────┐
                         │  Agent Gateway   │
                         └────────┬─────────┘
                                  │
                 ┌────────────────┼────────────────┐
                 │                │                │
                 ▼                ▼                ▼
              Auth/RBAC       Rate Limit       Routing
                 │                │                │
                 └────────────────┼────────────────┘
                                  ▼
                         ┌──────────────────┐
                         │  Agent Runtime   │
                         └────────┬─────────┘
                                  │
          ┌───────────────────────┼───────────────────────┐
          │                       │                       │
          ▼                       ▼                       ▼
       Planning                Memory                  Tools
          │                       │                       │
          │               ┌───────┼───────┐               │
          │               ▼       ▼       ▼               │
          │             Redis   Mem0    Zep              MCP
          │                                               │
          └───────────────────────┬───────────────────────┘
                                  ▼
                            Guardrails
                                  │
                                  ▼
                            LLM Gateway
                                  │
                  ┌───────────────┼───────────────┐
                  ▼               ▼               ▼
                OpenAI          Gemini          Groq
                  │               │               │
                  └───────────────┼───────────────┘
                                  ▼
                             Evaluation
                                  │
                                  ▼
                           Observability
                                  │
                    ┌─────────────┼─────────────┐
                    ▼             ▼             ▼
                 Traces        Metrics        Logs
```

---

# 🛠️ Technology Stack

## Core

* Python 3.11+
* LangChain
* LangGraph
* Pydantic

## LLM Providers

* OpenAI
* Anthropic
* Google Gemini
* Groq
* Ollama

## Agent Frameworks

* LangGraph
* OpenAI Agents SDK
* Google ADK
* AutoGen
* CrewAI

## Memory

* LangGraph persistence
* Mem0
* Zep
* Letta
* Redis
* PostgreSQL

## Retrieval

* Chroma
* FAISS
* PostgreSQL / pgvector
* Elasticsearch / OpenSearch
* Rerankers

## Evaluation

* RAGAS
* LangSmith
* LLM-as-a-Judge
* Custom evaluation harness

## Observability

* LangSmith
* OpenTelemetry
* Prometheus
* Grafana

## API & Deployment

* FastAPI
* Docker
* GitHub Actions
* GCP / Vertex AI

---

# 📈 Project Complexity

Projects are intentionally categorized by complexity.

### 🟢 Beginner

Focus on one major concept.

```text
LLM
 +
Tool
```

### 🟡 Intermediate

Combine several components.

```text
LLM
 +
Tools
 +
State
 +
Memory
```

### 🔴 Advanced

Long-running or multi-agent workflows.

```text
Planning
 +
Tools
 +
Memory
 +
RAG
 +
Evaluation
 +
Guardrails
 +
Observability
```

### ⭐ Flagship

Production-oriented systems.

```text
Agent
 │
 ├── Planning
 ├── Tools
 ├── Memory
 ├── RAG
 ├── Multi-Agent
 ├── Guardrails
 ├── Security
 ├── Evaluation
 ├── Observability
 ├── Reliability
 ├── Cost Optimization
 ├── HITL
 └── Deployment
```

---

# 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/<your-username>/agentic-ai-lab.git

cd agentic-ai-lab
```

Create an environment:

```bash
python -m venv .venv
```

Activate on Windows:

```bash
.venv\Scripts\activate
```

Activate on Linux/macOS:

```bash
source .venv/bin/activate
```

Install dependencies for a project:

```bash
pip install -e .
```

Create your environment file:

```bash
cp .env.example .env
```

Add the required API keys.

Then enter an individual project directory and follow its README.

---

# 🧪 Development Philosophy

Each project should answer five questions:

### 1. What agent problem are we solving?

Clearly define the task.

### 2. Why does an agent make sense?

Not every LLM application needs an agent.

### 3. What architecture are we using?

Document:

* state
* tools
* planning
* memory
* orchestration

### 4. How do we know it works?

Define measurable evaluation criteria.

### 5. What happens when it fails?

Document:

* retries
* fallbacks
* guardrails
* human escalation
* observability

---

# 🔬 Agent Design Principles

This lab follows several principles.

### Prefer deterministic workflows where possible

Not every step needs an LLM.

### Minimize autonomous actions

Give agents only the tools and permissions they require.

### Treat external data as untrusted

Retrieved documents and webpages may contain malicious instructions.

### Evaluate trajectories, not only answers

A correct final answer can still come from a dangerous or inefficient trajectory.

### Make long-running agents resumable

Persist state and checkpoints.

### Keep humans in the loop for high-impact actions

Autonomy should be bounded by policy.

### Optimize cost and latency

Agentic systems can multiply model calls quickly.

---

# 📊 What This Lab Demonstrates

By completing the lab, the repository demonstrates practical experience with:

```text
                    Agentic AI
                       │
 ┌─────────────────────┼─────────────────────┐
 │                     │                     │
 ▼                     ▼                     ▼
Reasoning            Tools                Memory
 │                     │                     │
 ▼                     ▼                     ▼
Planning             MCP                 Mem0/Zep
Reflection           APIs                Letta
 │                   SQL                 State
 └─────────────────────┬───────────────────┘
                       │
                       ▼
                 Multi-Agent
                       │
                       ▼
                 Multimodal
                       │
                       ▼
                 Evaluation
                       │
             ┌─────────┴─────────┐
             ▼                   ▼
        Guardrails          Observability
             │                   │
             └─────────┬─────────┘
                       ▼
                  Production
```

---

# 🏁 Final Goal

The ultimate objective of this repository is to progress from:

> **"I can call an LLM."**

to:

> **"I can design, implement, evaluate, secure, observe, optimize, and deploy autonomous AI systems."**

The 64 projects provide breadth.

The foundational agents provide understanding.

The memory, evaluation, guardrail, security, and observability modules provide engineering depth.

The flagship projects demonstrate real-world application.

And the final production platform brings everything together.

---

## 📌 Status

🚧 **Active Development**

Projects are implemented progressively from foundational agent patterns toward advanced multimodal, multi-agent, and production-grade systems.

---

## ⭐ If You Find This Useful

If this laboratory helps you learn agentic AI engineering, consider starring the repository and following the progression as new projects are added.

---

## 📜 License

MIT License
