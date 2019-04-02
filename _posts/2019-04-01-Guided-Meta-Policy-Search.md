---
layout: post
title: "Guided Meta-Policy Search"
date: 2019-04-01 16:47:28
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Russell Mendonca, Abhishek Gupta, Rosen Kralev, Pieter Abbeel, Sergey Levine, Chelsea Finn
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning (RL) algorithms have demonstrated promising results on complex tasks, yet often require impractical numbers of samples because they learn from scratch. Meta-RL aims to address this challenge by leveraging experience from previous tasks in order to more quickly solve new tasks. However, in practice, these algorithms generally also require large amounts of on-policy experience during the meta-training process, making them impractical for use in many problems. To this end, we propose to learn a reinforcement learning procedure through imitation of expert policies that solve previously-seen tasks. This involves a nested optimization, with RL in the inner loop and supervised imitation learning in the outer loop. Because the outer loop imitation learning can be done with off-policy data, we can achieve significant gains in meta-learning sample efficiency. In this paper, we show how this general idea can be used both for meta-reinforcement learning and for learning fast RL procedures from multi-task demonstration data. The former results in an approach that can leverage policies learned for previous tasks without significant amounts of on-policy data during meta-training, whereas the latter is particularly useful in cases where demonstrations are easy for a person to provide. Across a number of continuous control meta-RL problems, we demonstrate significant improvements in meta-RL sample efficiency in comparison to prior work as well as the ability to scale to domains with visual observations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00956](http://arxiv.org/abs/1904.00956)

##### PDF
[http://arxiv.org/pdf/1904.00956](http://arxiv.org/pdf/1904.00956)

