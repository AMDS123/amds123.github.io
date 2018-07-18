---
layout: post
title: "Preference-Based Monte Carlo Tree Search"
date: 2018-07-17 09:04:35
categories: arXiv_AI
tags: arXiv_AI Quantitative
author: Tobias Joppen, Christian Wirth, Johannes F&#xfc;rnkranz
mathjax: true
---

* content
{:toc}

##### Abstract
Monte Carlo tree search (MCTS) is a popular choice for solving sequential anytime problems. However, it depends on a numeric feedback signal, which can be difficult to define. Real-time MCTS is a variant which may only rarely encounter states with an explicit, extrinsic reward. To deal with such cases, the experimenter has to supply an additional numeric feedback signal in the form of a heuristic, which intrinsically guides the agent. Recent work has shown evidence that in different areas the underlying structure is ordinal and not numerical. Hence erroneous and biased heuristics are inevitable, especially in such domains. In this paper, we propose a MCTS variant which only depends on qualitative feedback, and therefore opens up new applications for MCTS. We also find indications that translating absolute into ordinal feedback may be beneficial. Using a puzzle domain, we show that our preference-based MCTS variant, wich only receives qualitative feedback, is able to reach a performance level comparable to a regular MCTS baseline, which obtains quantitative feedback.

##### Abstract (translated by Google)
蒙特卡罗树搜索（MCTS）是解决顺序随时出现问题的流行选择。但是，它取决于数字反馈信号，这可能很难定义。实时MCTS是一种变体，可能很少遇到具有明确的外在奖励的状态。为了处理这种情况，实验者必须以启发式的形式提供额外的数字反馈信号，其本质上引导代理。最近的工作已经证明，在不同的领域，基础结构是有序的而不是数字的。因此，错误和偏见的启发式方法是不可避免的，尤其是在这些领域。在本文中，我们提出了一种仅依赖于定性反馈的MCTS变体，因此为MCTS开辟了新的应用。我们还发现将绝对转换为有序反馈的迹象可能是有益的。使用谜题域，我们表明我们的基于偏好的MCTS变体只能接收定性反馈，能够达到与常规MCTS基线相当的性能水平，从而获得定量反馈。

##### URL
[http://arxiv.org/abs/1807.06286](http://arxiv.org/abs/1807.06286)

##### PDF
[http://arxiv.org/pdf/1807.06286](http://arxiv.org/pdf/1807.06286)

