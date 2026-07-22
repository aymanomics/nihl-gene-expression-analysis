# 🧬 Noise-Induced Hearing Loss Gene Expression Analysis

A bioinformatics project investigating oxidative stress and Nrf2-related gene expression patterns in noise-induced hearing loss through cross-dataset validation using publicly available Gene Expression Omnibus (GEO) datasets.

---

## Overview

This project analyzes transcriptomic data from mouse cochlear tissue following noise exposure to identify genes associated with oxidative stress, mitochondrial dysfunction, apoptosis, and cellular defense mechanisms.

The workflow combines a discovery dataset with an independent validation dataset to strengthen confidence in biologically relevant findings.

---

## Datasets

### Discovery Dataset

- **GSE100365**
- Mouse cochlear tissue
- Differential gene expression analysis

### Validation Dataset

- **GSE12810**
- Independent validation dataset
- Cross-validation of candidate genes

---

## Repository Contents

```
.
├── GSE100365_discovery_analysis.ipynb
├── GSE12810_validation_analysis.ipynb
├── Research Paper.pdf
└── README.md
```

---

## Methods

This project includes analyses such as:

- Differential Gene Expression
- Volcano Plot Visualization
- Heatmaps
- Principal Component Analysis (PCA)
- Random Forest Classification
- Gene Co-expression Network Analysis
- Cross-Dataset Validation

---

## Biological Focus

The project investigates pathways related to:

- Oxidative Stress
- Nrf2 Signaling
- Mitochondrial Dysfunction
- Apoptosis
- Noise-Induced Hearing Loss (NIHL)

---

## Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Author

**Ayman Rahman**

Incoming Biology (Bioinformatics) Student

University of California, San Diego

GitHub:
https://github.com/aymanomics

---

## Future Improvements

- Improve reproducibility
- Organize repository into folders
- Add downloadable figures
- Improve documentation
- Add installation instructions
