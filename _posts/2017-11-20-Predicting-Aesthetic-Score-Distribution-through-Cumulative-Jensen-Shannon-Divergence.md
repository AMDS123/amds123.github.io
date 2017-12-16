---
layout: post
title: "Predicting Aesthetic Score Distribution through Cumulative Jensen-Shannon Divergence"
date: 2017-11-20 20:12:21
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Prediction
author: Xin Jin, Le Wu, Xiaodong Li, Siyu Chen, Siwei Peng, Jingying Chi, Shiming Ge, Chenggen Song, Geng Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Aesthetic quality prediction is a challenging task in the computer vision community because of the complex interplay with semantic contents and photographic technologies. Recent studies on the powerful deep learning based aesthetic quality assessment usually use a binary high-low label or a numerical score to represent the aesthetic quality. However the scalar representation cannot describe well the underlying varieties of the human perception of aesthetics. In this work, we propose to predict the aesthetic score distribution (i.e., a score distribution vector of the ordinal basic human ratings) using Deep Convolutional Neural Network (DCNN). Conventional DCNNs which aim to minimize the difference between the predicted scalar numbers or vectors and the ground truth cannot be directly used for the ordinal basic rating distribution. Thus, a novel CNN based on the Cumulative distribution with Jensen-Shannon divergence (CJS-CNN) is presented to predict the aesthetic score distribution of human ratings, with a new reliability-sensitive learning method based on the kurtosis of the score distribution, which eliminates the requirement of the original full data of human ratings (without normalization). Experimental results on large scale aesthetic dataset demonstrate the effectiveness of our introduced CJS-CNN in this task.

##### Abstract (translated by Google)
美学质量预测在计算机视觉领域是一个具有挑战性的任务，因为它与语义内容和摄影技术的复杂的相互作用。最近对强大的基于深度学习的美学质量评估的研究通常使用二元高低标签或数值分数来表示美学质量。然而，标量表示不能很好地描述人类对美学的感受。在这项工作中，我们建议使用深度卷积神经网络（DCNN）来预测审美评分分布（即，序数基本人类评分的评分分布向量）。旨在最小化预测的标量数或矢量与基本事实之间差异的常规DCNN不能直接用于序数基本评级分布。因此，本文提出了一种基于Jensen-Shannon散度累积分布（CJS-CNN）的CNN新型CNN预测人体评分的美学评分分布，提出了一种基于分数峰度的新型可靠性敏感学习方法，消除了人类评级的原始完整数据的要求（没有标准化）。大规模美学数据集的实验结果证明了我们引入的CJS-CNN在这项任务中的有效性。

##### URL
[https://arxiv.org/abs/1708.07089](https://arxiv.org/abs/1708.07089)

##### PDF
[https://arxiv.org/pdf/1708.07089](https://arxiv.org/pdf/1708.07089)

