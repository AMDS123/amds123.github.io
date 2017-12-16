---
layout: post
title: "UnrealStereo: A Synthetic Dataset for Analyzing Stereo Vision"
date: 2016-12-14 14:13:59
categories: arXiv_CV
tags: arXiv_CV
author: Yi Zhang, Weichao Qiu, Qi Chen, Xiaolin Hu, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Stereo algorithm is important for robotics applications, such as quadcopter and autonomous driving. It needs to be robust enough to handle images of challenging conditions, such as raining or strong lighting. Textureless and specular regions of these images make feature matching difficult and smoothness assumption invalid. It is important to understand whether an algorithm is robust to these hazardous regions. Many stereo benchmarks have been developed to evaluate the performance and track progress. But it is not easy to quantize the effect of these hazardous regions. In this paper, we develop a synthetic image generation tool and build a benchmark with synthetic images. First, we manually tweak hazardous factors in a virtual world, such as making objects more specular or transparent, to simulate corner cases to test the robustness of stereo algorithms. Second, we use ground truth information, such as object mask, material property, to automatically identify hazardous regions and evaluate the accuracy of these regions. Our tool is based on a popular game engine Unreal Engine 4 and will be open-source. Many publicly available realistic game contents can be used by our tool which can provide an enormous resource for algorithm development and evaluation.

##### Abstract (translated by Google)
立体声算法对于四轴飞行器和自动驾驶等机器人应用非常重要。它需要足够强大，以处理具有挑战性的条件，如下雨或强烈的照明图像。这些图像的无纹理和高光区域使得特征匹配困难和平滑假设无效。理解一个算法是否对这些危险区域有效是很重要的。已经开发了许多立体声基准来评估性能和跟踪进度。但要量化这些危险地区的影响并不容易。在本文中，我们开发了一个合成图像生成工具，并建立一个合成图像的基准。首先，我们手动调整虚拟世界中的危险因素，例如使对象更加高光或透明，模拟角落案例来测试立体算法的鲁棒性。其次，我们使用物体掩模，材料属性等地面真实信息来自动识别危险区域并评估这些区域的准确性。我们的工具是基于一个流行的游戏引擎虚幻引擎4，并将是开源的。我们的工具可以使用很多公开的真实的游戏内容，为算法的开发和评估提供了巨大的资源。

##### URL
[https://arxiv.org/abs/1612.04647](https://arxiv.org/abs/1612.04647)

##### PDF
[https://arxiv.org/pdf/1612.04647](https://arxiv.org/pdf/1612.04647)

