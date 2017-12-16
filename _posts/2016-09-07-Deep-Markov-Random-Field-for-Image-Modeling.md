---
layout: post
title: "Deep Markov Random Field for Image Modeling"
date: 2016-09-07 15:56:36
categories: arXiv_CV
tags: arXiv_CV RNN
author: Zhirong Wu, Dahua Lin, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Markov Random Fields (MRFs), a formulation widely used in generative image modeling, have long been plagued by the lack of expressive power. This issue is primarily due to the fact that conventional MRFs formulations tend to use simplistic factors to capture local patterns. In this paper, we move beyond such limitations, and propose a novel MRF model that uses fully-connected neurons to express the complex interactions among pixels. Through theoretical analysis, we reveal an inherent connection between this model and recurrent neural networks, and thereon derive an approximated feed-forward network that couples multiple RNNs along opposite directions. This formulation combines the expressive power of deep neural networks and the cyclic dependency structure of MRF in a unified model, bringing the modeling capability to a new level. The feed-forward approximation also allows it to be efficiently learned from data. Experimental results on a variety of low-level vision tasks show notable improvement over state-of-the-arts.

##### Abstract (translated by Google)
马尔可夫随机场（MRF）是一种广泛用于生成图像建模的公式，长期以来一直受到缺乏表达能力的困扰。这个问题主要是因为传统的MRF公式倾向于使用简单的因子来捕获局部模式。在本文中，我们超越了这种限制，提出了一种新的MRF模型，它使用全连接的神经元来表示像素之间复杂的相互作用。通过理论分析，揭示了该模型与递归神经网络之间的内在联系，并在此基础上推导出一个近似的前馈网络，将多个RNNs沿相反方向耦合。该公式将深层神经网络的表现力与MRF的循环依赖结构统一在一个模型中，将建模能力提高到一个新的水平。前馈近似也可以有效地从数据中学习。在各种低级视觉任务上的实验结果显示出比现有技术有显着的提高。

##### URL
[https://arxiv.org/abs/1609.02036](https://arxiv.org/abs/1609.02036)

##### PDF
[https://arxiv.org/pdf/1609.02036](https://arxiv.org/pdf/1609.02036)

