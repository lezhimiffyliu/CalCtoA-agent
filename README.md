# CalCtoA: A Calculus Learning Agent built with NVIDIA NeMo 🧮🤖

**My journey of learning NVIDIA NeMo by building an interactive calculus learning agent.**  
This repository documents each step from setup to custom agent design through reproducible Jupyter notebooks.

I started this project to explore how tools like NVIDIA’s **NeMo Agent Toolkit** can make learning more interactive and supportive.  
Having once rebuilt my own math foundation after high school, I understand how challenging it can be to grasp abstract ideas alone.  
This is both a technical exploration and a personal project to see whether AI agents can help make learning calculus more intuitive, structured, and encouraging for others who are walking the same path.


---

## 📁 Project Structure

calctoa-agent/
├── notebooks/
├── src/
├── README.md
├── requirements.txt
└── .gitignore
```
calctoa-agent/
│
├── notebooks/
│   ├── day1_setup.ipynb
│   ├── day2_symbolic_demo.ipynb
│   ├── day3_nemo_tool_use.ipynb
│   ├── day4_agent_pipeline.ipynb
│   ├── day5_ui_demo.ipynb
│
├── src/
│   ├── agent/
│   │   ├── __init__.py
│   │   ├── calculator_tool.py
│   │   ├── learning_memory.py
│   │   └── nemo_pipeline.py
│   ├── app/
│   │   ├── main.py
│   │   ├── api.py
│   │   └── ui.py
│
├── README.md
├── requirements.txt
└── .gitignore
---
```

## 🚀 Progress Log

- 🗓️ Day 1: Setup NeMo environment and ran base model
- 🧮 Day 2: Implemented symbolic derivative tool using sympy
- 🧠 Day 3: Added memory system for learning progress
- 📊 Day 4: Built visualization of derivative curves
- 💬 Day 5: Streamlit demo prototype

---

## 💡 Next Steps

---

## ⚙️ Environment
- Python 3.11+  
- NVIDIA NeMo (installed via official docs)
- IDE: VS Code
- OS: macOS (local development)

---

## 🧩 Goal
To explore how large-model agent frameworks can assist in **calculus reasoning, tutoring, and problem solving**, and to document the full learning journey in an open, reproducible format.

---

## 🤨 Why NeMo?
