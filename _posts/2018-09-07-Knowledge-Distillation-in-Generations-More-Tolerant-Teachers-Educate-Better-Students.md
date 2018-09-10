---
layout: post
title: "Knowledge Distillation in Generations: More Tolerant Teachers Educate Better Students"
date: 2018-09-07 17:37:25
categories: arXiv_CV
tags: arXiv_CV Knowledge Image_Classification Optimization Classification
author: Chenglin Yang, Lingxi Xie, Siyuan Qiao, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
We focus on the problem of training a deep neural network in generations. The flowchart is that, in order to optimize the target network (student), another network (teacher) with the same architecture is first trained, and used to provide part of supervision signals in the next stage. While this strategy leads to a higher accuracy, many aspects (e.g., why teacher-student optimization helps) still need further explorations. 
 This paper studies this problem from a perspective of controlling the strictness in training the teacher network. Existing approaches mostly used a hard distribution (e.g., one-hot vectors) in training, leading to a strict teacher which itself has a high accuracy, but we argue that the teacher needs to be more tolerant, although this often implies a lower accuracy. The implementation is very easy, with merely an extra loss term added to the teacher network, facilitating a few secondary classes to emerge and complement to the primary class. Consequently, the teacher provides a milder supervision signal (a less peaked distribution), and makes it possible for the student to learn from inter-class similarity and potentially lower the risk of over-fitting. Experiments are performed on standard image classification tasks (CIFAR100 and ILSVRC2012). Although the teacher network behaves less powerful, the students show a persistent ability growth and eventually achieve higher classification accuracies than other competitors. Model ensemble and transfer feature extraction also verify the effectiveness of our approach.

##### Abstract (translated by Google)
我们专注于几代人训练深度神经网络的问题。该流程图是，为了优化目标网络（学生），首先训练具有相同架构的另一网络（教师），并用于在下一阶段提供部分监督信号。虽然这种策略可以提高准确性，但许多方面（例如，为什么师生优化有帮助）仍需要进一步探索。
 本文从控制教师网络培训严格性的角度研究了这一问题。现有的方法主要在训练中使用硬分布（例如，单热矢量），导致严格的教师本身具有高准确性，但我们认为教师需要更宽容，尽管这通常意味着较低的准确性。实施非常简单，只需在教师网络中增加一个额外的损失条款，便于一些中学课程的出现和对小学课程的补充。因此，教师提供较温和的监督信号（较低的分布），并使​​学生能够从课间相似性中学习，并可能降低过度拟合的风险。在标准图像分类任务（CIFAR100和ILSVRC2012）上进行实验。虽然教师网络的功能较弱，但学生表现出持续的能力增长，并最终获得比其他竞争对手更高的分类准确度。模型集合和传递特征提取也验证了我们的方法的有效性。

##### URL
[http://arxiv.org/abs/1805.05551](http://arxiv.org/abs/1805.05551)

##### PDF
[http://arxiv.org/pdf/1805.05551](http://arxiv.org/pdf/1805.05551)

