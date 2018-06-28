---
layout: post
title: "Efficient Neural Architecture Search with Network Morphism"
date: 2018-06-27 03:18:35
categories: arXiv_AI
tags: arXiv_AI Attention Optimization
author: Haifeng Jin, Qingquan Song, Xia Hu
mathjax: true
---

* content
{:toc}

##### Abstract
While neural architecture search (NAS) has drawn increasing attention for automatically tuning deep neural networks, existing search algorithms usually suffer from expensive computational cost. Network morphism, which keeps the functionality of a neural network while changing its neural architecture, could be helpful for NAS by enabling a more efficient training during the search. However, network morphism based NAS is still computationally expensive due to the inefficient process of selecting the proper morph operation for existing architectures. As we know, Bayesian optimization has been widely used to optimize functions based on a limited number of observations, motivating us to explore the possibility of making use of Bayesian optimization to accelerate the morph operation selection process. In this paper, we propose a novel framework enabling Bayesian optimization to guide the network morphism for efficient neural architecture search by introducing a neural network kernel and a tree-structured acquisition function optimization algorithm. With Bayesian optimization to select the network morphism operations, the exploration of the search space is more efficient. Moreover, we carefully wrapped our method into an open-source software, namely Auto-Keras for people without rich machine learning background to use. Intensive experiments on real-world datasets have been done to demonstrate the superior performance of the developed framework over the state-of-the-art baseline methods.

##### Abstract (translated by Google)
虽然神经架构搜索（NAS）已经引起越来越多的关注自动调谐深度神经网络，但现有的搜索算法通常会遭受昂贵的计算成本。网络态度，在改变神经架构的同时保持神经网络的功能，可以帮助NAS在搜索过程中实现更高效的训练。然而，由于为现有体系结构选择适当的变形操作的效率低下，基于网络态射的NAS仍然在计算上昂贵。正如我们所知，贝叶斯优化已被广泛用于基于有限数量的观测来优化函数，这激励我们探索利用贝叶斯优化来加速变形操作选择过程的可能性。在本文中，我们提出了一种新的框架，通过引入神经网络核和树形结构采集函数优化算法，使贝叶斯优化能够指导网络态射以进行有效的神经架构搜索。通过贝叶斯优化来选择网络态射操作，搜索空间的探索更加高效。此外，我们将我们的方法精心包装成一个开源软件，即Auto-Keras，适用于没有丰富机器学习背景的人使用。已经完成了对现实世界数据集的深入实验，以证明所开发的框架相对于最先进的基准方法的优越性能。

##### URL
[http://arxiv.org/abs/1806.10282](http://arxiv.org/abs/1806.10282)

##### PDF
[http://arxiv.org/pdf/1806.10282](http://arxiv.org/pdf/1806.10282)

