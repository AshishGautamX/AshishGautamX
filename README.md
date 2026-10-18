<div align="center">

# Ashish Gautam

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=2500&pause=1200&color=58A6FF&center=true&vCenter=true&width=560&height=42&lines=AI+%26+Systems+Engineer;Optimizing+Low-Latency+ML+Inference;Transformer+World+Models+%26+Explainability;Distributed+Backends+%7C+FastAPI%2C+Redis%2C+Celery">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=2500&pause=1200&color=0969DA&center=true&vCenter=true&width=560&height=42&lines=AI+%26+Systems+Engineer;Optimizing+Low-Latency+ML+Inference;Transformer+World+Models+%26+Explainability;Distributed+Backends+%7C+FastAPI%2C+Redis%2C+Celery" alt="Typing animation">
</picture>

<p>
AI and systems engineer building scalable machine learning infrastructure, model optimization pipelines, and high-throughput backend services.
</p>

<p>
  <a href="https://linkedin.com/in/ashishgautamx">LinkedIn</a> &nbsp;&bull;&nbsp;
  <a href="https://github.com/AshishGautamX">GitHub</a>
</p>

</div>

---

### Featured Projects

| Project | Description | Stack | Live Demo |
| :--- | :--- | :--- | :--- |
| **[PacketSentinel](https://packetsentinel.streamlit.app/)** | Temporal intrusion detection engine using a 3.28M-param Transformer world model over raw PCAP network streams. Achieved 92.41% Macro-F1 at 0.56% FPR (17.7x false-alarm reduction). | PyTorch, Transformers, Captum, Streamlit | [Launch Demo](https://packetsentinel.streamlit.app/) |
| **[Mulyankan AI](https://mulyankanai.netlify.app/)** | Distributed AI grading platform backend evaluating 9+ curriculum tiers with OCR parsing, schema validation, and asynchronous batch job execution. | FastAPI, PostgreSQL, Redis, Celery, Next.js | [Launch Demo](https://mulyankanai.netlify.app/) |

#### Architectural Deep Dives

- **[PacketSentinel](https://packetsentinel.streamlit.app/)**
  - Forecasts temporal network states via K-step autoregressive rollouts over a 91-feature PCAP streaming pipeline.
  - Mitigated 80%+ class imbalance with Focal Loss and effective-number weighting, generalizing to CIC-IoT-2023 at 99.83% Macro-F1 without structural modifications.
  - Serves real-time inference at 16,190 windows/sec on NVIDIA L4 GPUs with integrated Captum feature attributions and MITRE ATT&CK mapping.

- **[Mulyankan AI](https://mulyankanai.netlify.app/)**
  - Architected decoupled REST APIs handling high-throughput batch grading and automated rubric evaluations.
  - Implemented Redis and Celery worker pools for distributed task queues, retry logic, and real-time status polling.
  - Integrated OCR ingestion pipelines across heterogeneous student submission formats, saving educators 3–5 hours per week.

---

### Industry Experience

- **AI Developer** &mdash; Thesisly *(Sept. 2025 – Present)*
  - Optimized and containerized backend AI inference systems for 1,000+ active users, cutting model latency by 40% via quantization and Docker environments.
  - Improved model accuracy by 15% through hyperparameter tuning and automated end-to-end Git CI/CD pipelines reaching 95% test coverage.

- **Web Development Intern** &mdash; Adcuesta *(Dec. 2025 – Present)*
  - Shipped production operations dashboards with Next.js, React, and TypeScript across 12 screens and 17+ REST API integrations.
  - Optimized SQL reporting queries across centralized KPI layers, reducing manual reporting workloads by 60–80%.

---

### Honours & Recognition

- **National Winner, Smart India Hackathon** &mdash; Awarded ISRO's Quantum Frontiers Award among 15,000+ participants for developing quantum-secure systems.
- **National Finalist, NHIDE Hackathon** &mdash; Ranked top 20 nationally for architecting and deploying Mulyankan AI.

---

### Technical Proficiencies

- **Languages:** Python, SQL, C/C++, JavaScript, TypeScript
- **Machine Learning & AI:** PyTorch, Transformers, Model Quantization, Captum, Streamlit
- **Backend & Distributed Systems:** FastAPI, Django, Flask, Node.js, Express.js, Celery, Redis
- **Databases & Storage:** PostgreSQL, MySQL, MongoDB, Supabase
- **DevOps & Infrastructure:** Docker, AWS, Git, GitHub Actions, CI/CD Pipelines, REST APIs
