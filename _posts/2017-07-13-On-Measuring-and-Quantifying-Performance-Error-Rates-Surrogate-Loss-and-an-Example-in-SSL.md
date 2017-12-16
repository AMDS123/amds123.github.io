---
layout: post
title: "On Measuring and Quantifying Performance: Error Rates, Surrogate Loss, and an Example in SSL"
date: 2017-07-13 08:29:00
categories: arXiv_CV
tags: arXiv_CV Classification
author: Marco Loog, Jesse H. Krijthe, Are C. Jensen
mathjax: true
---

* content
{:toc}

##### Abstract
In various approaches to learning, notably in domain adaptation, active learning, learning under covariate shift, semi-supervised learning, learning with concept drift, and the like, one often wants to compare a baseline classifier to one or more advanced (or at least different) strategies. In this chapter, we basically argue that if such classifiers, in their respective training phases, optimize a so-called surrogate loss that it may also be valuable to compare the behavior of this loss on the test set, next to the regular classification error rate. It can provide us with an additional view on the classifiers' relative performances that error rates cannot capture. As an example, limited but convincing empirical results demonstrates that we may be able to find semi-supervised learning strategies that can guarantee performance improvements with increasing numbers of unlabeled data in terms of log-likelihood. In contrast, the latter may be impossible to guarantee for the classification error rate.

##### Abstract (translated by Google)
在各种学习方法中，特别是在领域适应，主动学习，协变量学习，半监督学习，概念漂移学习等等中，人们经常希望将基线分类器与一个或多个高级（或至少不同的）策略。在本章中，我们基本上认为，如果这些分类器在其各自的训练阶段优化所谓的替代损失，那么比较测试集上这种损失的行为也是有价值的，旁边是常规分类错误率。它可以为我们提供错误率无法捕捉的分类器相对表现的额外观点。作为一个例子，有限但令人信服的实证结果表明，我们可能能够找到半监督学习策略，可以保证性能的改善，随着数量越来越多的无标签数据的对数似然。相反，后者可能无法保证分类错误率。

##### URL
[https://arxiv.org/abs/1707.04025](https://arxiv.org/abs/1707.04025)

##### PDF
[https://arxiv.org/pdf/1707.04025](https://arxiv.org/pdf/1707.04025)

