---
layout: post
title: "Domain Adaptive Faster R-CNN for Object Detection in the Wild"
date: 2018-03-08 18:36:22
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Object_Detection Detection
author: Yuhua Chen, Wen Li, Christos Sakaridis, Dengxin Dai, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection typically assumes that training and test data are drawn from an identical distribution, which, however, does not always hold in practice. Such a distribution mismatch will lead to a significant performance drop. In this work, we aim to improve the cross-domain robustness of object detection. We tackle the domain shift on two levels: 1) the image-level shift, such as image style, illumination, etc, and 2) the instance-level shift, such as object appearance, size, etc. We build our approach based on the recent state-of-the-art Faster R-CNN model, and design two domain adaptation components, on image level and instance level, to reduce the domain discrepancy. The two domain adaptation components are based on H-divergence theory, and are implemented by learning a domain classifier in adversarial training manner. The domain classifiers on different levels are further reinforced with a consistency regularization to learn a domain-invariant region proposal network (RPN) in the Faster R-CNN model. We evaluate our newly proposed approach using multiple datasets including Cityscapes, KITTI, SIM10K, etc. The results demonstrate the effectiveness of our proposed approach for robust object detection in various domain shift scenarios.

##### Abstract (translated by Google)
对象检测通常假定训练和测试数据是从相同的分布中抽取出来的，然而在实践中并不总是如此。这种分配不匹配将导致显着的性能下降。在这项工作中，我们旨在提高对象检测的跨域稳健性。我们在两个层面上处理域转换：1）图像级别转换，例如图像风格，照明等; 2）实例级别转换，例如对象外观，大小等。我们基于最近最先进的Raster R-CNN模型，并在图像级别和实例级别设计两个域自适应组件，以减少域差异。这两个领域的适应组件是基于H-散度理论，并通过对抗训练方式学习领域分类器来实现。通过一致性正则化，可以进一步加强不同层次上的域分类器，从而在更快的R-CNN模型中学习域不变区域提议网络（RPN）。我们使用包括Cityscapes，KITTI，SIM10K等在内的多个数据集来评估我们新提出的方法。结果证明了我们提出的方法在各种域移位情景下的鲁棒对象检测的有效性。

##### URL
[http://arxiv.org/abs/1803.03243](http://arxiv.org/abs/1803.03243)

##### PDF
[http://arxiv.org/pdf/1803.03243](http://arxiv.org/pdf/1803.03243)

