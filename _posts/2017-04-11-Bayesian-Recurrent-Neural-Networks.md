---
layout: post
title: 'Bayesian Recurrent Neural Networks'
date: 2017-04-11 17:25:08
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN
author: Meire Fortunato, Charles Blundell, Oriol Vinyals
---

* content
{:toc}

##### Abstract
In this work we explore a straightforward variational Bayes scheme for Recurrent Neural Networks. Firstly, we show that a simple adaptation of truncated backpropagation through time can yield good quality uncertainty estimates and superior regularisation at only a small extra computational cost during training. Secondly, we demonstrate how a novel kind of posterior approximation yields further improvements to the performance of Bayesian RNNs. We incorporate local gradient information into the approximate posterior to sharpen it around the current batch statistics. This technique is not exclusive to recurrent neural networks and can be applied more widely to train Bayesian neural networks. We also empirically demonstrate how Bayesian RNNs are superior to traditional RNNs on a language modelling benchmark and an image captioning task, as well as showing how each of these methods improve our model over a variety of other schemes for training them. We also introduce a new benchmark for studying uncertainty for language models so future methods can be easily compared.

##### Abstract (translated by Google)
在这项工作中，我们探讨了递归神经网络的一个简单的变分贝叶斯方案。首先，我们表明，简单的时间截断反向传播适应可以产生良好的质量不确定性估计和优良的规则化，只需要在训练期间额外的计算成本。其次，我们证明了一种新颖的后验逼近如何进一步改进贝叶斯RNNs的性能。我们将本地渐变信息合并到近似后验中，以便在当前批处理统计信息周围进行锐化。这种技术不是唯一的循环神经网络，可以更广泛地应用于训练贝叶斯神经网络。我们还经验地演示了贝叶斯RNN如何在语言建模基准和图像字幕任务上优于传统的RNN，并且展示了这些方法如何通过各种其他方案改进我们的模型来训练它们。我们还为研究语言模型的不确定性提供了一个新的基准，因此可以轻松地比较未来的方法。

##### URL
[https://arxiv.org/abs/1704.02798](https://arxiv.org/abs/1704.02798)

