---
layout: post
title: "Unsupervised part learning for visual recognition"
date: 2017-04-12 13:35:03
categories: arXiv_CV
tags: arXiv_CV Image_Caption Image_Retrieval CNN Image_Classification Classification Recognition
author: Ronan Sicre, Yannis Avrithis, Ewa Kijak, Frederic Jurie
mathjax: true
---

* content
{:toc}

##### Abstract
Part-based image classification aims at representing categories by small sets of learned discriminative parts, upon which an image representation is built. Considered as a promising avenue a decade ago, this direction has been neglected since the advent of deep neural networks. In this context, this paper brings two contributions: first, it shows that despite the recent success of end-to-end holistic models, explicit part learning can boosts classification performance. Second, this work proceeds one step further than recent part-based models (PBM), focusing on how to learn parts without using any labeled data. Instead of learning a set of parts per class, as generally done in the PBM literature, the proposed approach both constructs a partition of a given set of images into visually similar groups, and subsequently learn a set of discriminative parts per group in a fully unsupervised fashion. This strategy opens the door to the use of PBM in new applications for which the notion of image categories is irrelevant, such as instance-based image retrieval, for example. We experimentally show that our learned parts can help building efficient image representations, for classification as well as for indexing tasks, resulting in performance superior to holistic state-of-the art Deep Convolutional Neural Networks (DCNN) encoding.

##### Abstract (translated by Google)
基于部分的图像分类的目的是通过一组学习的可辨识部分来表示类别，在其上构建图像表示。十年前被认为是一个有前途的途径，自从深度神经网络出现以来，这个方向一直被忽视。在此背景下，本文提出了两点贡献：首先，尽管最近端到端的整体模型取得了成功，但显式部分学习可以提高分类性能。其次，这项工作比最近的基于零件的模型（PBM）更进一步，重点是如何在不使用任何标记数据的情况下学习零件。所提出的方法不是像在PBM文献中通常所做的那样学习一组每个类别的部分，而是将给定的一组图像构建为视觉上相似的组，并随后在完全无监督下学习每组的一组判别性部分时尚。这种策略打开了在新的应用程序中使用PBM的大门，图像类别的概念是不相关的，比如基于实例的图像检索。我们通过实验表明，我们的学习部分可以帮助构建高效的图像表示，用于分类以及索引任务，从而导致性能优于整体先进的深度卷积神经网络（DCNN）编码。

##### URL
[https://arxiv.org/abs/1704.03755](https://arxiv.org/abs/1704.03755)

##### PDF
[https://arxiv.org/pdf/1704.03755](https://arxiv.org/pdf/1704.03755)

