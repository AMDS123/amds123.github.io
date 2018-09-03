---
layout: post
title: "Revisiting Deep Intrinsic Image Decompositions"
date: 2018-08-31 16:05:29
categories: arXiv_CV
tags: arXiv_CV Knowledge Optimization Deep_Learning
author: Qingnan Fan, Jiaolong Yang, Gang Hua, Baoquan Chen, David Wipf
mathjax: true
---

* content
{:toc}

##### Abstract
While invaluable for many computer vision applications, decomposing a natural image into intrinsic reflectance and shading layers represents a challenging, underdetermined inverse problem. As opposed to strict reliance on conventional optimization or filtering solutions with strong prior assumptions, deep learning based approaches have also been proposed to compute intrinsic image decompositions when granted access to sufficient labeled training data. The downside is that current data sources are quite limited, and broadly speaking fall into one of two categories: either dense fully-labeled images in synthetic/narrow settings, or weakly-labeled data from relatively diverse natural scenes. In contrast to many previous learning-based approaches, which are often tailored to the structure of a particular dataset (and may not work well on others), we adopt core network structures that universally reflect loose prior knowledge regarding the intrinsic image formation process and can be largely shared across datasets. We then apply flexibly supervised loss layers that are customized for each source of ground truth labels. The resulting deep architecture achieves state-of-the-art results on all of the major intrinsic image benchmarks, and runs considerably faster than most at test time.

##### Abstract (translated by Google)
虽然对于许多计算机视觉应用而言是非常宝贵的，但是将自然图像分解成固有反射率和阴影层代表了具有挑战性的，未确定的反问题。与严格依赖具有强预先假设的传统优化或滤波解决方案相反，还提出了基于深度学习的方法，以在被授权访问足够的标记训练数据时计算内在图像分解。缺点是当前的数据来源非常有限，从广义上讲，它属于两个类别之一：合成/窄设置中的密集全标记图像，或来自相对多样化的自然场景的弱标记数据。与之前许多基于学习的方法相比，这些方法通常适合特定数据集的结构（并且可能不适用于其他数据集），我们采用核心网络结构，普遍反映关于内在图像形成过程的松散先验知识，并且能够主要在数据集之间共享。然后，我们应用为每个地面实况标签源定制的灵活监督损失层。由此产生的深层架构在所有主要的固有图像基准测试中实现了最先进的结果，并且在测试时的运行速度远远超过大多数。

##### URL
[http://arxiv.org/abs/1701.02965](http://arxiv.org/abs/1701.02965)

##### PDF
[http://arxiv.org/pdf/1701.02965](http://arxiv.org/pdf/1701.02965)

