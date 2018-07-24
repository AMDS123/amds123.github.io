---
layout: post
title: "PS-FCN: A Flexible Learning Framework for Photometric Stereo"
date: 2018-07-23 16:13:27
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Guanying Chen, Kai Han, Kwan-Yee K. Wong
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of photometric stereo for non-Lambertian surfaces. Existing approaches often adopt simplified reflectance models to make the problem more tractable, but this greatly hinders their applications on real-world objects. In this paper, we propose a deep fully convolutional network, called PS-FCN, that takes an arbitrary number of images of a static object captured under different light directions with a fixed camera as input, and predicts a normal map of the object in a fast feed-forward pass. Unlike the recently proposed learning based method, PS-FCN does not require a pre-defined set of light directions during training and testing, and can handle multiple images and light directions in an order-agnostic manner. Although we train PS-FCN on synthetic data, it can generalize well on real datasets. We further show that PS-FCN can be easily extended to handle the problem of uncalibrated photometric stereo.Extensive experiments on public real datasets show that PS-FCN outperforms existing approaches in calibrated photometric stereo, and promising results are achieved in uncalibrated scenario, clearly demonstrating its effectiveness.

##### Abstract (translated by Google)
本文讨论了非朗伯曲面的光度立体问题。现有方法通常采用简化的反射模型来使问题更容易处理，但这极大地阻碍了它们在现实世界中的应用。在本文中，我们提出了一个深度完全卷积网络，称为PS-FCN，它采用固定摄像机作为输入，在不同光方向下捕获的静态对象的任意数量的图像，并预测对象的法线贴图。快速前馈传球。与最近提出的基于学习的方法不同，PS-FCN在训练和测试期间不需要预定义的一组光方向，并且可以以顺序无关的方式处理多个图像和光方向。虽然我们在合成数据上训练PS-FCN，但它可以很好地概括真实数据集。我们进一步表明，PS-FCN可以很容易地扩展到处理未经校准的光度立体声问题。公共真实数据集上的广泛实验表明，PS-FCN在校准光度立体声方面优于现有方法，并且在未校准场景中实现了有希望的结果，清楚地展示了它的有效性。

##### URL
[http://arxiv.org/abs/1807.08696](http://arxiv.org/abs/1807.08696)

##### PDF
[http://arxiv.org/pdf/1807.08696](http://arxiv.org/pdf/1807.08696)

