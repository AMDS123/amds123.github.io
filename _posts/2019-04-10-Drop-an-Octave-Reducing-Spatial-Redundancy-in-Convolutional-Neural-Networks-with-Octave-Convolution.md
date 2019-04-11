---
layout: post
title: "Drop an Octave: Reducing Spatial Redundancy in Convolutional Neural Networks with Octave Convolution"
date: 2019-04-10 08:15:00
categories: arXiv_CV
tags: arXiv_CV CNN Classification Recognition
author: Yunpeng Chen, Haoqi Fang, Bing Xu, Zhicheng Yan, Yannis Kalantidis, Marcus Rohrbach, Shuicheng Yan, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
In natural images, information is conveyed at different frequencies where higher frequencies are usually encoded with fine details and lower frequencies are usually encoded with global structures. Similarly, the output feature maps of a convolution layer can also be seen as a mixture of information at different frequencies. In this work, we propose to factorize the mixed feature maps by their frequencies and design a novel Octave Convolution (OctConv) operation to store and process feature maps that vary spatially "slower" at a lower spatial resolution reducing both memory and computation cost. Unlike existing multi-scale meth-ods, OctConv is formulated as a single, generic, plug-and-play convolutional unit that can be used as a direct replacement of (vanilla) convolutions without any adjustments in the network architecture. It is also orthogonal and complementary to methods that suggest better topologies or reduce channel-wise redundancy like group or depth-wise convolutions. We experimentally show that by simply replacing con-volutions with OctConv, we can consistently boost accuracy for both image and video recognition tasks, while reducing memory and computational cost. An OctConv-equipped ResNet-152 can achieve 82.9% top-1 classification accuracy on ImageNet with merely 22.2 GFLOPs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05049](http://arxiv.org/abs/1904.05049)

##### PDF
[http://arxiv.org/pdf/1904.05049](http://arxiv.org/pdf/1904.05049)

