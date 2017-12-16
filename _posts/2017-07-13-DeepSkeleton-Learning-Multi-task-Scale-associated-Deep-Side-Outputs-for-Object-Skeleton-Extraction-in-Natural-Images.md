---
layout: post
title: "DeepSkeleton: Learning Multi-task Scale-associated Deep Side Outputs for Object Skeleton Extraction in Natural Images"
date: 2017-07-13 19:39:16
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Prediction Detection Relation
author: Wei Shen, Kai Zhao, Yuan Jiang, Yan Wang, Xiang Bai, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Object skeletons are useful for object representation and object detection. They are complementary to the object contour, and provide extra information, such as how object scale (thickness) varies among object parts. But object skeleton extraction from natural images is very challenging, because it requires the extractor to be able to capture both local and non-local image context in order to determine the scale of each skeleton pixel. In this paper, we present a novel fully convolutional network with multiple scale-associated side outputs to address this problem. By observing the relationship between the receptive field sizes of the different layers in the network and the skeleton scales they can capture, we introduce two scale-associated side outputs to each stage of the network. The network is trained by multi-task learning, where one task is skeleton localization to classify whether a pixel is a skeleton pixel or not, and the other is skeleton scale prediction to regress the scale of each skeleton pixel. Supervision is imposed at different stages by guiding the scale-associated side outputs toward the groundtruth skeletons at the appropriate scales. The responses of the multiple scale-associated side outputs are then fused in a scale-specific way to detect skeleton pixels using multiple scales effectively. Our method achieves promising results on two skeleton extraction datasets, and significantly outperforms other competitors. Additionally, the usefulness of the obtained skeletons and scales (thickness) are verified on two object detection applications: Foreground object segmentation and object proposal detection.

##### Abstract (translated by Google)
对象骨架对于对象表示和对象检测非常有用。它们与对象轮廓互补，并提供额外的信息，如对象部分的对象比例（厚度）如何变化。但是从自然图像中提取对象骨架是非常具有挑战性的，因为它要求提取器能够捕获局部和非局部图像上下文以确定每个骨架像素的尺度。在本文中，我们提出了一个新的完全卷积网络与多个尺度相关的侧面输出来解决这个问题。通过观察网络中不同层次的接受场大小与它们可以捕获的骨架尺度之间的关系，我们在网络的每个阶段引入两个与尺度相关的侧向输出。通过多任务学习训练网络，其中一个任务是骨架定位以分类像素是否是骨架像素，另一个是骨架尺度预测以回归每个骨架像素的尺度。监督是在不同的阶段，通过引导规模相关的侧面产出在适当的尺度上朝向地面骨架而施加的。然后将多尺度相关边输出的响应以比例尺特定的方式进行融合，以有效地使用多尺度来检测骨架像素。我们的方法在两个骨架提取数据集上取得了令人满意的结果，并且明显优于其他竞争者。另外，所获得的骨架和尺度（厚度）的有用性在两个对象检测应用中被验证：前景对象分割和对象建议检测。

##### URL
[https://arxiv.org/abs/1609.03659](https://arxiv.org/abs/1609.03659)

##### PDF
[https://arxiv.org/pdf/1609.03659](https://arxiv.org/pdf/1609.03659)

