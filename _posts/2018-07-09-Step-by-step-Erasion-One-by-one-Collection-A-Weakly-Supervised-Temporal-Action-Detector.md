---
layout: post
title: "Step-by-step Erasion, One-by-one Collection: A Weakly Supervised Temporal Action Detector"
date: 2018-07-09 03:33:54
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Classification Detection
author: Jia-Xing Zhong, Nannan Li, Weijie Kong, Tao Zhang, Thomas H. Li, Ge Li
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly supervised temporal action detection is a Herculean task in understanding untrimmed videos, since no supervisory signal except the video-level category label is available on training data. Under the supervision of category labels, weakly supervised detectors are usually built upon classifiers. However, there is an inherent contradiction between classifier and detector; i.e., a classifier in pursuit of high classification performance prefers top-level discriminative video clips that are extremely fragmentary, whereas a detector is obliged to discover the whole action instance without missing any relevant snippet. To reconcile this contradiction, we train a detector by driving a series of classifiers to find new actionness clips progressively, via step-by-step erasion from a complete video. During the test phase, all we need to do is to collect detection results from the one-by-one trained classifiers at various erasing steps. To assist in the collection process, a fully connected conditional random field is established to refine the temporal localization outputs. We evaluate our approach on two prevailing datasets, THUMOS'14 and ActivityNet. The experiments show that our detector advances state-of-the-art weakly supervised temporal action detection results, and even compares with quite a few strongly supervised methods.

##### Abstract (translated by Google)
弱监督时间动作检测是理解未修剪视频的艰巨任务，因为除了视频级别类别标签之外，没有监控信号可用于训练数据。在类别标签的监督下，弱监督检测器通常建立在分类器之上。然而，分类器和检测器之间存在固有的矛盾;即，追求高分类性能的分类器优选极其零碎的顶级判别视频剪辑，而检测器必须发现整个动作实例而不丢失任何相关片段。为了调和这一矛盾，我们通过驱动一系列分类器来训练探测器，通过逐步擦除整个视频逐步找到新的动作片段。在测试阶段，我们需要做的就是在各种擦除步骤中从一个一个训练的分类器中收集检测结果。为了协助收集过程，建立完全连接的条件随机场以改进时间定位输出。我们在两个主流数据集THUMOS'14和ActivityNet上评估我们的方法。实验表明，我们的探测器推进了最先进的弱监督时间动作检测结果，甚至可以与相当多的强监督方法进行比较。

##### URL
[http://arxiv.org/abs/1807.02929](http://arxiv.org/abs/1807.02929)

##### PDF
[http://arxiv.org/pdf/1807.02929](http://arxiv.org/pdf/1807.02929)

