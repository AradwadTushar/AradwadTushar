<p align="center">
  <img src="assets/Tushar Aradwad - Full Stack Developer.png" alt="Banner" width="100%">
</p>

# Tushar Aradwad

AI Systems & Full-Stack Developer — LangGraph / FastAPI / React / Azure Cloud

Pune, India · [aradwadtushar72@gmail.com](mailto:aradwadtushar72@gmail.com) · [Portfolio](https://dev-tushar-aradwad-portfolio.vercel.app) · [LinkedIn](https://linkedin.com/in/tushar-aradwad-536570307)

---

## About

* **B.Tech in Information Technology**, First Class with Distinction (CGPA: 7.73 | Final Semester SGPA: 9.55).
* **Full-Stack & Systems**: Experience owning systems end-to-end, from database schema design (relational & vector) to state orchestration, authentication, and cloud deployment.
* **Production AI Workflows**: Focused on building stateful agentic graphs (DAGs), multimodal extraction pipelines, and RAG architectures as durable software, not surface-level API wrappers.
* **Continuous Learning**: Currently preparing for GATE CS 2027 alongside active software engineering and client engagements.

---

## Technical Stack

* **AI & Agentic Systems:** LangGraph, LangChain, Azure OpenAI (GPT-4o), Google Gemini API, Azure Video Indexer (OCR + STT), Azure AI Search (Vector RAG), PaddleOCR, Ollama
* **Backend & APIs:** Python (3.10+), FastAPI (async), Node.js, Flask, SQLAlchemy 2.0 (async), Pydantic v2, REST APIs, WebSockets
* **Frontend & Mobile:** React 18, React Native (Expo), Vite, TailwindCSS, Electron, Zustand, WeasyPrint, Jinja2
* **Databases & Storage:** PostgreSQL (JSONB), MongoDB Atlas, SQLite (better-sqlite3), Vector Embeddings
* **Cloud & Observability:** Microsoft Azure (Managed Identity, App Insights), OpenTelemetry, Docker, Render, Vercel, Git

---

## Featured Projects

### [Brand Guardian AI](https://github.com/AradwadTushar/langgraph-video-auditor) — Multimodal Video Compliance Engine
`Python` `FastAPI` `LangGraph` `Azure Video Indexer` `Azure AI Search` `Azure OpenAI (GPT-4o)` `OpenTelemetry` `React`
* Automated regulatory audit engine assessing video marketing streams against FTC Endorsement Guides and advertising platform specifications.
* Multimodal signal extraction combining Azure Video Indexer (frame-accurate OCR + speech transcripts) with Azure AI Search vector retrieval over regulatory rulebooks.
* Stateful LangGraph DAG orchestrating ingestion, extraction, and GPT-4o compliance reasoning with strict deterministic JSON output (`ComplianceIssue` schema).
* Enterprise web console with synchronized video seeking to offending violation timestamps and distributed tracing via OpenTelemetry and Azure Application Insights.

[Repository](https://github.com/AradwadTushar/langgraph-video-auditor) · [Working Demo Video (Google Drive)](https://drive.google.com/file/d/1IfOh9tgOWX-rfJrcTSTBQI7dtiS7Mal8/view?usp=sharing)

---

### [ResumeIQ AI](https://github.com/AradwadTushar/AI-Based-Resume-Builder-and-Analyzer) — Resume Builder & ATS Analytics Platform (v2)
`React` `FastAPI` `PostgreSQL (JSONB)` `SQLAlchemy Async` `Clerk` `Gemini 1.5 Flash` `WeasyPrint`
* Full-stack resume platform: React live-preview editor synced to an async FastAPI backend, with a server-side Jinja2 + WeasyPrint pipeline producing pixel-identical, ATS-compliant PDF exports.
* Schema flexibility via PostgreSQL JSONB columns to persist semi-structured resume sections with debounced autosaving.
* Built-in ATS keyword matcher and local textual PDF parsing via `pdfminer.six` with sliding-window rate limiting (15 req/min) and tiered AI quotas.
* Ownership-aware authorization pairing Clerk RS256 JWT verification with request-scoped async DB sessions, preventing IDOR-class vulnerabilities.

[Repository](https://github.com/AradwadTushar/AI-Based-Resume-Builder-and-Analyzer) · [Live Application](https://resumeiq-ai.pages.dev)

---

### [StudyTracker](https://github.com/AradwadTushar/StudyTracker) — Cross-Platform Exam Preparation App
`React Native` `Expo` `Zustand` `AsyncStorage` `WebView` `KaTeX`
* Cross-platform (iOS/Android) offline-first mobile app for competitive exam prep featuring a state-aware AI companion ("Pip") that reads live state from a global Zustand store.
* Rich notes module rendering markdown and mathematical KaTeX inside a WebView editor, with import support from ChatGPT, Gemini, and Notion exports.
* Full productivity toolkit: syllabus parser, quiz engine with re-attempt tracking, epoch-based session timer, and reminders running with zero-latency local caching.

[Repository](https://github.com/AradwadTushar/StudyTracker)

---

### [Salon Management Desktop App](https://github.com/AradwadTushar/Salon-Management-App) — POS & Business Operations Suite
`Electron` `JavaScript` `SQLite` `Chart.js`
* Production Electron billing and client management desktop application in active daily use at a commercial salon, optimized for sub-2-minute billing with phone-based customer autofill.
* Revenue analytics dashboard (daily/weekly/monthly, UPI vs. Cash, staff leaderboards) via Chart.js, plus automated WhatsApp bill-sharing and CSV ledger exports.
* Native SQLite integration ensuring 100% offline operational resilience with zero cloud downtime risks.

[Repository](https://github.com/AradwadTushar/Salon-Management-App)

---

### [NutriLens](https://github.com/AradwadTushar/NutriLens---An-Ingredient-Scanner-) — AI Food Label Scanner
`React` `Flask` `PaddleOCR` `MongoDB` `GPT-4o-mini`
* B.Tech final-year project, awarded EX (Highest Distinction).
* Tuned a custom PaddleOCR computer vision pipeline for Indian packaged goods (grayscale preprocessing, adaptive thresholding, bounding box merging), achieving 85–95% OCR accuracy.
* Evaluates extracted additives and nutritional tables against user dietary restrictions using structured LLM analysis.

[Repository](https://github.com/AradwadTushar/NutriLens---An-Ingredient-Scanner-)

---

## Education

**B.Tech, Information Technology** — M.S. Bidve Engineering College, Latur (DBATU)  
*2021 – 2025* · CGPA: 7.73 · Final Semester SGPA: 9.55 · First Class with Distinction

---

## Contact

Open to AI Systems / GenAI, Full-Stack, and Backend Engineering roles.

* [LinkedIn](https://linkedin.com/in/tushar-aradwad-536570307)
* [Portfolio](https://dev-tushar-aradwad-portfolio.vercel.app)
* [aradwadtushar72@gmail.com](mailto:aradwadtushar72@gmail.com)

---

<p align="center"><i>Building products, not tutorials.</i></p>
