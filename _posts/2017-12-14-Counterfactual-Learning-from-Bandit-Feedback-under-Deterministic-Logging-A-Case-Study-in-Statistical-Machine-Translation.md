---
layout: post
title: "Counterfactual Learning from Bandit Feedback under Deterministic Logging: A Case Study in Statistical Machine Translation"
date: 2017-12-14 13:44:31
categories: arXiv_CL
tags: arXiv_CL
author: Carolin Lawrence, Artem Sokolov, Stefan Riezler
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of counterfactual learning for statistical machine translation (SMT) is to optimize a target SMT system from logged data that consist of user feedback to translations that were predicted by another, historic SMT system. A challenge arises by the fact that risk-averse commercial SMT systems deterministically log the most probable translation. The lack of sufficient exploration of the SMT output space seemingly contradicts the theoretical requirements for counterfactual learning. We show that counterfactual learning from deterministic bandit logs is possible nevertheless by smoothing out deterministic components in learning. This can be achieved by additive and multiplicative control variates that avoid degenerate behavior in empirical risk minimization. Our simulation experiments show improvements of up to 2 BLEU points by counterfactual learning from deterministic bandit feedback.

##### Abstract (translated by Google)
针对统计机器翻译（SMT）的反事实学习的目标是从记录数据中优化目标SMT系统，所述记录数据由用户反馈到由另一个历史性SMT系统预测的翻译。一个挑战来自这样的事实，即规避风险的商业SMT系统确定性地记录最可能的翻译。对SMT输出空间缺乏足够的探索似乎与反事实学习的理论要求相矛盾。我们表明，从确定性的土匪日志反事实学习是可能的，然而通过平滑学习中的确定性组件。这可以通过在经验风险最小化时避免退化行为的加法和乘法控制变量来实现。我们的仿真实验显示通过从确定性的强盗反馈中反事实地学习，可以提高多达2个BLEU点。

##### URL
[http://arxiv.org/abs/1707.09118](http://arxiv.org/abs/1707.09118)

##### PDF
[http://arxiv.org/pdf/1707.09118](http://arxiv.org/pdf/1707.09118)

