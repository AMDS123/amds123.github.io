---
layout: post
title: "Semi-Supervised Learning via Compact Latent Space Clustering"
date: 2018-06-07 13:41:56
categories: arXiv_CV
tags: arXiv_CV Regularization Embedding Optimization Inference
author: Konstantinos Kamnitsas, Daniel C. Castro, Loic Le Folgoc, Ian Walker, Ryutaro Tanno, Daniel Rueckert, Ben Glocker, Antonio Criminisi, Aditya Nori
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel cost function for semi-supervised learning of neural networks that encourages compact clustering of the latent space to facilitate separation. The key idea is to dynamically create a graph over embeddings of labeled and unlabeled samples of a training batch to capture underlying structure in feature space, and use label propagation to estimate its high and low density regions. We then devise a cost function based on Markov chains on the graph that regularizes the latent space to form a single compact cluster per class, while avoiding to disturb existing clusters during optimization. We evaluate our approach on three benchmarks and compare to state-of-the art with promising results. Our approach combines the benefits of graph-based regularization with efficient, inductive inference, does not require modifications to a network architecture, and can thus be easily applied to existing networks to enable an effective use of unlabeled data.

##### Abstract (translated by Google)
我们提出了一个新的神经网络半监督学习的成本函数，鼓励潜在空间紧凑聚类，以促进分离。关键的想法是动态创建一个训练批次的已标记和未标记样本的嵌入图，以捕获特征空间中的基础结构，并使用标签传播来估计其高密度区域和低密度区域。然后，我们设计一个基于马尔可夫链的成本函数来规范潜在空间，从而形成每个类的单个紧凑集群，同时避免在优化过程中干扰现有集群。我们在三个基准上评估我们的方法，并与具有前景的结果进行比较。我们的方法结合了基于图形的正则化与高效归纳推理的优点，不需要修改网络架构，因此可以轻松应用到现有网络，以便有效使用未标记的数据。

##### URL
[http://arxiv.org/abs/1806.02679](http://arxiv.org/abs/1806.02679)

##### PDF
[http://arxiv.org/pdf/1806.02679](http://arxiv.org/pdf/1806.02679)

