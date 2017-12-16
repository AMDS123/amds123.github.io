---
layout: post
title: "TALL: Temporal Activity Localization via Language Query"
date: 2017-08-03 21:31:07
categories: arXiv_CV
tags: arXiv_CV
author: Jiyang Gao, Chen Sun, Zhenheng Yang, Ram Nevatia
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on temporal localization of actions in untrimmed videos. Existing methods typically train classifiers for a pre-defined list of actions and apply them in a sliding window fashion. However, activities in the wild consist of a wide combination of actors, actions and objects; it is difficult to design a proper activity list that meets users' needs. We propose to localize activities by natural language queries. Temporal Activity Localization via Language (TALL) is challenging as it requires: (1) suitable design of text and video representations to allow cross-modal matching of actions and language queries; (2) ability to locate actions accurately given features from sliding windows of limited granularity. We propose a novel Cross-modal Temporal Regression Localizer (CTRL) to jointly model text query and video clips, output alignment scores and action boundary regression results for candidate clips. For evaluation, we adopt TaCoS dataset, and build a new dataset for this task on top of Charades by adding sentence temporal annotations, called Charades-STA. We also build complex sentence queries in Charades-STA for test. Experimental results show that CTRL outperforms previous methods significantly on both datasets.

##### Abstract (translated by Google)
本文重点介绍未修剪视频中的动作的时间本地化。现有的方法通常会对预定义的动作列表进行分类，并以滑动窗口的方式应用它们。然而，野外活动包括演员，行动和对象的广泛组合;设计一个适合用户需求的适当的活动列表是很困难的。我们建议通过自然语言查询本地化活动。通过语言进行时间活动本地化（TALL）是具有挑战性的，因为它需要：（1）合适的文本和视频表示设计，以允许动作和语言查询的交叉模式匹配; （2）通过有限粒度的滑动窗口的特征准确定位动作的能力。我们提出了一种新型的交叉模态时态回归定位器（CTRL）来联合建模候选剪辑的文本查询和视频剪辑，输出对齐分数和行动边界回归结果。为了评估，我们采用了TaCoS数据集，并在Charades之上为这个任务建立了一个新的数据集，添加了句子时间注释，称为Charades-STA。我们还在Charades-STA中构建复杂的句子查询以供测试。实验结果表明，CTRL在两个数据集上均优于以前的方法。

##### URL
[https://arxiv.org/abs/1705.02101](https://arxiv.org/abs/1705.02101)

##### PDF
[https://arxiv.org/pdf/1705.02101](https://arxiv.org/pdf/1705.02101)

