---
layout: post
title: "Decomposition Methods with Deep Corrections for Reinforcement Learning"
date: 2019-04-22 19:54:27
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Maxime Bouton, Kyle Julian, Alireza Nakhaei, Kikuo Fujimura, Mykel J. Kochenderfer
mathjax: true
---

* content
{:toc}

##### Abstract
Decomposition methods have been proposed to approximate solutions to large sequential decision making problems. In contexts where an agent interacts with multiple entities, utility decomposition can be used to separate the global objective into local tasks considering each individual entity independently. An arbitrator is then responsible for combining the individual utilities and selecting an action in real time to solve the global problem. Although these techniques can perform well empirically, they rely on strong assumptions of independence between the local tasks and sacrifice the optimality of the global solution. This paper proposes an approach that improves upon such approximate solutions by learning a correction term represented by a neural network. We demonstrate this approach on a fisheries management problem where multiple boats must coordinate to maximize their catch over time as well as on a pedestrian avoidance problem for autonomous driving. In each problem, decomposition methods can scale to multiple boats or pedestrians by using strategies involving one entity. We verify empirically that the proposed correction method significantly improves the decomposition method and outperforms a policy trained on the full scale problem without utility decomposition.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.01772](http://arxiv.org/abs/1802.01772)

##### PDF
[http://arxiv.org/pdf/1802.01772](http://arxiv.org/pdf/1802.01772)

