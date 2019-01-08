---
layout: post
title: "Deep Reinforcement Learning for Imbalanced Classification"
date: 2019-01-05 07:59:47
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Classification
author: Enlu Lin, Qiong Chen, Xiaoming Qi
mathjax: true
---

* content
{:toc}

##### Abstract
Data in real-world application often exhibit skewed class distribution which poses an intense challenge for machine learning. Conventional classification algorithms are not effective in the case of imbalanced data distribution, and may fail when the data distribution is highly imbalanced. To address this issue, we propose a general imbalanced classification model based on deep reinforcement learning. We formulate the classification problem as a sequential decision-making process and solve it by deep Q-learning network. The agent performs a classification action on one sample at each time step, and the environment evaluates the classification action and returns a reward to the agent. The reward from minority class sample is larger so the agent is more sensitive to the minority class. The agent finally finds an optimal classification policy in imbalanced data under the guidance of specific reward function and beneficial learning environment. Experiments show that our proposed model outperforms the other imbalanced classification algorithms, and it can identify more minority samples and has great classification performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01379](http://arxiv.org/abs/1901.01379)

##### PDF
[http://arxiv.org/pdf/1901.01379](http://arxiv.org/pdf/1901.01379)

