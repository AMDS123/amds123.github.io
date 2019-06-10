---
layout: post
title: "Sample-Efficient Reinforcement Learning with Stochastic Ensemble Value Expansion"
date: 2019-06-07 16:39:35
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Jacob Buckman, Danijar Hafner, George Tucker, Eugene Brevdo, Honglak Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Integrating model-free and model-based approaches in reinforcement learning has the potential to achieve the high performance of model-free algorithms with low sample complexity. However, this is difficult because an imperfect dynamics model can degrade the performance of the learning algorithm, and in sufficiently complex environments, the dynamics model will almost always be imperfect. As a result, a key challenge is to combine model-based approaches with model-free learning in such a way that errors in the model do not degrade performance. We propose stochastic ensemble value expansion (STEVE), a novel model-based technique that addresses this issue. By dynamically interpolating between model rollouts of various horizon lengths for each individual example, STEVE ensures that the model is only utilized when doing so does not introduce significant errors. Our approach outperforms model-free baselines on challenging continuous control benchmarks with an order-of-magnitude increase in sample efficiency, and in contrast to previous model-based approaches, performance does not degrade in complex environments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.01675](http://arxiv.org/abs/1807.01675)

##### PDF
[http://arxiv.org/pdf/1807.01675](http://arxiv.org/pdf/1807.01675)

