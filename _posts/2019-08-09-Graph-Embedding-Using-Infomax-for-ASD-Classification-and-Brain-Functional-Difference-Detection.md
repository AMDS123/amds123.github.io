---
layout: post
title: "Graph Embedding Using Infomax for ASD Classification and Brain Functional Difference Detection"
date: 2019-08-09 05:25:46
categories: arXiv_CV
tags: arXiv_CV Regularization Embedding Classification Detection
author: Xiaoxiao Li, Nicha C. Dvornek, Juntang Zhuang, Pamela Ventola, James Duncana
mathjax: true
---

* content
{:toc}

##### Abstract
Significant progress has been made using fMRI to characterize the brain changes that occur in ASD, a complex neuro-developmental disorder. However, due to the high dimensionality and low signal-to-noise ratio of fMRI, embedding informative and robust brain regional fMRI representations for both graph-level classification and region-level functional difference detection tasks between ASD and healthy control (HC) groups is difficult. Here, we model the whole brain fMRI as a graph, which preserves geometrical and temporal information and use a Graph Neural Network (GNN) to learn from the graph-structured fMRI data. We investigate the potential of including mutual information (MI) loss (Infomax), which is an unsupervised term encouraging large MI of each nodal representation and its corresponding graph-level summarized representation to learn a better graph embedding. Specifically, this work developed a pipeline including a GNN encoder, a classifier and a discriminator, which forces the encoded nodal representations to both benefit classification and reveal the common nodal patterns in a graph. We simultaneously optimize graph-level classification loss and Infomax. We demonstrated that Infomax graph embedding improves classification performance as a regularization term. Furthermore, we found separable nodal representations of ASD and HC groups in prefrontal cortex, cingulate cortex, visual regions, and other social, emotional and execution related brain regions. In contrast with GNN with classification loss only, the proposed pipeline can facilitate training more robust ASD classification models. Moreover, the separable nodal representations can detect the functional differences between the two groups and contribute to revealing new ASD biomarkers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04769](http://arxiv.org/abs/1908.04769)

##### PDF
[http://arxiv.org/pdf/1908.04769](http://arxiv.org/pdf/1908.04769)

