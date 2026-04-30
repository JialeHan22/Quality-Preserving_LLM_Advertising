# Mechanism Design for Quality-Preserving LLM Advertising

This repository provides Python implementations of the auction mechanisms evaluated in the paper, with results presented in Jupyter notebooks.

## Repository Structure

- **`QP single`** — Code for the QP single-allocation mechanisms (**QP w/ repl.** and **QP w/o repl.**) across all 4 scenarios, along with output logs over 100 trials.
- **`QP multi`** — Code for the QP multi-allocation mechanism (**QP multi-allo**) across all 4 scenarios, along with output logs over 100 trials.
- **`Seg single & multi`** — Code for the Seg single-allocation mechanisms (**Seg w/ repl.** and **Seg w/o repl.**) and the Seg multi-allocation mechanism (**Seg multi-allo**) across all 4 scenarios, along with output logs over 100 trials.
- **`No-Ad Response`** — Code for generating no-ad responses and the corresponding results reported in Appendix G.

## Notebooks

- **`Metrics Comparison.ipynb`** — Compares all metrics across all mechanisms. Its output reproduces every results table in the paper, except for the initial relevance of the ads, which is computed in `QP_single.ipynb` under the **`QP single/`** folder.
- **`Quality Comparison.ipynb`** — Compares the output quality across all mechanisms, producing Figures 1, 3, 5, and 7 in the paper.
