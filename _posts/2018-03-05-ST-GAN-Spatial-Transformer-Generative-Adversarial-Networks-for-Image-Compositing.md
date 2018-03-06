---
layout: post
title: "ST-GAN: Spatial Transformer Generative Adversarial Networks for Image Compositing"
date: 2018-03-05 18:59:01
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Chen-Hsuan Lin, Ersin Yumer, Oliver Wang, Eli Shechtman, Simon Lucey
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of finding realistic geometric corrections to a foreground object such that it appears natural when composited into a background image. To achieve this, we propose a novel Generative Adversarial Network (GAN) architecture that utilizes Spatial Transformer Networks (STNs) as the generator, which we call Spatial Transformer GANs (ST-GANs). ST-GANs seek image realism by operating in the geometric warp parameter space. In particular, we exploit an iterative STN warping scheme and propose a sequential training strategy that achieves better results compared to naive training of a single generator. One of the key advantages of ST-GAN is its applicability to high-resolution images indirectly since the predicted warp parameters are transferable between reference frames. We demonstrate our approach in two applications: (1) visualizing how indoor furniture (e.g. from product images) might be perceived in a room, (2) hallucinating how accessories like glasses would look when matched with real portraits.

##### Abstract (translated by Google)
我们解决了寻找对前景物体的真实几何校正的问题，使得它在合成到背景图像时看起来很自然。为了实现这一目标，我们提出了一种新型的生成对抗网络（GAN）架构，该架构利用空间变换器网络（STN）作为发生器，我们称之为空间变换器GAN（ST-GAN）。 ST-GAN通过在几何扭曲参数空间中操作寻求图像真实感。特别是，我们利用迭代STN变形方案，并提出了一种顺序训练策略，与单个发生器的天真训练相比，可获得更好的结果。 ST-GAN的关键优势之一是它能够间接适用于高分辨率图像，因为预测的扭曲参数可以在参考帧之间转换。我们在两个应用中展示了我们的方法：（1）可视化室内家具（例如从产品图像中）如何在房间中感知，（2）幻想配件像眼镜在与真实肖像匹配时的外观。

##### URL
[http://arxiv.org/abs/1803.01837](http://arxiv.org/abs/1803.01837)

##### PDF
[http://arxiv.org/pdf/1803.01837](http://arxiv.org/pdf/1803.01837)

