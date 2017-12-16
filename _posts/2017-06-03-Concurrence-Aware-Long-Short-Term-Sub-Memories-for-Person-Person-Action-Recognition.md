---
layout: post
title: "Concurrence-Aware Long Short-Term Sub-Memories for Person-Person Action Recognition"
date: 2017-06-03 11:07:23
categories: arXiv_CV
tags: arXiv_CV Action_Recognition RNN Recognition
author: Xiangbo Shu, Jinhui Tang, Guo-Jun Qi, Yan Song, Zechao Li, Liyan Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, Long Short-Term Memory (LSTM) has become a popular choice to model individual dynamics for single-person action recognition due to its ability of modeling the temporal information in various ranges of dynamic contexts. However, existing RNN models only focus on capturing the temporal dynamics of the person-person interactions by naively combining the activity dynamics of individuals or modeling them as a whole. This neglects the inter-related dynamics of how person-person interactions change over time. To this end, we propose a novel Concurrence-Aware Long Short-Term Sub-Memories (Co-LSTSM) to model the long-term inter-related dynamics between two interacting people on the bounding boxes covering people. Specifically, for each frame, two sub-memory units store individual motion information, while a concurrent LSTM unit selectively integrates and stores inter-related motion information between interacting people from these two sub-memory units via a new co-memory cell. Experimental results on the BIT and UT datasets show the superiority of Co-LSTSM compared with the state-of-the-art methods.

##### Abstract (translated by Google)
最近，长时短记忆（LSTM）已经成为单个人动作识别的单个动态模型的流行选择，因为它能够在各种动态环境中对时间信息进行建模。然而，现有的RNN模型只集中于通过天真地结合个体的活动动态或者将它们作为一个整体进行建模来捕捉人与人之间相互作用的时间动态。这忽略了人与人之间的相互作用如何随着时间而改变的相互关联的动态。为此，我们提出了一种新型的Concurrence-Aware Long Short-Term Sub-Memories（Co-LSTSM）来模拟覆盖人群的包围盒上两个相互作用的人之间的长期相互关系的动态。具体而言，对于每个帧，两个子存储器单元存储各个运动信息，而并发LSTM单元经由新的共存储单元在来自这两个子存储器单元的交互人员之间选择性地整合和存储相互关联的运动信息。在BIT和UT数据集上的实验结果显示Co-LSTSM与最先进的方法相比的优越性。

##### URL
[https://arxiv.org/abs/1706.00931](https://arxiv.org/abs/1706.00931)

##### PDF
[https://arxiv.org/pdf/1706.00931](https://arxiv.org/pdf/1706.00931)

