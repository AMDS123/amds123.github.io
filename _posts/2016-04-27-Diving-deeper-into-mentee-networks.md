---
layout: post
title: "Diving deeper into mentee networks"
date: 2016-04-27 20:05:45
categories: arXiv_CV
tags: arXiv_CV Image_Caption Regularization CNN
author: Ragav Venkatesan, Baoxin Li
mathjax: true
---

* content
{:toc}

##### Abstract
Modern computer vision is all about the possession of powerful image representations. Deeper and deeper convolutional neural networks have been built using larger and larger datasets and are made publicly available. A large swath of computer vision scientists use these pre-trained networks with varying degrees of successes in various tasks. Even though there is tremendous success in copying these networks, the representational space is not learnt from the target dataset in a traditional manner. One of the reasons for opting to use a pre-trained network over a network learnt from scratch is that small datasets provide less supervision and require meticulous regularization, smaller and careful tweaking of learning rates to even achieve stable learning without weight explosion. It is often the case that large deep networks are not portable, which necessitates the ability to learn mid-sized networks from scratch. In this article, we dive deeper into training these mid-sized networks on small datasets from scratch by drawing additional supervision from a large pre-trained network. Such learning also provides better generalization accuracies than networks trained with common regularization techniques such as l2, l1 and dropouts. We show that features learnt thus, are more general than those learnt independently. We studied various characteristics of such networks and found some interesting behaviors.

##### Abstract (translated by Google)
现代计算机视觉就是拥有强大的图像表现力。越来越深的卷积神经网络已经使用越来越大的数据集建立起来，并被公之于众。一大批计算机视觉科学家使用这些预先训练的网络，在各种任务中取得不同程度的成功。尽管在复制这些网络方面取得了巨大的成功，但并不是以传统的方式从目标数据集中学习代表性空间。选择在网络上使用预先训练好的网络的原因之一是从小规模的数据集提供更少的监督和要求细致正规化，更小和仔细调整学习率，甚至实现稳定的学习，而不会发生体重爆炸。大型深度网络通常是不可移植的，因此需要从头开始学习中型网络的能力。在这篇文章中，我们更深入地从一个大的预训练网络中抽取额外的监督，从头开始在小数据集上训练这些中型网络。这种学习还提供了比使用常规正则化技术（例如l2，l1和辍学）训练的网络更好的泛化精度。我们展示了这样学习的特性，比那些独立学习的更普遍。我们研究了这种网络的各种特征，并发现了一些有趣的行为

##### URL
[https://arxiv.org/abs/1604.08220](https://arxiv.org/abs/1604.08220)

##### PDF
[https://arxiv.org/pdf/1604.08220](https://arxiv.org/pdf/1604.08220)

