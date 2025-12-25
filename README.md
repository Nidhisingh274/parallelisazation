A story generation agent built using **LangGraph**, **Groq (LLaMA 3.1)**, and **Parallel Prompt Chaining**.  
This project demonstrates how to create **multiple AI nodes running in parallel** to generate:
- Characters
- Setting
- Plot Premise
- Combined Story Introduction

All nodes operate independently and converge into a final agent that composes the story.

---

## ✨ Features
- ⚙️ **Agentic Workflow** with LangGraph
- ⚡ **Parallel Node Execution** (Character, Setting, Premise generated simultaneously)
- 🤖 Uses **Groq API** for ultra-fast inference
- 📌 Beginner-friendly state management using `TypedDict`
- 📊 Includes visual graph output (Mermaid Flow)
  
---

## 🧩 Tech Stack

| Component | Usage |
|-----------|--------|
| **Python** | Core project |
| **LangGraph** | Agent workflow & parallel nodes |
| **Groq + LLaMA-3.1** | Model inference |
| **Prompt Chaining** | Step-by-step task orchestration |

---
