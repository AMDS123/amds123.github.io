---
layout: post
title: "Achieving Verified Robustness to Symbol Substitutions via Interval Bound Propagation"
date: 2019-09-03 23:03:10
categories: arXiv_CL
tags: arXiv_CL Adversarial Text_Classification Classification
author: Po-Sen Huang, Robert Stanforth, Johannes Welbl, Chris Dyer, Dani Yogatama, Sven Gowal, Krishnamurthy Dvijotham, Pushmeet Kohli
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks are part of many contemporary NLP systems, yet their empirical successes come at the price of vulnerability to adversarial attacks. Previous work has used adversarial training and data augmentation to partially mitigate such brittleness, but these are unlikely to find worst-case adversaries due to the complexity of the search space arising from discrete text perturbations. In this work, we approach the problem from the opposite direction: to formally verify a system's robustness against a predefined class of adversarial attacks. We study text classification under synonym replacements or character flip perturbations. We propose modeling these input perturbations as a simplex and then using Interval Bound Propagation -- a formal model verification method. We modify the conventional log-likelihood training objective to train models that can be efficiently verified, which would otherwise come with exponential search complexity. The resulting models show only little difference in terms of nominal accuracy, but have much improved verified accuracy under perturbations and come with an efficiently computable formal guarantee on worst case adversaries.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01492](http://arxiv.org/abs/1909.01492)

##### PDF
[http://arxiv.org/pdf/1909.01492](http://arxiv.org/pdf/1909.01492)

