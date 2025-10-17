---
layout: default
title: Industrial Projects
permalink: /industrial/
description: Industrial Projects and Patents - Ge (John) Zhang
---

# 🏭 Industrial Projects & Patents

## Industrial Projects

### **Commonsense Reasoning Augmented App Recall**
- **Keywords**: Recommendation System, NLP, LLM, Graph.
- **Description**: The industrial landing of academic research **E-CARE: An Efficient LLM-based Commonsense-Augmented Framework for E-Commerce**. 
- **Key Contributions**:
  - Proposed a three-stage pipeline to distill domain commonsense from historical query-to-app interactions into a reasoning factor graph requiring no SFT or human annotation.
  - Developed a pipeline that recall app given reasoning factor graph with respect to commonsense behind the input query.
  - Online ABtest shown a increasement of 8.23% on Conversion Rate (CVR).
- **Diagram**:
  <div style="display:flex; gap: 12px; align-items:flex-start;">
    <img src="/resources/offline_training.png" alt="Offline Training Pipeline" style="width:50%; height:400px; object-fit:contain;" />
    <img src="/resources/app_recall.png" alt="App Recall Pipeline" style="width:50%; height:400px; object-fit:contain;" />
  </div>

### **Unorthodox Fund Name Abbreviation Matching**
- **Keywords**: FinTech, NLP, Recommendation System
- **Description**: Various abbreviation criteria of fund names are used in the market, posing a challenge for data aggregation
- **Key Contributions**:
  - Developed recall + ranking pipeline with Elastic Search and DSSM as recall and ranking model, respectively
  - Synthesize a large abbr-to-full name corpus for pre-training, followed by fine-tuning on the real corpus
  - Achieved 21% improvement on fund name recall compared to original word2vec cosine similarity

### **User Bonus Distribution with Causal Inference**
- **Keywords**: Causal Inference, Recommendation System, AB Testing, ROI Optimization
- **Description**: Specific users may be sensitive to money bonus while other users may not. This project aims to find users who may be stimulated by bonus using causal inference techniques to help reach maximum gain.
- **Key Contributions**:
  - Applied causal forest model for robust performance in user bonus sensitivity detection
  - Designed random AB-test on over 1 million users to collect user reactions to bonus changes
  - Proposed new split criterion for causal forest to address multi-target optimization problems
  - Used active days within next 14 days as label to catch long-term dependency instead of next-day retention
- **Results**: 
  - 34% elevation in retained users compared to random group in online AB-test
  - 15% improvement in Return On Investment (ROI)

---

## Patents Applications

### **NURG: An Efficient Learning-to-Rank Framework with Commonsense Reasoning from Large Language Models** (US Patent Application 19/337,555, 2025)
- **Authors**: **Ge Zhang**, R Ajwani, H Gu, Y Hu, Y Zhang

### **Methods and Processors for Relational Reasoning from Text** (US Patent Application 19/074,860, 2025)
- **Authors**: **Ge Zhang**, MA Alomrani, H Gu, Y Hu, Y Zhang

---

[← Back to Home](/)
