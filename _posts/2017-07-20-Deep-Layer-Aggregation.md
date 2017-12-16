---
layout: post
title: "Deep Layer Aggregation"
date: 2017-07-20 12:59:08
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Semantic_Segmentation Classification
author: Fisher Yu, Dequan Wang, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional networks have had great success in image classification and other areas of computer vision. Recent efforts have designed deeper or wider networks to improve performance; as convolutional blocks are usually stacked together, blocks at different depths represent information at different scales. Recent models have explored `skip' connections to aggregate information across layers, but heretofore such skip connections have themselves been `shallow', projecting to a single fusion node. In this paper, we investigate new deep-across-layer architectures to aggregate the information from multiple layers. We propose novel iterative and hierarchical structures for deep layer aggregation. The former can produce deep high resolution representations from a network whose final layers have low resolution, while the latter can effectively combine scale information from all blocks. Results show that the our proposed architectures can make use of network parameters and features more efficiently without dictating convolution module structure. We also show transfer of the learned networks to semantic segmentation tasks and achieve better results than alternative networks with baseline training settings.

##### Abstract (translated by Google)
卷积网络在图像分类和其他计算机视觉领域取得了巨大的成功。最近的努力设计了更深入或更广泛的网络来提高性能;由于卷积块通常堆叠在一起，不同深度的块表示不同尺度的信息。最近的模型已经探索了“跳过”连接，以跨层聚合信息，但是迄今为止，这样的跳过连接本身是“浅”的，投影到单个融合节点。在本文中，我们调查新的深层跨体系结构来聚合来自多个层次的信息。我们提出了深层聚合的新型迭代和分层结构。前者可以从最终层次较低的网络产生深度高分辨率表示，而后者可以有效地结合来自所有区块的尺度信息。结果表明，我们提出的架构可以更有效地利用网络参数和功能，而不需要指定卷积模块结构。我们还显示学习网络转移到语义分割任务，并取得比基线训练设置的替代网络更好的结果。

##### URL
[https://arxiv.org/abs/1707.06484](https://arxiv.org/abs/1707.06484)

##### PDF
[https://arxiv.org/pdf/1707.06484](https://arxiv.org/pdf/1707.06484)

