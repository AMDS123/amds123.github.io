---
layout: post
title: "Learning to Cluster for Proposal-Free Instance Segmentation"
date: 2018-03-17 04:35:21
categories: arXiv_AI
tags: arXiv_AI Object_Detection Segmentation CNN Semantic_Segmentation Detection Relation
author: Yen-Chang Hsu, Zheng Xu, Zsolt Kira, Jiawei Huang
mathjax: true
---

* content
{:toc}

##### Abstract
This work proposed a novel learning objective to train a deep neural network to perform end-to-end image pixel clustering. We applied the approach to instance segmentation, which is at the intersection of image semantic segmentation and object detection. We utilize the most fundamental property of instance labeling -- the pairwise relationship between pixels -- as the supervision to formulate the learning objective, then apply it to train a fully convolutional network (FCN) for learning to perform pixel-wise clustering. The resulting clusters can be used as the instance labeling directly. To support labeling of an unlimited number of instance, we further formulate ideas from graph coloring theory into the proposed learning objective. The evaluation on the Cityscapes dataset demonstrates strong performance and therefore proof of the concept. Moreover, our approach won the second place in the lane detection competition of 2017 CVPR Autonomous Driving Challenge, and was the top performer without using external data.

##### Abstract (translated by Google)
这项工作提出了一个新的学习目标，以训练一个深度神经网络来执行端到端图像像素聚类。我们将这种方法应用于图像语义分割和对象检测的交叉点实例分割。我们利用实例标记的最基本属性 - 像素之间的配对关系 - 作为制定学习目标的监督，然后将其应用于训练完全卷积网络（FCN），以便学习执行像素聚类。生成的集群可以直接用作实例标记。为了支持无限数量的实例的标记，我们进一步将图论着色理论中的想法写入提出的学习目标中。 Cityscapes数据集的评估表现出强劲的表现，因此也证明了这一概念。此外，我们的方法在2017年CVPR自主驾驶挑战赛车道检测竞赛中获得第二名，并且在没有使用外部数据的情况下表现最佳。

##### URL
[https://arxiv.org/abs/1803.06459](https://arxiv.org/abs/1803.06459)

##### PDF
[https://arxiv.org/pdf/1803.06459](https://arxiv.org/pdf/1803.06459)

