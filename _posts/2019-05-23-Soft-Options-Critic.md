---
layout: post
title: "Soft Options Critic"
date: 2019-05-23 21:27:11
categories: arXiv_AI
tags: arXiv_AI
author: Elita Lobo, Scott Jordan
mathjax: true
---

* content
{:toc}

##### Abstract
The option-critic paper and several variants have successfully demonstrated the use of the options framework proposed by Barto et al to scale learning and planning in hierarchical tasks. Although most of these frameworks use entropy as a regularizer to improve exploration, they do not maximize entropy along with returns at every time step. In this paper we investigate the effect of maximizing entropy of each options and inter-option policy in options framework. We adopt the architecture of the recently introduced soft-actor critic algorithm to enable learning of robust options in continuous and discrete action spaces in a off-policy manner thus also making it sample efficient. In this paper we derive the soft options improvement theorem and propose a novel soft-options framework to incorporate maximization of entropy of actions and options in a constrained manner. Our experiments show that maximizing entropy of actions and options in a constrained manner with high learning rate does not harm the main objective of maximizing returns and hence outperforms vanilla options-critic framework in most hierarchical tasks. We also observe faster recovery when the environment is subject to perturbations.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11222](https://arxiv.org/abs/1905.11222)

##### PDF
[https://arxiv.org/pdf/1905.11222](https://arxiv.org/pdf/1905.11222)

