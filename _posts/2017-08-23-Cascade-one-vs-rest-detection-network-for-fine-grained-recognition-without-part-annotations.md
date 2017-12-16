---
layout: post
title: "Cascade one-vs-rest detection network for fine-grained recognition without part annotations"
date: 2017-08-23 07:05:42
categories: arXiv_CV
tags: arXiv_CV Detection Recognition
author: Long Chen, Junyu Dong, ShengKe Wang, Kin-Man Lam, Muwei Jian, Hua Zhang, XiaoChun Cao
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-grained recognition is a challenging task due to the small intra-category variances. Most of top-performing fine-grained recognition methods leverage parts of objects for better performance. Therefore, part annotations which are extremely computationally expensive are required. In this paper, we propose a novel cascaded deep CNN detection framework for fine-grained recognition which is trained to detect the whole object without considering parts. Nevertheless, most of current top-performing detection networks use the N+1 class (N object categories plus background) softmax loss, and the background category with much more training samples dominates the feature learning progress so that the features are not good for object categories with fewer samples. To bridge this gap, we introduce a cascaded structure to eliminate background and exploit a one-vs-rest loss to capture more minute variances among different subordinate categories. Experiments show that our proposed recognition framework achieves comparable performance with state-of-the-art, part-free, fine-grained recognition methods on the CUB-200-2011 Bird dataset. Moreover, our method even outperforms most of part-based methods while does not need part annotations at the training stage and is free from any annotations at test stage.

##### Abstract (translated by Google)
细粒度识别是一个具有挑战性的任务，由于类别内部的差异很小。大多数高性能的细粒度识别方法利用部分对象来获得更好的性能。因此，需要计算上非常昂贵的部分注释。在本文中，我们提出了一种新的级联深度CNN检测框架，用于细粒度识别，可以在不考虑零件的情况下对整个对象进行检测。然而，当前大多数表现最好的检测网络使用N + 1类（N个对象类别加上背景）softmax损失，并且具有更多训练样本的背景类别主导特征学习进度，使得特征对于对象类别更少的样本。为了弥补这个差距，我们引入了一个级联结构来消除背景，并利用一对一的损失来捕获不同的下属类别之间更多的微小差异。实验表明，我们提出的识别框架在CUB-200-2011鸟类数据集上实现了与先进的，部分自由的，细粒度的识别方法相媲美的性能。此外，我们的方法甚至胜过大多数基于部件的方法，而在训练阶段不需要部分注释，并且在测试阶段没有任何注释。

##### URL
[https://arxiv.org/abs/1702.08692](https://arxiv.org/abs/1702.08692)

##### PDF
[https://arxiv.org/e-print/1702.08692](https://arxiv.org/e-print/1702.08692)

