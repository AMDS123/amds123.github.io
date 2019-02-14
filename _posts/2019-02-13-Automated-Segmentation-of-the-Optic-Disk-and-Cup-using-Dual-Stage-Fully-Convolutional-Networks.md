---
layout: post
title: "Automated Segmentation of the Optic Disk and Cup using Dual-Stage Fully Convolutional Networks"
date: 2019-02-13 02:29:59
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Deep_Learning Prediction Detection
author: Lei Bi, Yuyu Guo, Qian Wang, Dagan Feng, Michael Fulham, Jinman Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Automated segmentation of the optic cup and disk on retinal fundus images is fundamental for the automated detection / analysis of glaucoma. Traditional segmentation approaches depend heavily upon hand-crafted features and a priori knowledge of the user. As such, these methods are difficult to be adapt to the clinical environment. Recently, deep learning methods based on fully convolutional networks (FCNs) have been successful in resolving segmentation problems. However, the reliance on large annotated training data is problematic when dealing with medical images. If a sufficient amount of annotated training data to cover all possible variations is not available, FCNs do not provide accurate segmentation. In addition, FCNs have a large receptive field in the convolutional layers, and hence produce coarse outputs of boundaries. Hence, we propose a new fully automated method that we refer to as a dual-stage fully convolutional networks (DSFCN). Our approach leverages deep residual architectures and FCNs and learns and infers the location of the optic cup and disk in a step-wise manner with fine-grained details. During training, our approach learns from the training data and the estimated results derived from the previous iteration. The ability to learn from the previous iteration optimizes the learning of the optic cup and the disk boundaries. During testing (prediction), DSFCN uses test (input) images and the estimated probability map derived from previous iterations to gradually improve the segmentation accuracy. Our method achieved an average Dice co-efficient of 0.8488 and 0.9441 for optic cup and disk segmentation and an area under curve (AUC) of 0.9513 for glaucoma detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04713](http://arxiv.org/abs/1902.04713)

##### PDF
[http://arxiv.org/pdf/1902.04713](http://arxiv.org/pdf/1902.04713)

