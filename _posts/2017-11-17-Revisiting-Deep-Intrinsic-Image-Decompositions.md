---
layout: post
title: "Revisiting Deep Intrinsic Image Decompositions"
date: 2017-11-17 04:15:21
categories: arXiv_CV
tags: arXiv_CV Knowledge Optimization Deep_Learning
author: Qingnan Fan, David Wipf, Jiaolong Yang, Gang Hua, Baoquan Chen
mathjax: true
---

* content
{:toc}

##### Abstract
While invaluable for many computer vision applications, decomposing a natural image into intrinsic reflectance and shading layers represents a challenging, underdetermined inverse problem. As opposed to strict reliance on conventional optimization or filtering solutions with strong prior assumptions, deep learning-based approaches have also been proposed to compute intrinsic image decompositions when granted access to sufficient labeled training data. The downside is that current data sources are quite limited, and broadly speaking fall into one of two categories: either dense fully-labeled images in synthetic/narrow settings, or weakly-labeled data from relatively diverse natural scenes. In contrast to many previous learning-based approaches, which are often tailored to the structure of a particular dataset (and may not work well on others), we adopt core network structures that universally reflect loose prior knowledge regarding the intrinsic image formation process and can be largely shared across datasets. We then apply flexibly supervised loss layers that are customized for each source of ground truth labels. The resulting deep architecture achieves state-of-the-art results on all of the major intrinsic image benchmarks, and runs considerably faster than most at test time.

##### Abstract (translated by Google)
虽然对于许多计算机视觉应用而言是无价的，但将自然图像分解为内在反射和遮蔽层是一个具有挑战性的欠定反演问题。与严格依赖传统优化或过滤性强的先验假设相比，深度学习的方法也被提出来计算固有图像分解时，准许访问足够的标记训练数据。缺点是目前的数据来源是相当有限的，广泛地说，归入两类之一：合成/狭义设置中的密集全标记图像或来自相对不同自然场景的弱标记数据。与以前许多基于学习的方法（通常是根据特定数据集的结构量身定做的（而且在其他方​​面可能效果不佳））相比，我们采用的核心网络结构普遍反映了有关内在图像形成过程的松散的先验知识，大部分在数据集之间共享。然后我们应用灵活的监督损失层为每个地面实况标签来源定制。由此产生的深层架构在所有主要的内在映像基准测试中都达到了最新的结果，而且在测试时运行速度比大多数要快得多。

##### URL
[https://arxiv.org/abs/1701.02965](https://arxiv.org/abs/1701.02965)

##### PDF
[https://arxiv.org/pdf/1701.02965](https://arxiv.org/pdf/1701.02965)

