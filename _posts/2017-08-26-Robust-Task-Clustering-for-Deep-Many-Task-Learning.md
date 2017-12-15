---
layout: post
title: "Robust Task Clustering for Deep Many-Task Learning"
date: 2017-08-26 02:29:50
categories: arXiv_CL
tags: arXiv_CL Sentiment Sentiment_Classification Classification Deep_Learning
author: Mo Yu, Xiaoxiao Guo, Jinfeng Yi, Shiyu Chang, Saloni Potdar, Gerald Tesauro, Haoyu Wang, Bowen Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate task clustering for deep-learning based multi-task and few-shot learning in a many-task setting. We propose a new method to measure task similarities with cross-task transfer performance matrix for the deep learning scenario. Although this matrix provides us critical information regarding similarity between tasks, its asymmetric property and unreliable performance scores can affect conventional clustering methods adversely. Additionally, the uncertain task-pairs, i.e., the ones with extremely asymmetric transfer scores, may collectively mislead clustering algorithms to output an inaccurate task-partition. To overcome these limitations, we propose a novel task-clustering algorithm by using the matrix completion technique. The proposed algorithm constructs a partially-observed similarity matrix based on the certainty of cluster membership of the task-pairs. We then use a matrix completion algorithm to complete the similarity matrix. Our theoretical analysis shows that under mild constraints, the proposed algorithm will perfectly recover the underlying "true" similarity matrix with a high probability. Our results show that the new task clustering method can discover task clusters for training flexible and superior neural network models in a multi-task learning setup for sentiment classification and dialog intent classification tasks. Our task clustering approach also extends metric-based few-shot learning methods to adapt multiple metrics, which demonstrates empirical advantages when the tasks are diverse.

##### Abstract (translated by Google)
我们研究任务聚类为基础的深度学习多任务和少量学习在多任务设置。我们提出了一种用于深度学习场景的跨任务转移性能矩阵来衡量任务相似度的新方法。虽然这个矩阵为我们提供了关于任务之间相似性的关键信息，但是它的不对称性和不可靠的性能分数可能会对传统的聚类方法产生不利影响。另外，不确定的任务对，即具有非常不对称的传输分数的任务对可能会共同误导聚类算法，以输出不准确的任务分区。为了克服这些限制，我们使用矩阵完成技术提出了一种新的任务聚类算法。该算法基于任务对的集群隶属度的确定性，构造了一个部分观测的相似度矩阵。然后我们使用矩阵完成算法来完成相似性矩阵。我们的理论分析表明，在温和的约束条件下，所提出的算法将以较高的概率完美地恢复潜在的“真实”相似度矩阵。我们的研究结果表明，新的任务聚类方法可以发现任务集群训练灵活和优越的神经网络模型的多任务学习设置情感分类和对话意图分类任务。我们的任务聚类方法还扩展了基于度量的少量学习方法，以适应多个度量标准，这证明了任务多样化时的经验优势。

##### URL
[https://arxiv.org/abs/1708.07918](https://arxiv.org/abs/1708.07918)

##### PDF
[https://arxiv.org/pdf/1708.07918](https://arxiv.org/pdf/1708.07918)

