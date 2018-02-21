---
layout: post
title: "Unsupervised Document Embedding With CNNs"
date: 2018-02-20 01:54:17
categories: arXiv_CL
tags: arXiv_CL Embedding CNN Inference RNN Prediction
author: Chundi Liu, Shunan Zhao, Maksims Volkovs
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new model for unsupervised document embedding. Leading existing approaches either require complex inference or use recurrent neural networks (RNN) that are difficult to parallelize. We take a different route and develop a convolutional neural network (CNN) embedding model. Our CNN architecture is fully parallelizable resulting in over 10x speedup in inference time over RNN models. Parallelizable architecture enables to train deeper models where each successive layer has increasingly larger receptive field and models longer range semantic structure within the document. We additionally propose a fully unsupervised learning algorithm to train this model based on stochastic forward prediction. Empirical results on two public benchmarks show that our approach produces comparable to state-of-the-art accuracy at a fraction of computational cost.

##### Abstract (translated by Google)
我们提出了一种无监督文档嵌入的新模型。领先的现有方法要么需要复杂的推理，要么使用难以并行化的递归神经网络（RNN）。我们采取不同的路线并开发卷积神经网络（CNN）嵌入模型。我们的CNN架构完全可并行化，从而使RNN模型的推理时间超过10倍。可并行化的体系结构能够训练更深的模型，其中每个连续的层具有越来越大的接受域，并在文档内建立更长范围的语义结构。我们另外提出了一个完全无监督学习算法来训练基于随机前向预测的模型。对两个公共基准的实证结果表明，我们的方法在计算成本的一小部分上产生了与先进精度相当的效果。

##### URL
[http://arxiv.org/abs/1711.04168](http://arxiv.org/abs/1711.04168)

##### PDF
[http://arxiv.org/pdf/1711.04168](http://arxiv.org/pdf/1711.04168)

