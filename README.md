# 👋 Hi, I'm Hamza — Backend & Applied AI Engineer

🎓 Honours Computer Science @ WLU | Concentration in Big Data Systems

I build event-driven, multi-tenant systems that put LLMs into real workflows, with the guardrails that make them trustworthy.

---

## 🚀 What I've Built

### [TradeLedger AI](https://github.com/Siddiqui-Hamza/tradeledger-architecture)
SMS-based receipt capture for trade contractors. A field worker texts a receipt photo; the platform extracts the data with LLM vision, matches it to the right job, and posts a coded transaction to QuickBooks Online with the original image attached.

*   **Reliability:** Confidence-gated extraction that holds uncertain receipts instead of posting bad data, triggering a human-in-the-loop SMS disambiguation loop.
*   **Data Integrity:** 7-table multi-tenant PostgreSQL schema with partial/composite unique indexes and SHA-256 image hashing for strict idempotent ingestion.
*   **Infrastructure:** 10-state receipt lifecycle, database-side PL/pgSQL JSON aggregations (native weekly spend computations), and Intuit OAuth 2.0 token lifecycle management.

> <details>
> <summary><kbd> 🖼️ View System Architecture Diagram </kbd></summary>
> <br>
> <a href="https://github.com/Siddiqui-Hamza/tradeledger-architecture">
> <img src="./tradeledger.png" alt="TradeLedger AI Architecture" width="100%" />
> </a>
> </details>

### [LLM Prompt Enhancer](https://github.com/Siddiqui-Hamza/ai-prompt-enhancer)
A full-stack AI platform that seamlessly injects a native enhancement engine directly into the ChatGPT interface. It automatically reads raw inputs and replaces them with highly structured, LLM-optimized prompts without forcing the user to switch tabs.

*   **Frontend Engineering:** Bypassed complex React hydration conflicts using a debounced `MutationObserver` with idempotent injection guards to keep the UI persistent across ChatGPT's DOM mutations.
*   **Architecture:** A centralized Spring Boot REST API concurrently serving a standalone React/Vite dashboard and the Manifest V3 Chrome Extension.

> <details>
> <summary><kbd> 🖼️ View System Architecture Diagram </kbd></summary>
> <br>
> <a href="https://github.com/Siddiqui-Hamza/ai-prompt-enhancer">
> <img src="./prompt-enhancer.png" alt="LLM Prompt Enhancer Architecture" width="100%" />
> </a>
> </details>

---

## 🌱 Currently Building
- Automated financial news sentiment ETL pipeline (Python, PySpark, PostgreSQL)
- Distributed data processing & cloud infrastructure (Docker, Hadoop)

---

## ⚙️ Stack

### Languages & Databases
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

### Backend, Big Data & AI
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black)

### Infrastructure & APIs
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![OAuth 2.0](https://img.shields.io/badge/OAuth_2.0-EB5424?style=for-the-badge&logo=auth0&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
