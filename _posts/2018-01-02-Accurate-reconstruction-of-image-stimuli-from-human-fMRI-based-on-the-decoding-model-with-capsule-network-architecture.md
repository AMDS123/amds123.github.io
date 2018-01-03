---
layout: post
title: "Accurate reconstruction of image stimuli from human fMRI based on the decoding model with capsule network architecture"
date: 2018-01-02 10:39:05
categories: arXiv_AI
tags: arXiv_AI GAN
author: Kai Qiao, Chi Zhang, Linyuan Wang, Bin Yan, Jian Chen, Lei Zeng, Li Tong
mathjax: true
---

* content
{:toc}

##### Abstract
In neuroscience, all kinds of computation models were designed to answer the open question of how sensory stimuli are encoded by neurons and conversely, how sensory stimuli can be decoded from neuronal activities. Especially, functional Magnetic Resonance Imaging (fMRI) studies have made many great achievements with the rapid development of the deep network computation. However, comparing with the goal of decoding orientation, position and object category from activities in visual cortex, accurate reconstruction of image stimuli from human fMRI is a still challenging work. In this paper, the capsule network (CapsNet) architecture based visual reconstruction (CNAVR) method is developed to reconstruct image stimuli. The capsule means containing a group of neurons to perform the better organization of feature structure and representation, inspired by the structure of cortical mini column including several hundred neurons in primates. The high-level capsule features in the CapsNet includes diverse features of image stimuli such as semantic class, orientation, location and so on. We used these features to bridge between human fMRI and image stimuli. We firstly employed the CapsNet to train the nonlinear mapping from image stimuli to high-level capsule features, and from high-level capsule features to image stimuli again in an end-to-end manner. After estimating the serviceability of each voxel by encoding performance to accomplish the selecting of voxels, we secondly trained the nonlinear mapping from dimension-decreasing fMRI data to high-level capsule features. Finally, we can predict the high-level capsule features with fMRI data, and reconstruct image stimuli with the CapsNet. We evaluated the proposed CNAVR method on the dataset of handwritten digital images, and exceeded about 10% than the accuracy of all existing state-of-the-art methods on the structural similarity index (SSIM).

##### Abstract (translated by Google)
在神经科学中，各种计算模型被设计来回答关于感觉刺激如何被神经元编码的公开问题，并且相反，如何从神经元活动解码感官刺激。特别是随着深度网络计算的快速发展，功能磁共振成像（fMRI）研究取得了许多重大成果。然而，与从视觉皮层中的活动解码方向，位置和对象类别的目标相比，从人类功能磁共振成像的图像刺激准确重建是一个具有挑战性的工作。在本文中，基于CapsNet架构的视觉重建（CNAVR）方法被开发来重建图像刺激。胶囊手段包含一组神经元，以执行更好的特征结构和表示的组织，灵感来自皮质迷你柱的结构，包括在灵长类动物中的数百个神经元。 CapsNet中的高级胶囊功能包括图像刺激的各种特征，如语义类别，方向，位置等。我们使用这些功能来桥接人类功能磁共振成像和图像刺激。我们首先利用CapsNet对从图像刺激到高级胶囊特征，从高级胶囊特征到图像刺激以端到端的方式再次进行非线性映射。通过编码性能估计每个体素的适用性来完成体素的选择，然后我们对从维度递减的fMRI数据到高级囊体特征进行非线性映射。最后，我们可以用fMRI数据预测高级胶囊特征，并用CapsNet重建图像刺激。我们对手写数字图像数据集上的CNAVR方法进行了评估，并且超过了现有结构相似性指数（SSIM）方法的准确度10％。

##### URL
[http://arxiv.org/abs/1801.00602](http://arxiv.org/abs/1801.00602)

##### PDF
[http://arxiv.org/pdf/1801.00602](http://arxiv.org/pdf/1801.00602)

