---
layout: post
title: "Compressing Convolutional Neural Networks"
date: 2015-06-14 23:16:40
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Wenlin Chen, James T. Wilson, Stephen Tyree, Kilian Q. Weinberger, Yixin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNN) are increasingly used in many areas of computer vision. They are particularly attractive because of their ability to "absorb" great quantities of labeled data through millions of parameters. However, as model sizes increase, so do the storage and memory requirements of the classifiers. We present a novel network architecture, Frequency-Sensitive Hashed Nets (FreshNets), which exploits inherent redundancy in both convolutional layers and fully-connected layers of a deep learning model, leading to dramatic savings in memory and storage consumption. Based on the key observation that the weights of learned convolutional filters are typically smooth and low-frequency, we first convert filter weights to the frequency domain with a discrete cosine transform (DCT) and use a low-cost hash function to randomly group frequency parameters into hash buckets. All parameters assigned the same hash bucket share a single value learned with standard back-propagation. To further reduce model size we allocate fewer hash buckets to high-frequency components, which are generally less important. We evaluate FreshNets on eight data sets, and show that it leads to drastically better compressed performance than several relevant baselines.

##### Abstract (translated by Google)
卷积神经网络（CNN）越来越多地用于计算机视觉领域。它们特别具有吸引力，因为它们能够通过数百万个参数“吸收”大量标记的数据。但是，随着模型大小的增加，分类器的存储和内存要求也会增加。我们提出了一种新颖的网络体系结构 - 频率敏感散列网络（FreshNets），它利用卷积层和深度学习模型的完全连接层的固有冗余，从而显着节省存储和存储消耗。基于学习卷积滤波器的权重通常是平滑和低频的关键观察，我们首先利用离散余弦变换（DCT）将滤波器权重转换到频域，并且使用低成本哈希函数来随机地分组频率参数到哈希桶。所有分配相同散列桶的参数共享使用标准反向传播学习的单个值。为了进一步减少模型的大小，我们把更少的散列桶分配给高频分量，这通常不那么重要。我们评估FreshNets八个数据集，并显示它导致比几个相关的基线显着更好的压缩性能。

##### URL
[https://arxiv.org/abs/1506.04449](https://arxiv.org/abs/1506.04449)

##### PDF
[https://arxiv.org/pdf/1506.04449](https://arxiv.org/pdf/1506.04449)

