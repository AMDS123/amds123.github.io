---
layout: post
title: "Self Super-Resolution for Magnetic Resonance Images using Deep Networks"
date: 2018-02-26 16:17:18
categories: arXiv_CV
tags: arXiv_CV Super_Resolution
author: Can Zhao, Aaron Carass, Blake E. Dewey, Jerry L. Prince
mathjax: true
---

* content
{:toc}

##### Abstract
High resolution magnetic resonance~(MR) imaging~(MRI) is desirable in many clinical applications, however, there is a trade-off between resolution, speed of acquisition, and noise. It is common for MR images to have worse through-plane resolution~(slice thickness) than in-plane resolution. In these MRI images, high frequency information in the through-plane direction is not acquired, and cannot be resolved through interpolation. To address this issue, super-resolution methods have been developed to enhance spatial resolution. As an ill-posed problem, state-of-the-art super-resolution methods rely on the presence of external/training atlases to learn the transform from low resolution~(LR) images to high resolution~(HR) images. For several reasons, such HR atlas images are often not available for MRI sequences. This paper presents a self super-resolution~(SSR) algorithm, which does not use any external atlas images, yet can still resolve HR images only reliant on the acquired LR image. We use a blurred version of the input image to create training data for a state-of-the-art super-resolution deep network. The trained network is applied to the original input image to estimate the HR image. Our SSR result shows a significant improvement on through-plane resolution compared to competing SSR methods.

##### Abstract (translated by Google)
高分辨率磁共振〜（MR）成像〜（MRI）在许多临床应用中是理想的，然而，在分辨率，采集速度和噪声之间存在折衷。对于MR图像来说，穿透平面分辨率（切片厚度）比平面分辨率更差是常见的。在这些MRI图像中，没有获得贯穿平面方向的高频信息，并且不能通过插值来解决。为了解决这个问题，已经开发了超分辨率方法来提高空间分辨率。作为一个病态问题，最先进的超分辨率方法依赖于外部/训练图谱的存在来学习从低分辨率〜（LR）图像到高分辨率〜（HR）图像的转换。出于多种原因，这些HR图谱通常不适用于MRI序列。本文提出了一种自身超分辨率〜（SSR）算法，该算法不使用任何外部图谱，但仍然可以仅依赖于所获取的LR图像来分辨HR图像。我们使用输入图像的模糊版本来创建最先进的超分辨率深度网络的训练数据。将训练好的网络应用于原始输入图像以估计HR图像。与竞争SSR方法相比，我们的SSR结果显示通透分辨率显着提高。

##### URL
[http://arxiv.org/abs/1802.09431](http://arxiv.org/abs/1802.09431)

##### PDF
[http://arxiv.org/pdf/1802.09431](http://arxiv.org/pdf/1802.09431)

