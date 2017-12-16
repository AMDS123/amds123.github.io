---
layout: post
title: "A Deep Structured Learning Approach Towards Automating Connectome Reconstruction from 3D Electron Micrographs"
date: 2017-09-24 16:16:36
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction
author: Jan Funke, Fabian David Tschopp, William Grisaitis, Arlo Sheridan, Chandan Singh, Stephan Saalfeld, Srinivas C. Turaga
mathjax: true
---

* content
{:toc}

##### Abstract
We present a deep structured learning method for neuron segmentation from 3D electron microscopy (EM) which improves significantly upon the state of the art in terms of accuracy and scalability. Our method consists of a 3D U-Net classifier predicting affinity graphs on voxels, followed by iterative region agglomeration. We train the U-Net using a new structured loss based on MALIS that encourages topological correctness. Our extension consists of two parts: First, an $O(n\log(n))$ method to compute the loss gradient, improving over the originally proposed $O(n^2)$ algorithm. Second, we compute the gradient in two separate passes to avoid spurious contributions in early training stages. Our affinity predictions are accurate enough that simple agglomeration outperforms more involved methods used earlier on inferior predictions. We present results on three datasets (CREMI, FIB, and SegEM) of different imaging techniques and animals and achieve improvements over previous results of 27%, 15%, and 250%. Our findings suggest that a single 3D segmentation strategy can be applied to both isotropic and anisotropic EM data. The runtime of our method scales with $O(n)$ in the size of the volume and achieves a throughput of about 2.6 seconds per megavoxel, allowing processing of very large datasets.

##### Abstract (translated by Google)
我们提出了一个深度结构的学习方法从三维电子显微镜（EM）的神经元分割，在准确性和可扩展性方面，显着提高了现有技术。我们的方法由三维U-Net分类器预测体素上的亲和图，接着迭代区域聚集。我们使用基于MALIS的新的结构化损失来训练U-Net，鼓励拓扑正确性。我们的扩展包括两部分：首先，计算损失梯度的$ O（n \ log（n））$方法，改进了最初提出的$ O（n ^ 2）$算法。其次，我们计算两个独立通道中的梯度，以避免在早期训练阶段发生虚假贡献。我们的亲和力预测是足够准确的，简单的聚集胜过更多涉及较低的预测使用较早的方法。我们在不同成像技术和动物的三个数据集（CREMI，FIB和SegEM）上显示结果，并取得比以前的结果（27％，15％和250％）有所改善。我们的研究结果表明，单一的3D分割策略可以应用于各向同性和各向异性的EM数据。我们的方法的运行时间与体积大小的$ O（n）$成比例，并且每megavoxel实现大约2.6秒的吞吐量，允许处理非常大的数据集。

##### URL
[https://arxiv.org/abs/1709.02974](https://arxiv.org/abs/1709.02974)

##### PDF
[https://arxiv.org/pdf/1709.02974](https://arxiv.org/pdf/1709.02974)

