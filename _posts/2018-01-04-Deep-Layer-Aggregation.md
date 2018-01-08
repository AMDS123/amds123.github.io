---
layout: post
title: "Deep Layer Aggregation"
date: 2018-01-04 05:45:30
categories: arXiv_CV
tags: arXiv_CV Attention CNN Inference Recognition
author: Fisher Yu, Dequan Wang, Evan Shelhamer, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Visual recognition requires rich representations that span levels from low to high, scales from small to large, and resolutions from fine to coarse. Even with the depth of features in a convolutional network, a layer in isolation is not enough: compounding and aggregating these representations improves inference of what and where. Architectural efforts are exploring many dimensions for network backbones, designing deeper or wider architectures, but how to best aggregate layers and blocks across a network deserves further attention. Although skip connections have been incorporated to combine layers, these connections have been "shallow" themselves, and only fuse by simple, one-step operations. We augment standard architectures with deeper aggregation to better fuse information across layers. Our deep layer aggregation structures iteratively and hierarchically merge the feature hierarchy to make networks with better accuracy and fewer parameters. Experiments across architectures and tasks show that deep layer aggregation improves recognition and resolution compared to existing branching and merging schemes.

##### Abstract (translated by Google)
视觉识别需要丰富的表现形式，涵盖从低到高的级别，从小到大的级别，以及从细到粗的分辨率。即使在卷积网络中的特征深度，孤立的一个层是不够的：复合和汇总这些表示可以改进对什么和在哪里的推断。架构工作正在探索网络骨干的许多维度，设计更深层次或更广泛的架构，但是如何在网络上最好地聚合层和块则值得进一步关注。虽然跳过连接已经被结合到层次结合中，但是这些连接本身是“浅的”，并且仅通过简单的一步操作来融合。我们通过更深入的聚合来增强标准体系结构，以更好地融合跨层的信息。我们的深层聚合结构迭代地和分层地合并特征层次结构以使网络具有更好的准确性和更少的参数。体系结构和任务的实验表明，与现有的分支和合并方案相比，深层聚合提高了识别和解决方案。

##### URL
[http://arxiv.org/abs/1707.06484](http://arxiv.org/abs/1707.06484)

##### PDF
[http://arxiv.org/pdf/1707.06484](http://arxiv.org/pdf/1707.06484)

