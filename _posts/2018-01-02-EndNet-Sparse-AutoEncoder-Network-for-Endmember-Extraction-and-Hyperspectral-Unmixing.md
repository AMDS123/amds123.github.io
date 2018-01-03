---
layout: post
title: "EndNet: Sparse AutoEncoder Network for Endmember Extraction and Hyperspectral Unmixing"
date: 2018-01-02 17:53:46
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Savas Ozkan, Berk Kaya, Ersin Esen, Gozde Bozdagi Akar
mathjax: true
---

* content
{:toc}

##### Abstract
Data acquired from multi-channel sensors is a highly valuable asset to interpret the environment for a variety of remote sensing applications. However, low spatial resolution is a critical limitation for the sensors and the constituent materials of a scene can be mixed in different fractions due to their spatial interactions. Spectral unmixing is a technique that allows us to obtain the material spectral signatures with their fractions from data. In this paper, we propose a novel hyperspectral unmixing scheme, called EndNet, that is based on a two-staged autoencoder network. This well-known structure is completely enhanced and restructured by introducing additional layers and a projection metric (i.e spectral angle distance (SAD) instead of inner product) to achieve an optimum solution. Moreover, we present a novel loss function that is composed of Kullback-Leibler divergence term with SAD similarity and additional penalty terms to improve the sparsity of the estimates. These modifications enable us to set the common properties of endmembers such as nonlinearity and sparsity for autoencoder networks. Lastly, due to the stochastic-gradient based approach, the method is scalable for large-scale data and it can be accelerated on Graphical Processing Units (GPUs). To demonstrate the superiority of our method, we conduct extensive experiments on several wellknown datasets. The obtained results confirm that our method considerably improves the performance compared to the state-of-the-art techniques in literature.

##### Abstract (translated by Google)
从多通道传感器获取的数据是解释各种遥感应用环境的非常有价值的资产。然而，低空间分辨率是传感器的关键限制，并且由于它们的空间相互作用，场景的构成材料可以在不同的分数中混合。光谱解混是一种技术，使我们能够从数据中获得物质光谱特征。在本文中，我们提出了一种基于两级自编码器网络的新型高光谱分解方案，称为EndNet。通过引入附加层和投影度量（即光谱角距离（SAD）而不是内部产品），这种众所周知的结构被完全增强和重构，以实现最佳解决方案。此外，我们提出了一个新的损失函数，它由Kullback-Leibler散度项与SAD相似性和额外的惩罚项组成，以提高估计的稀疏性。这些修改使我们能够设置端元的共同特性，例如自编码器网络的非线性和稀疏性。最后，由于基于随机梯度的方法，该方法对于大规模数据是可扩展的，并且可以在图形处理单元（GPU）上加速。为了证明我们的方法的优越性，我们在几个众所周知的数据集上进行了广泛的实验。获得的结果证实，与文献中的最新技术相比，我们的方法显着改善了性能。

##### URL
[http://arxiv.org/abs/1708.01894](http://arxiv.org/abs/1708.01894)

##### PDF
[http://arxiv.org/pdf/1708.01894](http://arxiv.org/pdf/1708.01894)

