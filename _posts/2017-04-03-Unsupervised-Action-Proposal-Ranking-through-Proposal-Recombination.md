---
layout: post
title: "Unsupervised Action Proposal Ranking through Proposal Recombination"
date: 2017-04-03 18:43:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Action_Recognition Optimization Detection Recognition
author: Waqas Sultani, Dong Zhang, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, action proposal methods have played an important role in action recognition tasks, as they reduce the search space dramatically. Most unsupervised action proposal methods tend to generate hundreds of action proposals which include many noisy, inconsistent, and unranked action proposals, while supervised action proposal methods take advantage of predefined object detectors (e.g., human detector) to refine and score the action proposals, but they require thousands of manual annotations to train. Given the action proposals in a video, the goal of the proposed work is to generate a few better action proposals that are ranked properly. In our approach, we first divide action proposal into sub-proposal and then use Dynamic Programming based graph optimization scheme to select the optimal combinations of sub-proposals from different proposals and assign each new proposal a score. We propose a new unsupervised image-based actioness detector that leverages web images and employs it as one of the node scores in our graph formulation. Moreover, we capture motion information by estimating the number of motion contours within each action proposal patch. The proposed method is an unsupervised method that neither needs bounding box annotations nor video level labels, which is desirable with the current explosion of large-scale action datasets. Our approach is generic and does not depend on a specific action proposal method. We evaluate our approach on several publicly available trimmed and un-trimmed datasets and obtain better performance compared to several proposal ranking methods. In addition, we demonstrate that properly ranked proposals produce significantly better action detection as compared to state-of-the-art proposal based methods.

##### Abstract (translated by Google)
最近，行动建议方法在动作识别任务中扮演了重要的角色，因为他们大大减少了搜索空间。大多数无监督的行动建议方法倾向于产生数百个行动建议，其中包括许多嘈杂的，不一致的和未排序的行动建议，而受监督的行动建议方法利用预定义的对象检测器（例如人类检测器）来优化和评分行动建议，但是他们需要数千个手动注释来训练。鉴于视频中的行动建议，提议的工作的目标是产生一些更好的行动建议，排名适当。在我们的方法中，我们首先将行动建议划分为子建议，然后使用基于动态规划的图优化方案来选择来自不同建议的子建议的最佳组合，并为每个新建议书分配一个分数。我们提出了一种新的无监督的基于图像的动作检测器，它利用了网络图像，并将其用作图形表达式中的一个节点分数。此外，我们通过估计每个行动建议补丁内的运动轮廓的数量来捕捉运动信息。该方法是一种无监督的方法，既不需要边界框标注，也不需要视频标签，这是当前大规模动作数据集爆炸所期望的。我们的方法是通用的，不依赖于具体的行动建议方法。我们评估我们的方法在几个公开可用修剪和未修剪的数据集，并获得更好的性能比较几个提案排名方法。此外，我们还证明，与基于最新技术的提案方法相比，正确排名的提案产生更好的动作检测。

##### URL
[https://arxiv.org/abs/1704.00758](https://arxiv.org/abs/1704.00758)

##### PDF
[https://arxiv.org/pdf/1704.00758](https://arxiv.org/pdf/1704.00758)

