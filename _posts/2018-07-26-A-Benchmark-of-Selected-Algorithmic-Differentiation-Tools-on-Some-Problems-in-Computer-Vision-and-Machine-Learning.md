---
layout: post
title: "A Benchmark of Selected Algorithmic Differentiation Tools on Some Problems in Computer Vision and Machine Learning"
date: 2018-07-26 13:42:30
categories: arXiv_CV
tags: arXiv_CV
author: Filip &#x160;rajer, Zuzana Kukelova, Andrew Fitzgibbon
mathjax: true
---

* content
{:toc}

##### Abstract
Algorithmic differentiation (AD) allows exact computation of derivatives given only an implementation of an objective function. Although many AD tools are available, a proper and efficient implementation of AD methods is not straightforward. The existing tools are often too different to allow for a general test suite. In this paper, we compare fifteen ways of computing derivatives including eleven automatic differentiation tools implementing various methods and written in various languages (C++, F#, MATLAB, Julia and Python), two symbolic differentiation tools, finite differences, and hand-derived computation. 
 We look at three objective functions from computer vision and machine learning. These objectives are for the most part simple, in the sense that no iterative loops are involved, and conditional statements are encapsulated in functions such as {\tt abs} or {\tt logsumexp}. However, it is important for the success of algorithmic differentiation that such `simple' objective functions are handled efficiently, as so many problems in computer vision and machine learning are of this form. 
 Of course, our results depend on programmer skill, and familiarity with the tools. However, we contend that this paper presents an important datapoint: a skilled programmer devoting roughly a week to each tool produced the timings we present. We have made our implementations available as open source to allow the community to replicate and update these benchmarks.

##### Abstract (translated by Google)
算法区分（AD）允许仅给出目标函数的实现来精确计算导数。尽管可以使用许多AD工具，但是AD方法的正确且有效的实现并不简单。现有工具通常太不同，不允许使用通用测试套件。在本文中，我们比较了十五种计算衍生物的方法，包括十一种实现各种方法的自动微分工具，用各种语言编写（C ++，F＃，MATLAB，Julia和Python），两种符号微分工具，有限差分和手工衍生计算。
 我们从计算机视觉和机器学习中看到三个目标函数。这些目标在很大程度上是简单的，因为没有涉及迭代循环，并且条件语句被封装在诸如{\ tt abs}或{\ tt logsumexp}之类的函数中。然而，对于算法区分的成功而言，这种“简单”的目标函数被有效处理是很重要的，因为计算机视觉和机器学习中的许多问题都是这种形式。
 当然，我们的结果取决于程序员的技能，以及对工具的熟悉程度。然而，我们认为本文提出了一个重要的数据点：熟练的程序员在每个工具上花费大约一周的时间来生成我们提出的时间。我们已将我们的实现作为开源提供，以允许社区复制和更新这些基准。

##### URL
[http://arxiv.org/abs/1807.10129](http://arxiv.org/abs/1807.10129)

##### PDF
[http://arxiv.org/pdf/1807.10129](http://arxiv.org/pdf/1807.10129)

