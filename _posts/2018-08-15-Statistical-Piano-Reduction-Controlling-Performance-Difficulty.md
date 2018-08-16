---
layout: post
title: "Statistical Piano Reduction Controlling Performance Difficulty"
date: 2018-08-15 09:08:39
categories: arXiv_AI
tags: arXiv_AI Optimization Inference Relation
author: Eita Nakamura, Kazuyoshi Yoshii
mathjax: true
---

* content
{:toc}

##### Abstract
We present a statistical-modelling method for piano reduction, i.e. converting an ensemble score into piano scores, that can control performance difficulty. While previous studies have focused on describing the condition for playable piano scores, it depends on player's skill and can change continuously with the tempo. We thus computationally quantify performance difficulty as well as musical fidelity to the original score, and formulate the problem as optimization of musical fidelity under constraints on difficulty values. First, performance difficulty measures are developed by means of probabilistic generative models for piano scores and the relation to the rate of performance errors is studied. Second, to describe musical fidelity, we construct a probabilistic model integrating a prior piano-score model and a model representing how ensemble scores are likely to be edited. An iterative optimization algorithm for piano reduction is developed based on statistical inference of the model. We confirm the effect of the iterative procedure; we find that subjective difficulty and musical fidelity monotonically increase with controlled difficulty values; and we show that incorporating sequential dependence of pitches and fingering motion in the piano-score model improves the quality of reduction scores in high-difficulty cases.

##### Abstract (translated by Google)
我们提出了一种用于钢琴缩小的统计建模方法，即将整体乐谱分成钢琴乐谱，可以控制演奏难度。虽然以前的研究主要集中在描述可演奏钢琴乐谱的条件，但它取决于演奏者的技巧，并且可以随着节奏不断变化。因此，我们在计算上量化了表演难度以及对原始乐谱的音乐保真度，并将问题表达为在难度值约束下音乐保真度的优化。首先，通过钢琴得分的概率生成模型开发性能难度测量，并研究与性能误差率的关系。其次，为了描述音乐保真度，我们构建了一个概率模型，该模型整合了先前的钢琴乐谱模型和表示如何编辑乐团乐谱的模型。基于模型的统计推断，开发了一种用于钢琴缩减的迭代优化算法。我们确认了迭代过程的效果;我们发现主观难度和音乐保真度随着难度值的控制而单调增加;并且我们表明，在钢琴得分模型中加入音高和指法运动的顺序依赖性可以提高高难度情况下降低分数的质量。

##### URL
[http://arxiv.org/abs/1808.05006](http://arxiv.org/abs/1808.05006)

##### PDF
[http://arxiv.org/pdf/1808.05006](http://arxiv.org/pdf/1808.05006)

