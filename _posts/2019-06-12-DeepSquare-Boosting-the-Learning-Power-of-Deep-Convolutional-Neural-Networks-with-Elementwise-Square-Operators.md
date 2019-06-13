---
layout: post
title: "DeepSquare: Boosting the Learning Power of Deep Convolutional Neural Networks with Elementwise Square Operators"
date: 2019-06-12 07:27:44
categories: arXiv_CV
tags: arXiv_CV CNN Inference Classification
author: Sheng Chen, Xu Wang, Chao Chen, Yifan Lu, Xijin Zhang, Linfu Wen
mathjax: true
---

* content
{:toc}

##### Abstract
Modern neural network modules which can significantly enhance the learning power usually add too much computational complexity to the original neural networks. In this paper, we pursue very efficient neural network modules which can significantly boost the learning power of deep convolutional neural networks with negligible extra computational cost. We first present both theoretically and experimentally that elementwise square operator has a potential to enhance the learning power of neural networks. Then, we design four types of lightweight modules with elementwise square operators, named as Square-Pooling, Square-Softmin, Square-Excitation, and Square-Encoding. We add our four lightweight modules to Resnet18, Resnet50, and ShuffleNetV2 for better performance in the experiment on ImageNet 2012 dataset. The experimental results show that our modules can bring significant accuracy improvements to the base convolutional neural network models. The performance of our lightweight modules is even comparable to many complicated modules such as bilinear pooling, Squeeze-and-Excitation, and Gather-Excite. Our highly efficient modules are particularly suitable for mobile models. For example, when equipped with a single Square-Pooling module, the top-1 classification accuracy of ShuffleNetV2-0.5x on ImageNet 2012 is absolutely improved by 1.45% with no additional parameters and negligible inference time overhead.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04979](http://arxiv.org/abs/1906.04979)

##### PDF
[http://arxiv.org/pdf/1906.04979](http://arxiv.org/pdf/1906.04979)

