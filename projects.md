---
layout: default
title: Ge (John) Zhang
permalink: /projects/
---

## 🚀 Personal Projects

### **News Agent with LangGraph**
- **Technologies**: LangGraph, MCP, LLM Agent, Selenium
- **Description**: Developed an automated agent using LangGraph to manage end-to-end news clips generation workflow. The system implements LLM-based news collection, summarization, and multi-language email distribution, with automated publishing pipeline to social media platforms.
- **Features**:
  - Automated news gathering from multiple sources using MCP servers
  - AI-powered summarization in English and multiple languages
  - Multi-platform distribution (email newsletter, social media)
  - Robust error handling and comprehensive state management
- **Diagrams & Screenshots**:
  <div style="display:flex; gap: 12px; align-items:flex-start;">
    <img src="/resources/langgraph_mermaid_diagram.png" alt="LangGraph Workflow Diagram" style="width:50%; height:500px; object-fit:contain;" />
    <img src="/resources/xhs_screenshot.jpg" alt="Xiaohongshu Post Screenshot" style="width:50%; height:500px; object-fit:contain;" />
  </div>
  <img src="/resources/email_screen_shot.jpg" alt="Email Screenshot" style="width:100%; height:auto; margin-top:12px;" />
- Subscribe to [gz_daily_news_clips@googlegroups.com](mailto:gz_daily_news_clips@googlegroups.com) to receive daily news clips.

### **Reinforcement Learning for Chrome Dino Game**
- **Technologies**: Reinforcement Learning, Selenium, PyTorch
- **Description**: Implemented multiple RL algorithms (DQN, REINFORCE, Actor-Critic, PPO) to train agents to play Chrome Dino Game with real-time training environment using Selenium.
- **Key Features**:
  - Multiple RL algorithms for comparison and experimentation
  - Real-time observable training process on browser using Selenium
  - Advanced RL features: replay memory, Generalized Advantage Estimation (GAE)
  - Residual state sampling to detect acceleration of runway, as shown in the **State Sampling Diagram**
  - Continuous training capability with pre-trained models
- **State Sampling Diagram**:
  ![Image Processing Procedure](/resources/image_processing_procedure.png)
- **Results**: 
  - DQN: 9,088 (highest score)
  - Actor-Critic-GAE: 2,310
  - Actor-Critic-TD: 1,216
  - REINFORCE: 780
- **GitHub**: [Deep_Q_Network-on-chrome-dino-jump](https://github.com/ZG2017/Deep_Q_Network-on-chrome-dino-jump)

---

[← Back to Home](/)
