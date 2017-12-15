---
layout: post
title: "Deep Ranking for Person Re-identification via Joint Representation Learning"
date: 2016-03-23 03:37:36
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification CNN Represenation_Learning Relation
author: Shi-Zhe Chen, Chun-Chao Guo, Jian-Huang Lai
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel approach to person re-identification, a fundamental task in distributed multi-camera surveillance systems. Although a variety of powerful algorithms have been presented in the past few years, most of them usually focus on designing hand-crafted features and learning metrics either individually or sequentially. Different from previous works, we formulate a unified deep ranking framework that jointly tackles both of these key components to maximize their strengths. We start from the principle that the correct match of the probe image should be positioned in the top rank within the whole gallery set. An effective learning-to-rank algorithm is proposed to minimize the cost corresponding to the ranking disorders of the gallery. The ranking model is solved with a deep convolutional neural network (CNN) that builds the relation between input image pairs and their similarity scores through joint representation learning directly from raw image pixels. The proposed framework allows us to get rid of feature engineering and does not rely on any assumption. An extensive comparative evaluation is given, demonstrating that our approach significantly outperforms all state-of-the-art approaches, including both traditional and CNN-based methods on the challenging VIPeR, CUHK-01 and CAVIAR4REID datasets. Additionally, our approach has better ability to generalize across datasets without fine-tuning.

##### Abstract (translated by Google)
本文提出了一种新的人员重新识别方法，这是分布式多摄像机监控系统的一项基本任务。尽管在过去的几年中已经提出了各种强大的算法，但是其中大多数算法通常关注于单独或顺序地设计手工特征和学习度量。与以往不同的是，我们制定了统一的深度排序框架，共同攻克这两个关键组成部分，最大限度地发挥其优势。我们从探针图像的正确匹配应该被放置在整个图库集中的最高等级的原则开始。提出了一种有效的学习 - 排序算法，以使与画廊的排名障碍相对应的成本最小化。通过深度卷积神经网络（CNN）解决排序模型，通过直接从原始图像像素进行联合表示学习，建立输入图像对与其相似度分数之间的关系。所提出的框架允许我们摆脱特征工程，并不依赖任何假设。进行了广泛的比较评估，表明我们的方法明显优于所有最先进的方法，包括在具有挑战性的VIPeR，CUHK-01和CAVIAR4REID数据集上的传统方法和基于CNN的方法。此外，我们的方法有更好的能力来推广跨数据集没有微调。

##### URL
[https://arxiv.org/abs/1505.06821](https://arxiv.org/abs/1505.06821)

##### PDF
[https://arxiv.org/pdf/1505.06821](https://arxiv.org/pdf/1505.06821)

