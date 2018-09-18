---
layout: post
title: "DASNet: Reducing Pixel-level Annotations for Instance and Semantic Segmentation"
date: 2018-09-17 04:23:20
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Semantic_Segmentation Detection
author: Chuang Niu, Shenghan Ren, Jimin Liang
mathjax: true
---

* content
{:toc}

##### Abstract
Pixel-level annotation demands expensive human efforts and limits the performance of deep networks that usually benefits from more such training data. In this work we aim to achieve high quality instance and semantic segmentation results over a small set of pixel-level mask annotations and a large set of box annotations. The basic idea is exploring detection models to simplify the pixel-level supervised learning task and thus reduce the required amount of mask annotations. Our architecture, named DASNet, consists of three modules: detection, attention, and segmentation. The detection module detects all classes of objects, the attention module generates multi-scale class-specific features, and the segmentation module recovers the binary masks. Our method demonstrates substantially improved performance compared to existing semi-supervised approaches on PASCAL VOC 2012 dataset.

##### Abstract (translated by Google)
像素级注释需要昂贵的人力工作，并限制通常受益于更多此类训练数据的深度网络的性能。在这项工作中，我们的目标是通过一小组像素级掩码注释和大量的盒子注释来实现高质量的实例和语义分割结果。基本思想是探索检测模型以简化像素级监督学习任务，从而减少所需的掩码注释量。我们的架构名为DASNet，由三个模块组成：检测，注意和分段。检测模块检测所有类别的对象，注意模块生成多尺度类特定的特征，并且分割模块恢复二元掩模。与PASCAL VOC 2012数据集上现有的半监督方法相比，我们的方法显示出显着改善的性能。

##### URL
[http://arxiv.org/abs/1809.06013](http://arxiv.org/abs/1809.06013)

##### PDF
[http://arxiv.org/pdf/1809.06013](http://arxiv.org/pdf/1809.06013)

