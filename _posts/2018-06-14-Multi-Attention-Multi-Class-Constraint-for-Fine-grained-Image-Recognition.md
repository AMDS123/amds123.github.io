---
layout: post
title: "Multi-Attention Multi-Class Constraint for Fine-grained Image Recognition"
date: 2018-06-14 05:45:22
categories: arXiv_CV
tags: arXiv_CV Attention CNN Relation Recognition
author: Ming Sun, Yuchen Yuan, Feng Zhou, Errui Ding
mathjax: true
---

* content
{:toc}

##### Abstract
Attention-based learning for fine-grained image recognition remains a challenging task, where most of the existing methods treat each object part in isolation, while neglecting the correlations among them. In addition, the multi-stage or multi-scale mechanisms involved make the existing methods less efficient and hard to be trained end-to-end. In this paper, we propose a novel attention-based convolutional neural network (CNN) which regulates multiple object parts among different input images. Our method first learns multiple attention region features of each input image through the one-squeeze multi-excitation (OSME) module, and then apply the multi-attention multi-class constraint (MAMC) in a metric learning framework. For each anchor feature, the MAMC functions by pulling same-attention same-class features closer, while pushing different-attention or different-class features away. Our method can be easily trained end-to-end, and is highly efficient which requires only one training stage. Moreover, we introduce Dogs-in-the-Wild, a comprehensive dog species dataset that surpasses similar existing datasets by category coverage, data volume and annotation quality. This dataset will be released upon acceptance to facilitate the research of fine-grained image recognition. Extensive experiments are conducted to show the substantial improvements of our method on four benchmark datasets.

##### Abstract (translated by Google)
用于细粒度图像识别的基于注意力的学习仍然是一项具有挑战性的任务，其中大多数现有方法都是孤立地处理每个对象部分，而忽略它们之间的相关性。此外，所涉及的多阶段或多阶段机制使得现有方法的效率降低，难以接受端对端培训。在本文中，我们提出了一种新颖的基于注意力的卷积神经网络（CNN），它调节不同输入图像中的多个对象部分。我们的方法首先通过单挤压多激励（OSME）模块学习每个输入图像的多个关注区域特征，然后将多注意多类别约束（MAMC）应用于度量学习框架。对于每个锚点特征，MAMC通过拉近相同类型的同类特征来实现功能，同时推动不同类别的特征或不同类别的特征。我们的方法可以很容易地进行端到端培训，而且效率很高，只需要一个培训阶段。此外，我们还引入了一种综合性的狗物种数据集“野狗 - 数据集”，该数据集按类别覆盖率，数据量和注释质量超越了类似的现有数据集。该数据集将在接受后发布，以促进细粒度图像识别的研究。我们进行了大量的实验来展示我们的方法在四个基准数据集上的实质性改进。

##### URL
[http://arxiv.org/abs/1806.05372](http://arxiv.org/abs/1806.05372)

##### PDF
[http://arxiv.org/pdf/1806.05372](http://arxiv.org/pdf/1806.05372)

