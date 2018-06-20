---
layout: post
title: "Task Driven Generative Modeling for Unsupervised Domain Adaptation: Application to X-ray Image Segmentation"
date: 2018-06-11 22:39:35
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN Style_Transfer
author: Yue Zhang, Shun Miao, Tommaso Mansi, Rui Liao
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic parsing of anatomical objects in X-ray images is critical to many clinical applications in particular towards image-guided invention and workflow automation. Existing deep network models require a large amount of labeled data. However, obtaining accurate pixel-wise labeling in X-ray images relies heavily on skilled clinicians due to the large overlaps of anatomy and the complex texture patterns. On the other hand, organs in 3D CT scans preserve clearer structures as well as sharper boundaries and thus can be easily delineated. In this paper, we propose a novel model framework for learning automatic X-ray image parsing from labeled CT scans. Specifically, a Dense Image-to-Image network (DI2I) for multi-organ segmentation is first trained on X-ray like Digitally Reconstructed Radiographs (DRRs) rendered from 3D CT volumes. Then we introduce a Task Driven Generative Adversarial Network (TD-GAN) architecture to achieve simultaneous style transfer and parsing for unseen real X-ray images. TD-GAN consists of a modified cycle-GAN substructure for pixel-to-pixel translation between DRRs and X-ray images and an added module leveraging the pre-trained DI2I to enforce segmentation consistency. The TD-GAN framework is general and can be easily adapted to other learning tasks. In the numerical experiments, we validate the proposed model on 815 DRRs and 153 topograms. While the vanilla DI2I without any adaptation fails completely on segmenting the topograms, the proposed model does not require any topogram labels and is able to provide a promising average dice of 85% which achieves the same level accuracy of supervised training (88%).

##### Abstract (translated by Google)
X射线图像中解剖对象的自动解析对于许多临床应用，特别是对于图像引导的发明和工作流程自动化而言至关重要。现有的深层网络模型需要大量的标记数据。然而，由于解剖结构的重叠和复杂的纹理图案，在X射线图像中获得准确的像素方式标记严重依赖于熟练的临床医师。另一方面，三维CT扫描中的器官可以保留更清晰的结构以及更清晰的边界，因此可以很容易地进行描述。在本文中，我们提出了一种新的模型框架，用于从标记的CT扫描中学习自动X射线图像解析。具体来说，多器官分割的密集图像到图像网络（DI2I）首先在X射线上训练，如3D CT体积渲染的数字重建射线照片（DRR）。然后我们介绍一个任务驱动的生成敌对网络（TD-GAN）架构，以实现同步样式传输和解析看不见的真正的X射线图像。 TD-GAN由修改后的循环GAN子结构组成，用于DRR和X射线图像之间的像素到像素转换，以及一个利用预先训练的DI2I增强分段一致性的附加模块。 TD-GAN框架是一般的，可以很容易地适应其他学习任务。在数值实验中，我们在815个DRR和153个地形图上验证了所提出的模型。虽然没有任何适应的香草DI2I完全不能在分割地形图时失败，但所提出的模型不需要任何地形图标签，并且能够提供85％的有希望的平均骰子，其实现与监督训练（88％）相同的准确度。

##### URL
[http://arxiv.org/abs/1806.07201](http://arxiv.org/abs/1806.07201)

##### PDF
[http://arxiv.org/pdf/1806.07201](http://arxiv.org/pdf/1806.07201)

