---
layout: post
title: "On Random Weights for Texture Generation in One Layer Neural Networks"
date: 2016-12-19 08:21:04
categories: arXiv_CV
tags: arXiv_CV CNN
author: Mihir Mongia, Kundan Kumar, Akram Erraqabi, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work in the literature has shown experimentally that one can use the lower layers of a trained convolutional neural network (CNN) to model natural textures. More interestingly, it has also been experimentally shown that only one layer with random filters can also model textures although with less variability. In this paper we ask the question as to why one layer CNNs with random filters are so effective in generating textures? We theoretically show that one layer convolutional architectures (without a non-linearity) paired with the an energy function used in previous literature, can in fact preserve and modulate frequency coefficients in a manner so that random weights and pretrained weights will generate the same type of images. Based on the results of this analysis we question whether similar properties hold in the case where one uses one convolution layer with a non-linearity. We show that in the case of ReLu non-linearity there are situations where only one input will give the minimum possible energy whereas in the case of no nonlinearity, there are always infinite solutions that will give the minimum possible energy. Thus we can show that in certain situations adding a ReLu non-linearity generates less variable images.

##### Abstract (translated by Google)
最近在文献中的工作已经通过实验表明，可以使用经过训练的卷积神经网络（CNN）的较低层来模拟天然纹理。更有意思的是，它也已经通过实验表明，只有一层随机滤波器也可以模拟纹理，尽管变化较小。在这篇论文中，我们提出一个问题，为什么一层CNNs随机滤波器在生成纹理方面如此有效？我们从理论上证明，与先前文献中使用的能量函数配对的一层卷积结构（没有非线性）实际上可以保持和调制频率系数，使得随机权重和预训练权重将产生相同类型的图片。基于这个分析的结果，我们质疑在使用一个具有非线性的卷积层的情况下，相似的性质是否成立。我们证明，在ReLu非线性的情况下，只有一个输入会给出最小可能的能量，而在没有非线性的情况下，总会有无限的解决方案给出最小的可能能量。因此，我们可以证明，在某些情况下，添加ReLu非线性会生成较少的可变图像。

##### URL
[https://arxiv.org/abs/1612.06070](https://arxiv.org/abs/1612.06070)

##### PDF
[https://arxiv.org/pdf/1612.06070](https://arxiv.org/pdf/1612.06070)

