---
layout: post
title: "Neural Machine Translation with Gumbel-Greedy Decoding"
date: 2017-06-22 22:54:25
categories: arXiv_CL
tags: arXiv_CL
author: Jiatao Gu, Daniel Jiwoong Im, Victor O.K. Li
mathjax: true
---

* content
{:toc}

##### Abstract
Previous neural machine translation models used some heuristic search algorithms (e.g., beam search) in order to avoid solving the maximum a posteriori problem over translation sentences at test time. In this paper, we propose the Gumbel-Greedy Decoding which trains a generative network to predict translation under a trained model. We solve such a problem using the Gumbel-Softmax reparameterization, which makes our generative network differentiable and trainable through standard stochastic gradient methods. We empirically demonstrate that our proposed model is effective for generating sequences of discrete words.

##### Abstract (translated by Google)
之前的神经机器翻译模型使用一些启发式搜索算法（例如，波束搜索）以避免在测试时间解决翻译句子的最大后验问题。在本文中，我们提出Gumbel-Greedy解码，它训练一个生成网络来预测翻译模型。我们使用Gumbel-Softmax重新参数化来解决这个问题，这使得我们的生成网络可以通过标准的随机梯度方法进行微分和训练。我们经验证明，我们提出的模型是有效的生成序列的离散单词。

##### URL
[https://arxiv.org/abs/1706.07518](https://arxiv.org/abs/1706.07518)

##### PDF
[https://arxiv.org/pdf/1706.07518](https://arxiv.org/pdf/1706.07518)

