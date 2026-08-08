# Aditya Debnath

🚀 **AI & Backend Engineer | Distributed Systems & AI Agents**

I am a backend-focused software engineer specializing in building secure, high-concurrency distributed systems and AI-powered products. I design and scale applications utilizing LLMs, Retrieval-Augmented Generation (RAG), and multi-agent workflows.

---

### 🛠️ Core Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Languages** | ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-00758F?style=for-the-badge&logo=mysql&logoColor=white) |
| **Backend & Microservices** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white) ![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white) |
| **AI, RAG & Agents** | ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-orange?style=for-the-badge) ![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white) ![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75C2?style=for-the-badge&logo=googlegemini&logoColor=white) |
| **Databases & Vector Search** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-316192?style=for-the-badge) ![Qdrant](https://img.shields.io/badge/Qdrant-red?style=for-the-badge&logo=qdrant) ![Hibernate/JPA](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white) |
| **Infrastructure & Tools** | ![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![REST APIs](https://img.shields.io/badge/REST_APIs-005571?style=for-the-badge) |

---

### ⭐️ Highlighted Project: Nexora

**Nexora** is a proof-of-work developer network that replaces self-reported resume buzzwords with verified, inspectable code citations.

*   **Architecture:** Multi-service system powered by **Spring Boot**, **Spring Cloud (Eureka, API Gateway)**, and **PostgreSQL**.
*   **Security & Redaction:** Built a local extraction layer that scrubs secrets, JWT tokens, and credentials before transmission.
*   **AI Integration:** Leveraged **Spring AI** and **Google Gemini** to audit repository commit logs, pull requests, and file trees to build project-first developer profiles.
*   **System Design:**
```mermaid
graph TD
    Gateway[API Gateway] --> Eureka[Eureka Service Discovery]
    
    Gateway --> UserService[User Service]
    Gateway --> PostService[Post Service]
    Gateway --> ProfileService[Profile Service]
    
    subgraph Profile Service Internal
        ProfileService --> Encryptor[AES Credentials Encryptor]
        ProfileService --> Crawler[GitHub Crawler]
        ProfileService --> Scrubber[Secret Redactor]
        ProfileService --> SpringAI[Spring AI Client]
    end
    
    SpringAI --> Gemini[Google Gemini AI]
    ProfileService --> Postgres[(PostgreSQL DB)]
```

---

### 🧠 Core Expertise & Focus Areas

*   **AI Products & RAG:** Architecting Retrieval-Augmented Generation (RAG) pipelines and multi-agent workflows using **LangChain** and **LangGraph** with vector backends like **pgvector** and **Qdrant**.
*   **High-Concurrency & Multithreading:** Deep understanding of multithreading concepts, including the Producer-Consumer problem, custom thread pools, and multithreaded sorting implementations.
*   **Secure API Design:** Extensive implementation of authentication pipelines using **Spring Security**, OAuth2, and JWT.

---

### 📊 GitHub Statistics

<p align="left">
  <!-- General Stats Card -->
  <img src="https://github-readme-stats.vercel.app/api?username=adityadebnath009&show_icons=true&theme=tokyonight&count_private=true" alt="Aditya's GitHub Stats" height="190px" />
  <!-- Streak Stats Card -->
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=adityadebnath009&theme=tokyonight" alt="Aditya's Streak Stats" height="190px" />
  <!-- Top Languages Card -->
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=adityadebnath009&layout=compact&theme=tokyonight" alt="Aditya's Top Languages" height="190px" />
</p>

---

### 🏋️‍♂️ Fun Fact
*   *My best engineering ideas and system architectures are always explored and solved while I'm exercising.*

---

### 📬 Get in Touch

*   **LinkedIn:** [aditya-debnath-93330b325](https://linkedin.com/in/aditya-debnath-93330b325)
*   **Email:** [debnathaditya2005@gmail.com](mailto:debnathaditya2005@gmail.com)

*⚡ "Evidence before assertion."*
