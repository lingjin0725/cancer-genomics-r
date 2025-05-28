# Cancer Genomics Analysis Using R

This project was completed as part of STAT 437: High Dimensional Data Learning. It explores large-scale gene expression data from the TCGA Pan-Cancer HiSeq dataset and applies statistical and machine learning methods to identify and classify cancer subtypes.


## Project Overview

The dataset consists of 801 patient samples with expression levels for over 20,000 genes. This high-dimensional structure (p ≫ n) presents both computational and analytical challenges, which are addressed through dimensionality reduction, clustering, and classification models.


## Objectives

- Perform exploratory data analysis (EDA) and visualize patterns using PCA
- Identify natural groupings via unsupervised clustering (k-means, hierarchical)
- Apply supervised learning models (logistic regression, kNN, SVM) to classify samples
- Evaluate model performance using AUC and confusion matrix


## Dataset

- **Source**: TCGA Pan-Cancer (HiSeq)
- **Samples**: 801
- **Features**: 20,531 gene expression levels

Note: Raw gene expression matrix and SPAM.csv dataset used for classification are provided in the repository.


## Methods & Tools

| Tool/Library | Description |
|--------------|-------------|
| `R`          | Core statistical analysis and modeling |
| `PCAtools`   | Dimensionality reduction |
| `ggplot2`    | Visualization |
| `caret`      | Model training |
| `e1071`      | SVM implementation |
| `RMarkdown`  | Reproducible documentation |


## Key Results

- **PCA** revealed biologically meaningful structure in the gene expression space
- **Gap Statistic & Elbow Method** indicated 2–3 optimal clusters
- **SVM classifier** achieved **AUC = 0.92** with strong generalization on test data


## Key Learnings

This project improved my ability to:

- Handle high-dimensional biological data
- Design reproducible workflows using R
- Interpret unsupervised and supervised ML results
- Communicate insights effectively using visualizations


## 🔗 License

This project is shared for educational purposes only. Please cite TCGA if using the dataset.
