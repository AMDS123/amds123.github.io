---
layout: post
title: "Domain Adversarial Reinforcement Learning for Partial Domain Adaptation"
date: 2019-05-10 12:02:32
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Reinforcement_Learning
author: Jin Chen, Xinxiao Wu, Lixin Duan, Shenghua Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Partial domain adaptation aims to transfer knowledge from a label-rich source domain to a label-scarce target domain which relaxes the fully shared label space assumption across different domains. In this more general and practical scenario, a major challenge is how to select source instances in the shared classes across different domains for positive transfer. To address this issue, we propose a Domain Adversarial Reinforcement Learning (DARL) framework to automatically select source instances in the shared classes for circumventing negative transfer as well as to simultaneously learn transferable features between domains by reducing the domain shift. Specifically, in this framework, we employ deep Q-learning to learn policies for an agent to make selection decisions by approximating the action-value function. Moreover, domain adversarial learning is introduced to learn domain-invariant features for the selected source instances by the agent and the target instances, and also to determine rewards for the agent based on how relevant the selected source instances are to the target domain. Experiments on several benchmark datasets demonstrate that the superior performance of our DARL method over existing state of the arts for partial domain adaptation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04094](http://arxiv.org/abs/1905.04094)

##### PDF
[http://arxiv.org/pdf/1905.04094](http://arxiv.org/pdf/1905.04094)

