---
layout: post
title: "Closed-form Preintegration Methods for Graph-based Visual-Inertial Navigation"
date: 2019-03-20 17:22:55
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Kevin Eckenhoff, Patrick Geneva, Guoquan Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a new analytical preintegration theory for graph-based sensor fusion with an inertial measurement unit (IMU) and a camera (or other aiding sensors).Rather than using discrete sampling of the measurement dynamics as in current methods,we derive the closed-form solutions to the preintegration equations, yielding improved accuracy in state estimation.We advocate two new different inertial models for preintegration: (i) the model that assumes piecewise constant measurements, and (ii) the model that assumes piecewise constant local true acceleration.We show through extensive Monte-Carlo simulations the effect that the choice of preintegration model has on estimation performance.To validate the proposed preintegration theory, we develop both direct and indirect visual-inertial navigation systems (VINS) that leverage our preintegration.In the first, within a tightly-coupled, sliding-window optimization framework, we jointly estimate the features in the window and the IMU states while performing marginalization to bound the computational cost.In the second, we loosely-couple the IMU preintegration with a direct image alignment that estimates relative camera motion by minimizing the photometric errors (i.e., image intensity difference), allowing for efficient and informative loop closures. Both systems are extensively validated in real-world experiments and are shown to offer competitive performance to state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.02774](http://arxiv.org/abs/1805.02774)

##### PDF
[http://arxiv.org/pdf/1805.02774](http://arxiv.org/pdf/1805.02774)

