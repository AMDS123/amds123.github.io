---
layout: post
title: "Bayesian Recurrent Neural Networks"
date: 2018-03-21 12:14:16
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN Language_Model
author: Meire Fortunato, Charles Blundell, Oriol Vinyals
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we explore a straightforward variational Bayes scheme for Recurrent Neural Networks. Firstly, we show that a simple adaptation of truncated backpropagation through time can yield good quality uncertainty estimates and superior regularisation at only a small extra computational cost during training, also reducing the amount of parameters by 80\%. Secondly, we demonstrate how a novel kind of posterior approximation yields further improvements to the performance of Bayesian RNNs. We incorporate local gradient information into the approximate posterior to sharpen it around the current batch statistics. We show how this technique is not exclusive to recurrent neural networks and can be applied more widely to train Bayesian neural networks. We also empirically demonstrate how Bayesian RNNs are superior to traditional RNNs on a language modelling benchmark and an image captioning task, as well as showing how each of these methods improve our model over a variety of other schemes for training them. We also introduce a new benchmark for studying uncertainty for language models so future methods can be easily compared.

##### Abstract (translated by Google)
在这项工作中，我们探索了一种简单的变换神经网络变分贝叶斯方案。首先，我们证明了截断反向传播随时间的简单适应可以在训练期间仅以很小的额外计算成本产生良好质量的不确定性估计和优越的正则化，也将参数量减少80％。其次，我们演示了一种新型的后验近似如何进一步改善贝叶斯RNN的性能。我们将局部梯度信息合并到近似后部，以便在当前批次统计数据周围进行锐化。我们展示了这种技术如何不仅仅适用于递归神经网络，并且可以更广泛地应用于训练贝叶斯神经网络。我们还经验性地演示了贝叶斯RNN如何在语言建模基准和图像标题任务上优于传统RNN，并展示了这些方法中的每一种如何通过各种其他方案来改进我们的模型以进行训练。我们还引入了一个研究语言模型不确定性的新基准，因此可以轻松比较未来的方法。

##### URL
[https://arxiv.org/abs/1704.02798](https://arxiv.org/abs/1704.02798)

##### PDF
[https://arxiv.org/pdf/1704.02798](https://arxiv.org/pdf/1704.02798)

