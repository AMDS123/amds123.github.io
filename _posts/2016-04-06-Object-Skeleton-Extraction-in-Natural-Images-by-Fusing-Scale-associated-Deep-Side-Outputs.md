---
layout: post
title: "Object Skeleton Extraction in Natural Images by Fusing Scale-associated Deep Side Outputs"
date: 2016-04-06 05:51:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection Relation
author: Wei Shen, Kai Zhao, Yuan Jiang, Yan Wang, Zhijiang Zhang, Xiang Bai
mathjax: true
---

* content
{:toc}

##### Abstract
Object skeleton is a useful cue for object detection, complementary to the object contour, as it provides a structural representation to describe the relationship among object parts. While object skeleton extraction in natural images is a very challenging problem, as it requires the extractor to be able to capture both local and global image context to determine the intrinsic scale of each skeleton pixel. Existing methods rely on per-pixel based multi-scale feature computation, which results in difficult modeling and high time consumption. In this paper, we present a fully convolutional network with multiple scale-associated side outputs to address this problem. By observing the relationship between the receptive field sizes of the sequential stages in the network and the skeleton scales they can capture, we introduce a scale-associated side output to each stage. We impose supervision to different stages by guiding the scale-associated side outputs toward groundtruth skeletons of different scales. The responses of the multiple scale-associated side outputs are then fused in a scale-specific way to localize skeleton pixels with multiple scales effectively. Our method achieves promising results on two skeleton extraction datasets, and significantly outperforms other competitors.

##### Abstract (translated by Google)
对象骨架是物体检测的有用线索，与对象轮廓互补，因为它提供了描述对象部分之间关系的结构表示。虽然自然图像中的对象骨架提取是一个非常具有挑战性的问题，因为它要求提取器能够捕获局部和全局图像上下文以确定每个骨架像素的内在尺度。现有的方法依赖于基于每个像素的多尺度特征计算，这造成了难以建模和高时间消耗。在本文中，我们提出了一个具有多个尺度相关副输出的全卷积网络来解决这个问题。通过观察网络中连续阶段的感受野大小与它们可以捕获的骨架尺度之间的关系，我们在每个阶段引入一个与尺度相关的侧向输出。我们通过引导规模相关方面的产出向不同规模的地面骨架指导，对不同阶段实行监督。然后将多尺度相关副边输出的响应按照比例尺特定的方式进行融合，以有效地定位具有多尺度的骨架像素。我们的方法在两个骨架提取数据集上取得了令人满意的结果，并且明显优于其他竞争者。

##### URL
[https://arxiv.org/abs/1603.09446](https://arxiv.org/abs/1603.09446)

##### PDF
[https://arxiv.org/pdf/1603.09446](https://arxiv.org/pdf/1603.09446)

