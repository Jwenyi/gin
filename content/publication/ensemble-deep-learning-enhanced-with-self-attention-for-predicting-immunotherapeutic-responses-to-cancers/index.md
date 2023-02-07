---
title: Ensemble deep learning enhanced with self-attention for predicting
  immunotherapeutic responses to cancers
publication_types:
  - "2"
authors:
  - Wenyi Jin
  - Qian Yang
  - Hao Chi
  - Kongyuan Wei
  - Pengpeng Zhang
  - Guodong Zhao
  - Shi Chen
  - Zhijia Xia
  - Xiaosong Li
doi: 10.3389/fimmu.2022.1025330
publication: Frontiers in Immunology
abstract: >-
  Introduction: Despite the many benefits immunotherapy has brought to patients
  with different cancers, its clinical applications and improvements are still
  hindered by drug resistance. Fostering a reliable approach to identifying
  sufferers who are sensitive to certain immunotherapeutic agents is of great
  clinical relevance.


  Methods: We propose an ELISE (Ensemble Learning for Immunotherapeutic Response Evaluation) pipeline to generate a robust and highly accurate approach to predicting individual responses to immunotherapies. ELISE employed iterative univariable logistic regression to select genetic features of patients, using Monte Carlo Tree Search (MCTS) to tune hyperparameters. In each trial, ELISE selected multiple models for integration based on add or concatenate stacking strategies, including deep neural network, automatic feature interaction learning via self-attentive neural networks, deep factorization machine, compressed interaction network, and linear neural network, then adopted the best trial to generate a final approach. SHapley Additive exPlanations (SHAP) algorithm was applied to interpret ELISE, which was then validated in an independent test set.


  Result: Regarding prediction of responses to atezolizumab within esophageal adenocarcinoma (EAC) patients, ELISE demonstrated a superior accuracy (Area Under Curve [AUC] = 100.00%). AC005786.3 (Mean [|SHAP value|] = 0.0097) was distinguished as the most valuable contributor to ELISE output, followed by SNORD3D (0.0092), RN7SKP72 (0.0081), EREG (0.0069), IGHV4-80 (0.0063), and MIR4526 (0.0063). Mechanistically, immunoglobulin complex, immunoglobulin production, adaptive immune response, antigen binding and others, were downregulated in ELISE-neg EAC subtypes and resulted in unfavorable responses. More encouragingly, ELISE could be extended to accurately estimate the responsiveness of various immunotherapeutic agents against other cancers, including PD1/PD-L1 suppressor against metastatic urothelial cancer (AUC = 88.86%), and MAGE-A3 immunotherapy against metastatic melanoma (AUC = 100.00%).


  Discussion: This study presented deep insights into integrating ensemble deep learning with self-attention as a mechanism for predicting immunotherapy responses to human cancers, highlighting ELISE as a potential tool to generate reliable approaches to individualized treatment.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2022-12-01T11:17:21.815Z
---
