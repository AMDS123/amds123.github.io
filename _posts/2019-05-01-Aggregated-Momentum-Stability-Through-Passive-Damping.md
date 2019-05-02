---
layout: post
title: "Aggregated Momentum: Stability Through Passive Damping"
date: 2019-05-01 14:09:52
categories: arXiv_AI
tags: arXiv_AI Gradient_Descent
author: James Lucas, Shengyang Sun, Richard Zemel, Roger Grosse
mathjax: true
---

* content
{:toc}

##### Abstract
Momentum is a simple and widely used trick which allows gradient-based optimizers to pick up speed along low curvature directions. Its performance depends crucially on a damping coefficient $\beta$. Large $\beta$ values can potentially deliver much larger speedups, but are prone to oscillations and instability; hence one typically resorts to small values such as 0.5 or 0.9. We propose Aggregated Momentum (AggMo), a variant of momentum which combines multiple velocity vectors with different $\beta$ parameters. AggMo is trivial to implement, but significantly dampens oscillations, enabling it to remain stable even for aggressive $\beta$ values such as 0.999. We reinterpret Nesterov's accelerated gradient descent as a special case of AggMo and analyze rates of convergence for quadratic objectives. Empirically, we find that AggMo is a suitable drop-in replacement for other momentum methods, and frequently delivers faster convergence.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.00325](http://arxiv.org/abs/1804.00325)

##### PDF
[http://arxiv.org/pdf/1804.00325](http://arxiv.org/pdf/1804.00325)

