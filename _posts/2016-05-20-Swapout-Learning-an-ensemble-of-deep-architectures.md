---
layout: post
title: "Swapout: Learning an ensemble of deep architectures"
date: 2016-05-20 18:39:33
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Saurabh Singh, Derek Hoiem, David Forsyth
mathjax: true
---

* content
{:toc}

##### Abstract
We describe Swapout, a new stochastic training method, that outperforms ResNets of identical network structure yielding impressive results on CIFAR-10 and CIFAR-100. Swapout samples from a rich set of architectures including dropout, stochastic depth and residual architectures as special cases. When viewed as a regularization method swapout not only inhibits co-adaptation of units in a layer, similar to dropout, but also across network layers. We conjecture that swapout achieves strong regularization by implicitly tying the parameters across layers. When viewed as an ensemble training method, it samples a much richer set of architectures than existing methods such as dropout or stochastic depth. We propose a parameterization that reveals connections to exiting architectures and suggests a much richer set of architectures to be explored. We show that our formulation suggests an efficient training method and validate our conclusions on CIFAR-10 and CIFAR-100 matching state of the art accuracy. Remarkably, our 32 layer wider model performs similar to a 1001 layer ResNet model.

##### Abstract (translated by Google)
我们描述了Swapout，一种新的随机训练方法，它胜过了CIFAR-10和CIFAR-100上相同的网络结构的ResNet，产生了令人印象深刻的结果。作为特殊情况，从一组丰富的体系结构中抽取样本，包括辍学，随机深度和剩余体系结构。当被视为一种正则化方法时，交换不仅会抑制一个层中的单元的共同适应，类似于退出，而且还会跨越网络层。我们猜测，互换通过隐含地跨层参数来实现强正则化。当被视为一种集合训练方法时，它比现有的方法（例如辍学或随机深度）取样更丰富的体系结构。我们提出一个参数化来揭示与现有体系结构的联系，并提出一套更丰富的体系结构来探索。我们表明，我们的公式提出了一个有效的培训方法，并验证了我们对CIFAR-10和CIFAR-100匹配状态的最佳精度的结论。值得注意的是，我们的32层宽模型执行类似于1001层ResNet模型。

##### URL
[https://arxiv.org/abs/1605.06465](https://arxiv.org/abs/1605.06465)

##### PDF
[https://arxiv.org/pdf/1605.06465](https://arxiv.org/pdf/1605.06465)

