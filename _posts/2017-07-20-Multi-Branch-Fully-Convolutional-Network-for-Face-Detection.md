---
layout: post
title: "Multi-Branch Fully Convolutional Network for Face Detection"
date: 2017-07-20 00:49:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Detection Face_Detection
author: Yancheng Bai, Bernard Ghanem
mathjax: true
---

* content
{:toc}

##### Abstract
Face detection is a fundamental problem in computer vision. It is still a challenging task in unconstrained conditions due to significant variations in scale, pose, expressions, and occlusion. In this paper, we propose a multi-branch fully convolutional network (MB-FCN) for face detection, which considers both efficiency and effectiveness in the design process. Our MB-FCN detector can deal with faces at all scale ranges with only a single pass through the backbone network. As such, our MB-FCN model saves computation and thus is more efficient, compared to previous methods that make multiple passes. For each branch, the specific skip connections of the convolutional feature maps at different layers are exploited to represent faces in specific scale ranges. Specifically, small faces can be represented with both shallow fine-grained and deep powerful coarse features. With this representation, superior improvement in performance is registered for the task of detecting small faces. We test our MB-FCN detector on two public face detection benchmarks, including FDDB and WIDER FACE. Extensive experiments show that our detector outperforms state-of-the-art methods on all these datasets in general and by a substantial margin on the most challenging among them (e.g. WIDER FACE Hard subset). Also, MB-FCN runs at 15 FPS on a GPU for images of size 640 x 480 with no assumption on the minimum detectable face size.

##### Abstract (translated by Google)
人脸检测是计算机视觉中的一个基本问题。由于尺度，姿态，表情和遮挡的显着变化，在无约束条件下仍然是一个具有挑战性的任务。在本文中，我们提出了一个多分支全卷积网络（MB-FCN）用于人脸检测，它考虑了设计过程中的效率和效率。我们的MB-FCN探测器可以处理所有尺度范围内的人脸，只需要通过骨干网络一次。因此，与先前的多次通过的方法相比，我们的MB-FCN模型节省了计算量，因此效率更高。对于每个分支，利用不同层的卷积特征映射的特定跳转连接来表示特定尺度范围中的面孔。具体而言，可以用浅的细粒和深的粗粒特征表示小的面。通过这种表示，在检测小面部的任务中，性能的优异改进被记录下来。我们在两个公共人脸检测基准测试我们的MB-FCN检测器，包括FDDB和WIDER FACE。大量的实验表明，我们的检测器在所有这些数据集上总体上优于最先进的方法，并且在其中最具挑战性的方面（例如更宽的面硬子集）具有相当大的余量。此外，MB-FCN在GPU上运行速度为15 FPS，图像尺寸为640 x 480，不需要假定最小的可检测面部大小。

##### URL
[https://arxiv.org/abs/1707.06330](https://arxiv.org/abs/1707.06330)

##### PDF
[https://arxiv.org/pdf/1707.06330](https://arxiv.org/pdf/1707.06330)

