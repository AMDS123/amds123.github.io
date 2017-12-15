---
layout: post
title: "Lifting GIS Maps into Strong Geometric Context for Scene Understanding"
date: 2016-01-08 19:52:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation GAN Face Semantic_Segmentation Prediction Detection
author: Raúl Díaz, Minhaeng Lee, Jochen Schubert, Charless C. Fowlkes
mathjax: true
---

* content
{:toc}

##### Abstract
Contextual information can have a substantial impact on the performance of visual tasks such as semantic segmentation, object detection, and geometric estimation. Data stored in Geographic Information Systems (GIS) offers a rich source of contextual information that has been largely untapped by computer vision. We propose to leverage such information for scene understanding by combining GIS resources with large sets of unorganized photographs using Structure from Motion (SfM) techniques. We present a pipeline to quickly generate strong 3D geometric priors from 2D GIS data using SfM models aligned with minimal user input. Given an image resectioned against this model, we generate robust predictions of depth, surface normals, and semantic labels. We show that the precision of the predicted geometry is substantially more accurate other single-image depth estimation methods. We then demonstrate the utility of these contextual constraints for re-scoring pedestrian detections, and use these GIS contextual features alongside object detection score maps to improve a CRF-based semantic segmentation framework, boosting accuracy over baseline models.

##### Abstract (translated by Google)
上下文信息可以对诸如语义分割，对象检测和几何估计等视觉任务的性能有实质性的影响。存储在地理信息系统（GIS）中的数据提供了丰富的背景信息来源，这在很大程度上尚未被计算机视觉所利用。我们建议将这些信息用于场景的理解，通过结合运动（SfM）技术将GIS资源与大量无组织的照片相结合。我们提供了一个管道，使用与最小用户输入对齐的SfM模型，快速从2D GIS数据生成强大的3D几何先验。给定一个对这个模型进行切除的图像，我们生成深度，曲面法线和语义标签的强大预测。我们表明，预测几何的精度是其他单一图像深度估计方法大大更准确。然后，我们演示这些上下文约束的效用，用于对行人检测进行重新评分，并将这些GIS上下文特征与对象检测评分图一起使用，以改进基于CRF的语义分割框架，提高基线模型的准确性。

##### URL
[https://arxiv.org/abs/1507.03698](https://arxiv.org/abs/1507.03698)

##### PDF
[https://arxiv.org/pdf/1507.03698](https://arxiv.org/pdf/1507.03698)

