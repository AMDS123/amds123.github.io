---
layout: post
title: "Factors in Finetuning Deep Model for object detection"
date: 2016-04-14 01:15:12
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Wanli Ouyang, Xiaogang Wang, Cong Zhang, Xiaokang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Finetuning from a pretrained deep model is found to yield state-of-the-art performance for many vision tasks. This paper investigates many factors that influence the performance in finetuning for object detection. There is a long-tailed distribution of sample numbers for classes in object detection. Our analysis and empirical results show that classes with more samples have higher impact on the feature learning. And it is better to make the sample number more uniform across classes. Generic object detection can be considered as multiple equally important tasks. Detection of each class is a task. These classes/tasks have their individuality in discriminative visual appearance representation. Taking this individuality into account, we cluster objects into visually similar class groups and learn deep representations for these groups separately. A hierarchical feature learning scheme is proposed. In this scheme, the knowledge from the group with large number of classes is transferred for learning features in its sub-groups. Finetuned on the GoogLeNet model, experimental results show 4.7% absolute mAP improvement of our approach on the ImageNet object detection dataset without increasing much computational cost at the testing stage.

##### Abstract (translated by Google)
从一个预训练的深层模型中学习，可以发现许多视觉任务的最新性能。本文研究了影响微调中物体检测性能的诸多因素。对象检测中的类有一个长尾分布的样本数。我们的分析和实证结果表明，样本越多，对特征学习的影响越大。最好让样本数量在各个班级之间更加一致。通用对象检测可以被认为是多个同样重要的任务。每个班的检测是一项任务。这些类别/任务在辨别性视觉外观表示方面具有其个性。考虑到这种个性，我们把对象聚类成视觉上相似的班级组，并分别为这些组学习深度表达。提出了一种分层特征学习方案。在这个方案中，将来自大量班级的知识转移到其子组的学习特征中。在GoogLeNet模型上进行实验，实验结果显示我们在ImageNet对象检测数据集上的方法的绝对mAP改善4.7％，而在测试阶段没有增加太多的计算成本。

##### URL
[https://arxiv.org/abs/1601.05150](https://arxiv.org/abs/1601.05150)

