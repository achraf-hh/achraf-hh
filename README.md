<img src="./assets/profile-banner.png" alt="Abstract data pipelines flowing through an intelligent system" width="100%" />

<h1 align="center">Hi, I'm Achraf.</h1>

<p align="center">
  <strong>Computer science engineering student building LLM systems, and the evaluation that tells you whether they work.</strong>
</p>

<p align="center">
  LLM pipelines · Evaluation · Retrieval · Backend engineering
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/achraf-badreddine/">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="mailto:badreddineachraf03@gmail.com">Email</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/achraf-hh?tab=repositories">Projects</a>
</p>

<br>

## About

I'm in the final year of a double-degree engineering program in computer science at
**École des Mines de Saint-Étienne** and **INPT Rabat**. Most of what I build sits where
LLMs, retrieval, and backend engineering meet, and I care as much about measuring a system
as about building it.

- At **Hellebore Technologies**, I ran a feasibility study on extracting the 22 fields of credit-derivatives trades from bank emails with a local LLM, fully on-premise: **97.3% precision, 98.3% recall** on a ground-truth set
- Built the evaluation harness that steered an AI coding agent writing a model-free email splitter, and it caught the first version overfitting (**100%** on seen senders, **55.4%** on a held-out one)
- Compared 3 local and 5 hosted models: the choice of model mattered about **10× less** than the pipeline around it
- Shipped an internal AI agent serving **500+ requests/day**

I'm looking for a **6-month end-of-studies internship from March 2027**, in AI or software engineering.

## Flagship project

<table>
  <tr>
    <td valign="top">
      <h3><a href="https://github.com/achraf-hh/notestream">NoteStream ↗</a></h3>
      <p><strong>A self-hosted, multi-tier document Q&amp;A backend.</strong></p>
      <p>
        NoteStream turns document collections into a searchable knowledge base.
        Its Java API layer orchestrates a Python processing service and PostgreSQL
        with pgvector through a complete <code>ingest → embed → retrieve</code>
        pipeline across <strong>5,000+ document chunks</strong>.
      </p>
      <p>
        <code>Java</code>
        <code>Spring Boot</code>
        <code>Python</code>
        <code>FastAPI</code>
        <code>PostgreSQL</code>
        <code>pgvector</code>
      </p>
    </td>
  </tr>
</table>

## More work

### BioGas Scout AI

Led the architecture and deployment of a sector-intelligence
platform with retrieval across **10,000+ pages** of European biogas documents.
Self-hosted the live service on Linux with secure tunneling.

`RAGFlow` `Docker` `Linux` `Python`

## Experience at a glance

- **Hellebore Technologies, AI Engineering Intern (2026):** first a natural-language interface to the company's API (two-stage retrieval over pgvector, demoed to the whole company), then a local-LLM extraction study run fully on-premise, where I cut a 1,000-email run from 12h to 4h across two GPUs (Python, LangGraph, llama.cpp, Docker)
- **ATMView, Software Engineering Intern (2025):** shipped a CRM-integrated AI agent end to end, from training to internal REST deployment
- **ATMView, Software Engineering Intern (2024):** built fraud-detection pipelines and a role-based internal web application for 50+ users

## Tools I reach for

**Languages** &nbsp; Python · Java · SQL · C · Bash<br>
**Backend** &nbsp; Spring Boot · FastAPI · REST · Microservices<br>
**AI & LLMs** &nbsp; LangGraph · LangChain · llama.cpp · Ollama · pgvector · scikit-learn · Claude Code<br>
**Data & infrastructure** &nbsp; PostgreSQL · MongoDB · Docker · Linux · Git

<br>

<p align="center">
  <sub>Based in France · Arabic, French, and English · TOEIC 965</sub>
</p>
