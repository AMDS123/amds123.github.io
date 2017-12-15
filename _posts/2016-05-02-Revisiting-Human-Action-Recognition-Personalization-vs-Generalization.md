---
layout: post
title: "Revisiting Human Action Recognition: Personalization vs. Generalization"
date: 2016-05-02 08:46:23
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Classification Recognition
author: Andrea Zunino, Jacopo Cavazza, Vittorio Murino
mathjax: true
---

* content
{:toc}

##### Abstract
By thoroughly revisiting the classic human action recognition paradigm, this paper aims at proposing a new approach for the design of effective action classification systems. Taking as testbed publicly available three-dimensional (MoCap) action/activity datasets, we analyzed and validated different training/testing strategies. In particular, considering that each human action in the datasets is performed several times by different subjects, we were able to precisely quantify the effect of inter- and intra-subject variability, so as to figure out the impact of several learning approaches in terms of classification performance. The net result is that standard testing strategies consisting in cross-validating the algorithm using typical splits of the data (holdout, k-fold, or one-subject-out) is always outperformed by a "personalization" strategy which learns how a subject is performing an action. In other words, it is advantageous to customize (i.e., personalize) the method to learn the actions carried out by each subject, rather than trying to generalize the actions executions across subjects. Consequently, we finally propose an action recognition framework consisting of a two-stage classification approach where, given a test action, the subject is first identified before the actual recognition of the action takes place. Despite the basic, off-the-shelf descriptors and standard classifiers adopted, we noted a relevant increase in performance with respect to standard state-of-the-art algorithms, so motivating the usage of personalized approaches for designing effective action recognition systems.

##### Abstract (translated by Google)
通过彻底重新审视经典的人类行为识别范式，本文旨在为有效的行动分类系统的设计提出一种新的方法。作为测试公开可用的三维（MoCap）行动/活动数据集，我们分析和验证不同的培训/测试策略。特别是，考虑到数据集中的每个人的行为是由不同的主体多次执行的，我们能够精确地量化主体间和主体间的变化的影响，从而找出几个学习方法的影响分类表现。最终的结果是，使用典型的数据拆分（holdout，k-fold或one-subject-out）交叉验证算法的标准测试策略总是优于“个性化”策略，该策略可以学习某个主题执行一个动作。换句话说，定制（即，个性化）学习由每个主题执行的动作的方法是有利的，而不是试图概括跨主题的动作执行。因此，我们最终提出了一个行动识别框架，该框架由两阶段的分类方法组成，其中，在实际识别行动发生之前，在给定测试行为的情况下首先识别出主体。尽管采用了基本的现成描述符和标准分类器，但我们注意到相对于标准的最先进的算法，性能有了相应的提高，因此激发了使用个性化方法来设计有效的动作识别系统。

##### URL
[https://arxiv.org/abs/1605.00392](https://arxiv.org/abs/1605.00392)

##### PDF
[https://arxiv.org/pdf/1605.00392](https://arxiv.org/pdf/1605.00392)

