---
layout: post
title: "On Inductive Biases in Deep Reinforcement Learning"
date: 2019-07-05 16:14:55
categories: arXiv_AI
tags: arXiv_AI Knowledge Face Reinforcement_Learning
author: Matteo Hessel, Hado van Hasselt, Joseph Modayil, David Silver
mathjax: true
---

* content
{:toc}

##### Abstract
Many deep reinforcement learning algorithms contain inductive biases that sculpt the agent's objective and its interface to the environment. These inductive biases can take many forms, including domain knowledge and pretuned hyper-parameters. In general, there is a trade-off between generality and performance when algorithms use such biases. Stronger biases can lead to faster learning, but weaker biases can potentially lead to more general algorithms. This trade-off is important because inductive biases are not free; substantial effort may be required to obtain relevant domain knowledge or to tune hyper-parameters effectively. In this paper, we re-examine several domain-specific components that bias the objective and the environmental interface of common deep reinforcement learning agents. We investigated whether the performance deteriorates when these components are replaced with adaptive solutions from the literature. In our experiments, performance sometimes decreased with the adaptive components, as one might expect when comparing to components crafted for the domain, but sometimes the adaptive components performed better. We investigated the main benefit of having fewer domain-specific components, by comparing the learning performance of the two systems on a different set of continuous control problems, without additional tuning of either system. As hypothesized, the system with adaptive components performed better on many of the new tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02908](http://arxiv.org/abs/1907.02908)

##### PDF
[http://arxiv.org/pdf/1907.02908](http://arxiv.org/pdf/1907.02908)

