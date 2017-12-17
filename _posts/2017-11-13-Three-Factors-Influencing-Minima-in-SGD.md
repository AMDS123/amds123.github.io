---
layout: post
title: "Three Factors Influencing Minima in SGD"
date: 2017-11-13 15:11:56
categories: arXiv_CV
tags: arXiv_CV Gradient_Descent
author: Stanisław Jastrzębski, Zachary Kenton, Devansh Arpit, Nicolas Ballas, Asja Fischer, Yoshua Bengio, Amos Storkey
mathjax: true
---

* content
{:toc}

##### Abstract
We study the properties of the endpoint of stochastic gradient descent (SGD). By approximating SGD as a stochastic differential equation (SDE) we consider the Boltzmann-Gibbs equilibrium distribution of that SDE under the assumption of isotropic variance in loss gradients. Through this analysis, we find that three factors - learning rate, batch size and the variance of the loss gradients - control the trade-off between the depth and width of the minima found by SGD, with wider minima favoured by a higher ratio of learning rate to batch size. We have direct control over the learning rate and batch size, while the variance is determined by the choice of model architecture, model parameterization and dataset. In the equilibrium distribution only the ratio of learning rate to batch size appears, implying that the equilibrium distribution is invariant under a simultaneous rescaling of learning rate and batch size by the same amount. We then explore experimentally how learning rate and batch size affect SGD from two perspectives: the endpoint of SGD and the dynamics that lead up to it. For the endpoint, the experiments suggest the endpoint of SGD is invariant under simultaneous rescaling of batch size and learning rate, and also that a higher ratio leads to flatter minima, both findings are consistent with our theoretical analysis. We note experimentally that the dynamics also seem to be invariant under the same rescaling of learning rate and batch size, which we explore showing that one can exchange batch size and learning rate for cyclical learning rate schedule. Next, we illustrate how noise affects memorization, showing that high noise levels lead to better generalization. Finally, we find experimentally that the invariance under simultaneous rescaling of learning rate and batch size breaks down if the learning rate gets too large or the batch size gets too small.

##### Abstract (translated by Google)
我们研究随机梯度下降（SGD）的终点的性质。通过将SGD近似为随机微分方程（SDE），我们考虑损失梯度各向同性假设下SDE的Boltzmann-Gibbs均衡分布。通过这一分析，我们发现三个因素 - 学习率，批量大小和损失梯度的变化 - 控制SGD发现的最小值的深度和宽度之间的折衷，更宽的最小值受更高学习比率的青睐率到批量大小。我们直接控制学习率和批量大小，而方差则由模型结构，模型参数化和数据集的选择决定。在均衡分布中，只有学习率与批量大小的比率出现，意味着在学习率和批量大小同时重新缩放的情况下，均衡分布是不变的。然后，我们从两个角度实验性地研究学习速度和批量大小对新元的影响：新元的终点和导致它的动态。对于终点，实验表明SGD的终点在批量大小和学习速率同时重新缩放的情况下是不变的，并且更高的比率导致更平坦的最小值，这两个结果都与我们的理论分析一致。我们从实验上注意到，在相同的学习速率和批量大小重新缩放的情况下，动态也似乎是不变的，我们研究表明，可以交换批量大小和学习速率的周期性学习率的时间表。接下来，我们说明噪音如何影响记忆，表明高噪音水平导致更好的泛化。最后，我们通过实验发现，如果学习速率太大或批量太小，学习速率和批量大小同时重新缩放的不变性会下降。

##### URL
[https://arxiv.org/abs/1711.04623](https://arxiv.org/abs/1711.04623)

##### PDF
[https://arxiv.org/pdf/1711.04623](https://arxiv.org/pdf/1711.04623)

