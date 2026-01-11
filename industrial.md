---
layout: default
title: Ge (John) Zhang
permalink: /industrial/
---

## 🏭 Industrial Projects

### **Commonsense Reasoning Augmented App Recall**
- **Background**: Industrial application of academic research [**E-CARE: An Efficient LLM-based Commonsense-Augmented Framework for E-Commerce**](https://arxiv.org/abs/2511.04087) to efficiently enhance the app recall procedure with LLM-driven commonsense reasoning.
- **Key Contributions**:
  - Designed a commonsense-augmented recall framework that improves **query–app relevance estimation** by incorporating **commonsense reasoning** signals from LLMs.
  - Followed the same 3-stage pipeline from [**E-CARE**](https://arxiv.org/abs/2511.04087) that employs **Qwen2.5-7B-Instruct** to generate commonsense reasoning between query-app interactions, and builds a **reasoning factor graph** to store semantic relationships between queries and apps through reasoning factors.
  - Trained lightweight adapters that map queries and apps into the reasoning factor space, enabling **efficient inference** for serving stage.
  - During serving, the query adapter predicts reasoning factors that represent user intentions, and apps linked to those predicted factors are retrieved as recall candidates.
- **Results**:
  - Online A/B test demonstrated **1.41%**, **0.65%** and **3.39%** improvements for **Value Per Mille (VPM)**, **Click Through Rate (CTR)**, and **ConVersion Rate (CVR)**, respectively.
- **Diagram**:
<img src="/resources/ECARE_pipeline_v2.png" alt="graph generation" style="width:100%; height:220px; object-fit:contain;" />
<div style="display:flex; gap: 12px; align-items:flex-start;">
  <img src="/resources/offline_training.png" alt="Offline Training Pipeline" style="width:50%; height:400px; object-fit:contain;" />
  <img src="/resources/app_recall.png" alt="App Recall Pipeline" style="width:50%; height:400px; object-fit:contain;" />
</div>

### **Unorthodox Fund Name Abbreviation Matching**
- **Background**: Different institutions use inconsistent abbreviation rules, which poses a challenge for **automatic fund name matching** during data aggregation and analytics for fin-tech companies.
- **Key Contributions**:
  - Formulated the task as an **information retrieval** task: map a given fund name abbreviation to the most relevant standard fund name in the internal database
  - Built a two-stage pipeline: **Elasticsearch**-based **candidate recall** followed by a **char-tokenized Transformer DSSM** **ranking model** for fine-grained similarity scoring
  - Enhanced the performance by synthesizing a large abbreviation-to-full name corpus for **pre-training** of char-tokenized transformer, followed by **fine-tuning** on the real abbreviation-to-full name pairs
- **Results**:
  - Achieved **21%** improvement on fund name retrieval compared to original word2vec cosine similarity

### **User Incentives Distribution**
- **Background**: Specific users may be sensitive to monetary bonuses while others may not. This project aims to identify users who may be stimulated by bonuses using causal inference techniques to maximize potential gain.
- **Key Contributions**:
  - Addressed the **causal inference** challenge of identifying users who are more sensitive to monetary bonuses to optimize **incentive distribution** and increase **user retention** for China's second-largest short video platform
  - Conducted an online randomized incentive experiment on **1M+ users**, collecting high-quality treatment/control data for building a robust causal inference framework
  - Leveraged the **X-learner framework** to estimate heterogeneous treatment effects while addressing **treatment/control data imbalance** issue
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
