---
layout: post
title: "Actor-Action Semantic Segmentation with Region Masks"
date: 2018-07-23 05:11:23
categories: arXiv_AI
tags: arXiv_AI Segmentation Semantic_Segmentation
author: Kang Dang, Chunluan Zhou, Zhigang Tu, Michael Hoy, Justin Dauwels, Junsong Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study the actor-action semantic segmentation problem, which requires joint labeling of both actor and action categories in video frames. One major challenge for this task is that when an actor performs an action, different body parts of the actor provide different types of cues for the action category and may receive inconsistent action labeling when they are labeled independently. To address this issue, we propose an end-to-end region-based actor-action segmentation approach which relies on region masks from an instance segmentation algorithm. Our main novelty is to avoid labeling pixels in a region mask independently - instead we assign a single action label to these pixels to achieve consistent action labeling. When a pixel belongs to multiple region masks, max pooling is applied to resolve labeling conflicts. Our approach uses a two-stream network as the front-end (which learns features capturing both appearance and motion information), and uses two region-based segmentation networks as the back-end (which takes the fused features from the two-stream network as the input and predicts actor-action labeling). Experiments on the A2D dataset demonstrate that both the region-based segmentation strategy and the fused features from the two-stream network contribute to the performance improvements. The proposed approach outperforms the state-of-the-art results by more than 8% in mean class accuracy, and more than 5% in mean class IOU, which validates its effectiveness.

##### Abstract (translated by Google)
在本文中，我们研究了演员 - 动作语义分割问题，该问题需要在视频帧中联合标记演员和动作类别。对于该任务的一个主要挑战是当演员执行动作时，演员的不同身体部分为动作类别提供不同类型的提示，并且当它们被独立标记时可能接收不一致的动作标记。为了解决这个问题，我们提出了一种端到端的基于区域的行动者 - 动作分割方法，该方法依赖于来自实例分割算法的区域掩模。我们的主要新颖性是避免单独标记区域掩模中的像素 - 而是我们为这些像素分配单个动作标签以实现一致的动作标记。当像素属于多个区域掩码时，将应用最大池来解决标记冲突。我们的方法使用双流网络作为前端（学习捕获外观和运动信息的特征），并使用两个基于区域的分段网络作为后端（从双流网络获取融合特征）作为输入和预测行动者行动标签）。对A2D数据集的实验表明，基于区域的分割策略和来自双流网络的融合特征都有助于提高性能。所提出的方法在平均类别准确度方面优于最先进的结果超过8％，在平均类别IOU方面超过5％，这证实了其有效性。

##### URL
[http://arxiv.org/abs/1807.08430](http://arxiv.org/abs/1807.08430)

##### PDF
[http://arxiv.org/pdf/1807.08430](http://arxiv.org/pdf/1807.08430)

