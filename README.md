# Taha Tahir

Final-year computer engineering student at EMSI Casablanca (5th year, 2022–2027). I work on data pipelines, retrieval systems and applied machine learning, mostly for French and Arabic business contexts, and I try to measure whether things work before calling them done.

Looking for a final-year (PFE) internship in data engineering, data science or applied AI, from February 2027, in Casablanca or Rabat.

Portfolio: [taha-tahir-portfolio.vercel.app](https://taha-tahir-portfolio.vercel.app) · [LinkedIn](https://www.linkedin.com/in/taha-tahir-611500256/) · taha-tahir-2003@hotmail.com

## Selected projects

| Project | What it does | Result | Stack |
|---|---|---|---|
| [Telecom churn and revenue at risk](https://github.com/Tahatahir-IIR/telecom-churn-revenue) | Predicts which telecom customers churn next month and converts the probability into 12-month revenue at risk, with a scoring API and Power BI views. | Test ROC AUC 0.846, recall 0.70, calibrated (Brier 0.135); 874 high-risk customers carrying 741k of 3.1M revenue at risk | scikit-learn, pandas, FastAPI, PostgreSQL, Power BI, Docker, CI |
| [Enterprise RAG Knowledge Assistant](https://github.com/Tahatahir-IIR/Enterprise-RAG-Knowledge-Assistant) | Bilingual FR/AR assistant over invoices, contracts and HR policies. Hybrid search (dense + BM25), access control per department, page citations, refuses when the answer is not in the documents. | 40-question eval: 0% hallucination, MRR 0.944, 100% correct refusals, 29 ms on cache hits | Python, FastAPI, Qdrant, Ollama, Streamlit, Docker, CI |
| [Asterisk Call Logger](https://github.com/Tahatahir-IIR/AsteriskCallLogger) | Ingests call detail records from an Asterisk PBX into a streaming pipeline with search, analytics and role-based access. | 15-service Docker stack; replaces CSV-based CDR handling | Java, Spring Boot, Kafka, Spark, ClickHouse, Elasticsearch, MinIO, Airflow |
| [E-commerce market intelligence pipeline](https://github.com/Tahatahir-IIR/architecture-donnees-projet-nexus) | Scrapes Moroccan e-commerce sites into a bronze/silver/gold data lake and a PostgreSQL warehouse with a price-comparison dashboard. | End-to-end medallion pipeline with Kafka and MinIO | Python, pandas, Kafka, MinIO, PostgreSQL, Streamlit, Airflow |
| [S.O.P.H.I.A](https://github.com/Tahatahir-IIR/S.O.P.H.I.A) | Multi-agent voice assistant: LangGraph routes each request to a specialist agent (system commands, local RAG, maths, writing) and answers in a cloned voice through a 3D avatar. | Final-year capstone, local LLM reasoning with Ollama | Python, LangGraph, LlamaIndex, Ollama, TTS |

Other work: a voxel engine in C++ ([Mooncraft](https://github.com/Tahatahir-IIR/Mooncraft)), a networked JavaFX Pac-Man, a phone-company tycoon game, a MERN chat app, and the redesign of an internal web platform during a year at Wafasalaf.

## Skills

- Languages: Python, SQL, Java, TypeScript, C/C++
- Data and ML: pandas, scikit-learn, model evaluation and calibration, Power BI, Kafka, Spark, Airflow, ClickHouse, PostgreSQL, MinIO
- LLM systems: RAG, hybrid search (Qdrant, BM25), LangGraph agents, evaluation of grounded answers, Ollama
- Backend and tooling: FastAPI, Spring Boot, Next.js, Docker, GitHub Actions, Git
- Spoken: Arabic, French, English
