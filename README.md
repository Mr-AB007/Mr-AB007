# Hi, I'm ANUBHAV 👋

I'm a **Java Full Stack Engineer** who builds **event-driven microservices** with Spring Boot, Kafka, Redis and AWS, and who is now building **AI applications**: local LLM assistants, RAG, ML model serving and MLOps.

My recent work spans both worlds: an **event-driven banking platform** (SmartPay) on the backend side, and **B2**, a private ChatGPT-style assistant that runs **my own versioned LLM** locally with RAG web search, on the AI side.

🔭 **Currently building:** B2, my local AI assistant (React + Python + Ollama + Qwen3)
🌱 **Currently learning:** MLOps (training → CI/CD → deployment), LLM fine-tuning (LoRA), RAG over documents
💬 **Ask me about:** Spring Boot microservices, Kafka, Redis, Resilience4j, local LLMs, RAG

---

## 🛠 Skills
- **Languages**: Java, Python, JavaScript, TypeScript, SQL, C++
- **Backend**: Spring Boot 3, Spring Cloud Gateway, Eureka, OpenFeign, Spring Security (JWT), REST APIs, Camunda BPM
- **Messaging & Resilience**: Apache Kafka, Redis (caching, rate limiting), Resilience4j (retry, circuit breaker)
- **AI / LLM**: Ollama, LLM integration, RAG (Retrieval-Augmented Generation), Prompt Engineering, Custom Models (Modelfiles), Model Quantization & Selection, Hugging Face API
- **ML / MLOps**: Scikit-learn, Pandas, NumPy, FastAPI model serving, Docker
- **Frontend**: React, TypeScript, Vite, Bootstrap, Framer Motion
- **Databases**: PostgreSQL, MySQL, MongoDB, H2
- **Cloud & DevOps**: AWS, Docker / Docker Compose, Jenkins, Maven, Git
- **Methodologies**: Agile, Scrum

---

## 🤖 AI & Machine Learning Projects

- **⚡ [B2: Personal AI Assistant](https://github.com/Mr-AB007/b2-personal-ai)**
  A private, ChatGPT-style chatbot that runs 100% on my own PC. It serves **my own versioned LLM** (`b2:v1` Llama 3.2 → `b2:v2` Qwen3 4B) built from Ollama Modelfiles, with one-command upgrades and rollback. It adds **web search with cited sources (RAG)**, where the model rewrites follow-up questions into search queries, plus streaming answers, personas and an **"Under the hood" panel** that shows the exact prompt, tokens and speed.
  `Python` `React` `Vite` `Bootstrap` `Framer Motion` `Ollama` `Qwen3` `RAG`

  <img src="https://raw.githubusercontent.com/Mr-AB007/b2-personal-ai/main/docs/chat-web-search.png" width="85%" alt="B2 answering with web search and sources"/>

- **🧪 [Applied MLOps](https://github.com/Mr-AB007/applied-mlops)**
  A hands-on, day-by-day path through the MLOps stack: Python fundamentals, NumPy/Pandas data work, ML fundamentals (train/test split, overfitting, evaluation, feature engineering), **serving a trained model with FastAPI**, and **containerising with Docker**. Next up: CI/CD and production deployment.
  `Python` `Pandas` `Scikit-learn` `FastAPI` `Docker`

- **📓 [Journal API with AI enrichment](https://github.com/Mr-AB007/journal-api)**
  A Spring Boot REST API for journal entries with **JWT-secured** user management and MongoDB storage. It calls the **Hugging Face API** to enrich entries with NLP and integrates a weather service.
  `Java 17` `Spring Boot 3` `Spring Security` `MongoDB` `Hugging Face`

- **📊 [Census Income Prediction](https://github.com/Mr-AB007/Census-Income-Prediction)**
  A machine learning model that classifies income levels from demographic census data.
  `Python` `Scikit-learn` `Pandas` `Matplotlib`

---

## 🏗️ Backend & Microservices Projects

- **🏦 [SmartPay Banking Platform](https://github.com/Mr-AB007/smartpay-platform)**
  An enterprise-style, **event-driven banking platform** with account, transaction and notification services behind an API Gateway:
  - **Kafka** for async transaction events
  - **OpenFeign** for synchronous account validation
  - **Redis** caching and distributed rate limiting
  - **Resilience4j** retry, circuit breaker and fallbacks
  - global exception handling and **correlation-ID request tracing**
  `Java 21` `Spring Boot 3` `Kafka` `Redis` `PostgreSQL` `Resilience4j` `Docker Compose`

- **🛒 [TradePay: E-commerce Microservices](https://github.com/Mr-AB007/TradePay)**
  A retail transaction system with independently deployable [Product](https://github.com/Mr-AB007/productservice), [Order](https://github.com/Mr-AB007/orderservice) and [Payment](https://github.com/Mr-AB007/paymentservice) services, a [Eureka service registry](https://github.com/Mr-AB007/service-registry) and an [API Gateway](https://github.com/Mr-AB007/trade-api-gateway). Services talk through Feign clients and are protected by a Resilience4j circuit breaker.
  `Java 17` `Spring Boot` `Spring Cloud Gateway` `Eureka` `Feign` `Resilience4j` `MySQL`

- **💰 [Loan App](https://github.com/Mr-AB007/loan-app)** and **✅ [Task Management API](https://github.com/Mr-AB007/task-management)**
  Spring Boot REST APIs with **JWT authentication** (custom filter and token utility), DTO layers, repositories, global exception handling and API documentation.
  `Java` `Spring Boot` `Spring Security` `JWT`

## 🎨 Frontend Projects
- **📚 [Library App](https://github.com/Mr-AB007/library-app)**: a React + TypeScript library website with book search, pagination, a carousel and a component-based layout. `React` `TypeScript`
- **⚛️ [React Apps](https://github.com/Mr-AB007/react-apps)** and **🎮 [Tic-Tac-Toe](https://github.com/Mr-AB007/tic-tac-game)**: React and JavaScript practice projects. `React` `JavaScript`

## 💼 Professional Work
- **Camunda Workflow Automation**: designed and deployed Camunda BPM workflows to automate complex business processes. `Camunda` `Spring Boot` `PostgreSQL`
- **Kafka-based Real-Time Processing**: high-throughput, asynchronous data processing with Kafka. `Kafka` `Spring Boot` `PostgreSQL`
- **Monolith → Spring Boot Migration**: led the migration of legacy monolithic applications to Spring Boot for better scalability and maintainability. `Java` `Spring Boot` `AWS` `Docker`

## 🧩 Problem Solving
Consistent DSA practice in Java, Python and C++:
[LeetCode DSA Journey](https://github.com/Mr-AB007/leetcode-dsa-journey) ·
[DSA Practice](https://github.com/Mr-AB007/DSA-practice) ·
[DSA in Python](https://github.com/Mr-AB007/DSA-PYTHON) ·
[Data Structures in C++](https://github.com/Mr-AB007/DS-LAB) ·
[Competitive Programming](https://github.com/Mr-AB007/Contest-CP) ·
[100 Days of Code](https://github.com/Mr-AB007/100daysofcode)

## 🎮 Beyond Code
**[MLBB YouTube Channel](https://www.youtube.com/@FuryGuild)**: epic Mobile Legends: Bang Bang moments, including perfect Bruno gameplay and Vexana victories in ranked tournaments.

---

## 🤖 AI Journey

| Step | Status |
|---|---|
| ML fundamentals and model serving with FastAPI + Docker | ✅ Done |
| AI features in Java APIs (Hugging Face) | ✅ Done |
| Run open-source LLMs locally (Ollama) | ✅ Done |
| Full-stack LLM chat app with streaming | ✅ Done |
| RAG: web search with citations | ✅ Done |
| Custom versioned models (Modelfiles) | ✅ Done |
| MLOps: CI/CD and production deployment | 🔄 In progress |
| Fine-tune my own model (LoRA) | 🔄 Learning |
| RAG over documents and AI agents | 📌 Next |

---

## GitHub Insights

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Mr-AB007&theme=github_dark" width="80%" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Mr-AB007&theme=github_dark" width="40%" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Mr-AB007&theme=github_dark&utcOffset=5.5" width="40%" />
</p>

---

## 📈 Top Languages

<p align="center">
  <img src="https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white&labelColor=333333" alt="Java" height="40"/>
  <img src="https://img.shields.io/badge/Python-%2336758C.svg?style=for-the-badge&logo=python&logoColor=white&labelColor=333333" alt="Python" height="40"/>
  <img src="https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black&labelColor=333333" alt="JavaScript" height="40"/>
  <img src="https://img.shields.io/badge/TypeScript-%233178C6.svg?style=for-the-badge&logo=typescript&logoColor=white&labelColor=333333" alt="TypeScript" height="40"/>
  <img src="https://img.shields.io/badge/SQL-%23276DC3.svg?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=333333" alt="SQL" height="40"/>
</p>

---

## 🛠 Technologies & Tools

<p align="center">
  <img src="https://img.shields.io/badge/Java-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white" alt="Java" height="20"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-%236DB33F.svg?style=flat&logo=spring-boot&logoColor=white" alt="Spring Boot" height="20"/>
  <img src="https://img.shields.io/badge/Spring%20Security-%236DB33F.svg?style=flat&logo=spring-security&logoColor=white" alt="Spring Security" height="20"/>
  <img src="https://img.shields.io/badge/Kafka-%23231F20.svg?style=flat&logo=apache-kafka&logoColor=white" alt="Kafka" height="20"/>
  <img src="https://img.shields.io/badge/Redis-%23DC382D.svg?style=flat&logo=redis&logoColor=white" alt="Redis" height="20"/>
  <img src="https://img.shields.io/badge/Camunda-%23007acc.svg?style=flat&logo=camunda&logoColor=white" alt="Camunda" height="20"/>
  <img src="https://img.shields.io/badge/PostgreSQL-%23336791.svg?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL" height="20"/>
  <img src="https://img.shields.io/badge/MySQL-%234479A1.svg?style=flat&logo=mysql&logoColor=white" alt="MySQL" height="20"/>
  <img src="https://img.shields.io/badge/MongoDB-%2347A248.svg?style=flat&logo=mongodb&logoColor=white" alt="MongoDB" height="20"/>
  <img src="https://img.shields.io/badge/AWS-%23232F3E.svg?style=flat&logo=amazon-aws&logoColor=white" alt="AWS" height="20"/>
  <img src="https://img.shields.io/badge/Docker-%232496ED.svg?style=flat&logo=docker&logoColor=white" alt="Docker" height="20"/>
  <img src="https://img.shields.io/badge/Jenkins-%23D24939.svg?style=flat&logo=jenkins&logoColor=white" alt="Jenkins" height="20"/>
  <img src="https://img.shields.io/badge/Git-%23F05033.svg?style=flat&logo=git&logoColor=white" alt="Git" height="20"/>
  <br/>
  <img src="https://img.shields.io/badge/Python-%2336758C.svg?style=flat&logo=python&logoColor=white" alt="Python" height="20"/>
  <img src="https://img.shields.io/badge/FastAPI-%23009688.svg?style=flat&logo=fastapi&logoColor=white" alt="FastAPI" height="20"/>
  <img src="https://img.shields.io/badge/Ollama-%23000000.svg?style=flat&logo=ollama&logoColor=white" alt="Ollama" height="20"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-%23FFD21E.svg?style=flat&logo=huggingface&logoColor=black" alt="Hugging Face" height="20"/>
  <img src="https://img.shields.io/badge/LLM-RAG-%238B5CF6.svg?style=flat" alt="LLM RAG" height="20"/>
  <img src="https://img.shields.io/badge/Scikit%20Learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white" alt="Scikit-learn" height="20"/>
  <img src="https://img.shields.io/badge/Pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white" alt="Pandas" height="20"/>
  <img src="https://img.shields.io/badge/Jupyter-%23F37626.svg?style=flat&logo=jupyter&logoColor=white" alt="Jupyter" height="20"/>
  <br/>
  <img src="https://img.shields.io/badge/React-%2361DAFB.svg?style=flat&logo=react&logoColor=black" alt="React" height="20"/>
  <img src="https://img.shields.io/badge/TypeScript-%233178C6.svg?style=flat&logo=typescript&logoColor=white" alt="TypeScript" height="20"/>
  <img src="https://img.shields.io/badge/Vite-%23646CFF.svg?style=flat&logo=vite&logoColor=white" alt="Vite" height="20"/>
  <img src="https://img.shields.io/badge/Bootstrap-%237952B3.svg?style=flat&logo=bootstrap&logoColor=white" alt="Bootstrap" height="20"/>
</p>

---

## 🤝 Connect with Me
<p align="center">
  <a href="https://www.linkedin.com/in/anubhav-ranjan007/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" height="30"/>
  </a>
  <a href="https://www.youtube.com/@FuryGuild" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" height="30"/>
  </a>
  <a href="mailto:anubhav7.ranjan@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-%23EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" height="30"/>
  </a>
</p>
