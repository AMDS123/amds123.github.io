---
layout: post
title: "Neuron Pruning for Compressing Deep Networks using Maxout Architectures"
date: 2017-07-21 10:53:37
categories: arXiv_CV
tags: arXiv_CV Face Recognition
author: Fernando Moya Rueda, Rene Grzeszick, Gernot A. Fink
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an efficient and robust approach for reducing the size of deep neural networks by pruning entire neurons. It exploits maxout units for combining neurons into more complex convex functions and it makes use of a local relevance measurement that ranks neurons according to their activation on the training set for pruning them. Additionally, a parameter reduction comparison between neuron and weight pruning is shown. It will be empirically shown that the proposed neuron pruning reduces the number of parameters dramatically. The evaluation is performed on two tasks, the MNIST handwritten digit recognition and the LFW face verification, using a LeNet-5 and a VGG16 network architecture. The network size is reduced by up to $74\%$ and $61\%$, respectively, without affecting the network's performance. The main advantage of neuron pruning is its direct influence on the size of the network architecture. Furthermore, it will be shown that neuron pruning can be combined with subsequent weight pruning, reducing the size of the LeNet-5 and VGG16 up to $92\%$ and $80\%$ respectively.

##### Abstract (translated by Google)
本文提出了一种通过修剪整个神经元来减少深度神经网络大小的有效和稳健的方法。它利用最大单位将神经元组合成更复杂的凸函数，并利用本地相关性度量，根据它们在训练集上的激活对神经元进行排序，以修剪它们。此外，还显示了神经元和体重修剪之间的参数缩减比较。从经验上可以看出，所提出的神经修剪大大减少了参数的数量。使用LeNet-5和VGG16网络架构对MNIST手写数字识别和LFW人脸验证进行评估。在不影响网络性能的情况下，网络规模分别降低了$ 74 \％$和$ 61 \％$。神经修剪的主要优点是它直接影响网络架构的规模。此外，将显示神经元修剪可以结合随后的减肥修剪，将LeNet-5和VGG16的大小分别降低到$ 92 \％$和$ 80 \％$。

##### URL
[https://arxiv.org/abs/1707.06838](https://arxiv.org/abs/1707.06838)

##### PDF
[https://arxiv.org/pdf/1707.06838](https://arxiv.org/pdf/1707.06838)

