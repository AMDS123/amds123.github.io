---
layout: post
title: "Quantifying Infra-Marginality and Its Trade-off with Group Fairness"
date: 2019-09-03 07:24:35
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Arpita Biswas, Siddharth Barman, Amit Deshpande, Amit Sharma
mathjax: true
---

* content
{:toc}

##### Abstract
In critical decision-making scenarios, optimizing accuracy can lead to a biased classifier, hence past work recommends enforcing group-based fairness metrics in addition to maximizing accuracy. However, doing so exposes the classifier to another kind of bias called infra-marginality. This refers to individual-level bias where some individuals/subgroups can be worse off than under simply optimizing for accuracy. For instance, a classifier implementing race-based parity may significantly disadvantage women of the advantaged race. To quantify this bias, we propose a general notion of $\eta$-infra-marginality that can be used to evaluate the extent of this bias. We prove theoretically that, unlike other fairness metrics, infra-marginality does not have a trade-off with accuracy: high accuracy directly leads to low infra-marginality. This observation is confirmed through empirical analysis on multiple simulated and real-world datasets. Further, we find that maximizing group fairness often increases infra-marginality, suggesting the consideration of both group-level fairness and individual-level infra-marginality. However, measuring infra-marginality requires knowledge of the true distribution of individual-level outcomes correctly and explicitly. We propose a practical method to measure infra-marginality, and a simple algorithm to maximize group-wise accuracy and avoid infra-marginality.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00982](http://arxiv.org/abs/1909.00982)

##### PDF
[http://arxiv.org/pdf/1909.00982](http://arxiv.org/pdf/1909.00982)

