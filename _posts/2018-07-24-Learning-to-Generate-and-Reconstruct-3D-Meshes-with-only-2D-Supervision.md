---
layout: post
title: "Learning to Generate and Reconstruct 3D Meshes with only 2D Supervision"
date: 2018-07-24 17:54:51
categories: arXiv_CV
tags: arXiv_CV Attention Quantitative
author: Paul Henderson, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
We present a unified framework tackling two problems: class-specific 3D reconstruction from a single image, and generation of new 3D shape samples. These tasks have received considerable attention recently; however, existing approaches rely on 3D supervision, annotation of 2D images with keypoints or poses, and/or training with multiple views of each object instance. Our framework is very general: it can be trained in similar settings to these existing approaches, while also supporting weaker supervision scenarios. Importantly, it can be trained purely from 2D images, without ground-truth pose annotations, and with a single view per instance. We employ meshes as an output representation, instead of voxels used in most prior work. This allows us to exploit shading information during training, which previous 2D-supervised methods cannot. Thus, our method can learn to generate and reconstruct concave object classes. We evaluate our approach on synthetic data in various settings, showing that (i) it learns to disentangle shape from pose; (ii) using shading in the loss improves performance; (iii) our model is comparable or superior to state-of-the-art voxel-based approaches on quantitative metrics, while producing results that are visually more pleasing; (iv) it still performs well when given supervision weaker than in prior works.

##### Abstract (translated by Google)
我们提出了一个统一的框架来解决两个问题：从单个图像中进行类特定的3D重建，以及生成新的3D形状样本。这些任务最近受到了相当多的关注;然而，现有方法依赖于3D监督，具有关键点或姿势的2D图像的注释，和/或具有每个对象实例的多个视图的训练。我们的框架非常通用：它可以在与现有方法类似的设置中进行培训，同时还支持较弱的监督方案。重要的是，它可以纯粹来自2D图像，没有地面真实姿势注释，每个实例只有一个视图。我们使用网格作为输出表示，而不是大多数先前工作中使用的体素。这允许我们在训练期间利用着色信息，而以前的2D监督方法不能。因此，我们的方法可以学习生成和重建凹对象类。我们在各种环境中评估我们对合成数据的处理方法，表明它（i）它学会了从姿势中解开形状; （ii）在损失中使用阴影改善表现; （iii）我们的模型与量化指标的最先进的基于体素的方法相当或更优，同时产生视觉上更令人满意的结果; （iv）如果监管比以前的工程弱，它仍然表现良好。

##### URL
[https://arxiv.org/abs/1807.09259](https://arxiv.org/abs/1807.09259)

##### PDF
[https://arxiv.org/pdf/1807.09259](https://arxiv.org/pdf/1807.09259)

