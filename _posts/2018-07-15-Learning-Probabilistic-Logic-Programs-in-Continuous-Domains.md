---
layout: post
title: "Learning Probabilistic Logic Programs in Continuous Domains"
date: 2018-07-15 11:00:00
categories: arXiv_AI
tags: arXiv_AI Inference Relation
author: Stefanie Speichert, Vaishak Belle
mathjax: true
---

* content
{:toc}

##### Abstract
The field of statistical relational learning aims at unifying logic and probability to reason and learn from data. Perhaps the most successful paradigm in the field is probabilistic logic programming: the enabling of stochastic primitives in logic programming, which is now increasingly seen to provide a declarative background to complex machine learning applications. While many systems offer inference capabilities, the more significant challenge is that of learning meaningful and interpretable symbolic representations from data. In that regard, inductive logic programming and related techniques have paved much of the way for the last few decades. 
 Unfortunately, a major limitation of this exciting landscape is that much of the work is limited to finite-domain discrete probability distributions. Recently, a handful of systems have been extended to represent and perform inference with continuous distributions. The problem, of course, is that classical solutions for inference are either restricted to well-known parametric families (e.g., Gaussians) or resort to sampling strategies that provide correct answers only in the limit. When it comes to learning, moreover, inducing representations remains entirely open, other than "data-fitting" solutions that force-fit points to aforementioned parametric families. 
 In this paper, we take the first steps towards inducing probabilistic logic programs for continuous and mixed discrete-continuous data, without being pigeon-holed to a fixed set of distribution families. Our key insight is to leverage techniques from piecewise polynomial function approximation theory, yielding a principled way to learn and compositionally construct density functions. We test the framework and discuss the learned representations.

##### Abstract (translated by Google)
统计关系学习领域旨在统一逻辑和概率来推理和学习数据。也许该领域最成功的范例是概率逻辑编程：逻辑编程中随机基元的启用，现在越来越多地被视为复杂机器学习应用程序的声明背景。虽然许多系统提供推理功能，但更重要的挑战是从数据中学习有意义和可解释的符号表示。在这方面，归纳逻辑程序设计和相关技术在过去几十年中铺平了很多道路。
 不幸的是，这个令人兴奋的景观的一个主要限制是大部分工作仅限于有限域离散概率分布。最近，一些系统已经扩展到用连续分布表示和执行推理。当然，问题在于用于推理的经典解决方案要么限于众所周知的参数族（例如，高斯人），要么采用仅在极限情况下提供正确答案的采样策略。此外，在学习方面，除了“数据拟合”解决方案之外，诱导表示仍然是完全开放的，而这些解决方案将点拟合到上述参数族。
 在本文中，我们采取了第一步，为连续和混合离散连续数据引入概率逻辑程序，而不是将其分配到一组固定的分布族。我们的主要观点是利用分段多项式函数逼近理论中的技术，产生一种学习和组合构建密度函数的原则方法。我们测试框架并讨论学习的表示。

##### URL
[http://arxiv.org/abs/1807.05527](http://arxiv.org/abs/1807.05527)

##### PDF
[http://arxiv.org/pdf/1807.05527](http://arxiv.org/pdf/1807.05527)

