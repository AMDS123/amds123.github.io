---
layout: post
title: "Learning to rank for censored survival data"
date: 2018-06-06 02:30:00
categories: arXiv_AI
tags: arXiv_AI Classification
author: Margaux Luck, Tristan Sylvain, Joseph Paul Cohen, Heloise Cardinal, Andrea Lodi, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Survival analysis is a type of semi-supervised ranking task where the target output (the survival time) is often right-censored. Utilizing this information is a challenge because it is not obvious how to correctly incorporate these censored examples into a model. We study how three categories of loss functions, namely partial likelihood methods, rank methods, and our classification method based on a Wasserstein metric (WM) and the non-parametric Kaplan Meier estimate of the probability density to impute the labels of censored examples, can take advantage of this information. The proposed method allows us to have a model that predict the probability distribution of an event. If a clinician had access to the detailed probability of an event over time this would help in treatment planning. For example, determining if the risk of kidney graft rejection is constant or peaked after some time. Also, we demonstrate that this approach directly optimizes the expected C-index which is the most common evaluation metric for ranking survival models.

##### Abstract (translated by Google)
生存分析是一种半监督的排名任务，目标输出（生存时间）通常是右删失的。利用这些信息是一个挑战，因为如何正确地将这些经过审查的示例合并到模型中并不明显。我们研究了三类损失函数，即部分似然方法，秩方法，基于Wasserstein度量（WM）的我们的分类方法以及归因于截尾示例标签的概率密度的非参数Kaplan Meier估计，能够利用这些信息。所提出的方法允许我们有一个模型来预测事件的概率分布。如果临床医生能够随时了解事件的详细概率，这将有助于治疗计划。例如，确定肾移植排斥反应的风险是恒定的还是在一段时间后达到峰值。此外，我们证明这种方法直接优化预期的C指数，这是评估生存模型排名最常用的评估指标。

##### URL
[http://arxiv.org/abs/1806.01984](http://arxiv.org/abs/1806.01984)

##### PDF
[http://arxiv.org/pdf/1806.01984](http://arxiv.org/pdf/1806.01984)

