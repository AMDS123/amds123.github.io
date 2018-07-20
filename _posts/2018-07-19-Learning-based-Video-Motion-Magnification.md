---
layout: post
title: "Learning-based Video Motion Magnification"
date: 2018-07-19 17:45:57
categories: arXiv_CV
tags: arXiv_CV CNN
author: Tae-Hyun Oh, Ronnachai Jaroensri, Changil Kim, Mohamed Elgharib, Fr&#xe9;do Durand, William T. Freeman, Wojciech Matusik
mathjax: true
---

* content
{:toc}

##### Abstract
Video motion magnification techniques allow us to see small motions previously invisible to the naked eyes, such as those of vibrating airplane wings, or swaying buildings under the influence of the wind. Because the motion is small, the magnification results are prone to noise or excessive blurring. The state of the art relies on hand-designed filters to extract representations that may not be optimal. In this paper, we seek to learn the filters directly from examples using deep convolutional neural networks. To make training tractable, we carefully design a synthetic dataset that captures small motion well, and use two-frame input for training. We show that the learned filters achieve high-quality results on real videos, with less ringing artifacts and better noise characteristics than previous methods. While our model is not trained with temporal filters, we found that the temporal filters can be used with our extracted representations up to a moderate magnification, enabling a frequency-based motion selection. Finally, we analyze the learned filters and show that they behave similarly to the derivative filters used in previous works. Our code, trained model, and datasets will be available online.

##### Abstract (translated by Google)
视频运动放大技术使我们能够看到以前肉眼看不到的小动作，例如振动飞机机翼的动作，或者在风的影响下摇摆的建筑物。由于运动很小，因此放大效果容易产生噪音或过度模糊。现有技术依赖于手工设计的过滤器来提取可能不是最佳的表示。在本文中，我们试图直接从使用深度卷积神经网络的例子中学习滤波器。为了使训练易于处理，我们仔细设计了一个合成数据集，可以很好地捕捉小动作，并使用两帧输入进行训练。我们表明，学习过滤器可以在真实视频上获得高质量的结果，与以前的方法相比，具有更少的振铃伪像和更好的噪声特性。虽然我们的模型没有使用时间滤波器进行训练，但我们发现时间滤波器可以与我们提取的表示一起使用，直到中等放大率，从而实现基于频率的运动选择。最后，我们分析了学习过滤器，并表明它们的行为类似于以前工作中使用的派生过滤器。我们的代码，经过培训的模型和数据集将在线提供。

##### URL
[http://arxiv.org/abs/1804.02684](http://arxiv.org/abs/1804.02684)

##### PDF
[http://arxiv.org/pdf/1804.02684](http://arxiv.org/pdf/1804.02684)

