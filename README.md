🧠 Feature Selection Cross-Domain Evaluation (Chi2, RFE, LASSO)

This repository supports the publication:

"Comparative Evaluation of Chi-square, RFE, and LASSO Feature Selection Across Three Data Domains Using an Optimized Pipeline"
by Aulia Miftah Razak & Shofwatul Uyun

📄 Overview

This project presents a systematic comparison of three feature selection (FS) 
methods — Chi-square, Recursive Feature Elimination (RFE), and LASSO 
across datasets representing three different data domains:

- 🧬 Breast Cancer Wisconsin (Tabular Medical)
- 📰 20 Newsgroups (Sparse Text)
- 🖼️ MNIST (Grid-structured Image)

The evaluation considers predictive performance (Macro-F1), execution time (seconds), and memory usage (MB) using a reproducible, optimized pipeline.

---

📁 Repository Structure
```bash
feature-selection-crossdomain/
│
├── fs_full_pipeline_one_domain - OPTTIMIZED2.ipynb      # Main pipeline: FS methods, model training
├── combined visualisation.ipynb          # Charts: macro-F1, runtime, memory usage
├── requirements.txt             # Required Python packages
├── LICENSE                      # MIT License
├── README.md                    # You are here
├── results/                     # Charts, CSVs of results, performance tables
    └── macrof1_plot.png, runtime_table.csv, etc.
