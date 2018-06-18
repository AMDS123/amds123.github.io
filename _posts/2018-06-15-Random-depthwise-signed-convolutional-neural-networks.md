---
layout: post
title: "Random depthwise signed convolutional neural networks"
date: 2018-06-15 02:26:11
categories: arXiv_AI
tags: arXiv_AI Adversarial CNN Classification
author: Yunzhe Xue, Usman Roshan
mathjax: true
---

* content
{:toc}

##### Abstract
Random weights in convolutional neural networks have shown promising results in previous studies yet remain below par compared to trained networks on image benchmarks. We explore depthwise convolutional neural networks with thousands of random filters in each layer, the sign activation function in between layers, and training performed only at the last layer with a linear support vector machine. We show that our network attains higher accuracies than previous random networks and is comparable to trained large networks on large images from the STL10 and ImageNet benchmarks. Since our network lacks a gradient due to the sign activation it is not possible to produce gradient-based adversarial examples targeting it. We show that our network is also less affected by gradient based adversarial examples produced from state of the art networks that considerably hamper their performance. As a possible explanation for our network's accuracy with random weights we show that the the margin of the linear support vector machine is larger on our final representation compared to the original dataset and increases with the number of random filters. Our network is simple and fast to train and predict, attains high classification accuracy particularly on large images, is hard to attack with adversarial examples, and is less affected by gradient based adversarial examples compared to state of the art networks.

##### Abstract (translated by Google)
卷积神经网络中的随机权重在以前的研究中显示出有希望的结果，但与图像基准测试中的训练网络相比仍然低于标准。我们研究了深度卷积神经网络，每层中有成千上万的随机滤波器，层间的符号激活函数，以及仅在最后一层使用线性支持向量机进行训练。我们表明，我们的网络比之前的随机网络获得更高的精度，并且可以与来自STL10和ImageNet基准的大型图像上训练有素的大型网络相媲美。由于我们的网络由于符号激活而缺少渐变，因此无法生成以其为目标的基于渐变的对抗示例。我们表明，我们的网络也受到基于梯度的敌对示例的影响较小，这些示例从最先进的网络产生，大大阻碍了它们的性能。作为我们的网络随机权重的准确性的一个可能的解释，我们证明了线性支持向量机的边际在我们的最终表示上比原始数据集大，并且随着随机过滤器的数量增加。我们的网络简单快速地进行训练和预测，特别是在大图像上获得高分类准确度，难以用对抗性示例进行攻击，并且与现有技术网络相比，受到基于梯度的对抗性示例的影响较小。

##### URL
[http://arxiv.org/abs/1806.05789](http://arxiv.org/abs/1806.05789)

##### PDF
[http://arxiv.org/pdf/1806.05789](http://arxiv.org/pdf/1806.05789)

