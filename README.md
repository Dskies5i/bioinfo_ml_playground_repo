'''
# Bio-ML Playground

A curated workspace of hands-on notebooks, reference tutorials, and reusable modules across **Classical Machine Learning**, **Deep Learning & NLP**, and **Bioinformatics**.

## Overview

This repository demonstrates core implementation and experimentation skills across:
- **Classical ML:** Supervised learning workflows (`linear_regression`, `logistic_regression`, `knn_classifier`, `decision_tree`, `naive_bayes`).
- **Deep Learning & NLP:** PyTorch fundamentals, word embedding exploration (GloVe + NumPy and Skip-gram from scratch), and custom GPT-2 transformer implementations.
- **Bioinformatics:** Reusable tutorials and reference workflows, including single-cell RNA-seq analysis with Seurat.

## Repository Structure

```text
bio-ml-playground/
├── README.md
├── .gitignore
├── requirements.txt
├── classical_ml/
│   ├── decision_tree.ipynb
│   ├── knn_classifier.ipynb
│   ├── linear_regression.ipynb
│   ├── logistic_regression.ipynb
│   └── naive_bayes.ipynb
├── deep_learning/
│   ├── glove_embeddings_numpy.ipynb
│   ├── gpt2_complete.ipynb
│   ├── gpt2_from_scratch_quijote.ipynb
│   ├── pytorch_basics.ipynb
│   └── skipgram_embeddings_scratch.ipynb
└── bioinformatics/
    └── seurat_scrnaseq_tutorial.pdf
```

--- 

## Highlights by Module
### classical_ml/
- Foundational supervised learning notebooks covering regression and classification models:
- linear_regression.ipynb — Linear regression modeling and core concepts.
- logistic_regression.ipynb — Binary/multi-class classification with logistic regression.
- knn_classifier.ipynb — K-Nearest Neighbors classification experiments.
- decision_tree.ipynb — Decision tree classification and splitting behavior.
- naive_bayes.ipynb — Probabilistic classification with Naive Bayes.

### deep_learning/
- Hands-on PyTorch, representation learning, and transformer notebooks:
- pytorch_basics.ipynb — Core PyTorch tensor operations and building blocks.
- glove_embeddings_numpy.ipynb — Pre-trained GloVe vector lookups, PCA & t-SNE dimensionality reduction, cosine similarity, and vector analogies using NumPy.
- skipgram_embeddings_scratch.ipynb — Skip-gram word embeddings implemented from scratch in PyTorch with embedding visualization and similarity queries.
- gpt2_from_scratch_quijote.ipynb — From-scratch PyTorch GPT-2 architecture (causal self-attention, feed-forward blocks, weight tying) trained on text corpora.
- gpt2_complete.ipynb — End-to-end GPT-2 notebook reference.

### bioinformatics/
Reusable tutorials, walkthroughs, and short reference guides:
- seurat_scrnaseq_tutorial.pdf — Single-cell RNA-seq analysis workflow in R using Seurat (QC, normalization, PCA, UMAP, clustering, and marker gene identification).

### Getting Started
```
Bash
git clone [https://github.com/](https://github.com/)<your-username>/bio-ml-playground.git
cd bio-ml-playground
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

### Notes
Notebooks are structured for clarity, reproducibility, and rapid prototyping.
Larger domain-specific pipelines and production projects are maintained in dedicated repositories.
