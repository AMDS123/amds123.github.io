---
layout: post
title: "Uncertainty-guided Continual Learning with Bayesian Neural Networks"
date: 2019-06-06 05:40:25
categories: arXiv_AI
tags: arXiv_AI Regularization Knowledge Classification
author: Sayna Ebrahimi, Mohamed Elhoseiny, Trevor Darrell, Marcus Rohrbach
mathjax: true
---

* content
{:toc}

##### Abstract
Continual learning aims to learn new tasks without forgetting previously learned ones. This is especially challenging when one cannot access data from previous tasks and when the model has a fixed capacity. Current regularization-based continual learning algorithms need an external representation and extra computation to measure the parameters' importance. In contrast, we propose Uncertainty-guided Continual Bayesian Neural Networks (UCB), where the learning rate adapts according to the uncertainty defined in the probability distribution of the weights in networks. Uncertainty is a natural way to identify what to remember and what to change as we continually learn, allowing to mitigate catastrophic forgetting. We also show a variant of our model, which uses uncertainty for weight pruning and retains task performance after pruning by saving binary masks per tasks. We evaluate our UCB approach extensively on diverse object classification datasets with short and long sequences of tasks and report superior or on-par performance compared to existing approaches. Additionally, we show that our model does not necessarily need task information at test time, i.e. it does not presume knowledge of which task a sample belongs to.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02425](http://arxiv.org/abs/1906.02425)

##### PDF
[http://arxiv.org/pdf/1906.02425](http://arxiv.org/pdf/1906.02425)

