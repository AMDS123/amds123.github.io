---
layout: post
title: "HMM-based Writer Identification in Music Score Documents without Staff-Line Removal"
date: 2017-07-27 23:11:51
categories: arXiv_CV
tags: arXiv_CV Detection
author: Partha Pratim Roy, Ayan Kumar Bhunia, Umapada Pal
mathjax: true
---

* content
{:toc}

##### Abstract
Writer identification from musical score documents is a challenging task due to its inherent problem of overlapping of musical symbols with staff lines. Most of the existing works in the literature of writer identification in musical score documents were performed after a preprocessing stage of staff lines removal. In this paper we propose a novel writer identification framework in musical documents without removing staff lines from documents. In our approach, Hidden Markov Model has been used to model the writing style of the writers without removing staff lines. The sliding window features are extracted from musical score lines and they are used to build writer specific HMM models. Given a query musical sheet, writer specific confidence for each musical line is returned by each writer specific model using a loglikelihood score. Next, a loglikelihood score in page level is computed by weighted combination of these scores from the corresponding line images of the page. A novel Factor Analysis based feature selection technique is applied in sliding window features to reduce the noise appearing from staff lines which proves efficiency in writer identification performance.In our framework we have also proposed a novel score line detection approach in musical sheet using HMM. The experiment has been performed in CVC-MUSCIMA dataset and the results obtained that the proposed approach is efficient for score line detection and writer identification without removing staff lines. To get the idea of computation time of our method, detail analysis of execution time is also provided.

##### Abstract (translated by Google)
由于音乐符号与职员线重叠的固有问题，来自乐谱文件的作者识别是具有挑战性的任务。音乐记分文件中作者身份识别文献中的大部分现有作品是在删除职员线的预处理阶段之后进行的。在本文中，我们提出了一个新的作家识别框架在音乐文件，而不删除从文件的员工线。在我们的方法中，隐马尔可夫模型已经被用来模拟作家的写作风格而不删除职员线。滑动窗口的特征是从乐谱中提取的，它们被用来构建作家特定的HMM模型。给定一个查询音乐表，每个作者具体的信心为每个音乐线由每个作家具体模型返回使用loglikelihood分数。接下来，通过来自页面的对应线图像的这些分数的加权组合来计算页面级别的对数似然分数。基于因子分析的特征选择新技术应用于滑动窗口特征中，减少了人员线条出现的噪声，证明了作者识别性能的有效性。在我们的框架中，我们还提出了一种使用隐马尔可夫模型的乐谱的新颖的分数线检测方法。实验已经在CVC-MUSCIMA数据集中进行，结果表明所提出的方法对于得分线检测和书写器识别是有效的，而不需要移除员工队列。为了得到我们方法的计算时间的思想，还提供了执行时间的详细分析。

##### URL
[https://arxiv.org/abs/1707.06828](https://arxiv.org/abs/1707.06828)

##### PDF
[https://arxiv.org/pdf/1707.06828](https://arxiv.org/pdf/1707.06828)

