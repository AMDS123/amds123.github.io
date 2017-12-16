---
layout: post
title: "What You Expect is NOT What You Get! Questioning Reconstruction/Classification Correlation of Stacked Convolutional Auto-Encoder Features"
date: 2017-05-31 07:51:08
categories: arXiv_CV
tags: arXiv_CV CNN Classification Relation
author: Michele Alberti, Mathias Seuret, Rolf Ingold, Marcus Liwicki (University Of Fribourg, Fribourg, Switzerland)
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we thoroughly investigate the quality of features produced by deep neural network architectures obtained by stacking and convolving Auto-Encoders. In particular, we are interested into the relation of their reconstruction score with their performance on document layout analysis. When using Auto-Encoders, intuitively one could assume that features which are good for reconstruction will also lead to high classification accuracies. However, we prove that this is not always the case. We examine the reconstruction score, training error and the results obtained if we were to use the same features for both input reconstruction and a classification task. We show that the reconstruction score is not a good metric because it is biased by the decoder quality. Furthermore, experimental results suggest that there is no correlation between the reconstruction score and the quality of features for a classification task and that given the network size and configuration it is not possible to make assumptions on its training error magnitude. Therefore we conclude that both, reconstruction score and training error should not be used jointly to evaluate the quality of the features produced by a Stacked Convolutional Auto-Encoders for a classification task. Consequently one should independently investigate the network classification abilities directly.

##### Abstract (translated by Google)
在本文中，我们深入研究了通过堆栈和卷积自动编码器获得的深度神经网络结构产生的特征的质量。我们特别感兴趣的是他们的重建分数与他们在文档布局分析上的表现之间的关系。当使用自动编码器时，可以直观地假设有利于重建的特征也将导致高分类精度。但是，我们证明这并非总是如此。我们检查重建分数，训练误差和如果我们要使用相同的功能进行输入重建和分类任务获得的结果。我们表明，重建分数是不是一个好的指标，因为它是由解码器的质量偏见。此外，实验结果表明重建分数与分类任务的特征质量之间没有相关性，并且考虑到网络的大小和配置，不可能对其训练误差幅度进行假设。因此，我们得出结论：重建分数和训练误差不应该联合使用来评估堆叠卷积自动编码器为分类任务产生的特征的质量。因此应该直接独立调查网络分类能力。

##### URL
[https://arxiv.org/abs/1703.04332](https://arxiv.org/abs/1703.04332)

##### PDF
[https://arxiv.org/pdf/1703.04332](https://arxiv.org/pdf/1703.04332)

