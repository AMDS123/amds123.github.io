---
layout: post
title: "Graph Neural Network for Interpreting Task-fMRI Biomarkers"
date: 2019-07-02 21:43:43
categories: arXiv_CV
tags: arXiv_CV Classification
author: Xiaoxiao Li, Nicha C. Dvornek, Yuan Zhou, Juntang Zhuang, Pamela Ventola, James S. Duncan
mathjax: true
---

* content
{:toc}

##### Abstract
Finding the biomarkers associated with ASD is helpful for understanding the underlying roots of the disorder and can lead to earlier diagnosis and more targeted treatment. A promising approach to identify biomarkers is using Graph Neural Networks (GNNs), which can be used to analyze graph structured data, i.e. brain networks constructed by fMRI. One way to interpret important features is through looking at how the classification probability changes if the features are occluded or replaced. The major limitation of this approach is that replacing values may change the distribution of the data and lead to serious errors. Therefore, we develop a 2-stage pipeline to eliminate the need to replace features for reliable biomarker interpretation. Specifically, we propose an inductive GNN to embed the graphs containing different properties of task-fMRI for identifying ASD and then discover the brain regions/sub-graphs used as evidence for the GNN classifier. We first show GNN can achieve high accuracy in identifying ASD. Next, we calculate the feature importance scores using GNN and compare the interpretation ability with Random Forest. Finally, we run with different atlases and parameters, proving the robustness of the proposed method. The detected biomarkers reveal their association with social behaviors. We also show the potential of discovering new informative biomarkers. Our pipeline can be generalized to other graph feature importance interpretation problems.1

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01661](http://arxiv.org/abs/1907.01661)

##### PDF
[http://arxiv.org/pdf/1907.01661](http://arxiv.org/pdf/1907.01661)

