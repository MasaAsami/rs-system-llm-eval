# DLJ-2: Debiased LLM-as-a-Judge 2 stage framework

This repository contains the code, data, and evaluation scripts for our study:

> **Uncovering the Risk of Evaluation Formalism: A Debiased LLM-as-a-Judge Study in Japan's Government Project Reviews**  
> Masahiro Asami and Kai Fukunaga (2025)
> , Available at SSRN: https://ssrn.com/abstract=5249953 or http://dx.doi.org/10.2139/ssrn.5249953

We propose a two-stage framework—DLJ-2—that combines large language model (LLM) scoring with hierarchical Bayesian regression to assess the consistency and credibility of logic models submitted in Japan’s administrative project reviews (RS System). This repository provides the full pipeline for replicating our experiments, including prompt templates, LLM outputs, regression scripts, and annotated data.

---

## 📂 Repository Structure

```
│
├── notebooks/            # Analysis notebooks (Bayesian model, plots)
├── data/
│   ├── raw/              # Raw RS data (external link)
│   └── dtm/        # Cleaned logic models and LLM outputs
├── docs/                 # Figures, tables, and LaTeX fragments
├── LICENSE               # MIT License (for code)
└── README.md             # You're here
```



---

## 🚧 Repository Status

This repository is still under active development.  
We will continue to update the code, documentation, and processed data files until the camera-ready version of the paper is released.

