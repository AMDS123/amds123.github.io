---
layout: post
title: "Learning to Divide and Conquer for Online Multi-Target Tracking"
date: 2015-09-14 05:25:52
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: Francesco Solera, Simone Calderara, Rita Cucchiara
mathjax: true
---

* content
{:toc}

##### Abstract
Online Multiple Target Tracking (MTT) is often addressed within the tracking-by-detection paradigm. Detections are previously extracted independently in each frame and then objects trajectories are built by maximizing specifically designed coherence functions. Nevertheless, ambiguities arise in presence of occlusions or detection errors. In this paper we claim that the ambiguities in tracking could be solved by a selective use of the features, by working with more reliable features if possible and exploiting a deeper representation of the target only if necessary. To this end, we propose an online divide and conquer tracker for static camera scenes, which partitions the assignment problem in local subproblems and solves them by selectively choosing and combining the best features. The complete framework is cast as a structural learning task that unifies these phases and learns tracker parameters from examples. Experiments on two different datasets highlights a significant improvement of tracking performances (MOTA +10%) over the state of the art.

##### Abstract (translated by Google)
在线多目标跟踪（MTT）通常在逐个检测范例内解决。检测先前在每个帧中独立提取，然后通过最大化专门设计的相干函数来建立对象轨迹。尽管如此，在出现闭塞或检测错误时仍会出现含糊不清的情况。在本文中，我们声称可以通过选择性地使用特征来解决跟踪中的模糊问题，如果可能的话使用更可靠的特征，并且只在必要时利用目标的更深的表示。为此，本文提出了一种静态摄像机场景的在线分治智能跟踪器，将分配问题划分为局部子问题，并通过有选择地选择和组合最佳特征来解决。完整的框架被作为一个结构化的学习任务来统一这些阶段，并从例子中学习跟踪参数。两个不同数据集上的实验突出显示了跟踪性能（MOTA + 10％）在现有技术水平上的显着改进。

##### URL
[https://arxiv.org/abs/1509.03956](https://arxiv.org/abs/1509.03956)

##### PDF
[https://arxiv.org/pdf/1509.03956](https://arxiv.org/pdf/1509.03956)

