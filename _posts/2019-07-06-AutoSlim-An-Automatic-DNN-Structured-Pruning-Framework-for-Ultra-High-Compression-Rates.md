---
layout: post
title: "AutoSlim: An Automatic DNN Structured Pruning Framework for Ultra-High Compression Rates"
date: 2019-07-06 15:40:02
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Inference
author: Ning Liu, Xiaolong Ma, Zhiyuan Xu, Yanzhi Wang, Jian Tang, Jieping Ye
mathjax: true
---

* content
{:toc}

##### Abstract
Structured weight pruning is a representative model compression technique of DNNs to reduce the storage and computation requirements and accelerate inference. An automatic hyperparameter determination process is necessary due to the large number of flexible hyperparameters. This work proposes AutoSlim, an automatic structured pruning framework with the following key performance improvements: (i) effectively incorporate the combination of structured pruning schemes in the automatic process; (ii) adopt the state-of-art ADMM-based structured weight pruning as the core algorithm, and propose an innovative additional purification step for further weight reduction without accuracy loss; and (iii) develop effective heuristic search method enhanced by experience-based guided search, replacing the prior deep reinforcement learning technique which has underlying incompatibility with the target pruning problem. Extensive experiments on CIFAR-10 and ImageNet datasets demonstrate that AutoSlim is the key to achieve ultra-high pruning rates on the number of weights and FLOPs that cannot be achieved before. As an example, AutoSlim outperforms the prior work on automatic model compression by up to 33$\times$ in pruning rate under the same accuracy. We release all models of this work at anonymous link: <a href="http://bit.ly/2VZ63dS.">this http URL</a>

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03141](http://arxiv.org/abs/1907.03141)

##### PDF
[http://arxiv.org/pdf/1907.03141](http://arxiv.org/pdf/1907.03141)

