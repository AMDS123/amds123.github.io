---
layout: post
title: "Single Image Deraining using Scale-Aware Multi-Stage Recurrent Network"
date: 2017-12-19 09:12:39
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN
author: Ruoteng Li, Loong-Fah Cheong, Robby T. Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Given a single input rainy image, our goal is to visually remove rain streaks and the veiling effect caused by scattering and transmission of rain streaks and rain droplets. We are particularly concerned with heavy rain, where rain streaks of various sizes and directions can overlap each other and the veiling effect reduces contrast severely. To achieve our goal, we introduce a scale-aware multi-stage convolutional neural network. Our main idea here is that different sizes of rain-streaks visually degrade the scene in different ways. Large nearby streaks obstruct larger regions and are likely to reflect specular highlights more prominently than smaller distant streaks. These different effects of different streaks have their own characteristics in their image features, and thus need to be treated differently. To realize this, we create parallel sub-networks that are trained and made aware of these different scales of rain streaks. To our knowledge, this idea of parallel sub-networks that treats the same class of objects according to their unique sub-classes is novel, particularly in the context of rain removal. To verify our idea, we conducted experiments on both synthetic and real images, and found that our method is effective and outperforms the state-of-the-art methods.

##### Abstract (translated by Google)
给定一个输入多雨的图像，我们的目标是从视觉上去除雨水条纹和由雨滴和雨滴的散射和传播引起的遮盖效应。我们特别关注的是大雨和不同尺寸，不同方向的雨痕可以相互重叠，遮盖效果严重降低对比度。为了实现我们的目标，我们引入了一个尺度感知的多级卷积神经网络。我们这里的主要想法是，不同尺寸的雨纹以不同的方式在视觉上降低了场景。较大的附近条纹阻碍较大的区域，并且可能比较小的远处条纹更明显地反映镜面高光。这些不同条纹的不同效果在图像特征上各有特点，因此需要区别对待。为了实现这一点，我们创建了并行的子网络，这些网络经过训练并意识到这些不同尺度的雨痕。就我们所知，这种按照其独特的子类来处理相同类别的对象的并行子网络的想法是新颖的，尤其是在降雨的情况下。为了验证我们的想法，我们对合成和真实图像进行了实验，发现我们的方法是有效的并且胜过最先进的方法。

##### URL
[http://arxiv.org/abs/1712.06830](http://arxiv.org/abs/1712.06830)

##### PDF
[http://arxiv.org/pdf/1712.06830](http://arxiv.org/pdf/1712.06830)

