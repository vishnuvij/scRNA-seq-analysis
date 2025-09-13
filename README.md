# scRNA-seq-analysis

# scRNA-seq Analysis of Real PBMC Data (10x Genomics) using Scanpy and PyTorch

## Overview
This project demonstrates a single-cell RNA sequencing (scRNA-seq) analysis workflow using real PBMC (Peripheral Blood Mononuclear Cells) data from 10x Genomics.  

The analysis combines:
- Scanpy for preprocessing, visualization, and clustering  
- PyTorch to build and train a deep autoencoder for dimensionality reduction  
- UMAP projection and Leiden clustering using the learned features  

---

## Background
Single-cell RNA sequencing (scRNA-seq) allows measurement of gene expression at the resolution of individual cells. Unlike bulk RNA-seq, which averages signals across many cells, scRNA-seq reveals cellular diversity, rare cell types, and dynamic processes within complex tissues.  

Applications include studying development, immune responses, and disease progression.  

---

## Important Python Packages
- **scanpy** – main toolkit for single-cell RNA-seq analysis  
- **anndata** – efficient data structure for single-cell datasets (required by Scanpy)  
- **scikit-learn** – machine learning library for clustering and PCA  
- **matplotlib** and **seaborn** – visualization libraries  
- **umap-learn** – dimensionality reduction for visualization  
- **torch** – building and training deep learning models  

---


