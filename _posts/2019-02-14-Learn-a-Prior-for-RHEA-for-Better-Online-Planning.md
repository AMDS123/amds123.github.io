---
layout: post
title: "Learn a Prior for RHEA for Better Online Planning"
date: 2019-02-14 09:56:00
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Xin Tong, Weiming Liu, Bin Li
mathjax: true
---

* content
{:toc}

##### Abstract
Rolling Horizon Evolutionary Algorithms (RHEA) are a class of online planning methods for real-time game playing; their performance is closely related to the planning horizon and the search time allowed. In this paper, we propose to learn a prior for RHEA in an offline manner by training a value network and a policy network. The value network is used to reduce the planning horizon by providing an estimation of future rewards, and the policy network is used to initialize the population, which helps to narrow down the search scope. The proposed algorithm, named prior-based RHEA (p-RHEA), trains policy and value networks by performing planning and learning iteratively. In the planning stage, the horizon-limited search assisted with the policy network and value network is performed to improve the policies and collect training samples. In the learning stage, the policy network and value network are trained with the collected samples to learn better prior knowledge. Experimental results on OpenAI Gym MuJoCo tasks show that the performance of the proposed p-RHEA is significantly improved compared to that of RHEA.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05284](http://arxiv.org/abs/1902.05284)

##### PDF
[http://arxiv.org/pdf/1902.05284](http://arxiv.org/pdf/1902.05284)

