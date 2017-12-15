---
layout: post
title: "Convergence rates for pretraining and dropout: Guiding learning parameters using network structure"
date: 2017-02-22 17:32:07
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Vamsi K. Ithapu, Sathya Ravi, Vikas Singh
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised pretraining and dropout have been well studied, especially with respect to regularization and output consistency. However, our understanding about the explicit convergence rates of the parameter estimates, and their dependence on the learning (like denoising and dropout rate) and structural (like depth and layer lengths) aspects of the network is less mature. An interesting question in this context is to ask if the network structure could "guide" the choices of such learning parameters. In this work, we explore these gaps between network structure, the learning mechanisms and their interaction with parameter convergence rates. We present a way to address these issues based on the backpropagation convergence rates for general nonconvex objectives using first-order information. We then incorporate two learning mechanisms into this general framework -- denoising autoencoder and dropout, and subsequently derive the convergence rates of deep networks. Building upon these bounds, we provide insights into the choices of learning parameters and network sizes that achieve certain levels of convergence accuracy. The results derived here support existing empirical observations, and we also conduct a set of experiments to evaluate them.

##### Abstract (translated by Google)
无监督的训练和辍学得到了充分的研究，特别是在正规化和产出一致性方面。然而，我们对参数估计的显式收敛速度的理解，以及它们对网络学习（如去噪和丢失率）和结构（如深度和层长度）方面的依赖性还不太成熟。在这种情况下一个有趣的问题是询问网络结构是否可以“引导”这种学习参数的选择。在这项工作中，我们探讨了网络结构，学习机制及其与参数收敛速度的相互作用的差距。我们提出了一种方法来解决这些问题的基础上反向传播收敛率为一般非凸目标使用一阶信息。然后，我们将两个学习机制纳入这个总体框架 - 去噪自动编码器和丢失，并随后推导出深度网络的收敛速度。基于这些界限，我们提供洞察学习参数和网络大小的选择，达到一定水平的收敛精度。这里得到的结果支持现有的经验观察，我们也进行了一系列的实验来评估它们。

##### URL
[https://arxiv.org/abs/1506.03412](https://arxiv.org/abs/1506.03412)

##### PDF
[https://arxiv.org/e-print/1506.03412](https://arxiv.org/e-print/1506.03412)

