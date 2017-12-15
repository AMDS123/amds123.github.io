---
layout: post
title: "Residual Networks Behave Like Ensembles of Relatively Shallow Networks"
date: 2016-10-27 00:43:58
categories: arXiv_CV
tags: arXiv_CV
author: Andreas Veit, Michael Wilber, Serge Belongie
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we propose a novel interpretation of residual networks showing that they can be seen as a collection of many paths of differing length. Moreover, residual networks seem to enable very deep networks by leveraging only the short paths during training. To support this observation, we rewrite residual networks as an explicit collection of paths. Unlike traditional models, paths through residual networks vary in length. Further, a lesion study reveals that these paths show ensemble-like behavior in the sense that they do not strongly depend on each other. Finally, and most surprising, most paths are shorter than one might expect, and only the short paths are needed during training, as longer paths do not contribute any gradient. For example, most of the gradient in a residual network with 110 layers comes from paths that are only 10-34 layers deep. Our results reveal one of the key characteristics that seem to enable the training of very deep networks: Residual networks avoid the vanishing gradient problem by introducing short paths which can carry gradient throughout the extent of very deep networks.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个残余网络的新颖解释，表明它们可以被看作是许多不同长度路径的集合。而且，剩余网络似乎只能在训练期间利用短路径来实现非常深的网络。为了支持这个观察，我们将剩余网络重写为路径的显式集合。与传统模型不同，通过残留网络的路径长度不同。此外，损伤研究表明，这些路径表现出类似集合的行为，因为它们并不强烈地相互依赖。最后，也是最令人惊讶的是，大多数路径比人们所期望的要短，在训练中只需要短路径，因为较长的路径不会产生任何梯度。例如，有110层残留网络中的大部分梯度来自仅10-34层深的路径。我们的研究结果揭示了似乎能够训练非常深的网络的关键特征之一：剩余网络通过引入可在整个深度网络范围内传递梯度的短路径来避免消失梯度问题。

##### URL
[https://arxiv.org/abs/1605.06431](https://arxiv.org/abs/1605.06431)

##### PDF
[https://arxiv.org/pdf/1605.06431](https://arxiv.org/pdf/1605.06431)

