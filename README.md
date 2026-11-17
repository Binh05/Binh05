<h1 align="center">Hi, I'm Thanh Binh Nguyen 👋</h1>

<p align="center">
  <strong>Backend-focused Software Engineer</strong><br/>
  Interested in software architecture, domain-driven design, distributed systems, and building reliable products.
</p>

<p align="center">
  <a href="https://fabricio.id.vn">FabricIO</a> ·
  <a href="https://www.linkedin.com/in/thanh-binh-nguyen-831166319/">LinkedIn</a> ·
  <a href="https://doi.org/10.9734/ajrcos/2025/v18i5650">Research Publication</a>
</p>

---

## About Me

I'm a Computer Science / Information Technology student at Ho Chi Minh City University of Education (HCMUE), based in Ho Chi Minh City, Vietnam.

I focus on backend engineering and enjoy working beyond the implementation of individual features: understanding business requirements, defining clear domain boundaries, making architecture trade-offs, optimizing database access, and deploying applications.

My main backend stack is **Java and Spring Boot**. I also have practical experience building backend services with **Python and FastAPI**, and developing full-stack applications when needed.

- 🔭 Currently building and improving **FabricIO**, a browser-based WebGL game platform.
- 💼 Backend Software Engineering Intern experience at **ETECHS**.
- 🧠 Interested in **DDD, modular monoliths, distributed systems, database performance, and system design**.
- 🎯 Open to **Backend Developer / Software Engineer Intern and Fresher opportunities**.
- 📍 Ho Chi Minh City, Vietnam.

## Tech Stack

### Backend

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white" alt="Express.js"/>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white" alt=".NET"/>
  <img src="https://img.shields.io/badge/REST_API-005571?style=flat" alt="REST API"/>
</p>

### Frontend

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/Redux-764ABC?style=flat&logo=redux&logoColor=white" alt="Redux"/>
</p>

### Databases & Infrastructure

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white" alt="SQL Server"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white" alt="Cloudflare"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" alt="Linux"/>
</p>

### Engineering Concepts

- Object-Oriented Programming, SOLID principles, and design patterns
- Domain-Driven Design (DDD) and Hexagonal Architecture
- Modular Monolith and Microservices
- REST API design, JWT authentication, and role-based authorization
- SQL query optimization, indexing, and database transactions
- Event-driven communication with Kafka
- Unit testing, benchmarking, Docker, and CI/CD

## Featured Projects

### 1. [FabricIO — WebGL Game Platform](https://fabricio.id.vn)

A web platform where users can discover, play, and share WebGL games directly in their browsers without installing a desktop application.

**Tech:** Java 21, Spring Boot, Spring Modulith, PostgreSQL, React, TypeScript, Docker, Render, Cloudflare Pages, Cloudflare R2.

**Engineering highlights**

- Reworked the backend into a **Modular Monolith** using Spring Modulith, with feature modules organized around DDD-lite boundaries (`web`, `application`, and `domain`).
- Designed backend modules for authentication, games, users, and uploads, with DTOs and mappers separating API contracts from persistence entities.
- Implemented JWT-based authentication with short-lived access tokens and refresh-session handling, alongside role/permission-based authorization.
- Built direct-to-object-storage game uploads using **presigned URLs**, allowing the frontend to upload files to Cloudflare R2.
- Supported game packages and associated assets such as thumbnails and videos.
- Investigated and fixed an **N+1 query** issue in game listing, using a two-phase query approach to avoid collection-fetch pagination problems.
- Used **k6** to benchmark API behavior and compare query/performance changes.
- Deployed the application using Docker, Render, Cloudflare Pages, Cloudflare R2, and Neon PostgreSQL.

**Live:** [fabricio.id.vn](https://fabricio.id.vn)

### 2. bmessage — Real-time Messaging App

A web messaging application supporting one-to-one conversations and group chats with real-time message delivery.

**Tech:** Next.js, TypeScript, Node.js, Express.js, Socket.IO, MongoDB, Redux Toolkit, JWT.

**Highlights**

- Built real-time messaging features using Socket.IO.
- Implemented backend APIs with Node.js and Express.
- Used MongoDB for message and conversation data.
- Applied JWT-based authentication and Redux Toolkit for client-side state management.

### 3. Food Nutritional Estimation Using Deep Learning

**Research topic:** *Estimating Nutritional Composition from Food Volume via Deep Learning-Based Depth and Segmentation Models.*

A research project exploring how image segmentation and depth-estimation models can be used to estimate food volume and derive nutritional composition.

**Highlights**

- Explored segmentation and depth-estimation approaches for food image analysis.
- Worked on estimating food volume as an intermediate step toward nutritional estimation.
- Received **Third Prize** in a Ministry-level student research competition.
- Research publication: [DOI: 10.9734/ajrcos/2025/v18i5650](https://doi.org/10.9734/ajrcos/2025/v18i5650).

### 4. AI-assisted Grocery Store Management

An ongoing idea for applying AI to practical sales and operations workflows in a family grocery store. The concept is being explored for MoMo Tech Contest 2026.

*Project status: In development / problem exploration.*

## Experience

### Backend Software Engineering Intern — ETECHS

**July 2026 – September 2026**

- Contributed to backend services for an education technology platform using Python and FastAPI.
- Worked with PostgreSQL and a multi-database environment for teacher-related domains.
- Applied DDD and Hexagonal Architecture concepts to organize domain logic and infrastructure concerns.
- Worked on REST APIs, domain events, and service-to-service communication using Kafka.
- Explored transactional patterns including Unit of Work and Outbox in event-driven workflows.

### Coding & Robotics Teaching Assistant — MindX Technology School

**October 2026 – Present**

- Support programming and robotics learning activities.
- Guide students through programming fundamentals, computational thinking, and project-based exercises.
- Work with educational tools and environments such as Scratch and GameMaker.

### Secondary Mathematics Instructor — CEDT

**June 2025 – December 2025**

- Taught mathematics to lower-secondary students.
- Practiced explaining complex ideas in a structured and accessible way.
- Developed communication, patience, and problem-solving skills through teaching.

## Awards & Activities

- **Third Prize — Ministry-level Student Research Competition:** Deep-learning-based food volume and nutritional estimation.
- **Team Leader — Team Lambda, CodeRace 2025:** Bosch-organized programming competition.
- **ICPC Vietnam — 2024–2025:** Participated in university-level competitive programming.
- **Green Summer Volunteer Campaign — 2025 and 2026:** Participated in digital transformation and community activities.
- Attended technology events and meetups, including One Day Boschler, AIOps & MLOps Meetup, and MoMo TechDay.

## Currently Learning

- Advanced Java and Spring Boot
- Data structures and algorithms
- SQL and database performance
- System design and distributed systems
- Domain-Driven Design and architectural trade-offs
- Technical English and VSTEP preparation

## GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Binh05&show_icons=true&hide_border=true&rank_icon=github" alt="GitHub statistics"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Binh05&layout=compact&hide_border=true" alt="Top languages"/>
</p>

---

<p align="center">
  <i>Building software with intention — from understanding the problem to making the system work reliably.</i>
</p>