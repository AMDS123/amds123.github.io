---
layout: post
title: "Hierarchical Attentive Recurrent Tracking"
date: 2017-09-05 14:35:08
categories: arXiv_CV
tags: arXiv_CV Attention Tracking Object_Tracking Recognition
author: Adam R. Kosiorek, Alex Bewley, Ingmar Posner
mathjax: true
---

* content
{:toc}

##### Abstract
Class-agnostic object tracking is particularly difficult in cluttered environments as target specific discriminative models cannot be learned a priori. Inspired by how the human visual cortex employs spatial attention and separate "where" and "what" processing pathways to actively suppress irrelevant visual features, this work develops a hierarchical attentive recurrent model for single object tracking in videos. The first layer of attention discards the majority of background by selecting a region containing the object of interest, while the subsequent layers tune in on visual features particular to the tracked object. This framework is fully differentiable and can be trained in a purely data driven fashion by gradient methods. To improve training convergence, we augment the loss function with terms for a number of auxiliary tasks relevant for tracking. Evaluation of the proposed model is performed on two datasets: pedestrian tracking on the KTH activity recognition dataset and the more difficult KITTI object tracking dataset.

##### Abstract (translated by Google)
类别不可知的对象跟踪在混乱的环境中特别困难，因为目标特定的判别模型不能被先验地学习。受到人类视觉皮层如何利用空间注意力，分离“哪里”和“什么”处理途径以积极抑制不相关的视觉特征的启发，这项工作为视频中的单个对象跟踪开发了一个分层的周密循环模型。第一层关注点通过选择一个包含感兴趣对象的区域来丢弃大部分的背景，而随后的层调入跟踪对象特有的视觉特征。这个框架是完全可以区分的，可以通过梯度方法以纯数据驱动的方式进行培训。为了改善训练收敛性，我们用与跟踪有关的许多辅助任务的项来增加损失函数。所提出的模型的评估在两个数据集上进行：在KTH活动识别数据集上的行人追踪和比较困难的KITTI对象追踪数据集。

##### URL
[https://arxiv.org/abs/1706.09262](https://arxiv.org/abs/1706.09262)

##### PDF
[https://arxiv.org/pdf/1706.09262](https://arxiv.org/pdf/1706.09262)

