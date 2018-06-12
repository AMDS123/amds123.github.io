---
layout: post
title: "Abstaining Classification When Error Costs are Unequal and Unknown"
date: 2018-06-09 09:00:08
categories: arXiv_CV
tags: arXiv_CV Classification
author: Hongjiao Guan, Yingtao Zhang, H. D. Cheng, Xianglong Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Abstaining classificaiton aims to reject to classify the easily misclassified examples, so it is an effective approach to increase the clasificaiton reliability and reduce the misclassification risk in the cost-sensitive applications. In such applications, different types of errors (false positive or false negative) usaully have unequal costs. And the error costs, which depend on specific applications, are usually unknown. However, current abstaining classification methods either do not distinguish the error types, or they need the cost information of misclassification and rejection, which are realized in the framework of cost-sensitive learning. In this paper, we propose a bounded-abstention method with two constraints of reject rates (BA2), which performs abstaining classification when error costs are unequal and unknown. BA2 aims to obtain the optimal area under the ROC curve (AUC) by constraining the reject rates of the positive and negative classes respectively. Specifically, we construct the receiver operating characteristic (ROC) curve, and stepwise search the optimal reject thresholds from both ends of the curve, untill the two constraints are satisfied. Experimental results show that BA2 obtains higher AUC and lower total cost than the state-of-the-art abstaining classification methods. Meanwhile, BA2 achieves controllable reject rates of the positive and negative classes.

##### Abstract (translated by Google)
弃权分类的目的是拒绝对容易错误分类的例子进行分类，因此它是提高分类可靠性并降低成本敏感应用中误分类风险的有效方法。在这种应用中，不同类型的错误（假阳性或假阴性）通常具有不同的成本。而依赖于特定应用的错误成本通常是未知的。然而，目前的弃权分类方法要么不区分错误类型，要么需要错误分类和拒绝的成本信息，这是在成本敏感的学习框架中实现的。在本文中，我们提出了一种有两个拒绝率约束（BA2）的有界弃权方法，当误差成本不等且未知时，它执行弃权分类。 BA2旨在通过分别限制正和负类别的拒绝率来获得ROC曲线（AUC）下的最佳面积。具体来说，我们构造了接收器操作特性（ROC）曲线，并从曲线两端逐步搜索最优拒绝阈值，直到满足两个约束条件。实验结果显示BA2比现有技术的弃权分类方法获得更高的AUC和更低的总成本。同时，BA2达到了可控的正负类废品率。

##### URL
[http://arxiv.org/abs/1806.03445](http://arxiv.org/abs/1806.03445)

##### PDF
[http://arxiv.org/pdf/1806.03445](http://arxiv.org/pdf/1806.03445)

