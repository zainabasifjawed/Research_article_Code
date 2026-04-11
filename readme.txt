# Personality-Aware Recommendation System using LLMs, RAG, XAI, and LoRA (HOMEFIT)

## Description

This repository contains the complete implementation and experimental results of a **personality-aware recommendation system** based on MBTI personality prediction and large language model-based recommendation generation.

The system integrates:
- Machine Learning for personality prediction  
- Explainable AI (XAI) for interpretability  
- Retrieval-Augmented Generation (RAG) for contextual retrieval  
- Large Language Models (LLMs) for recommendation generation  
- Parameter-efficient fine-tuning using LoRA  

The project is designed for research reproducibility and evaluation in academic settings.

---

## Important Note (API Keys & Security)

For security reasons, all **API keys (OpenAI / Groq / LLM keys)** have been completely removed from the codebase.

If required for reproduction or evaluation purposes, API keys can be provided upon request via email.

---

## Repository Structure

### Notebook 1 — Main Pipeline
- Dataset preprocessing (cleaning, splitting, balancing)
- MBTI personality prediction model
- Evaluation of prediction performance
- Explainable AI (XAI) analysis
- Recommendation generation using RAG + LLMs
- Fine-tuning using LoRA
- Evaluation metrics:
  - BLEU
  - ROUGE-L
  - SBERT similarity

---

### Notebook 2 — Generalization & Test Cases
- Contains test cases across multiple MBTI personality types
- Validates robustness and generalization of recommendation system
- Demonstrates that outputs remain consistent across different personality classes

---

## HTML Version (Important)

Due to persistent **Jupyter widget rendering issues in Google Colab and GitHub notebook preview**, separate HTML versions of the notebooks have been created.

These HTML files:
- Preserve all outputs (tables, graphs, metrics, results)
- Properly display evaluation results and predictions
- Serve as the primary artifact for result visualization

👉 HTML files should be used to view complete outputs if notebook rendering fails.

---


## Results

All outputs are already included in:
- Notebooks (code)
- HTML versions (full visual outputs)

Evaluation metrics include:
- Personality prediction accuracy ,Precison ,Recall and F1
- BLEU score  
- ROUGE-L score  
- SBERT semantic similarity  

---

## Reproducibility

All code required for reproduction is included in this repository.  
If any additional API keys or access credentials are required, they can be provided upon formal request.


---

## License

For academic and research purposes only.