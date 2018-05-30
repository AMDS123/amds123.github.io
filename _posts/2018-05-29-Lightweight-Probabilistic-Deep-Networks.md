---
layout: post
title: "Lightweight Probabilistic Deep Networks"
date: 2018-05-29 09:40:52
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification Prediction
author: Jochen Gast, Stefan Roth
mathjax: true
---

* content
{:toc}

##### Abstract
Even though probabilistic treatments of neural networks have a long history, they have not found widespread use in practice. Sampling approaches are often too slow already for simple networks. The size of the inputs and the depth of typical CNN architectures in computer vision only compound this problem. Uncertainty in neural networks has thus been largely ignored in practice, despite the fact that it may provide important information about the reliability of predictions and the inner workings of the network. In this paper, we introduce two lightweight approaches to making supervised learning with probabilistic deep networks practical: First, we suggest probabilistic output layers for classification and regression that require only minimal changes to existing networks. Second, we employ assumed density filtering and show that activation uncertainties can be propagated in a practical fashion through the entire network, again with minor changes. Both probabilistic networks retain the predictive power of the deterministic counterpart, but yield uncertainties that correlate well with the empirical error induced by their predictions. Moreover, the robustness to adversarial examples is significantly increased.

##### Abstract (translated by Google)
尽管神经网络的概率处理有着悠久的历史，但它们在实践中还没有被广泛使用。对于简单的网络，采样方法通常太慢。计算机视觉中输入的大小和典型的CNN体​​系结构的深度只会增加这个问题。在实践中，神经网络中的不确定性在很大程度上被忽略了，尽管它可能提供关于预测可靠性和网络内部工作的重要信息。在本文中，我们介绍两种轻量级的方法，用概率深度网络进行监督式学习，这是实用的：首先，我们提出用于分类和回归的概率输出层，只需对现有网络进行最小限度的更改。其次，我们采用假设的密度过滤，并表明激活不确定性可以在整个网络中以实用的方式传播，并且只需稍作更改。概率网络都保留了确定性对应物的预测能力，但产生的不确定性与它们的预测所导致的经验误差很好地相关。此外，对抗案例的稳健性显着增加。

##### URL
[http://arxiv.org/abs/1805.11327](http://arxiv.org/abs/1805.11327)

##### PDF
[http://arxiv.org/pdf/1805.11327](http://arxiv.org/pdf/1805.11327)

