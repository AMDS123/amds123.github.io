---
layout: post
title: "The Termination Critic"
date: 2019-02-26 15:26:10
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Anna Harutyunyan, Will Dabney, Diana Borsa, Nicolas Heess, Remi Munos, Doina Precup
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we consider the problem of autonomously discovering behavioral abstractions, or options, for reinforcement learning agents. We propose an algorithm that focuses on the termination condition, as opposed to -- as is common -- the policy. The termination condition is usually trained to optimize a control objective: an option ought to terminate if another has better value. We offer a different, information-theoretic perspective, and propose that terminations should focus instead on the compressibility of the option's encoding -- arguably a key reason for using abstractions. To achieve this algorithmically, we leverage the classical options framework, and learn the option transition model as a "critic" for the termination condition. Using this model, we derive gradients that optimize the desired criteria. We show that the resulting options are non-trivial, intuitively meaningful, and useful for learning and planning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09996](http://arxiv.org/abs/1902.09996)

##### PDF
[http://arxiv.org/pdf/1902.09996](http://arxiv.org/pdf/1902.09996)

