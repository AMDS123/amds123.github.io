---
layout: post
title: "Weakly-supervised DCNN for RGB-D Object Recognition in Real-World Applications Which Lack Large-scale Annotated Training Data"
date: 2017-03-19 00:29:35
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised CNN Classification Detection Recognition
author: Li Sun, Cheng Zhao, Rustam Stolkin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of RGBD object recognition in real-world applications, where large amounts of annotated training data are typically unavailable. To overcome this problem, we propose a novel, weakly-supervised learning architecture (DCNN-GPC) which combines parametric models (a pair of Deep Convolutional Neural Networks (DCNN) for RGB and D modalities) with non-parametric models (Gaussian Process Classification). Our system is initially trained using a small amount of labeled data, and then automatically prop- agates labels to large-scale unlabeled data. We first run 3D- based objectness detection on RGBD videos to acquire many unlabeled object proposals, and then employ DCNN-GPC to label them. As a result, our multi-modal DCNN can be trained end-to-end using only a small amount of human annotation. Finally, our 3D-based objectness detection and multi-modal DCNN are integrated into a real-time detection and recognition pipeline. In our approach, bounding-box annotations are not required and boundary-aware detection is achieved. We also propose a novel way to pretrain a DCNN for the depth modality, by training on virtual depth images projected from CAD models. We pretrain our multi-modal DCNN on public 3D datasets, achieving performance comparable to state-of-the-art methods on Washington RGBS Dataset. We then finetune the network by further training on a small amount of annotated data from our novel dataset of industrial objects (nuclear waste simulants). Our weakly supervised approach has demonstrated to be highly effective in solving a novel RGBD object recognition application which lacks of human annotations.

##### Abstract (translated by Google)
本文针对实际应用中的RGBD对象识别问题，其中大量的注释训练数据通常不可用。为了克服这个问题，我们提出了一种新的弱监督学习架构（DCNN-GPC），它将参数模型（用于RGB和D模态的一对深度卷积神经网络（DCNN））与非参数模型（高斯过程分类）。我们的系统最初使用少量的标记数据进行训练，然后自动将标签推送到大规模未标记的数据。我们首先在RGBD视频上运行基于3D的对象检测来获取许多未标记的对象提议，然后使用DCNN-GPC来标记它们。因此，我们的多模式DCNN可以使用少量的人工注释进行端到端的训练。最后，我们基于3D的物体检测和多模式DCNN被集成到实时检测和识别流水线中。在我们的方法中，边界框注解不是必需的，并且边界感知检测被实现。我们还提出了一种通过训练CAD模型投影的虚拟深度图像来预训深度模态的DCNN的新方法。我们在公共三维数据集上预编译了我们的多模式DCNN，实现了与华盛顿RGBS数据集上最先进的方法相媲美的性能。然后，我们通过对来自我们的新型工业对象数据集（核废料模拟物）的少量注释数据进行进一步培训，对网络进行微调。我们的弱监督方法已被证明是非常有效的解决缺乏人类注释的新颖的RGBD对象识别应用程序。

##### URL
[https://arxiv.org/abs/1703.06370](https://arxiv.org/abs/1703.06370)

##### PDF
[https://arxiv.org/pdf/1703.06370](https://arxiv.org/pdf/1703.06370)

