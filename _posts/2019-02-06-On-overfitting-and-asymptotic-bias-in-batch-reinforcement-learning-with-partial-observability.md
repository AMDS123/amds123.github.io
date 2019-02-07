---
layout: post
title: "On overfitting and asymptotic bias in batch reinforcement learning with partial observability"
date: 2019-02-06 18:30:04
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Vincent Francois-Lavet, Guillaume Rabusseau, Joelle Pineau, Damien Ernst, Raphael Fonteneau
mathjax: true
---

* content
{:toc}

##### Abstract
This paper provides an analysis of the tradeoff between asymptotic bias (suboptimality with unlimited data) and overfitting (additional suboptimality due to limited data) in the context of reinforcement learning with partial observability. Our theoretical analysis formally characterizes that while potentially increasing the asymptotic bias, a smaller state representation decreases the risk of overfitting. This analysis relies on expressing the quality of a state representation by bounding L1 error terms of the associated belief states. Theoretical results are empirically illustrated when the state representation is a truncated history of observations, both on synthetic POMDPs and on a large-scale POMDP in the context of smartgrids, with real-world data. Finally, similarly to known results in the fully observable setting, we also briefly discuss and empirically illustrate how using function approximators and adapting the discount factor may enhance the tradeoff between asymptotic bias and overfitting in the partially observable context.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1709.07796](http://arxiv.org/abs/1709.07796)

##### PDF
[http://arxiv.org/pdf/1709.07796](http://arxiv.org/pdf/1709.07796)

