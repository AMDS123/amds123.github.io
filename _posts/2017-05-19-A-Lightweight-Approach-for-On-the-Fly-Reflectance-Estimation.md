---
layout: post
title: "A Lightweight Approach for On-the-Fly Reflectance Estimation"
date: 2017-05-19 19:45:57
categories: arXiv_CV
tags: arXiv_CV Face Optimization Inference
author: Kihwan Kim, Jinwei Gu, Stephen Tyree, Pavlo Molchanov, Matthias Nießner, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
Estimating surface reflectance (BRDF) is one key component for complete 3D scene capture, with wide applications in virtual reality, augmented reality, and human computer interaction. Prior work is either limited to controlled environments (\eg gonioreflectometers, light stages, or multi-camera domes), or requires the joint optimization of shape, illumination, and reflectance, which is often computationally too expensive (\eg hours of running time) for real-time applications. Moreover, most prior work requires HDR images as input which further complicates the capture process. In this paper, we propose a lightweight approach for surface reflectance estimation directly from $8$-bit RGB images in real-time, which can be easily plugged into any 3D scanning-and-fusion system with a commodity RGBD sensor. Our method is learning-based, with an inference time of less than 90ms per scene and a model size of less than 340K bytes. We propose two novel network architectures, HemiCNN and Grouplet, to deal with the unstructured input data from multiple viewpoints under unknown illumination. We further design a loss function to resolve the color-constancy and scale ambiguity. In addition, we have created a large synthetic dataset, SynBRDF, which comprises a total of $500$K RGBD images rendered with a physically-based ray tracer under a variety of natural illumination, covering $5000$ materials and $5000$ shapes. SynBRDF is the first large-scale benchmark dataset for reflectance estimation. Experiments on both synthetic data and real data show that the proposed method effectively recovers surface reflectance, and outperforms prior work for reflectance estimation in uncontrolled environments.

##### Abstract (translated by Google)
估计表面反射率（BRDF）是完整的三维场景捕捉的关键组件，在虚拟现实，增强现实和人机交互中具有广泛的应用。先前的工作要么限于受控环境（例如，反射镜，光照阶段或多摄像机圆顶），要么需要联合优化形状，照度和反射率，这在计算上通常太昂贵（例如运行时间的小时数）用于实时应用程序。此外，大多数先前的工作需要HDR图像作为输入，这进一步使捕获过程复杂化。在本文中，我们提出了一个实时从$ 8 $位RGB图像直接进行表面反射估计的轻量级方法，可以很容易地将其插入任何具有商品RGBD传感器的3D扫描和融合系统。我们的方法是基于学习的，每个场景的推理时间小于90ms，模型大小小于340K字节。我们提出了两种新颖的网络体系结构HemiCNN和Grouplet来处理来自未知照明下多个视点的非结构化输入数据。我们进一步设计了一个损失函数来解决颜色恒常性和尺度模糊性。此外，我们还创建了一个大型合成数据集SynBRDF，其中包括总共$ 500 $ K的RGBD图像，这些图像通过基于物理的光线跟踪器在各种自然光照下呈现，包括$ 5000 $材质和$ 5000 $形状。 SynBRDF是第一个用于估算反射率的大型基准数据集。对合成数据和实际数据进行的实验表明，所提出的方法有效地恢复了地表反射率，并且在非控制环境下比以往的反射估计工作更胜一筹。

##### URL
[https://arxiv.org/abs/1705.07162](https://arxiv.org/abs/1705.07162)

##### PDF
[https://arxiv.org/pdf/1705.07162](https://arxiv.org/pdf/1705.07162)

