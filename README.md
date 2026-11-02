# Hi, I'm Allan Ayikanying 👋

**Senior Backend Engineer & Solution Architect**  
*Kampala, Uganda* • [LinkedIn](https://linkedin.com/in/allan-ayikanying) • [Portfolio](https://ayikanying.netlify.app) • [Email](mailto:allanayikanying72@gmail.com)

---

### 🚀 About Me
Backend engineer and solutions architect specializing in **high-throughput financial platforms**, **multi-tenant data architectures**, and **applied machine learning inference pipelines**. I design mission-critical systems that enforce strict data safety invariants (PostgreSQL Row-Level Security, pessimistic concurrency locking, and double-entry ledger parity).

---

### 🛠️ Core Technical Expertise

- **Backend & APIs:** Python 3.11+ (FastAPI, Pydantic V2, SQLAlchemy), Java 17+ (Spring Boot 3), RESTful APIs, OpenAPI / Swagger
- **Databases & Multi-Tenancy:** PostgreSQL (Row-Level Security - RLS with `FORCE ROW LEVEL SECURITY`), DuckDB, Redis Caching, PostGIS
- **Applied ML & Decision Systems:** Model Lifecycle Management (`ACTIVE` → `TESTING` → `LIVE`), scikit-learn, FastEmbed vector mapping, GoRules (ZEN JDM Engine)
- **Architecture & Reliability:** Maker-Checker (Four-Eyes Principle), Transactional Outbox Pattern, Concurrency Locking (`SELECT ... FOR UPDATE`), Universal Idempotency Keys
- **DevOps & Tooling:** Docker, Docker Compose, Git (Trunk-Based), GitHub Actions (CI/CD), Postman

---

### 🏛️ Key Engineered Systems

#### 1. [FlexiScore: Automated Multi-Tenant Credit Decisioning Engine](https://github.com/Ayikanying-ux/Credit-scoring-system.-)
*Python, FastAPI, PostgreSQL RLS, scikit-learn, Docker, Redis*
- Engineered an enterprise credit scoring engine evaluating loan applicants using financial indicators, alternative telecom data, and risk scorecards.
- Built full ML model versioning and runtime inference with strict pre-scoring input data contracts.
- Implemented a custom node handler bridging the Go-based ZEN rule engine with Python scikit-learn models.
- Enforced cryptographic tenant isolation at the database layer using PostgreSQL **Row-Level Security (RLS)** with table-owner enforcement.
- Built an atomic, transaction-scoped audit event bus guaranteeing tamper-evident auditability.

#### 2. Applied Machine Learning & Acoustic Signal Processing
*Python, scikit-learn, STFT, MFCCs, Librosa*
- Researched audio-based respiratory disorder detection by isolating respiratory acoustics from ambient noise.
- Extracted 13-band Mel-Frequency Cepstral Coefficients (MFCCs) and tuned an RBF-kernel SVM classifier, achieving **93% precision** on acoustic benchmark datasets.

#### 3. Enterprise Trade Financing & Financial Invariant Framework
*Java / Spring Boot 3, PostgreSQL, Redis*
- Designed invoice pass-through workflows and maker-checker approval state machines enforcing role separation (`maker_id != checker_id`).
- Codified institutional architectural standards establishing universal invariants: database-level locking, idempotent payment retries, and double-entry balance parity.

---

### 🤝 Open Source & Ecosystem
I actively participate in open-source developer ecosystems across Africa and globally:
- **Ecosystem Interests:** Rule engines ([GoRules ZEN](https://github.com/gorules/zen)), vector embeddings ([FastEmbed](https://github.com/qdrant/fastembed)), authorization ([Casbin](https://github.com/casbin)), and financial inclusion systems.
- **Community:** Active member of the East African developer ecosystem ([OSCA Kampala](https://oscafrica.org/), PyCon Uganda).

---

<p align="center">
  <a href="https://linkedin.com/in/allan-ayikanying"><b>LinkedIn</b></a> •
  <a href="https://ayikanying.netlify.app"><b>Portfolio</b></a> •
  <a href="mailto:allanayikanying72@gmail.com"><b>Email</b></a>
</p>
