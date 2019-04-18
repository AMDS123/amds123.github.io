---
layout: post
title: "Posterior-regularized REINFORCE for Instance Selection in Distant Supervision"
date: 2019-04-17 02:21:51
categories: arXiv_CL
tags: arXiv_CL Regularization Reinforcement_Learning Relation
author: Qi Zhang, Siliang Tang, Xiang Ren, Fei Wu, Shiliang Pu, Yueting Zhuang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper provides a new way to improve the efficiency of the REINFORCE training process. We apply it to the task of instance selection in distant supervision. Modeling the instance selection in one bag as a sequential decision process, a reinforcement learning agent is trained to determine whether an instance is valuable or not and construct a new bag with less noisy instances. However unbiased methods, such as REINFORCE, could usually take much time to train. This paper adopts posterior regularization (PR) to integrate some domain-specific rules in instance selection using REINFORCE. As the experiment results show, this method remarkably improves the performance of the relation classifier trained on cleaned distant supervision dataset as well as the efficiency of the REINFORCE training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08051](http://arxiv.org/abs/1904.08051)

##### PDF
[http://arxiv.org/pdf/1904.08051](http://arxiv.org/pdf/1904.08051)

