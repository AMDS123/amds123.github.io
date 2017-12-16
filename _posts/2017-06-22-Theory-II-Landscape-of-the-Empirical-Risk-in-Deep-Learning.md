---
layout: post
title: "Theory II: Landscape of the Empirical Risk in Deep Learning"
date: 2017-06-22 09:33:35
categories: arXiv_CV
tags: arXiv_CV Face CNN Optimization Deep_Learning
author: Qianli Liao, Tomaso Poggio
mathjax: true
---

* content
{:toc}

##### Abstract
Previous theoretical work on deep learning and neural network optimization tend to focus on avoiding saddle points and local minima. However, the practical observation is that, at least in the case of the most successful Deep Convolutional Neural Networks (DCNNs), practitioners can always increase the network size to fit the training data (an extreme example would be [1]). The most successful DCNNs such as VGG and ResNets are best used with a degree of "overparametrization". In this work, we characterize with a mix of theory and experiments, the landscape of the empirical risk of overparametrized DCNNs. We first prove in the regression framework the existence of a large number of degenerate global minimizers with zero empirical error (modulo inconsistent equations). The argument that relies on the use of Bezout theorem is rigorous when the RELUs are replaced by a polynomial nonlinearity (which empirically works as well). As described in our Theory III [2] paper, the same minimizers are degenerate and thus very likely to be found by SGD that will furthermore select with higher probability the most robust zero-minimizer. We further experimentally explored and visualized the landscape of empirical risk of a DCNN on CIFAR-10 during the entire training process and especially the global minima. Finally, based on our theoretical and experimental results, we propose an intuitive model of the landscape of DCNN's empirical loss surface, which might not be as complicated as people commonly believe.

##### Abstract (translated by Google)
以前关于深度学习和神经网络优化的理论工作往往侧重于避免鞍点和局部最小值。然而，实际观察到，至少在最深的卷积神经网络（DCNNs）中，从业者总是可以增加网络大小以适应训练数据（一个极端的例子是[1]）。最成功的DCNN，如VGG和ResNets最适用于一定程度的“过度参数化”。在这项工作中，我们用理论和实验的混合来描述过度参数化DCNN的经验风险。我们首先在回归框架中证明了大量具有零经验误差（模数不一致方程）的退化全局极小值的存在性。依赖于Bezout定理的论证在RELU被多项式非线性取代（其经验性地起作用）时是严格的。正如在我们的理论III [2]论文中所描述的那样，同样的最小化因子是退化的，因此很有可能被SGD发现，它将进一步选择具有更高可能性的最稳健的零最小化子。在整个训练过程中，特别是全球最低点，我们进一步实验性地探索和可视化了DCNN在CIFAR-10上的经验风险状况。最后，根据我们的理论和实验结果，我们提出了一个DCNN的经验损失面的直观模型，这可能不像人们通常所认为的那样复杂。

##### URL
[https://arxiv.org/abs/1703.09833](https://arxiv.org/abs/1703.09833)

##### PDF
[https://arxiv.org/pdf/1703.09833](https://arxiv.org/pdf/1703.09833)

