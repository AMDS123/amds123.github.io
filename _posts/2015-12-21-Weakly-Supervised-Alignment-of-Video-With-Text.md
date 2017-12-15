---
layout: post
title: "Weakly-Supervised Alignment of Video With Text"
date: 2015-12-21 14:57:40
categories: arXiv_CL
tags: arXiv_CL
author: Piotr Bojanowski (WILLOW, LIENS), Rémi Lajugie (LIENS, SIERRA), Edouard Grave (APAM), Francis Bach (LIENS, SIERRA), Ivan Laptev (WILLOW, LIENS), Jean Ponce (WILLOW, LIENS), Cordelia Schmid (LEAR)
mathjax: true
---

* content
{:toc}

##### Abstract
Suppose that we are given a set of videos, along with natural language descriptions in the form of multiple sentences (e.g., manual annotations, movie scripts, sport summaries etc.), and that these sentences appear in the same temporal order as their visual counterparts. We propose in this paper a method for aligning the two modalities, i.e., automatically providing a time stamp for every sentence. Given vectorial features for both video and text, we propose to cast this task as a temporal assignment problem, with an implicit linear mapping between the two feature modalities. We formulate this problem as an integer quadratic program, and solve its continuous convex relaxation using an efficient conditional gradient algorithm. Several rounding procedures are proposed to construct the final integer solution. After demonstrating significant improvements over the state of the art on the related task of aligning video with symbolic labels [7], we evaluate our method on a challenging dataset of videos with associated textual descriptions [36], using both bag-of-words and continuous representations for text.

##### Abstract (translated by Google)
假设给予我们一组视频，以及多个句子形式的自然语言描述（例如，手工注释，电影剧本，体育概要等），并且这些句子以与其视觉对应物相同的时间顺序出现。我们在本文中提出了一种对齐两种模式的方法，即为每个句子自动提供一个时间标记。给定视频和文本的矢量特征，我们建议把这个任务作为一个时间分配问题，在两个特征模态之间隐含线性映射。我们把这个问题作为一个整数二次规划，并用有效的条件梯度算法求解它的连续凸松弛。提出了几个舍入程序来构造最终的整数解。在对视频与符号标签进行对齐的相关任务上展示了显着的改进之后，我们使用相关的文本描述[36]来评估我们的方法在具有挑战性的视频数据集上[36]连续的文字表示。

##### URL
[https://arxiv.org/abs/1505.06027](https://arxiv.org/abs/1505.06027)

##### PDF
[https://arxiv.org/pdf/1505.06027](https://arxiv.org/pdf/1505.06027)

