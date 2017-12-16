---
layout: post
title: "Light-Head R-CNN: In Defense of Two-Stage Object Detector"
date: 2017-11-23 02:53:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection Recognition
author: Zeming Li, Chao Peng, Gang Yu, Xiangyu Zhang, Yangdong Deng, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we first investigate why typical two-stage methods are not as fast as single-stage, fast detectors like YOLO and SSD. We find that Faster R-CNN and R-FCN perform an intensive computation after or before RoI warping. Faster R-CNN involves two fully connected layers for RoI recognition, while R-FCN produces a large score maps. Thus, the speed of these networks is slow due to the heavy-head design in the architecture. Even if we significantly reduce the base model, the computation cost cannot be largely decreased accordingly. We propose a new two-stage detector, Light-Head R-CNN, to address the shortcoming in current two-stage approaches. In our design, we make the head of network as light as possible, by using a thin feature map and a cheap R-CNN subnet (pooling and single fully-connected layer). Our ResNet-101 based light-head R-CNN outperforms state-of-art object detectors on COCO while keeping time efficiency. More importantly, simply replacing the backbone with a tiny network (e.g, Xception), our Light-Head R-CNN gets 30.7 mmAP at 102 FPS on COCO, significantly outperforming the single-stage, fast detectors like YOLO and SSD on both speed and accuracy. Code will be made publicly available.

##### Abstract (translated by Google)
在本文中，我们首先研究为什么典型的两阶段方法不如单阶段快速检测器如YOLO和SSD。我们发现更快的R-CNN和R-FCN在RoI翘曲之前或之后进行密集计算。更快的R-CNN涉及两个完全连接的RoI识别层，而R-FCN产生一个大的分数图。因此，由于架构中的重头设计，这些网络的速度很慢。即使我们大大减少了基本模型，计算成本也不能相应地大大降低。我们提出了一个新的两阶段探测器，光头R-CNN，以解决当前两阶段方法的缺点。在我们的设计中，我们通过使用薄特征映射和廉价的R-CNN子网（汇聚和单个完全连接层）使网络头部尽可能轻。我们的基于ResNet-101的光头R-CNN在COCO上优于目前最先进的物体探测器，同时保持时间效率。更重要的是，简单地用一个小网络（例如Xception）取代骨干，我们的光头R-CNN在COCO上以102 FPS获得30.7 mmAP，在速度和速度上明显优于单级快速检测器，如YOLO和SSD准确性。代码将被公开。

##### URL
[https://arxiv.org/abs/1711.07264](https://arxiv.org/abs/1711.07264)

##### PDF
[https://arxiv.org/pdf/1711.07264](https://arxiv.org/pdf/1711.07264)

