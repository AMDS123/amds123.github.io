---
layout: post
title: "Auto-Meta: Automated Gradient Based Meta Learner Search"
date: 2018-06-11 04:28:02
categories: arXiv_AI
tags: arXiv_AI Knowledge Classification
author: Jaehong Kim, Youngduck Choi, Moonsu Cha, Jung Kwon Lee, Sangyeul Lee, Sungwan Kim, Yongseok Choi, Jiwon Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Fully automating machine learning pipeline is one of the outstanding challenges of general artificial intelligence, as practical machine learning often requires costly human driven process, such as hyper-parameter tuning, algorithmic selection, and model selection. In this work, we consider the problem of executing automated, yet scalable search for finding optimal gradient based meta-learners in practice. As a solution, we apply progressive neural architecture search to proto-architectures by appealing to the model agnostic nature of general gradient based meta learners. In the presence of recent universality result of Finn \textit{et al.}\cite{finn:universality_maml:DBLP:/journals/corr/abs-1710-11622}, our search is a priori motivated in that neural network architecture search dynamics---automated or not---may be quite different from that of the classical setting with the same target tasks, due to the presence of the gradient update operator. A posteriori, our search algorithm, given appropriately designed search spaces, finds gradient based meta learners with non-intuitive proto-architectures that are narrowly deep, unlike the inception-like structures previously observed in the resulting architectures of traditional NAS algorithms. Along with these notable findings, the searched gradient based meta-learner achieves state-of-the-art results on the few shot classification problem on Mini-ImageNet with $76.29\%$ accuracy, which is an $13.18\%$ improvement over results reported in the original MAML paper. To our best knowledge, this work is the first successful AutoML implementation in the context of meta learning.

##### Abstract (translated by Google)
完全自动化机器学习管道是一般人工智能的突出挑战之一，因为实际的机器学习通常需要昂贵的人为驱动过程，例如超参数调整，算法选择和模型选择。在这项工作中，我们考虑在实践中执行自动化但可扩展的搜索以找到最佳渐变基元学习者的问题。作为一种解决方案，我们将渐进神经架构搜索应用于原始架构，吸引了基于一般梯度的元学习者的模型不可知性。在存在最近的普遍性结果的情况下，我们的搜索是在该神经网络结构搜索动力学中的先验动机---自动化与否---可能与具有相同目标任务的经典设置完全不同，因为存在渐变更新操作符。后验，我们的搜索算法在给定适当设计的搜索空间的基础上，发现基于梯度的元学习者具有非直观的原始体系结构，这与原来在传统NAS算法的结构体系中观察到的初始结构不同。除了这些显着的发现之外，搜索到的基于渐变的元学习者在Mini-ImageNet上的少数镜头分类问题上获得了最新的结果，精确度为76.29美元/％，与结果报告相比，这是一个13.18美元/美元的改进在原来的MAML论文中。据我们所知，这项工作是元学习环境下首次成功的AutoML实现。

##### URL
[http://arxiv.org/abs/1806.06927](http://arxiv.org/abs/1806.06927)

##### PDF
[http://arxiv.org/pdf/1806.06927](http://arxiv.org/pdf/1806.06927)

