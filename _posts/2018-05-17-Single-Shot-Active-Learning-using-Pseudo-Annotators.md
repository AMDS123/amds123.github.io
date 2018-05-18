---
layout: post
title: "Single Shot Active Learning using Pseudo Annotators"
date: 2018-05-17 09:05:28
categories: arXiv_CV
tags: arXiv_CV
author: Yazhou Yang, Marco Loog
mathjax: true
---

* content
{:toc}

##### Abstract
Standard myopic active learning assumes that human annotations are always obtainable whenever new samples are selected. This, however, is unrealistic in many real-world applications where human experts are not readily available at all times. In this paper, we consider the single shot setting: all the required samples should be chosen in a single shot and no human annotation can be exploited during the selection process. We propose a new method, Active Learning through Random Labeling (ALRL), which substitutes single human annotator for multiple, what we will refer to as, pseudo annotators. These pseudo annotators always provide uniform and random labels whenever new unlabeled samples are queried. This random labeling enables standard active learning algorithms to also exhibit the exploratory behavior needed for single shot active learning. The exploratory behavior is further enhanced by selecting the most representative sample via minimizing nearest neighbor distance between unlabeled samples and queried samples. Experiments on real-world datasets demonstrate that the proposed method outperforms several state-of-the-art approaches.

##### Abstract (translated by Google)
标准近视主动学习假设每当选择新样本时总是可以获得人类注释。然而，这在许多现实世界的应用中是不现实的，因为人类专家在任何时候都不容易获得。在本文中，我们考虑单一拍摄设置：所有需要的样本应该在一次拍摄中进行选择，并且在选择过程中不能使用人类注释。我们提出了一种新的方法，通过随机标记的主动学习（ALRL），它将单个人类注释器替换为多个，我们将称之为伪注释器。这些伪注释器总是在新的未标记样本被查询时提供统一标签和随机标签。这种随机标签使标准的主动学习算法能够展现单次主动学习所需的探索行为。通过最小化未标记样本和查询样本之间的最近邻距离来选择最具代表性的样本，进一步增强了探索行为。对现实世界数据集的实验表明，所提出的方法胜过了几种最先进的方法。

##### URL
[http://arxiv.org/abs/1805.06660](http://arxiv.org/abs/1805.06660)

##### PDF
[http://arxiv.org/pdf/1805.06660](http://arxiv.org/pdf/1805.06660)

