---
layout: post
title: "Switchable Temporal Propagation Network"
date: 2018-05-04 17:55:41
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation
author: Sifei Liu, Guangyu Zhong, Shalini De Mello, Jinwei Gu, Varun Jampani, Ming-Hsuan Yang, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
Videos contain highly redundant information between frames. Such redundancy has been extensively studied in video compression and encoding, but is less explored for more advanced video processing. In this paper, we propose a learnable unified framework for propagating a variety of visual properties of video images, including but not limited to color, high dynamic range (HDR), and segmentation information, where the properties are available for only a few key-frames. Our approach is based on a temporal propagation network (TPN), which models the transition-related affinity between a pair of frames in a purely data-driven manner. We theoretically prove two essential factors for TPN: (a) by regularizing the global transformation matrix as orthogonal, the "style energy" of the property can be well preserved during propagation; (b) such regularization can be achieved by the proposed switchable TPN with bi-directional training on pairs of frames. We apply the switchable TPN to three tasks: colorizing a gray-scale video based on a few color key-frames, generating an HDR video from a low dynamic range (LDR) video and a few HDR frames, and propagating a segmentation mask from the first frame in videos. Experimental results show that our approach is significantly more accurate and efficient than the state-of-the-art methods.

##### Abstract (translated by Google)
视频在帧之间包含高度冗余的信息。这种冗余已经在视频压缩和编码方面得到了广泛的研究，但对于更先进的视频处理的研究较少。在本文中，我们提出了一个可学习的统一框架，用于传播视频图像的各种视觉属性，包括但不限于颜色，高动态范围（HDR）和分割信息，其中属性仅适用于几个键 - 帧。我们的方法基于时间传播网络（TPN），该网络以纯数据驱动的方式对一对帧之间的转换相关亲和力进行建模。我们在理论上证明了TPN的两个基本要素：（a）通过将全局变换矩阵规则化为正交，在传播过程中可以很好地保留属性的“样式能量”; （b）这种正规化可以通过建议的可切换TPN在成对帧上进行双向训练来实现。我们将可切换TPN应用于三项任务：基于几个颜色关键帧着色灰度视频，从低动态范围（LDR）视频和几个HDR帧生成HDR视频，并从视频中的第一帧。实验结果表明，我们的方法比最先进的方法更精确和有效。

##### URL
[http://arxiv.org/abs/1804.08758](http://arxiv.org/abs/1804.08758)

##### PDF
[http://arxiv.org/pdf/1804.08758](http://arxiv.org/pdf/1804.08758)

