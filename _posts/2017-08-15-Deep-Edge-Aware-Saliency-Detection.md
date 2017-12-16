---
layout: post
title: "Deep Edge-Aware Saliency Detection"
date: 2017-08-15 00:35:55
categories: arXiv_CV
tags: arXiv_CV Salient CNN Deep_Learning Detection
author: Jing Zhang, Yuchao Dai, Fatih Porikli, Mingyi He
mathjax: true
---

* content
{:toc}

##### Abstract
There has been profound progress in visual saliency thanks to the deep learning architectures, however, there still exist three major challenges that hinder the detection performance for scenes with complex compositions, multiple salient objects, and salient objects of diverse scales. In particular, output maps of the existing methods remain low in spatial resolution causing blurred edges due to the stride and pooling operations, networks often neglect descriptive statistical and handcrafted priors that have potential to complement saliency detection results, and deep features at different layers stay mainly desolate waiting to be effectively fused to handle multi-scale salient objects. In this paper, we tackle these issues by a new fully convolutional neural network that jointly learns salient edges and saliency labels in an end-to-end fashion. Our framework first employs convolutional layers that reformulate the detection task as a dense labeling problem, then integrates handcrafted saliency features in a hierarchical manner into lower and higher levels of the deep network to leverage available information for multi-scale response, and finally refines the saliency map through dilated convolutions by imposing context. In this way, the salient edge priors are efficiently incorporated and the output resolution is significantly improved while keeping the memory requirements low, leading to cleaner and sharper object boundaries. Extensive experimental analyses on ten benchmarks demonstrate that our framework achieves consistently superior performance and attains robustness for complex scenes in comparison to the very recent state-of-the-art approaches.

##### Abstract (translated by Google)
视觉显着性得到了深刻的发展，得益于深厚的学习架构，但是对于复杂构图，多显着对象，多尺度显着对象的场景，仍然存在着三大难题。特别是，现有方法的输出图在空间分辨率上保持较低，由于步幅和池操作而导致边缘模糊，网络往往忽略描述性统计和手工制作的具有补充显着性检测结果的潜在前景，并且不同层的深度特征主要等待有效融合处理多尺度显着物体的荒凉。在本文中，我们通过一个新的完全卷积神经网络来解决这些问题，该网络以端到端的方式共同学习显着边缘和显着性标签。我们的框架首先使用卷积层，将检测任务重新表达为一个稠密标签问题，然后将层次化的手工显着特征集成到深层网络的较低和较高层次，以利用可用信息进行多尺度响应，最后提炼显着性通过施加上下文来通过扩张的卷积来映射。通过这种方式，突出的边缘先验被有效地结合在一起，并且输出分辨率得到显着改善，同时保持低存储器要求，导致更清晰和更清晰的对象边界。对十个基准进行广泛的实验分析表明，与最新的最先进方法相比，我们的框架可以获得始终如一的卓越性能，并且可以为复杂的场景提供稳健性。

##### URL
[https://arxiv.org/abs/1708.04366](https://arxiv.org/abs/1708.04366)

##### PDF
[https://arxiv.org/pdf/1708.04366](https://arxiv.org/pdf/1708.04366)

