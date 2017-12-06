---
layout: post
title: 'An End-to-end 3D Convolutional Neural Network for Action Detection and Segmentation in Videos'
date: 2017-11-30 19:26:49
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Rui Hou, Chen Chen, Mubarak Shah
---

* content
{:toc}

##### Abstract
In this paper, we propose an end-to-end 3D CNN for action detection and segmentation in videos. The proposed architecture is a unified deep network that is able to recognize and localize action based on 3D convolution features. A video is first divided into equal length clips and next for each clip a set of tube proposals are generated based on 3D CNN features. Finally, the tube proposals of different clips are linked together and spatio-temporal action detection is performed using these linked video proposals. This top-down action detection approach explicitly relies on a set of good tube proposals to perform well and training the bounding box regression usually requires a large number of annotated samples. To remedy this, we further extend the 3D CNN to an encoder-decoder structure and formulate the localization problem as action segmentation. The foreground regions (i.e. action regions) for each frame are segmented first then the segmented foreground maps are used to generate the bounding boxes. This bottom-up approach effectively avoids tube proposal generation by leveraging the pixel-wise annotations of segmentation. The segmentation framework also can be readily applied to a general problem of video object segmentation. Extensive experiments on several video datasets demonstrate the superior performance of our approach for action detection and video object segmentation compared to the state-of-the-arts.

##### Abstract (translated by Google)
在本文中，我们提出了一个端到端的3D CNN，用于视频中的动作检测和分割。所提出的体系结构是一个统一的深度网络，能够基于三维卷积特征识别和定位动作。首先将视频分成等长的剪辑，然后针对每个剪辑，基于3D CNN特征生成一组管提议。最后，将不同剪辑的管提议链接在一起，并使用这些链接的视频提议来执行时空动作检测。这种自顶向下的动作检测方法明确地依赖于一组好的管提议来良好地执行，并且训练边界框回归通常需要大量的带注释的样本。为了弥补这一点，我们进一步将3D CNN扩展到编码器 - 解码器结构，并将动作分割制定为定位问题。首先对每帧的前景区域（即动作区域）进行分段，然后使用分段的前景地图来生成边界框。这种自下而上的方法通过利用分段的像素明智的注释来有效地避免管提议生成。分割框架也可以容易地应用于视频对象分割的一般问题。对多个视频数据集进行的大量实验证明，与现有技术相比，我们的动作检测和视频对象分割方法具有优越的性能。

##### URL
[http://arxiv.org/abs/1712.01111](http://arxiv.org/abs/1712.01111)

