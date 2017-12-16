---
layout: post
title: "Learning Video Object Segmentation with Visual Memory"
date: 2017-07-12 13:26:13
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Pavel Tokmakov, Karteek Alahari, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the task of segmenting moving objects in unconstrained videos. We introduce a novel two-stream neural network with an explicit memory module to achieve this. The two streams of the network encode spatial and temporal features in a video sequence respectively, while the memory module captures the evolution of objects over time. The module to build a "visual memory" in video, i.e., a joint representation of all the video frames, is realized with a convolutional recurrent unit learned from a small number of training video sequences. Given a video frame as input, our approach assigns each pixel an object or background label based on the learned spatio-temporal features as well as the "visual memory" specific to the video, acquired automatically without any manually-annotated frames. The visual memory is implemented with convolutional gated recurrent units, which allows to propagate spatial information over time. We evaluate our method extensively on two benchmarks, DAVIS and Freiburg-Berkeley motion segmentation datasets, and show state-of-the-art results. For example, our approach outperforms the top method on the DAVIS dataset by nearly 6%. We also provide an extensive ablative analysis to investigate the influence of each component in the proposed framework.

##### Abstract (translated by Google)
本文介绍了在无约束视频中分割移动对象的任务。我们引入了一个具有显式记忆模块的新型双流神经网络来实现这一点。网络的两个流分别对视频序列中的空间和时间特征进行编码，而存储器模块随时间捕获对象的演变。利用从少量训练视频序列中学习的卷积递归单元实现在视频中建立“视觉存储器”的模块，即所有视频帧的联合表示。给定视频帧作为输入，我们的方法基于学习的时空特征以及特定于视频的“视觉记忆”为每个像素指定对象或背景标签，而不需要任何手动注释的帧。视觉记忆是用卷积门控循环单元实现的，它允许随着时间传播空间信息。我们在两个基准DAVIS和Freiburg-Berkeley运动分割数据集上广泛评估了我们的方法，并显示了最新的结果。例如，我们的方法胜过DAVIS数据集的顶级方法近6％。我们还提供广泛的烧蚀分析来调查每个组件在提出的框架中的影响。

##### URL
[https://arxiv.org/abs/1704.05737](https://arxiv.org/abs/1704.05737)

##### PDF
[https://arxiv.org/pdf/1704.05737](https://arxiv.org/pdf/1704.05737)

