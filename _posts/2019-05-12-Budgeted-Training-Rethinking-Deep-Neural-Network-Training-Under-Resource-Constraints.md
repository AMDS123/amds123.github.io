---
layout: post
title: "Budgeted Training: Rethinking Deep Neural Network Training Under Resource Constraints"
date: 2019-05-12 17:49:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation NAS Image_Classification Semantic_Segmentation Optimization Video_Classification Classification Detection
author: Mengtian Li, Ersin Yumer, Deva Ramanan
mathjax: true
---

* content
{:toc}

##### Abstract
In most practical settings and theoretical analysis, one assumes that a model can be trained until convergence. However, the growing complexity of machine learning datasets and models may violate such assumptions. Moreover, current approaches for hyper-parameter tuning and neural architecture search tend to be limited by practical resource constraints. Therefore, we introduce a formal setting for studying training under the non-asymptotic, resource-constrained regime, i.e. budgeted training. We analyze the following problem: "given a dataset, algorithm, and resource budget, what is the best achievable performance?" We focus on the number of optimization iterations as the representative resource. Under such a setting, we show that it is critical to adjust the learning rate schedule according to the given budget. Among budget-aware learning schedules, we find simple linear decay to be both robust and high-performing. We support our claim through extensive experiments with state-of-the-art models on ImageNet (image classification), Cityscapes (semantic segmentation), MS COCO (object detection and instance segmentation), and Kinetics (video classification). We also analyze our results and find that the key to a good schedule is budgeted convergence, a phenomenon whereby the gradient vanishes at the end of each allowed budget. We also revisit existing approaches for fast convergence, and show that budget-aware learning schedules readily outperform such approaches under (the practical but under-explored) budgeted setting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04753](http://arxiv.org/abs/1905.04753)

##### PDF
[http://arxiv.org/pdf/1905.04753](http://arxiv.org/pdf/1905.04753)

