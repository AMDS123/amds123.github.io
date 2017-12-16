---
layout: post
title: "Deep Supervision with Shape Concepts for Occlusion-Aware 3D Object Parsing"
date: 2017-04-20 20:19:33
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN
author: Chi Li, M. Zeeshan Zia, Quoc-Huy Tran, Xiang Yu, Gregory D. Hager, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
Monocular 3D object parsing is highly desirable in various scenarios including occlusion reasoning and holistic scene interpretation. We present a deep convolutional neural network (CNN) architecture to localize semantic parts in 2D image and 3D space while inferring their visibility states, given a single RGB image. Our key insight is to exploit domain knowledge to regularize the network by deeply supervising its hidden layers, in order to sequentially infer intermediate concepts associated with the final task. To acquire training data in desired quantities with ground truth 3D shape and relevant concepts, we render 3D object CAD models to generate large-scale synthetic data and simulate challenging occlusion configurations between objects. We train the network only on synthetic data and demonstrate state-of-the-art performances on real image benchmarks including an extended version of KITTI, PASCAL VOC, PASCAL3D+ and IKEA for 2D and 3D keypoint localization and instance segmentation. The empirical results substantiate the utility of our deep supervision scheme by demonstrating effective transfer of knowledge from synthetic data to real images, resulting in less overfitting compared to standard end-to-end training.

##### Abstract (translated by Google)
在包括遮挡推理和整体场景解释的各种场景中，单眼3D对象解析是非常需要的。我们提出一种深度卷积神经网络（CNN）体系结构来定位2D图像和3D空间中的语义部分，同时给出单个RGB图像来推断它们的可见性状态。我们的主要观点是利用领域知识通过深度监督其隐藏层来规范网络，以便顺序地推断与最终任务相关的中间概念。为了获得具有地面真实三维形状和相关概念的理想数量的训练数据，我们渲染三维物体CAD模型以生成大规模合成数据并模拟物体之间具有挑战性的遮挡配置。我们仅对合成数据进行网络训练，并在实际图像基准测试中展示最先进的性能，包括用于2D和3D关键点定位和实例分割的KITTI，PASCAL VOC，PASCAL3D +和IKEA的扩展版本。实证结果证明了我们的深度监督方案的实用性，证明从合成数据到实际图像的知识的有效传递，导致与标准的端到端培训相比较少的过拟合。

##### URL
[https://arxiv.org/abs/1612.02699](https://arxiv.org/abs/1612.02699)

##### PDF
[https://arxiv.org/pdf/1612.02699](https://arxiv.org/pdf/1612.02699)

