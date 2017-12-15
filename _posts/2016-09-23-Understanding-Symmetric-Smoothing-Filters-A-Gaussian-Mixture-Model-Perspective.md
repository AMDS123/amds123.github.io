---
layout: post
title: "Understanding Symmetric Smoothing Filters: A Gaussian Mixture Model Perspective"
date: 2016-09-23 02:10:56
categories: arXiv_CV
tags: arXiv_CV
author: Stanley H. Chan, Todd Zickler, Yue M. Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Many patch-based image denoising algorithms can be formulated as applying a smoothing filter to the noisy image. Expressed as matrices, the smoothing filters must be row normalized so that each row sums to unity. Surprisingly, if we apply a column normalization before the row normalization, the performance of the smoothing filter can often be significantly improved. Prior works showed that such performance gain is related to the Sinkhorn-Knopp balancing algorithm, an iterative procedure that symmetrizes a row-stochastic matrix to a doubly-stochastic matrix. However, a complete understanding of the performance gain phenomenon is still lacking. In this paper, we study the performance gain phenomenon from a statistical learning perspective. We show that Sinkhorn-Knopp is equivalent to an Expectation-Maximization (EM) algorithm of learning a Gaussian mixture model of the image patches. By establishing the correspondence between the steps of Sinkhorn-Knopp and the EM algorithm, we provide a geometrical interpretation of the symmetrization process. This observation allows us to develop a new denoising algorithm called Gaussian mixture model symmetric smoothing filter (GSF). GSF is an extension of the Sinkhorn-Knopp and is a generalization of the original smoothing filters. Despite its simple formulation, GSF outperforms many existing smoothing filters and has a similar performance compared to several state-of-the-art denoising algorithms.

##### Abstract (translated by Google)
许多基于块的图像去噪算法可以被表述为对噪声图像应用平滑滤波器。用矩阵表示，平滑滤波器必须进行行归一化，以使每一行相加为1。令人惊讶的是，如果我们在行归一化之前应用列归一化，平滑滤波器的性能往往会得到显着的改善。先前的工作表明，这种性能增益与Sinkhorn-Knopp平衡算法有关，该算法是将行 - 随机矩阵对称为双随机矩阵的迭代过程。然而，对性能增益现象的完整理解仍然不足。在本文中，我们从统计学习的角度来研究性能增益现象。我们证明Sinkhorn-Knopp相当于一个期望最大化（EM）学习图像块的高斯混合模型的算法。通过建立Sinkhorn-Knopp步骤与EM算法之间的对应关系，我们提供了对称化过程的几何解释。这个观察允许我们开发一种称为高斯混合模型对称平滑滤波器（GSF）的新的去噪算法。 GSF是Sinkhorn-Knopp的扩展，是原始平滑滤波器的推广。尽管其表述简单，GSF却胜过了许多现有的平滑滤波器，并且与几种最先进的去噪算法相比具有相似的性能。

##### URL
[https://arxiv.org/abs/1601.00088](https://arxiv.org/abs/1601.00088)

##### PDF
[https://arxiv.org/pdf/1601.00088](https://arxiv.org/pdf/1601.00088)

