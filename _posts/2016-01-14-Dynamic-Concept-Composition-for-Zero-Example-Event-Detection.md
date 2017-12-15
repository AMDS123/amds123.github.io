---
layout: post
title: "Dynamic Concept Composition for Zero-Example Event Detection"
date: 2016-01-14 17:40:09
categories: arXiv_CV
tags: arXiv_CV Prediction Detection Relation
author: Xiaojun Chang, Yi Yang, Guodong Long, Chengqi Zhang, Alexander G. Hauptmann
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we focus on automatically detecting events in unconstrained videos without the use of any visual training exemplars. In principle, zero-shot learning makes it possible to train an event detection model based on the assumption that events (e.g. \emph{birthday party}) can be described by multiple mid-level semantic concepts (e.g. "blowing candle", "birthday cake"). Towards this goal, we first pre-train a bundle of concept classifiers using data from other sources. Then we evaluate the semantic correlation of each concept \wrt the event of interest and pick up the relevant concept classifiers, which are applied on all test videos to get multiple prediction score vectors. While most existing systems combine the predictions of the concept classifiers with fixed weights, we propose to learn the optimal weights of the concept classifiers for each testing video by exploring a set of online available videos with free-form text descriptions of their content. To validate the effectiveness of the proposed approach, we have conducted extensive experiments on the latest TRECVID MEDTest 2014, MEDTest 2013 and CCV dataset. The experimental results confirm the superiority of the proposed approach.

##### Abstract (translated by Google)
在本文中，我们专注于自动检测无约束视频中的事件，而不使用任何视觉训练范例。原则上，零点射击学习可以根据以下假设来训练事件检测模型：事件（例如\ emph {生日派对}）可以由多个中级语义概念（例如“吹蜡烛”，“生日”蛋糕”）。为了实现这个目标，我们首先使用来自其他来源的数据对一批概念分类器进行预训练。然后，我们评估每个概念与兴趣事件之间的语义关联，并提取相关的概念分类器，将其应用到所有测试视频中以获得多个预测分数向量。尽管大多数现有的系统将概念分类器的预测与固定权重结合起来，但我们建议通过探索一组在线视频的自由文本描述来了解每个测试视频的概念分类器的最佳权重。为了验证所提出的方法的有效性，我们在最新的TRECVID MEDTest 2014，MEDTest 2013和CCV数据集上进行了广泛的实验。实验结果证实了该方法的优越性。

##### URL
[https://arxiv.org/abs/1601.03679](https://arxiv.org/abs/1601.03679)

##### PDF
[https://arxiv.org/pdf/1601.03679](https://arxiv.org/pdf/1601.03679)

