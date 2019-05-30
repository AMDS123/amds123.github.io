---
layout: post
title: "LeTS-Drive: Driving in a Crowd by Learning from Tree Search"
date: 2019-05-29 03:27:01
categories: arXiv_AI
tags: arXiv_AI Deep_Learning
author: Panpan Cai, Yuanfu Luo, Aseem Saxena, David Hsu, Wee Sun Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomous driving in a crowded environment, e.g., a busy traffic intersection, is an unsolved challenge for robotics. The robot vehicle must contend with a dynamic and partially observable environment, noisy sensors, and many agents. A principled approach is to formalize it as a Partially Observable Markov Decision Process (POMDP) and solve it through online belief-tree search. To handle a large crowd and achieve real-time performance in this very challenging setting, we propose LeTS-Drive, which integrates online POMDP planning and deep learning. It consists of two phases. In the offline phase, we learn a policy and the corresponding value function by imitating the belief tree search. In the online phase, the learned policy and value function guide the belief tree search. LeTS-Drive leverages the robustness of planning and the runtime efficiency of learning to enhance the performance of both. Experimental results in simulation show that LeTS-Drive outperforms either planning or imitation learning alone and develops sophisticated driving skills.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12197](http://arxiv.org/abs/1905.12197)

##### PDF
[http://arxiv.org/pdf/1905.12197](http://arxiv.org/pdf/1905.12197)

