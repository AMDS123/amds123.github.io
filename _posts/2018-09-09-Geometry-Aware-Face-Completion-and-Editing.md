---
layout: post
title: "Geometry-Aware Face Completion and Editing"
date: 2018-09-09 13:29:40
categories: arXiv_CV
tags: arXiv_CV Regularization Face Quantitative
author: Linsen Song, Jie Cao, Linxiao Song, Yibo Hu, Ran He
mathjax: true
---

* content
{:toc}

##### Abstract
Face completion is a challenging generation task because it requires generating visually pleasing new pixels that are semantically consistent with the unmasked face region. This paper proposes a geometry-aware Face Completion and Editing NETwork (FCENet) by systematically studying facial geometry from the unmasked region. Firstly, a facial geometry estimator is learned to estimate facial landmark heatmaps and parsing maps from the unmasked face image. Then, an encoder-decoder structure generator serves to complete a face image and disentangle its mask areas conditioned on both the masked face image and the estimated facial geometry images. Besides, since low-rank property exists in manually labeled masks, a low-rank regularization term is imposed on the disentangled masks, enforcing our completion network to manage occlusion area with various shape and size. Furthermore, our network can generate diverse results from the same masked input by modifying estimated facial geometry, which provides a flexible mean to edit the completed face appearance. Extensive experimental results qualitatively and quantitatively demonstrate that our network is able to generate visually pleasing face completion results and edit face attributes as well.

##### Abstract (translated by Google)
面部完成是一项具有挑战性的生成任务，因为它需要生成视觉上令人愉悦的新像素，这些新像素在语义上与未屏蔽的面部区域一致。本文通过系统地研究未掩盖区域的面部几何，提出了几何感知的面部完成和编辑网络（FCENet）。首先，学习面部几何估计器以估计面部地标热图并从未掩蔽的面部图像解析地图。然后，编码器 - 解码器结构生成器用于完成面部图像并解开其在掩蔽的面部图像和估计的面部几何图像两者上调节的掩模区域。此外，由于低级别属性存在于手动标记的掩码中，因此对解开的掩码施加低秩正则化项，强制执行我们的完成网络以管理具有各种形状和大小的遮挡区域。此外，我们的网络可以通过修改估计的面部几何结构从相同的蒙版输入生成不同的结果，这为编辑完成的面部外观提供了灵活的平均值。定性和定量地展示了我们的网络能够产生视觉上令人愉悦的面部完成结果和编辑面部属性的广泛实验结果。

##### URL
[http://arxiv.org/abs/1809.02967](http://arxiv.org/abs/1809.02967)

##### PDF
[http://arxiv.org/pdf/1809.02967](http://arxiv.org/pdf/1809.02967)

