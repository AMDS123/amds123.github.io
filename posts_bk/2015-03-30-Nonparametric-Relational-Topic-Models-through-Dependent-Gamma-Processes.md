---
layout: post
title: "Nonparametric Relational Topic Models through Dependent Gamma Processes"
date: 2015-03-30 05:40:41
categories: arXiv_CL
tags: arXiv_CL Knowledge GAN Inference Prediction Relation
author: Junyu Xuan, Jie Lu, Guangquan Zhang, Richard Yi Da Xu, Xiangfeng Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional Relational Topic Models provide a way to discover the hidden topics from a document network. Many theoretical and practical tasks, such as dimensional reduction, document clustering, link prediction, benefit from this revealed knowledge. However, existing relational topic models are based on an assumption that the number of hidden topics is known in advance, and this is impractical in many real-world applications. Therefore, in order to relax this assumption, we propose a nonparametric relational topic model in this paper. Instead of using fixed-dimensional probability distributions in its generative model, we use stochastic processes. Specifically, a gamma process is assigned to each document, which represents the topic interest of this document. Although this method provides an elegant solution, it brings additional challenges when mathematically modeling the inherent network structure of typical document network, i.e., two spatially closer documents tend to have more similar topics. Furthermore, we require that the topics are shared by all the documents. In order to resolve these challenges, we use a subsampling strategy to assign each document a different gamma process from the global gamma process, and the subsampling probabilities of documents are assigned with a Markov Random Field constraint that inherits the document network structure. Through the designed posterior inference algorithm, we can discover the hidden topics and its number simultaneously. Experimental results on both synthetic and real-world network datasets demonstrate the capabilities of learning the hidden topics and, more importantly, the number of topics.

##### Abstract (translated by Google)
传统的关系主题模型提供了一种从文档网络中发现隐藏主题的方法。许多理论和实践任务，如降维，文档聚类，链接预测，受益于这个显示的知识。然而，现有的关系型主题模型是基于一个假设，即隐藏主题的数量是事先已知的，而这在许多实际应用中是不切实际的。因此，为了放宽这个假设，本文提出了一个非参数关系主题模型。我们使用随机过程而不是在其生成模型中使用固定维概率分布。具体来说，伽玛过程分配给每个文件，这代表了这个文件的主题兴趣。虽然这种方法提供了一个优雅的解决方案，但是在对典型文档网络的固有网络结构进行数学建模时，也就是说两个空间上更接近的文档倾向于具有更相似的主题，这带来了额外的挑战此外，我们要求所有的文件共享这些话题。为了解决这些挑战，我们使用二次采样策略为每个文档分配一个与全局伽玛过程不同的伽玛过程，文档的二次采样概率被赋予一个继承文档网络结构的马尔可夫随机场约束。通过设计的后验推理算法，可以同时发现隐藏的主题和数量。综合和现实世界的网络数据集的实验结果表明了学习隐藏话题的能力，更重要的是，话题的数量。

##### URL
[https://arxiv.org/abs/1503.08542](https://arxiv.org/abs/1503.08542)

##### PDF
[https://arxiv.org/pdf/1503.08542](https://arxiv.org/pdf/1503.08542)

