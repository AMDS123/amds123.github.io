---
layout: post
title: "Scale Optimization for Full-Image-CNN Vehicle Detection"
date: 2018-02-20 00:54:15
categories: arXiv_AI
tags: arXiv_AI Object_Detection CNN Optimization Detection
author: Yang Gao, Shouyan Guo, Kaimin Huang, Jiaxin Chen, Qian Gong, Yang Zou, Tong Bai, Gary Overett
mathjax: true
---

* content
{:toc}

##### Abstract
Many state-of-the-art general object detection methods make use of shared full-image convolutional features (as in Faster R-CNN). This achieves a reasonable test-phase computation time while enjoys the discriminative power provided by large Convolutional Neural Network (CNN) models. Such designs excel on benchmarks which contain natural images but which have very unnatural distributions, i.e. they have an unnaturally high-frequency of the target classes and a bias towards a "friendly" or "dominant" object scale. In this paper we present further study of the use and adaptation of the Faster R-CNN object detection method for datasets presenting natural scale distribution and unbiased real-world object frequency. In particular, we show that better alignment of the detector scale sensitivity to the extant distribution improves vehicle detection performance. We do this by modifying both the selection of Region Proposals, and through using more scale-appropriate full-image convolution features within the CNN model. By selecting better scales in the region proposal input and by combining feature maps through careful design of the convolutional neural network, we improve performance on smaller objects. We significantly increase detection AP for the KITTI dataset car class from 76.3% on our baseline Faster R-CNN detector to 83.6% in our improved detector.

##### Abstract (translated by Google)
许多最先进的通用对象检测方法利用共享的全图像卷积特征（如更快的R-CNN）。这实现了合理的测试阶段计算时间，同时享有由大型卷积神经网络（CNN）模型提供的判别力。这样的设计擅长于包含自然图像但具有非常不自然的分布的基准，即它们具有不自然的高频目标等级并且偏向于“友好”或“主导”对象尺度。在本文中，我们将进一步研究更快的R-CNN物体检测方法在数据集中的使用和适应情况，以呈现自然尺度分布和无偏的现实世界物体频率。特别是，我们证明，探测器比例灵敏度与现存分布的更好对准会提高车辆检测性能。我们通过修改区域建议的选择以及在CNN模型中使用更多的适合尺度的全图像卷积功能来实现这一点。通过在地区提案输入中选择更好的尺度，并通过仔细设计卷积神经网络来组合特征地图，我们可以提高小型物体的性能。我们将KITTI数据集车型的检测AP从我们的基准Faster R-CNN检测器的76.3％显着提高至83.6％。

##### URL
[http://arxiv.org/abs/1802.06926](http://arxiv.org/abs/1802.06926)

##### PDF
[http://arxiv.org/pdf/1802.06926](http://arxiv.org/pdf/1802.06926)

