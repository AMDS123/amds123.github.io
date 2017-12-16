---
layout: post
title: "Gaussian Prototypical Networks for Few-Shot Learning on Omniglot"
date: 2017-08-09 06:53:31
categories: arXiv_CV
tags: arXiv_CV Embedding Classification
author: Stanislav Fort
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel architecture for $k$-shot classification on the Omniglot dataset. Building on prototypical networks, we extend their architecture to what we call Gaussian prototypical networks. Prototypical networks learn a map between images and embedding vectors, and use their clustering for classification. In our model, a part of the encoder output is interpreted as a confidence region estimate about the embedding point, and expressed as a Gaussian covariance matrix. Our network then constructs a direction and class dependent distance metric on the embedding space, using uncertainties of individual data points as weights. We show that Gaussian prototypical networks are a preferred architecture over vanilla prototypical networks with an equivalent number of parameters. We report state-of-the-art performance in 1-shot and 5-shot classification both in 5-way and 20-way regime (for 5-shot 5-way, we are comparable to previous state-of-the-art) on the Omniglot dataset. We explore artificially down-sampling a fraction of images in the training set, which improves our performance even further. We therefore hypothesize that Gaussian prototypical networks might perform better in less homogeneous, noisier datasets, which are commonplace in real world applications.

##### Abstract (translated by Google)
我们为Omniglot数据集上的$ k $ -shot分类提出了一种新颖的架构。在原型网络的基础上，我们将其架构扩展到我们所说的高斯原型网络。原型网络学习图像和嵌入向量之间的映射，并使用它们的聚类进行分类。在我们的模型中，编码器输出的一部分被解释为关于嵌入点的置信区域估计，并表示为高斯协方差矩阵。然后我们的网络在嵌入空间上构建一个方向和类别相关距离度量，使用单个数据点的不确定性作为权重。我们表明，高斯原型网络是一个首选的架构，香草原型网络与相当数量的参数。我们报告了在5路和20路方式下的1路和5路分类的最先进的性能（对于5路5路，我们可以比较先前的最新技术）在Omniglot数据集上。我们在训练集中人为地探测一小部分图像，这进一步提高了我们的表现。因此，我们假设高斯原型网络可能在较不均匀，噪音较大的数据集中表现更好，这在现实世界的应用中是司空见惯的。

##### URL
[https://arxiv.org/abs/1708.02735](https://arxiv.org/abs/1708.02735)

##### PDF
[https://arxiv.org/pdf/1708.02735](https://arxiv.org/pdf/1708.02735)

