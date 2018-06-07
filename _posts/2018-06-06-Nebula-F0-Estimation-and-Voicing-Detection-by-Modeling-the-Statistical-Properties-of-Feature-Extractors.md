---
layout: post
title: "Nebula: F0 Estimation and Voicing Detection by Modeling the Statistical Properties of Feature Extractors"
date: 2018-06-06 11:55:58
categories: arXiv_SD
tags: arXiv_SD Detection
author: Kanru Hua
mathjax: true
---

* content
{:toc}

##### Abstract
A F0 and voicing status estimation algorithm for high quality speech analysis/synthesis is proposed. This problem is approached from a different perspective that models the behavior of feature extractors under noise, instead of directly modeling speech signals. Under time-frequency locality assumptions, the joint distribution of extracted features and target F0 can be characterized by training a bank of Gaussian mixture models (GMM) on artificial data generated from Monte-Carlo simulations. The trained GMMs can then be used to generate a set of conditional distributions on the predicted F0, which are then combined and post-processed by Viterbi algorithm to give a final F0 trajectory. Evaluation on CSTR and CMU Arctic speech databases shows that the proposed method, trained on fully synthetic data, achieves lower gross error rates than state-of-the-art methods.

##### Abstract (translated by Google)
提出了一种用于高质量语音分析/合成的F0和浊音状态估计算法。这个问题是从不同的角度来处理的，它模拟了噪声下特征提取器的行为，而不是直接建模语音信号。在时频局部性假设下，提取特征和目标F0的联合分布可以通过训练由Monte-Carlo模拟产生的人造数据的一组高斯混合模型（GMM）来表征。然后，训练好的GMM可以用来生成一组关于预测F0的条件分布，然后将这些分布进行组合并且通过维特比算法进行后处理以给出最终的F0轨迹。对CSTR和CMU北极语音数据库的评估表明，所提出的方法经过全面综合数据训练，与现有技术方法相比，实现了较低的粗差错率。

##### URL
[http://arxiv.org/abs/1710.11317](http://arxiv.org/abs/1710.11317)

##### PDF
[http://arxiv.org/pdf/1710.11317](http://arxiv.org/pdf/1710.11317)

