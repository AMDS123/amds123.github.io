---
layout: post
title: "Learning Proximal Operators: Using Denoising Networks for Regularizing Inverse Imaging Problems"
date: 2017-08-30 11:22:33
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Optimization Deep_Learning Relation
author: Tim Meinhardt, Michael Moeller, Caner Hazirbas, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
While variational methods have been among the most powerful tools for solving linear inverse problems in imaging, deep (convolutional) neural networks have recently taken the lead in many challenging benchmarks. A remaining drawback of deep learning approaches is their requirement for an expensive retraining whenever the specific problem, the noise level, noise type, or desired measure of fidelity changes. On the contrary, variational methods have a plug-and-play nature as they usually consist of separate data fidelity and regularization terms. In this paper we study the possibility of replacing the proximal operator of the regularization used in many convex energy minimization algorithms by a denoising neural network. The latter therefore serves as an implicit natural image prior, while the data term can still be chosen independently. Using a fixed denoising neural network in exemplary problems of image deconvolution with different blur kernels and image demosaicking, we obtain state-of-the-art reconstruction results. These indicate the high generalizability of our approach and a reduction of the need for problem-specific training. Additionally, we discuss novel results on the analysis of possible optimization algorithms to incorporate the network into, as well as the choices of algorithm parameters and their relation to the noise level the neural network is trained on.

##### Abstract (translated by Google)
虽然变分方法已经成为解决成像中的线性逆问题的最强大的工具之一，但是深度（卷积）神经网络最近在许多具有挑战性的基准中处于领先地位。深度学习方法的另一个缺点是，只要具体问题，噪声级别，噪声类型或所需的保真度度量发生变化，就需要进行昂贵的再训练。相反，变分方法具有即插即用特性，因为它们通常由单独的数据保真度和正则化项组成。在本文中，我们研究了用降噪神经网络代替许多凸能量最小化算法中使用的正则化算子的可能性。因此后者作为一个隐含的自然图像，而数据项仍然可以独立选择。使用固定的去噪神经网络在具有不同模糊核的图像去卷积和图像去马赛克的示例性问题中，我们获得了最先进的重建结果。这些表明了我们的方法具有很高的普遍性，减少了针对特定问题培训的需求。另外，我们讨论了分析可能的优化算法的新颖结果，以将网络纳入，以及选择算法参数及其与神经网络训练的噪声水平的关系。

##### URL
[https://arxiv.org/abs/1704.03488](https://arxiv.org/abs/1704.03488)

##### PDF
[https://arxiv.org/pdf/1704.03488](https://arxiv.org/pdf/1704.03488)

