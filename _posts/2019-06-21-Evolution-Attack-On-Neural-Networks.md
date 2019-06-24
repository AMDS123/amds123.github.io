---
layout: post
title: "Evolution Attack On Neural Networks"
date: 2019-06-21 11:22:03
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Optimization
author: YiGui Luo, RuiJia Yang, Wei Sha, WeiYi Ding, YouTeng Sun, YiSi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Many studies have been done to prove the vulnerability of neural networks to adversarial example. A trained and well-behaved model can be fooled by a visually imperceptible perturbation, i.e., an originally correctly classified image could be misclassified after a slight perturbation. In this paper, we propose a black-box strategy to attack such networks using an evolution algorithm. First, we formalize the generation of an adversarial example into the optimization problem of perturbations that represent the noise added to an original image at each pixel. To solve this optimization problem in a black-box way, we find that an evolution algorithm perfectly meets our requirement since it can work without any gradient information. Therefore, we test various evolution algorithms, including a simple genetic algorithm, a parameter-exploring policy gradient, an OpenAI evolution strategy, and a covariance matrix adaptive evolution strategy. Experimental results show that a covariance matrix adaptive evolution Strategy performs best in this optimization problem. Additionally, we also perform several experiments to explore the effect of different regularizations on improving the quality of an adversarial example.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09072](http://arxiv.org/abs/1906.09072)

##### PDF
[http://arxiv.org/pdf/1906.09072](http://arxiv.org/pdf/1906.09072)

