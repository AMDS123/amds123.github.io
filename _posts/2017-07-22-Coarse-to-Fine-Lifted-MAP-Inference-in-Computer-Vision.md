---
layout: post
title: "Coarse-to-Fine Lifted MAP Inference in Computer Vision"
date: 2017-07-22 13:45:28
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference
author: Haroun Habeeb, Ankit Anand, Mausam, Parag Singla
mathjax: true
---

* content
{:toc}

##### Abstract
There is a vast body of theoretical research on lifted inference in probabilistic graphical models (PGMs). However, few demonstrations exist where lifting is applied in conjunction with top of the line applied algorithms. We pursue the applicability of lifted inference for computer vision (CV), with the insight that a globally optimal (MAP) labeling will likely have the same label for two symmetric pixels. The success of our approach lies in efficiently handling a distinct unary potential on every node (pixel), typical of CV applications. This allows us to lift the large class of algorithms that model a CV problem via PGM inference. We propose a generic template for coarse-to-fine (C2F) inference in CV, which progressively refines an initial coarsely lifted PGM for varying quality-time trade-offs. We demonstrate the performance of C2F inference by developing lifted versions of two near state-of-the-art CV algorithms for stereo vision and interactive image segmentation. We find that, against flat algorithms, the lifted versions have a much superior anytime performance, without any loss in final solution quality.

##### Abstract (translated by Google)
在概率图模型（PGMs）中，提升推理有大量的理论研究。然而，很少有演示将提升与顶层应用算法结合使用。我们追求计算机视觉（CV）提升推理的适用性，并且认为全局最优（MAP）标签对于两个对称像素可能具有相同的标签。我们的方法的成功在于有效地处理每个节点（像素）上不同的一元化潜力，这是典型的CV应用程序。这使我们能够通过PGM推断来解决模拟CV问题的大量算法。我们提出了一个通用模板，用于CV中的从粗到细（C2F）推理，逐步完善初始粗提PGM以改变质量时间的权衡。我们展示了C2F推断的性能，通过开发两个接近最先进的CV算法的升级版本来进行立体视觉和交互式图像分割。我们发现，与平面算法相比，提升版本具有更高的随时性能，在最终解决方案质量方面没有任何损失。

##### URL
[https://arxiv.org/abs/1707.07165](https://arxiv.org/abs/1707.07165)

##### PDF
[https://arxiv.org/pdf/1707.07165](https://arxiv.org/pdf/1707.07165)

