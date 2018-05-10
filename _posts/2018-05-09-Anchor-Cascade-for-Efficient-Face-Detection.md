---
layout: post
title: "Anchor Cascade for Efficient Face Detection"
date: 2018-05-09 03:46:35
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Face Image_Classification Classification Detection Face_Detection Recognition Face_Recognition
author: Baosheng Yu, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Face detection is essential to facial analysis tasks such as facial reenactment and face recognition. Both cascade face detectors and anchor-based face detectors have translated shining demos into practice and received intensive attention from the community. However, cascade face detectors often suffer from a low detection accuracy, while anchor-based face detectors rely heavily on very large networks pre-trained on large scale image classification datasets such as ImageNet [1], which is not computationally efficient for both training and deployment. In this paper, we devise an efficient anchor-based cascade framework called anchor cascade. To improve the detection accuracy by exploring contextual information, we further propose a context pyramid maxout mechanism for anchor cascade. As a result, anchor cascade can train very efficient face detection models with a high detection accuracy. Specifically, comparing with a popular CNN-based cascade face detector MTCNN [2], our anchor cascade face detector greatly improves the detection accuracy, e.g., from 0.9435 to 0.9704 at 1k false positives on FDDB, while it still runs in comparable speed. Experimental results on two widely used face detection benchmarks, FDDB and WIDER FACE, demonstrate the effectiveness of the proposed framework.

##### Abstract (translated by Google)
人脸检测对面部分析任务至关重要，例如面部重演和人脸识别。级联面部探测器和基于锚点的面部探测器都将闪光的演示转化为实践并受到社区的广泛关注。然而，级联人脸检测器经常遭受低检测精度，而基于锚的人脸检测器严重依赖于在大规模图像分类数据集（例如ImageNet [1]）上预先训练的非常大的网络，这对于训练和计算都不是有效的部署。在本文中，我们设计了一个高效的基于锚的级联框架，称为锚级联。为了通过探索上下文信息来提高检测精度，我们进一步提出了锚定级联的上下文金字塔最大值机制。因此，锚定级联可以训练非常有效的人脸检测模型，具有较高的检测精度。具体来说，与流行的基于CNN的级联人脸检测器MTCNN [2]相比，我们的锚定级联人脸检测器大大提高了检测精度，例如，在FDDB上1k误报时，检测精度从0.9435到0.9704，而它仍以相当的速度运行。在两个广泛使用的人脸检测基准FDDB和WIDER FACE上的实验结果证明了所提出的框架的有效性。

##### URL
[http://arxiv.org/abs/1805.03363](http://arxiv.org/abs/1805.03363)

##### PDF
[http://arxiv.org/pdf/1805.03363](http://arxiv.org/pdf/1805.03363)

