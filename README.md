# 🧩 RevStack Challenge Catalog (Part 1)

> This document serves as the master list of engineering challenges available in **RevStack**.
>
> Each challenge is designed like a project-level LeetCode problem. The goal is to solve the engineering problem using clean architecture, best practices, and production-inspired design.
>
> Every repository expands on these with its own detailed `PROBLEM.md`, requirements, constraints, bonus tasks, and interview notes.

---

# 🖥 Backend — Spring Boot

|     ID     | Challenge                 | Difficulty | Problem Statement                                                                                                                                                                                                                                                                                                                | Technology Stack                                                 |
| :--------: | ------------------------- | :--------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| **SB-001** | **TaskFlow API**          |     🟢     | Design and implement a RESTful task management platform where authenticated users can create workspaces, manage projects, assign tasks to team members, update task progress, and search tasks efficiently using filtering, pagination, and sorting. The application should follow layered architecture and REST best practices. | Spring Boot • Spring Data JPA • MySQL • Docker • Swagger • JUnit |
| **SB-002** | **Authentication Server** |     🟡     | Build a centralized authentication and authorization service capable of registering users, issuing JWT access and refresh tokens, supporting role-based access control, secure password hashing, session management, and token revocation. The service should be reusable by multiple applications.                              | Spring Boot • Spring Security • JWT • MongoDB • Redis • Docker   |
| **SB-003** | **Inventory Service**     |     🟡     | Design an event-driven inventory management system capable of tracking product stock across multiple warehouses. Inventory updates should be synchronized asynchronously using events while ensuring consistency, caching frequently accessed products, and maintaining transaction safety.                                      | Spring Boot • Kafka • Redis • MySQL • Docker Compose             |
| **SB-004** | **File Storage Service**  |     🔴     | Build a scalable file storage API capable of uploading, downloading, deleting, and managing metadata for documents and images. Large files should be processed asynchronously, and the application should support object storage integration with proper security and access control.                                            | Spring Boot • PostgreSQL • MinIO (or S3) • Docker • Spring Async |

---

# 🟩 Backend — NestJS

|     ID     | Challenge                 | Difficulty | Problem Statement                                                                                                                                                                                                                                        | Technology Stack                             |
| :--------: | ------------------------- | :--------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- |
| **NS-001** | **Blogging Platform API** |     🟢     | Build the backend of a blogging platform where users can publish articles, organize them into categories, comment on posts, and manage profiles. The API should provide authentication, authorization, validation, and efficient database relationships. | NestJS • Prisma • PostgreSQL • Docker        |
| **NS-002** | **URL Shortener**         |     🟢     | Develop a URL shortening service that converts long URLs into short links while tracking analytics such as click count, expiration dates, and visit history. Frequently accessed URLs should be cached to improve performance.                           | NestJS • MongoDB • Redis • Docker            |
| **NS-003** | **Notification Service**  |     🟡     | Design an event-driven notification microservice capable of consuming events from Kafka and delivering email or in-app notifications asynchronously. Failed notifications should be retried using a queue with proper error handling.                    | NestJS • Kafka • BullMQ • Redis • PostgreSQL |
| **NS-004** | **Realtime Chat Backend** |     🔴     | Build a scalable WebSocket-based chat server supporting multiple chat rooms, user authentication, online presence, typing indicators, and horizontal scaling using Redis adapters.                                                                       | NestJS • Socket.IO • Redis • JWT • Docker    |

---

# ⚡ Backend — FastAPI

|     ID     | Challenge             | Difficulty | Problem Statement                                                                                                                                                                                                                   | Technology Stack                                     |
| :--------: | --------------------- | :--------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| **FA-001** | **Notes API**         |     🟢     | Design a lightweight note management API that allows authenticated users to create, organize, search, archive, and manage personal notes. The application should expose asynchronous REST endpoints and support efficient querying. | FastAPI • SQLAlchemy • Alembic • PostgreSQL • Docker |
| **FA-002** | **Resume Analyzer**   |     🟡     | Create an API capable of accepting resume PDFs, extracting text, identifying technical skills, education, and work experience, then returning structured information suitable for further analysis or ranking.                      | FastAPI • PyMuPDF • spaCy • Docker                   |
| **FA-003** | **ML Prediction API** |     🟡     | Expose trained machine learning models through REST endpoints. Users should be able to submit single or batch prediction requests, upload datasets, and receive prediction results along with confidence scores.                    | FastAPI • Scikit-learn • Pandas • Pydantic • Docker  |
| **FA-004** | **RAG Assistant API** |     🔴     | Implement a Retrieval-Augmented Generation (RAG) service capable of ingesting documents, generating embeddings, storing them in a vector database, retrieving relevant context, and producing accurate responses using a local LLM. | FastAPI • LangChain • ChromaDB • Ollama • Docker     |

---

# ⚛ Frontend — React

|     ID     | Challenge           | Difficulty | Problem Statement                                                                                                                                                                                                                                     | Technology Stack                                                         |
| :--------: | ------------------- | :--------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| **RE-001** | **Admin Dashboard** |     🟢     | Develop a responsive administrative dashboard that consumes backend APIs to manage users, products, analytics, and reports. The application should include authentication, protected routes, charts, responsive layouts, and reusable UI components.  | React • TypeScript • Vite • Tailwind CSS • React Router • TanStack Query |
| **RE-002** | **Kanban Board**    |     🟡     | Build a Trello-like Kanban application where users can create boards, manage columns, drag tasks between stages, assign labels, and persist state efficiently. The interface should support smooth drag-and-drop interactions and responsive layouts. | React • Zustand • DnD Kit • Tailwind CSS                                 |
| **RE-003** | **GitHub Explorer** |     🟢     | Create an application that allows users to search GitHub profiles and repositories, display repository statistics, support infinite scrolling, and provide detailed information about contributors and projects using the GitHub API.                 | React • GitHub REST API • TanStack Query • Tailwind CSS                  |
| **RE-004** | **Expense Tracker** |     🟢     | Design a personal finance dashboard where users can record income and expenses, categorize transactions, visualize monthly spending, and generate summary reports using interactive charts and dashboards.                                            | React • Chart.js • React Hook Form • Tailwind CSS                        |

---

# 📌 Topics Covered in Part 1

### Spring Boot

* REST APIs
* Spring Security
* JWT
* Spring Data JPA
* Validation
* DTO Pattern
* Transactions
* Swagger
* Docker
* Kafka
* Redis

---

### NestJS

* Modules
* Guards
* Validation
* Prisma ORM
* WebSockets
* BullMQ
* Kafka
* Redis

---

### FastAPI

* Async Programming
* SQLAlchemy
* Alembic
* File Uploads
* Machine Learning APIs
* LangChain
* ChromaDB
* Ollama
* Retrieval-Augmented Generation (RAG)

---

### React

* TypeScript
* Vite
* Tailwind CSS
* State Management
* React Router
* TanStack Query
* Drag-and-Drop
* Charts
* Forms
* API Integration

---

# 🧩 RevStack Challenge Catalog (Part 2)

> Continue building production-inspired projects to revise mobile development, frontend design, deep learning, and classical machine learning. Each repository should contain its own detailed `PROBLEM.md` describing functional requirements, technical constraints, and bonus objectives.

---

# 📱 Mobile — Expo (React Native)

|     ID     | Challenge                | Difficulty | Problem Statement                                                                                                                                                                                                                                                   | Technology Stack                                                            |
| :--------: | ------------------------ | :--------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| **EX-001** | **Habit Tracker**        |     🟢     | Build a habit-tracking application that allows users to create daily habits, track streaks, receive reminder notifications, and visualize progress over time. The application should work offline and synchronize data when connectivity becomes available.         | Expo • Expo Router • React Native • SQLite • Expo Notifications             |
| **EX-002** | **QR Attendance System** |     🟡     | Design a QR-code-based attendance application where instructors generate attendance sessions and students scan QR codes to mark their attendance. The application should prevent duplicate entries and synchronize attendance records with a backend API.           | Expo • React Native • Expo Camera • QR Scanner • FastAPI/Spring Boot        |
| **EX-003** | **Fitness Tracker**      |     🟡     | Develop a mobile fitness application capable of tracking walking distance, step count, calories burned, and route history using device sensors and GPS. Users should be able to review previous workouts and visualize progress.                                    | Expo • React Native • Expo Location • Maps • SQLite • Expo Sensors          |
| **EX-004** | **Realtime Chat App**    |     🔴     | Build a secure realtime messaging application supporting one-to-one chats, group conversations, push notifications, online presence, typing indicators, and media sharing. The application should continue functioning smoothly with unstable network connectivity. | Expo • React Native • Socket.IO • Firebase Cloud Messaging • FastAPI/NestJS |

---

# 🎨 Frontend — Tailwind CSS

|     ID     | Challenge               | Difficulty | Problem Statement                                                                                                                                                                                                                                                | Technology Stack                                    |
| :--------: | ----------------------- | :--------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| **TW-001** | **SaaS Landing Page**   |     🟢     | Recreate a modern SaaS company landing page featuring responsive layouts, pricing sections, testimonials, animations, call-to-action components, and accessibility best practices. Focus on pixel-perfect implementation and responsive behavior across devices. | Tailwind CSS • React • Vite • Framer Motion         |
| **TW-002** | **Analytics Dashboard** |     🟢     | Design and build a responsive analytics dashboard displaying KPIs, interactive charts, tables, notifications, and activity feeds. The interface should adapt gracefully to desktop, tablet, and mobile layouts.                                                  | Tailwind CSS • React • Recharts • TypeScript        |
| **TW-003** | **Developer Portfolio** |     🟢     | Create a modern developer portfolio showcasing projects, skills, experience, blogs, and contact information. The website should support dark mode, animations, responsive layouts, SEO optimization, and accessibility standards.                                | Tailwind CSS • React • Framer Motion • React Router |

---

# 🤖 Artificial Intelligence — TensorFlow

|     ID     | Challenge                        | Difficulty | Problem Statement                                                                                                                                                                                                                                   | Technology Stack                               |
| :--------: | -------------------------------- | :--------: | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| **TF-001** | **Handwritten Digit Classifier** |     🟢     | Train and deploy a Convolutional Neural Network capable of recognizing handwritten digits. Evaluate model performance using standard classification metrics and visualize predictions on unseen images.                                             | TensorFlow • Keras • NumPy • Matplotlib        |
| **TF-002** | **Plant Disease Detection**      |     🟡     | Build an image classification model capable of identifying diseases in plant leaves using transfer learning. The application should preprocess images, train the model, evaluate performance, and expose predictions through an inference pipeline. | TensorFlow • Keras • EfficientNet • OpenCV     |
| **TF-003** | **Sentiment Analysis**           |     🟡     | Develop a Natural Language Processing model capable of classifying customer reviews or social media posts as positive, negative, or neutral. The solution should include preprocessing, tokenization, model training, and evaluation.               | TensorFlow • TextVectorization • LSTM • Pandas |
| **TF-004** | **Object Detection System**      |     🔴     | Build an object detection pipeline capable of identifying multiple objects in uploaded images or live video streams. The system should visualize detected objects with confidence scores and bounding boxes.                                        | TensorFlow • YOLO • OpenCV • NumPy             |

---

# 📊 Machine Learning — Scikit-learn

|     ID     | Challenge                     | Difficulty | Problem Statement                                                                                                                                                                                                                   | Technology Stack                                        |
| :--------: | ----------------------------- | :--------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| **SK-001** | **House Price Prediction**    |     🟢     | Build a regression model capable of predicting house prices based on historical property data. The project should include feature engineering, preprocessing, model evaluation, and comparison of multiple regression algorithms.   | Scikit-learn • Pandas • NumPy • XGBoost • Matplotlib    |
| **SK-002** | **Customer Churn Prediction** |     🟡     | Design a classification model that predicts whether a customer is likely to leave a subscription-based service. Perform exploratory data analysis, feature selection, model training, evaluation, and interpretation of results.    | Scikit-learn • Pandas • Imbalanced-learn • SHAP         |
| **SK-003** | **Fraud Detection System**    |     🔴     | Develop an anomaly detection system capable of identifying fraudulent financial transactions using highly imbalanced datasets. Compare supervised and unsupervised approaches while minimizing false positives and false negatives. | Scikit-learn • Isolation Forest • SMOTE • SHAP • Pandas |
| **SK-004** | **Recommendation Engine**     |     🟡     | Build a recommendation system that suggests similar products or movies based on user preferences and item similarity. Compare content-based and collaborative filtering approaches where appropriate.                               | Scikit-learn • KNN • Cosine Similarity • Pandas • NumPy |

---

# 📌 Topics Covered in Part 2

## Expo

* React Native
* Expo Router
* Navigation
* SQLite
* Offline Storage
* Push Notifications
* Camera APIs
* QR Code Scanner
* Maps
* Location Services
* Device Sensors
* Authentication
* API Integration
* Realtime Communication

---

## Tailwind CSS

* Utility-First CSS
* Responsive Design
* Flexbox
* Grid
* Dark Mode
* Accessibility
* Framer Motion
* Component Design
* Dashboard Layouts
* Modern UI Patterns

---

## TensorFlow

* Deep Learning
* CNNs
* Transfer Learning
* Computer Vision
* NLP
* LSTM
* Image Classification
* Object Detection
* Model Evaluation
* Model Deployment

---

## Scikit-learn

* Data Cleaning
* Feature Engineering
* Regression
* Classification
* Clustering
* Recommendation Systems
* Anomaly Detection
* Hyperparameter Tuning
* Cross Validation
* Model Explainability (SHAP)

---

# 🧩 RevStack Challenge Catalog (Part 3)

> This section focuses on modern AI engineering, backend systems, blockchain development, and DevOps. These projects combine multiple technologies to simulate production-grade software engineering challenges.

---

# 🤖 AI Engineering — LangChain, LangGraph & LLM Applications

|     ID     | Challenge                   | Difficulty | Problem Statement                                                                                                                                                                                                                                         | Technology Stack                                     |
| :--------: | --------------------------- | :--------: | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| **AI-001** | **PDF Chatbot**             |     🟢     | Build an intelligent chatbot capable of answering questions from uploaded PDF documents. The application should extract text, generate embeddings, retrieve relevant context, and answer questions accurately using Retrieval-Augmented Generation (RAG). | FastAPI • LangChain • ChromaDB • Ollama • Docker     |
| **AI-002** | **Resume AI Assistant**     |     🟢     | Develop an AI assistant that analyzes resumes, identifies strengths and weaknesses, suggests improvements, and generates interview questions based on the candidate's profile using large language models.                                                | FastAPI • LangChain • Ollama/OpenAI • Redis • Docker |
| **AI-003** | **Customer Support Agent**  |     🟡     | Build an AI-powered customer support assistant capable of answering FAQs, retrieving company knowledge, maintaining conversation history, and calling external tools when required.                                                                       | FastAPI • LangGraph • Redis • PostgreSQL • Docker    |
| **AI-004** | **Research Assistant**      |     🔴     | Design a multi-agent research assistant capable of planning research tasks, searching the web, summarizing information, verifying sources, and generating structured reports with citations.                                                              | LangGraph • Tavily • ChromaDB • Ollama • FastAPI     |
| **AI-005** | **Coding Assistant**        |     🔴     | Develop an AI coding assistant capable of understanding Git repositories, searching codebases, explaining source code, generating implementations, and assisting with debugging using autonomous agents.                                                  | LangGraph • MCP • GitHub API • Ollama • FastAPI      |
| **AI-006** | **Meeting Notes Assistant** |     🟡     | Create an assistant that converts meeting audio into structured notes, extracts action items, summarizes discussions, and stores searchable meeting knowledge for future retrieval.                                                                       | LangChain • Whisper • ChromaDB • FastAPI             |
| **AI-007** | **SQL Agent**               |     🟡     | Build an intelligent SQL assistant capable of converting natural language questions into SQL queries, executing them securely, explaining results, and preventing unsafe database operations.                                                             | LangChain • SQLAlchemy • PostgreSQL • FastAPI        |
| **AI-008** | **Web Search Agent**        |     🟡     | Implement an AI agent capable of searching the web, retrieving reliable sources, summarizing findings, and generating citations while maintaining conversational context.                                                                                 | LangChain • Tavily • FastAPI • Redis                 |
| **AI-009** | **Autonomous Planner**      |     🔴     | Build a planning agent capable of breaking complex objectives into smaller tasks, prioritizing execution, delegating work to specialized agents, and tracking overall progress autonomously.                                                              | LangGraph • Redis • Docker • FastAPI                 |
| **AI-010** | **Personal Knowledge Base** |     🔴     | Create a personal AI knowledge system capable of ingesting documents, notes, web pages, and code snippets while supporting semantic search, long-term memory, and contextual conversations.                                                               | LangChain • ChromaDB • Ollama • FastAPI • Docker     |

---

# ⚡ Backend — V Language (VWeb)

|     ID     | Challenge         | Difficulty | Problem Statement                                                                                                                                                                        | Technology Stack                        |
| :--------: | ----------------- | :--------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------- |
| **VW-001** | **Todo API**      |     🟢     | Develop a lightweight REST API that allows users to manage personal tasks, including creating, updating, deleting, and searching todos while emphasizing performance and simplicity.     | V Language • VWeb • SQLite              |
| **VW-002** | **URL Shortener** |     🟢     | Implement a high-performance URL shortening service capable of generating short URLs, redirecting users efficiently, tracking analytics, and caching frequently accessed links.          | V Language • VWeb • Redis • SQLite      |
| **VW-003** | **Blog Server**   |     🟡     | Build a server-side rendered blogging platform supporting authentication, article publishing, comments, categories, and session management while maintaining a lightweight architecture. | V Language • VWeb • PostgreSQL • Docker |
| **VW-004** | **File Server**   |     🟡     | Design a secure file hosting service capable of handling uploads, downloads, metadata management, access control, and efficient storage of user files.                                   | V Language • VWeb • Docker • SQLite     |

---

# ⛓ Blockchain — Solidity

|     ID     | Challenge                 | Difficulty | Problem Statement                                                                                                                                                                            | Technology Stack                              |
| :--------: | ------------------------- | :--------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------- |
| **SO-001** | **Voting Smart Contract** |     🟢     | Build a decentralized voting application that allows eligible users to vote securely while preventing duplicate votes and ensuring transparency through blockchain technology.               | Solidity • Hardhat • Ethers.js                |
| **SO-002** | **Crowdfunding DApp**     |     🟡     | Create a decentralized crowdfunding platform where users can launch fundraising campaigns, contribute securely, and automatically release funds only when campaign conditions are satisfied. | Solidity • Hardhat • React • Ethers.js        |
| **SO-003** | **NFT Marketplace**       |     🟡     | Develop a decentralized NFT platform where users can mint, buy, sell, and transfer ERC-721 tokens while storing metadata using decentralized storage solutions.                              | Solidity • Hardhat • ERC-721 • IPFS • React   |
| **SO-004** | **MultiSig Wallet**       |     🔴     | Implement a secure multi-signature cryptocurrency wallet requiring multiple owners to approve transactions before funds are transferred, ensuring enhanced security for shared assets.       | Solidity • Hardhat • OpenZeppelin • Ethers.js |

---

# 🐳 DevOps — Docker & Microservices

|     ID     | Challenge                       | Difficulty | Problem Statement                                                                                                                                                                                                                             | Technology Stack                                                                     |
| :--------: | ------------------------------- | :--------: | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| **DK-001** | **Three-Tier Application**      |     🟢     | Containerize a complete three-tier application consisting of a frontend, backend, and relational database while enabling communication through Docker Compose and environment configuration.                                                  | Docker • Docker Compose • React • Spring Boot • MySQL                                |
| **DK-002** | **Event-Driven Stack**          |     🟡     | Deploy a distributed event-driven system using Kafka, Redis, MongoDB, and multiple producer-consumer services while ensuring reliable communication and fault tolerance.                                                                      | Docker • Kafka • Redis • MongoDB • Docker Compose                                    |
| **DK-003** | **Machine Learning Deployment** |     🟡     | Package and deploy a machine learning inference service capable of serving TensorFlow or Scikit-learn models behind a REST API with reverse proxy support and production-ready configuration.                                                 | Docker • FastAPI • TensorFlow • Nginx • Docker Compose                               |
| **DK-004** | **Microservices Platform**      |     🔴     | Design and deploy a production-inspired microservices ecosystem consisting of API Gateway, Authentication Service, Product Service, Notification Service, Redis, Kafka, MongoDB, PostgreSQL, and centralized networking using Docker Compose. | Docker • Spring Boot • Kafka • Redis • MongoDB • PostgreSQL • Nginx • Docker Compose |

---

# 📌 Topics Covered in Part 3

## LangChain & AI Engineering

* Prompt Engineering
* LangChain
* LangGraph
* Retrieval-Augmented Generation (RAG)
* AI Agents
* Multi-Agent Systems
* Tool Calling
* Function Calling
* Agent Memory
* Planning Agents
* SQL Agents
* Code Assistants
* Web Search Agents
* Document Processing
* Vector Databases
* Embeddings
* Semantic Search
* Model Context Protocol (MCP)
* Ollama
* OpenAI-Compatible APIs
* Whisper
* ChromaDB

---

## V Language (VWeb)

* REST APIs
* Routing
* Server-Side Rendering
* SQLite
* PostgreSQL
* Sessions
* Authentication
* File Uploads
* Redis
* Docker

---

## Solidity

* Smart Contracts
* ERC-20
* ERC-721
* Hardhat
* Ethers.js
* OpenZeppelin
* IPFS
* Web3 Integration
* Contract Testing
* Wallet Security

---

## Docker & DevOps

* Docker
* Docker Compose
* Multi-stage Builds
* Environment Variables
* Container Networking
* Reverse Proxy (Nginx)
* Microservices
* Kafka
* Redis
* MongoDB
* PostgreSQL
* Health Checks
* Volumes
* Service Discovery

---

# 🎯 Final Objective

RevStack is designed to help you revise an entire modern software engineering stack through practical engineering challenges.

By completing every challenge, you'll gain hands-on experience with:

* **Backend Development**
* **Frontend Development**
* **Mobile Development**
* **Machine Learning**
* **Deep Learning**
* **LLM Applications**
* **AI Agents & RAG**
* **Blockchain Development**
* **Distributed Systems**
* **Microservices**
* **Cloud-Native Development**
* **DevOps & Containerization**

Every project emphasizes clean architecture, production-inspired design, testing, documentation, and maintainability—skills that are highly valued in software engineering interviews.

---

> **RevStack Philosophy:**
> *Learn → Build → Break → Debug → Rebuild → Master.*

**The goal isn't to complete the challenges once—it's to become capable of rebuilding them from memory with confidence.**
