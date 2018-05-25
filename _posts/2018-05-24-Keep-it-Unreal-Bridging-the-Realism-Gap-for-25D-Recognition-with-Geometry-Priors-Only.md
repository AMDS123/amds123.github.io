---
layout: post
title: "Keep it Unreal: Bridging the Realism Gap for 2.5D Recognition with Geometry Priors Only"
date: 2018-05-24 16:08:07
categories: arXiv_CV
tags: arXiv_CV Adversarial Recognition
author: Sergey Zakharov, Benjamin Planche, Ziyan Wu, Andreas Hutter, Harald Kosch, Slobodan Ilic
mathjax: true
---

* content
{:toc}

##### Abstract
With the increasing availability of large databases of 3D CAD models, depth-based recognition methods can be trained on an uncountable number of synthetically rendered images. However, discrepancies with the real data acquired from various depth sensors still noticeably impede progress. Previous works adopted unsupervised approaches to generate more realistic depth data, but they all require real scans for training, even if unlabeled. This still represents a strong requirement, especially when considering real-life/industrial settings where real training images are hard or impossible to acquire, but texture-less 3D models are available. We thus propose a novel approach leveraging only CAD models to bridge the realism gap. Purely trained on synthetic data, playing against an extensive augmentation pipeline in an unsupervised manner, our generative adversarial network learns to effectively segment depth images and recover the clean synthetic-looking depth information even from partial occlusions. As our solution is not only fully decoupled from the real domains but also from the task-specific analytics, the pre-processed scans can be handed to any kind and number of recognition methods also trained on synthetic data. Through various experiments, we demonstrate how this simplifies their training and consistently enhances their performance, with results on par with the same methods trained on real data, and better than usual approaches doing the reverse mapping.

##### Abstract (translated by Google)
随着3D CAD模型的大型数据库日益增加的可用性，基于深度的识别方法可以通过不可数量的合成渲染图像进行训练。然而，从各种深度传感器获得的真实数据的差异仍然明显阻碍了进展。以前的作品采用无监督方法来生成更真实的深度数据，但它们都需要真实的扫描来进行训练，即使没有标记。这仍然是一个强大的要求，特别是在考虑实际培训图像难以或不可能获得的真实/工业环境时，但无纹理的3D模型可用。因此，我们提出了一种仅利用CAD模型弥合现实差距的新颖方法。纯粹的合成数据训练，以无监督的方式对抗广泛的增强管道，我们的生成对抗网络学习有效分割深度图像，并恢复清晰的合成深度信息，即使是部分遮挡。由于我们的解决方案不仅与真实领域完全脱钩，而且还与特定任务分析有关，因此可以将预处理扫描交给任何种类和数量的合成数据识别方法。通过各种实验，我们演示了如何简化他们的训练并不断提高他们的表现，结果与在真实数据上训练相同的方法一致，并且比通常的方法进行反向映射更好。

##### URL
[http://arxiv.org/abs/1804.09113](http://arxiv.org/abs/1804.09113)

##### PDF
[http://arxiv.org/pdf/1804.09113](http://arxiv.org/pdf/1804.09113)

