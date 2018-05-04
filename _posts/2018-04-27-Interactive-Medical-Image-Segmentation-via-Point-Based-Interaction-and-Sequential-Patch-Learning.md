---
layout: post
title: "Interactive Medical Image Segmentation via Point-Based Interaction and Sequential Patch Learning"
date: 2018-04-27 13:03:42
categories: arXiv_CV
tags: arXiv_CV Segmentation RNN
author: Jinquan Sun, Yinghuan Shi, Yang Gao, Lei Wang, Luping Zhou, Wanqi Yang, Dinggang Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Due to low tissue contrast, irregular object appearance, and unpredictable location variation, segmenting the objects from different medical imaging modalities (e.g., CT, MR) is considered as an important yet challenging task. In this paper, we present a novel method for interactive medical image segmentation with the following merits. (1) Our design is fundamentally different from previous pure patch-based and image-based segmentation methods. We observe that during delineation, the physician repeatedly check the inside-outside intensity changing to determine the boundary, which indicates that comparison in an inside-outside manner is extremely important. Thus, we innovatively model our segmentation task as learning the representation of the bi-directional sequential patches, starting from (or ending in) the given central point of the object. This can be realized by our proposed ConvRNN network embedded with a gated memory propagation unit. (2) Unlike previous interactive methods (requiring bounding box or seed points), we only ask the physician to merely click on the rough central point of the object before segmentation, which could simultaneously enhance the performance and reduce the segmentation time. (3) We utilize our method in a multi-level framework for better performance. We systematically evaluate our method in three different segmentation tasks including CT kidney tumor, MR prostate, and PROMISE12 challenge, showing promising results compared with state-of-the-art methods. The code is available here: \href{this https URL}{Sequential-patch-based-segmentation}.

##### Abstract (translated by Google)
由于组织对比度低，不规则的物体外观和不可预知的位置变化，将来自不同医学成像模态（例如，CT，MR）的对象分割被认为是重要但具有挑战性的任务。在本文中，我们提出了一种新颖的交互式医学图像分割方法，具有以下优点。 （1）我们的设计与以前纯粹的基于补丁和基于图像的分割方法有着根本的不同。我们观察到，在描绘过程中，医生反复检查内侧 - 外侧强度变化以确定边界，这表明以内外方式进行比较是非常重要的。因此，我们创造性地将我们的分割任务建模为从对象的给定中心点开始（或结束）开始学习双向连续色块的表示。这可以通过我们提出的嵌入了门控存储器传播单元的ConvRNN网络来实现。 （2）与以前的交互式方法（需要边界框或种子点）不同，我们只要求医师在分割之前点击对象的粗糙中心点，这可以同时提高性能并缩短分割时间。 （3）我们在多层框架中使用我们的方法以获得更好的性能。我们系统地评估了我们的方法在三种不同的分割任务中，包括CT肾肿瘤，MR前列腺和PROMISE12挑战，与最先进的方法相比显示出有前途的结果。代码可以在这里找到：\ href {this https URL} {Sequential-patch-based-segmentation}。

##### URL
[https://arxiv.org/abs/1804.10481](https://arxiv.org/abs/1804.10481)

##### PDF
[https://arxiv.org/pdf/1804.10481](https://arxiv.org/pdf/1804.10481)

