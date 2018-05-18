---
layout: post
title: "Disparity Sliding Window: Object Proposals From Disparity Images"
date: 2018-05-17 15:45:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection Recognition
author: Julian M&#xfc;ller, Andreas Fregin, Klaus Dietmayer
mathjax: true
---

* content
{:toc}

##### Abstract
Sliding window approaches have been widely used for object recognition tasks in recent years. They guarantee an investigation of the entire input image for the object to be detected and allow a localization of that object. Despite the current trend towards deep neural networks, sliding window methods are still used in combination with convolutional neural networks. The risk of overlooking an object is clearly reduced compared to alternative detection approaches which detect objects based on shape, edges or color. Nevertheless, the sliding window technique strongly increases the computational effort as the classifier has to verify a large number of object candidates. This paper proposes a sliding window approach which also uses depth information from a stereo camera. This leads to a greatly decreased number of object candidates without significantly reducing the detection accuracy. A theoretical investigation of the conventional sliding window approach is presented first. Other publications to date only mentioned rough estimations of the computational cost. A mathematical derivation clarifies the number of object candidates with respect to parameters such as image and object size. Subsequently, the proposed disparity sliding window approach is presented in detail. The approach is evaluated on pedestrian detection with annotations and images from the KITTI object detection benchmark. Furthermore, a comparison with two state-of-the-art methods is made. Code is available in C++ and Python https://github.com/julimueller/ disparity-sliding-window.

##### Abstract (translated by Google)
近年来，滑动窗口方法已被广泛用于目标识别任务。它们保证对待检测对象的整个输入图像进行调查，并允许对该对象进行本地化。尽管目前的趋势是深度神经网络，滑动窗口方法仍然与卷积神经网络结合使用。与根据形状，边缘或颜色检测物体的替代检测方法相比，俯视物体的风险显着降低。然而，由于分类器必须验证大量候选对象，所以滑动窗口技术大大增加了计算量。本文提出了一种滑动窗口方法，它也使用立体相机的深度信息。这导致候选对象的数量大大减少，而不会显着降低检测精度。首先介绍传统滑动窗口方法的理论研究。迄今为止的其他出版物仅提到了计算成本的粗略估计。数学推导澄清了对象参数（如图像和对象大小）的数量。随后，详细介绍了所提出的视差滑动窗口方法。该方法通过基于KITTI物体检测基准的注释和图像对行人检测进行评估。此外，与两种最先进的方法进行比较。代码在C ++和Python中可用https://github.com/julimueller/ disparity-sliding-window。

##### URL
[http://arxiv.org/abs/1805.06830](http://arxiv.org/abs/1805.06830)

##### PDF
[http://arxiv.org/pdf/1805.06830](http://arxiv.org/pdf/1805.06830)

