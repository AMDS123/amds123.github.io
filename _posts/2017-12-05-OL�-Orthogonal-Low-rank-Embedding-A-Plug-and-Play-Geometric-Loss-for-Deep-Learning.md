---
layout: post
title: 'OLÉ: Orthogonal Low-rank Embedding, A Plug and Play Geometric Loss for Deep Learning'
date: 2017-12-05 16:03:56
categories: arXiv_CV
tags: arXiv_CV GAN Deep_Learning Recognition
author: José Lezama, Qiang Qiu, Pablo Musé, Guillermo Sapiro
---

* content
{:toc}

##### Abstract
Deep neural networks trained using a softmax layer at the top and the cross-entropy loss are ubiquitous tools for image classification. Yet, this does not naturally enforce intra-class similarity nor inter-class margin of the learned deep representations. To simultaneously achieve these two goals, different solutions have been proposed in the literature, such as the pairwise or triplet losses. However, such solutions carry the extra task of selecting pairs or triplets, and the extra computational burden of computing and learning for many combinations of them. In this paper, we propose a plug-and-play loss term for deep networks that explicitly reduces intra-class variance and enforces inter-class margin simultaneously, in a simple and elegant geometric manner. For each class, the deep features are collapsed into a learned linear subspace, or union of them, and inter-class subspaces are pushed to be as orthogonal as possible. Our proposed Orthogonal Low-rank Embedding (OL\'E) does not require carefully crafting pairs or triplets of samples for training, and works standalone as a classification loss, being the first reported deep metric learning framework of its kind. Because of the improved margin between features of different classes, the resulting deep networks generalize better, are more discriminative, and more robust. We demonstrate improved classification performance in general object recognition, plugging the proposed loss term into existing off-the-shelf architectures. In particular, we show the advantage of the proposed loss in the small data/model scenario, and we significantly advance the state-of-the-art on the Stanford STL-10 benchmark.

##### Abstract (translated by Google)
使用顶部的softmax层和交叉熵损失训练的深度神经网络是图像分类的无处不在的工具。然而，这并不能自然而然地强化学习深度表达的类内相似性和类间边界。为了同时实现这两个目标，已经在文献中提出了不同的解决方案，例如成对或三重损失。然而，这样的解决方案承担了选择对或三元组的额外任务，并且为它们的许多组合计算和学习额外的计算负担。在本文中，我们提出了一个深度网络的即插即用损失项，明确减少了类内差异，并以一种简单而优雅的几何方式同时强化了类间的余量。对于每个类，深度特征被折叠成学习的线性子空间或它们的联合，并且类间子空间被推到尽可能正交。我们提出的正交低秩嵌入（OL \ E）并不需要仔细地对训练样本进行成对或三元训练，而是作为分类损失独立工作，是第一个被报告的深度量纲学习框架。由于不同类别的特征之间的差距有所改善，所以深层网络的泛化性能更好，更具有判别力，更强健。我们在一般的对象识别中表现出改进的分类性能，将建议的损失项插入到现有的现成架构中。特别是，我们展示了在小数据/模型情景下提出的损失的优势，并且我们大大提高了斯坦福大学STL-10基准测试的最新水平。

##### URL
[https://arxiv.org/abs/1712.01727](https://arxiv.org/abs/1712.01727)

