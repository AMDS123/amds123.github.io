---
layout: post
title: "Leveraging Deep Neural Network Activation Entropy to cope with Unseen Data in Speech Recognition"
date: 2017-08-31 01:00:19
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Vikramjit Mitra, Horacio Franco
mathjax: true
---

* content
{:toc}

##### Abstract
Unseen data conditions can inflict serious performance degradation on systems relying on supervised machine learning algorithms. Because data can often be unseen, and because traditional machine learning algorithms are trained in a supervised manner, unsupervised adaptation techniques must be used to adapt the model to the unseen data conditions. However, unsupervised adaptation is often challenging, as one must generate some hypothesis given a model and then use that hypothesis to bootstrap the model to the unseen data conditions. Unfortunately, reliability of such hypotheses is often poor, given the mismatch between the training and testing datasets. In such cases, a model hypothesis confidence measure enables performing data selection for the model adaptation. Underlying this approach is the fact that for unseen data conditions, data variability is introduced to the model, which the model propagates to its output decision, impacting decision reliability. In a fully connected network, this data variability is propagated as distortions from one layer to the next. This work aims to estimate the propagation of such distortion in the form of network activation entropy, which is measured over a short- time running window on the activation from each neuron of a given hidden layer, and these measurements are then used to compute summary entropy. This work demonstrates that such an entropy measure can help to select data for unsupervised model adaptation, resulting in performance gains in speech recognition tasks. Results from standard benchmark speech recognition tasks show that the proposed approach can alleviate the performance degradation experienced under unseen data conditions by iteratively adapting the model to the unseen datas acoustic condition.

##### Abstract (translated by Google)
看不见的数据条件会导致依赖监督机器学习算法的系统严重的性能下降。由于数据往往是不可见的，而且由于传统的机器学习算法是以监督的方式进行训练的，必须使用无监督的自适应技术来使模型适应不可见的数据条件。然而，无监督的适应往往是具有挑战性的，因为人们必须根据模型产生一些假设，然后使用该假设将模型引导到看不见的数据条件。不幸的是，考虑到训练和测试数据集之间的不匹配，这些假设的可靠性通常很差。在这种情况下，模型假设置信度测量使得能够为模型适应执行数据选择。这种方法的基础是，对于看不见的数据条件，将数据可变性引入模型，模型传播到其输出决策，影响决策的可靠性。在完全连接的网络中，这种数据可变性作为从一层到下一层的失真传播。这项工作的目的是以网络激活熵的形式来估计这种失真的传播，在给定的隐藏层的每个神经元的激活下，在短时间运行窗口上测量这个熵，然后这些测量结果被用来计算汇总熵。这项工作表明，这种熵度量可以帮助选择无监督模型自适应的数据，从而导致语音识别任务的性能提升。标准基准语音识别任务的结果表明，所提出的方法可以通过迭代地将该模型适配于看不见的数据声学条件来减轻在看不见的数据条件下经历的性能退化。

##### URL
[https://arxiv.org/abs/1708.09516](https://arxiv.org/abs/1708.09516)

##### PDF
[https://arxiv.org/pdf/1708.09516](https://arxiv.org/pdf/1708.09516)

