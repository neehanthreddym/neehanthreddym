<!-- <p align="left">
  <img src="https://komarev.com/ghpvc/?username=neehanthreddym&amp;label=Profile+views&amp;color=0e75b6&amp;style=flat" alt="Profile views" />
</p> -->
![Profile views](https://komarev.com/ghpvc/?username=neehanthreddym&label=Profile+views&color=0e75b6&style=flat)

# Hi 👋, I'm Neehanth Reddy
### AI/ML | Data Analytics | Data Science
### Turning raw data into predictive models, decision-ready dashboards, and deployable AI systems.

I build analytical and AI systems from initial data preparation through evaluation and delivery. My public work includes customer segmentation and forecasting pipelines, churn models and Power BI dashboards, document-grounded RAG, structured LLM workflows, and FastAPI services backed by relational and document databases.

<p align="left">
  <a href="https://neehanth.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-868629?style=flat-square" alt="Portfolio">
  </a>
  <a href="https://www.linkedin.com/in/neehanthreddy">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://x.com/NeehanthReddyM">
    <img src="https://img.shields.io/badge/-000000?style=flat-square&logo=x&logoColor=white" alt="X">
  </a>
</p>

## Selected work

### [SmartSupply — Inventory API and Natural-Language Agent](https://github.com/neehanthreddym/smartsupply)

A FastAPI inventory system that separates transactional operations in PostgreSQL from audit and conversation history in MongoDB.

- Seeded and managed 22 products, 4 warehouses, 88 inventory records, and 320 movement records.
- Implemented JWT authentication, request tracing, FIFO stock movement, low-stock detection, and immutable audit logs.
- Exposed 12 permission-aware agent tools for querying and modifying inventory through natural language.
- Tested more than 20 agent queries and documented matching, error-handling, and response-formatting limitations.

<!-- `Python` · `FastAPI` · `PostgreSQL` · `MongoDB` · `SQLAlchemy` · `LangChain` · `JWT` -->
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain">
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT">
</p>

### [Agentic Resume Screening Workflow](https://github.com/neehanthreddym/agentic-resume-screener)

A LangGraph workflow for extracting resume and job requirements, analyzing skill gaps, and returning structured candidate–job fit evidence.

- Parallelized resume and job-description extraction with asynchronous LangGraph nodes.
- Reduced end-to-end Gemini pipeline latency by approximately 30–40%, bringing tested runs below 40 seconds.
- Added typed Pydantic outputs and documented failure modes involving coursework inflation, domain pollution, and invalid transferable-skill mappings.

<!-- `Python` · `LangGraph` · `Pydantic` · `Structured LLM Output` · `Document Parsing` -->
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph">
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" alt="Pydantic">
  <img src="https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Google Gemini">
  <img src="https://img.shields.io/badge/PyMuPDF-EC1C24?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="PyMuPDF">
</p>

### [DocQuery — Research Paper RAG](https://github.com/neehanthreddym/doc_query_rag)

A document-grounded question-answering application for AI and machine-learning research papers.

- Built PDF ingestion, chunking, 384-dimensional MiniLM embeddings, and ChromaDB HNSW retrieval.
- Connected retrieved context to `gpt-oss-20b` through Groq and exposed the workflow through FastAPI.
- Containerized the application with Docker and documented delivery through GitHub Actions, AWS ECR, and EC2.
- Added a benchmarking harness for comparing ANN implementations by build time, memory, query speed, and Recall@K.

<!-- `Python` · `FastAPI` · `ChromaDB` · `Sentence Transformers` · `Docker` · `AWS` -->
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/ChromaDB-5A29E4?style=flat-square&logoColor=white" alt="ChromaDB">
  <img src="https://img.shields.io/badge/Sentence%20Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Sentence Transformers">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
</p>

### [E-Commerce Analytics Pipeline](https://github.com/neehanthreddym/ecommerce_analytics_pipeline)

An analytical pipeline for customer behavior, product relationships, and revenue forecasting.

- Cleaned 541,909 retail records to 398,139 validated transactions by removing cancellations, missing customer identifiers, invalid prices, and administrative entries.
- Identified four customer segments using RFM features, K-means clustering, and silhouette-based model selection.
- Generated association rules for product bundling and inventory-planning opportunities.
- Selected a SARIMA specification with test RMSE of approximately 25,108, compared with approximately 28,060 for the initial specification.

<!-- `Python` · `pandas` · `scikit-learn` · `RFM Analysis` · `Association Rules` · `SARIMA` · `Prophet` -->
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white" alt="Plotly">
  <img src="https://img.shields.io/badge/SARIMA-4051B5?style=flat-square" alt="SARIMA">
  <img src="https://img.shields.io/badge/Prophet library-Facebook-0072B2?style=flat-square" alt="Prophet">
</p>

### Telecom Churn — Analysis and Prediction

Two complementary projects examining the same business problem from reporting and predictive-modeling perspectives.

- [Customer Churn Analysis Dashboard](https://github.com/neehanthreddym/customer-churn-anlaysis): analyzed 7,043 customers in Power BI, measuring a 27% churn rate and approximately $139.13K in monthly revenue exposure.
- [Telecom Churn Prediction](https://github.com/neehanthreddym/telecom-churn-model): trained a Keras ANN that reached 91.22% validation accuracy and 0.81 F1 for the churn class.
- Examined contract type, tenure, payment method, service bundles, billing, and support activity as retention indicators.

<!-- `Power BI` · `Python` · `pandas` · `TensorFlow` · `Keras` · `scikit-learn` -->
<p>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" alt="Keras">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
</p>

## Technical strengths

| Area | Technologies |
|---|---|
| Data and analytics | Python, SQL, pandas, NumPy, scikit-learn, Power BI, PySpark |
| Modeling and signal processing | TensorFlow, Keras, statsmodels, MNE, SciPy |
| Applied AI | LangGraph, LangChain, ChromaDB, sentence-transformers |
| APIs and data stores | FastAPI, PostgreSQL, MongoDB, SQLAlchemy |
| Delivery and reproducibility | Docker, DVC, GitHub Actions, AWS ECR, EC2, S3, CloudWatch |

## Engineering approach

Across these projects, I focus on:

- validating and documenting data-quality decisions before modeling;
- selecting evaluation methods that match the problem, including class-specific metrics, time-based testing, and leakage-aware validation;
- packaging models and analytical workflows so they can be reproduced or used through an application;
- documenting limitations, failure modes, and operational trade-offs alongside successful results.

## Connect
<p align="left">
  <a href="https://neehanth.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-868629?style=flat-square" alt="Portfolio">
  </a>
  <a href="https://www.linkedin.com/in/neehanthreddy">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://x.com/NeehanthReddyM">
    <img src="https://img.shields.io/badge/-000000?style=flat-square&logo=x&logoColor=white" alt="X">
  </a>
</p>

---

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=light)
