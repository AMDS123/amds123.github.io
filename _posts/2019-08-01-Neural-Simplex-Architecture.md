---
layout: post
title: "Neural Simplex Architecture"
date: 2019-08-01 17:39:18
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Dung Phan, Nicola Paoletti, Radu Grosu, Nils Jansen, Scott A. Smolka, Scott D. Stoller
mathjax: true
---

* content
{:toc}

##### Abstract
We present the Neural Simplex Architecture (NSA), a new approach to runtime assurance that provides safety guarantees for neural controllers (obtained e.g. using reinforcement learning) of complex autonomous and other cyber-physical systems without unduly sacrificing performance. NSA is inspired by the Simplex control architecture of Sha et al., but with some significant differences. In the traditional Simplex approach, the advanced controller (AC) is treated as a black box; there are no techniques for correcting the AC after it generates a potentially unsafe control input that causes a failover to the BC. Our NSA addresses this limitation. NSA not only provides safety assurances for CPSs in the presence of a possibly faulty neural controller, but can also improve the safety of such a controller in an online setting via retraining, without degrading its performance. NSA also offers reverse switching strategies, which allow the AC to resume control of the system under reasonable conditions, allowing the mission to continue unabated. Our experimental results on several significant case studies, including a target-seeking ground rover navigating an obstacle field and a neural controller for an artificial pancreas system, demonstrate NSA's benefits.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00528](http://arxiv.org/abs/1908.00528)

##### PDF
[http://arxiv.org/pdf/1908.00528](http://arxiv.org/pdf/1908.00528)

