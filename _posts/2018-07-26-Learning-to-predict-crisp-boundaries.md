---
layout: post
title: "Learning to predict crisp boundaries"
date: 2018-07-26 12:40:36
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Detection
author: Ruoxi Deng, Chunhua Shen, Shengjun Liu, Huibing Wang, Xinru Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Recent methods for boundary or edge detection built on Deep Convolutional Neural Networks (CNNs) typically suffer from the issue of predicted edges being thick and need post-processing to obtain crisp boundaries. Highly imbalanced categories of boundary versus background in training data is one of main reasons for the above problem. In this work, the aim is to make CNNs produce sharp boundaries without post-processing. We introduce a novel loss for boundary detection, which is very effective for classifying imbalanced data and allows CNNs to produce crisp boundaries. Moreover, we propose an end-to-end network which adopts the bottom-up/top-down architecture to tackle the task. The proposed network effectively leverages hierarchical features and produces pixel-accurate boundary mask, which is critical to reconstruct the edge map. Our experiments illustrate that directly making crisp prediction not only promotes the visual results of CNNs, but also achieves better results against the state-of-the-art on the BSDS500 dataset (ODS F-score of .815) and the NYU Depth dataset (ODS F-score of .762).

##### Abstract (translated by Google)
最近基于深度卷积神经网络（CNN）的边界或边缘检测方法通常遭受预测边缘厚且需要后处理以获得清晰边界的问题。训练数据中高度不平衡的边界与背景类别是导致上述问题的主要原因之一。在这项工作中，目标是使CNN产生清晰的边界而无需后处理。我们引入了一种新的边界检测损失，这对于分类不平衡数据非常有效，并且允许CNN产生清晰的边界。此外，我们提出了一种端到端网络，它采用自下而上/自上而下的架构来处理任务。所提出的网络有效地利用分层特征并产生像素精确的边界掩模，这对于重建边缘图是至关重要的。我们的实验表明，直接进行清晰预测不仅可以促进CNN的视觉效果，而且可以在BSDS500数据集（ODS F-score为.815）和NYU Depth数据集（ ODS F-score为.762）。

##### URL
[http://arxiv.org/abs/1807.10097](http://arxiv.org/abs/1807.10097)

##### PDF
[http://arxiv.org/pdf/1807.10097](http://arxiv.org/pdf/1807.10097)

