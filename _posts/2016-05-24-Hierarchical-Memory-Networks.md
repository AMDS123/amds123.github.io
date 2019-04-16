---
layout: post
title: "Hierarchical Memory Networks"
date: 2016-05-24 12:48:19
categories: arXiv_CV
tags: arXiv_CV Attention GAN Reinforcement_Learning Inference Memory_Networks
author: Sarath Chandar, Sungjin Ahn, Hugo Larochelle, Pascal Vincent, Gerald Tesauro, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Memory networks are neural networks with an explicit memory component that can be both read and written to by the network. The memory is often addressed in a soft way using a softmax function, making end-to-end training with backpropagation possible. However, this is not computationally scalable for applications which require the network to read from extremely large memories. On the other hand, it is well known that hard attention mechanisms based on reinforcement learning are challenging to train successfully. In this paper, we explore a form of hierarchical memory network, which can be considered as a hybrid between hard and soft attention memory networks. The memory is organized in a hierarchical structure such that reading from it is done with less computation than soft attention over a flat memory, while also being easier to train than hard attention over a flat memory. Specifically, we propose to incorporate Maximum Inner Product Search (MIPS) in the training and inference procedures for our hierarchical memory network. We explore the use of various state-of-the art approximate MIPS techniques and report results on SimpleQuestions, a challenging large scale factoid question answering task.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1605.07427](https://arxiv.org/abs/1605.07427)

##### PDF
[https://arxiv.org/pdf/1605.07427](https://arxiv.org/pdf/1605.07427)

