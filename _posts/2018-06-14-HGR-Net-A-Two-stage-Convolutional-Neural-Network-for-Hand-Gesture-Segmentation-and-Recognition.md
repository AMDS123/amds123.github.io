---
layout: post
title: "HGR-Net: A Two-stage Convolutional Neural Network for Hand Gesture Segmentation and Recognition"
date: 2018-06-14 17:15:16
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification Recognition
author: Amirhossein Dadashzadeh, Alireza Tavakoli Targhi, Maryam Tahmasbi
mathjax: true
---

* content
{:toc}

##### Abstract
Robust recognition of hand gesture in real-world applications is still a challenging task due to the many aspects such as cluttered backgrounds and uncontrolled environment factors. In most existing methods hand segmentation is a primary step for hand gesture recognition, because it reduces redundant information from the image background, before passing them to the recognition stages. Therefore, in this paper we propose a two-stage deep convolutional neural network (CNN) architecture called HGR-Net, where the first stage performs accurate pixel-level semantic segmentation into hand region and the second stage identifies hand gesture style. The segmentation stage architecture is based on the combination of fully convolutional deep residual neural network and atrous spatial pyramid pooling. Although the segmentation sub-network is trained without using depth information, it is robust enough against challenging situations such as changes in the lightning and complex backgrounds. In the recognition stage a two-stream CNN is used to obtain the best classification score. We also apply an effective data augmentation technique for maximizing the generalization capability of HGR-Net. Extensive experiments on public hand gesture datasets show that our deep architecture achieves prominent performance in segmentation and recognition for static hand gestures.

##### Abstract (translated by Google)
由于混乱的背景和不受控制的环境因素等诸多方面，在实际应用中对手势的鲁棒识别仍然是一项具有挑战性的任务。在大多数现有的方法中，手划分是手势识别的主要步骤，因为它可以在将图像背景传递到识别阶段之前减少来自图像背景的冗余信息。因此，在本文中，我们提出了一种名为HGR-Net的两阶段深度卷积神经网络（CNN）体系结构，其中第一阶段对手区域执行精确的像素级语义分割，第二阶段识别手势风格。分割阶段体系结构是基于完全卷积深度残差神经网络和空间金字塔池化的结合。虽然分割子网络是在不使用深度信息的情况下进行训练的，但它足以抵御诸如闪电和复杂背景变化等具有挑战性的情况。在识别阶段，使用双流CNN来获得最佳分类分数。我们还应用有效的数据增强技术来最大化HGR-Net的泛化能力。公共手势数据集上的大量实验表明，我们的深层架构在静态手势的分割和识别方面取得了突出的性能。

##### URL
[http://arxiv.org/abs/1806.05653](http://arxiv.org/abs/1806.05653)

##### PDF
[http://arxiv.org/pdf/1806.05653](http://arxiv.org/pdf/1806.05653)

