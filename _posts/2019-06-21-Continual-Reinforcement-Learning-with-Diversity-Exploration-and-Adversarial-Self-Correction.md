---
layout: post
title: "Continual Reinforcement Learning with Diversity Exploration and Adversarial Self-Correction"
date: 2019-06-21 15:44:41
categories: arXiv_AI
tags: arXiv_AI Adversarial Knowledge Reinforcement_Learning
author: Fengda Zhu, Xiaojun Chang, Runhao Zeng, Mingkui Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning has made significant progress in the field of continuous control, such as physical control and autonomous driving. However, it is challenging for a reinforcement model to learn a policy for each task sequentially due to catastrophic forgetting. Specifically, the model would forget knowledge it learned in the past when trained on a new task. We consider this challenge from two perspectives: i) acquiring task-specific skills is difficult since task information and rewards are not highly related; ii) learning knowledge from previous experience is difficult in continuous control domains. In this paper, we introduce an end-to-end framework namely Continual Diversity Adversarial Network (CDAN). We first develop an unsupervised diversity exploration method to learn task-specific skills using an unsupervised objective. Then, we propose an adversarial self-correction mechanism to learn knowledge by exploiting past experience. The two learning procedures are presumably reciprocal. To evaluate the proposed method, we propose a new continuous reinforcement learning environment named Continual Ant Maze (CAM) and a new metric termed Normalized Shorten Distance (NSD). The experimental results confirm the effectiveness of diversity exploration and self-correction. It is worthwhile noting that our final result outperforms baseline by 18.35% in terms of NSD, and 0.61 according to the average reward.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09205](http://arxiv.org/abs/1906.09205)

##### PDF
[http://arxiv.org/pdf/1906.09205](http://arxiv.org/pdf/1906.09205)

