---
layout: post
title: "Spectral Learning for Supervised Topic Models"
date: 2016-02-19 02:07:20
categories: arXiv_SD
tags: arXiv_SD Review Inference
author: Yong Ren, Yining Wang, Jun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised topic models simultaneously model the latent topic structure of large collections of documents and a response variable associated with each document. Existing inference methods are based on variational approximation or Monte Carlo sampling, which often suffers from the local minimum defect. Spectral methods have been applied to learn unsupervised topic models, such as latent Dirichlet allocation (LDA), with provable guarantees. This paper investigates the possibility of applying spectral methods to recover the parameters of supervised LDA (sLDA). We first present a two-stage spectral method, which recovers the parameters of LDA followed by a power update method to recover the regression model parameters. Then, we further present a single-phase spectral algorithm to jointly recover the topic distribution matrix as well as the regression weights. Our spectral algorithms are provably correct and computationally efficient. We prove a sample complexity bound for each algorithm and subsequently derive a sufficient condition for the identifiability of sLDA. Thorough experiments on synthetic and real-world datasets verify the theory and demonstrate the practical effectiveness of the spectral algorithms. In fact, our results on a large-scale review rating dataset demonstrate that our single-phase spectral algorithm alone gets comparable or even better performance than state-of-the-art methods, while previous work on spectral methods has rarely reported such promising performance.

##### Abstract (translated by Google)
受监督的主题模型同时模拟大型文档集合的潜在主题结构以及与每个文档相关的响应变量。现有的推理方法是基于变分近似或蒙特卡罗（Monte Carlo）采样，而这种采样经常受到局部最小缺陷的影响。已经应用光谱方法来学习无监督的主题模型，如潜在的Dirichlet分配（LDA），并提供可证明的保证。本文研究了应用谱方法恢复监督LDA（sLDA）参数的可能性。我们首先提出了一个两阶段谱方法，它恢复了LDA的参数，然后是一个功率更新方法来恢复回归模型参数。然后，我们进一步提出一个单相光谱算法来共同恢复主题分布矩阵以及回归权重。我们的光谱算法证明是正确的，计算效率高。我们证明了每个算法的样本复杂度，并且随后为sLDA的可识别性导出了一个充分的条件。对合成和现实世界的数据集进行彻底的实验验证了理论，并证明了谱算法的实际有效性。实际上，我们在大规模综述评级数据库上的结果表明，我们的单相光谱算法本身就比现有技术方法具有可比性甚至更好的性能，而以前在光谱方法方面的工作很少报道如此有希望的性能。

##### URL
[https://arxiv.org/abs/1602.06025](https://arxiv.org/abs/1602.06025)

##### PDF
[https://arxiv.org/pdf/1602.06025](https://arxiv.org/pdf/1602.06025)

