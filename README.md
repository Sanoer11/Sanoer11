# Hi, I'm Sanoer 👋

### AI Engineer · Generative AI · Agentic AI · RAG · MCP

I build **agentic AI systems with guardrails**: permission-aware RAG, multi-agent LangGraph workflows, and tool-calling agents connected through MCP. I care about the parts that make AI safe to ship: access control, structured outputs, evaluation, and CI.

Final-year ECE (AI/ML) @ MIT-WPU, Pune · Class of 2027

[![Email](https://img.shields.io/badge/Email-sanoersoni26%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:sanoersoni26@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sanoer/)

---

### 🔭 Right now

- 🔧 Fixing guardrail bugs in open-source agent frameworks. My **CrewAI** MCP tool-filter fix is under review.
- 🧩 Publishing **needtoknow-haystack**, a permission-aware retrieval component for Haystack.
- 📄 My IEEE **INDICON 2026** paper on edge-AI debris detection has been accepted.

---

### 🚀 Featured Projects

| Project | What it does | Result | Stack |
|---|---|---|---|
| [**NeedToKnow**](https://github.com/Sanoer11/needtoknow) | Enterprise RAG chatbot that only answers from documents the user is allowed to see. A LangGraph agent tool-calls 2 MCP servers for retrieval and ACL checks. | Restricted-content leakage **43.2% → 0%** across 250 adversarial results | LangGraph, MCP, PostgreSQL, pgvector, Docker, GitHub Actions |
| [**needtoknow-haystack**](https://github.com/Sanoer11/needtoknow-haystack) | Fail-closed, permission-aware retrieval component for Haystack | Cross-user leakage **58% → 0%** on a 50-query test benchmark | Haystack 2.x/3.x, Python, CI |
| [**ContentForge**](https://github.com/Sanoer11/contentforge) | 10-node multi-agent content workflow with human-in-the-loop approval and Pydantic validators | **7 assets** under a hard API budget cap, with 3-tier API fallbacks | LangGraph, LangSmith, Groq, Pydantic |
| [**Carbon Footprint Tracker**](https://github.com/Sanoer11/AI-Powered-Carbon-Footprint-Tracker-) | FastAPI + ML service that forecasts emissions trends | **30-day** forecast from 60+ days of time-series data | FastAPI, Scikit-learn, Pandas, React |
| [**Sentinel**](https://github.com/Sanoer11/edge-ai-runway-fod-detection) | Edge-AI runway debris detection with vision, thermal and LiDAR fusion | **Sub-500ms** end-to-end on Raspberry Pi 5 · IEEE INDICON 2026 | YOLOv10s, ONNX, OpenCV, MQTT |

---

### 🌍 Open Source

- **crewAIInc/crewAI**: Reported and fixed an MCP tool-filter fail-open bug where async filters silently exposed blocked tools to agents. Added regression tests. [Issue #8680](https://github.com/crewAIInc/crewAI/issues/8680) · [PR #8681](https://github.com/crewAIInc/crewAI/pull/8681) *(under review)*
- **deepset-ai/haystack-integrations**: Submitted an integration listing for needtoknow-haystack. [PR #687](https://github.com/deepset-ai/haystack-integrations/pull/687) *(under review)*

---

### 🛠️ Stack

**GenAI & Agents:** LLMs · Prompt Engineering · RAG · Embeddings · LangGraph · LangChain · LangSmith · CrewAI · Haystack · MCP · Tool Calling · Structured Outputs

**Data & ML:** Python · Pandas · NumPy · Scikit-learn · PyTorch · OpenCV

**Backend & Infra:** FastAPI · Pydantic · PostgreSQL · pgvector · ChromaDB · Docker · GitHub Actions · AWS

[![Stack](https://skillicons.dev/icons?i=py,pytorch,sklearn,fastapi,postgres,docker,githubactions,aws,opencv,git,linux,raspberrypi)](https://skillicons.dev)

*Also:* embedded systems (bare-metal C, SPI, I2C, UART, MQTT, Raspberry Pi), which I use to run AI on the edge.

---

### 📄 Research

**Sentinel: An Edge-AI System for Foreign Object Debris Detection and Runway Maintenance Prioritization.** IEEE INDICON 2026 *(Accepted, Paper ID 4722)*
