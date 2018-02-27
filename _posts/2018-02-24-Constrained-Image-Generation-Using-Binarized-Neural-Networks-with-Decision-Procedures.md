---
layout: post
title: "Constrained Image Generation Using Binarized Neural Networks with Decision Procedures"
date: 2018-02-24 04:12:30
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Svyatoslav Korneev, Nina Narodytska, Luca Pulina, Armando Tacchella, Nikolaj Bjorner, Mooly Sagiv
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of binary image generation with given properties. This problem arises in a number of practical applications, including generation of artificial porous medium for an electrode of lithium-ion batteries, for composed materials, etc. A generated image represents a porous medium and, as such, it is subject to two sets of constraints: topological constraints on the structure and process constraints on the physical process over this structure. To perform image generation we need to define a mapping from a porous medium to its physical process parameters. For a given geometry of a porous medium, this mapping can be done by solving a partial differential equation (PDE). However, embedding a PDE solver into the search procedure is computationally expensive. We use a binarized neural network to approximate a PDE solver. This allows us to encode the entire problem as a logical formula. Our main contribution is that, for the first time, we show that this problem can be tackled using decision procedures. Our experiments show that our model is able to produce random constrained images that satisfy both topological and process constraints.

##### Abstract (translated by Google)
我们考虑具有给定属性的二值图像生成问题。这个问题在许多实际应用中产生，包括用于锂离子电池的电极的人造多孔介质的生成，用于组成材料等。生成的图像表示多孔介质，并且因此它受到两组约束：对结构上的物理过程的结构和过程约束的拓扑约束。为了执行图像生成，我们需要定义从多孔介质到其物理过程参数的映射。对于给定的多孔介质几何形状，可以通过求解偏微分方程（PDE）来完成此映射。但是，将PDE解算器嵌入搜索过程的计算量很大。我们使用二值化神经网络来逼近PDE解算器。这使我们能够将整个问题编码为一个逻辑公式。我们的主要贡献是，我们第一次表明可以通过决策程序解决这个问题。我们的实验表明，我们的模型能够产生满足拓扑和过程约束的随机约束图像。

##### URL
[http://arxiv.org/abs/1802.08795](http://arxiv.org/abs/1802.08795)

##### PDF
[http://arxiv.org/pdf/1802.08795](http://arxiv.org/pdf/1802.08795)

