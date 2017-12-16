---
layout: post
title: "FoveaNet: Perspective-aware Urban Scene Parsing"
date: 2017-08-08 09:29:50
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Xin Li, Zequn Jie, Wei Wang, Changsong Liu, Jimei Yang, Xiaohui Shen, Zhe Lin, Qiang Chen, Shuicheng Yan, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Parsing urban scene images benefits many applications, especially self-driving. Most of the current solutions employ generic image parsing models that treat all scales and locations in the images equally and do not consider the geometry property of car-captured urban scene images. Thus, they suffer from heterogeneous object scales caused by perspective projection of cameras on actual scenes and inevitably encounter parsing failures on distant objects as well as other boundary and recognition errors. In this work, we propose a new FoveaNet model to fully exploit the perspective geometry of scene images and address the common failures of generic parsing models. FoveaNet estimates the perspective geometry of a scene image through a convolutional network which integrates supportive evidence from contextual objects within the image. Based on the perspective geometry information, FoveaNet "undoes" the camera perspective projection analyzing regions in the space of the actual scene, and thus provides much more reliable parsing results. Furthermore, to effectively address the recognition errors, FoveaNet introduces a new dense CRFs model that takes the perspective geometry as a prior potential. We evaluate FoveaNet on two urban scene parsing datasets, Cityspaces and CamVid, which demonstrates that FoveaNet can outperform all the well-established baselines and provide new state-of-the-art performance.

##### Abstract (translated by Google)
解析城市场景图像有利于许多应用，特别是自驾车。目前大多数的解决方案都采用通用的图像解析模型，它们均等地处理图像中的所有尺度和位置，而不考虑汽车捕捉的城市场景图像的几何属性。因此，它们受到摄像机在实际场景中透视投影造成的异构物体尺度的困扰，不可避免地会遇到远处物体的解析失败以及其他边界和识别错误。在这项工作中，我们提出了一个新的FoveaNet模型，以充分利用场景图像的视角几何，并解决通用解析模型的常见失败。 FoveaNet通过卷积网络估计场景图像的透视几何图形，该图像集成了来自图像中的上下文对象的支持性证据。基于透视几何信息，FoveaNet“撤销”了相机透视投影分析的实际场景空间区域，从而提供更可靠的解析结果。此外，为了有效解决识别错误，FoveaNet引入了新的密集型CRF模型，将透视几何图形作为先验潜力。我们在两个城市场景解析数据集Cityspaces和CamVid上评估FoveaNet，这表明FoveaNet可以胜过所有已建立的基线并提供新的最新性能。

##### URL
[https://arxiv.org/abs/1708.02421](https://arxiv.org/abs/1708.02421)

##### PDF
[https://arxiv.org/pdf/1708.02421](https://arxiv.org/pdf/1708.02421)

