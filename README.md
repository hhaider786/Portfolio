# Muhammad Haider Mustafa — Portfolio

**Full-Stack Developer · AI/NLP · Cybersecurity**

Hobart, TAS | haidermustafa2012@gmail.com | [linkedin.com/in/haider-mustafa-03104b196](https://linkedin.com/in/haider-mustafa-03104b196)

---

> **A note on this portfolio:** These repositories represent my projects and work across university and professional settings. Some projects have been reduced to what I can share publicly — due to NDAs, government security classifications, or commercial confidentiality. Where full code cannot be shared, each repo contains a detailed architecture document covering the system design, technical decisions, and outcomes, so readers can still evaluate the depth and quality of work involved.

---

## About

I'm a software developer completing a **Master of Information Technology** at the University of Tasmania (graduating July 2026), specialising in **Artificial Intelligence** and **Cybersecurity**. I hold a Bachelor of Science in Computer Science from Information Technology University (ITU), Lahore.

My work spans full-stack web development, geospatial platforms, AI/NLP systems, PKI and identity infrastructure, and secure code practices — applied across government, enterprise, and academic settings:

- **Government:** Built the DSS platform, a production three-tier reporting system commissioned by the **Tasmanian Department of Premier and Cabinet (DPAC)**, serving 100+ government staff across agencies. The system uses Azure Entra ID authentication, dynamic schema design, CI/CD via GitHub Actions and Docker, and meets Australian Government security and audit compliance requirements.
- **National-level deployment:** Co-led the ATLAS geospatial platform as team lead at ITU Lahore — a custom WFS-T geospatial data service accepted by the **Punjab Information Technology Board (PITB)** for national deployment in Pakistan.
- **Enterprise PKI:** At Codegic, contributed to the Khatim PKI platform — a custom Certificate Authority and Registration Authority for corporate PDF signing and document integrity, built in Java Spring Boot and Hibernate.
- **AI/NLP:** Built RAG systems with ChromaDB and Gemini function calling, and trained multi-classifier speech emotion recognition pipelines achieving 92.73% accuracy on the RAVDESS dataset.
- **Data science:** Analysed World Bank education data across 60+ countries and performed exploratory spatial data analysis (ESDA) of global earthquake patterns, including Moran's I clustering confirmation.

I hold a student visa with work rights (48 hrs/fortnight) and will transition to a **Subclass 485 post-study work visa** in mid-2026, giving full unrestricted work rights for 3–4 years.

---

## Skills

| Category | Technologies |
|---|---|
| **Frontend** | React, TypeScript, JavaScript (ES6+), HTML5, CSS3, Tailwind CSS, Vite, OpenLayers, Leaflet |
| **Backend** | ASP.NET Core, Java Spring Boot, FastAPI, Flask, Node.js, PHP (Laravel) |
| **AI / NLP** | Google Gemini API, ChromaDB, SentenceTransformers, scikit-learn, XGBoost, PyTorch |
| **Databases** | SQL Server, PostgreSQL, PostGIS, MongoDB, SQLite, Entity Framework Core |
| **DevOps** | Docker, Docker Compose, GitHub Actions, CI/CD |
| **Identity & Auth** | Azure Entra ID (MSAL), JWT, PBKDF2, OAuth 2.0 |
| **Geospatial** | GeoServer, PostGIS, WFS-T, GeoJSON, KML, Shapefiles |
| **Cybersecurity** | OWASP Top 10, CWE analysis, secure code review, honeypots, ELK Stack |
| **Tools** | Git, Jira, Figma, Agile/Scrum |

---

## Projects

### Full-Stack / Web Development

| Project | Description | Tech | Repo |
|---|---|---|---|
| **DSS — Tasmanian Government Platform** | Production self-service reporting platform for the Dept. of Premier and Cabinet (DPAC). 14+ dynamic field components, Azure Entra ID auth, rate limiting, CI/CD. | React · TypeScript · ASP.NET Core 10 · SQL Server · Azure AD · Docker | [dss-platform](https://github.com/hhaider786/dss-platform) |
| **ATLAS — Geospatial Data Service** | National geospatial platform accepted by Punjab IT Board (PITB). Custom WFS-T service, dual-database architecture, 10× performance improvement over PostGIS. | React · OpenLayers · Leaflet · Node.js · GeoServer · PostGIS · MongoDB | [atlas-geospatial](https://github.com/hhaider786/atlas-geospatial) |

---

### Artificial Intelligence / NLP

| Project | Description | Tech | Repo |
|---|---|---|---|
| **WWII Q&A RAG System** | Question-answering system with 4-mode query router (RAG, Gemini, Tools, hybrid). ChromaDB vector store, SentenceTransformer embeddings, Gemini API function calling. | Python · Gemini API · ChromaDB · SentenceTransformers · Gradio | [gemini-rag-qa](https://github.com/hhaider786/gemini-rag-qa) |
| **Speech Emotion Recognition** | Multi-classifier ML pipeline for emotion detection from raw audio. MFCC + spectral feature extraction via Librosa. MLP achieved 92.73% accuracy; KNN 90.67% with best efficiency. Compared 6 classifiers via 5-fold CV grid search. | Python · Librosa · scikit-learn · RAVDESS · TESS | [speech-emotion-recognition](https://github.com/hhaider786/speech-emotion-recognition) |

---

### Data Science / Geospatial Analysis

| Project | Description | Tech | Repo |
|---|---|---|---|
| **Global Education Analytics** | Two-phase World Bank data analysis. Phase 1: LinearRegression forecasts 2025 indicators for 60+ countries with KNN imputation. Phase 2: Decision Tree / Random Forest / Logistic Regression classify country performance tiers. | Python · pandas · scikit-learn · Matplotlib | [big-data-education-analytics](https://github.com/hhaider786/big-data-education-analytics) |
| **Earthquake Spatial Analysis** | ESDA of global earthquake epicenter data. Moran's I of 0.89 (depth) and 0.73 (magnitude) confirm strong spatial clustering. LISA maps show clusters align with tectonic fault lines. | Python · PySAL · ESDA · GeoPandas · Folium | [earthquake-spatial-analysis](https://github.com/hhaider786/earthquake-spatial-analysis) |

---

### Cybersecurity

| Project | Description | Tech | Repo |
|---|---|---|---|
| **Banking App Security Audit** | Full vulnerability audit of a Python banking application. Identifies and remediates 7 CWEs including SQL injection, path traversal, plaintext passwords, and timing attacks. Before/after code comparison. | Python · SQLite · PBKDF2 · secrets module | [banking-security-audit](https://github.com/hhaider786/banking-security-audit) |

---

### Algorithms & Data Structures

| Project | Description | Tech | Repo |
|---|---|---|---|
| **CS Algorithms** | Clean implementations of classical algorithms and data structures from coursework at ITU Lahore. Covers recursion, counting sort, heaps/HeapSort (two buildHeap methods compared), priority queue, BSTree, and Minimax Tic-Tac-Toe. | C++ · Python | [cs-algorithms](https://github.com/hhaider786/cs-algorithms) |

---

## Education

**Master of Information Technology and Systems** *(Expected Jul 2026)*
University of Tasmania, Hobart | Specialisations: Artificial Intelligence & Cybersecurity

**Bachelor of Science in Computer Science** *(Aug 2023)*
Information Technology University, Lahore, Pakistan

---

## Certifications

- Introduction to Computer Science and Programming Using Python — edX / MIT OpenCourseWare
- Certified Java Programming Training — Cisco Networking Academy

---

## Professional Experience

**Software Engineer (Associate)** — Codegic, Lahore | Sep–Nov 2023

Contributed to **Khatim**, Codegic's enterprise Public Key Infrastructure (PKI) platform for corporate-level digital document signing.

- Developed backend services for a custom **Certificate Authority (CA)** and **Registration Authority (RA)** using **Java Spring Boot**, **Hibernate ORM**, and **Apache Tomcat**
- The CA issued X.509 digital certificates bound to corporate identities; the RA validated and authorised certificate requests before issuance — separating trust management from certificate issuance for security compliance
- Integrated PKI workflows into a **PDF digital signing pipeline**, enabling organisations to cryptographically sign documents and verify their integrity and authenticity over time
- Worked within an Agile team using Jira for sprint planning and task tracking

