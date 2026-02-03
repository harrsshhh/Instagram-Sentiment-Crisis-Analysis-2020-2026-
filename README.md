# Instagram-Sentiment-Crisis-Analysis-2020-2026-
# 📊 Scalable Sentiment Intelligence: Instagram Review Analysis (2020–2026)

![Python](https://img.shields.io/badge/Python-3.12-blue)
![NLP](https://img.shields.io/badge/AI-Llama3%20%2B%20VADER-purple)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 🚀 Project Overview
This project addresses the challenge of analyzing **6 million+ unstructured app reviews** to diagnose root causes of user churn. By implementing a Hybrid AI Architecture, I combined the depth of Generative AI (Llama 3) with the scalability of Machine Learning to classify user complaints at scale without high compute costs.

## 🏗️ Technical Architecture
The pipeline utilizes a multi-tier approach:
1.  Tier 1 (The Pulse): VADER scans 100% of data for instant sentiment trending.
2.  Tier 2: Llama 3 (via Ollama) labels a stratified "Gold Standard" sample to understand context.
3.  Tier 3: Logistic Regression learns from the LLM and scales insights to 6M rows.

## 📂 Repository Structure
- `main.py`: CLI entry point for the analysis pipeline.
- `preprocessing.py`: Pandas chunking and regex text cleaning.
- `sentiment_analysis.py`: Logic for VADER, Ollama integration, and ML training.
- `visualization.py`: Scripts to generate heatmaps and trend lines.
- `config.py`: Configuration for paths and model parameters.

## 📊 Key Insights
- **Root Cause Discovery:** Shifted insights from generic "satisfaction drops" to specific triggers like the **Q3 Ad Policy Change**.
- **Crisis Detection:** Automated anomaly detection identified specific "Crash Months" where ratings dropped >0.5 stars.
