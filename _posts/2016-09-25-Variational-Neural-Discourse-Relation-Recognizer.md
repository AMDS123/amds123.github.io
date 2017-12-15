---
layout: post
title: "Variational Neural Discourse Relation Recognizer"
date: 2016-09-25 23:33:44
categories: arXiv_SD
tags: arXiv_SD Inference Relation Recognition
author: Biao Zhang, Deyi Xiong, Jinsong Su, Qun Liu, Rongrong Ji, Hong Duan, Min Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Implicit discourse relation recognition is a crucial component for automatic discourselevel analysis and nature language understanding. Previous studies exploit discriminative models that are built on either powerful manual features or deep discourse representations. In this paper, instead, we explore generative models and propose a variational neural discourse relation recognizer. We refer to this model as VarNDRR. VarNDRR establishes a directed probabilistic model with a latent continuous variable that generates both a discourse and the relation between the two arguments of the discourse. In order to perform efficient inference and learning, we introduce neural discourse relation models to approximate the prior and posterior distributions of the latent variable, and employ these approximated distributions to optimize a reparameterized variational lower bound. This allows VarNDRR to be trained with standard stochastic gradient methods. Experiments on the benchmark data set show that VarNDRR can achieve comparable results against stateof- the-art baselines without using any manual features.

##### Abstract (translated by Google)
隐性话语关系识别是自动话语分析和自然语言理解的重要组成部分。以前的研究利用基于强大的手动特征或深度话语表征的判别模型。在本文中，我们探索生成模型，并提出了一个变分神经话语关系识别器。我们把这个模型称为VarNDRR。 VarNDRR建立了一个带有潜在连续变量的有向概率模型，它产生了一个话语以及话语的两个论点之间的关系。为了进行有效的推理和学习，我们引入了神经话语关系模型来逼近潜变量的前后分布，并利用这些近似的分布来优化重新参数化的变分下界。这使VarNDRR可以用标准的随机梯度方法进行训练。在基准数据集上进行的实验表明，VarNDRR可以在不使用任何手动功能的情况下，与先进的基线实现可比较的结果。

##### URL
[https://arxiv.org/abs/1603.03876](https://arxiv.org/abs/1603.03876)

##### PDF
[https://arxiv.org/pdf/1603.03876](https://arxiv.org/pdf/1603.03876)

