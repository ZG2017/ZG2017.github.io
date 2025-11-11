---
layout: default
title: Ge (John) Zhang
permalink: /industrial/
---

## 🏭 Industrial Projects

### **Commonsense Reasoning Augmented App Recall**
- **Keywords**: Recommendation System, NLP, LLM, Graph.
- **Background**: Industrial implementation of academic research [**E-CARE: An Efficient LLM-based Commonsense-Augmented Framework for E-Commerce**](https://arxiv.org/abs/2511.04087) to efficiently enhance the app recall procedure with LLM-driven commonsense reasoning.
- **Key Contributions**:
  - Developed a scalable LLM-enhanced framework to improve **query-item relevance matching** in e-commerce recommendation scenarios by injecting **commonsense reasoning** from LLMs
  - Designed a 3-stage training pipeline that removes the need for costly SFT, large-scale human annotations, and real-time LLM inference during serving
  - Constructed a **reasoning factor graph** that distills reasoning from **Qwen2.5-7B-Instruct** and **Llama-3.1-8B-Instruct**, enabling downstream ranking models to access commonsense knowledge with only a single LLM forward pass per query
  - Optimized the reasoning factor graph with **LLM uncertainty estimation** mechanisms to improve its reliability and robustness
- **Results**:
  - Achieved improvements of up to **12.8% Micro-F1** (search relevance) and **12.1% Precision@5** (app recall) in offline evaluations
  - Online A/B test demonstrated **+8.2% Conversion Rate (CVR)** in app advertising recall
  - Published [**research paper**](https://arxiv.org/abs/2511.04087); filed **U.S. Patent Application** (19/337,555)
- **Diagram**:
<img src="/resources/ECARE_pipeline_v2.png" alt="graph generation" style="width:100%; height:220px; object-fit:contain;" />
<div style="display:flex; gap: 12px; align-items:flex-start;">
  <img src="/resources/offline_training.png" alt="Offline Training Pipeline" style="width:50%; height:400px; object-fit:contain;" />
  <img src="/resources/app_recall.png" alt="App Recall Pipeline" style="width:50%; height:400px; object-fit:contain;" />
</div>

### **Unorthodox Fund Name Abbreviation Matching**
- **Keywords**: FinTech, NLP, Information Retrieval
- **Background**: Different institutions use inconsistent abbreviation rules, which poses a challenge for **automatic fund name matching** during data aggregation and analytics for fin-tech companies.
- **Key Contributions**:
  - Formulated the task as an **information retrieval** task: map a given fund name abbreviation to the most relevant standard fund name in the internal database
  - Built a two-stage pipeline: **Elasticsearch**-based **candidate recall** followed by a **char-tokenized Transformer DSSM** **ranking model** for fine-grained similarity scoring
  - Enhanced the performance by synthesizing a large abbreviation-to-full name corpus for **pre-training** of char-tokenized transformer, followed by **fine-tuning** on the real abbreviation-to-full name pairs
- **Results**:
  - Achieved **21%** improvement on fund name retrieve compared to original word2vec cosine similarity

### **User Incentives Distribution**
- **Keywords**: Causal Inference, Recommendation System, AB Testing, ROI Optimization
- **Background**: Specific users may be sensitive to monetary bonuses while others may not. This project aims to identify users who may be stimulated by bonuses using causal inference techniques to maximize potential gain.
- **Key Contributions**:
  - Addressed the **causal inference** challenge of identifying users who are more sensitive to monetary bonuses to optimize **incentive distribution** and increase **user retention** for China's second-largest short video platform
  - Conducted an online randomized incentive experiment on **1M+ users**, collecting high-quality treatment/control data for building a robust causal inference framework
  - Leveraged the **X-learner framework** to estimate heterogeneous treatment effects while addressing **treatment/control data imbalance** issue
  - Used active days within the next 14 days as label to capture long-term dependency instead of next-day retention
- **Results**: 
  - Increased **retained user count by 34%** compared to a random allocation baseline in A/B testing
  - Improved **Return on Investment (ROI) by 15%** by accurately targeting users most likely to respond to incentives

---

## 🏭 Patent Filed

### **NURG: An Efficient Learning-to-Rank Framework with Commonsense Reasoning from Large Language Models** 
- US Patent Application 19/337,555, 2025
- **Authors**: **Ge Zhang**, RD Ajwani, H Gu, Y Hu, Y Zhang

### **Methods and Processors for Relational Reasoning from Text** 
- US Patent Application 19/074,860, 2025
- **Authors**: **Ge Zhang**, MA Alomrani, H Gu, Y Hu, Y Zhang

---

[← Back to Home](/)
