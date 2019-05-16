---
layout: post
title: "Reinforcement Learning for Robotics and Control with Active Uncertainty Reduction"
date: 2019-05-15 16:21:05
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Optimization
author: Narendra Patwardhan, Zequn Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Model-free reinforcement learning based methods such as Proximal Policy Optimization, or Q-learning typically require thousands of interactions with the environment to approximate the optimum controller which may not always be feasible in robotics due to safety and time consumption. Model-based methods such as PILCO or BlackDrops, while data-efficient, provide solutions with limited robustness and complexity. To address this tradeoff, we introduce active uncertainty reduction-based virtual environments, which are formed through limited trials conducted in the original environment. We provide an efficient method for uncertainty management, which is used as a metric for self-improvement by identification of the points with maximum expected improvement through adaptive sampling. Capturing the uncertainty also allows for better mimicking of the reward responses of the original system. Our approach enables the use of complex policy structures and reward functions through a unique combination of model-based and model-free methods, while still retaining the data efficiency. We demonstrate the validity of our method on several classic reinforcement learning problems in OpenAI gym. We prove that our approach offers a better modeling capacity for complex system dynamics as compared to established methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.06274](http://arxiv.org/abs/1905.06274)

##### PDF
[http://arxiv.org/pdf/1905.06274](http://arxiv.org/pdf/1905.06274)

