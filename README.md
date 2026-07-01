# Hi, I'm Esneider 👋

### AI/ML Engineer · Backend Developer

Junior developer focused on AI/ML Engineering, workflow automation, and backend development, going deep into the data, machine learning, and language model ecosystem through real projects — conversational agents, RAG architectures, and model fine-tuning. What drives me about AI is the practical side: not just understanding how it works, but building tools with it that solve concrete problems.

<div align="center">

<a href="https://linkedin.com/in/tu-usuario"><img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff" height="100" height="35"></a>
<a href="mailto:esalgo22@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" height="100" height="35"></a>

</div>

---

## Stack

<div align="center">

![Skills](https://skillicons.dev/icons?i=python,pytorch,sklearn,fastapi,django,ts,js,nodejs,express,html,css,postgres,supabase,mysql,mongodb,docker,git,github&perline=9)

</div>

```
ML / AI       →  PyTorch · Scikit-learn · LangChain · LangGraph · Ollama · ChromaDB · Pgvector
Fine-tuning   →  QLoRA · LoRA
Data          →  Pandas · NumPy · Matplotlib · Seaborn · Plotly
Backend       →  Python · FastAPI · Django · DRF · Node.js · Express
Databases     →  PostgreSQL · MySQL · MongoDB
Automation    →  n8n
DevOps        →  Docker · Git · GitHub
Frontend      →  HTML · CSS · JavaScript · TypeScript
```

---

## Featured projects

### SOS-AuxilioBot — First aid agent *(completed)*
First-aid conversational agent that guides users step by step through a medical emergency. With text, audio, and image support — because in a critical situation, typing is not always an option.
- RAG architecture with a knowledge base built from MSD Manuals (custom scraper)
- Automatic interpretation of vital signs: temperature, pulse, respiratory rate
- Stack: **FastAPI · n8n · LangChain · vector databases · JavaScript**

🔗 [View repository](https://github.com/esalgo/SOS-AuxilioBot.git)

### Task Manager — REST API with role-based access control *(completed)*
Robust REST API with JWT authentication, differentiated role-based access control (user and administrator), and integrated SPA.
- Scalable, typed, and maintainable architecture with TypeScript and pnpm
- Role-based dashboards and permissions; secure JWT authentication
- Decoupled frontend as a JavaScript vanilla SPA to complete the full functional cycle
- Stack: **Node.js · Express · TypeScript · JavaScript vanilla**

🔗 [View repository](https://github.com/esalgo/task-manager.git)

### Lingua Academia — A customer-service assistant for a simulated language academy *(completed)* 
built on n8n cloud, answers questions (schedules, pricing, courses) via Telegram or a web form, 

- Using RAG over the academy's documents; remembers the last 10 turns, escalates to a human by email when it can't answer, and shows a stats dashboard.
- Stack: **n8n Cloud (orchestration) · OpenAI (gpt-4.1-mini + embeddings) · Pinecone (vector DB) · Google Drive (documents) · Google Sheets (logs) · Gmail (escalation) · Telegram Bot API · plain HTML/CSS/JS frontend, no frameworks.**

🔗 [View repository](https://github.com/esalgo/lingua-academia.git)

### Celeris — AI-Powered Operations Platform for Event Production Agencies (Collaborative project, I worked as Backend developer)

Celeris is a white-label, multi-tenant SaaS platform for ATL/BTL event-production agencies. It replaces scattered spreadsheets with a single workspace covering the full operations   
  cycle — from quote generation to invoicing — all under the agency's own branding.                                                                                                     
                                                                                                                                                                                                      
  - AI-assisted event planning — generate a full event plan from a natural-language brief: the AI classifies the event by attendance tier, scales quantities, prices items against      
  Colombian market ranges, and marks each line as owned inventory vs. external supplier. Financials (cost, revenue, margin) are computed deterministically so the numbers always cohere.
  - Quotes & events — build itemized quotes manually or with AI assistance, track margin/profit per line and per quote, move through a draft → review → approved → sent approval        
  workflow with a full audit log.                                                                                                                                                       
  - Inventory, suppliers & crew management — track owned equipment, external suppliers, and personnel, with availability and scheduling-conflict checks.                                
  - CRM — billing-ready client records with tax ID, contact history, etc.                                                                                                               
  - AI chat assistant — a conversational agent (admin-only) that answers questions about a tenant's events, clients, and finances by querying live data.                                
  - Knowledge base (RAG) — tenants upload their own documents, which are embedded and used to ground the AI's answers and pricing suggestions.                                          
  - Billing & exports — PDF invoices, Excel quote exports, with margin visibility gated by role.                                                                                        
  - Analytics — revenue/margin breakdowns by event, client, and period.                                                                                                                 
  - Multi-tenant, white-label — per-tenant branding, strict data isolation, role-based access control (admin, comercial, contable, logística, personal, viewer), and a super-admin      
  console for cross-tenant management.
  - Stack: **React · Node.js/Express (TypeScript) · Python/FastAPI (AI) · n8n · Supabase (Postgres + pgvector) · Vercel/Render**

🔗 [View deployed](https://celeris-beta.vercel.app/)

### Dental Office Management System *(active development)*
Full web system with differentiated roles (patient, dentist, administrator), appointment scheduling, and clinical records. Hybrid MVT + REST API architecture structured in independent domain applications.
- Custom user model with token-based password recovery
- DB-level integrity constraints to prevent scheduling conflicts
- Stack: **Django · DRF · PostgreSQL · JavaScript**
- *Next: migration to a decoupled API-based architecture — JavaScript vanilla SPA + RAG agent in n8n to handle frequent patient queries*

🔗 [View repository](https://github.com/esalgo/sonrisas.git)

### Local AI Assistant with RAG *(active development)*
Built with full data privacy as a core design decision — no external API calls, no data leaving the machine. Ideal for use cases where information privacy is critical.
- Semantic search over personal documents (PDFs, Word files) with ChromaDB
- Local orchestration with Ollama; web interface with FastAPI
- Stack: **Python · ChromaDB · Ollama · FastAPI · LangChain**

🔗 [View repository](https://github.com/esalgo/asistente-ia-local.git)

---

## Currently learning

**Applying in projects:**
- Advanced RAG patterns for production AI apps (Adaptive RAG, Self-RAG, Agentic RAG)
- LangGraph for stateful agents with complex decision flows

**Studying:**
- Training and fine-tuning deep learning models with QLoRA — efficient adaptation for specific tasks
- MLOps: model deployment, monitoring, and lifecycle management
- NestJS · CI/CD

---
