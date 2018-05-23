---
layout: post
title: "Facade Segmentation in the Wild"
date: 2018-05-09 16:21:31
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: John Femiani, Wamiq Reyaz Para, Niloy Mitra, Peter Wonka
mathjax: true
---

* content
{:toc}

##### Abstract
Urban facade segmentation from automatically acquired imagery, in contrast to traditional image segmentation, poses several unique challenges. 360-degree photospheres captured from vehicles are an effective way to capture a large number of images, but this data presents difficult-to-model warping and stitching artifacts. In addition, each pixel can belong to multiple facade elements, and different facade elements (e.g., window, balcony, sill, etc.) are correlated and vary wildly in their characteristics. In this paper, we propose three network architectures of varying complexity to achieve multilabel semantic segmentation of facade images while exploiting their unique characteristics. Specifically, we propose a MULTIFACSEGNET architecture to assign multiple labels to each pixel, a SEPARABLE architecture as a low-rank formulation that encourages extraction of rectangular elements, and a COMPATIBILITY network that simultaneously seeks segmentation across facade element types allowing the network to 'see' intermediate output probabilities of the various facade element classes. Our results on benchmark datasets show significant improvements over existing facade segmentation approaches for the typical facade elements. For example, on one commonly used dataset, the accuracy scores for window(the most important architectural element) increases from 0.91 to 0.97 percent compared to the best competing method, and comparable improvements on other element types.

##### Abstract (translated by Google)
与传统图像分割相比，自动获取图像的城市门面分割带来了几个独特的挑战。从车辆捕捉到的360度光球是捕捉大量图像的有效方式，但是这些数据表明难以模拟的翘曲和拼接伪影。另外，每个像素可以属于多个立面元件，并且不同的立面元件（例如，窗户，阳台，门槛等）相关并且在其特性上大幅变化。在本文中，我们提出了三种不同复杂度的网络体系结构，在利用其独特特性的同时实现门面图像的多标签语义分割。具体来说，我们提出了一个MULTIFACSEGNET架构为每个像素分配多个标签，一个SEPARABLE架构作为鼓励提取矩形元素的低阶公式，以及一个COMPATIBILITY网络，它同时寻求跨立面元素类型的分割，允许网络“看到”各种立面元素类的中间输出概率。我们在基准数据集上的结果显示，与典型外立面元素的现有立面分割方法相比，显着改进。例如，在一个常用的数据集中，与最佳竞争方法相比，窗口（最重要的架构元素）的准确性分数从0.91增加到0.97％，并对其他元素类型进行可比较的改进。

##### URL
[https://arxiv.org/abs/1805.08634](https://arxiv.org/abs/1805.08634)

##### PDF
[https://arxiv.org/pdf/1805.08634](https://arxiv.org/pdf/1805.08634)

