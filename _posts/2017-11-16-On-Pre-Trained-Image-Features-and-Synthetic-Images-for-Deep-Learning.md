---
layout: post
title: "On Pre-Trained Image Features and Synthetic Images for Deep Learning"
date: 2017-11-16 21:46:24
categories: arXiv_CV
tags: arXiv_CV Object_Detection Deep_Learning Detection Recognition
author: Stefan Hinterstoisser, Vincent Lepetit, Paul Wohlhart, Kurt Konolige
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Learning methods usually require huge amounts of training data to perform at their full potential, and often require expensive manual labeling. Using synthetic images is therefore very attractive to train object detectors, as the labeling comes for free, and several approaches have been proposed to combine synthetic and real images for training. In this paper, we show that a simple trick is sufficient to train very effectively modern object detectors with synthetic images only: We freeze the layers responsible for feature extraction to generic layers pre-trained on real images, and train only the remaining layers with plain OpenGL rendering. Our experiments with very recent deep architectures for object recognition (Faster-RCNN, R-FCN, Mask-RCNN) and image feature extractors (InceptionResnet and Resnet) show this simple approach performs surprisingly well.

##### Abstract (translated by Google)
深度学习方法通​​常需要大量的培训数据来充分发挥其潜力，而且往往需要昂贵的人工标签。因此，使用合成图像对于训练物体检测器是非常有吸引力的，因为标签是免费的，并且已经提出了几种方法来将合成图像和真实图像进行训练。在本文中，我们展示了一个简单的技巧就足以用合成图像非常有效地训练现代物体探测器：我们将负责特征提取的层冻结到在真实图像上预训练的通用层，并且仅训练剩余的层OpenGL渲染。我们用非常近的深度体系结构（Faster-RCNN，R-FCN，Mask-RCNN）和图像特征提取器（InceptionResnet and Resnet）进行的实验表明，这种简单的方法表现出色。

##### URL
[https://arxiv.org/abs/1710.10710](https://arxiv.org/abs/1710.10710)

##### PDF
[https://arxiv.org/pdf/1710.10710](https://arxiv.org/pdf/1710.10710)

