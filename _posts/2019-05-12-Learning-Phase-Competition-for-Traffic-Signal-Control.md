---
layout: post
title: "Learning Phase Competition for Traffic Signal Control"
date: 2019-05-12 13:31:04
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Guanjie Zheng, Yuanhao Xiong, Xinshi Zang, Jie Feng, Hua Wei, Huichu Zhang, Yong Li, Kai Xu, Zhenhui Li
mathjax: true
---

* content
{:toc}

##### Abstract
Increasingly available city data and advanced learning techniques have empowered people to improve the efficiency of our city functions. Among them, improving the urban transportation efficiency is one of the most prominent topics. Recent studies have proposed to use reinforcement learning (RL) for traffic signal control. Different from traditional transportation approaches which rely heavily on prior knowledge, RL can learn directly from the feedback. On the other side, without a careful model design, existing RL methods typically take a long time to converge and the learned models may not be able to adapt to new scenarios. For example, a model that is trained well for morning traffic may not work for the afternoon traffic because the traffic flow could be reversed, resulting in a very different state representation. In this paper, we propose a novel design called FRAP, which is based on the intuitive principle of phase competition in traffic signal control: when two traffic signals conflict, priority should be given to one with larger traffic movement (i.e., higher demand). Through the phase competition modeling, our model achieves invariance to symmetrical cases such as flipping and rotation in traffic flow. By conducting comprehensive experiments, we demonstrate that our model finds better solutions than existing RL methods in the complicated all-phase selection problem, converges much faster during training, and achieves superior generalizability for different road structures and traffic conditions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04722](http://arxiv.org/abs/1905.04722)

##### PDF
[http://arxiv.org/pdf/1905.04722](http://arxiv.org/pdf/1905.04722)

