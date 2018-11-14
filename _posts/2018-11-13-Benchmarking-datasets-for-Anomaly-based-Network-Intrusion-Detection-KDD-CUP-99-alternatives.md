---
layout: post
title: "Benchmarking datasets for Anomaly-based Network Intrusion Detection: KDD CUP 99 alternatives"
date: 2018-11-13 15:49:54
categories: arXiv_AI
tags: arXiv_AI Classification Detection
author: Abhishek Divekar (1 and 5), Meet Parekh (2 and 5), Vaibhav Savla (3 and 5), Rudra Mishra (4 and 5), Mahesh Shirole (5) ((1) Amazon, (2) New York University, (3) Infosys, (4) Samsung, (5) Veermata Jijabai Technological Institute)
mathjax: true
---

* content
{:toc}

##### Abstract
Machine Learning has been steadily gaining traction for its use in Anomaly-based Network Intrusion Detection Systems (A-NIDS). Research into this domain is frequently performed using the KDD~CUP~99 dataset as a benchmark. Several studies question its usability while constructing a contemporary NIDS, due to the skewed response distribution, non-stationarity, and failure to incorporate modern attacks. In this paper, we compare the performance for KDD-99 alternatives when trained using classification models commonly found in literature: Neural Network, Support Vector Machine, Decision Tree, Random Forest, Naive Bayes and K-Means. Applying the SMOTE oversampling technique and random undersampling, we create a balanced version of NSL-KDD and prove that skewed target classes in KDD-99 and NSL-KDD hamper the efficacy of classifiers on minority classes (U2R and R2L), leading to possible security risks. We explore UNSW-NB15, a modern substitute to KDD-99 with greater uniformity of pattern distribution. We benchmark this dataset before and after SMOTE oversampling to observe the effect on minority performance. Our results indicate that classifiers trained on UNSW-NB15 match or better the Weighted F1-Score of those trained on NSL-KDD and KDD-99 in the binary case, thus advocating UNSW-NB15 as a modern substitute to these datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.05372](https://arxiv.org/abs/1811.05372)

##### PDF
[https://arxiv.org/pdf/1811.05372](https://arxiv.org/pdf/1811.05372)

