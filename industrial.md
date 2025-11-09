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
  - Proposed a three-stage pipeline to distill domain commonsense from historical query-to-app interactions into a reasoning factor graph requiring no supervised fine-tuning or human annotation.
  - Developed a pipeline that recalls apps given reasoning factor graph with respect to commonsense behind the input query.
- **Results**:
  - Offline evaluation showed that recall@5 improved by 11.1%, while precision@5 increased by 12.1%.
  - Online A/B testing demonstrated an 8.23% increase in Conversion Rate (CVR).
- **Diagram**:
<img src="/resources/ECARE_pipeline_v2.png" alt="graph generation" style="width:100%; height:220px; object-fit:contain;" />
<div style="display:flex; gap: 12px; align-items:flex-start;">
  <img src="/resources/offline_training.png" alt="Offline Training Pipeline" style="width:50%; height:400px; object-fit:contain;" />
  <img src="/resources/app_recall.png" alt="App Recall Pipeline" style="width:50%; height:400px; object-fit:contain;" />
</div>

### **Unorthodox Fund Name Abbreviation Matching**
- **Keywords**: FinTech, NLP, Recommendation System
- **Background**: Various abbreviation criteria of fund names are used in the market, posing challenges for data aggregation.
- **Key Contributions**:
  - Developed recall and ranking pipeline with Elasticsearch and DSSM as recall and ranking models, respectively
  - Synthesized a large abbreviation-to-full name corpus for pre-training, followed by fine-tuning on the real corpus
- **Results**:
  - Achieved 21% improvement in fund name recall compared to original word2vec cosine similarity

### **User incentives Distribution**
- **Keywords**: Causal Inference, ROI Optimization
- **Background**: Specific users may be sensitive to monetary bonuses while others may not. This project aims to identify users who may be stimulated by incentives using causal inference techniques to increase user retention.
- **Key Contributions**:
  - collected random treatment data from over one million users
  - Used active days of next 7 days as label instead of next-day retention to reduce the variance of label 
  - Applied the X-learner framework for robust performance in user incentive sensitivity detection
- **Results**: 
  - 34% increase in retained users compared to random group in online A/B testing
  - 15% improvement in Return on Investment (ROI)

---

## 🏭 Patent Filed

### **NURG: An Efficient Learning-to-Rank Framework with Commonsense Reasoning from Large Language Models** 
- US Patent Application 19/337,555, 2025
- **Authors**: **Ge Zhang**, R Ajwani, H Gu, Y Hu, Y Zhang

### **Methods and Processors for Relational Reasoning from Text** 
- US Patent Application 19/074,860, 2025
- **Authors**: **Ge Zhang**, MA Alomrani, H Gu, Y Hu, Y Zhang

---

[← Back to Home](/)
