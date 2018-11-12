---
layout: post
title: "Long Short-Term Memory with Dynamic Skip Connections"
date: 2018-11-09 12:11:22
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning RNN Prediction Relation
author: Tao Gui, Qi Zhang, Lujun Zhao, Yaosong Lin, Minlong Peng, Jingjing Gong, Xuanjing Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, long short-term memory (LSTM) has been successfully used to model sequential data of variable length. However, LSTM can still experience difficulty in capturing long-term dependencies. In this work, we tried to alleviate this problem by introducing a dynamic skip connection, which can learn to directly connect two dependent words. Since there is no dependency information in the training data, we propose a novel reinforcement learning-based method to model the dependency relationship and connect dependent words. The proposed model computes the recurrent transition functions based on the skip connections, which provides a dynamic skipping advantage over RNNs that always tackle entire sentences sequentially. Our experimental results on three natural language processing tasks demonstrate that the proposed method can achieve better performance than existing methods. In the number prediction experiment, the proposed model outperformed LSTM with respect to accuracy by nearly 20%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03873](http://arxiv.org/abs/1811.03873)

##### PDF
[http://arxiv.org/pdf/1811.03873](http://arxiv.org/pdf/1811.03873)

