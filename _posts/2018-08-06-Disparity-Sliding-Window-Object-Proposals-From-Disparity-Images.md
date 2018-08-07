---
layout: post
title: "Disparity Sliding Window: Object Proposals From Disparity Images"
date: 2018-08-06 09:16:04
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
近年来，滑动窗口方法已被广泛用于对象识别任务。它们保证调查要检测的对象的整个输入图像并允许该对象的定位。尽管当前趋向于深度神经网络，但滑动窗口方法仍然与卷积神经网络结合使用。与基于形状，边缘或颜色检测物体的替代检测方法相比，明显减少了俯视物体的风险。然而，滑动窗口技术强烈地增加了计算工作量，因为分类器必须验证大量候选对象。本文提出了一种滑动窗口方法，该方法还使用来自立体相机的深度信息。这导致对象候选者的数量大大减少而不会显着降低检测精度。首先介绍了传统滑动窗口方法的理论研究。迄今为止的其他出版物仅提到计算成本的粗略估计。数学推导阐明了关于参数（例如图像和对象大小）的候选对象的数量。随后，详细介绍了所提出的视差滑动窗口方法。该方法使用来自KITTI物体检测基准的注释和图像来评估行人检测。此外，还与两种最先进的方法进行了比较。代码以C ++和Python https://github.com/julimueller/ disparity-sliding-window提供。

##### URL
[http://arxiv.org/abs/1805.06830](http://arxiv.org/abs/1805.06830)

##### PDF
[http://arxiv.org/pdf/1805.06830](http://arxiv.org/pdf/1805.06830)

