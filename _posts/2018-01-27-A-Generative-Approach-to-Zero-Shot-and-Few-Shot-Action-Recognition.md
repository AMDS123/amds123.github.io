---
layout: post
title: "A Generative Approach to Zero-Shot and Few-Shot Action Recognition"
date: 2018-01-27 13:13:29
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Recognition
author: Ashish Mishra, Vinay Kumar Verma, M Shiva Krishna Reddy, Arulkumar S, Piyush Rai, Anurag Mittal
mathjax: true
---

* content
{:toc}

##### Abstract
We present a generative framework for zero-shot action recognition where some of the possible action classes do not occur in the training data. Our approach is based on modeling each action class using a probability distribution whose parameters are functions of the attribute vector representing that action class. In particular, we assume that the distribution parameters for any action class in the visual space can be expressed as a linear combination of a set of basis vectors where the combination weights are given by the attributes of the action class. These basis vectors can be learned solely using labeled data from the known (i.e., previously seen) action classes, and can then be used to predict the parameters of the probability distributions of unseen action classes. We consider two settings: (1) Inductive setting, where we use only the labeled examples of the seen action classes to predict the unseen action class parameters; and (2) Transductive setting which further leverages unlabeled data from the unseen action classes. Our framework also naturally extends to few-shot action recognition where a few labeled examples from unseen classes are available. Our experiments on benchmark datasets (UCF101, HMDB51 and Olympic) show significant performance improvements as compared to various baselines, in both standard zero-shot (disjoint seen and unseen classes) and generalized zero-shot learning settings.

##### Abstract (translated by Google)
我们提出了一个零射击动作识别的生成框架，其中一些可能的动作类不会出现在训练数据中。我们的方法是基于使用概率分布对每个行为类别建模，其概率分布参数是表示该行为类别的属性向量的函数。特别地，我们假设视觉空间中的任何动作类别的分布参数可以表示为一组基础向量的线性组合，其中组合权重由动作类别的属性给出。这些基矢量可以仅使用来自已知（即，先前看到的）动作类的标记数据来学习，然后可以用来预测未知动作类的概率分布的参数。我们考虑两个设置：（1）归纳设置，我们只使用所看到的动作类的标记示例来预测看不见的动作类参数; （2）进一步利用看不见的行动类别的未标记数据的传导设置。我们的框架自然延伸到少数动作识别，其中有几个来自不可见类的标记示例可用。我们在基准数据集（UCF101，HMDB51和奥运）上的实验显示，与标准零点（不相交的看到和看不见的类）和广义零点学习设置中的各种基线相比，性能得到显着改善。

##### URL
[http://arxiv.org/abs/1801.09086](http://arxiv.org/abs/1801.09086)

##### PDF
[http://arxiv.org/pdf/1801.09086](http://arxiv.org/pdf/1801.09086)

