---
layout: post
title: "Auxiliary Tasks in Multi-task Learning"
date: 2018-05-16 13:59:20
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation CNN Semantic_Segmentation NMT
author: Lukas Liebel, Marco K&#xf6;rner
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-task convolutional neural networks (CNNs) have shown impressive results for certain combinations of tasks, such as single-image depth estimation (SIDE) and semantic segmentation. This is achieved by pushing the network towards learning a robust representation that generalizes well to different atomic tasks. We extend this concept by adding auxiliary tasks, which are of minor relevance for the application, to the set of learned tasks. As a kind of additional regularization, they are expected to boost the performance of the ultimately desired main tasks. To study the proposed approach, we picked vision-based road scene understanding (RSU) as an exemplary application. Since multi-task learning requires specialized datasets, particularly when using extensive sets of tasks, we provide a multi-modal dataset for multi-task RSU, called synMT. More than 2.5 $\cdot$ 10^5 synthetic images, annotated with 21 different labels, were acquired from the video game Grand Theft Auto V (GTA V). Our proposed deep multi-task CNN architecture was trained on various combination of tasks using synMT. The experiments confirmed that auxiliary tasks can indeed boost network performance, both in terms of final results and training time.

##### Abstract (translated by Google)
多任务卷积神经网络（CNNs）对于某些任务组合（如单图像深度估计（SIDE）和语义分割）显示出令人印象深刻的结果。这是通过推动网络学习强大的表示来实现的，这种表示可以很好地适应不同的原子任务。我们通过向学习任务集添加与应用程序关系不大的辅助任务来扩展此概念。作为一种额外的正规化，它们有望提高最终期望的主要任务的性能。为了研究所提出的方法，我们选择基于视觉的道路场景理解（RSU）作为示例应用。由于多任务学习需要专门的数据集，特别是在使用大量任务时，我们提供多任务RSU的多模式数据集，称为synMT。从视频游戏Grand Theft Auto V（GTA V）获得超过2.5 $ \ cdot $ 10 ^ 5合成图像，注有21种不同的标签。我们提出的深度多任务CNN架构是通过使用synMT的各种任务组合来训练的。实验证实，辅助任务确实可以提高网络性能，无论是最终结果还是训练时间。

##### URL
[http://arxiv.org/abs/1805.06334](http://arxiv.org/abs/1805.06334)

##### PDF
[http://arxiv.org/pdf/1805.06334](http://arxiv.org/pdf/1805.06334)

