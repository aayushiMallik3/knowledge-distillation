# Online Feedback Distillation

This repository contains a research prototype for teaching lightweight language models to mimic expert feedback in reasoning tasks.

The project builds on CLEAR (Contrasting Textual Feedback with Experts and Amateurs for Reasoning), a framework where a base model generates an answer, expert and amateur models critique it, and the answer is revised using unified feedback.

Our extension replaces the fixed amateur model with an adaptive student model trained through online knowledge distillation, reducing reliance on expensive expert feedback while preserving feedback quality.

online-feedback-distillation/

├── README.md
├── requirements.txt

├── notebooks/
│   ├── 01_data_generation.ipynb
│   ├── 02_clear_baseline.ipynb
│   ├── 03_cot_baseline.ipynb
│   ├── 04_cod_baseline.ipynb
│   ├── 05_kd_training.ipynb
│   └── 06_evaluation.ipynb

├── src/
│   ├── models/
│   ├── training/
│   ├── evaluation/
│   ├── thresholds/
│   └── metrics/

├── results/
│   ├── figures/
│   ├── plots/
│   └── tables/

├── paper/
│   ├── proposal.pdf
│   └── final_paper.pdf

└── assets/
    └── architecture.png
