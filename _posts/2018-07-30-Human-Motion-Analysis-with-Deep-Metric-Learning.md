---
layout: post
title: "Human Motion Analysis with Deep Metric Learning"
date: 2018-07-30 05:12:09
categories: arXiv_CV
tags: arXiv_CV Embedding RNN Relation
author: Huseyin Coskun, David Joseph Tan, Sailesh Conjeti, Nassir Navab, Federico Tombari
mathjax: true
---

* content
{:toc}

##### Abstract
Effectively measuring the similarity between two human motions is necessary for several computer vision tasks such as gait analysis, person identi- fication and action retrieval. Nevertheless, we believe that traditional approaches such as L2 distance or Dynamic Time Warping based on hand-crafted local pose metrics fail to appropriately capture the semantic relationship across motions and, as such, are not suitable for being employed as metrics within these tasks. This work addresses this limitation by means of a triplet-based deep metric learning specifically tailored to deal with human motion data, in particular with the prob- lem of varying input size and computationally expensive hard negative mining due to motion pair alignment. Specifically, we propose (1) a novel metric learn- ing objective based on a triplet architecture and Maximum Mean Discrepancy; as well as, (2) a novel deep architecture based on attentive recurrent neural networks. One benefit of our objective function is that it enforces a better separation within the learned embedding space of the different motion categories by means of the associated distribution moments. At the same time, our attentive recurrent neural network allows processing varying input sizes to a fixed size of embedding while learning to focus on those motion parts that are semantically distinctive. Our ex- periments on two different datasets demonstrate significant improvements over conventional human motion metrics.

##### Abstract (translated by Google)
有效地测量两个人类运动之间的相似性对于几个计算机视觉任务是必要的，例如步态分析，人员识别和动作检索。尽管如此，我们认为基于手工制作的局部姿势指标的传统方法（如L2距离或动态时间扭曲）无法适当地捕捉跨运动的语义关系，因此不适合用作这些任务中的指标。这项工作通过专门为处理人体运动数据而设计的基于三重态的深度量学习来解决这一局限，特别是由于运动对对齐导致的输入大小变化和计算成本高昂的硬负挖掘问题。具体而言，我们提出（1）基于三元架构和最大均值差异的新颖度量学习目标;以及（2）基于细心的递归神经网络的新型深层架构。我们的目标函数的一个好处是它通过相关的分布时刻在不同运动类别的学习嵌入空间内实现更好的分离。同时，我们专注的递归神经网络允许将不同的输入大小处理为固定的嵌入大小，同时学习专注于那些在语义上与众不同的运动部分。我们对两个不同数据集的实验表明，与传统的人体运动指标相比有了显着的改进。

##### URL
[http://arxiv.org/abs/1807.11176](http://arxiv.org/abs/1807.11176)

##### PDF
[http://arxiv.org/pdf/1807.11176](http://arxiv.org/pdf/1807.11176)

