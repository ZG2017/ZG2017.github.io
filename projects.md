---
layout: default
title: Ge (John) Zhang
permalink: /projects/
---

## 🚀 Personal Projects

### **News Agent with LangGraph**
- **Technologies**: LangGraph, MCP, LLM Agent, Selenium
- **Description**: Built an automated **LLM-driven agent workflow** using **LangGraph** to handle end-to-end news collection, summarization, newsletter distribution, and platform posting.
- **Features**:
  - Integrated news sources such as Yahoo Finance and Financial Times; used **gpt-4.1-mini** with **MCP** tools for controlled retrieval and summarization
  - Implemented daily multilingual newsletter distribution and content posting for consistent news delivery
  - Developed a **Selenium**-based automation module to post generated news clips to the **RedNote** platform
- **Diagrams & Screenshots**:
  <div style="display:flex; gap: 12px; align-items:flex-start;">
    <img src="/resources/langgraph_mermaid_diagram.png" alt="LangGraph Workflow Diagram" style="width:50%; height:500px; object-fit:contain;" />
    <img src="/resources/xhs_screenshot.jpg" alt="Xiaohongshu Post Screenshot" style="width:50%; height:500px; object-fit:contain;" />
  </div>
  <img src="/resources/email_screen_shot.jpg" alt="Email Screenshot" style="width:100%; height:auto; margin-top:12px;" />
- Subscribe to [gz_daily_news_clips@googlegroups.com](mailto:gz_daily_news_clips@googlegroups.com) to receive daily news clips.

### **Reinforcement Learning to Play Chrome T-rex Runner Game**
- **Technologies**: Reinforcement Learning, Selenium, PyTorch
- **Description**: Implemented multiple **RL algorithms** (**DQN**, **REINFORCE**, **Actor-Critic**, **PPO**) to train agents to play the Chrome T-Rex Runner game.
- **Key Features**:
  - Constructed an online learning environment using **Selenium** for real-time browser interaction and state observation
  - Applied **experience replay** and **Generalized Advantage Estimation (GAE)** for more stable training and improved sample efficiency
  - Designed **state fusion** by merging consecutive frames to capture game acceleration effects
- **State Sampling Diagram**:
  ![Image Processing Procedure](/resources/image_processing_procedure.png)
- **Results**: 
  - Achieved best scores: REINFORCE (780), Actor-Critic-TD (1,216), Actor-Critic-GAE (2,310), DQN (9,088)
- **GitHub**: [Deep_Q_Network-on-chrome-dino-jump](https://github.com/ZG2017/Deep_Q_Network-on-chrome-dino-jump)

### **Practical Comparison of SFT Approaches for LLMs**
- **Technologies**: LLM SFT, DeepSpeed, LoRA, PyTorch
- **Description**: Evaluated GPU memory usage and training speed across multiple **LLM SFT strategies** using **Qwen2.5-3B-Instruct** on a 2-GPU NVLink-connected setup.
- **Key Features**:
  - Compared **Vanilla SFT**, **DDP**, **DeepSpeed ZeRO-2**, **ZeRO-2 + LoRA**, **ZeRO-3**, and **ZeRO-3 + CPU Offload**
  - Used a toy dataset to minimize the impact of activations and isolate **optimizer state and parameter memory effects**
  - **ZeRO-2 + LoRA** provided the **lowest GPU memory consumption** (26.14 GB) while maintaining **competitive training speed and model performance**, making it a good practice for SFT on small LLMs

---

[← Back to Home](/)
