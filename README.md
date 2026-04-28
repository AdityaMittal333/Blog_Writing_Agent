# AI Blog Writing Agent

An intelligent **AI-powered blog writing agent** built using LangGraph that automatically generates complete, research-backed blog posts.  
The system goes beyond simple prompt-based generation by using a **planning-based multi-agent architecture** that performs research, organizes content, and generates structured blog posts with citations and images.

This project demonstrates how **modern AI agents are designed and orchestrated** using LangGraph, LangChain, and large language models.

---

## 🚀 Features

- Planning-based AI agent workflow
- Multi-agent architecture using LangGraph
- Automatic internet research using Tavily API
- Parallel task execution with worker agents
- Structured blog generation with sections
- Automatic citation generation
- Image-aware blog content
- End-to-end blog generation pipeline
- Interactive UI built with Streamlit

---

## 🧠 Agent Architecture

The project implements an **Orchestrator–Worker architecture** where multiple agents collaborate to generate a blog.

Main components:

### Router Node
Determines the type of request and routes it to the appropriate workflow.

### Planner Node
Creates a structured plan for the blog including headings and sections.

### Worker Agents
Multiple worker agents generate content for each section in parallel.

### Research Module
Uses Tavily API to fetch real-time internet information for factual accuracy.

### Reducer Node
Combines outputs from worker agents into a final structured blog post.

---

## 🏗 Tech Stack

- Python
- LangGraph
- LangChain
- OpenAI / Gemini LLMs
- Tavily Search API
- Streamlit
- Async task execution


- Multi-agent orchestration

--

## 📊 Workflow

1. User enters a blog topic
2. Router identifies the request type
3. Planner creates a structured blog outline
4. Worker agents generate section content
5. Tavily performs internet research
6. Citations and images are added
7. Reducer compiles the final blog post

---

## 📁 Project Structure

```
Blog_Writing_Agent
│
├── bwa_backend.py
├── bwa_frontend.py
├── 1_bwa_basic.ipynb
├── 2_bwa_improved_prompting.ipynb
├── 3_bwa_research.ipynb
├── 4_bwa_research_fine_tuned.ipynb
├── 5_bwa_image.ipynb
├── tavily_test.ipynb
```

---

## 🎯 Learning Outcomes

This project demonstrates:

- Designing real-world AI agents
- Multi-agent orchestration with LangGraph
- Planning-based agent systems
- Research-augmented generation
- Parallel task execution with worker agents
- Building production-style AI pipelines

---

## 📌 Future Improvements

- Add vector database for RAG
- Implement hallucination detection
- Add agent monitoring and evaluation
- Add cost and token tracking
- Deploy the application on cloud

---

## 👨‍💻 Author

Aditya Mittal

GitHub:  
https://github.com/AdityaMittal333

---

## ⭐ If you found this project useful, consider giving it a star!
