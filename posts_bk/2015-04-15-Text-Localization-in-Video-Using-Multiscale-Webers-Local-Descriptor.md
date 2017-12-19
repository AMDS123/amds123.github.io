---
layout: post
title: "Text Localization in Video Using Multiscale Weber's Local Descriptor"
date: 2015-04-15 07:56:05
categories: arXiv_CV
tags: arXiv_CV Relation
author: B.H. Shekar, Smitha M.L.
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel approach for detecting the text present in videos and scene images based on the Multiscale Weber's Local Descriptor (MWLD). Given an input video, the shots are identified and the key frames are extracted based on their spatio-temporal relationship. From each key frame, we detect the local region information using WLD with different radius and neighborhood relationship of pixel values and hence obtained intensity enhanced key frames at multiple scales. These multiscale WLD key frames are merged together and then the horizontal gradients are computed using morphological operations. The obtained results are then binarized and the false positives are eliminated based on geometrical properties. Finally, we employ connected component analysis and morphological dilation operation to determine the text regions that aids in text localization. The experimental results obtained on publicly available standard Hua, Horizontal-1 and Horizontal-2 video dataset illustrate that the proposed method can accurately detect and localize texts of various sizes, fonts and colors in videos.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于多尺度Weber局部描述符（MWLD）检测视频和场景图像中的文本的新方法。给定一个输入视频，镜头被识别，关键帧被提取基于他们的时空关系。从每个关键帧中，我们使用不同半径的WLD和像素值的邻域关系检测局部区域信息，从而获得多尺度的强度增强关键帧。这些多尺度WLD关键帧合并在一起，然后使用形态学运算来计算水平梯度。然后将得到的结果二值化，根据几何特性消除误报。最后，我们采用连通分量分析和形态学扩张操作来确定文本区域，这有助于文本定位。实验结果表明，该方法可以准确地检测和定位视频中各种大小，字体和颜色的文本。

##### URL
[https://arxiv.org/abs/1504.03810](https://arxiv.org/abs/1504.03810)

##### PDF
[https://arxiv.org/pdf/1504.03810](https://arxiv.org/pdf/1504.03810)

