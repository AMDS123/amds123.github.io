---
layout: post
title: "Solving Bilinear Inverse Problems using Deep Generative Priors"
date: 2018-02-12 14:39:04
categories: arXiv_CV
tags: arXiv_CV Gradient_Descent
author: Muhammad Asim, Fahad Shamshad, Ali Ahmed
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a new framework to handle the bilinear inverse problems (BIPs): recover $\boldsymbol{w}$, and $\boldsymbol{x}$ from the measurements of the form $\boldsymbol{y} = \mathcal{A}(\boldsymbol{w},\boldsymbol{x})$, where $\mathcal{A}$ is a bilinear operator. The recovery problem of the unknowns $\boldsymbol{w}$, and $\boldsymbol{x}$ can be formulated as a non-convex program. A general strategy is proposed to turn the ill-posed BIP to a relatively well-conditioned BIP by imposing a structural assumption that $\boldsymbol{w}$, and $\boldsymbol{x}$ are members of some classes $\mathcal{W}$, and $\mathcal{X}$, respectively, that are parameterized by unknown latent low-dimensional features. We learn functions mapping from the hidden feature space to the ambient space for each class using generative models. The resulting reduced search space of the solution enables a simple alternating gradient descent scheme to yield promising result in solving the non-convex BIP. 
 To demonstrate the performance of our algorithm, we choose an important BIP; namely, blind image deblurring as a motivating application. We show through extensive experiments that this technique shows promising results in deblurring images of real datasets and is also robust to noise perturbations.

##### Abstract (translated by Google)
本文提出了一个新的框架来处理双线性反问题（BIPs）：从形式$ \ boldsymbol {y} = \ mathcal {A}中恢复$ \ boldsymbol {w} $和$ \ boldsymbol {x} $ }（\ boldsymbol {w}，\ boldsymbol {x}）$，其中$ \ mathcal {A} $是一个双线性算子。未知数$ \ boldsymbol {w} $和$ \ boldsymbol {x} $的恢复问题可以表示为非凸程序。提出了一种通用策略，通过施加$ \ boldsymbol {w} $和$ \ boldsymbol {x} $是某些类的成员$ \ mathcal的结构假设，将不适合的BIP转换为相对有条件的BIP。 W} $和$ \ mathcal {X} $，它们由未知的潜在低维特征参数化。我们学习了使用生成模型从隐藏特征空间映射到每个类的环境空间的函数。所得到的解决方案的搜索空间减少使得简单的交替梯度下降方案在解决非凸BIP中产生有希望的结果。
 为了演示我们算法的性能，我们选择一个重要的BIP;也就是说，作为激励应用程序的盲目去模糊化。我们通过大量的实验表明，这种技术在去模糊真实数据集的图像中显示出有希望的结果，并且对噪声扰动也是强健的。

##### URL
[http://arxiv.org/abs/1802.04073](http://arxiv.org/abs/1802.04073)

##### PDF
[http://arxiv.org/pdf/1802.04073](http://arxiv.org/pdf/1802.04073)

