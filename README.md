# Hi, I'm Ayash 👋

**B.Tech Artificial Intelligence & Data Science Student**  
Building production-grade Retrieval-Augmented Generation (RAG) systems, real-time AI security engines, and full-stack applications.  
*Actively seeking technical project coordination, AI/ML engineering, and software development internships.*

---

## 👨‍💻 About Me

- 🎓 **Education**: B.Tech in Artificial Intelligence & Data Science (India 🇮🇳)
- 🛠️ **What I Build**: Local-first RAG systems with verifiable citations, real-time audio deepfake classifiers, robust asynchronous REST APIs, and multi-role enterprise workflows.
- 👥 **Project Coordination & Leadership**: Experienced in leading technical project teams—defining architecture, managing Git workflows, enforcing testing standards, and delivering end-to-end solutions.
- 🎯 **Focus Areas**: Retrieval-Augmented Generation (RAG), AI/ML Engineering, Backend & Full-Stack Systems, and Technical Project Management.

---

## 🚀 What I Build & Coordinate

- **Retrieval-Augmented Generation (RAG) & Document AI** — Hybrid dense-sparse retrieval (Qdrant + BM25), Reciprocal Rank Fusion (RRF), page-attributed citation grounding, strict output constraints, and hallucination guardrails.
- **AI & Audio ML Systems** — Acoustic feature extraction, deepfake audio detection, neural waveform classification (SincNet), and low-latency streaming analysis.
- **Backend & Full-Stack Systems** — Asynchronous REST APIs with FastAPI & Flask, role-based access control (RBAC), multi-tenant isolation, SQLite / MongoDB / MySQL persistence, and modern React (TypeScript) interfaces.
- **Technical Team Leadership** — Sprint planning, repository organization, test-driven development (TDD), and cross-functional task tracking.

---

## 🛠️ Verified Tech Stack

### Languages
`Python` · `TypeScript` · `SQL` · `JavaScript` · `Java` · `HTML5 / CSS3`

### AI, Machine Learning & RAG
`sentence-transformers` · `Qdrant (Vector DB)` · `BM25Okapi` · `Reciprocal Rank Fusion (RRF)` · `Ollama (Local LLMs)` · `PyTorch` · `torchaudio` · `scikit-learn` · `librosa` · `SciPy` · `NumPy`

### Backend & Databases
`FastAPI` · `Flask` · `SQLAlchemy` · `SQLite` · `MongoDB (Motor)` · `MySQL` · `REST APIs` · `WebSockets` · `JWT Authentication` · `Bcrypt`

### Frontend & DevOps
`React 18` · `Vite` · `Tailwind CSS` · `Git` · `GitHub` · `Docker` · `Docker Compose` · `pytest` · `Render` · `Linux / Bash`

---

## ⭐ Featured Projects

### 🧠 [DocuMind AI — Local Grounded Document Intelligence & RAG Assistant](https://github.com/aayash317-svg/DocuMind-AI)
> A 100% private, local-first RAG assistant featuring hybrid dense-sparse retrieval, reciprocal rank fusion, context-grounded citations, and local LLM inference.

- **Hybrid Dense-Sparse Retrieval**: Combines semantic embeddings (`all-MiniLM-L6-v2` in Qdrant) with sparse keyword matching (`BM25Okapi`), fused via Reciprocal Rank Fusion ($k=60$) with query-aware target page boosting.
- **Verifiable Citation Grounding**: Every factual assertion links to its exact source file and page (`[Source: <doc>, Page: <p>]`) with 180-character centered matching snippets; faithfully abstains when facts are unstated.
- **Output Constraint Enforcement**: Enforces exact bullet counts, ordered pipeline stages, single-sentence constraints, and structured numbered Q&A formatting.
- **Multi-Tenant Security & History**: JWT authentication with bcrypt password hashing, SQLite foreign-key cascade isolation across users, and multi-session chat replay.
- **Production-Ready & Fully Tested**: Automated regression suite with 41 passing tests covering auth, extraction edge cases (PDF, DOCX tables, TXT), retrieval accuracy, and response formatting.
- **Tech**: `Python` · `FastAPI` · `React (TypeScript)` · `Qdrant` · `BM25` · `Ollama (qwen2.5)` · `SQLite` · `pytest` · `Vite`

---

### 🛡️ [Voice Shield AI — Real-Time Voice Cloning Detection](https://github.com/aayash317-svg/Ai_voice-_cloning)
> An AI-powered security engine that detects synthetic speech, cloned voices, and deepfakes during live audio calls and uploads.

- **Dual-Model Ensemble**: Late-fusion combining PyTorch SincNet 1D raw-waveform neural filters with a 63-D calibrated Random Forest classifier.
- **Real-Time Streaming**: Low-latency WebSocket streaming with a 3-stage progressive threat scoring engine.
- **Privacy-by-Design**: Zero-retention ephemeral RAM ring buffer (no audio saved to disk) paired with a SHA-256 cryptographic audit ledger.
- **Production-Ready**: Dockerized deployment on Render with automated `pytest` test suite.
- **Tech**: `Python` · `FastAPI` · `PyTorch` · `librosa` · `scikit-learn` · `WebSockets` · `Docker`  
- 🌐 [Live Interactive Demo](https://ai-voice-cloning-qxvc.onrender.com)

---

### 🎓 [Smart Absentee Leave Monitoring & Reporting System](https://github.com/aayash317-svg/Smart-Absentee-Leave-Monitoring-and-Reporting-System)
> A full-stack college ERP automating student attendance management, role-based leave approvals, and multi-channel reporting.

- **Role & Scope**: **Project Lead & Technical Contributor** — Coordinated team tasks, GitHub branch integration, system design, and documentation.
- **Granular RBAC**: 5 distinct roles (Student, Coordinator, HOD, Dean, Admin) with JWT authentication and brute-force lockout protection.
- **Automated Workflows**: Tiered attendance warning engine, automated ReportLab PDF & openpyxl Excel exports, and Twilio SMS / email alerts.
- **Architecture**: Async FastAPI backend connected to MongoDB with 32 responsive frontend screens and 16 unit tests.
- **Tech**: `Python` · `FastAPI` · `MongoDB` · `Vanilla JS` · `Docker` · `Twilio` · `ReportLab`

---

### 💼 [WorkNow — Student Gig Marketplace](https://github.com/aayash317-svg/work-now-new-repository) *(Active Prototype)*
> A marketplace concept connecting student freelancers with short-term local gigs and employers.

- **Data Architecture**: Structured relational MySQL schema supporting users, jobs, gig applications, escrow wallet balances, and reviews.
- **Features**: Role-based access for workers and employers, location-aware gig listings, and responsive UI design.
- **Tech**: `Python` · `Flask` · `MySQL` · `HTML / CSS / JS` · `REST API`

---

## 📚 Current Learning & Growth Direction

- Advanced RAG architectures (agentic workflows, query rewriting, re-ranking cross-encoders)
- Real-time multimodal streaming and on-device model optimization (ONNX / TensorRT)
- Cloud architecture patterns, CI/CD pipelines, and scalable microservices
- Agile project management methodologies and technical sprint coordination

---

## 🤝 Connect With Me

- 📧 **Email**: [aayash317@gmail.com](mailto:aayash317@gmail.com)
- 🐙 **GitHub**: [github.com/aayash317-svg](https://github.com/aayash317-svg)

---
*B.Tech AI & Data Science · Dedicated to building clean, tested, real-world systems.*
