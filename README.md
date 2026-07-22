# Investigating Oxidative Stress and Nrf2-Related Gene Expression Patterns in Noise-Induced Hearing Loss Using Bioinformatics and Cross-Dataset Validation

## Overview

Noise-Induced Hearing Loss (NIHL) is one of the leading causes of acquired sensorineural hearing loss worldwide. Although excessive noise exposure is known to damage cochlear structures, the molecular mechanisms driving cellular degeneration remain incompletely understood.

This project applies a comprehensive bioinformatics workflow to investigate transcriptomic changes associated with NIHL, with particular emphasis on oxidative stress pathways and Nrf2-mediated antioxidant signaling. Using publicly available Gene Expression Omnibus (GEO) datasets, differential gene expression analysis, dimensionality reduction, machine learning, and network analysis were integrated to identify biologically meaningful genes and pathways involved in cochlear injury.

Through cross-dataset validation, this study demonstrates how computational biology can generate biologically relevant hypotheses from publicly available genomic datasets while increasing confidence in candidate biomarkers associated with noise-induced hearing loss.

---

# Abstract

Noise-induced hearing loss remains a significant public health concern, yet its molecular mechanisms are not fully understood. This project investigated transcriptomic alterations following acoustic trauma using publicly available mouse cochlear gene expression datasets from the NCBI Gene Expression Omnibus (GEO). Differential gene expression analysis, Principal Component Analysis (PCA), heatmap visualization, Random Forest machine learning, gene co-expression network analysis, and independent dataset validation were performed to identify reproducible oxidative stress-related biomarkers. Results demonstrated coordinated dysregulation of genes involved in oxidative stress, mitochondrial dysfunction, apoptosis, heat shock response, and Nrf2 antioxidant signaling. Rather than identifying a single causative biomarker, the findings support a systems-level model in which multiple interconnected biological pathways contribute to cochlear degeneration following noise exposure.

---

# Research Objectives

This study sought to answer the following biological questions:

- Which genes are significantly altered following noise exposure?
- Are oxidative stress pathways consistently dysregulated across independent datasets?
- Which candidate genes demonstrate reproducible expression changes between discovery and validation cohorts?
- Can machine learning accurately distinguish healthy and noise-exposed cochlear tissue?
- Which genes occupy central positions within oxidative stress-related interaction networks?

---

# Datasets

## Discovery Dataset

**GSE100365**

- Mouse cochlear tissue
- Multiple post-noise exposure timepoints
- Primary differential gene expression analysis
- PCA
- Machine learning
- Network analysis

## Validation Dataset

**GSE12810**

- Independent mouse cochlear dataset
- Cross-dataset validation of candidate genes
- Biological confirmation of discovery findings

---

# Bioinformatics Workflow

The computational pipeline consisted of:

1. Data acquisition from NCBI GEO
2. Data preprocessing and quality assessment
3. Differential gene expression analysis
4. Volcano plot visualization
5. Principal Component Analysis (PCA)
6. Heatmap visualization
7. Random Forest classification
8. Gene co-expression network analysis
9. Cross-dataset validation
10. Biological interpretation through literature review

---

# Computational Methods

## Differential Gene Expression

Identified genes exhibiting statistically significant expression changes following acoustic trauma.

## Principal Component Analysis (PCA)

Reduced transcriptomic dimensionality to visualize clustering between control and noise-exposed cochlear samples.

## Heatmap Visualization

Visualized expression patterns of oxidative stress-related genes across experimental conditions.

## Random Forest Machine Learning

Developed a supervised classification model capable of distinguishing healthy and noise-exposed cochlear tissue while identifying highly informative predictive genes.

## Gene Co-expression Network Analysis

Constructed interaction networks to identify coordinated transcriptional responses and highly connected candidate genes associated with oxidative stress.

## Cross-Dataset Validation

Validated candidate biomarkers using an independent GEO dataset to improve biological confidence and reduce dataset-specific bias.

---

# Key Biological Findings

The analyses identified coordinated dysregulation of genes involved in:

- Oxidative stress
- Nrf2 antioxidant signaling
- Mitochondrial dysfunction
- Heat shock response
- Apoptosis
- Cellular stress adaptation
- Noise-induced cochlear degeneration

Rather than identifying a single causative biomarker, the results support the hypothesis that NIHL develops through coordinated disruption of multiple interconnected oxidative stress pathways.

---

# Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- SciPy
- Matplotlib
- Scikit-learn

---

# Repository Contents

```
.
├── GSE100365_Discovery_Analysis.ipynb
├── GSE12810_Validation_Analysis.ipynb
├── NIHL_Bioinformatics_Research_Paper.pdf
└── README.md
```

---

# Scientific Significance

Noise-induced hearing loss affects hundreds of millions of individuals worldwide and remains one of the most prevalent occupational and environmental health conditions. Despite extensive research, effective molecular therapies remain limited.

By integrating transcriptomic analysis, machine learning, and cross-dataset validation, this project demonstrates how computational biology can identify reproducible molecular signatures associated with cochlear injury. The computational framework presented here may contribute to future studies investigating therapeutic targets and protective mechanisms against hearing loss.

---

# Future Directions

Potential extensions of this work include:

- RNA-Seq analysis of additional NIHL datasets
- Gene Ontology (GO) enrichment analysis
- KEGG pathway enrichment analysis
- Gene Set Enrichment Analysis (GSEA)
- Protein-protein interaction network analysis
- Single-cell RNA sequencing integration
- Multi-omics approaches
- Experimental laboratory validation

---

# Author

**Ayman Rahman**

Incoming Biology with a Specialization in Bioinformatics Student  
University of California, San Diego

### Research Interests

- Bioinformatics
- Computational Biology
- Auditory Neuroscience
- Hearing Loss
- Regenerative Medicine
- Functional Genomics
- Machine Learning in Biology

GitHub: https://github.com/aymanomics

---

# Citation

If you reference this repository, please cite the accompanying research paper:

> Rahman, A. (2026). *Investigating Oxidative Stress and Nrf2-Related Gene Expression Patterns in Noise-Induced Hearing Loss Using Bioinformatics and Cross-Dataset Validation.*

---

# Acknowledgements

This project was completed as an independent high school biomedical research project using publicly available transcriptomic datasets from the National Center for Biotechnology Information (NCBI) Gene Expression Omnibus (GEO).

The study builds upon the work of the researchers who generated and publicly shared these datasets, making reproducible computational biology research possible.

This repository serves as both a scientific research record and a demonstration of computational biology, bioinformatics, and data analysis techniques applied to real-world biological questions.

---

# Disclaimer

This repository is intended for educational and research purposes. The analyses and interpretations presented here are not intended for clinical diagnosis or medical decision-making.

---

# License

This project is available for educational and non-commercial research purposes.
