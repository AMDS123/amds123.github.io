---
layout: post
title: "Progressive Relation Learning for Group Activity Recognition"
date: 2019-08-08 06:50:42
categories: arXiv_CV
tags: arXiv_CV Attention Reinforcement_Learning Relation Recognition
author: Guyue Hu, Bo Cui, Yuan He, Shan Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Group activities usually involve spatio-temporal dynamics among many interactive individuals, while only a few participants at several key frames essentially define the activity. Therefore, effectively modeling the group-relevant and suppressing the irrelevant actions (and interactions) are vital for group activity recognition. In this paper, we propose a novel method based on deep reinforcement learning to progressively refine the low-level features and high-level relations of group activities. Firstly, we construct a semantic relation graph (SRG) to explicitly model the relations among persons. Then, two agents adopting policy according to two Markov decision processes are applied to progressively refine the SRG. Specifically, one feature-distilling (FD) agent in the discrete action space refines the low-level spatio-temporal features by distilling the most informative frames. Another relation-gating (RG) agent in continuous action space adjusts the high-level semantic graph to pay more attention to group-relevant relations. The SRG, FD agent, and RG agent are optimized alternately to mutually boost the performance of each other. Extensive experiments on two widely used benchmarks demonstrate the effectiveness and superiority of the proposed approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02948](http://arxiv.org/abs/1908.02948)

##### PDF
[http://arxiv.org/pdf/1908.02948](http://arxiv.org/pdf/1908.02948)

