---
layout: post
title: "Learning Compressible 360° Video Isomers"
date: 2017-12-12 00:35:23
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yu-Chuan Su, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
Standard video encoders developed for conventional narrow field-of-view video are widely applied to 360{\deg} video as well, with reasonable results. However, while this approach commits arbitrarily to a projection of the spherical frames, we observe that some orientations of a 360{\deg} video, once projected, are more compressible than others. We introduce an approach to predict the sphere rotation that will yield the maximal compression rate. Given video clips in their original encoding, a convolutional neural network learns the association between a clip's visual content and its compressibility at different rotations of a cubemap projection. Given a novel video, our learning-based approach efficiently infers the most compressible direction in one shot, without repeated rendering and compression of the source video. We validate our idea on thousands of video clips and multiple popular video codecs. The results show that this untapped dimension of 360{\deg} compression has substantial potential--"good" rotations are typically 8-10% more compressible than bad ones, and our learning approach can predict them reliably 82% of the time.

##### Abstract (translated by Google)
针对传统窄视场视频开发的标准视频编码器也被广泛应用于360度视频，并获得了合理的结果。然而，尽管这种方法任意地进行球形框架的投影，但是我们观察到，一旦投影，360°视频的一些方向比其他方向更可压缩。我们介绍一种方法来预测将产生最大压缩率的球体旋转。给定以原始编码的视频片段，卷积神经网络在立方图投影的不同旋转中学习片段的视觉内容与其可压缩性之间的关联。给定一个新颖的视频，我们的基于学习的方法有效地推断一个镜头中最可压缩的方向，而不重复渲染和压缩源视频。我们验证了我们的想法，成千上万的视频剪辑和多个流行的视频编解码器。结果表明，360°压缩的这个未开发的维度具有很大的潜力 - “好”的旋转通常比坏的旋转可压缩8-10％，而我们的学习方法可以在82％的时间内可靠地预测它们。

##### URL
[https://arxiv.org/abs/1712.04083](https://arxiv.org/abs/1712.04083)

##### PDF
[https://arxiv.org/pdf/1712.04083](https://arxiv.org/pdf/1712.04083)

