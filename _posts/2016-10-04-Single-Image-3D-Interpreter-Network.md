---
layout: post
title: "Single Image 3D Interpreter Network"
date: 2016-10-04 19:35:54
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Optimization
author: Jiajun Wu, Tianfan Xue, Joseph J. Lim, Yuandong Tian, Joshua B. Tenenbaum, Antonio Torralba, William T. Freeman
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding 3D object structure from a single image is an important but difficult task in computer vision, mostly due to the lack of 3D object annotations in real images. Previous work tackles this problem by either solving an optimization task given 2D keypoint positions, or training on synthetic data with ground truth 3D information. In this work, we propose 3D INterpreter Network (3D-INN), an end-to-end framework which sequentially estimates 2D keypoint heatmaps and 3D object structure, trained on both real 2D-annotated images and synthetic 3D data. This is made possible mainly by two technical innovations. First, we propose a Projection Layer, which projects estimated 3D structure to 2D space, so that 3D-INN can be trained to predict 3D structural parameters supervised by 2D annotations on real images. Second, heatmaps of keypoints serve as an intermediate representation connecting real and synthetic data, enabling 3D-INN to benefit from the variation and abundance of synthetic 3D objects, without suffering from the difference between the statistics of real and synthesized images due to imperfect rendering. The network achieves state-of-the-art performance on both 2D keypoint estimation and 3D structure recovery. We also show that the recovered 3D information can be used in other vision applications, such as 3D rendering and image retrieval.

##### Abstract (translated by Google)
从单个图像理解3D对象结构在计算机视觉中是一项重要而又艰巨的任务，主要是由于在实际图像中缺少3D对象注释。以前的工作通过解决二维关键点位置的优化任务或利用地面真实三维信息训练合成数据来解决这个问题。在这项工作中，我们提出三维解释网络（3D-INN），这是一个端到端的框架，可以连续估计二维关键点热图和三维物体结构，训练真实的二维注释图像和合成三维数据。这主要得益于两项技术创新。首先，我们提出了一个投影层，它将估计的三维结构投影到二维空间，从而可以训练3D-INN以预测由实际图像上的二维注释监督的三维结构参数。其次，关键点的热图可作为连接真实和合成数据的中间表示，使得3D-INN能够从合成3D对象的变化和丰富中受益，而不会由于不完美的渲染而导致真实和合成图像的统计差异。该网络在二维关键点估计和三维结构恢复方面都达到了最先进的性能。我们还表明，恢复的3D信息可以用于其他视觉应用，例如3D渲染和图像检索。

##### URL
[https://arxiv.org/abs/1604.08685](https://arxiv.org/abs/1604.08685)

##### PDF
[https://arxiv.org/pdf/1604.08685](https://arxiv.org/pdf/1604.08685)

