---
layout: post
title: "Prior-aware Neural Network for Partially-Supervised Multi-Organ Segmentation"
date: 2019-04-12 17:57:40
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation GAN Gradient_Descent
author: Yuyin Zhou, Zhe Li, Song Bai, Chong Wang, Xinlei Chen, Mei Han, Elliot Fishman, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate multi-organ abdominal CT segmentation is essential to many clinical applications such as computer-aided intervention. As data annotation requires massive human labor from experienced radiologists, it is common that training data are partially labeled, e.g., pancreas datasets only have the pancreas labeled while leaving the rest marked as background. However, these background labels can be misleading in multi-organ segmentation since the "background" usually contains some other organs of interest. To address the background ambiguity in these partially-labeled datasets, we propose Prior-aware Neural Network (PaNN) via explicitly incorporating anatomical priors on abdominal organ sizes, guiding the training process with domain-specific knowledge. More specifically, PaNN assumes that the average organ size distributions in the abdomen should approximate their empirical distributions, a prior statistics obtained from the fully-labeled dataset. As our training objective is difficult to be directly optimized using stochastic gradient descent [20], we propose to reformulate it in a min-max form and optimize it via the stochastic primal-dual gradient algorithm. PaNN achieves state-of-the-art performance on the MICCAI2015 challenge "Multi-Atlas Labeling Beyond the Cranial Vault", a competition on organ segmentation in the abdomen. We report an average Dice score of 84.97%, surpassing the prior art by a large margin of 3.27%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06346](http://arxiv.org/abs/1904.06346)

##### PDF
[http://arxiv.org/pdf/1904.06346](http://arxiv.org/pdf/1904.06346)

