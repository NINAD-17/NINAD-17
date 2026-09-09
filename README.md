<h1 align="center">Hi, I'm Ninad 👋</h1>

<h3 align="center">Software Engineer | Full-Stack & GenAI</h3>

<br>

I build full-stack web applications and AI-powered systems, but what keeps me interested is understanding how they actually work underneath.

I started with full-stack development — learning how frontend applications, APIs, databases, authentication, and backend services fit together. Over time, that naturally led me into GenAI, where I've been exploring RAG, multi-agent systems, asynchronous workflows, and the engineering challenges of building useful applications around LLMs.

I enjoy taking a complex problem, breaking it into smaller systems, and figuring out how those pieces should work together. These days, that means working mainly with TypeScript and Python, building web applications and APIs, and experimenting with AI systems along the way.

---

## Things I've Built

### [Resumarq](https://github.com/NINAD-17/Resumarq)
**AI-powered Resume & Job Description Analyzer**

An AI-powered application that analyzes resumes against target job descriptions and produces a structured evaluation of ATS compatibility, content quality, and alignment.

**Engineering highlights:**
- **Asynchronous distributed architecture** using Redis queues and dedicated Python workers to keep heavy AI processing outside the web request lifecycle.
- **Multi-agent analysis pipeline** built with LangGraph, covering resume/JD analysis, ATS evaluation, quantifiable impact, company research, and structured reporting.
- **Independent workload scaling** by decoupling the Next.js application from AI workers, allowing workers to scale horizontally across AWS EC2 instances.
- **Cloud & deployment infrastructure** using AWS S3, AWS EC2, Docker, and GitHub Actions for CI/CD, with LangSmith for LLM observability.

**Stack:** Next.js · FastAPI · Python · Redis · LangGraph · MongoDB · AWS · Docker · GitHub Actions

---

### [PolicyGuard](https://github.com/NINAD-17/Policy-Guard)
**AI-powered SOP Compliance Prototype**

A prototype exploring how employees can use AI to understand organizational SOPs, search policies in natural language, and verify their work for compliance.

**Engineering highlights:**
- **RAG pipeline with 5 specialized AI agents** for routing, retrieval, explanation, compliance auditing, and hierarchical escalation.
- **Multi-query retrieval** that decomposes complex questions and combines vector search results using Reciprocal Rank Fusion (RRF).
- **Document-grounded responses** with page-level citations and structured compliance results for submitted work or PR descriptions.
- **Durable event-driven processing** using Inngest and Inngest AgentKit for long-running workflows, retries, batching, concurrency control, and asynchronous audits.

**Stack:** Next.js · TypeScript · Inngest AgentKit · Inngest · LangChain · RAG · MongoDB Atlas Vector Search · Gemini

---

### [SSPM Community](https://github.com/NINAD-17/SSPM-Community)
**Full-Stack Student & Alumni Community Platform**

A full-stack social platform built for students and alumni of SSPM, providing a shared space for opportunities, discussions, learning, and community interaction.

**Engineering highlights:**
- **18+ REST APIs** built with Express.js, including routes and controllers for core application workflows.
- **JWT access & refresh token authentication** with protected application routes and OTP-based authentication.
- **MongoDB schema/model design** for the application's data layer.
- **Redux Toolkit state management** with 10 Redux slices, alongside reusable layouts, forms, and UI components.
- **Cursor-based pagination and infinite scrolling** for content-heavy application views.

**Stack:** React · JavaScript · Redux Toolkit · Node.js · Express.js · MongoDB · JWT · Tailwind CSS

---

## What I'm Working With

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,express,python,fastapi,mongodb,mysql,redis,aws,docker,githubactions,git,github,postman&perline=17&size=10" />
  </a>
</p>

<p align="center">
  <strong>AI / GenAI:</strong> RAG · LangGraph · LangChain · Inngest AgentKit · LLMs · Agentic AI
</p>

---

## What I Like Exploring

Software architecture · Backend systems · AI application engineering · RAG · Multi-agent systems · Distributed processing · Cloud infrastructure

I'm also strengthening my foundations in data structures, algorithms, and core computer science while continuing to go deeper into modern web and AI systems.

---

<table border="0">
  <tr>
    <td rowspan="2" width="45%">
      <img width="100%" height="100%" src="https://github.com/NINAD-17/NINAD-17/assets/94175390/36b73704-0188-4502-b228-122d68112b4b" />
    </td>
    <td>
      <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=NINAD-17&theme=github_dark" />
    </td>
  </tr>
  <tr>
    <td>
      <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=NINAD-17&theme=github_dark" />
    </td>
  </tr>
</table>

---

<h3 align="center">Building software. Understanding the systems behind it.</h3>
