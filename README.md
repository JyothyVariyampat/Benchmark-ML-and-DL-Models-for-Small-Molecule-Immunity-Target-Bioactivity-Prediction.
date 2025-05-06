# Benchmark-ML-and-DL-Models-for-Small-Molecule-Immunity-Target-Bioactivity-Prediction.
## 🔍 Overview

This study benchmarks various Machine Learning (ML) and Deep Learning (DL) models, including:
- Support Vector Machines (SVM)
- Gaussian Naive Bayes (GNB)
- Feedforward Neural Networks (FFNN)
- Convolutional Neural Networks (CNN)
- Graph Neural Networks (GCN, VanillaGNN)
- AttentiveFP 

The models were trained to predict and classify the bioactivity of molecules against key innate immunity protein targets:
- STAT1 (alpha/beta isoform)
- NF-κB (p105 subunit)
- NOD1 (isoform 1)
- IL1-RL1 (Interleukin-1 receptor-like 1 ST2)

  The influence of dataset chemical space diversity was further assessed by analysing t-distributed Stochastic Neighbor Embedding (t-SNE) projections. To optimize predictive performance, Ensemble Learning techniques incorporating Logical AND, Logical OR, and Majority Voting approaches are used to refine the precision-recall trade-off for early-stage screening applications. To enhance transparency, a Concept Whitening regularizer is integrated into the GCN model, aligning learned features with known molecular descriptors.

  
## Dataset

The dataset is hosted externally due to size limits.  
[Click here to download the dataset](https://drive.google.com/drive/folders/185XXqtQOjVpqSIdpFlkQmFWjuElTU9FA?usp=sharing)

