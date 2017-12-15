---
layout: post
title: "Superpixel Convolutional Networks using Bilateral Inceptions"
date: 2016-08-08 15:31:14
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Raghudeep Gadde, Varun Jampani, Martin Kiefel, Daniel Kappler, Peter V. Gehler
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a CNN architecture for semantic image segmentation. We introduce a new 'bilateral inception' module that can be inserted in existing CNN architectures and performs bilateral filtering, at multiple feature-scales, between superpixels in an image. The feature spaces for bilateral filtering and other parameters of the module are learned end-to-end using standard backpropagation techniques. The bilateral inception module addresses two issues that arise with general CNN segmentation architectures. First, this module propagates information between (super) pixels while respecting image edges, thus using the structured information of the problem for improved results. Second, the layer recovers a full resolution segmentation result from the lower resolution solution of a CNN. In the experiments, we modify several existing CNN architectures by inserting our inception module between the last CNN (1x1 convolution) layers. Empirical results on three different datasets show reliable improvements not only in comparison to the baseline networks, but also in comparison to several dense-pixel prediction techniques such as CRFs, while being competitive in time.

##### Abstract (translated by Google)
在本文中，我们提出了一种用于语义图像分割的CNN体​​系结构。我们引入了一个新的“双边启动”模块，可以插入到现有的CNN架构中，并在多个特征尺度上对图像中的超像素进行双边过滤。使用标准反向传播技术来端对端学习模块的双边过滤和其他参数的特征空间。双边启动模块解决了一般CNN分割体系结构中出现的两个问题。首先，该模块在尊重图像边缘的同时在（超）像素之间传播信息，从而使用问题的结构化信息来改善结果。其次，该层从CNN的较低分辨率解决方案恢复全分辨率分割结果。在实验中，我们通过在最后的CNN（1x1卷积）层之间插入我们的初始模块来修改几个现有的CNN体​​系结构。对三个不同数据集的实证结果显示，不仅与基线网络相比，其可靠性有所提高，而且与一些像CRF这样的密集像素预测技术相比，在时间上具有竞争性。

##### URL
[https://arxiv.org/abs/1511.06739](https://arxiv.org/abs/1511.06739)

##### PDF
[https://arxiv.org/pdf/1511.06739](https://arxiv.org/pdf/1511.06739)

