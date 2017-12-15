---
layout: post
title: "Bethe Learning of Conditional Random Fields via MAP Decoding"
date: 2015-03-04 05:41:29
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Kui Tang, Nicholas Ruozzi, David Belanger, Tony Jebara
mathjax: true
---

* content
{:toc}

##### Abstract
Many machine learning tasks can be formulated in terms of predicting structured outputs. In frameworks such as the structured support vector machine (SVM-Struct) and the structured perceptron, discriminative functions are learned by iteratively applying efficient maximum a posteriori (MAP) decoding. However, maximum likelihood estimation (MLE) of probabilistic models over these same structured spaces requires computing partition functions, which is generally intractable. This paper presents a method for learning discrete exponential family models using the Bethe approximation to the MLE. Remarkably, this problem also reduces to iterative (MAP) decoding. This connection emerges by combining the Bethe approximation with a Frank-Wolfe (FW) algorithm on a convex dual objective which circumvents the intractable partition function. The result is a new single loop algorithm MLE-Struct, which is substantially more efficient than previous double-loop methods for approximate maximum likelihood estimation. Our algorithm outperforms existing methods in experiments involving image segmentation, matching problems from vision, and a new dataset of university roommate assignments.

##### Abstract (translated by Google)
许多机器学习任务可以通过预测结构化输出来制定。在诸如结构化支持向量机（SVM-Struct）和结构化感知器的框架中，通过迭代应用有效的最大后验（MAP）解码来学习判别函数。然而，在这些相同的结构化空间上的概率模型的最大似然估计（MLE）需要计算分区函数，这通常是棘手的。本文提出了一种使用Bethe逼近MLE来学习离散指数族模型的方法。值得注意的是，这个问题也减少到迭代（MAP）解码。这种联系通过结合Bethe逼近与Frank-Wolfe（FW）算法在凸双目标上的结合而产生，这避开了难以处理的分割函数。结果是新的单回路算法MLE-Struct，其比先前的双回路方法在近似最大似然估计方面实质上更高效。我们的算法在涉及图像分割，视觉匹配问题和大学室友分配的新数据集方面优于现有方法。

##### URL
[https://arxiv.org/abs/1503.01228](https://arxiv.org/abs/1503.01228)

##### PDF
[https://arxiv.org/pdf/1503.01228](https://arxiv.org/pdf/1503.01228)

