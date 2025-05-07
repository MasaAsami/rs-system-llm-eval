# DLJ-2: Debiased LLM-as-a-Judge for Logic Model Evaluation in Japanese Government Reviews

This repository contains the code, data, and evaluation scripts for our study:

> **A Debiased LLM-as-a-Judge Approach Reveals the
Risk of Evaluation Formalism in Japan’s EBPM**  
> Masahiro Asami and Kai Fukunaga (2025)  
> [Preprint DOI:XXXXXXX]()

We propose a two-stage framework—DLJ-2—that combines large language model (LLM) scoring with hierarchical Bayesian regression to assess the consistency and credibility of logic models submitted in Japan’s administrative project reviews (RS System). This repository provides the full pipeline for replicating our experiments, including prompt templates, LLM outputs, regression scripts, and annotated data.

---

## 📂 Repository Structure

```
├── src/                  # DLJ-2 implementation (scoring + debiasing)
├── notebooks/            # Analysis notebooks (Bayesian model, plots)
├── data/
│   ├── raw/              # Raw RS data (external link)
│   └── processed/        # Cleaned logic models and LLM outputs
├── models/
│   └── prompts/          # Prompt examples and GPT-4o responses
├── docs/                 # Figures, tables, and LaTeX fragments
├── LICENSE               # MIT License (for code)
└── README.md             # You're here
```



---

## 🚧 Repository Status

This repository is still under active development.  
We will continue to update the code, documentation, and processed data files until the camera-ready version of the paper is released.

