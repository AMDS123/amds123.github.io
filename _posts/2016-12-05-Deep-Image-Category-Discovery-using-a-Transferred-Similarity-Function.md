---
layout: post
title: "Deep Image Category Discovery using a Transferred Similarity Function"
date: 2016-12-05 05:41:26
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Yen-Chang Hsu, Zhaoyang Lv, Zsolt Kira
mathjax: true
---

* content
{:toc}

##### Abstract
Automatically discovering image categories in unlabeled natural images is one of the important goals of unsupervised learning. However, the task is challenging and even human beings define visual categories based on a large amount of prior knowledge. In this paper, we similarly utilize prior knowledge to facilitate the discovery of image categories. We present a novel end-to-end network to map unlabeled images to categories as a clustering network. We propose that this network can be learned with contrastive loss which is only based on weak binary pair-wise constraints. Such binary constraints can be learned from datasets in other domains as transferred similarity functions, which mimic a simple knowledge transfer. We first evaluate our experiments on the MNIST dataset as a proof of concept, based on predicted similarities trained on Omniglot, showing a 99\% accuracy which significantly outperforms clustering based approaches. Then we evaluate the discovery performance on Cifar-10, STL-10, and ImageNet, which achieves both state-of-the-art accuracy and shows it can be scalable to various large natural images.

##### Abstract (translated by Google)
在未标记的自然图像中自动发现图像类别是无监督学习的重要目标之一。然而，这个任务是具有挑战性的，甚至人类都会根据大量的先验知识来定义视觉类别。在本文中，我们同样利用先验知识来促进图像类别的发现。我们提出了一种新颖的端到端网络，将未标记的图像作为聚类网络分类。我们建议，这个网络可以学习与对比损失，这只是基于弱二进制成对约束。这种二元约束可以从其他领域的数据集中学习，作为传递的相似度函数，模仿一个简单的知识转移。我们首先评估我们在MNIST数据集上的实验，作为概念证明，基于在Omniglot上训练的预测相似度，显示99％的准确度，这明显优于基于聚类的方法。然后，我们评估在Cifar-10，STL-10和ImageNet上的发现性能，它既达到了最新的精确度，又显示出可扩展到各种大型自然图像。

##### URL
[https://arxiv.org/abs/1612.01253](https://arxiv.org/abs/1612.01253)

##### PDF
[https://arxiv.org/pdf/1612.01253](https://arxiv.org/pdf/1612.01253)

