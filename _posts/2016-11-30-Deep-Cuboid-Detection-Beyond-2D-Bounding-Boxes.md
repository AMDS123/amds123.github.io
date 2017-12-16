---
layout: post
title: "Deep Cuboid Detection: Beyond 2D Bounding Boxes"
date: 2016-11-30 06:00:47
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Deep_Learning Detection
author: Debidatta Dwibedi, Tomasz Malisiewicz, Vijay Badrinarayanan, Andrew Rabinovich
mathjax: true
---

* content
{:toc}

##### Abstract
We present a Deep Cuboid Detector which takes a consumer-quality RGB image of a cluttered scene and localizes all 3D cuboids (box-like objects). Contrary to classical approaches which fit a 3D model from low-level cues like corners, edges, and vanishing points, we propose an end-to-end deep learning system to detect cuboids across many semantic categories (e.g., ovens, shipping boxes, and furniture). We localize cuboids with a 2D bounding box, and simultaneously localize the cuboid's corners, effectively producing a 3D interpretation of box-like objects. We refine keypoints by pooling convolutional features iteratively, improving the baseline method significantly. Our deep learning cuboid detector is trained in an end-to-end fashion and is suitable for real-time applications in augmented reality (AR) and robotics.

##### Abstract (translated by Google)
我们提供了一个深度立方体探测器，它可以获取杂乱景象的消费者级RGB图像，并将所有3D立方体（盒状物体）进行本地化。与经典方法相比，这些经典方法适合于像角落，边缘和消失点等低级线索的3D模型，我们提出了一个端到端的深度学习系统来检测跨许多语义类别的立方体（例如，烤箱，运输箱和家具）。我们用一个2D边界框来定位长方体，同时定位这个长方体的边角，从而有效地产生一个盒状物体的三维解释。我们通过迭代地合并卷积特征来改进关键点，显着改善基线方法。我们的深度学习长方体探测器以端到端的方式进行训练，适用于增强现实（AR）和机器人的实时应用。

##### URL
[https://arxiv.org/abs/1611.10010](https://arxiv.org/abs/1611.10010)

##### PDF
[https://arxiv.org/pdf/1611.10010](https://arxiv.org/pdf/1611.10010)

