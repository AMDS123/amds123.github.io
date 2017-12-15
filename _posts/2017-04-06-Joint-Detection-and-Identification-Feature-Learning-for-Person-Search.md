---
layout: post
title: "Joint Detection and Identification Feature Learning for Person Search"
date: 2017-04-06 01:31:08
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification CNN Deep_Learning Detection
author: Tong Xiao, Shuang Li, Bochao Wang, Liang Lin, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Existing person re-identification benchmarks and methods mainly focus on matching cropped pedestrian images between queries and candidates. However, it is different from real-world scenarios where the annotations of pedestrian bounding boxes are unavailable and the target person needs to be searched from a gallery of whole scene images. To close the gap, we propose a new deep learning framework for person search. Instead of breaking it down into two separate tasks---pedestrian detection and person re-identification, we jointly handle both aspects in a single convolutional neural network. An Online Instance Matching (OIM) loss function is proposed to train the network effectively, which is scalable to datasets with numerous identities. To validate our approach, we collect and annotate a large-scale benchmark dataset for person search. It contains 18,184 images, 8,432 identities, and 96,143 pedestrian bounding boxes. Experiments show that our framework outperforms other separate approaches, and the proposed OIM loss function converges much faster and better than the conventional Softmax loss.

##### Abstract (translated by Google)
现有的人员重新识别基准和方法主要集中于在查询和候选人之间匹配裁剪后的行人图像。然而，与现实世界中的情况不同的是，无法使用行人边界框的注释，并且需要从整个场景图像库中搜索目标人物。为弥合这一差距，我们提出了一个新的深度学习框架来进行人物搜索。而不是把它分解成两个独立的任务---行人检测和人员重新识别，我们共同处理单个卷积神经网络中的两个方面。提出了一种在线实例匹配（Online Instance Matching，OIM）丢失函数来有效地对网络进行训练，可以对具有众多身份的数据集进行扩展。为了验证我们的方法，我们收集并注释了一个用于人员搜索的大型基准数据集。它包含18,184个图像，8,432个身份和96,143个行人包围盒。实验表明，我们的框架优于其他独立的方法，所提出的OIM损失函数收敛速度比传统的Softmax损失快得多。

##### URL
[https://arxiv.org/abs/1604.01850](https://arxiv.org/abs/1604.01850)

##### PDF
[https://arxiv.org/pdf/1604.01850](https://arxiv.org/pdf/1604.01850)

