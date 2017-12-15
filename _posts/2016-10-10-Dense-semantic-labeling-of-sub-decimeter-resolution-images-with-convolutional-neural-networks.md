---
layout: post
title: "Dense semantic labeling of sub-decimeter resolution images with convolutional neural networks"
date: 2016-10-10 15:07:33
categories: arXiv_CV
tags: arXiv_CV CNN Inference Classification Prediction
author: Michele Volpi, Devis Tuia
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic labeling (or pixel-level land-cover classification) in ultra-high resolution imagery (< 10cm) requires statistical models able to learn high level concepts from spatial data, with large appearance variations. Convolutional Neural Networks (CNNs) achieve this goal by learning discriminatively a hierarchy of representations of increasing abstraction. In this paper we present a CNN-based system relying on an downsample-then-upsample architecture. Specifically, it first learns a rough spatial map of high-level representations by means of convolutions and then learns to upsample them back to the original resolution by deconvolutions. By doing so, the CNN learns to densely label every pixel at the original resolution of the image. This results in many advantages, including i) state-of-the-art numerical accuracy, ii) improved geometric accuracy of predictions and iii) high efficiency at inference time. We test the proposed system on the Vaihingen and Potsdam sub-decimeter resolution datasets, involving semantic labeling of aerial images of 9cm and 5cm resolution, respectively. These datasets are composed by many large and fully annotated tiles allowing an unbiased evaluation of models making use of spatial information. We do so by comparing two standard CNN architectures to the proposed one: standard patch classification, prediction of local label patches by employing only convolutions and full patch labeling by employing deconvolutions. All the systems compare favorably or outperform a state-of-the-art baseline relying on superpixels and powerful appearance descriptors. The proposed full patch labeling CNN outperforms these models by a large margin, also showing a very appealing inference time.

##### Abstract (translated by Google)
超高分辨率图像（<10cm）中的语义标注（或像素级土地覆盖分类）需要能够从空间数据学习高级概念的统计模型，具有大的外观变化。卷积神经网络（CNN）通过区分地学习增加抽象的表示层次来实现这个目标。在本文中，我们提出了一个基于CNN的系统依赖于一个下采样然后上采样架构。具体而言，它首先通过卷积学习高级表示的粗略空间图，然后通过反卷积学习将其上采样回原始分辨率。通过这样做，CNN学习以图像的原始分辨率密集地标记每个像素。这导致了许多优点，包括i）最先进的数值精度，ii）提高的预测几何精度，以及iii）推断时间的高效率。我们在Vaihingen和Potsdam的亚分辨率分辨率数据集上测试所提出的系统，分别涉及9cm和5cm分辨率的航空图像的语义标记。这些数据集是由许多大的，完全注释的图块组成的，允许对利用空间信息的模型进行无偏差的评估。我们通过比较两种标准的CNN架构与标准贴片分类，通过仅采用卷积来预测局部标签贴片以及通过采用反卷积来实现全贴片标签来实现。所有的系统都比较好或超越了依靠超级像素和强大的外观描述符的最先进的基线。提出的全贴片标签CNN的性能优于这些模型，也显示出非常吸引人的推断时间。

##### URL
[https://arxiv.org/abs/1608.00775](https://arxiv.org/abs/1608.00775)

##### PDF
[https://arxiv.org/pdf/1608.00775](https://arxiv.org/pdf/1608.00775)

