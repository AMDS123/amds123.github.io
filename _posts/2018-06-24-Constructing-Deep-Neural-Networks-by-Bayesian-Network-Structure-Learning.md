---
layout: post
title: "Constructing Deep Neural Networks by Bayesian Network Structure Learning"
date: 2018-06-24 13:05:06
categories: arXiv_AI
tags: arXiv_AI CNN Image_Classification Classification Relation
author: Raanan Y. Yehezkel Rohekar, Shami Nisimov, Guy Koren, Yaniv Gurwicz, Gal Novik
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a principled approach for unsupervised structure learning of deep neural networks. We propose a new interpretation for depth and inter-layer connectivity where conditional independencies in the input distribution are encoded hierarchically in the network structure. Thus, the depth of the network is determined inherently (equal to the maximal order of independence in the input distribution). The proposed method casts the problem of neural network structure learning as a problem of Bayesian network structure learning. Then, instead of directly learning the discriminative structure, it learns a generative graph, constructs its stochastic inverse, and then constructs a discriminative graph. We prove that conditional-dependency relations among the latent variables in the generative graph are preserved in the class-conditional discriminative graph. We demonstrate on image classification benchmarks that the deepest layers (convolutional and dense) of common networks can be replaced by significantly smaller learned structures, while maintaining classification accuracy---state-of-the-art on tested benchmarks. Our structure learning algorithm requires a small computational cost and runs efficiently on a standard desktop CPU.

##### Abstract (translated by Google)
我们介绍了一种用于深度神经网络的无监督结构学习的原理方法。我们对深度和层间连接提出了新的解释，其中输入分布中的条件独立性在网络结构中分层编码。因此，网络的深度固有地确定（等于输入分布中的最大独立顺序）。该方法将神经网络结构学习问题作为贝叶斯网络结构学习的一个问题。然后，它不是直接学习辨别结构，而是学习一个生成图，构造它的随机逆，然后构造一个判别图。我们证明了生成图中潜在变量之间的条件依赖关系保存在类条件判别图中。我们在图像分类基准上展示了常见网络的最深层（卷积和密集）可以被显着更小的学习结构所取代，同时保持分类准确性---最新的测试基准。我们的结构学习算法需要很小的计算成本，并且可以在标准桌面CPU上高效运行。

##### URL
[http://arxiv.org/abs/1806.09141](http://arxiv.org/abs/1806.09141)

##### PDF
[http://arxiv.org/pdf/1806.09141](http://arxiv.org/pdf/1806.09141)

