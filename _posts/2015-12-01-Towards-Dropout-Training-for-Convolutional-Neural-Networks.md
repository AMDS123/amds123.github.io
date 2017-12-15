---
layout: post
title: "Towards Dropout Training for Convolutional Neural Networks"
date: 2015-12-01 12:46:11
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Haibing Wu, Xiaodong Gu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, dropout has seen increasing use in deep learning. For deep convolutional neural networks, dropout is known to work well in fully-connected layers. However, its effect in convolutional and pooling layers is still not clear. This paper demonstrates that max-pooling dropout is equivalent to randomly picking activation based on a multinomial distribution at training time. In light of this insight, we advocate employing our proposed probabilistic weighted pooling, instead of commonly used max-pooling, to act as model averaging at test time. Empirical evidence validates the superiority of probabilistic weighted pooling. We also empirically show that the effect of convolutional dropout is not trivial, despite the dramatically reduced possibility of over-fitting due to the convolutional architecture. Elaborately designing dropout training simultaneously in max-pooling and fully-connected layers, we achieve state-of-the-art performance on MNIST, and very competitive results on CIFAR-10 and CIFAR-100, relative to other approaches without data augmentation. Finally, we compare max-pooling dropout and stochastic pooling, both of which introduce stochasticity based on multinomial distributions at pooling stage.

##### Abstract (translated by Google)
最近，辍学越来越多地用于深度学习。对于深卷积神经网络，已知退出在完全连接的层中工作良好。但是，它在卷积层和汇集层中的效果还不清楚。本文证明了最大池化丢失相当于在训练时间基于多项式分布的随机挑选激活。鉴于这种见解，我们主张使用我们提出的概率加权池，而不是常用的最大池，在测试时间作为模型平均。经验证据验证了概率加权池的优越性。我们也经验地表明，卷积辍学的影响并不是微不足道的，尽管由于卷积架构而导致过度拟合的可能性大大降低。同时在最大池和完全连接层同时精心设计丢失训练，与没有数据增强的其他方法相比，我们在MNIST上获得了最先进的性能，在CIFAR-10和CIFAR-100上也获得了非常有竞争力的结果。最后，我们比较了最大池化丢失和随机池化，这两者在池化阶段引入了基于多项分布的随机性。

##### URL
[https://arxiv.org/abs/1512.00242](https://arxiv.org/abs/1512.00242)

##### PDF
[https://arxiv.org/pdf/1512.00242](https://arxiv.org/pdf/1512.00242)

