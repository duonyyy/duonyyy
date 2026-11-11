<div align="center">

# Hi, I'm Dương Tùng Dương 👋

### Backend Developer & AI Engineer

*Building reliable backend systems and practical AI-powered applications.*

📍 Ho Chi Minh City, Vietnam · 🎓 Information Technology, UIT – VNU-HCM  
💼 Open to **Backend Developer / AI Engineer Intern & Fresher** opportunities

[![GitHub](https://img.shields.io/badge/GitHub-duonyyy-181717?style=flat-square&logo=github)](https://github.com/duonyyy)
[![Email](https://img.shields.io/badge/Email-Contact_Me-0F766E?style=flat-square&logo=gmail&logoColor=white)](mailto:duongtungduong34@gmail.com)

</div>

---

## 👨‍💻 About Me

I'm an Information Technology student focused on **Backend Development and AI Engineering**. I enjoy building backend services, data pipelines, and intelligent applications that integrate machine learning and LLM capabilities into real-world systems.

- **Backend Engineering:** REST APIs, authentication and authorization, database design, asynchronous processing, and service integration.
- **AI Engineering:** LLM applications, RAG, multi-agent workflows, NLP model evaluation, OCR, and AI service integration.
- **Infrastructure:** Event-driven processing, caching, Docker, and CI/CD pipelines.
- **Currently Building:** An enterprise AI agent platform focused on modular execution, tool governance, and human-in-the-loop workflows.

## 🛠️ Tech Stack

| Area | Technologies |
| --- | --- |
| **Languages** | TypeScript, JavaScript, Python, PHP |
| **Backend** | NestJS, Node.js, Express.js, FastAPI, Laravel |
| **AI / LLM** | PyTorch, LangGraph, RAG, BGE-M3, BM25, PaddleOCR |
| **Data & Messaging** | PostgreSQL, MongoDB, Redis, Qdrant, Apache Kafka |
| **Frontend** | Next.js, React, Tailwind CSS |
| **DevOps & Tools** | Docker, Git, GitHub Actions, Postman, MinIO / S3 |

---

## 🚀 Featured Projects

### 🤖 AI Engineering & Intelligent Systems

#### [Enterprise AI Agent Platform](https://github.com/duonyyy/Enterprise-AI-Agent-Platform) · *In Active Development*

A reusable platform that enables enterprises to build and manage secure AI agents across business workflows without developing separate agent infrastructure for each use case.

- **Agent Architecture:** Designed a modular, multi-tenant architecture separating the Control API, LangGraph-based Agent Runtime, background workers, and Studio Web.
- **Execution & State:** Developed agent execution foundations with REST APIs, SSE streaming, persistent run state, idempotent requests, and retry/recovery mechanisms.
- **Tool Governance:** Designing a secure Tool Gateway for MCP integrations, schema validation, permission enforcement, human-in-the-loop approvals, and audit logging.
- **Security & Isolation:** Developing authentication, RBAC, and workspace isolation to enforce secure access across enterprise tenants.
- **RAG Infrastructure:** Configured Qdrant vector search with multilingual E5 embeddings, Redis, and MinIO using Docker Compose.

**Stack:** Python · FastAPI · LangGraph · PostgreSQL · Redis · Qdrant · MinIO · Next.js · Docker

#### [BodyWise — Health & InBody Multi-Agent RAG](https://github.com/duonyyy/Health-InBody-Agent-RAG)

An AI-powered health assistant that interprets InBody measurements and retrieves evidence from health documents to support personalized nutrition and workout guidance.

- **Multi-Agent System:** Built LangGraph-based workflows with specialized agents for InBody analysis, nutrition planning, workout recommendations, and knowledge retrieval.
- **Document ETL & OCR:** Developed document-processing pipelines with PaddleOCR, text normalization, table-aware chunking, and parent-child retrieval to preserve document context.
- **Hybrid RAG:** Combined BGE-M3 embeddings (1024 dimensions), Qdrant vector search, and BM25 lexical retrieval for evidence-based question answering.
- **Safety & Validation:** Implemented deterministic safety checks, citation verification, and evidence-based response validation to reduce unsupported medical claims.
- **Testing:** Reported 152 passing automated tests and indexed 4,405 document chunks for retrieval.

**Stack:** Python · FastAPI · LangGraph · Qdrant · BGE-M3 · BM25 · PaddleOCR · PostgreSQL · Next.js · Docker

#### [Vietnamese Toxic Comment Classification](https://github.com/duonyyy/Predict-toxic-comments) · *Team Project*

An NLP-based content moderation system combining Vietnamese social media data collection, hierarchical toxicity classification, and real-time comment monitoring.

- **Data ETL & Annotation:** Collected and preprocessed 48,670 Vietnamese comments from Facebook, YouTube, TikTok, VOZ, and Threads using multi-stage cleaning and LLM-assisted labeling.
- **Model Evaluation:** Benchmarked TextCNN, PhoBERT, ViDeBERTa, and XLM-RoBERTa. PhoBERT achieved **91.76% accuracy and 0.7943 Macro-F1** for binary toxicity classification.
- **Hierarchical Classification:** Evaluated explicit versus implicit toxic expressions, with XLM-RoBERTa achieving **83.79% accuracy** on the second-stage classification task.
- **Real-Time Processing:** Integrated Apache Kafka, Python/PyTorch inference workers, Redis, Node.js APIs, and SSE streaming for live comment analysis and dashboard updates.

**Stack:** Python · PyTorch · PhoBERT · XLM-RoBERTa · Node.js · TypeScript · Apache Kafka · MongoDB · Redis · Next.js

#### [MLOps Pipeline](https://github.com/duonyyy/MLOps-Pipeline) · *Learning Project*

A hands-on machine learning engineering project exploring reproducible experiments, dataset versioning, automated quality checks, and model delivery.

- **ML Experimentation:** Worked with the UCI Adult Income dataset to explore model training, hyperparameter tracking, and evaluation using MLflow.
- **Data Versioning:** Practiced reproducible dataset management with DVC and cloud object storage.
- **CI/CD & Model Serving:** Explored GitHub Actions workflows for automated testing, training, F1-score quality gates, and FastAPI-based model serving.

**Stack:** Python · Scikit-learn · MLflow · DVC · GitHub Actions · FastAPI

---

### 🧩 Backend Engineering & Full-Stack Systems

#### [Foodee — Smart Food Delivery](https://github.com/duonyyy/Foodee-Smart-Food-Delivery)

A food delivery platform integrating restaurant management, online ordering, digital payments, computer vision, and conversational AI to simplify food discovery and ordering.

- **Backend Architecture:** Developed modular NestJS backend services for restaurant management, product catalogs, order processing, authentication, and role-based access control.
- **AI Food Recognition:** Integrated a computer vision pipeline combining YOLOv8 food detection and EfficientNet-B2 classification to recognize 30 Vietnamese dishes from images.
- **Conversational Ordering:** Built a FastAPI-based AI chatbot service to interpret natural-language food requests and support order creation.
- **Payments & Reliability:** Integrated payment workflows with MoMo and VNPay, using transaction validation, idempotency, and order-state management.
- **Infrastructure:** Used PostgreSQL, Redis, BullMQ background workers, and Docker Compose to support asynchronous processing and service integration.

**Stack:** NestJS · TypeScript · Next.js · FastAPI · YOLOv8 · EfficientNet-B2 · PostgreSQL · Redis · BullMQ · Docker

#### [ThiSmart — Online Examination Platform](https://github.com/duonyyy/Exam-Platform)

An online examination and assessment platform designed to help educational institutions manage question banks, organize exams, evaluate students, and automate exam preparation.

- **REST API & RBAC:** Developed Laravel-based REST APIs for user management, academic subjects, question banks, and examination workflows with Sanctum authentication and role-based authorization.
- **Exam Management:** Built workflows for exam scheduling, student assignments, question distribution, automated scoring, and result management.
- **Reliable Exam Submission:** Implemented debounced answer autosaving, idempotent updates, and database transactions with pessimistic locking to prevent duplicate submissions.
- **AI-Assisted Exam Planning:** Developed an ExamOps AI Copilot architecture using FastAPI and LangGraph to support question-blueprint generation, deterministic validation, and human approval workflows.

**Stack:** PHP · Laravel · Next.js · TypeScript · FastAPI · LangGraph · PostgreSQL · Redis · Docker

---

## 🔍 Engineering Interests

- **Backend Systems:** API design, authentication, clean architecture, event-driven processing, distributed systems, and reliability engineering.
- **Agentic AI & LLMs:** Agent orchestration, RAG evaluation, context engineering, tool calling, MCP, AI safety, and observability.
- **MLOps:** Reproducible experiments, model deployment, automated evaluation, and CI/CD for ML systems.

## 📫 Let's Connect

I'm open to **Backend Developer and AI Engineer Intern / Fresher opportunities**, as well as collaboration on practical AI and open-source projects.

- **GitHub:** [github.com/duonyyy](https://github.com/duonyyy)
- **Email:** [duongtungduong34@gmail.com](mailto:duongtungduong34@gmail.com)

---

<div align="center">

<sub>Build reliable systems. Make AI useful.</sub>

</div>
