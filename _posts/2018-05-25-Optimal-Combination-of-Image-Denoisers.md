---
layout: post
title: "Optimal Combination of Image Denoisers"
date: 2018-05-25 20:53:40
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Joon Hee Choi, Omar Elgendy, Stanley H. Chan
mathjax: true
---

* content
{:toc}

##### Abstract
Given a set of image denoisers, each having a different denoising capability, is there a provably optimal way of combining these denoisers to produce an overall better result? An answer to this question is fundamental to designing ensembles of weak estimators for complex scenes. In this paper, we present an optimal procedure leveraging deep neural networks and convex optimization. The proposed framework, called the Consensus Neural Network (CsNet), introduces three new concepts in image denoising: (1) A deep neural network to estimate the mean squared error (MSE) of denoised images without needing the ground truths; (2) A provably optimal procedure to combine the denoised outputs via convex optimization; (3) An image boosting procedure using a deep neural network to improve contrast and to recover lost details of the combined images. Experimental results show that CsNet can consistently improve denoising performance for both deterministic and neural network denoisers.

##### Abstract (translated by Google)
给定一组图像分解器，每个分解器都具有不同的去噪能力，是否有一种将这些分解器合并以产生总体较好结果的可行的最佳方法？这个问题的答案对于设计复杂场景弱估计量的集合很重要。在本文中，我们提出了一个利用深度神经网络和凸优化的最优过程。所提出的框架称为共识神经网络（CsNet），它引入了三个新的图像去噪概念：（1）深度神经网络，用于估计去噪图像的均方差（MSE），而不需要基本事实; （2）通过凸优化来组合经去噪的输出的可证明的最佳程序; （3）使用深度神经网络来提高对比度并恢复组合图像的丢失细节的图像增强过程。实验结果表明，CsNet可以持续提高确定性和神经网络分解器的去噪性能。

##### URL
[http://arxiv.org/abs/1711.06712](http://arxiv.org/abs/1711.06712)

##### PDF
[http://arxiv.org/pdf/1711.06712](http://arxiv.org/pdf/1711.06712)

