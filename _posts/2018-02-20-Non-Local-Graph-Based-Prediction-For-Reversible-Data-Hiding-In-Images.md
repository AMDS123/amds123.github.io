---
layout: post
title: "Non-Local Graph-Based Prediction For Reversible Data Hiding In Images"
date: 2018-02-20 02:28:51
categories: arXiv_CV
tags: arXiv_CV Embedding Prediction Gradient_Descent
author: Qi Chang, Gene Cheung, Yao Zhao, Xiaolong Li, Rongrong Ni
mathjax: true
---

* content
{:toc}

##### Abstract
Reversible data hiding (RDH) is desirable in applications where both the hidden message and the cover medium need to be recovered without loss. Among many RDH approaches is prediction-error expansion (PEE), containing two steps: i) prediction of a target pixel value, and ii) embedding according to the value of prediction-error. In general, higher prediction performance leads to larger embedding capacity and/or lower signal distortion. Leveraging on recent advances in graph signal processing (GSP), we pose pixel prediction as a graph-signal restoration problem, where the appropriate edge weights of the underlying graph are computed using a similar patch searched in a semi-local neighborhood. Specifically, for each candidate patch, we first examine eigenvalues of its structure tensor to estimate its local smoothness. If sufficiently smooth, we pose a maximum a posteriori (MAP) problem using either a quadratic Laplacian regularizer or a graph total variation (GTV) term as signal prior. While the MAP problem using the first prior has a closed-form solution, we design an efficient algorithm for the second prior using alternating direction method of multipliers (ADMM) with nested proximal gradient descent. Experimental results show that with better quality GSP-based prediction, at low capacity the visual quality of the embedded image exceeds state-of-the-art methods noticeably.

##### Abstract (translated by Google)
在隐藏消息和封面媒体都需要被恢复而没有丢失的应用中，可逆数据隐藏（RDH）是理想的。在许多RDH方法中，预测误差扩展（PEE）包含两个步骤：i）预测目标像素值，以及ii）根据预测误差的值进行嵌入。一般来说，较高的预测性能会导致较大的嵌入容量和/或较低的信号失真。利用图形信号处理（GSP）的最新进展，我们将像素预测视为图形信号恢复问题，其中使用在半局部邻域中搜索到的相似斑块来计算底层图的适当边缘权重。具体而言，对于每个候选贴片，我们首先检查其结构张量的特征值以估计其局部平滑度。如果足够平滑，我们使用二次拉普拉斯正则化器或图形总变差（GTV）作为先验信号来构成最大后验（MAP）问题。虽然使用第一个先验的MAP问题具有封闭形式的解决方案，但我们使用交替方向乘法器（ADMM）和嵌套近端梯度下降为第二个先验设计了一种有效的算法。实验结果表明，以更高质量的基于GSP的预测，在低容量下，嵌入图像的视觉质量明显超过最先进的方法。

##### URL
[http://arxiv.org/abs/1802.06935](http://arxiv.org/abs/1802.06935)

##### PDF
[http://arxiv.org/pdf/1802.06935](http://arxiv.org/pdf/1802.06935)

