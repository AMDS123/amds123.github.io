---
layout: post
title: "Best-Effort Inductive Logic Programming via Fine-grained Cost-based Hypothesis Generation"
date: 2018-02-23 23:08:07
categories: arXiv_AI
tags: arXiv_AI
author: Peter Sch&#xfc;ller, Mishal Benz
mathjax: true
---

* content
{:toc}

##### Abstract
We describe the Inspire system which participated in the first competition on Inductive Logic Programming (ILP). Inspire is based on Answer Set Programming (ASP). The distinguishing feature of Inspire is an ASP encoding for hypothesis space generation: given a set of facts representing the mode bias, and a set of cost configuration parameters, each answer set of this encoding represents a single rule that is considered for finding a hypothesis that entails the given examples. Compared with state-of-the-art methods that use the length of the rule body as a metric for rule complexity, our approach permits a much more fine-grained specification of the shape of hypothesis candidate rules. The Inspire system iteratively increases the rule cost limit and thereby increases the search space until it finds a suitable hypothesis. The system searches for a hypothesis that entails a single example at a time, utilizing an ASP encoding derived from the encoding used in XHAIL. We perform experiments with the development and test set of the ILP competition. For comparison we also adapted the ILASP system to process competition instances. Experimental results show that the cost parameters for the hypothesis search space are an important factor for finding hypotheses to competition instances within tight resource bounds.

##### Abstract (translated by Google)
我们描述了参加第一届感应逻辑编程竞赛（ILP）的Inspire系统。启发是基于应答集编程（ASP）。 Inspire的显着特征是用于假设空间生成的ASP编码：给定表示模式偏差的一组事实以及一组成本配置参数，该编码的每个答案集代表单个规则，该规则被考虑用于找到假设需要给出的例子。与使用规则体的长度作为规则复杂度的度量标准的最先进的方法相比，我们的方法允许更精细地规定假设候选规则的形状。 Inspire系统迭代地增加了规则成本限制，从而增加了搜索空间，直到找到合适的假设为止。系统使用从XHAIL中使用的编码导出的ASP编码，一次搜索一个需要一个示例的假设。我们用ILP竞赛的开发和测试集进行实验。为了比较，我们还调整了ILASP系统来处理竞争情况。实验结果表明，假设搜索空间的成本参数是在严格资源范围内找到竞争实例的假设的重要因素。

##### URL
[http://arxiv.org/abs/1707.02729](http://arxiv.org/abs/1707.02729)

##### PDF
[http://arxiv.org/pdf/1707.02729](http://arxiv.org/pdf/1707.02729)

