---
layout: post
title: "Deep Spectral Descriptors: Learning the point-wise correspondence metric via Siamese deep neural networks"
date: 2017-10-17 16:26:04
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Zhiyu Sun, Yusen He, Andrey Gritsenko, Amaury Lendasse, Stephen Baek
mathjax: true
---

* content
{:toc}

##### Abstract
A robust and informative local shape descriptor plays an important role in mesh registration. In this regard, spectral descriptors that are based on the spectrum of the Laplace-Beltrami operator have gained a spotlight among the researchers for the last decade due to their desirable properties, such as isometry invariance. Despite such, however, spectral descriptors often fail to give a correct similarity measure for non-isometric cases where the metric distortion between the models is large. Hence, they are in general not suitable for the registration problems, except for the special cases when the models are near-isometry. In this paper, we investigate a way to develop shape descriptors for non-isometric registration tasks by embedding the spectral shape descriptors into a different metric space where the Euclidean distance between the elements directly indicates the geometric dissimilarity. We design and train a Siamese deep neural network to find such an embedding, where the embedded descriptors are promoted to rearrange based on the geometric similarity. We found our approach can significantly enhance the performance of the conventional spectral descriptors for the non-isometric registration tasks, and outperforms recent state-of-the-art method reported in literature.

##### Abstract (translated by Google)
一个健壮的和信息丰富的局部形状描述符在网格注册中起着重要的作用。在这方面，基于拉普拉斯 - 贝尔特拉米算子谱的光谱描述符在过去的十年中由于其诸如恒定不变等理想特性而在研究人员中引起了关注。但是，尽管如此，光谱描述符经常无法给出模型之间的度量失真很大的非等距情况的正确相似性度量。因此，除了模型接近等距的特殊情况外，它们通常不适用于注册问题。在本文中，我们通过将频谱形状描述符嵌入到不同的度量空间中来研究一种开发用于非等长配准任务的形状描述符的方法，其中元素之间的欧几里德距离直接指示几何不相似性。我们设计和训练一个连体深层神经网络来找到这样一个嵌入，嵌入的描述符根据几何相似性被提升为重新排列。我们发现我们的方法可以显着提高常规光谱描述符在非等距配准任务中的性能，并且超过了文献报道的最新的最先进的方法。

##### URL
[https://arxiv.org/abs/1710.06368](https://arxiv.org/abs/1710.06368)

##### PDF
[https://arxiv.org/pdf/1710.06368](https://arxiv.org/pdf/1710.06368)

